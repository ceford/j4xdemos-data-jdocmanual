<!-- Filename: Help4.x:Extensions:_Manage / Display title: Erweiterungen: Verwalten -->

## Beschreibung

Diese Seite ermöglicht das Aktivieren oder Deaktivieren von
Erweiterungen, äquivalent zum Veröffentlichen und Verstecken, sowie das
Deinstallieren von nicht mehr benötigten Erweiterungen.

## Wie darauf zugreifen

- Im Administrator-Menü die Option
  **System **→** Verwalten **→** Erweiterungen** wählen.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/4/46/Help-4x-Extensions-Manage-Manage-screen-de.png/800px-Help-4x-Extensions-Manage-Manage-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/46/Help-4x-Extensions-Manage-Manage-screen-de.png/1200px-Help-4x-Extensions-Manage-Manage-screen-de.png 1.5x, https://docs.joomla.org/images/4/46/Help-4x-Extensions-Manage-Manage-screen-de.png 2x"
data-file-width="1385" data-file-height="820" width="800" height="474"
alt="Help-4x-Extensions-Manage-Manage-screen-de.png" />

## Spalten-Überschriften

In der Erweiterungs-Tabelle werden unterschiedliche Spalten gezeigt. Ein
Klick auf eine Spaltenüberschrift sortiert die Liste nach dessen Wert.

- **Kontrollkästchen**. Die Kästchen markieren, um ein oder mehrere
  Einträge auszuwählen. Um alle Einträge auszuwählen, das Kästchen im
  Spaltenkopf markieren. Nachdem ein oder mehrere Kästchen markiert
  sind, auf eine Schaltfläche in der Symbolleiste klicken, um eine
  Aktion für die gewählten Einträge auszuführen.
- **Status**. Ein grüner Haken oder ein roter Kreis zeigen ob die
  Erweiterung aktiviert/deaktiviert ist. Auf das Symbol klicken, um den
  Status zu wechseln. Ein Schloß zeigt eine geschützte Erweiterung an.
- **Name**. Der Name der Erweiterung.
- **Bereich**. Zeigt an, ob es eine Site- oder Administrator-Erweiterung
  ist.
- **Typ**. Der Erweiterungstyp. Beispiele sind Modul, Plugin, Template,
  Komponente, Sprache oder Paket.
- **Version**. Die Versionsnummer der Erweiterung.
- **Datum**. Das Veröffentlichungsdatum der Erweiterung.
- **Autor**. Der Autor der Erweiterung.
- **Verzeichnis**. Falls die Erweiterung ein Plugin ist, befindet sich
  das Unterverzeichnis im Verzeichnis /plugins der Joomla!-Installation,
  in dem sich die Erweiterung befindet. Standardmäßig verfügt Joomla! im
  Plugins-Verzeichnis über die folgenden Unterverzeichnisse, die jeweils
  die verschiedenen Arten von definierten Plugins darstellen:
  authentication, content, editors, editors-xtd, extension, search,
  system, user.
- **Paket-ID**. Die Nummer der Paket-ID. Einmalig vergebene
  Identifikations-Nummer für das Element, automatisch von Joomla!
  vergeben. Sie wird zur internen Identifikation des Elements verwendet,
  man kann die Nummer nicht ändern.
- **ID**. Die ID-Nummer. Einmalig vergebene Identifikations-Nummer für
  diesen Eintrag. Sie wird automatisch von Joomla! vergeben und wird zur
  internen Identifikation des Elements verwendet. Man kann die Nummer
  nicht verändern.

## Listen-Filter

