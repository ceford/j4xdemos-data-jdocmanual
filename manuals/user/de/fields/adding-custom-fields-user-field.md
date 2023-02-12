<!-- Filename: J3.x:Adding_custom_fields/User_Field / Display title: Benutzer Feld -->

## Benutzer-Feld

**Artikel in dieser Serie**

1.  [Einführung](https://docs.joomla.org/J3.x:Adding_custom_fields "Special:MyLanguage/J3.x:Adding custom fields")
2.  [Parameter für alle Eigenen
    Felder](https://docs.joomla.org/J3.x:Adding_custom_fields/Parameters_for_all_Custom_Fields "Special:MyLanguage/J3.x:Adding custom fields/Parameters for all Custom Fields")
3.  [Kalender-Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field "Special:MyLanguage/J3.x:Adding custom fields/Calendar Field")
4.  [Kontrollkästchen-Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/Checkboxes_Field "Special:MyLanguage/J3.x:Adding custom fields/Checkboxes Field")
5.  [Farbe
    Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/Color_Field "Special:MyLanguage/J3.x:Adding custom fields/Color Field")
6.  [Editor
    Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/Editor_Field "Special:MyLanguage/J3.x:Adding custom fields/Editor Field")
7.  [Zahlen
    Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/Integer_Field "Special:MyLanguage/J3.x:Adding custom fields/Integer Field")
8.  [Listen
    Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/List_Field "Special:MyLanguage/J3.x:Adding custom fields/List Field")
9.  [Bilder-Listen
    Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/ListOfImages_Field "Special:MyLanguage/J3.x:Adding custom fields/ListOfImages Field")
10. [Medien
    Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/Media_Field "Special:MyLanguage/J3.x:Adding custom fields/Media Field")
11. [Optionsfeld
    (radio)](https://docs.joomla.org/J3.x:Adding_custom_fields/Radio_Field "Special:MyLanguage/J3.x:Adding custom fields/Radio Field")
12. [Repeatable
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Repeatable_Field "Special:MyLanguage/J3.x:Adding custom fields/Repeatable Field")
13. [Sql
    Feld](https://docs.joomla.org/J3.x:Adding_custom_fieldshttps://docs.joomla.org/J3.x:Adding%20custom%20fields/Sql%20Field)
14. [Textfeld](https://docs.joomla.org/J3.x:Adding_custom_fields/Text_Field "Special:MyLanguage/J3.x:Adding custom fields/Text Field")
15. [Textbereich
    Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/Textarea_Field "Special:MyLanguage/J3.x:Adding custom fields/Textarea Field")
16. [URL
    Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/Url_Field "Special:MyLanguage/J3.x:Adding custom fields/Url Field")
17. [Benutzer
    Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/User_Field "Special:MyLanguage/J3.x:Adding custom fields/User Field")
18. [Benutzergruppe
    Feld](https://docs.joomla.org/J3.x:Adding_custom_fields/Usergroup_Field "Special:MyLanguage/J3.x:Adding custom fields/Usergroup Field")
19. [Wie man die Eigenen Felder
    gruppiert](https://docs.joomla.org/J3.x:Adding_custom_fields/How%CC%9E_can_you_group_custom_fields "Special:MyLanguage/J3.x:Adding custom fields/How̞ can you group custom fields")
20. [Welche Komponenten unterstützen die Eigenen
    Felder](https://docs.joomla.org/J3.x:Adding_custom_fields/What_components_are_supporting_custom_fields "Special:MyLanguage/J3.x:Adding custom fields/What components are supporting custom fields")
21. [Implementierung in der eigenen
    Komponente](https://docs.joomla.org/J3.x:Adding_custom_fields/Implement_into_your_component "Special:MyLanguage/J3.x:Adding custom fields/Implement into your component")
22. [Eigene Felder in Overrides
    anwenden](https://docs.joomla.org/J3.x:Adding_custom_fields/Overrides "Special:MyLanguage/J3.x:Adding custom fields/Overrides")

### Benutzer

Dieser Feld-Typ stellt ein Auswahl eines Benutzers in einer Modal-Liste
zur Verfügung. Das Feld zeigt den Benutzernamen und speichert die
Benutzer-ID.

#### Optionen

Gibt es keine speziellen Optionen in diesem Bereich.

#### Zugehörige Informationen

Siehe [Benutzer
Formular-Feld-Typ](https://docs.joomla.org/User_form_field_type "Special:MyLanguage/User form field type")

#### Screenshots

##### Feld erstellen

Als Beispiel erstellen wir ein Feld mit den Optionen wie im nächsten
Bild gezeigt.

<img
src="https://docs.joomla.org/images/thumb/1/1f/User_field_create-en.png/800px-User_field_create-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/1f/User_field_create-en.png/1200px-User_field_create-en.png 1.5x, https://docs.joomla.org/images/1/1f/User_field_create-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="User field create-en.png" />

##### Nutzung des Feldes im Backend

Im Backend wird während der Erstellung oder Bearbeitung eines Beitrages
(oder auch Kontaktes) das Feld wie im folgenden Bild angezeigt:

<img
src="https://docs.joomla.org/images/thumb/7/71/User-en.png/800px-User-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/71/User-en.png/1200px-User-en.png 1.5x, https://docs.joomla.org/images/7/71/User-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="User-en.png" />

Und wenn Du darauf klickst, öffnet sich ein modales Fenster, in dem man
einen Benutzer auswählen kann.

<img
src="https://docs.joomla.org/images/thumb/1/1a/User_2-en.png/800px-User_2-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/1a/User_2-en.png/1200px-User_2-en.png 1.5x, https://docs.joomla.org/images/1/1a/User_2-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="User 2-en.png" />

##### Nutzung des Feldes im Frontend

Im Frontend wird das Feld angezeigt wie im folgenden Bild zu sehen. Die
Option *Automatische Anzeige* gibt die Position des Feldes an und das
Template bestimmt das Design des Feldes.  
Felderinhalte werden nur im Frontend angezeigt, wenn es im Beitrag mit
Daten gefüllt wurde. Das Feld kann auch als Pflichtfeld deklariert
werden, dann vergisst man auch nicht das Ausfüllen.

<img
src="https://docs.joomla.org/images/thumb/e/e5/User_field_frontend-en.png/800px-User_field_frontend-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/e5/User_field_frontend-en.png/1200px-User_field_frontend-en.png 1.5x, https://docs.joomla.org/images/e/e5/User_field_frontend-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="User field frontend-en.png" />

<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/Url_Field"
id="content-button" class="button expand success">Zurück: URL Feld</a>
<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Usergroup_Field"
id="content-button" class="button expand">Weiter: Benutzergruppen
Feld</a>
