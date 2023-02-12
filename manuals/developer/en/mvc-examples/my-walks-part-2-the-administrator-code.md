<!-- Filename: J4.x:My_Walks_Part_2:_The_Administrator_code / Display title: My Walks Part 2: The Administrator code -->

## J4 Component Tutorial: Mywalks Part 2 - The Admin Code

It should be possible to read through Part 2 of the Mywalks tutorial
without first reading Part 1. Take them in either order. This part is
about the Admin code. There will be some repeat of points common to
both. Please download the complete code from Github:

- <a
  href="https://github.com/ceford/j4xdemos-com-mywalks/blob/master/com_mywalks.zip"
  class="external free" target="_blank"
  rel="nofollow noreferrer noopener">https://github.com/ceford/j4xdemos-com-mywalks/blob/master/com_mywalks.zip</a>

and read through it where indicated in the tutorial.

## Review of Part 1

The scenario is that, for tutorial purposes, the Mywalks component
manages a list of walks and the occasions on which those walks were
undertaken. So two tables are needed. There are no frills: no
categories, scores, hit counters or site side data entry, etc. Just
simple code to get newcomers and upgraders to Joomla 4 started on
component coding.

The data schema is given in part 1. Or you can look at the
admin/sql/install.mysql.sql file in the unzipped source code. You can
also look at the mywalks.xml manifest file in the root of the downloaded
source to see the component structure. Notice the folders and files with
Upper Case first letters in folder and file names are name-spaced and
others are not. And there is a different folder and file structure from
previous Joomla versions.

## The Language Files

Small components grow bigger and bigger components grow bigger still.
This can lead to language files that are messy and hard to maintain. The
lib_joomla.ini file contains over 800 lines. So it pays to think about
the structure in advance. Here is my suggestion:

    [COM_COMPONENT]_[VIEW]_[USAGE]_[DESCRIPTIVE_TEXT]="The translation"

For example:

    COM_MYWALKS_MYWALKS_PAGE_TITLE="Mywalks - list of Walks"
    COM_MYWALKS_MYWALKS_TABLE_CAPTION="List of Walks"
    COM_MYWALKS_MYWALKS_LABEL_DESCRIPTION="Description"
    COM_MYWALKS_MYWALKS_LABEL_DISTANCE="Distance"

And sort into alphabet order. You can look at the Joomla core language
files to see for alternatives. The choice is yours. Just think about it!

In case you were wondering: the \[component\].sys.ini file is used by
the admin system for managing the component. It contains very few terms.
The \[component\].ini file is the one where the component text terms
live.

A word of warning: all fixed English text in the component should appear
as keys. You may be tempted to enter just the text value in the code
with the intention of fixing it later. If you do, you will come to
regret it!

## The Admin Files

Just a reminder of the Admin folder structure from the manifest
mywalks.xml file:

        
            
                access.xml
                config.xml
                forms
                services
                sql
                src
                tmpl
            
            
                language/en-GB/com_mywalks.ini
                language/en-GB/com_mywalks.sys.ini
            
            Mywalks
        

Note that the **src** folder contains all of the namespaced code in
separate sub-folders.

Not so obvious is that there are four Views to manage: the list of
walks, the walk edit form, the list of dates visited and the date
visited form. So four View files, four tmpl files, four Model files,
four form files, four Controller files but only two Table files. More on
that later. It is probably enough to cover two examples: the walks list
View and the walk Edit view. Notice the singular and plural: walk and
walks. The former implies an Edit view and the latter a List view. A
subtle difference for tired old eyes! The component is entered via a
menu item leading to the walks list view. None of the other views have
menu items. The walks list view and the walk edit view have some tricky
linking issues to be covered later.

## The Walks List

This is a screen shot of the working Administrator's Walks list:

<img
src="https://docs.joomla.org/images/1/14/Mywalks-admin-walks-list.jpg"
decoding="async" data-file-width="800" data-file-height="481"
width="800" height="481" alt="The Administrator Walks List" />

The code to generate this list is explained here in reverse alphabet
order: View, tmpl, Model and Controller. A Table is not required as the
list is not modifying data and is in fact extracting data from two
tables.

### The View file - View/Mywalks/HtmlView.php

To explain fragments of the file piece by piece

#### The namespace and use statements

        namespace J4xdemos\Component\Mywalks\Administrator\View\Mywalks;
        
        defined('_JEXEC') or die;
        
        use Joomla\CMS\Helper\ContentHelper;
        use Joomla\CMS\Language\Text;
        use Joomla\CMS\MVC\View\GenericDataException;
        use Joomla\CMS\MVC\View\HtmlView as BaseHtmlView;
        use Joomla\CMS\Toolbar\Toolbar;
        use Joomla\CMS\Toolbar\ToolbarHelper;