**Suchleiste**. Das [Bildschirmfoto](#screenshot) zeigt die Suchleiste
im oberen Bereich.

- **Suche nach Text**. Einen Teil des Suchbegriffs eingeben, auf das
  Symbol für Suche klicken. Wird der Mauszeiger *über das Eingabefeld
  bewegt*, zeigt ein *Hilfetext* durchsuchbare Bereiche.Um 'Nach der ID'
  zu suchen, "id:x" eingeben ("x" ist die ID-Nummer, z.B. "id:19").
- **Filter-Optionen**. Durch Anklicken zusätzliche Filter zeigen.
- **Zurücksetzen**. Durch Klicken werden Filter zurückgesetzt und die
  Liste im ungefilterten Zustand gezeigt.
- **Reihenfolge**. Zeigt das aktuelle Feld für die Reihenfolge an. Es
  gibt 2 Möglichkeiten, die Reihenfolge zu ändern:
  - Im Dropdown-Menü wählen. Die Reihenfolge ist aufsteigend oder
    absteigend möglich.
  - Eine Spaltenüberschrift anklicken. Ein Klick auf die
    Spaltenüberschrift wechselt zwischen aufsteigender und absteigender
    Reihenfolge.
- **Anzuzeigende Anzahl**. Zeigt die Anzahl der Einträge an. Zur
  Änderung in der Dropdown-Liste die gewünschte Anzahl wählen.Der
  Standardwert für die Site ist '20', er kann in der
  [Konfiguration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/de#defaultlistlimit "Help4.x:Site Global Configuration/de")
  geändert werden.

### Filtern nach Bereich, Status, Typ und Verzeichnis

**Location**

- **- Bereich wählen -**. Einen Bereich aus der Drop-down-Liste der
  möglichen Bereiche wählen.
- **Site**. Site-Erweiterungen werden in Bereichen außerhalb des
  Administrator-Bereiches verwendet.
- **Administrator**. Administrator-Erweiterungen werden für
  administrative Aufgaben verwendet. Üblicherweise wird mit diesen
  Erweiterungen direkt im Backend gearbeitet.

**Status**

- **- Status wählen -**. Den Status der Erweiterung aus der
  Drop-down-Liste wählen.
- **Deaktiviert**. Installierte, aber nicht aktive Erweiterung.
- **Aktiviert**. Installierte und aktivierte Erweiterung.
- **Geschützt**. Installierte und geschützte Erweiterung. Diese
  Erweiterung kann weder deaktiviert noch deinstalliert werden.
- **Ungeschützt**. Installierte und ungeschützte Erweiterung. Diese
  Erweiterung kann aktiviert, deaktiviert oder deinstalliert werden.

**Extension Type**

- **- Typ wählen -**. Den Typ der Erweiterungen aus der Dropdown-Liste
  wählen.

**Folder**

- **- Verzeichnis wählen. -**. Ein Plugin-Verzeichnis aus der
  Drop-down-Liste wählen. Für jeden Plugin-Typ gibt es ein eigenes
  Verzeichnis.

### Seitennavigation

**Seitenkontrolle**. Gibt es mehr Erweiterung(en) als auf der Seite
gezeigt, wird im unteren Bereich die Seitenkontrollleiste wie auf dem
[Bildschirmfoto](#screenshot) eingeblendet. Die aktuelle Seitenzahl ist
mit dunkler Farbe unterlegt.

- **Start**. Anklicken, um die erste Seite anzuzeigen.
- **Vorherige**. Anklicken, um die vorherige Seite anzuzeigen.
- **Seitennummer**. Anklicken, um die anzuzeigende Seite auszuwählen.
- **Weiter**. Anklicken, um die nächste Seite anzuzeigen.
- **Ende**. Anklicken, um die letzte Seite anzuzeigen.

## Werkzeugleiste

Das [Bildschirmfoto](#Bildschirmfoto) am Anfang der Seite zeigt die
Werkzeugleiste im oberen Bereich. Die Funktionen sind:

- **Aktivieren.** Gewählte Elemente können auf der Website verwendet
  werden.
- **Deaktivieren**: Macht gewählte Erweiterungen für die Besucher der
  Webseite unsichtbar.
- **Cache erneuern**. Erneuert die angezeigten Informationen der
  gewählten Erweiterung(en).
- **Deinstallieren:** Deinstalliert die gewählten Erweiterungen.
- **Optionen.** Öffnet das Optionen-Fenster, in dem Einstellungen, wie
  die Standard-Parameter, bearbeitet werden können.
- **Hilfe**. Öffnet die Hilfeseite.

## Tipps

- Überall im Backend von Joomla! finden sich die Begriffe
  „Veröffentlicht“ und „Versteckt“. *Veröffentlichen* bedeutet dasselbe
  wie *Eingeschaltet* oder *Aktiviert*. *Versteckt* meint dasselbe wie
  *Ausgeschaltet* oder *Deaktiviert*. Die Begriffe können
  gleichbedeutend in Erweiterungsseiten und Hilfe-Dokumentationen
  verwendet werden.
- Informationen wie *Datum* oder *Autor* werden für eine Erweiterung
  vielleicht nicht angezeigt. Das ist kein Problem da es nur bedeutet,
  dass der Entwickler diese Informationen im Installationspaket nicht
  angegeben hat.
