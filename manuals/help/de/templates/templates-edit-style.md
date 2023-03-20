<!-- Filename: Help4.x:Templates:_Edit_Style / Display title: Templates: Stile bearbeiten -->

## Beschreibung

Hier werden Template-Stile bearbeitet. Bei der ersten Installation eines
Templates wird ein Standardstil erstellt. Der Name ist der des Templates
plus „- Default“ (Standard). Um weitere Stilvarianten zu generieren, das
Kontrollkästchen des Standardstils markieren, die Schaltfläche
*Kopieren* in der Symbolleiste anklicken und die Kopie bearbeiten.

## Wie darauf zugreifen

- Im Administrator-Menü die Option **System **→** Templates **→** Site
  Templates Stile** wählen oder ...
- im Administrator-Menü die Option
  **System **→** Templates **→** Administrator Templates Stile** wählen.
  Dann ...
  - den Namen des zu bearbeitenden Template-Stils in der Spalte „Stil“
    wählen.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/f/f3/Help-4x-Extensions-Template-Manager-Styles-Edit-screen-de.png/800px-Help-4x-Extensions-Template-Manager-Styles-Edit-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f3/Help-4x-Extensions-Template-Manager-Styles-Edit-screen-de.png/1200px-Help-4x-Extensions-Template-Manager-Styles-Edit-screen-de.png 1.5x, https://docs.joomla.org/images/f/f3/Help-4x-Extensions-Template-Manager-Styles-Edit-screen-de.png 2x"
data-file-width="1498" data-file-height="689" width="800" height="368"
alt="Help-4x-Extensions-Template-Manager-Styles-Edit-screen-de.png" />

## Formular Felder

- **Stil**. Der Name des Stils. Dies ist der Name, der in der Spalte
  *Stil* der Templates-Liste angezeigt wird.

### Details Tab

- **Template-Name.** Der Name des Templates, das Indikatorfeld „Site“
  oder „Administrator“ und eine kurze Beschreibung.
- **Standard**. Gibt an, ob der Stil der Standardstil für die Website
  ist oder nicht.
- **Template**. Der Name des Templates, von dem der Stil abstammt.

### Erweitert

Dieser Reiter ist möglicherweise nicht bei allen Stilen vorhanden. Wenn
ein Stil, von dem einem Template abstammt, das konfigurierbare Optionen
besitzt, werden diese hier angezeigt. Es sind diese zusätzlichen
konfigurierbaren Optionen, die es ermöglichen, mehrere verschiedene
Templates-Stile mit Varianten dieser Optionen zu nutzen. Die verfügbaren
Optionen hängen davon ab, was der Template-Entwickler bereitstellt.

### Atum Farbeinstellungen

Mit dem Standard-Template für den Administrator kann man mit
Farbvariationen experimentieren. Abspeichern und beobachten!

### Atum Bild-Einstellungen

Man kann ein Bild auswählen, welches das **Login-Logo** im
Anmeldeformular des Administrators und das **Firmenlogo** in der
Titelleiste des Administrators im erweiterten und im komprimierten Modus
ersetzt. Standardmäßig sind die Joomla Markenzeichen voreingestellt. In
der Titelleiste ist das Wort Joomla! in der **Brand Large** Version
vorhanden und in der **Brand Small** Version ausgelassen. Um die
Änderung zu sehen, auf **Toggle Menu** klicken.

Wenn ein eigenes Markenzeichen (Brand Small) verwendet wird, muss die
Breite des Bildes ebenfalls angepasst werden. Hierzu legt man eine
user.css-Datei im Stammverzeichnis des Templates an und fügt Folgendes
ein, wobei man 3rem durch eine passende Breite für das eigene Bild
ersetzt:

       .header .logo.small {
           width: 3rem;
       }

### Menüzugehörigkeit

Dieser Reiter enthält alle auf der Joomla! Website konfigurierten
Menüeinträge. Um den aktuellen Stil auf die entsprechende Webseite eines
Menüpunkts anzuwenden, das Kästchen neben dem Menüpunkt aktivieren. Die
Schaltfläche *Auswahl umkehren* drücken, um die Auswahl der Menüpunkte
umzutauschen.

**Hinweis**: Wenn ein Kontrollkästchen ausgegraut ist und nicht
angekreuzt werden kann, könnte es daran liegen, dass der Menüeintrag von
einem anderen Benutzer verwendet wird. Um das zu überprüfen, die
[Menü-Manager-Seite für das betreffende
Menü](https://docs.joomla.org/Help4.x:Menus:_Items/de "Help4.x:Menus: Items/de")
aufrufen. Wenn sich neben dem Menüeintrag ein Schloss-Symbol befindet,
wird der Menüeintrag gerade von einem anderen Benutzer verwendet.

## Werkzeugleiste

Das [Bildschirmfoto](#Bildschirmfoto) am Anfang der Seite zeigt die
Werkzeugleiste im oberen Bereich. Die Funktionen sind:

- **Speichern**. Speichert den Eintrag und bleibt auf der aktuellen
  Seite.
- **Speichern & Schließen**. Speichert den Eintrag und schließt die
  aktuelle Seite.
- **Als Kopie speichern**. Speichert Änderungen in einer Kopie des
  aktuellen Eintrags. Der aktuelle Eintrag wird davon nicht beeinflusst.
  Dieses Symbol wird nicht angezeigt, wenn ein neuer Eintrag erstellt
  wird.
- **Abbrechen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück.
- **Hilfe**. Öffnet die Hilfeseite.

## Verwandte Informationen

- Um Templates zu installieren: [Erweiterungen:
  Installieren](https://docs.joomla.org/Help4.x:Extensions:_Install/de "Help4.x:Extensions: Install/de")
