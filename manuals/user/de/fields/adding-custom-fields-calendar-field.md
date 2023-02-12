<!-- Filename: J3.x:Adding_custom_fields/Calendar_Field / Display title: Anwendung von Eigene Felder / Kalender-Feld -->

## Kalender-Feld

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

## Das Kalender-Feld

Stellt ein Textfeld für die Eingabe eines Datums zur Verfügung. Neben
dem Textfeld ist ein Icon zum öffnen eines Popup-Kalenders. Dieser kann
zur Auswahl des Datums genutzt werden.

#### Optionen

Wenn das Standarddatum genutzt wird: Der Wert kann ISO 8601 Format
(JJJJ-MM-TT HH:MM:SS) oder NOW sein, welches das aktuelle Datum
anzeigt.  
**Achtung**: Wurde im Standarddatum keine Zeit angeben, aber die Option
*Uhrzeit anzeigen* ist aktiviert, wird die Uhrzeit trotzdem angezeigt.  
Spezielle Optionen des Feldes sind:

- Uhrzeit anzeigen  
  Wenn aktiviert, erwartet das Kalenderfeld ein Datum und Uhrzeit und
  wird auch die Zeit anzeigen. Das Format ist lokalisiert und verwendet
  bei der Ausgabe das Format der regulären Sprachdateien.

#### Zugehörige Informationen

Siehe:

- [Kalender Formular
  Feldtyp](https://docs.joomla.org/Calendar_form_field_type "Special:MyLanguage/Calendar form field type")
- <a href="http://php.net/manual/de/datetime.formats.date.php"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">Datums-Formate</a>

#### Screenshots

##### Feld erstellen

Als Beispiel erstellen wir ein Feld mit den Optionen wie im nächsten
Bild gezeigt.

<img
src="https://docs.joomla.org/images/thumb/f/f9/Calendar_field_create-de.png/670px-Calendar_field_create-de.png.jpeg"
decoding="async"
srcset="https://docs.joomla.org/images/f/f9/Calendar_field_create-de.png 1.5x"
data-file-width="800" data-file-height="561" width="670" height="470"
alt="Calendar field create-de.png" />

##### Nutzung des Feldes im Backend

Im Backend wird während der Erstellung oder Bearbeitung eines Beitrages
(oder auch Kontaktes) das Feld wie im folgenden Bild angezeigt:

<img
src="https://docs.joomla.org/images/thumb/9/92/Calendar-de.png/670px-Calendar-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/9/92/Calendar-de.png 1.5x"
data-file-width="800" data-file-height="687" width="670" height="575"
alt="Calendar-de.png" />

##### Nutzung des Feldes im Frontend

Im Frontend wird das Faled angezeigt wie im folgenden Bild zu sehen. Die
Option *Automatische Anzeige* gibt die Position des Feldes an und das
Template bestimmt das Design des Feldes.  
Felderinhalte werden nur im Frontend angezeigt, wenn es im Beitrag mit
Daten gefüllt wurde. Das Feld kann auch als Pflichtfeld deklariert
werden, dann vergisst man auch nicht das Ausfüllen.

<img
src="https://docs.joomla.org/images/thumb/4/43/Calendar_field_frontend-de.png/670px-Calendar_field_frontend-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/4/43/Calendar_field_frontend-de.png 1.5x"
data-file-width="800" data-file-height="494" width="670" height="414"
alt="Calendar field frontend-de.png" />

<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Parameters_for_all_Custom_Fields"
id="content-button" class="button expand success">Zurück: Parameter für
alle Felder</a> <a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Checkboxes_Field"
id="content-button" class="button expand">Weiter: Checkbox Feld</a>