The namespace statement must come before any executable statements, so
before the check that this script has been loaded by Joomla and not
called directly via a web url. The references to use Joomla\CMS in fact
refer to classes found in site_root/libraries/src. If you copy and paste
from another component you may have library files you don't need and you
might be missing ones you do.

#### The class statements

        class HtmlView extends BaseHtmlView
        {
            protected $items;
            protected $pagination;
            protected $state;
            public $filterForm;
            public $activeFilters;
            protected $sidebar;

When the tmpl file uses \$this it is referring to this class. So
\$this-\>items needs to be populated with walk data in this file.

#### The display function

        public function display($tpl = null)
        {
            $this->items         = $this->get('Items');
            $this->pagination    = $this->get('Pagination');
            $this->state         = $this->get('State');
            $this->filterForm    = $this->get('FilterForm');
            $this->activeFilters = $this->get('ActiveFilters');

            // Check for errors.
            if (count($errors = $this->get('Errors')))
            {
                throw new GenericDataException(implode("\n", $errors), 500);
            }

            $this->addToolbar();

            return parent::display($tpl);
        }

It is not obvious, but calls of the form \$this-\>get('Items') refer to
the getItems() public function in the model or its parent model. So look
for the functions in Model/MywalksModel.php. After setting up the View
with Model data control is passed to the parent::display() and returns
whatever it returns.

#### The addToolbar function

       protected function addToolbar()
        {
            // Get the toolbar object instance
            $toolbar = Toolbar::getInstance('toolbar');

            ToolbarHelper::title(Text::_('COM_MYWALKS_MYWALKS_PAGE_TITLE'), 'mywalks');

            $canDo = ContentHelper::getActions('com_mywalks');

            if ($canDo->get('core.create'))
            {
                $toolbar->addNew('mywalk.add');
            }

The ToolbarHelper::Title call puts the Title at the top of the page. In
this case translated as *Mywalks - list of Walks*.

The ContentHelper::getActions function is called to find out what this
user can do with this component. If the user is allowed to create new
walks then a '***New'*** button is added to the Toolbar. Look at the
code to see how other buttons are created. There are a lot buttons to
choose from and you can create custom buttons.

### The tmpl file - tmpl/mywalks/default.php

As this is the default view of the component the tmpl file is named
default.php file. Have a look at it in the downloaded code. Notice that
there is no namespace statement at the top of the file. This file does
not declare a class so a namespace is not needed. Short extracts are
explained here.

#### Setting some variables

        $listOrder = $this->escape($this->state->get('list.ordering'));
        $listDirn  = $this->escape($this->state->get('list.direction'));
        $states = array (
                '0' => Text::_('JUNPUBLISHED'),
                '1' => Text::_('JPUBLISHED'),
                '2' => Text::_('JARCHIVED'),
                '-2' => Text::_('JTRASHED')
        );
        $editIcon = '';

It is sometimes helpful to create pieces of text within the top php
section for use later. It makes the code more readable and in some cases
creates a variable once for use many times as an alternative to calling
a function many times.

#### The Form tag

        
            
                
                    
                         $this)); ?>

When submitted the form calls itself. The actions it can take involve
changing the sort order or changing the state of one or more walks.
Pretty much all Joomla forms have '***adminForm'*** for the '**name'**
and '**id'**. Anything else requires custom handling. The call to
LayoutHelper:: render creates the Search tools bar above the results
table.

Bootstrap 4 markup is not covered in this tutorial!

#### The No Data Alert

        items)) : ?>
            
                
                
                
            
        

If there are no data returned, for example if the Trashed state filter
has been selected and there are no trashed walks, a simple message is
displayed and there is no results table. Otherwise the results table is
displayed.

#### The Data Table

        
            
                , 
                
            
            
                
                    
                        
                    

The HTMLHelper here creates the check all checkbox and the column
sorting feature in the table header.

#### The Table Rows

        
        
        items);
        foreach ($this->items as $i => $item) :
        ?>
            
                
                    id); ?>
                

state\]; ?\>

escape(\$item-\>title); ?\>

description; ?\>

To create the table of results the code cycles through each of the
\$items, creating one row for each \$item. The item results are accessed
as object variables: \$item-\>id, \$item-\>state, \$item-\>description
and so on.

#### Pagination

            
        



    pagination->getListFooter(); ?>

If there are more results than is set in the filters (the default is
typically 20 or 25 and is set globally) the pagination function returns
the html code to render a page selector. Otherwise it returns nothing.

