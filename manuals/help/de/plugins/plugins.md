<!-- Filename: Help4.x:Plugins / Display title: Plugins -->

## Beschreibung

Mit dem Plugin-Manager können Joomla!-Plugins aktiviert und deaktiviert
werden sowie die Einstellungen und Optionen eines Plugins bearbeitet
werden. Er ist außerdem hilfreich, um schnell mehrere Plugins auf einmal
zu aktivieren/deaktivieren.

## Wie darauf zugreifen

- Im Administrator-Menü die Option
  **System **→** Verwalten-Panel **→** Plugins** wählen oder ...
- im Administrator-Menü die Option
  **Dashboard **→** Site-Panel **→** Plugins** wählen.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/9/9d/Help-4x-Extensions-Plugin-Manager-screen-de.png/800px-Help-4x-Extensions-Plugin-Manager-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/9/9d/Help-4x-Extensions-Plugin-Manager-screen-de.png 1.5x"
data-file-width="1200" data-file-height="534" width="800" height="356"
alt="Help-4x-Extensions-Plugin-Manager-screen-de.png" />

## Spalten-Überschriften

- **Checkbox**. Dieses Kästchen markieren, um einen oder mehrere
  Einträge auszuwählen. Um alle Einträge auszuwählen, das Kästchen im
  Spaltenkopf markieren. Nachdem ein oder mehrere Kästchen markiert
  sind, auf eine Schaltfläche in der Werkzeugleiste klicken, um eine
  Aktion für den ausgewählten Eintrag oder die ausgewählten Einträge
  durchzuführen. Viele Aktionen, wie z.B. Veröffentlichen und
  Verstecken, können mit mehreren Einträgen arbeiten. Andere, wie z.B.
  Bearbeiten, funktionieren gleichzeitig jeweils nur mit einem Eintrag.
  Wenn mehrere Einträge markiert sind und Sie auf „Bearbeiten“ drücken,
  wird der erste der markierten Einträge zur Bearbeitung geöffnet.
- **Reihenfolge.** Die Reihenfolge eines Eintrags innerhalb einer Liste
  kann wie folgt geändert werden:
  - Wenn die Liste Filter-Optionen einen Positions-Filter enthält, dann
    wählt man die gewünschte Position aus. Dadurch wird die Liste auf
    Positionen beschränkt, die dieser Position zugeordnet sind.
  - Das Reihenfolge-Symbol <img
    src="https://docs.joomla.org/images/e/ee/Help30-Ordering-colheader-icon.png"
    decoding="async" data-file-width="12" data-file-height="23" width="12"
    height="23" alt="Help30-Ordering-colheader-icon.png" /> in der
    Tabellenüberschrift anklicken, um diese Spalte zur aktiven
    Sortierung zu machen. Die Ordnungssymbole in jeder Zeile ändern sich
    von hellgrau zu dunkelgrau, und der Mauszeiger verwandelt sich beim
    Überfahren in einen Ziehpfeil.
  - Eines der Reihenfolge-Symbole <img
    src="https://docs.joomla.org/images/8/87/Help30-Ordering-colheader-grab-bar-icon.png"
    decoding="async" data-file-width="10" data-file-height="21" width="10"
    height="21" alt="Help30-Ordering-colheader-grab-bar-icon.png" />
    wählen und es nach oben oder unten ziehen, um die Position dieser
    Zeile in der Liste zu ändern. Die Einträge werden in der neuen
    Reihenfolge innerhalb der Position angezeigt.
- **Status.** Ein grüner Haken oder ein rotes Kreuz zeigen den
  aktivierten/deaktivierten Status der Komponente an. Zum Ändern des
  Status auf das Symbol klicken.
- **Pluginname:** Der Name des Plugins.
- **Typ.** Der Typ des Plugins. Einige Typen sind: authentication,
  content, editors, editors-xtd, search, system und user. Diese
  Bezeichnungen werden auch für Unterverzeichnisse der Website
  verwendet, in der sich die Plugin-Dateien befinden. Beispiel: Plugins
  des Typs 'authentication' befinden sich im Verzeichnis
  'plugins/authentication'.
- **Plugindatei.** Das Plugins-Verzeichnis, das die Plugin-Dateien
  enthält. Das Verzeichnis befindet sich im zugehörigen
  Plugin-Verzeichnis. Beispiel: Das Plugin „Authentifizierung – Joomla!“
  ist vom Typ 'authentication' und der Datei 'joomla'. Das Verzeichnis
  befindet sich in 'plugins/authentication/joomla'.
