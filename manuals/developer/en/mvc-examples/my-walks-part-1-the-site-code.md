<!-- Filename: J4.x:My_Walks_Part_1:_The_Site_code / Display title: My Walks Part 1: The Site code -->

## J4 Component Tutorial: Mywalks Part 1 - The Site Code

## Background

As an experienced Joomla! 3.x developer I needed to learn about Joomla!
4.x and found it really difficult to get started. Although
*experienced*, my actual knowledge of Joomla internals is limited. I
started at the 1.6 stage and many new features passed me by. So this
tutorial may be a case of the blind leading the blind. It took me about
10 days to get something to work by reading the code, stepping through
with the debugger and reading the limited amount of J4 documentation
available. The tutorial started with Joomla 4.x at the Alpha 10 stage
and has been updated for the Beat 4 stage. Even so, it may be out of
date all too soon.

The tutorial text was prepared as an article written with Joomla 4.0
Alpha 10, converted to MediaWiki and then Github Markdown formats with
Pandoc. And finally finished here.

## Component Purpose and Data Schema

For the last few years I have been going out for walks with my family,
sometimes once a week, sometimes twice, but only in good weather. I kept
a list - there are 50 or so walks and we have done each of them several
times. This was all part of trying to keep fit in old age. So for
self-teaching purposes I decided to develop a Joomla! component that has
two Site views: the list of walks and the details on individual walks.
To keep it simple I don't want any frills: no site side data entry, no
scores, hit counters, categories or other Joomla goodies. For test
purposes sample data was entered directly into the database with
phpMyAdmin. The component needs two database tables: the list of walks
and the list of individual visits. I decided to name the component
com_mywalks and the tables \#\_\_mywalks and \#\_\_mywalks_dates.

All of the code for this tutorial component can be obtained from here:

- <a
  href="https://github.com/ceford/j4xdemos-com-mywalks/blob/master/com_mywalks.zip"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">https://github.com/ceford/j4xdemos-com-mywalks/blob/master/com_mywalks.zip</a>

You might find it helpful to install the component or unpack it without
installation and look at the working files.

### The mywalks table

At the time of writing the install script in the admin/sql folder is not
being called. So, if you are installing a working version of the code
for this tutorial, run the following scripts manually **first**. Is this
a bug in Joomla or the Tutorial code? The uninstall script is working -
the tables successfully disappear.