#### The Hidden Variables

        
        
        

These variables are important! The task variable initially has no value.
It is given a value when an action button is clicked. For example the
New or Status buttons or the Filter Options button. The form is then
submitted with that action requested. The boxchecked value is set and
unset by Javascript and is used to block form submission if no check
boxes are selected. The form token Helper creates a hidden field with a
long alphanumeric name and a value of 1. The form token is validated
when the form is submitted. If it is not valid the action is blocked and
a blank screen result is returned.

### The Filter XML File - forms/mywalks_filter.xml

Notice the file naming convention. Stick to it or the filter will not
appear. There are typically two parts to the xml content: the filter and
the list.

        
        
            
                
        
                
                    JOPTION_SELECT_PUBLISHED
                
            
        
            
                
                    JGLOBAL_SORT_BY
                    JSTATUS_ASC
                    JSTATUS_DESC
                    JGLOBAL_TITLE_ASC
                    JGLOBAL_TITLE_DESC
                    JGRID_HEADING_ID_ASC
                    JGRID_HEADING_ID_DESC
                
        
                
            
        

In this case the filter tools bar will contain a text search form field
and a status form fiel. You could add more fields - for example a
toilets form field. If you do, you also have to make an entry in the
model, covered next. Notice that a change in the list limit filter field
will trigger imediate form submission.

### The Model File - Model/MywalksModel

See your downloaded code for the full file with its Joomla doc blocks.

#### The class constructor

        class MywalksModel extends ListModel
        {
            public function __construct($config = array())
            {
                if (empty($config['filter_fields']))
                {
                    $config['filter_fields'] = array(
                        'id', 'a.id',
                        'title', 'a.title',
                        'state', 'a.state',
                    );
                }
        
                parent::__construct($config);
            }

This is where the filter fields added to the mywalks_filter.xml must be
declared to make them appear in the output. The parent ListModel has a
lot of code not mentioned here. See the API documentation when it
appears. Or just look for the file containing the ListModel class and
its parent too.

#### The populateState method

        protected function populateState($ordering = 'a.id', $direction = 'asc')
        {
            $search = $this->getUserStateFromRequest($this->context . '.filter.search', 'filter_search');
            $this->setState('filter.search', $search);

            $published = $this->getUserStateFromRequest($this->context . '.filter.published', 'filter_published', '');
            $this->setState('filter.published', $published);

            // List state information.
            parent::populateState($ordering, $direction);
        }

When a page is first loaded no filters are set. When a filter is set the
next page load has the new filter setting in the form submission. We
need to save that setting as state variable for use when filtering is
actually used in the getQuery function. Notice the default values for
ordering and direction if none are passed to this function.

#### The getStoreId method

        protected function getStoreId($id = '')
        {
            // Compile the store id.
            $id .= ':' . $this->getState('filter.search');
            $id .= ':' . $this->getState('filter.published');

            return parent::getStoreId($id);
        }

Tricky to explain! This function puts together a string from which a
hash is calculated that is used to cache part of an SQL query to avoid
clashes with another extension, such as a module, that may be executed
in the same page load.

#### The getListQuery function

        protected function getListQuery()
        {
            // Create a new query object.
            $db    = $this->getDbo();
            $query = $db->getQuery(true);

            // Select the required fields from the table.
            $query->select(
                $this->getState(
                    'list.select',
                    'a.*, (SELECT count(`date`) from #__mywalk_dates WHERE walk_id = a.id) AS nvisits'
                )
            );
            $query->from('#__mywalks AS a');

            // Filter by published state
            $published = (string) $this->getState('filter.published');

            if (is_numeric($published))
            {
                $query->where($db->quoteName('a.state') . ' = :published');
                $query->bind(':published', $published, ParameterType::INTEGER);
            }
            elseif ($published === '')
            {
                $query->where('(' . $db->quoteName('a.state') . ' = 0 OR ' . $db->quoteName('a.state') . ' = 1)');
            }

            // Filter by search in title.
            $search = $this->getState('filter.search');

            if (!empty($search))
            {
                $search = $db->quote('%' . str_replace(' ', '%', $db->escape(trim($search), true) . '%'));
                $query->where('(a.title LIKE ' . $search . ')');
            }

            // Add the list ordering clause.
            $orderCol  = $this->state->get('list.ordering', 'a.id');
            $orderDirn = $this->state->get('list.direction', 'ASC');

            $query->order($db->escape($orderCol) . ' ' . $db->escape($orderDirn));

            return $query;
        }

This where you need to know about sql! You need to be able to write
queries and debug them. To start we need a database object in the \$db
variable and a database query object in \$query. Passing true to
\$db-\>getQuery(true) returns a new object. If true is omitted an
existing query is returned that is already populated, usually resulting
in disaster. In Joomla, parts of a query can be chained together, which
tends to make for tricky understanding. So here the parts are assembled
separately.

The '**select'** statement: the part that says \$this-\>getState will
either get the query using the storeId hash or create a new query and
store it in the hash for later in this page load. The query itself
selects all fields from table '***a'*** and a count of the number of
walk visits for each walk returned. ToDo: add a where clause to count
only published walk visits.

The '**from'** statement: this simply says which table to use. The
\#\_\_ part gets replaced by the table prefix, which varies from site to
site.

The '**where'** clauses use any filters set. They are complicated
because they may be integers or strings or null.

The '**order'** clause adds the ordering statements.

The query is then returned to the caller where page limit statements are
added.

If there is an error in your sql syntax you may just see a 500 Internal
Error message. If so, before the return statement you can insert echo
\$query-\>\_\_tostring();die(); to see what your query contains at that
stage.

#### The getItems function

        public function getItems()
        {
            $items = parent::getItems();

            return $items;
        }

You only need this if you want to add access code or as a step in
debugging. If the function is left out the parent getIems function will
be callsed.

### The Controller File - Controller/DisplayController.php

Note: this is the controller file with th doc blocks removed. Put them
in or leave them in on any component you create.

        namespace J4xdemos\Component\Mywalks\Administrator\Controller;
        
        defined('_JEXEC') or die;
        
        use Joomla\CMS\MVC\Controller\BaseController;
        
        class DisplayController extends BaseController
        {
            protected $default_view = 'mywalks';
        
            public function display($cachable = false, $urlparams = array())
            {
                return parent::display();
            }
        }

The only job the controller has to do is define the default component
view.

That is it! This view should now display by selecting the Menu item.

## The Walk Edit Form

In the list of walks the walk Title was made a link to the Edit form.
The link says index.php?option=com_mywalks&task=mywalk.edit&id=1. A
similar set of files are involved to those needed for the list of walks,
except that all of the filenames are singular and this time a Table file
is required.

This is a screenshot of the working Administrator's Walk edit form: <img
src="https://docs.joomla.org/images/d/de/Mywalks-admin-walk-edit-details.jpg"
decoding="async" data-file-width="800" data-file-height="859"
width="800" height="859"
alt="The Administrator Walkd edit form - details panel" />

### The View file - View/Mywalk/HtmlView

This file is very similar to the View/Mywalks/Html file so there is
nothing to be gained by showing it in full. It loads a different title
and a different set of buttons. See the downloaded code.

### The tmpl file - tmpl/Mywalk/edit.php

#### The form tab top code

        
        
            
        
            
                 'details')); ?>
        
                

