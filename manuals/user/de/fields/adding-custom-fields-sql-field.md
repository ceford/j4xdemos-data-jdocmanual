<!-- Filename: J3.x:Adding_custom_fields/Sql_Field / Display title: SQL-Feld -->

## SQL-Feld

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

### SQL

Dieses Feld bietet eine Dropdown Liste aus Einträgen aus aus einer
Abfrage aus der Joomla! Datenbank. Die ersten Abfrageergebnisse aus der
Abfrage werden als Optionen in einer Dropdown Liste angezeigt.

#### Optionen

Spezielle Optionen in diesem Bereich sind:

- Mehrfachauswahl  
  Erlaubt die Mehrfachauswahl - falls aktiviert.
- Abfrage  
  Die SQL-Abfrage, die die Daten für die Dropdown-Liste liefert. Die
  Abfrage muss zwei Spalten zurückgeben; eine mit dem Namen"value", die
  die Werte der Listenelemente enthält; die andere mit dem Namen"text",
  die den Text in der Dropdown-Liste enthält.

#### Zugehörige Informationen

Siehe [SQL
Formular-Feld-Typ](https://docs.joomla.org/SQL_form_field_type "Special:MyLanguage/SQL form field type")

#### Screenshots

##### Feld erstellen

Als Beispiel erstellen wir ein Feld mit den Optionen wie im nächsten
Bild gezeigt.

<img
src="https://docs.joomla.org/images/thumb/c/cf/Sql_field_create-en.png/800px-Sql_field_create-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/cf/Sql_field_create-en.png/1200px-Sql_field_create-en.png 1.5x, https://docs.joomla.org/images/c/cf/Sql_field_create-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Sql field create-en.png" />

##### Nutzung des Feldes im Backend

Im Backend wird während der Erstellung oder Bearbeitung eines Beitrages
(oder auch Kontaktes) das Feld wie im folgenden Bild angezeigt:

<img
src="https://docs.joomla.org/images/thumb/4/4a/Sql-en.png/800px-Sql-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/4a/Sql-en.png/1200px-Sql-en.png 1.5x, https://docs.joomla.org/images/4/4a/Sql-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Sql-en.png" />

##### Nutzung des Feldes im Frontend

Im Frontend kannst du das Feld wie im nachfolgenden Bild sehen. Die
Option "Automatische Anzeige" ist für die Position des Feldes
verantwortlich und dein Template ist für die Gestaltung des Feldes
verantwortlich.  
Felder sind nur sichtbar im Frontend, wenn du diese auch mit Daten im
Artikel befüllt hast. Wenn es kein Pflichtfeld ist, können Sie es
vergessen?

<img
src="https://docs.joomla.org/images/thumb/6/66/Sql_field_frontend-en.png/800px-Sql_field_frontend-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/66/Sql_field_frontend-en.png/1200px-Sql_field_frontend-en.png 1.5x, https://docs.joomla.org/images/6/66/Sql_field_frontend-en.png 2x"
data-file-width="1291" data-file-height="661" width="800" height="410"
alt="Sql field frontend-en.png" />

<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Repeatable_Field"
id="content-button" class="button expand success">Zurück: Wiederholbares
Feld</a>
<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/Text_Field"
id="content-button" class="button expand">Weiter: Text Feld</a>