The sql files in the working example zip file include the sample data.

        CREATE TABLE IF NOT EXISTS `#__mywalks` (
      `id` int(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,
      `title` varchar(64) NOT NULL,
      `description` text NOT NULL,
      `distance` decimal(10,0) NOT NULL,
      `toilets` tinyint(1) NOT NULL DEFAULT '0',
      `cafe` tinyint(1) NOT NULL DEFAULT '0',
      `hills` int(11) NOT NULL DEFAULT '0',
      `bogs` int(11) NOT NULL DEFAULT '0',
      `picture` varchar(128) DEFAULT NULL,
      `width` int(11) DEFAULT NULL,
      `height` int(11) DEFAULT NULL,
      `alt` varchar(64) DEFAULT NULL,
      `state` TINYINT NOT NULL DEFAULT '1'
    ) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 DEFAULT COLLATE utf8mb4_unicode_ci;

### The mywalks_dates table

        CREATE TABLE IF NOT EXISTS `#__mywalk_dates` (
      `id` int(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,
      `walk_id` int(11) NOT NULL,
      `date` date NOT NULL,
      `weather` varchar(256) DEFAULT NULL,
      `state` TINYINT NOT NULL DEFAULT '1',
      KEY `idx_walk` (`walk_id`)
    ) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 DEFAULT COLLATE utf8mb4_unicode_ci;

If this were a real component it would be obvious that the schema design
has a long way to go! Look at the WalkHighlands site to see how far.
However, it is enough for tutorial purposes.

## The Manifest file and component folder structure

The component zip file used for installation should contain the manifest
file named mywalks.xml (notice no com\_) along with admin and site
folders, like so:

    com_mywalks.zip
         admin
         site
         mywalks.xml

On installation the manifest file is copied to the
site_root/administrator/components/com_mywalks folder where it is needed
for uninstall purposes. It should not be there in the source code!
Entries are also made in site_root/administrator/cache/autoload_psr4.php
\[**New in Joomla 4**\].

### The manifest file

Note that the method is set to **upgrade** so the component can be
installed repeatedly, for example if the code is updated. However, the
sql statements will not be executed a second time. If the install sql
statements are not executed for any reason, try executing them manually
by copying them from the source code into phpMyAdmin.


        com_mywalks
        
        August 2019
        Clifford E Ford
        cliff@ford.myzen.co.uk
        http://www.fford.me.uk/
        Copyright (C) 2019 Clifford E Ford, All rights reserved.
        GNU/GPL Version 2 or later - http://www.gnu.org/licenses/gpl-2.0.html
        
        0.2.0
        
        COM_MYWALKS_XML_DESCRIPTION
        J4xdemos\Component\Mywalks

         
            
                sql/install.mysql.sql
            
        
         
            
                sql/uninstall.mysql.sql
            
        

        
        

        
            src
            tmpl
        
        
        
            language/en-GB/com_mywalks.ini
        
        
        
            
                access.xml
                config.xml
                forms
                services
                sql
                src
                tmpl
            
            
                language/en-GB/com_mywalks.ini
                language/en-GB/com_mywalks.sys.ini
            
            com_mywalks
        

### The Namespace

Notice the **namespace** tag in the manifest file. The first item should
be the Company name. I don't have one so I have used J4xdemos. The
namespace is used in the extension to distinguish its code from code in
other extensions that may have identical class names. The namespace is
used to register a service provider - see below.

The second item is the type of extension: Component, Module, Plugin or
Template. The third item is the extension name without preceding com\_,
mod\_, etc., Mywalks in this case.

The namespace attribute, path="src", indicates that all of the files
containing namespaced code will be found in the src directory.

## Language files

In case you are not familiar with Joomla extensions, the source site
language folder contains one file: en-GB.com_mywalks.ini, which contains
the translated values of fixed strings, used to allow translation from
English into other languages. The folder structure is simple:

    site                               - the folder containing the site files       
         language                      - the folder containing the site language translation file
              en-GB                    - the folder containing English translations
                   com_mywalks.ini     - the file of translated keys

And the com_mywalks.ini contains this:

    COM_MYWALKS_LIST_DESCRIPTION="Description"
    COM_MYWALKS_LIST_DISTANCE="Distance in Km"
    COM_MYWALKS_LIST_LAST_VISIT="Last Visit"
    COM_MYWALKS_LIST_NVISITS="nVisits"
    COM_MYWALKS_LIST_PAGE_HEADING="List of Walks"
    COM_MYWALKS_LIST_TABLE_CAPTION="List of Walks"
    COM_MYWALKS_LIST_TITLE="Title"
    COM_MYWALKS_ERROR_WALK_NOT_FOUND="Walk not found!"

    COM_MYWALKS_WALK_DATE="Visit date"
    COM_MYWALKS_WALK_REPORTS="Walk Reports"
    COM_MYWALKS_WALK_WEATHER="Weather Report"

For each line, the first part is a **key** and the second part is its
**value**, the English translation. Any fixed text in the component site
interface should be in this file. For example, the walks list column
headings should be keys in the source code and translated here. Note
also that the primary language of Joomla is British English. Other
languages need separate translation files. By convention, the keys
should be sorted into alphabet order!

The admin language files: Todo!

## The Site Files

You may notice that some of the Joomla! 4.x folder and file names begin
with Upper Case letters and others begin with Lower case letters. J4
also has a different structure from J3. In short, files with Upper Case
leading character names are name-spaced and those that are not are not.

Also, be aware that the code required to display site views also
includes some functions from the admin code, covered below.

### The tmpl files

The tmpl files contain the code that displays the page views. They ought
to be the easiest to explain and to understand. The tmpl file structure
in the source code looks like this:

    site
         tmpl
              mywalk
                  default.php
              mywalks
                  default-items.php
                  default.php
                  default.xml

#### The single walk view - tmpl/mywalk/default.php:


        item->title; ?>


    item->description; ?>!




      
      
      
        
            

reports as \$id =\> \$report) : ?\>

date; ?\>

weather; ?\>

For newcomers to Joomla: each php file starts with a DocBlock used in
automated documentation; in namespaced files the next statement is the
namspace, not used in tmpl files; the first executable statement is
always defined('\_JEXEC') or die; which ensures the file has been loaded
by Joomla and not called directly through a web url.

The remaining lines output the walk title, description and list of
visits extracted from the database. The use Joomla\CMS\Language\Text
statement defines the location of the class that converts string keys to
string values. The class is loaded when it is first needed, in this case
via the Text::\_() function call. The //use Joomla\CMS\HTML\HTMLHelper;
statement is commented out because this file does not use any one of a
number of HTML embelishments. Look at the file to see what:
site_root/libraries/src/HTML/HTMLHelper.php.

#### The walks list view - tmpl/mywalks/default.php



        loadTemplate('items');
        ?>

Note that the use statements are defining the locations of additional
php files using their namespaces. Joomla\CMS\HTML\HTMLHelper is for
files used in page display, for example the Javascript files needed for
table sorting. Joomla\CMS\Language\Text is for the file used to convert
fixed string keys to their English values.
Joomla\CMS\Layout\LayoutHelper was copied here when copy and paste from
elsewhere was being used during development. It is left in but commented
out to illustrate that there my be lots of instances of accidental code
that does nothing but use server resources.

This file outputs a page heading and then loads another file,
default-items.php, which displays the list of walks.
\$this-\>loadTemplate('items') uses library code to locate the
default_items.php file in the same directory in which it was called.

#### The list items - tmpl/mywalks/default_items.php

Notice the creation of a slug by converting the title to lower case
alpha-numeric only with spaces replaced by minus signs.


      
      
      
        
            

items as \$id =\> \$item) : \$slug = preg_replace('/\[^a-z\d\]/i', '-',
\$item-\>title); \$slug = strtolower(str_replace(' ', '-', \$slug)); ?\>

