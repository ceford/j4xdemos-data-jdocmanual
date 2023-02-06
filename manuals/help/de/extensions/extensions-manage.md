<!-- Display title: Extensions: Manage -->

## Beschreibung

Diese Seite ermÃ¶glicht das Aktivieren oder Deaktivieren von
Erweiterungen, Ã¤quivalent zum VerÃ¶ffentlichen und Verstecken, sowie
das Deinstallieren von nicht mehr benÃ¶tigten Erweiterungen.

## Wie darauf zugreifen

- Im Administrator-MenÃ¼ die Option
  **System **→** Verwalten **→** Erweiterungen** wÃ¤hlen.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/4/46/Help-4x-Extensions-Manage-Manage-screen-de.png/800px-Help-4x-Extensions-Manage-Manage-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/46/Help-4x-Extensions-Manage-Manage-screen-de.png/1200px-Help-4x-Extensions-Manage-Manage-screen-de.png 1.5x, https://docs.joomla.org/images/4/46/Help-4x-Extensions-Manage-Manage-screen-de.png 2x"
data-file-width="1385" data-file-height="820" width="800" height="474"
alt="Help-4x-Extensions-Manage-Manage-screen-de.png" />

## Spalten-Ãœberschriften

In der Erweiterungs-Tabelle werden unterschiedliche Spalten gezeigt. Ein
Klick auf eine SpaltenÃ¼berschrift sortiert die Liste nach dessen Wert.

- **KontrollkÃ¤stchen**. Die KÃ¤stchen markieren, um ein oder mehrere
  EintrÃ¤ge auszuwÃ¤hlen. Um alle EintrÃ¤ge auszuwÃ¤hlen, das KÃ¤stchen
  im Spaltenkopf markieren. Nachdem ein oder mehrere KÃ¤stchen markiert
  sind, auf eine SchaltflÃ¤che in der Symbolleiste klicken, um eine
  Aktion fÃ¼r die gewÃ¤hlten EintrÃ¤ge auszufÃ¼hren.
- **Status**. Ein grÃ¼ner Haken oder ein roter Kreis zeigen ob die
  Erweiterung aktiviert/deaktiviert ist. Auf das Symbol klicken, um den
  Status zu wechseln. Ein SchloÃŸ zeigt eine geschÃ¼tzte Erweiterung an.
- **Name**. Der Name der Erweiterung.
- **Bereich**. Zeigt an, ob es eine Site- oder Administrator-Erweiterung
  ist.
- **Typ**. Der Erweiterungstyp. Beispiele sind Modul, Plugin, Template,
  Komponente, Sprache oder Paket.
- **Version**. Die Versionsnummer der Erweiterung.
- **Datum**. Das VerÃ¶ffentlichungsdatum der Erweiterung.
- **Autor**. Der Autor der Erweiterung.
- **Verzeichnis**. Falls die Erweiterung ein Plugin ist, befindet sich
  das Unterverzeichnis im Verzeichnis /plugins der Joomla!-Installation,
  in dem sich die Erweiterung befindet. StandardmÃ¤ÃŸig verfÃ¼gt Joomla!
  im Plugins-Verzeichnis Ã¼ber die folgenden Unterverzeichnisse, die
  jeweils die verschiedenen Arten von definierten Plugins darstellen:
  authentication, content, editors, editors-xtd, extension, search,
  system, user.
- **Paket-ID**. Die Nummer der Paket-ID. Einmalig vergebene
  Identifikations-Nummer fÃ¼r das Element, automatisch von Joomla!
  vergeben. Sie wird zur internen Identifikation des Elements verwendet,
  man kann die Nummer nicht Ã¤ndern.
- **ID**. Die ID-Nummer. Einmalig vergebene Identifikations-Nummer fÃ¼r
  diesen Eintrag. Sie wird automatisch von Joomla! vergeben und wird zur
  internen Identifikation des Elements verwendet. Man kann die Nummer
  nicht verÃ¤ndern.

## Listen-Filter