Notice tha the form action refers to itself. In this case the id is
different in case we need to implement a custom form validator. The
LayoutHelper::render function puts the walk Title above the rest of the
form, which is broken into tabbed panels. This is a common Joomla
layout.

The Tabset and individual tabs are created by the HTMLHelper. It is
possible to get the form structure from the form xml file and cycle
through the tabs and the fields in code. That technique is not
implemented here.

#### The details tab and its form fields

            
            
                
                    
                        
                            form->renderField('description'); ?>
                            form->renderField('distance'); ?>
                            form->renderField('id'); ?>
                        
                    
                
                
                    
                        
                            
                        
                    
                
            
            

In this layout the first three form fields appear occupying 9/12 of the
parent div width. The status field appears to the right, occupying 3/12
of the parent div width.

#### The options tab and its form fields

            
            
                
                    form->renderField('toilets'); ?>
                    form->renderField('cafe'); ?>
                    form->renderField('bogs'); ?>
                
            
            

#### The picture tab and its form fields

            
            
                
                    form->renderField('picture'); ?>
                    form->renderField('width'); ?>
                    form->renderField('height'); ?>
                    form->renderField('alt'); ?>
                
            
            

            
        
        
        

The appearance of each of the form fields is defined in the form xml
file

### The xml form file - forms/mywalk.xml

Notice that if the field sets and fields are cycled through in code they
will appear in the order given here.

#### The details fields

        
        
        
            
        
                
        
                
        
                
        
                
        
                
                    JPUBLISHED
                    JUNPUBLISHED
                    JARCHIVED
                    JTRASHED
                
        
            

The id field is set to read only because the id is allocated on saving
and must not be changed. Notice the different field types: number, text,
textarea, decimel and list. Various attributes are set here, such as
class, readonly, size and so on.