title; ?\>

description; ?\>

distance; ?\>

last_visit //\$item-\>lastvisit; ?\>

nvisits; ?\>

Also notice the static call to Route which is used to create a url for a
link to an individual walk description. And notice its associated use
call that tells the loader where to find the required class and
function. More on routing later.

This is an extract from the getWalkRoute function:

        public static function getWalkRoute($id, $slug, $language = 0, $layout = null)
        {
            // Create the link
            $link = 'index.php?option=com_mywalks&view=mywalk&id=' . $id . '&slug=' . $slug;

            if ($language && $language !== '*' && Multilanguage::isEnabled())
            {
                $link .= '&lang=' . $language;
            }

            if ($layout)
            {
                $link .= '&layout=' . $layout;
            }

            return $link;
        }

### Getting the data - The HtmlView files

The tmpl files are supposed to deal solely with the composition of html.
Any data needed to create the html, such as the list of walks, should be
stored in variables in the HtmlView files where they are made available
in the \$this object.

#### The HtmlView.php file for the single walk view

    get('State');
            $item       = $this->get('Item');
            $reports    = $this->get('Reports');

            $this->state       = &$state;
            $this->item        = &$item;
            $this->reports     = &$reports;

            // Check for errors.
            if (count($errors = $this->get('Errors')))
            {
                throw new GenericDataException(implode("\n", $errors), 500);
            }

            return parent::display($tpl);
        }
    }

The display function is very simple. It fetches state, single walk and
walk report data for that walk from the model. If any of the data
retrieval steps return an error it throws an exception, usually
resulting in some sort of error message page. Otherwise control is
passed via Joomla to the tmpl file to create the html output. HtmlView
files can become quite complex - have a look at the content component
article HtmlView for for an example.

#### The HtmlView file for the list of walks

    getParams();

            // Get some data from the models
            $state      = $this->get('State');
            $items      = $this->get('Items');
            $pagination = $this->get('Pagination');

            // Flag indicates to not add limitstart=0 to URL
            $pagination->hideEmptyLimitstart = true;

            // Check for errors.
            if (count($errors = $this->get('Errors')))
            {
                throw new GenericDataException(implode("\n", $errors), 500);
            }

            $this->state      = &$state;
            $this->items      = &$items;
            $this->params     = &$params;
            $this->pagination = &$pagination;

            return parent::display($tpl);
        }
    }

Ready for the models?

### Getting the data - The Model files

For the single walk model we need a model file that implements
populateState, getItem and getVisits. For the list of walks we need
populateState, getListQuery, getItems and a few more to sort on columns
and paginate long lists, neither of which are implemented in this
tutorial.

