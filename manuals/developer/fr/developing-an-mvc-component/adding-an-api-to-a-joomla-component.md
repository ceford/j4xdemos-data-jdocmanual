<!-- Filename: J4.x:Adding_an_API_to_a_Joomla_Component / Display title: Ajout d'une API à un composant de Joomla -->

Joomla!  4.0

Cette page a pour but de documenter comment intégrer la couche de
services Web introduite dans
<img src="https://docs.joomla.org/images/f/f4/Compat_icon_4_0.png"
decoding="async" data-file-width="40" data-file-height="17" width="40"
height="17" alt="Joomla 4.0" /> dans votre composant Joomla existant.
Cela suppose que vous utilisez la couche MVC par défaut de Joomla.

  
**Intégration des services Web pour l'extension des liens Web à titre
d'exemple**

Dépôt de l'extension
<a href="https://github.com/joomla-extensions/weblinks"
class="external free" target="_blank"
rel="nofollow noreferrer noopener">https://github.com/joomla-extensions/weblinks</a>

Pull request:
<a href="https://github.com/joomla-extensions/weblinks/pull/407"
class="external free" target="_blank"
rel="nofollow noreferrer noopener">https://github.com/joomla-extensions/weblinks/pull/407</a>

## Première étape

1\. Créer un répertoire ***src/api***

<img src="https://docs.joomla.org/images/e/ec/Struct1.png"
class="thumbimage" decoding="async" data-file-width="414"
data-file-height="262" width="414" height="262" />
<a href="https://docs.joomla.org/File:Struct1.png" class="internal"
title="Enlarge"></a>File system structure

2\. Créer une classe ***WeblinksController***

    use Joomla\CMS\MVC\Controller\ApiController;

    class WeblinksController extends ApiController 
    {
        protected $contentType = 'weblinks';

        protected $default_view = 'weblinks';
    }

Remplacez les champs suivants :

    $contentType - sera utilisé par défaut pour $modelName également lors de la sortie de la réponse en tant qu'objet de type
    $default_view - sera utilisé par défaut pour $viewName

3\. Créer une classe ***JsonApiView.php***

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

Remplacez les champs suivants :

    $fieldsToRenderItem - tableau de champs pour afficher un seul objet
    $fieldsToRenderList - tableau de champs pour la liste des objets

## Deuxième étape

1\. Créer un répertoire ***plugins/webservices/weblinks***

<img src="https://docs.joomla.org/images/0/0f/Struct2.png.png"
class="thumbimage" decoding="async" data-file-width="328"
data-file-height="339" width="328" height="339" />
<a href="https://docs.joomla.org/File:Struct2.png.png" class="internal"
title="Enlarge"></a>File system structure

2\. Dans le fichier ***weblinks.php***, créez la classe
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

Dans la méthode ***onBeforeApiRoute***, enregistrez toutes les chemins
dont nous avons besoin pour le webservice.

3\. Créer ***weblinks.xml***


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
        

4\. Créer les fichiers ***en-GB/en-GB.plg_webservices_weblinks.ini***,
***en-GB/en-GB.plg_webservices_weblinks.sys.ini*** avec le contenu
suivant :

    ; Joomla! Project
    ; Copyright (C) 2005 - 2019 Open Source Matters. All rights reserved.
    ; License GNU General Public License version 2 or later; see LICENSE.txt, see LICENSE.php
    ; Note : All ini files need to be saved as UTF-8

    PLG_WEBSERVICES_WEBLINKS="Web Services - Weblinks"
    PLG_WEBSERVICES_WEBLINKS_XML_DESCRIPTION="Used to add weblinks routes to the Web Services API for your website."

## Troisième étape

Si ce plugin est lié à un autre élément (un composant, par exemple),
alors l'ensemble doit être assemblé comme un package. Dans ce cas, dans
le fichier ***src/administrator/manifests/packages/pkg_weblinks.xml***
ajouter une description pour le plugin webservice

        ...
        plg_webservices_weblinks.zip

## Catégories

1\. Ajouter le support des catégories pour le service weblinks. Modifiez
le fichier ***src/plugins/webservices/weblinks/weblinks.php***.

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

Nous utilisons le composant prêt à l'emploi ***com_categories***, il
suffit de passer le paramètre 'extension' =\> 'com_weblinks'

### Champs

1\. Ajouter le support des champs et groupes de champs pour le
webservice weblinks. Modifiez le fichier
***src/plugins/webservices/weblinks/weblinks.php***

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

2\. Substituer la fonction ***save*** sur ***WeblinksController***

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

3\. Substituer les fonctions ***displayList, displayItem, prepareItem***
sur ***Weblinks\JsonApiView***

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

Faites attention dans la fonction prepareItem à

    $field->apivalue

Si le type du champ est complexe, nous espérons qu'il retournera une
valeur pour la sortie dans le composant Web Services API, sinon nous
prendrons

    $field->rawvalue

## Exemple de travail d'intégration

***NOTE : N'oubliez pas d'activer le plugin weblinks webservice !***

### Weblinks

#### Obtenir la liste de liens Web

curl -X GET /api/index.php/v1/weblinks

#### Obtenir un seul lien web

curl -X GET /api/index.php/v1/weblinks/{weblink_id}

#### Supprimer un lien web

curl -X DELETE /api/index.php/v1/weblinks/{weblink_id}

#### Créer un lien web

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

#### Mettre à jour un lien web

curl -X PUT -H "Content-Type: application/json"
/api/index.php/v1/weblinks/{weblink_id} -d

    {
        "catid": "8",
        "description": "some new text",
        "language": "*",
        "title": "new title",
        "url": "http://newsomelink.com/"
    }

### Catégories

Le routage des catégories de liens Web est : "v1/weblinks/categories"

Son utilisation est similaire à celle de [Catégories de
bannières](https://docs.joomla.org/J4.x:Joomla_Core_APIs#Categories "Special:MyLanguage/J4.x:Joomla Core APIs").

### Champs

Le routage des champs de liens web est : "v1/fields/weblinks"

Son utilisation est similaire à celle des [Champs de
Contact](https://docs.joomla.org/J4.x:Joomla_Core_APIs#Fields_Contact "Special:MyLanguage/J4.x:Joomla Core APIs").

### Groupes de champs

Le routage des groupes de champs est : "v1/fields/groups/weblinks"

Travailler avec eux est similaire aux [Groupes de champs de
Contact](https://docs.joomla.org/J4.x:Joomla_Core_APIs#Groups_Fields_Contact "Special:MyLanguage/J4.x:Joomla Core APIs").
