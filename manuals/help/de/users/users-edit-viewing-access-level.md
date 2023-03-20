<!-- Filename: Help4.x:Users:_Edit_Viewing_Access_Level / Display title: Benutzer: Zugriffsebenen anzeigen und bearbeiten -->

## Beschreibung

Zugriffsebenen kontrollieren, welche Objekte der Seite welcher Benutzer
sehen kann. Objekte sind etwa Menü-Einträge, Module, Kategorien und
Komponenten-Elemente (Beiträge, Kontakte, usw.). Jedes Objekt der Seite
ist einer Zugriffsebene zugeordnet. Benutzergruppen sind ebenfalls einer
Zugriffsebene zugeordnet.

Ist ein Benutzer Mitglied einer Gruppe, die einer Zugriffsebene
zugeordnet ist, sieht der Benutzer jedes Objekt dieser Zugriffsebene. Es
ist wichtig zu verstehen, dass Benutzergruppen hierarchisch in
Unter-Gruppen angeordnet werden können. Dann hat eine Unter-Gruppe
Zugriff auf alle Zugriffsebenen der übergeordneten Benutzergruppen.
Damit müssen einer Unter-Gruppe keine Zugriffsebene zugeordnet werden,
welche die übergeordnete Benutzergruppe schon enthält.

## Wie darauf zugreifen

- Im Administrator-Menü **Benutzer **→** Zugriffsebenen** auswählen,
  dann ...
  - einen Link aus der Spalte **Ebenenname** auswählen, um eine
    vorhandene Ebene zu bearbeiten oder ...
  - auf die Schaltfläche **+ Neu** klicken, um eine neue Zugriffsebene
    zu erstellen.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/f/f0/Help-4x-users-user-manager-add-new-viewing-access-level-de.png/600px-Help-4x-users-user-manager-add-new-viewing-access-level-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f0/Help-4x-users-user-manager-add-new-viewing-access-level-de.png/900px-Help-4x-users-user-manager-add-new-viewing-access-level-de.png 1.5x, https://docs.joomla.org/images/f/f0/Help-4x-users-user-manager-add-new-viewing-access-level-de.png 2x"
data-file-width="1079" data-file-height="828" width="600" height="460"
alt="Help-4x-users-user-manager-add-new-viewing-access-level-de.png" />

## Zugriffsebenen-Details

- **Ebenentitel.** Einen Titel für diese Zugriffsebene eingeben.
- **Benutzergruppen mit Zugriff** Jede Gruppe markieren, welche diese
  Zugriffsebene erhalten soll.

## Benutzergruppen mit Zugriff

Ein Kontrollkästchen markieren, um eine Benutzergruppe zu einer
Zugriffssebene hinzuzufügen. Im gezeigten Beispiel sind alle Gruppen
Untergruppen von „Öffentlich“, so dass es nicht notwendig ist, eine der
Untergruppen zu markieren. Sie erben die Zugriffsberechtigungen von
„Öffentlich“. Diese Funktion sollte nur für benutzerdefinierte Gruppen
verwendet werden!

## Werkzeugleiste

Das [Bildschirmfoto](#Bildschirmfoto) am Anfang der Seite zeigt die
Werkzeugleiste im oberen Bereich. Die Funktionen sind:

- **Speichern**. Speichert den Eintrag und bleibt auf der aktuellen
  Seite.
- **Speichern & Schließen**. Speichert den Eintrag und schließt die
  aktuelle Seite.
- **Speichern & Neu**. Speichert den Eintrag und hält die Seite offen,
  damit ein neuer Eintrag erstellt werden kann.
- **Abbrechen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück.
- **Hilfe**. Öffnet die Hilfeseite.

## Tipps

- Beim Erstellen einer Gruppe muss man möglicherweise jede Zugriffsebene
  bearbeiten, für die diese Gruppe Zugriff haben soll.

## Verwandte Informationen

- [Benutzer: Zugriffsebenen
  anzeigen](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/de "Help4.x:Users: Viewing Access Levels/de")
- [Benutzer:
  Gruppen](https://docs.joomla.org/Help4.x:Users:_Groups/de "Help4.x:Users: Groups/de")
- [Tutorial zur Zugriffssteuerungsliste
  (ACL)](https://docs.joomla.org/J3.x:Access_Control_List_Tutorial/de "J3.x:Access Control List Tutorial/de")
