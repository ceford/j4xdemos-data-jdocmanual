<!-- Filename: Help4.x:Permissions_for_Group / Display title: Berechtigungen für Gruppen -->

## Beschreibung

Der Erweiterte Berechtigungsbericht zeigt die exakten Berechtigungen für
eine bestimmte Benutzergruppe für alle Objekte der Joomla! Installation
an. Er ist hilfreich für die Fehlersuche bei Problemen mit dem
Benutzerzugang.

## Wie darauf zugreifen

- Im Administrator-Menü **Benutzer → Gruppen** auswählen, dann ...
  - das Symbol **Berechtigungen** für eine bestimmte Gruppe in der Liste
    der Benutzergruppen anklicken.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/1/18/Help-4x-debug_groups-screen-de.png/800px-Help-4x-debug_groups-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/18/Help-4x-debug_groups-screen-de.png/1200px-Help-4x-debug_groups-screen-de.png 1.5x, https://docs.joomla.org/images/thumb/1/18/Help-4x-debug_groups-screen-de.png/1600px-Help-4x-debug_groups-screen-de.png 2x"
data-file-width="2182" data-file-height="980" width="800" height="359"
alt="Help-4x-debug groups-screen-de.png" />

## Spalten-Überschriften

Die Asset-Liste der Joomla! Site enthält folgende Spalten. Für jedes
Asset wird die Berechtigung für die jeweilige Gruppe angezeigt, farblich
codiert gemäß der Legende (siehe Screenshot).

- **Bestandstitel**. Titel des jeweiligen Assets.
- **Bestandsname**. Interner Name des Assets.
- **Site-Anmeldung.** Ermöglicht Benutzern in der Gruppe, sich im
  Frontend anzumelden.
- **Administratoranmeldung**. Ermöglicht den Benutzern der Gruppe, sich
  im Administrator-Backend anzumelden.
- **Web Services Login.** Ermöglicht die Nutzung der Joomla Web Services
  API über ein Superuser API Token.
- **Offlinezugang**. Ermöglicht den Benutzern der Gruppe, sich im
  Frontend anzumelden, auch wenn die Seite offline ist.
- **Super Benutzer**. Ermöglicht den Benutzern der Gruppe, jede Aktion
  auf der ganzen Seite, unabhängig von anderen
  Berechtigungseinstellungen, durchzuführen.
  - **Nur Optionen konfigurieren**. Erlaubt den Benutzern der Gruppe,
    die Optionen zu bearbeiten, mit Ausnahme der Berechtigung
    irgendeiner Erweiterung.
- **Administrationszugriff**. Erlaubt den Benutzern der Gruppe Zugriff
  auf alle Bereiche der Backend-Administration mit Ausnahme der globalen
  Konfiguration.
- **Erstellen**. Ermöglicht den Benutzern der Gruppe, jeden Inhalt in
  jeder Erweiterung zu erstellen.
- **Löschen**. Ermöglicht den Benutzern der Gruppe, jeden Inhalt in
  jeder Erweiterung zu löschen.
- **Bearbeiten**. Ermöglicht den Benutzern der Gruppe, jeden Inhalt in
  jeder Erweiterung zu bearbeiten.
- **Status bearbeiten**. Ermöglicht den Benutzern der Gruppe, den Status
  der Inhalte in jeder Erweiterung zu bearbeiten.
- **Bearbeiten**. Ermöglicht den Benutzern der Gruppe, jeden eigenen
  Inhalt in jeder Erweiterung zu bearbeiten.
- **Inhalt von eigenen Feldern bearbeiten**. Ermöglicht den Benutzern
  der Gruppe, jeden Inhalt von eigenen Feldern in jeder Erweiterung zu
  bearbeiten.
- **LFT**. Die linken und rechten Werte in der Hierarchie. Siehe [Using
  nested
  sets](https://docs.joomla.org/Using_nested_sets "Using nested sets")
  in Englisch.

<!-- -->

- **ID**. Einmalig vergebene Identifikations-Nummer für den Eintrag. Sie
  wird von Joomla automatisch vergeben und dient zur internen
  Identifikation des Eintrages. Man kann die Nummer nicht ändern. Beim
  Neu-Erstellen eines Eintrags zeigt das Feld "0" an, bis man speichert,
  dabei wird dann die neue ID vergeben.

## Listen-Filter

Im oberen Bereich der Seite befindet sich die im Bildschirmfoto oben
dargestellte Filterleiste. Die Funktionen sind:

- **Suche**. Einen Teil des Bestandstitels eingeben und auf das
  Lupen-Symbol klicken, um passende Namen zu finden. Durch Tippen auf
  **X** oder „Zurücksetzen“ wird das Suchfeld geleert und die komplette
  Liste der Menüs wieder angezeigt.
- **Komponente auswählen**. Filtern nach installierter Komponente in
  Joomla.
- **Anfangsebene auswählen**. Die Anfangsebene des Elements.
- **Endebene auswählen**. Die Endebene des Elements.

**Seitenkontrolle**. Gibt es mehr Einträge als auf der Seite gezeigt,
wird im unteren Bereich die Seitenkontrollleiste wie auf dem
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

- **Schließen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück. Dieses Symbol wird nicht
  angezeigt, wenn ein neuer Eintrag erstellt wird.

<!-- -->

- **Optionen.** Öffnet das Optionen-Fenster, in dem Einstellungen, wie
  die Standard-Parameter, bearbeitet werden können.

<!-- -->

- **Hilfe**. Öffnet die Hilfeseite.

## Legende

Am Seitenende befindet sich diese Legende:

<img
src="https://docs.joomla.org/images/4/4a/Help31-Help-Permissions-Report-Legend-de.png"
decoding="async" data-file-width="296" data-file-height="22" width="296"
height="22" alt="Help31-Help-Permissions-Report-Legend-de.png" />

- **Nicht erlaubt**. Die Aktion ist nicht erlaubt.
- **Erlaubt**. Die Aktion ist erlaubt.
- **Verboten**. Die Aktion ist verboten.

## Verwandte Informationen

- [Konfiguration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/de "Help4.x:Site Global Configuration/de")
