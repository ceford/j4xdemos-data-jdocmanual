<!-- Filename: J4.x:Adding_an_API_to_a_Joomla_Component / Display title: Adding an API to a Joomla Component -->

Joomla!  4.0

This page is intended to document how to integrate the Web Services
layer introduced in
<img src="https://docs.joomla.org/images/f/f4/Compat_icon_4_0.png"
decoding="async" data-file-width="40" data-file-height="17" width="40"
height="17" alt="Joomla 4.0" /> into your existing Joomla component.
This assumes that you are using the default Joomla MVC layer

  
**Web Services integration for weblinks extension as an example**

Repository extension:
<a href="https://github.com/joomla-extensions/weblinks"
class="external free" target="_blank"
rel="nofollow noreferrer noopener">https://github.com/joomla-extensions/weblinks</a>

Pull request:
<a href="https://github.com/joomla-extensions/weblinks/pull/407"
class="external free" target="_blank"
rel="nofollow noreferrer noopener">https://github.com/joomla-extensions/weblinks/pull/407</a>

## First step

1\. Create a folder ***src/api***

<img src="https://docs.joomla.org/images/e/ec/Struct1.png"
class="thumbimage" decoding="async" data-file-width="414"
data-file-height="262" width="414" height="262" />
<a href="https://docs.joomla.org/File:Struct1.png" class="internal"
title="Enlarge"></a>File system structure

2\. Create a class ***WeblinksController***

    use Joomla\CMS\MVC\Controller\ApiController;

    class WeblinksController extends ApiController 
    {
        protected $contentType = 'weblinks';

        protected $default_view = 'weblinks';
    }

Override the following fields:

    $contentType - will be used as default for $modelName as well when outputting response as type object
    $default_view - will be used as default for $viewName

3\. Create a class ***JsonApiView.php***

    use Joomla\CMS\MVC\View\JsonApiView as BaseApiView;

    class JsonApiView extends BaseApiView
    {
        protected $fieldsToRenderItem = [
            'id',
            'catid',
            'title',
            'alias',
            'url',
            'xreference',
            'tags',
        ];

        protected $fieldsToRenderList = [
            'id',
            'title',
            'alias',
        ];
    }

Override the following fields:

    $fieldsToRenderItem - array of fields to display a single object
    $fieldsToRenderList - array of fields for listing objects

## Second step

1\. Create a folder ***plugins/webservices/weblinks***

<img src="https://docs.joomla.org/images/0/0f/Struct2.png.png"
class="thumbimage" decoding="async" data-file-width="328"
data-file-height="339" width="328" height="339" />
<a href="https://docs.joomla.org/File:Struct2.png.png" class="internal"
title="Enlarge"></a>File system structure

2\. In the ***weblinks.php***, create the class
***PlgWebservicesWeblinks***

    use Joomla\CMS\Plugin\CMSPlugin;
    use Joomla\CMS\Router\ApiRouter;

    class PlgWebservicesWeblinks extends CMSPlugin
    {
        public function onBeforeApiRoute(&$router)
        {
            $router->createCRUDRoutes('v1/weblinks', 'weblinks', ['component' => 'com_weblinks']);
        }
    }

In the ***onBeforeApiRoute*** method, register all the routes that we
need for webservice.

3\. Create ***weblinks.xml***


        plg_webservices_weblinks
        Joomla! Project
        August 2017
        (C) 2005 - 2019 Open Source Matters. All rights reserved.
        GNU General Public License version 2 or later; see LICENSE.txt
        admin@joomla.org
        www.joomla.org
        4.0.0
        PLG_WEBSERVICES_WEBLINKS_XML_DESCRIPTION
        
             ##FILES##
        
        
             ##LANGUAGE_FILES##
        

4\. Create files ***en-GB/en-GB.plg_webservices_weblinks.ini***,
***en-GB/en-GB.plg_webservices_weblinks.sys.ini*** with next content:

    ; Joomla! Project
    ; Copyright (C) 2005 - 2019 Open Source Matters. All rights reserved.
    ; License GNU General Public License version 2 or later; see LICENSE.txt, see LICENSE.php
    ; Note : All ini files need to be saved as UTF-8

    PLG_WEBSERVICES_WEBLINKS="Web Services - Weblinks"
    PLG_WEBSERVICES_WEBLINKS_XML_DESCRIPTION="Used to add weblinks routes to the Web Services API for your website."

## Third step

If this plugin is linked to another element (a component, for example),
then the whole thing needs putting together as a package. In that case
in the file ***src/administrator/manifests/packages/pkg_weblinks.xml***
add a description for webservice plugin

        ...
        plg_webservices_weblinks.zip

## Categories

1\. Add categories support for weblinks webservice. Edit the file
***src/plugins/webservices/weblinks/weblinks.php***

    class PlgWebservicesWeblinks extends CMSPlugin
    {
        public function onBeforeApiRoute(&$router)
        {
            ...
            $router->createCRUDRoutes(
                'v1/weblinks/categories',
                'categories',
                ['component' => 'com_categories', 'extension' => 'com_weblinks']
            );
        }
    }