#### Model file: MywalkModel

    input->getInt('id');
            $this->setState('mywalk.id', $pk);

            $offset = $app->input->getUInt('limitstart');
            $this->setState('list.offset', $offset);

            // Load the parameters.
            $params = $app->getParams();
            $this->setState('params', $params);
        }

        /**
         * Method to get walk data.
         *
         * @param   integer  $pk  The id of the walk.
         *
         * @return  object|boolean  Menu item data object on success, boolean false
         */
        public function getItem($pk = null)
        {
            $pk = (!empty($pk)) ? $pk : (int) $this->getState('mywalk.id');

                try
                {
                    $db = $this->getDbo();
                    $query = $db->getQuery(true)
                        ->select(
                            $this->getState(
                                'item.select', 'a.*'
                            )
                        );
                    $query->from('#__mywalks AS a')
                        ->where('a.id = ' . (int) $pk);

                    $db->setQuery($query);

                    $data = $db->loadObject();

                    if (empty($data))
                    {
                        throw new \Exception(Text::_('COM_MYWALKS_ERROR_WALK_NOT_FOUND'), 404);
                    }
                }
                catch (\Exception $e)
                {
                    if ($e->getCode() == 404)
                    {
                        // Need to go through the error handler to allow Redirect to work.
                        throw new \Exception($e->getMessage(), 404);
                    }
                    else
                    {
                        $this->setError($e);
                        $this->_item[$pk] = false;
                    }
                }

            return $data;
        }
        /**
         * Method to get walk visit data.
         *
         * @param   integer  $pk  The id of the walk.
         *
         * @return  object|boolean  Menu item data object on success, boolean false
         */
        public function getReports($pk = null)
        {
            $pk = (!empty($pk)) ? $pk : (int) $this->getState('mywalk.id');

            try
            {
                $db = $this->getDbo();
                $query = $db->getQuery(true)
                ->select('b.*');
                $query->from('#__mywalk_dates AS b')
                ->where('b.walk_id = ' . (int) $pk);
                $query->order('`date` DESC');

                $db->setQuery($query);

                $data = $db->loadObjectList();

                // It is OK to have a walk without visit data - handle it the view.
            }
            catch (\Exception $e)
            {
                if ($e->getCode() == 404)
                {
                    // Need to go through the error handler to allow Redirect to work.
                    throw new \Exception($e->getMessage(), 404);
                }
                else
                {
                    $this->setError($e);
                    $this->_item[$pk] = false;
                }
            }

            return $data;
        }
    }