**Suchleiste**. Das [Bildschirmfoto](#screenshot) zeigt die Suchleiste
im oberen Bereich.

- **Suche nach Text**. Einen Teil des Suchbegriffs eingeben, auf das
  Symbol fÃ¼r Suche klicken. Wird der Mauszeiger *Ã¼ber das Eingabefeld
  bewegt*, zeigt ein *Hilfetext* durchsuchbare Bereiche.Um 'Nach der ID'
  zu suchen, "id:x" eingeben ("x" ist die ID-Nummer, z.B. "id:19").
- **Filter-Optionen**. Durch Anklicken zusÃ¤tzliche Filter zeigen.
- **ZurÃ¼cksetzen**. Durch Klicken werden Filter zurÃ¼ckgesetzt und die
  Liste im ungefilterten Zustand gezeigt.
- **Reihenfolge**. Zeigt das aktuelle Feld fÃ¼r die Reihenfolge an. Es
  gibt 2 MÃ¶glichkeiten, die Reihenfolge zu Ã¤ndern:
  - Im Dropdown-MenÃ¼ wÃ¤hlen. Die Reihenfolge ist aufsteigend oder
    absteigend mÃ¶glich.
  - Eine SpaltenÃ¼berschrift anklicken. Ein Klick auf die
    SpaltenÃ¼berschrift wechselt zwischen aufsteigender und absteigender
    Reihenfolge.
- **Anzuzeigende Anzahl**. Zeigt die Anzahl der EintrÃ¤ge an. Zur
  Ã„nderung in der Dropdown-Liste die gewÃ¼nschte Anzahl wÃ¤hlen.Der
  Standardwert fÃ¼r die Site ist '20', er kann in der
  [Konfiguration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/de#defaultlistlimit "Help4.x:Site Global Configuration/de")
  geÃ¤ndert werden.

### Filtern nach Bereich, Status, Typ und Verzeichnis

**Location**

- **- Bereich wÃ¤hlen -**. Einen Bereich aus der Drop-down-Liste der
  mÃ¶glichen Bereiche wÃ¤hlen.
- **Site**. Site-Erweiterungen werden in Bereichen auÃŸerhalb des
  Administrator-Bereiches verwendet.
- **Administrator**. Administrator-Erweiterungen werden fÃ¼r
  administrative Aufgaben verwendet. Ãœblicherweise wird mit diesen
  Erweiterungen direkt im Backend gearbeitet.

**Status**

- **- Status wÃ¤hlen -**. Den Status der Erweiterung aus der
  Drop-down-Liste wÃ¤hlen.
- **Deaktiviert**. Installierte, aber nicht aktive Erweiterung.
- **Aktiviert**. Installierte und aktivierte Erweiterung.
- **GeschÃ¼tzt**. Installierte und geschÃ¼tzte Erweiterung. Diese
  Erweiterung kann weder deaktiviert noch deinstalliert werden.
- **UngeschÃ¼tzt**. Installierte und ungeschÃ¼tzte Erweiterung. Diese
  Erweiterung kann aktiviert, deaktiviert oder deinstalliert werden.

**Extension Type**

- **- Typ wÃ¤hlen -**. Den Typ der Erweiterungen aus der Dropdown-Liste
  wÃ¤hlen.

**Folder**

- **- Verzeichnis wÃ¤hlen. -**. Ein Plugin-Verzeichnis aus der
  Drop-down-Liste wÃ¤hlen. FÃ¼r jeden Plugin-Typ gibt es ein eigenes
  Verzeichnis.

### Seitennavigation

**Seitenkontrolle**. Gibt es mehr Erweiterung(en) als auf der Seite
gezeigt, wird im unteren Bereich die Seitenkontrollleiste wie auf dem
[Bildschirmfoto](#screenshot) eingeblendet. Die aktuelle Seitenzahl ist
mit dunkler Farbe unterlegt.

- **Start**. Anklicken, um die erste Seite anzuzeigen.
- **Vorherige**. Anklicken, um die vorherige Seite anzuzeigen.
- **Seitennummer**. Anklicken, um die anzuzeigende Seite auszuwÃ¤hlen.
- **Weiter**. Anklicken, um die nÃ¤chste Seite anzuzeigen.
- **Ende**. Anklicken, um die letzte Seite anzuzeigen.

## Werkzeugleiste

Das [Bildschirmfoto](#Bildschirmfoto) am Anfang der Seite zeigt die
Werkzeugleiste im oberen Bereich. Die Funktionen sind:

- **Aktivieren.** GewÃ¤hlte Elemente kÃ¶nnen auf der Website verwendet
  werden.

<!-- -->

- **Deaktivieren**: Macht gewÃ¤hlte Erweiterungen fÃ¼r die Besucher der
  Webseite unsichtbar.

<!-- -->

- **Cache erneuern**. Erneuert die angezeigten Informationen der
  gewÃ¤hlten Erweiterung(en).

<!-- -->

- **Deinstallieren:** Deinstalliert die gewÃ¤hlten Erweiterungen.

<!-- -->

- **Optionen.** Ã–ffnet das Optionen-Fenster, in dem Einstellungen, wie
  die Standard-Parameter, bearbeitet werden kÃ¶nnen.

<!-- -->

- **Hilfe**. Ã–ffnet die Hilfeseite.

## Tipps

- Ãœberall im Backend von Joomla! finden sich die Begriffe
  â€žVerÃ¶ffentlichtâ€œ und â€žVerstecktâ€œ. *VerÃ¶ffentlichen* bedeutet
  dasselbe wie *Eingeschaltet* oder *Aktiviert*. *Versteckt* meint
  dasselbe wie *Ausgeschaltet* oder *Deaktiviert*. Die Begriffe kÃ¶nnen
  gleichbedeutend in Erweiterungsseiten und Hilfe-Dokumentationen
  verwendet werden.
- Informationen wie *Datum* oder *Autor* werden fÃ¼r eine Erweiterung
  vielleicht nicht angezeigt. Das ist kein Problem da es nur bedeutet,
  dass der Entwickler diese Informationen im Installationspaket nicht
  angegeben hat.