#### The options fields

        
            
                JNO
                JYES
            

            
                JNO
                JYES
            

            
                JNO
                JYES
            
        

The fields here return Yes/No boolean values. In some cases a number may
be preferable, for example a bog facto on a scale of 1 to 5.

#### The picture fields

        

            

            

            

            
        

The media field allows selection of a photograph from the site images
folder. And the selector form that appears also allows uploads. ToDo:
implement use of the pictures.

### The Model file - Models/MywalksModel.php

The model file is about 300 lines long and mostly boilerplate code that
does not need much comment.

#### The getTable function

        public function getTable($name = '', $prefix = '', $options = array())
        {
            $name = 'mywalks';
            $prefix = 'Table';

            if ($table = $this->_createTable($name, $prefix, $options))
            {
                return $table;
            }

            throw new \Exception(Text::sprintf('JLIB_APPLICATION_ERROR_TABLE_NAME_NOT_SUPPORTED', $name), 0);
        }

This is worthy of mention because it is where the name of the database
table containing the list of walks is defined. ToDo: find out what this
file does that the Table file does not.

### The Table file - Table/MywalksTable.php

        namespace J4xdemos\Component\Mywalks\Administrator\Table;
        
        defined('JPATH_PLATFORM') or die;
        
        use Joomla\CMS\Table\Table;
        use Joomla\Database\DatabaseDriver;
        
        class MywalksTable extends Table
        {
            public function __construct(DatabaseDriver $db)
            {
                parent::__construct('#__mywalks', 'id', $db);
            }
        }

### The Controller file - Controller/MywalkController

        namespace J4xdemos\Component\Mywalks\Administrator\Controller;
        
        defined('_JEXEC') or die;
        
        use Joomla\CMS\MVC\Controller\FormController;
        
        class MywalkController extends FormController
        {
        }

This file does nothing! All of the required actions are executed by the
parent Class.

That is it! We should now be able to edit existing walks and create new
ones.

## The Walk Dates List and Edit Form

Much of the code for handling the walk dates is similar to the code for
handling the walks and there is no real need to repeat that here for
tutorial purposes. However, there is one big difference that needs
explanation. It concerns passing the walk id from walks list to the walk
dates list.

Access to the visits list is via a link in the walks list:
index.php?option=com_mywalks&view=mywalk_dates&walk_id=1. So the walk id
is passed to the list to show the list of walk dates for that walk,
including none if the walk has yet to be visited. The walk id needs to
be stored in a hidden field in the list form because it disappears from
the url if there is a table sort or filter change. So we capture the
walk id in the populateState function or from a session state variable.

Extract from Mywalk_datesModel.php

        protected function populateState($ordering = 'a.id', $direction = 'asc')
        {
            $app = Factory::getApplication();

            $walk_id = $app->input->get('walk_id', 0, 'int');
            if (empty($walk_id)) {
                $walk_id = $app->getUserState('com_mywalks.walk_id');
            }
            $this->setState('walk_id', $walk_id);
            // keep the walk_id for adding new visits
            $app->setUserState('com_mywalks.walk_id', $walk_id);

We get the Walk title and walk id in the tmpl/Mywalk_dates/default.php
file and display the title, in case we have forgotten which walk we are
dealing with. And we put the walk id into a hidden form variable.

Extract from tmpl/mywalk_dates/default.php

        $editIcon = '';
        $title = MywalksHelper::getWalkTitle($this->state->get('walk_id'))->title;
        $walk_id = $this->state->get('walk_id')
        ?>
        
        
                        
                        
                        
        ...
        

The walk dates list has a link to existing visits so we don't need the
walk id to edit existing visits. The '***New'*** button does not help
because the default id is 0. That is the id of the new visit until
committed to the database, when it takes the next available value. We
pick up the walk id in tmp/mywalk_date/edit.php and set the value of the
walk id in the form field:

        $app = Factory::getApplication();
        $walk_id = $app->getUserState('com_mywalks.walk_id');
        
        if (empty($walk_id)) {
            throw new GenericDataException("\nThe walk id was not set!\n", 500);
        }
        ...
                                form->renderField('date'); ?>
                                form->renderField('weather'); ?>
                                form->renderField('id'); ?>
                                form->setValue('walk_id', null, $walk_id); ?>
                                form->renderField('walk_id'); ?>

The walk_id field is read only to prevent the user from changing it. And
here is one of those instances where a fixed string was typed in English
rather than a language file key. Left in to illustrate the point!

ToDo: Implement a Save and Close button.

## And Finally

That is it! A primitive but working component.

Clifford E Ford. August 2019.
