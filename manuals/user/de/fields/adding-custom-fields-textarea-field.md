<!-- Filename: J3.x:Adding_custom_fields/Textarea_Field / Display title: Textbereich Feld -->

## Textbereich-Feld

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

### Textbereich

Dieser Feld-Typ stellt einen Textbereich für die Eingabe von
mehrzeiligem Text zur Verfügung.

#### Optionen

Spezielle Optionen in diesem Feld sind:

- Zeilen  
  Die Höhe des sichtbaren Textbereichs in Zeilen. Wenn keine Angabe
  gemacht wird, gilt die Browsereinstellung. Dieser Wert hat keinen
  Einfluss auf die Anzahl der Zeichen, die in das Feld eingegeben werden
  können. Die Zeilen sind im Backend aktiv wenn Du einen Artikel, einen
  Kontakt oder eine Komponente eines Drittherstellers mit
  Felder-Unterstützung verwendest. Diese Option hat keinen Einfluss auf
  die Größe des Feldes im Frontend.
- Spalten  
  Die Breite des sichtbaren Textbereichs in Spalten. Wenn keine Angabe
  gemacht wird, gilt die Browsereinstellung. Dieser Wert hat keinen
  Einfluss auf die Anzahl der Zeichen, die in das Feld eingegeben werden
  können. Die Spalten sind im Backend aktiv wenn Du einen Artikel, einen
  Kontakt oder eine Komponente eines Drittherstellers mit
  Felder-Unterstützung verwendest. Diese Option hat keinen Einfluss auf
  die Größe des Feldes im Frontend.
- Maximale Länge  
  Die maximale Anzahl an Zeichen, die eingegeben werden können.
- Filter  
  Dem System erlauben, bestimmte HTML-Tags oder ungefilterte Eingaben zu
  speichern.

#### Zugehörige Informationen

Siehe [Textbereich
Formular-Feld-Typ](https://docs.joomla.org/Textarea_form_field_type "Special:MyLanguage/Textarea form field type")

#### Screenshots

##### Feld erstellen

Als Beispiel erstellen wir ein Feld mit den Optionen wie im nächsten
Bild gezeigt.

<img
src="https://docs.joomla.org/images/thumb/e/ec/Textarea_field_create-de.png/800px-Textarea_field_create-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/ec/Textarea_field_create-de.png/1200px-Textarea_field_create-de.png 1.5x, https://docs.joomla.org/images/e/ec/Textarea_field_create-de.png 2x"
data-file-width="1291" data-file-height="800" width="800" height="496"
alt="Textarea field create-de.png" />

##### Nutzung des Feldes im Backend

Im Backend wird während der Erstellung oder Bearbeitung eines Beitrages
(oder auch Kontaktes) das Feld wie im folgenden Bild angezeigt:

<img
src="https://docs.joomla.org/images/thumb/d/dc/Textarea-en.png/800px-Textarea-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/dc/Textarea-en.png/1200px-Textarea-en.png 1.5x, https://docs.joomla.org/images/d/dc/Textarea-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Textarea-en.png" />

##### Nutzung des Feldes im Frontend

Im Frontend wird das Feld angezeigt wie im folgenden Bild zu sehen. Die
Option *Automatische Anzeige* gibt die Position des Feldes an und das
Template bestimmt das Design des Feldes.  
Felderinhalte werden nur im Frontend angezeigt, wenn es im Beitrag mit
Daten gefüllt wurde. Das Feld kann auch als Pflichtfeld deklariert
werden, dann vergisst man auch nicht das Ausfüllen.

<img
src="https://docs.joomla.org/images/thumb/4/4e/Textarea_field_frontend-en.png/800px-Textarea_field_frontend-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/4e/Textarea_field_frontend-en.png/1200px-Textarea_field_frontend-en.png 1.5x, https://docs.joomla.org/images/4/4e/Textarea_field_frontend-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Textarea field frontend-en.png" />

<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/Text_Field"
id="content-button" class="button expand success">Zurück: Textfeld</a>
<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/Url_Field"
id="content-button" class="button expand">Weiter: URL Feld</a>
