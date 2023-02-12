<!-- Filename: Help4.x:Fields:_Edit / Display title: Felder: Bearbeiten -->

## Beschreibung

Hinzufügen oder Bearbeiten von Feldern in Beiträge, Kontakte und
Benutzer.

Die Hilfeseite zeigt als Beispiel 'Benutzer'.

## Wie darauf zugreifen

**Benutzer **→** Felder**

Ein Feld hinzufügen:

- auf den Button **Neu** der Werkzeugleiste klicken.

Ein Feld bearbeiten:

- einen **Titel** aus der Liste wählen.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/2/23/Help-4x-Fields-Edit-screen-de.png/800px-Help-4x-Fields-Edit-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/23/Help-4x-Fields-Edit-screen-de.png/1200px-Help-4x-Fields-Edit-screen-de.png 1.5x, https://docs.joomla.org/images/thumb/2/23/Help-4x-Fields-Edit-screen-de.png/1600px-Help-4x-Fields-Edit-screen-de.png 2x"
data-file-width="2720" data-file-height="1700" width="800" height="500"
alt="Help-4x-Fields-Edit-screen-de.png" />

## Formular Felder

- **Titel**. Der Titel des Feldes.

### Allgemein

**Linke Seite**

Parameter für alle Eigenen Felder:

- **Typ**. Beim Anlegen eines Feldes kann aus 16 Feldtypen gewählt
  werden. Nach dem Speichern ist der Typ des Feldes dauerhaft. [Mehr
  erfahren.](https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field/de "J3.x:Adding custom fields/Calendar Field/de")
- **Name**. Der Name wird benutzt um das Feld zu bestimmen. Wird das
  Feld frei gelassen, nimmt Joomla als Standardwert den Titel des
  Feldes.
- **Beschriftung**. Einen beschreibenden Text als Beschriftung des
  Feldes verwenden. Dieser Text ist bei einer mehrsprachigen Website
  nicht übersetzbar. Wenn kein Text für die Beschriftung angegeben
  wurde, wird der Titeltext auch als Beschriftung verwendet.
- **Beschreibung**. Eine Beschreibung für das Feld, die in einem Tooltip
  über dem Eingabefeld angezeigt wird. Die Beschreibung erscheint, wenn
  der Nutzer bei der Eingabe im Backend die Maus über das Feld bewegt -
  z.B. beim Erstellen eines Beitrages, Kontaktes oder bei einer
  Komponente, die Felder unterstützt. Die Beschreibung ist bei einer
  mehrsprachigen Website nicht übersetzbar. Im Frontend ist die
  Beschreibung nicht sichtbar.
- **Erforderlich**. Ist das ein Pflichtfeld? In diesem Fall muss das
  Feld ausgefüllt werden, bevor ein Beitrag, ein Kontakt oder ein
  Formular einer Komponente, die Felder verwendet, abgesendet werden
  kann.

**Rechte Seite**

