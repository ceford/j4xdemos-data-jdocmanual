<!-- Display title: Permissions for Group -->

## Beschreibung

Der Erweiterte Berechtigungsbericht zeigt die exakten Berechtigungen
fÃ¼r eine bestimmte Benutzergruppe fÃ¼r alle Objekte der Joomla!
Installation an. Er ist hilfreich fÃ¼r die Fehlersuche bei Problemen mit
dem Benutzerzugang.

## Wie darauf zugreifen

- Im Administrator-MenÃ¼ **Benutzer â†’ Gruppen** auswÃ¤hlen, dann ...
  - das Symbol **Berechtigungen** fÃ¼r eine bestimmte Gruppe in der
    Liste der Benutzergruppen anklicken.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/1/18/Help-4x-debug_groups-screen-de.png/800px-Help-4x-debug_groups-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/18/Help-4x-debug_groups-screen-de.png/1200px-Help-4x-debug_groups-screen-de.png 1.5x, https://docs.joomla.org/images/thumb/1/18/Help-4x-debug_groups-screen-de.png/1600px-Help-4x-debug_groups-screen-de.png 2x"
data-file-width="2182" data-file-height="980" width="800" height="359"
alt="Help-4x-debug groups-screen-de.png" />

## Spalten-Ãœberschriften

Die Asset-Liste der Joomla! Site enthÃ¤lt folgende Spalten. FÃ¼r jedes
Asset wird die Berechtigung fÃ¼r die jeweilige Gruppe angezeigt,
farblich codiert gemÃ¤ÃŸ der Legende (siehe Screenshot).

- **Bestandstitel**. Titel des jeweiligen Assets.
- **Bestandsname**. Interner Name des Assets.
- **Site-Anmeldung.** ErmÃ¶glicht Benutzern in der Gruppe, sich im
  Frontend anzumelden.
- **Administratoranmeldung**. ErmÃ¶glicht den Benutzern der Gruppe, sich
  im Administrator-Backend anzumelden.
- **Web Services Login.** ErmÃ¶glicht die Nutzung der Joomla Web
  Services API Ã¼ber ein Superuser API Token.
- **Offlinezugang**. ErmÃ¶glicht den Benutzern der Gruppe, sich im
  Frontend anzumelden, auch wenn die Seite offline ist.
- **Super Benutzer**. ErmÃ¶glicht den Benutzern der Gruppe, jede Aktion
  auf der ganzen Seite, unabhÃ¤ngig von anderen
  Berechtigungseinstellungen, durchzufÃ¼hren.
  - **Nur Optionen konfigurieren**. Erlaubt den Benutzern der Gruppe,
    die Optionen zu bearbeiten, mit Ausnahme der Berechtigung
    irgendeiner Erweiterung.
- **Administrationszugriff**. Erlaubt den Benutzern der Gruppe Zugriff
  auf alle Bereiche der Backend-Administration mit Ausnahme der globalen
  Konfiguration.
- **Erstellen**. ErmÃ¶glicht den Benutzern der Gruppe, jeden Inhalt in
  jeder Erweiterung zu erstellen.
- **LÃ¶schen**. ErmÃ¶glicht den Benutzern der Gruppe, jeden Inhalt in
  jeder Erweiterung zu lÃ¶schen.
- **Bearbeiten**. ErmÃ¶glicht den Benutzern der Gruppe, jeden Inhalt in
  jeder Erweiterung zu bearbeiten.
- **Status bearbeiten**. ErmÃ¶glicht den Benutzern der Gruppe, den
  Status der Inhalte in jeder Erweiterung zu bearbeiten.
- **Bearbeiten**. ErmÃ¶glicht den Benutzern der Gruppe, jeden eigenen
  Inhalt in jeder Erweiterung zu bearbeiten.
- **Inhalt von eigenen Feldern bearbeiten**. ErmÃ¶glicht den Benutzern
  der Gruppe, jeden Inhalt von eigenen Feldern in jeder Erweiterung zu
  bearbeiten.
- **LFT**. Die linken und rechten Werte in der Hierarchie. Siehe [Using
  nested
  sets](https://docs.joomla.org/Using_nested_sets "Using nested sets")
  in Englisch.

<!-- -->

- **ID**. Einmalig vergebene Identifikations-Nummer fÃ¼r den Eintrag.
  Sie wird von Joomla automatisch vergeben und dient zur internen
  Identifikation des Eintrages. Man kann die Nummer nicht Ã¤ndern. Beim
  Neu-Erstellen eines Eintrags zeigt das Feld "0" an, bis man speichert,
  dabei wird dann die neue ID vergeben.

## Listen-Filter

Im oberen Bereich der Seite befindet sich die im Bildschirmfoto oben
dargestellte Filterleiste. Die Funktionen sind:

- **Suche**. Einen Teil des Bestandstitels eingeben und auf das
  Lupen-Symbol klicken, um passende Namen zu finden. Durch Tippen auf
  **X** oder â€žZurÃ¼cksetzenâ€œ wird das Suchfeld geleert und die
  komplette Liste der MenÃ¼s wieder angezeigt.
- **Komponente auswÃ¤hlen**. Filtern nach installierter Komponente in
  Joomla.
- **Anfangsebene auswÃ¤hlen**. Die Anfangsebene des Elements.
- **Endebene auswÃ¤hlen**. Die Endebene des Elements.

**Seitenkontrolle**. Gibt es mehr EintrÃ¤ge als auf der Seite gezeigt,
wird im unteren Bereich die Seitenkontrollleiste wie auf dem
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

- **SchlieÃŸen**. SchlieÃŸt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Ã„nderungen zurÃ¼ck. Dieses Symbol wird nicht
  angezeigt, wenn ein neuer Eintrag erstellt wird.

<!-- -->

- **Optionen.** Ã–ffnet das Optionen-Fenster, in dem Einstellungen, wie
  die Standard-Parameter, bearbeitet werden kÃ¶nnen.

<!-- -->

- **Hilfe**. Ã–ffnet die Hilfeseite.

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
