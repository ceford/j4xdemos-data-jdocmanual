<!-- Filename: J3.x:Adding_custom_fields/Parameters_for_all_Custom_Fields / Display title: Hinzufügen von Feldern/ Parametern für Felder -->

<span id="section-portal-heading"></span>

## Parameter für alle Felder

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

## Parameter für alle Felder

Die Liste für die Felder ist anfänglich leer. Klicke auf **Neu** um ein
Feld hinzuzufügen.  
Im Reiter **Allgemein** müssen die notwendigen Daten ausgefüllt werden:

- Titel  
  Der Titel des Feldes. Der Titel wird auf Felder-Manager Seite
  angezeigt, wo das Feld durch klicken auf den Feld-Titel bearbeitet
  werden kann. Der Titel wird nicht beim Erstellen eines Beitrages oder
  Kontaktes im Frontend angezeigt.
- Name  
  Der Name wird benutzt um das Feld zu bestimmen. Wird das Feld frei
  gelassen, nimmt Joomla! als Standardwert den Titel des Feldes.
- Typ  
  Beim Anlegen eines Feldes kann aus 16 verschiedenen Feld-Typen
  ausgewählt werden. Nach dem Speichern ist der Typ des Feldes
  dauerhaft. Man kann ihn später nicht mehr ändern.

Für jedes Feld können diese Parameter genutzt werden:

- Beschriftung  
  Verwende einen beschreibenden Text als Beschriftung des Feldes. Dieser
  Text ist bei einer mehrsprachigen Website nicht übersetzbar. Wenn kein
  Text für die Beschriftung angegeben wurde, wird der Titeltext auch als
  Beschriftung verwendet.
- Beschreibung  
  Eine Beschreibung für das Feld, die in einem Tooltip über dem
  Eingabefeld angezeigt wird. Die Beschreibung erscheint, wenn der
  Nutzer bei der Eingabe die Maus über das Feld bewegt - z.B. beim
  Erstellen eines Beitrages, Kontaktes oder bei einer Komponente die die
  Eigenen Felder unterstützt. Die Beschreibung ist bei einer
  mehrsprachigen Website nicht übersetzbar. Im Frontent ist die
  Beschreibung nicht sichtbar.
- Erforderlich  
  Ist das ein Pflichtfeld? In diesem Fall muss das Feld ausgefüllt
  werden, bevor ein Beitrag, ein Kontakt oder ein Formular einer
  Komponente, die Eigene Felder verwendet, abgesendet werden kann. Als
  Option kann *Ja* oder *Nein* gewählt werden.
- Standard  
  Hier kann ein Standardwert für das Feld eingetragen werden. Dieser
  Text ist bei mehrsprachigen Installationen nicht übersetzbar. Hinweis:
  In einigen Feldern muss der Wert als Standard eingetragen werden, in
  andere der Index-Wert.
- Status  
  Hier kann der Wert für die Veröffentlichung eingestellt werden. Ist
  der Wert *Veröffentlicht*, *Versteckt*, *Archiviert* oder
  *Papierkorb*?
  - Veröffentlicht: Das Feld ist beim Bearbeiten eines Beitrages oder
    Kontaktes sichtbar und wird angezeigt. Auf der veröffentlichten
    Website ist es ebenfalls sichtbar.
  - Unveröffentlicht: Das Feld wird Nutzern bei der Bearbeitung von
    Beiträgen oder Kontakten nicht angezeigt.
  - Archiviert: Das Feld wird nicht mehr beim Bearbeiten eines Beitrages
    oder Kontaktes angezeigt. Es im Felder-Manager geöffnet werden, wenn
    der Status auf Archivert gesetzt wurde.
  - Papierkorb: Das Feld wurde gelöscht, befindet sich aber noch in der
    Datenbank. Dauerhaft und vollständig gelöscht wird es über den
    Papierkorb leeren Button des Felder-Managers.
- Feld Gruppe  
  Ein Feld kann einer oder mehreren Feld-Gruppen zugeordnet werden.
- Kategorie  
  Du kannst einem Feld eine oder mehrere Feldkategorien zuordnen.
  Hinweis: Der Standard 'Alle' schließt nicht die 'Unkategorisierten'
  Artikel mit ein.
- Zugriff  
  Die
  [Zugriffsebene](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/de "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/de")
  für diesen Eintrag.
- Sprache  
  Hier kann die Sprache dem Feld zugewiesen werden. Wird die
  [Mehrsprachen-Funktionalität](https://docs.joomla.org/J3.x:Setup_a_Multilingual_Site "J3.x:Setup a Multilingual Site")
  nicht genutzt, sollte die Einstellung auf *Alle* bleiben.
- Hinweis  
  Ein optionales Feld das zur Beschreibung oder als Hinweis für das
  Feld.

Im Reiter **Optionen** können folgende Optionen genutzt werden:

- Platzhalter  
  Ein Platzhalter-Text erscheint innerhalb eines Feldes als Hinweis für
  die Eingabe. Der Platzhalter wird im Backend beim Anlegen eines
  Beitrages, Kontaktes oder einer Komponente (welches benutzerdefinierte
  Felder nutzt) angezeigt. Im Frontend wird der Text nicht angezeigt.
- CSS-Klasse Feld  
  Das Klassen-Attribut des Feldes, nachdem es gerendert wurde.
- Edit Klasse  
  Das Klassen-Attribut des Feldes im Bearbeitungsformular. Wenn
  verschiedene Klassen benötigt werden, mit Leerzeichen trennen.
- Einsatzbereich  
  Legt fest, in welchem Bereich der Website das Feld angezeigt werden
  soll. Backend, Frontend oder beides.
- Beschriftung  
  Anzeigen oder Verbergen der Beschriftung des Feldes beim Rendern.
- Automatische Anzeige  
  Joomla unterstützt einige Inhalts-Events die beim Erzeugen des
  Inhaltes getriggert werden. Das ist die Stelle an der eingestellt
  wird, wie das Feld im Inhalt integriert werden soll. Es können 'Nach
  Titel (After Title)', 'Vor Inhalt (Before Display Content)', 'Nach
  Inhalt (After Display Content)' oder 'Keine automatische Anzeige'
  gewählt werden.
- Versteckt  
  Wenn das Feld im Bearbeitungsformular verborgen werden soll.
- Nur Lesen  
  Wenn das Feld im Bearbeitungformular nur gelesen werden darf (Inhalt
  nicht änderbar).

<a href="https://docs.joomla.org/J3.x:Adding_custom_fields"
id="content-button" class="button expand success">Zurück: Einführung</a>
<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field"
id="content-button" class="button expand">Weiter: Kalender Feld</a>
