<!-- Filename: Help4.x:Articles:_Edit / Display title: Beiträge: Bearbeiten -->

## Beschreibung

Diese Seite dient zum Hinzufügen eines neuen oder Bearbeiten eines
bestehenden Beitrags, üblicherweise mit einem Wysiwyg-Editor. Der
Standardeditor ist TinyMCE, falls jedoch andere Editoren installiert
sind, kann der Standardeditor für die Site als Ganzes oder für einzelne
Benutzer geändert werden.

Die meisten Parameter haben die geeigneten Standardwerte, aber es könnte
sein, dass eine bestimmte Kategorie oder beitragsspezifische Metadaten
festgelegt werden sollen.

## Wie darauf zugreifen

**Inhalt **→** Beiträge**

Einen Beitrag hinzufügen:

- auf den Button **Neu** der Werkzeugleiste klicken.

Einen Beitrag bearbeiten:

- einen **Titel** aus der Liste wählen.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/c/c8/Help-4x-content-article-manager-add-new-article-de.png/800px-Help-4x-content-article-manager-add-new-article-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c8/Help-4x-content-article-manager-add-new-article-de.png/1200px-Help-4x-content-article-manager-add-new-article-de.png 1.5x, https://docs.joomla.org/images/thumb/c/c8/Help-4x-content-article-manager-add-new-article-de.png/1600px-Help-4x-content-article-manager-add-new-article-de.png 2x"
data-file-width="2880" data-file-height="1584" width="800" height="440"
alt="Help-4x-content-article-manager-add-new-article-de.png" />

## Formular Felder