#### Model file: MywalksModel

     input->get('limit', $app->get('list_limit', 0), 'uint');
            $this->setState('list.limit', $value);

            $value = $app->input->get('limitstart', 0, 'uint');
            $this->setState('list.start', $value);

            $orderCol = $app->input->get('filter_order', 'a.id');

            if (!in_array($orderCol, $this->filter_fields))
            {
                $orderCol = 'a.id';
            }

            $this->setState('list.ordering', $orderCol);

            $listOrder = $app->input->get('filter_order_Dir', 'ASC');

            if (!in_array(strtoupper($listOrder), array('ASC', 'DESC', '')))
            {
                $listOrder = 'ASC';
            }

            $this->setState('list.direction', $listOrder);

            $params = $app->getParams();
            $this->setState('params', $params);

            //$this->setState('layout', $app->input->getString('layout'));
        }

        /**
         * Method to get a store id based on model configuration state.
         *
         * This is necessary because the model is used by the component and
         * different modules that might need different sets of data or different
         * ordering requirements.
         *
         * @param   string  $id  A prefix for the store id.
         *
         * @return  string  A store id.
         *
         * @since   1.6
         */
        protected function getStoreId($id = '')
        {
            // Compile the store id.

            return parent::getStoreId($id);
        }

        /**
         * Get the master query for retrieving a list of walks subject to the model state.
         *
         * @return  \JDatabaseQuery
         *
         * @since   1.6
         */
        protected function getListQuery()
        {
            // Get the current user for authorisation checks
            $user = Factory::getUser();

            // Create a new query object.
            $db    = $this->getDbo();
            $query = $db->getQuery(true);

            // Select the required fields from the table.
            $query->select(
                $this->getState(
                    'list.select',
                    'a.*,
                    (SELECT MAX(`date`) from #__mywalk_dates WHERE walk_id = a.id) AS last_visit,
                    (SELECT count(`date`) from #__mywalk_dates WHERE walk_id = a.id) AS nvisits
                    ')
            );
            $query->from('#__mywalks AS a');

            $params      = $this->getState('params');

            // Add the list ordering clause.
            $query->order($this->getState('list.ordering', 'a.id') . ' ' . $this->getState('list.direction', 'ASC'));

            return $query;
        }

        /**
         * Method to get a list of walks.
         *
         * Overridden to inject convert the attribs field into a \JParameter object.
         *
         * @return  mixed  An array of objects on success, false on failure.
         *
         * @since   1.6
         */
        public function getItems()
        {
            $items  = parent::getItems();
            return $items;
        }

        /**
         * Method to get the starting number of items for the data set.
         *
         * @return  integer  The starting number of items available in the data set.
         *
         * @since   3.0.1
         */
        public function getStart()
        {
            return $this->getState('list.start');
        }
    }

## Control Flow

### Starting the component - the Controller

It is worth remembering that the non-SEF url for the list of walks page
is index.php?option=com_mywalks&task=display&view=mywalks. The *task*
part is often left out, in which case the default task is set to
*display*. If the *view* part is left out then the component must set
the default view.

Each page request starts with an initialisation sequence. That done, the
entry points to the component are via their controller files. The
default component view is *display* so it should be no surprise that the
default controller is DisplayController. This controller does not do
much other than call its parent controller. However, controllers can be
used to do initial processing. For example, if a form is being submitted
it is common practice to check the form token and *die* if it is
invalid.

#### DisplayController

    Essential Administrator Files
    Although we are still developing the code for the Site display, some Administrator code is needed. The services/provider.php file is used to boot the component, either to display its own site views or for use by the menu module to create menu items.


    The services provider file: administrator/components/com_mywalks/services/provider.php

    Pay special notice to the lines starting $container->registerServiceProvider as this is where your code gets registered in a container for use later.

    registerServiceProvider(new CategoryFactory('\\J4xdemos\\Component\\Mywalks'));
            $container->registerServiceProvider(new MVCFactory('\\J4xdemos\\Component\\Mywalks'));
            $container->registerServiceProvider(new ComponentDispatcherFactory('\\J4xdemos\\Component\\Mywalks'));
            $container->registerServiceProvider(new RouterFactory('\\J4xdemos\\Component\\Mywalks'));
            $container->set(
                    ComponentInterface::class,
                    function (Container $container)
                    {
                        $component = new MywalksComponent($container->get(ComponentDispatcherFactoryInterface::class));

                        $component->setRegistry($container->get(Registry::class));
                        $component->setMVCFactory($container->get(MVCFactoryInterface::class));
    //                  $component->setCategoryFactory($container->get(CategoryFactoryInterface::class));
                        $component->setRouterFactory($container->get(RouterFactoryInterface::class));

                        return $component;
            }
            );
        }
    };

#### The component boot file: administrator/components/com_mywalks/src/Extension/MywalksComponent.php

    getRegistry()->register('mywalksadministrator', new AdministratorService);
        }
    }

For the moment the call to register the Administrator Service is
commented out. That results in a run-time error when invoking the
Mywalks component from the Administrator interface. Something to come
back to in Part 2.

### The Component Router

At this stage the com_mywalks component works. One menu item is needed
to link to the list of walks. There is snag: in the list of walks the
links to individual walks like like this:

    /site-root/my-walks.html?view=mywalk&id=1

(where the site-root my or may not be a subfolder tree). Time for a
custom SEF router? And take a break to read <a
href="https://docs.joomla.org/J3.x:Supporting_SEF_URLs_in_your_component"
class="external text" target="_blank"
rel="noreferrer noopener">Supporting SEF URLs in your component</a> . I
have another Joomla package that uses SEF urls of the form
\[domain\]/XXX/YY/page-title.html where XXX is an organisation branch
code and YY is a language code. Some branches use multiple languages.
Non-standard! Yes, but that is what the organisation asked for.

For the mywalks component I want to use individual walk urls like this:

    /site-root/mywalks/walk-n/walk-title.html

Where n is the individual walk id and the walk-title is automatically
generated from the actual title. Neither walk-title nor .html are
actually needed. The former is for friendliness and the latter because I
am old fashioned.

There are no menu items for individual walks. They are not wanted and
there is no way to generate them. A custom router is required,
consisting of two files: Router.php and MywalksNomenuRules.php.