- **Zugriffsebene:** Zeigt welche Zugriffsebenen der Benutzer auf diesen
  Eintrag Zugriff haben. Die Zugriffsebene eines Eintrags kann durch
  Anklicken seines Namens geändert und zur Bearbeitung geöffnet werden.
  Die Zugriffsebenen der Benutzer, die mit Joomla! vorkonfiguriert sind,
  sind:
  - Öffentlich: Alle haben Zugriff, einschließlich der
    Webseitenbesucher, die nicht eingeloggt sind.
  - Registriert: Nur Benutzer mit dem Status „registriert“ oder höher
    haben Zugriff
  - Spezial: Nur Benutzer mit Autorenstatus oder höher haben Zugriff
- **ID**. Einmalig vergebene Identifikations-Nummer für den Eintrag. Sie
  wird von Joomla automatisch vergeben und dient zur internen
  Identifikation des Eintrages. Man kann die Nummer nicht ändern. Beim
  Neu-Erstellen eines Eintrags zeigt das Feld "0" an, bis man speichert,
  dabei wird dann die neue ID vergeben.

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
  [Konfiguration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/de#defaultlistlimit "Special:MyLanguage/Help4.x:Site Global Configuration/de")
  geändert werden.

Die Pluginliste kann sehr lang sein. Das Anwenden von einem oder
mehreren kombinierten Filtern kann die angezeigte Liste begrenzt werden.

**Filter-Optionen**

- **Status**. Einen Status (Deaktiviert/Aktiviert) aus der Liste wählen,
  um nur Plugins mit diesem Status anzuzeigen.
- **Typ wählen**. Einen Typ aus der Liste wählen, um nur Plugins mit dem
  gewählten Typ anzuzeigen.
- **Plugindatei wählen**. Eine lange Liste von Einträgen, die eine
  gezielte Auswahl ermöglicht.
- **Zugriffsebene wählen**. Eine Zugriffsebene aus der Liste wählen, um
  nur Plugins der gewählten Zugriffsebene anzuzeigen.

## Werkzeugleiste

Das [Bildschirmfoto](#Bildschirmfoto) am Anfang der Seite zeigt die
Werkzeugleiste im oberen Bereich. Die Funktionen sind:

- **Aktivieren.** Gewählte Elemente können auf der Website verwendet
  werden. Alternativ kann zwischen Aktiviert und Deaktiviert
  umgeschaltet werden, indem man auf das Symbol in der Spalte *Status'
  klickt.*
- **Deaktivieren**: Macht gewählte Plugins für die Besucher der Webseite
  unsichtbar. Alternativ kann zwischen Aktiviert und Deaktiviert
  umgeschaltet werden, indem man auf das Symbol in der Spalte *Status*
  klickt.
- **Freigeben**. Gibt die ausgewählten Plugins wieder frei. Funktioniert
  mit einem oder mehreren ausgewählten Plugins.
- **Optionen.** Öffnet das Optionen-Fenster, in dem Einstellungen, wie
  die Standard-Parameter, bearbeitet werden können.
- **Hilfe**. Öffnet die Hilfeseite.

## Tipps

- Um eine ganze Reihe von Plugins zu aktivieren oder zu deaktivieren,
  das Kontrollkästchen für jedes gewünschte Plugin markieren und dann in
  der Symbolleiste auf die Schaltfläche „Aktivieren“ bzw. „Deaktivieren“
  klicken.
- Seit Joomla! 1.6 werden konfigurierbare Plugin-Einstellungen als
  „Optionen“ bezeichnet. Vorher wurden sie „Parameter“ genannt. Beide
  Bezeichnungen werden in Hilfedokumentationen und Tutorials
  gleichbedeutend verwendet.

## Verwandte Informationen

- Um die Details oder Optionen für ein Plugin zu ändern: [Plugins Name -
  Bearbeiten](https://docs.joomla.org/Help4.x:Plugins:_Name_of_Plugin/de "Help4.x:Plugins: Name of Plugin/de")
- Um Plugins zu installieren: [Erweiterungen:
  Installieren](https://docs.joomla.org/Help4.x:Extensions:_Install/de "Help4.x:Extensions: Install/de")
- Um Plugins zu deinstallieren: [Erweiterungen:
  Verwalten](https://docs.joomla.org/Help4.x:Extensions:_Manage/de "Help4.x:Extensions: Manage/de")