We use the ready-made component ***com_categories***, just need to pass
the parameter 'extension' =\> 'com_weblinks'

## Fields

1\. Add fields and fields groups support for weblinks webservice. Edit
the file ***src/plugins/webservices/weblinks/weblinks.php***

    class PlgWebservicesWeblinks extends CMSPlugin
    {
        public function onBeforeApiRoute(&$router)
        {
            ...
            $router->createCRUDRoutes(
                'v1/fields/weblinks',
                'fields',
                ['component' => 'com_fields', 'context' => 'com_weblinks.weblink']
            );

            $router->createCRUDRoutes(
                'v1/fields/groups/weblinks',
                'groups',
                ['component' => 'com_fields', 'context' => 'com_weblinks.weblink']
            );
        }
    }

2\. Override the function ***save*** in ***WeblinksController***

    class WeblinksController extends ApiController
    {
        ...

        protected function save($recordKey = null)
        {
            $data = (array) json_decode($this->input->json->getRaw(), true);

            foreach (FieldsHelper::getFields('com_weblinks.weblink') as $field)
            {
                if (isset($data[$field->name]))
                {
                    !isset($data['com_fields']) && $data['com_fields'] = [];

                    $data['com_fields'][$field->name] = $data[$field->name];
                    unset($data[$field->name]);
                }
            }

            $this->input->set('data', $data);

            return parent::save($recordKey);
        }

        ...
    }

3\. Override the functions ***displayList, displayItem, prepareItem***
in ***Weblinks\JsonApiView***

    class JsonApiView extends BaseApiView
    {
        ...

        public function displayList(array $items = null)
        {
            foreach (FieldsHelper::getFields('com_weblinks.weblink') as $field)
            {
                $this->fieldsToRenderList[] = $field->name;
            }

            return parent::displayList();
        }

        public function displayItem($item = null)
        {
            foreach (FieldsHelper::getFields('com_weblinks.weblink') as $field)
            {
                $this->fieldsToRenderItem[] = $field->name;
            }

            return parent::displayItem();
        }

        protected function prepareItem($item)
        {
            foreach (FieldsHelper::getFields('com_weblinks.weblink', $item, true) as $field)
            {
                $item->{$field->name} = isset($field->apivalue) ? $field->apivalue : $field->rawvalue;
            }

            return parent::prepareItem($item);
        }

        ...
    }

Pay attention in function prepareItem to

    $field->apivalue

If the type of the field is complex, we hope that it will return a value
for output in the Web Services API component, otherwise we will take

    $field->rawvalue

## Integration Work Example

***NOTE: Remember to enable weblinks webservice plugin!***

### Weblinks

#### Get List of Weblinks

curl -X GET /api/index.php/v1/weblinks

#### Get Single Weblink

curl -X GET /api/index.php/v1/weblinks/{weblink_id}

#### Delete Weblink

curl -X DELETE /api/index.php/v1/weblinks/{weblink_id}

#### Create Weblink

curl -X POST -H "Content-Type: application/json"
/api/index.php/v1/weblinks -d

    {
        "access": "1",
        "alias": "",
        "catid": "8",
        "description": "text",
        "images": {
            "float_first": "",
            "float_second": "",
            "image_first": "",
            "image_first_alt": "",
            "image_first_caption": "",
            "image_second": "",
            "image_second_alt": "",
            "image_second_caption": ""
        },
        "language": "*",
        "metadata": {
            "rights": "",
            "robots": ""
        },
        "metadesc": "",
        "metakey": "",
        "modified": "",
        "params": {
            "count_clicks": "",
            "height": "",
            "target": "",
            "width": ""
        },
        "title": "weblink title",
        "url": "http://somelink.com/",
        "xreference": "xreference"
    }

#### Update Weblink

curl -X PUT -H "Content-Type: application/json"
/api/index.php/v1/weblinks/{weblink_id} -d

    {
        "catid": "8",
        "description": "some new text",
        "language": "*",
        "title": "new title",
        "url": "http://newsomelink.com/"
    }

### Categories

Route Weblinks Categories is: "v1/weblinks/categories"

Working with it is similar to [Banners
Categories](https://docs.joomla.org/J4.x:Joomla_Core_APIs#Categories "Special:MyLanguage/J4.x:Joomla Core APIs").

### Fields

Route Fields Weblinks is: "v1/fields/weblinks"

Working with it is similar to [Fields
Contact](https://docs.joomla.org/J4.x:Joomla_Core_APIs#Fields_Contact "Special:MyLanguage/J4.x:Joomla Core APIs").

### Groups Fields

Route Groups Fields Weblinks is: "v1/fields/groups/weblinks"

Working with it is similar to [Groups Fields
Contact](https://docs.joomla.org/J4.x:Joomla_Core_APIs#Groups_Fields_Contact "Special:MyLanguage/J4.x:Joomla Core APIs").