#### The Router File: component/com_mywalks/src/Service/Router.php

    categoryFactory = $categoryFactory;
            $this->db              = $db;

            $params = ComponentHelper::getParams('com_mywalks');
            $this->noIDs = (bool) $params->get('sef_ids');

            $mywalks = new RouterViewConfiguration('mywalks');
            $mywalks->setKey('id');
            $this->registerView($mywalks);

            $mywalk = new RouterViewConfiguration('mywalk');
            $mywalk->setKey('id');
            $this->registerView($mywalk);

            parent::__construct($app, $menu);

            $this->attachRule(new MenuRules($this));
            $this->attachRule(new StandardRules($this));
            $this->attachRule(new NomenuRules($this));
        }
    }

Notice the lines that define and use custom rules:

        use Joomla\Component\Mywalks\Site\Service\MywalksNomenuRules as NomenuRules;
        ...
                $this->attachRule(new NomenuRules($this));

The rules include a *build* function to create the links to individual
walks, and a *parse* function to translate an incoming SEF url to an
internal Joomla route. There is no need to worry about the link in the
menu item as it is take care of by the MenuRules rules.

#### The Router Rules file: components/my_walks/src/Service/MywalksNomenuRules.php

    router = $router;
        }

        /**
         * Dummymethod to fullfill the interface requirements
         *
         * @param   array  &$query  The query array to process
         *
         * @return  void
         *
         * @since   3.4
         * @codeCoverageIgnore
         */
        public function preprocess(&$query)
        {
            $test = 'Test';
        }

        /**
         * Parse a menu-less URL
         *
         * @param   array  &$segments  The URL segments to parse
         * @param   array  &$vars      The vars that result from the segments
         *
         * @return  void
         *
         * @since   3.4
         */
        public function parse(&$segments, &$vars)
        {
            //with this url: http://localhost/j4x/my-walks/mywalk-n/walk-title.html
            // segments: [[0] => mywalk-n, [1] => walk-title]
            // vars: [[option] => com_mywalks, [view] => mywalks, [id] => 0]

            $vars['view'] = 'mywalk';
            $vars['id'] = substr($segments[0], strpos($segments[0], '-') + 1);
            array_shift($segments);
            array_shift($segments);
            return;
        }

        /**
         * Build a menu-less URL
         *
         * @param   array  &$query     The vars that should be converted
         * @param   array  &$segments  The URL segments to create
         *
         * @return  void
         *
         * @since   3.4
         */
        public function build(&$query, &$segments)
        {
            // content of $query ($segments is empty or [[0] => mywalk-3])
            // when called by the menu: [[option] => com_mywalks, [Itemid] => 126]
            // when called by the component: [[option] => com_mywalks, [view] => mywalk, [id] => 1, [Itemid] => 126]
            // when called from a module: [[option] => com_mywalks, [view] => mywalks, [format] => html, [Itemid] => 126]
            // when called from breadcrumbs: [[option] => com_mywalks, [view] => mywalks, [Itemid] => 126]

            // the url should look like this: /site-root/mywalks/walk-n/walk-title.html

            // if the view is not mywalk - the single walk view
            if (!isset($query['view']) || (isset($query['view']) && $query['view'] !== 'mywalk') || isset($query['format']))
            {
                return;
            }
            $segments[] = $query['view'] . '-' . $query['id'];
            // the last part of the url may be missing
            if (isset($query['slug'])) {
                $segments[] = $query['slug'];
                unset($query['slug']);
            }
            unset($query['view']);
            unset($query['id']);
        }
    }

When there is a menu item for a mywalks list page the MywalksNomenuRules
build function will be called for every internal link in a page: in
modules, menus and even content articles. So watch out for run-time
error messages.

## And Finally

That is it - a working component, but only working on the site side!

<img
src="https://docs.joomla.org/images/2/2a/Mywalks-site-walks-list.jpg"
decoding="async" data-file-width="800" data-file-height="672"
width="800" height="672" alt="The Mywalks site walks list" />

## More Information

[Manifest
Files](https://docs.joomla.org/Manifest_files "Special:MyLanguage/Manifest files")

## Todo:

- Add code to sort the walks list on a selected column.
- Add code for for walks list pagination.
- Add some sort of *back* link in the single walk page, or modify the
  breadcrumb module.
