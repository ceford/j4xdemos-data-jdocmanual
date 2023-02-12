<!-- Filename: J4.x:Adding_an_API_to_a_Joomla_Component / Display title: Eine API zu einer Joomla-Komponente hinzufügen -->

Joomla!  4.0

Diese Seite soll dokumentieren, wie sich die in
<img src="https://docs.joomla.org/images/f/f4/Compat_icon_4_0.png"
decoding="async" data-file-width="40" data-file-height="17" width="40"
height="17" alt="Joomla 4.0" /> eingeführte Webservices-Schicht in
bestehende Joomla-Komponenten integrieren können. Dies setzt voraus,
dass die Standard-Joomla-MVC-Schicht verwendet wird.

  
**Ein Beispiel der Webservices-Integration zur Erweiterung von
Weblinks**

Repository der Erweiterung:
<a href="https://github.com/joomla-extensions/weblinks"
class="external free" target="_blank"
rel="nofollow noreferrer noopener">https://github.com/joomla-extensions/weblinks</a>

Pull request:
<a href="https://github.com/joomla-extensions/weblinks/pull/407"
class="external free" target="_blank"
rel="nofollow noreferrer noopener">https://github.com/joomla-extensions/weblinks/pull/407</a>

## Erster Schritt

1\. Verzeichnis erstellen: ***src/api***

<img src="https://docs.joomla.org/images/e/ec/Struct1.png"
class="thumbimage" decoding="async" data-file-width="414"
data-file-height="262" width="414" height="262" />
<a href="https://docs.joomla.org/File:Struct1.png" class="internal"
title="Enlarge"></a>File system structure

2\. Anlegen der Klasse: ***WeblinksController***

    use Joomla\CMS\MVC\Controller\ApiController;

    class WeblinksController extends ApiController 
    {
        protected $contentType = 'weblinks';

        protected $default_view = 'weblinks';
    }

Die folgenden Felder übersteuern (override):

    $contentType - wird als Standard für $modelName verwendet, wenn die Antwort als Typ-Objekt ausgegeben wird
    $default_view - wird als Standard für $viewName verwendet

3\. Anlegen der Klasse: ***JsonApiView.php***

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

Die folgenden Felder übersteuern (override):

    $fieldsToRenderItem - Array aus Feldern zur Anzeige eines einzelnen Objekts
    $fieldsToRenderList - Array aus Feldern um Objekte aufzulisten

## Zweiter Schritt

1\. Verzeichnis erstellen: ***plugins/webservices/weblinks***

<img src="https://docs.joomla.org/images/0/0f/Struct2.png.png"
class="thumbimage" decoding="async" data-file-width="328"
data-file-height="339" width="328" height="339" />
<a href="https://docs.joomla.org/File:Struct2.png.png" class="internal"
title="Enlarge"></a>File system structure

2\. In der Datei ***weblinks.php***, erstellen der Klasse:
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

In der Methode ***onBeforeApiRoute***, alle Routen registrieren, die wir
für den Webservice benötigen.

3\. Erstellen von: ***weblinks.xml***


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
        

4\. Erstellen der Dateien
***en-GB/en-GB.plg_webservices_weblinks.ini***,
***en-GB/en-GB.plg_webservices_weblinks.sys.ini*** mit dem folgenden
Inhalt:

    ; Joomla! Project
    ; Copyright (C) 2005 - 2019 Open Source Matters. All rights reserved.
    ; License GNU General Public License version 2 or later; see LICENSE.txt, see LICENSE.php
    ; Note : All ini files need to be saved as UTF-8

    PLG_WEBSERVICES_WEBLINKS="Web Services - Weblinks"
    PLG_WEBSERVICES_WEBLINKS_XML_DESCRIPTION="Used to add weblinks routes to the Web Services API for your website."

## Dritter Schritt

Wenn dieses Plugin mit einem anderen Element (z. B. einer Komponente)
verknüpft ist, dann muss das Ganze als Paket zusammengestellt werden. In
diesem Fall in der Datei
***src/administrator/manifests/packages/pkg_weblinks.xml*** eine
Beschreibung für das Webservice-Plugin hinzufügen.

        ...
        plg_webservices_weblinks.zip

## Kategorien

1\. Hinzufügen der Kategorie-Unterstützung für den Weblinks-Webservice.
Bearbeiten der Datei
***src/plugins/webservices/weblinks/weblinks.php***.

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

Wir verwenden die vorgefertigte Komponente ***com_categories*** und
müssen nur noch den Parameter 'extension' =\> 'com_weblinks'

## Felder

1\. Hinzufügen von Feldern und Feldgruppen für den Webservice
„Weblinks“. Bearbeiten der Datei
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

2\. Überschreiben der Funktion ***save*** in ***WeblinksController***

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

3\. Überschreiben der Funktionen ***displayList, displayItem,
prepareItem*** in ***Weblinks\JsonApiView***

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

In der Funktion *prepareItem* muss geachtet werden auf:

    $field->apivalue

Falls der Typ des Feldes komplex ist, wird hoffentlich ein Wert für die
Ausgabe in der Web Services API-Komponente zurückgegeben, andernfalls
greifen wir zurück auf:

    $field->rawvalue

## Beispiel für eine integrierte Arbeit

***Hinweis: Nicht vergessen, das Weblinks Webservice Plugin zu
aktivieren!***

### Weblinks

#### Liste von Weblinks erhalten

curl -X GET /api/index.php/v1/weblinks

#### Einzelnen Weblink erhalten

curl -X GET /api/index.php/v1/weblinks/{weblink_id}

#### Weblink löschen

curl -X DELETE /api/index.php/v1/weblinks/{weblink_id}

#### Weblink erstellen

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

#### Weblink aktualisieren

curl -X PUT -H "Content-Type: application/json"
/api/index.php/v1/weblinks/{weblink_id} -d

    {
        "catid": "8",
        "description": "some new text",
        "language": "*",
        "title": "new title",
        "url": "http://newsomelink.com/"
    }

### Kategorien

Die Route zu den Weblinks-Kategorien ist: "v1/weblinks/categories"

Die Arbeitsweise ist vergleichbar mit:
[Banner-Kategorien](https://docs.joomla.org/J4.x:Joomla_Core_APIs#Kategorien "Special:MyLanguage/J4.x:Joomla Core APIs").

## Felder

Die Route zu den Weblinks-Feldern ist: "v1/fields/weblinks"

Die Arbeitsweise ist vergleichbar mit:
[Kontakt-Felder](https://docs.joomla.org/J4.x:Joomla_Core_APIs#Kontakt-Felder "Special:MyLanguage/J4.x:Joomla Core APIs").

### Gruppenfelder

Die Route zu den Weblinks-Gruppenfeldern ist:
"v1/fields/groups/weblinks"

Die Arbeitsweise ist vergleichbar mit:
[Kontakt-Feldgruppen](https://docs.joomla.org/J4.x:Joomla_Core_APIs#Kontakt-Feldgruppen "Special:MyLanguage/J4.x:Joomla Core APIs")