- **Titel**. Der Titel des Beitrages.
- **Alias**. Der interne Name des Beitrages. Das Feld kann leergelassen
  werden und Joomla wird den Standardwert Titel in Kleinbuchstaben und
  Bindestrichen statt Leerzeichen eintragen. [Mehr
  erfahren.](https://docs.joomla.org/Alias/de "Alias/de")

### Inhalt

**Linke Seite**

- **Beitragsinhalt**. Den Inhalt des Beitrages eingeben. Joomla hat 3
  Editoren, der Standard-[Editor -
  TinyMCE](https://docs.joomla.org/Help4.x:Editors/de#tinymce "Help4.x:Editors/de")
  wird hier gezeigt.

<img
src="https://docs.joomla.org/images/thumb/d/d3/Help-4x-Article-Editor-buttons-de.png/600px-Help-4x-Article-Editor-buttons-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/d3/Help-4x-Article-Editor-buttons-de.png/900px-Help-4x-Article-Editor-buttons-de.png 1.5x, https://docs.joomla.org/images/thumb/d/d3/Help-4x-Article-Editor-buttons-de.png/1200px-Help-4x-Article-Editor-buttons-de.png 2x"
data-file-width="1985" data-file-height="758" width="600" height="229"
alt="Help-4x-Article-Editor-buttons-de.png" />

Die Dropdown-Liste 'CMS Inhalt' ermöglicht Links auf einen Beitrag,
Felder, Kontakt, Medien, Menü oder Modul. [Mehr
erfahren.](https://docs.joomla.org/Help4.x:Editors/de#cmscontent "Help4.x:Editors/de")

- **Editor an/aus**. Der Button wird unterhalb des Editor-Fensters
  gezeigt. Damit kann zwischen TinyMCE und [Editor -
  Keiner](https://docs.joomla.org/Help4.x:Editors/de#none "Help4.x:Editors/de")
  gewechselt werden.

**Rechte Seite**

- **Status**. Der Veröffentlichungs-Status des Beitrages.
  - Veröffentlicht: Der Beitrag ist im Frontend der Seite sichtbar.
  - Versteckt: Der Beitrag ist im Frontend der Seite für Besucher nicht
    sichtbar. Für angemeldete Benutzer mit der Berechtigung [„Status
    bearbeiten“](#permissions) ist der Beitrag sichtbar.
  - Archiviert: Der Beitrag wird nicht mehr in
    [Kategorieblog](https://docs.joomla.org/Help4.x:Menu_Item:_Category_Blog/de "Help4.x:Menu Item: Category Blog/de")-
    oder
    [Kategorieliste](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/de "Help4.x:Menu Item: Category List/de")-Menüs
    angezeigt.
  - Papierkorb: Der Beitrag ist gelöscht, befindet sich aber noch in der
    Datenbank. [Mehr
    erfahren.](https://docs.joomla.org/J4.x:Deleting_an_Article/de "J4.x:Deleting an Article/de")
- **Kategorie**. Die Kategorie des Beitrags wählen.
- **Hauptbeitrag**. 'Ja' wählen, um den Beitrag in einem Menüeintrag
  [Hauptbeiträge](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/de "Help4.x:Menu Item: Featured Articles/de")
  anzuzeigen.
- **Zugriffsebene**. Die Zugriffsebene des Beitrags wählen. Sie werden
  in [Benutzer:
  Zugriffsebenen](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/de "Help4.x:Users: Viewing Access Levels/de")
  eingerichtet.
- **Sprache**. Die Sprache des Beitrags wählen. Den Standard 'Alle'
  beibehalten, wenn
  [Mehrsprachigkeit](https://docs.joomla.org/Help4.x:Extensions:_Languages/de "Help4.x:Extensions: Languages/de")
  nicht verwendet wird.
- **Schlagwörter**. Dem Beitrag Schlagwörter zuordnen. Dazu ein
  Schlagwort aus einer [vordefinierten
  Liste](https://docs.joomla.org/Help4.x:Tags/de "Help4.x:Tags/de")
  wählen oder ein neues Schlagwort im Feld eingeben und 'Eingabe'
  drücken.
- **Notiz**. Die Notiz wird meist vom Administrator verwendet, um zum
  Beispiel Informationen über den Beitrag zu notieren. Die Notiz wird
  nicht im Frontend gezeigt.
- **Versionshinweis**. Optionales Feld, um diese Version des Beitrages
  im
  [Versionsverlauf](https://docs.joomla.org/Help4.x:Components_Version_History/de "Help4.x:Components Version History/de")
  zu identifizieren.

### Bilder und Links

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in [Beiträge:
Optionen](https://docs.joomla.org/Help4.x:Articles:_Options/de "Help4.x:Articles: Options/de")
ausgeblendet werden.  
Dieser Teil zeigt in Beiträgen, Bilder und Links in standardisierten
Layouts.

<img
src="https://docs.joomla.org/images/thumb/6/61/Help-4x-screenshot-article-edit-images-links-de.png/600px-Help-4x-screenshot-article-edit-images-links-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/61/Help-4x-screenshot-article-edit-images-links-de.png/900px-Help-4x-screenshot-article-edit-images-links-de.png 1.5x, https://docs.joomla.org/images/thumb/6/61/Help-4x-screenshot-article-edit-images-links-de.png/1200px-Help-4x-screenshot-article-edit-images-links-de.png 2x"
data-file-width="2880" data-file-height="1166" width="600" height="243"
alt="Help-4x-screenshot-article-edit-images-links-de.png" />

**Einleitungsbild**

- **Einleitungsbild**. Auf den Auswählen-Button klicken, um das Bild an
  eine fixen Stelle im Einleitungstext des Beitrages anzuzeigen. Ein
  Fenster wird geöffnet, in dem ein Bild aus dem Bilder-Verzeichnis
  gewählt wird. [Mehr
  erfahren.](https://docs.joomla.org/Adding_an_image_to_an_article/de "Adding an image to an article/de")
- **Bildbeschreibung (Alternativer Text)**. Das Alt-Attribut für das
  Bild mit einigen beschreibenden Wörtern für Screenreader festlegen.
- **Keine Beschreibung**. Im seltenen Fall eines rein dekorativen Bildes
  markieren. Das Bild erfüllt nicht die Barrierefreiheit, wenn
  'Bildbeschreibung (Alternativer Text)' leer und das Kontrollkästchen
  'Keine Beschreibung' nicht markiert sind. Ist eine Bildbeschreibung
  vorhanden, hat das Kontrollkästchen keine Auswirkung.
- **CSS-Klasse Bild**. Es kann eine beliebige CSS-Klasse für eigene
  Styling-Ideen hinzugefügt werden. Für die Bildposition kann zum
  Beispiel „float-start“ und „float-end“ verwendet werden.
  <a href="https://cassiopeia.joomla.com/help" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">Mehr erfahren.</a>
- **Bildunterschrift**. Eine Bildunterschrift für das Bild eingeben.

**Komplettes Beitragsbild**

- **Komplettes Beitragsbild**. Auf den Auswählen-Button klicken, um das
  Bild an eine fixen Stelle des Beitrages anzuzeigen. Ein Fenster wird
  geöffnet, in dem ein Bild aus dem Bilder-Verzeichnis gewählt wird.
  [Mehr
  erfahren.](https://docs.joomla.org/Adding_an_image_to_an_article/de "Adding an image to an article/de")
- **Bildbeschreibung (Alternativer Text)**. Das Alt-Attribut für das
  Bild mit einigen beschreibenden Wörtern für Screenreader festlegen.
- **Keine Beschreibung**. Im seltenen Fall eines rein dekorativen Bildes
  markieren. Das Bild erfüllt nicht die Barrierefreiheit, wenn
  'Bildbeschreibung (Alternativer Text)' leer und das Kontrollkästchen
  'Keine Beschreibung' nicht markiert sind. Ist eine Bildbeschreibung
  vorhanden, hat das Kontrollkästchen keine Auswirkung.
- **CSS-Klasse Bild**. Es kann eine beliebige CSS-Klasse für eigene
  Styling-Ideen hinzugefügt werden. Für die Bildposition kann zum
  Beispiel „float-start“ und „float-end“ verwendet werden.
  <a href="https://cassiopeia.joomla.com/help" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">Mehr erfahren.</a>
- **Bildunterschrift**. Eine Bildunterschrift für das Bild eingeben.

**Link A**

- **Link A**. Die URL des ersten Links, der an einer fixen Stelle eines
  Beitrages angezeigt wird. Es muß eine absolute, keine relative URL
  sein. Zum Beispiel beginnt sie mit 'https://'.
- **Linktext A**. Der Text des Link A. Wenn leer, wird die URL
  angezeigt.
- **URL-Zielfenster**. Bestimmt den Standard-Wert für das Ziel des
  ersten Links im Beitrag. Zur Auswahl stehen:
  - In gleichem Fenster öffnen: Öffnet den Link im gleichen
    Browser-Fenster und ersetzt den aktuellen Joomla-Beitrag.
  - In neuem Fenster öffnen: Öffnet den Link in einem neuen
    Browser-Fenster.
  - Als Pop-up-Fenster öffnen: Öffnet den Link in einem
    Pop-up-Browser-Fenster (ohne Navigations-Elementen).
  - Modalfenster: Öffnet den Link in einem Modal-Pop-up-Browser-Fenster.

**Link B**, **Link C**: Dieselben Optionen wie Link A.

### Optionen

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in [Beiträge:
Optionen](https://docs.joomla.org/Help4.x:Articles:_Options/de "Help4.x:Articles: Options/de")
ausgeblendet werden.  
Optionen, um das Aussehen eines Beitrages im Frontend einzustellen.

<img
src="https://docs.joomla.org/images/thumb/1/15/Help-4x-screenshot-article-edit-article-options-de.png/600px-Help-4x-screenshot-article-edit-article-options-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/15/Help-4x-screenshot-article-edit-article-options-de.png/900px-Help-4x-screenshot-article-edit-article-options-de.png 1.5x, https://docs.joomla.org/images/thumb/1/15/Help-4x-screenshot-article-edit-article-options-de.png/1200px-Help-4x-screenshot-article-edit-article-options-de.png 2x"
data-file-width="2880" data-file-height="1168" width="600" height="243"
alt="Help-4x-screenshot-article-edit-article-options-de.png" />

**Layout**

- **Layout**. Unterschiedliche Layouts der Beitragsansicht oder
  [Override im
  Template](https://docs.joomla.org/Help4.x:Templates:_Customise/de "Help4.x:Templates: Customise/de")
  wählen.
- **Titel**. Den Titel des Beitrages zeigen.
- **Titel verlinken**. Den Titel als Link zeigen.
- **Schlagwörter anzeigen**. Ein oder mehrere Schlagwörter für den
  Beitrag eingeben. Man kann vorhandene Schlagwörter nach Eingabe der
  ersten Buchstaben auswählen oder neue Schlagwörter eingeben. [Mehr
  erfahren.](https://docs.joomla.org/J4.x:How_To_Use_Content_Tags_in_Joomla/de "J4.x:How To Use Content Tags in Joomla/de")
- **Einleitungstext**.
  - Anzeigen: Der Beitrag wird inklusive Einleitungstext gezeigt.
  - Verbergen: Der Beitrag wird ohne Einleitungstext gezeigt.
- **Position der Beitragsinfo**.
  - Darüber: Der Block mit den Beitragsinformationen steht oberhalb des
    Beitrags.
  - Darunter: Der Block mit den Beitragsinformationen steht unterhalb
    des Beitrags.
  - Aufteilen: Die Beitragsinformationen werden in einen Block oberhalb
    und einen Block unterhalb des Beitrags aufgeteilt.
- **Beitragsinfotitel**. Zeigt 'Details' über dem Block der
  Beitragsinformation an.

**Kategorie**

- **Kategorie**. Den Kategorietitel des Beitrags zeigen.
- **Kategorie verlinken**. Den Kategorietitel als Link zeigen.
- **Übergeordnete Kategorie**. Den Titel der übergeordneten Kategorie
  des Beitrages zeigen.
- **Übergeordnete Kategorie verlinken**. Den Kategorietitel als Link
  zeigen.

**Verknüpfungen**

- **Verknüpfungen**. Zeigt verknüpfte Flaggen oder den Sprachcode. [Nur
  bei mehrsprachigen
  Seiten](https://docs.joomla.org/Help4.x:Multilingual_Associations/de "Help4.x:Multilingual Associations/de").

**Autor**

- **Autor**. Zeigt den Autor des Beitrags.
- **Autor verlinken**. Zum Kontakt des Autors verlinken.Hinweis: Der
  Autor muss [als
  Kontakt](https://docs.joomla.org/Help4.x:Contacts/de "Help4.x:Contacts/de")
  angelegt sein.

**Datum**

- **Erstellungsdatum**. Das Erstellungsdatum des Beitrages zeigen.
- **Bearbeitungsdatum**. Das Bearbeitungsdatum des Beitrages zeigen.
- **Veröffentlichungsdatum**. Das Veröffentlichungsdatum des Beitrages
  zeigen.

**Optionen**

- **Seitennavigation**. Zeigt die Navigationslinks 'Zurück' oder
  'Weiter', wenn der Beitrag gezeigt wird.
- **Zugriffe**. Zeigt, wie oft der Beitrag von Benutzern aufgerufen
  wurde.
- **Nicht zugängliche Links**. Ja: Der Einleitungstext wird angezeigt.
  Nach Klick auf den Link "Weiterlesen" muss sich der Besucher anmelden,
  um den vollständigen Beitrag zu sehen.
- **Linkpositionierung.**
  - Darüber: Links werden oberhalb des Inhalts angezeigt.
  - Darunter: Links werden unterhalb des Inhalts angezeigt.
- **Eigener "Weiterlesen"-Text**. Einen eigenen Text anstelle von
  'Weiterlesen' zeigen.
- **Seitentitel im Browser**. Text für den 'Seitentitel im Browser',
  wenn der Beitrag nicht mit einem Beitrags-Menü anzeigt wird. Ist das
  Feld leer, wird der Titel des Beitrags verwendet.

### Felder

Dieser Teil zeigt für den Beitrag definierte
[Felder](https://docs.joomla.org/Help4.x:Fields/de "Help4.x:Fields/de").

<img
src="https://docs.joomla.org/images/thumb/1/1a/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-de.png/600px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/1a/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-de.png/900px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/1/1a/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-de.png/1200px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-de.png 2x"
data-file-width="2880" data-file-height="658" width="600" height="137"
alt="Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-de.png" />

### Veröffentlichung

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in [Beiträge:
Optionen](https://docs.joomla.org/Help4.x:Articles:_Options/de "Help4.x:Articles: Options/de")
ausgeblendet werden.  
Dieser Teil erlaubt die Eingabe von Parametern und
[Metadaten](https://docs.joomla.org/Using_The_Meta_Description/de "Using The Meta Description/de")
des Beitrages.

<img
src="https://docs.joomla.org/images/thumb/6/68/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-de.png/600px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/68/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-de.png/900px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/6/68/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-de.png/1200px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-de.png 2x"
data-file-width="2880" data-file-height="1167" width="600" height="243"
alt="Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-de.png" />

**Veröffentlichung**

- **Veröffentlichung starten**. Datum und Uhrzeit, um die
  Veröffentlichung zu starten. Der Beitrag kann vor der Zeit erstellt
  und später automatisch veröffentlicht werden.
- **Veröffentlichung beenden**. Datum und Uhrzeit, um die
  Veröffentlichung zu beenden. Dem Beitrag wird automatisch der Status
  'Versteckt' zugewiesen.
- **Hauptbeitrag von**. Datum und Uhrzeit, um die Veröffentlichung als
  Hauptbeitrag zu starten. Der Beitrag kann vor der Zeit erstellt und
  später automatisch als Hauptbeitrag definiert werden.
- **Hauptbeitrag bis**. Datum und Uhrzeit, um die Veröffentlichung als
  Hauptbeitrag zu beenden. Den Beitrag vor der Zeit erstellen und später
  automatisch den Status als Hauptbeitrag entziehen.
- **Erstellungsdatum**. Das Erstellungsdatum des Beitrages. Ein anderes
  Datum oder Uhrzeit eingeben oder auf das Kalender-Symbol klicken.
- **Autor**. Der Name des Benutzers, der den Beitrag erstellt hat.
  Standard ist der aktuell eingewählte Benutzer. Um einen anderen
  Benutzer auszuwählen, auf den Button 'Benutzer auswählen' klicken.
- **Autoralias**. Einen Alias für den Autor dieses Beitrags eingeben.
  Ein anderer Autorennamen wird für diesen Beitrag angezeigt.
- **Bearbeitungsdatum**. Datum der letzten Bearbeitung.
- **Bearbeitet von**. Benutzer, der die letzte Bearbeitung ausgeführt
  hat.
- **Überarbeitung**. Anzahl der Überarbeitungen des Beitrags.
- **Zugriffe**. Anzahl der Aufrufe eines Beitrags.
- **ID**. Einmalig vergebene Identifikations-Nummer für den Beitrag, die
  nicht geändert werden kann. Beim Erstellen eines neuen Beitrags zeigt
  das Feld „0“ an, bis man speichert.

**Metadaten**

- **Meta-Beschreibung**. Ein Absatz zur Beschreibung der Seite. [Mehr
  erfahren.](https://docs.joomla.org/Using_The_Meta_Description/de "Using The Meta Description/de")
- **Schlüsselwörter**. Eintrag für Schlüsselwörter. [Mehr
  erfahren.](https://docs.joomla.org/Using_Keywords/de "Using Keywords/de")
- **Robots**. Anweisungen für Web-'Robots', die diese Seite durchsuchen.
  „Globale Einstellung“ in
  [Konfiguration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/de#robots "Help4.x:Site Global Configuration/de")
  einstellen.
- **Autor**. Eintrag des Autorennamens in den Metadaten.
- **Inhaltsrechte**. Legt fest, welche Rechte andere Personen beim
  Gebrauch dieses Beitragsinhalts haben.

### Verknüpfungen

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in [Beiträge:
Optionen](https://docs.joomla.org/Help4.x:Articles:_Options/de "Help4.x:Articles: Options/de")
ausgeblendet werden.  
Der Tab wird nur bei [Mehrsprachigen
Seiten](https://docs.joomla.org/Help4.x:Multilingual_Associations/de "Help4.x:Multilingual Associations/de")
gezeigt.

<img
src="https://docs.joomla.org/images/thumb/1/12/Help-4x-screenshot-article-edit-associations-de.png/600px-Help-4x-screenshot-article-edit-associations-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/12/Help-4x-screenshot-article-edit-associations-de.png/900px-Help-4x-screenshot-article-edit-associations-de.png 1.5x, https://docs.joomla.org/images/thumb/1/12/Help-4x-screenshot-article-edit-associations-de.png/1200px-Help-4x-screenshot-article-edit-associations-de.png 2x"
data-file-width="2880" data-file-height="1175" width="600" height="245"
alt="Help-4x-screenshot-article-edit-associations-de.png" />

### Konfigurieren des Editorfensters

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in [Beiträge:
Optionen](https://docs.joomla.org/Help4.x:Articles:_Options/de "Help4.x:Articles: Options/de")
ausgeblendet werden.

<img
src="https://docs.joomla.org/images/thumb/8/86/Help-4x-screenshot-article-edit-configure-edit-screen-de.png/600px-Help-4x-screenshot-article-edit-configure-edit-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/86/Help-4x-screenshot-article-edit-configure-edit-screen-de.png/900px-Help-4x-screenshot-article-edit-configure-edit-screen-de.png 1.5x, https://docs.joomla.org/images/thumb/8/86/Help-4x-screenshot-article-edit-configure-edit-screen-de.png/1200px-Help-4x-screenshot-article-edit-configure-edit-screen-de.png 2x"
data-file-width="2880" data-file-height="987" width="600" height="206"
alt="Help-4x-screenshot-article-edit-configure-edit-screen-de.png" />

- **Veröffentlichungsparameter anzeigen**. Ist 'Verbergen' gewählt, wird
  der Tab
  [Veröffentlichung](https://docs.joomla.org/Help4.x:Articles:_Edit/de#publishing "Help4.x:Articles: Edit/de")
  im Backend nicht gezeigt. Benutzer des Backends können die Felder des
  Tabs nicht bearbeiten. Den Feldern werden immer Standardwerte
  zugeordnet.
- **Beitragseinstellungen anzeigen**. Ist 'Verbergen' gewählt, wird der
  Tab
  [Optionen](https://docs.joomla.org/Help4.x:Articles:_Edit/de#options "Help4.x:Articles: Edit/de")
  im Backend nicht gezeigt. Benutzer des Backends können die Felder des
  Tabs nicht bearbeiten. Den Feldern werden immer Standardwerte
  zugeordnet.
- **Bilder und Links im Backend**. Ist 'Ja' gewählt, wird der Tab
  [Bilder und
  Links](https://docs.joomla.org/Help4.x:Articles:_Edit/de#imagesandlinks "Help4.x:Articles: Edit/de")
  gezeigt.
- **Bilder und Links im Frontend**. Ist 'Ja' gewählt, wird der 'Bilder
  und Links'-Tab im Frontend-Editor des Beitrages angezeigt.

### Berechtigungen

**Hinweis**: Dieser Abschnitt kann von einem Benutzer mit
Administrator-Rechten in [Beiträge:
Optionen](https://docs.joomla.org/Help4.x:Articles:_Options/de "Help4.x:Articles: Options/de")
ausgeblendet werden.  
Hier können die Berechtigungen für den Beitrag eingegeben werden. [Mehr
erfahren.](https://docs.joomla.org/J3.x:Access_Control_List_Tutorial/de#hierarchylevels "J3.x:Access Control List Tutorial/de")

<img
src="https://docs.joomla.org/images/thumb/4/46/Help-4x-screenshot-article-edit-permissions-de.png/600px-Help-4x-screenshot-article-edit-permissions-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/46/Help-4x-screenshot-article-edit-permissions-de.png/900px-Help-4x-screenshot-article-edit-permissions-de.png 1.5x, https://docs.joomla.org/images/thumb/4/46/Help-4x-screenshot-article-edit-permissions-de.png/1200px-Help-4x-screenshot-article-edit-permissions-de.png 2x"
data-file-width="2880" data-file-height="1166" width="600" height="243"
alt="Help-4x-screenshot-article-edit-permissions-de.png" />

Um Berechtigungen dieses Beitrages zu ändern:

1.  Die **Gruppe** durch Anklicken des Namens auf der linken Seite
    auswählen.
2.  Die gewünschte **Aktion** aussuchen.
    - **Löschen**. Benutzer können diesen Beitrag löschen.
    - **Bearbeiten**. Benutzer können diesen Beitrag bearbeiten.
    - **Status bearbeiten**. Benutzer können den Status dieses Beitrags
      ändern.
3.  Die Berechtigungen der gewählten Aktion wählen.
    - **Vererbt**. Berechtigungen für Benutzer der Gruppe werden von der
      [Konfiguration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/de#permissions "Help4.x:Site Global Configuration/de"),
      den
      [Beitrags-Optionen](https://docs.joomla.org/Help4.x:Articles:_Options/de#permissions "Help4.x:Articles: Options/de")
      oder der
      [Beitrags-Kategorie](https://docs.joomla.org/Help4.x:Articles:_Edit_Category/de#permissions "Help4.x:Articles: Edit Category/de")
      vererbt.
    - **Erlaubt**. Für Benutzer dieser Gruppe erlaubt.Hinweis: Wenn die
      Aktion auf einer höheren Ebene 'Verweigert' wird, ist die
      'Erlaubt'-Berechtigung hier dadurch überschrieben. Eine
      'Verweigert'-Einstellung kann nicht überschrieben werden.
    - **Verweigert**. Für Benutzer dieser Gruppe verweigert.
4.  Auf **Speichern** in der **Werkzeugleiste** oben klicken. Danach
    aktualisiert sich die Anzeige, erst dann werden die errechneten
    Einstellungen angezeigt.

## Werkzeugleiste

Das [Bildschirmfoto](#screenshot) zeigt die Werkzeugleiste im oberen
Bereich.

- **Speichern**. Speichert den Beitrag und bleibt auf der aktuellen
  Seite.
- **Speichern & Schließen**. Speichert den Beitrag und schließt die
  aktuelle Seite.
  - **Speichern & Neu**. Speichert den Eintrag und hält die Seite offen,
    damit ein neuer Beitrag erstellt werden kann.
  - **Im Menü speichern**. Speichert den Beitrag in einem Menüeintrag
    und öffnet den Bildschirm für den Menüeintrag.
  - **Als Kopie speichern**. Speichert Änderungen in einer Kopie des
    aktuellen Beitrags. Der aktuelle Beitrag wird davon nicht
    beeinflusst.
- **Schließen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück.
- **Versionen**. Öffnet den Versionsverlauf, der ältere Versionen des
  Beitrags zeigt. Damit können ältere Versionen des Beitrags gezeigt und
  wiederhergestellt werden. [Mehr
  erfahren.](https://docs.joomla.org/Help4.x:Components_Version_History/de "Help4.x:Components Version History/de")
- **Vorschau**. Zeigt die Seitenansicht des Beitrages. Benötigt
  [Gemeinsame
  Sitzungen](https://docs.joomla.org/Help4.x:Site_Global_Configuration/de#sharedsessions "Help4.x:Site Global Configuration/de")
  oder die Anmeldung im Frontend.
- **Barriere-Check**. Öffnet ein Fenster mit den Ergebnissen der
  Barrierefreiheitsprüfung des Beitrags.
- **Verknüpfungen**. Den Beitrag mit seiner festgelegten Sprache
  parallel in einer weiteren Sprache bearbeiten. Dieses Symbol wird nur
  bei [Mehrsprachigen
  Seiten](https://docs.joomla.org/Help4.x:Multilingual_Associations/de "Help4.x:Multilingual Associations/de")
  gezeigt.
- **Inline-Hilfe umschalten**. Hilfetext unter einigen Optionen ein-
  oder ausschalten.
- **Hilfe**. Öffnet die Hilfeseite.

## Tipps

- Es gibt 2 Methoden, um mit dem TinyMCE-Editor ein Bild in einen
  Beitrag einzufügen.
  1.  Die Dropdown-Liste [CMS
      Inhalt](https://docs.joomla.org/Help4.x:Editors/de#cmscontent "Help4.x:Editors/de")
      ermöglicht den Zugriff auf die Seite
      [Medien](https://docs.joomla.org/Help4.x:Media/de "Help4.x:Media/de"),
      in der Bilddateien durchsucht und Bilder hochgeladen werden
      können.
  2.  Die Dropdown-Liste 'Einfügen' öffnet ein einfaches
      Eingabeformular, für das die Bild-URL benötigt wird. Es wird für
      externe Bilder verwendet.
- [Weiterlesen](https://docs.joomla.org/Help4.x:Editors/de#readmore "Help4.x:Editors/de")-Umbrüche
  sparen Platz auf der Startseite und Blog-Layout-Seiten, weil nur der
  erste Teil des Beitrages gezeigt wird. Die
  [Seitennavigation](https://docs.joomla.org/Help4.x:Editors/de#pagebreak "Help4.x:Editors/de")
  teilt lange Beiträge in mehrere Seiten auf. Beides kann im selben
  Beitrag verwendet werden.Zum Beispiel könnte ein 'Weiterlesen'-Umbruch
  nach dem ersten Absatz eines mehrseitigen Artikels eingefügt werden
  und nach jeder Seite ein Seitenumbruch. Auf der Titelseite würde keine
  Seitennavigation angezeigt, bis der Benutzer den Link 'Weiterlesen'
  anklickt. Dann wird das Inhaltsverzeichnis des Artikels mit den Links
  zu den einzelnen Seiten angezeigt.

## Verwandte Informationen

- Dieses
  [Portal](https://docs.joomla.org/Portal:Joomla_4/de "Portal:Joomla 4/de")
  bringt alle Informationen zu Joomla 4 zusammen.

|                                                                                                                                                                             |                                                                                                                                                                                                                |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Verwandte Hilfeseiten                                                                                                                                                       | Beschreibung                                                                                                                                                                                                   |
| [Beiträge: Optionen](https://docs.joomla.org/Help4.x:Articles:_Options/de "Help4.x:Articles: Options/de")                                                                   | Festlegen globaler Standardwerte für Menüeinträge, die Beiträge anzeigen. Diese Werte werden verwendet, wenn in einem Menüeintrag 'Global' als Option ausgewählt wird.                                         |
| [Beiträge](https://docs.joomla.org/Help4.x:Articles/de "Help4.x:Articles/de")                                                                                               | Die Beitragsliste wird verwendet, um Beiträge zu finden, zu markieren, hinzuzufügen und zu bearbeiten.                                                                                                         |
| <span class="mw-selflink selflink">Beiträge: Bearbeiten</span>                                                                                                              | Hier werden Beiträge hinzugefügt und bearbeitet. Außerdem lässt sich die Kategorie für einen Beitrag auswählen und festlegen, ob er veröffentlicht wird und auf der Startseite erscheint.                      |
| [Beiträge: Hauptbeiträge](https://docs.joomla.org/Help4.x:Articles:_Featured/de "Help4.x:Articles: Featured/de")                                                            | Dient zur Steuerung, welche 'Hauptbeiträge' in welcher Reihenfolge auf der Startseite angezeigt werden.                                                                                                        |
| [Beiträge: Kategorien](https://docs.joomla.org/Help4.x:Articles:_Categories/de "Help4.x:Articles: Categories/de")                                                           | Die Liste der Beitragskategorien wird verwendet, um Kategorien für Beiträge zu finden, hinzuzufügen und zu bearbeiten.                                                                                         |
| [Menü: Archivierte Beiträge](https://docs.joomla.org/Help4.x:Menu_Item:_Article_Archived/de "Help4.x:Menu Item: Article Archived/de")                                       | Zeigt eine angepasste Liste nach Datum oder Titel geordneter Beiträge. Archivierte Beiträge sind nicht mehr veröffentlicht, bleiben aber auf der Website gespeichert.                                          |
| [Menü: Kategorieblog](https://docs.joomla.org/Help4.x:Menu_Item:_Category_Blog/de "Help4.x:Menu Item: Category Blog/de")                                                    | Zeigt Beiträge einer Kategorie im Blog-Layout. Steuert führende und einleitende Beiträge sowie zusätzliche Links zu Beiträgen.                                                                                 |
| [Menü: Kategorieliste](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/de "Help4.x:Menu Item: Category List/de")                                                   | Zeigt eine Liste von Beiträgen einer Kategorie in einem Listenlayout an.                                                                                                                                       |
| [Menü: Beitrag erstellen](https://docs.joomla.org/Help4.x:Menu_Item:_Create_Article/de "Help4.x:Menu Item: Create Article/de")                                              | Ermöglicht es Benutzern, einen Beitrag zu verfassen. Normalerweise steht dies nur angemeldeten Benutzern im Frontend der Website zur Verfügung. Benutzer müssen die Berechtigung haben, Beiträge zu erstellen. |
| [Menü: Hauptbeiträge](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/de "Help4.x:Menu Item: Featured Articles/de")                                            | Dient zur Anzeige der als 'Hauptbeiträge' markierten Beiträge. Die Beiträge werden in einem Blog-Layout angezeigt.                                                                                             |
| [Menü: Alle Kategorien in einer Beitragskategorie auflisten](https://docs.joomla.org/Help4.x:Menu_Item:_List_All_Categories/de "Help4.x:Menu Item: List All Categories/de") | Dient zur Anzeige einer hierarchischen Liste von Kategorien. Je nach den gewählten Optionen für dieses Format kann man auf den Namen einer Kategorie klicken, um die Beiträge in dieser Kategorie anzuzeigen.  |
| [Menü: Einzelner Beitrag](https://docs.joomla.org/Help4.x:Menu_Item:_Single_Article/de "Help4.x:Menu Item: Single Article/de")                                              | Dient zur Anzeige eines einzelnen Beitrags.                                                                                                                                                                    |