- **Status**. Der Veröffentlichungs-Status des Feldes.
  - Veröffentlicht: Das Feld ist beim Bearbeiten eines Beitrages oder
    Kontaktes sichtbar. Im Frontend ist es ebenfalls sichtbar.
  - Versteckt: Das Feld wird Nutzern bei der Bearbeitung von Beiträgen
    oder Kontakten nicht angezeigt.
  - Archiviert: Das Feld wird nicht beim Bearbeiten eines Beitrages oder
    Kontaktes angezeigt. Es kann in
    [Felder](https://docs.joomla.org/Help4.x:Fields/de#selectstatus "Help4.x:Fields/de")
    geöffnet werden, wenn der Statusfilter auf 'Archiviert' gesetzt
    wurde.
  - Papierkorb: Das Feld wurde gelöscht, befindet sich aber noch in der
    Datenbank. Dauerhaft und vollständig gelöscht wird es in
    [Felder](https://docs.joomla.org/Help4.x:Fields/de#selectstatus "Help4.x:Fields/de")
    über den Button 'Papierkorb leeren'. [Mehr
    erfahren.](https://docs.joomla.org/J4.x:Deleting_an_Article/de "J4.x:Deleting an Article/de")
- **Feld Gruppe**. Ein Feld kann einer oder mehreren Feldgruppen
  zugeordnet werden.
- **Kategorie**. Ein Feld kann einer oder mehreren Kategorien zugeordnet
  werden. Hinweis: Der Standard 'Alle' schließt nicht die
  'Unkategorisierten' Beiträge mit ein.
- **Zugriff**. Die Zugriffsebene des Feldes wählen. Sie werden in
  [Benutzer:
  Zugriffsebenen](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/de "Help4.x:Users: Viewing Access Levels/de")
  eingerichtet.
- **Sprache**. Die Sprache des Feldes wählen. Wird
  [Mehrsprachigkeit](https://docs.joomla.org/Help4.x:Extensions:_Languages/de "Help4.x:Extensions: Languages/de")
  nicht verwendet, den Standardwert 'Alle' beibehalten.
- **Notiz**. Ein optionales Feld das zur Beschreibung oder als Hinweis
  für das Feld.

### Optionen

<img
src="https://docs.joomla.org/images/thumb/b/b5/Help-4x-Fields-Edit-options-subscreen-de.png/600px-Help-4x-Fields-Edit-options-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/b/b5/Help-4x-Fields-Edit-options-subscreen-de.png/900px-Help-4x-Fields-Edit-options-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/b/b5/Help-4x-Fields-Edit-options-subscreen-de.png/1200px-Help-4x-Fields-Edit-options-subscreen-de.png 2x"
data-file-width="2880" data-file-height="1378" width="600" height="287"
alt="Help-4x-Fields-Edit-options-subscreen-de.png" />

**Eingabemaske-Optionen**

- **Platzhalter**. Ein Platzhalter-Text erscheint innerhalb eines Feldes
  als Hinweis für die Eingabe. Der Platzhalter wird im Backend beim
  Anlegen eines Beitrages, Kontaktes oder einer Komponente, die Felder
  unterstützt, angezeigt. Im Frontend wird der Text nicht angezeigt.
- **CSS-Klasse Feld**. Das Klassen-Attribut des Feldes, nachdem es
  gerendert wurde.
- **CSS-Klasse Label**. CSS-Klasse der Feld-Beschriftung im
  Bearbeiten-Modus (Inhalte in das Feld eingeben).
- **Einsatzbereich**. Das Feld im Backend, Frontend oder beiden
  anzeigen.
- **Showon Attribute**. Conditionally show or hide the field depending
  on the value of other fields. The syntax to use here, for example:
  `list-of-items:value1[OR]list-of-items:value2`
  - list-of-items – It is the *name* of an already created field on
    which this field will depends to be show.
  - value1 – Is the value need have the field on which it depends to be
    show.
  - \[OR\] – To create a choice among multiple fields. In the example,
    this field will show when *list-of-items* field have the value:
    *value1* OR *value2*
  - \[AND\] – To combine multiple fields. This field will show only when
    *list-of-items* field have the value: *value1* AND *value2*
  - You can also use value 'does not equal' as in
    **list-of-items!:value1**. The syntax will show this field only when
    *list-of-items* is not equal to *value1*
  - To show this field when *list-of-items* field has been selected and
    have not a empty value, use the syntax *list-of-items!:* (without a
    value specified).

**Note:** Subform fields handle different the identifier *name* of
*list-of-items*. If you create a Subform custom field and you add this
conditional field you are creating to there, you need use *field\[ID\]*
instead of *list-of-items*, where ID is the id of the field
*list-of-items*. Therefore, the showon attribute for this conditional
field you are creating need be: `field36:value1[OR]field36:value2` where
36 is the ID of the field 'List of items'.

**Ausgabe-Optionen**

- **CSS-Klasse Ausgabe**. Das CSS-Klassenattribut für das Feld, wenn es
  ausgegeben wird. Mehrere Klassen mit Leerzeichen trennen.
- **CSS-Klasse**. Das CSS-Klassenattribut für den Wert, wenn er
  ausgegeben wird. Mehrere Klassen mit Leerzeichen trennen.
- **Beschriftung**. Die Beschriftung des Feldes zeigen.
- **CSS-Klasse Beschriftung**. CSS-Klasse der Feld-Beschriftung, wenn es
  gezeigt wird (Inhalte des Feldes anzeigen).
- **Automatische Anzeige**. Wie das Feld im Inhalt integriert werden
  soll.
  - Nach Titel (After Title)
  - Vor Inhalt (Before Display Content)
  - Nach Inhalt (After Display Content)
  - Keine automatische Anzeige
- **Präfix**. Vor dem Feld gezeigter, vorgegebener Text wie zum Beispiel
  £.
- **Suffix**. Nach dem Feld gezeigter, vorgegebener Text wie zum
  Beispiel EUR.
- **Layout**. Benutzerdefiniertes Layout wählen.
- **Anzeigen wenn schreibgeschützt**. Soll ein schreibgeschütztes Feld
  (fehlende Zugriffsberechtigung des Benutzers) gezeigt werden.

### Veröffentlichung

<img
src="https://docs.joomla.org/images/thumb/f/f3/Help-4x-Fields-Edit-publishing-subscreen-de.png/600px-Help-4x-Fields-Edit-publishing-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f3/Help-4x-Fields-Edit-publishing-subscreen-de.png/900px-Help-4x-Fields-Edit-publishing-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/f/f3/Help-4x-Fields-Edit-publishing-subscreen-de.png/1200px-Help-4x-Fields-Edit-publishing-subscreen-de.png 2x"
data-file-width="2880" data-file-height="980" width="600" height="204"
alt="Help-4x-Fields-Edit-publishing-subscreen-de.png" />

- **Erstellungsdatum**. Das Erstellungsdatum des Feldes. Ein anderes
  Datum oder Uhrzeit eingeben oder auf das Kalender-Symbol klicken.
- **Autor**. Der Name des Benutzers, der das Feld erstellt hat. Standard
  ist der aktuell eingewählte Benutzer. Um einen anderen Benutzer
  auszuwählen, auf den Button 'Benutzer auswählen' klicken.
- **Bearbeitungsdatum**. Datum der letzten Bearbeitung.
- **Bearbeitet von**. Benutzer, der die letzte Bearbeitung ausgeführt
  hat.
- **ID**. Einmalig vergebene Identifikations-Nummer für das Feld, die
  nicht geändert werden kann. Beim Erstellen eines neuen Feldes zeigt
  das Feld "0" an, bis man speichert.

### Berechtigungen

Hier können die Berechtigungen für das Feld eingegeben werden. [Mehr
erfahren.](https://docs.joomla.org/J3.x:Access_Control_List_Tutorial/de#hierarchylevels "J3.x:Access Control List Tutorial/de")

<img
src="https://docs.joomla.org/images/thumb/0/09/Help-4x-Fields-Edit-permissions-subscreen-de.png/600px-Help-4x-Fields-Edit-permissions-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/09/Help-4x-Fields-Edit-permissions-subscreen-de.png/900px-Help-4x-Fields-Edit-permissions-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/0/09/Help-4x-Fields-Edit-permissions-subscreen-de.png/1200px-Help-4x-Fields-Edit-permissions-subscreen-de.png 2x"
data-file-width="2880" data-file-height="1260" width="600" height="263"
alt="Help-4x-Fields-Edit-permissions-subscreen-de.png" />

Um Berechtigungen dieses Feldes zu ändern:

1.  Die **Gruppe** durch Anklicken des Namens auf der linken Seite
    auswählen.
2.  Die gewünschte **Aktion** aussuchen.
    - **Löschen**. Benutzer können dieses Feld löschen.
    - **Bearbeiten**. Benutzer können dieses Feld bearbeiten.
    - **Status bearbeiten**. Benutzer können den Status dieses Feldes
      bearbeiten.
    - **Inhalt von eigenen Feldern bearbeiten**. Benutzer können dieses
      Feld bearbeiten.
3.  Die Berechtigungen der gewählten Aktion wählen.
    - **Vererbt**. Für Benutzer dieser Gruppe von der
      [Konfiguration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/de#permissions "Help4.x:Site Global Configuration/de"),
      der übergeordneten Gruppe und der Kategorie vererbt .
    - **Erlaubt**. Für Benutzer dieser Gruppe erlaubt.Hinweis: Wenn die
      Aktion auf einer höheren Ebene 'Verweigert' wird, ist die
      'Erlaubt'-Berechtigung hier dadurch überschrieben. Eine
      'Verweigert'-Einstellung kann nicht überschrieben werden.
    - **Verweigert**. Für Benutzer dieser Gruppe verweigert .
4.  Auf **Speichern** in der **Werkzeugleiste** oben klicken. Danach
    aktualisiert sich die Anzeige, erst dann werden die errechneten
    Einstellungen angezeigt.

## Werkzeugleiste

Das [Bildschirmfoto](#screenshot) zeigt die Werkzeugleiste im oberen
Bereich.

- **Speichern**. Speichert das Feld und bleibt auf der aktuellen Seite.
- **Speichern & Schließen**. Speichert das Feld und schließt die
  aktuelle Seite.
  - **Speichern & Neu**. Speichert das Feld und hält die Seite offen,
    damit ein neues Feld erstellt werden kann.
  - **Als Kopie speichern**. Speichert Änderungen in einer Kopie des
    aktuellen Feldes. Das aktuelle Feld wird davon nicht beeinflusst.
- **Schließen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück.
- **Hilfe**. Öffnet die Hilfeseite.

## Tipps

Mehr zur [Anwendung benutzerdefinierter
Felder](https://docs.joomla.org/J3.x:Adding_custom_fields/de "J3.x:Adding custom fields/de").

## Verwandte Informationen

- Dieses
  [Portal](https://docs.joomla.org/Portal:Joomla_4/de "Portal:Joomla 4/de")
  bringt alle Informationen zu Joomla 4 zusammen.

|                                                                                                                  |                                                                                                                                                                           |
|------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Verwandte Hilfeseiten                                                                                            | Beschreibung                                                                                                                                                              |
| [Felder](https://docs.joomla.org/Help4.x:Fields/de "Help4.x:Fields/de")                                          | Felder werden verwendet, um zusätzliche Eigenschaften von Beiträgen, Kontakten oder Benutzern anzuzeigen. Die Daten werden im Backend eingegeben und im Frontend gezeigt. |
| <span class="mw-selflink selflink">Felder: Bearbeiten</span>                                                     | Hinzufügen oder Bearbeiten von Feldern in Beiträge, Kontakte und Benutzer.                                                                                                |
| [Feldgruppen](https://docs.joomla.org/Help4.x:Field_Groups/de "Help4.x:Field Groups/de")                         | Die Liste wird verwendet, um Feldgruppen zu finden, zu markieren, hinzuzufügen und zu bearbeiten.                                                                         |
| [Feldgruppen: Bearbeiten](https://docs.joomla.org/Help4.x:Field_Groups:_Edit/de "Help4.x:Field Groups: Edit/de") | Feldgruppen gruppieren verwandte Felder für die Eingabe der Daten in Tabs.                                                                                                |
