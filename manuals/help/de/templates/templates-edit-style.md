<!-- Display title: Templates: Edit Style -->

## Beschreibung

Hier werden Template-Stile bearbeitet. Bei der ersten Installation eines
Templates wird ein Standardstil erstellt. Der Name ist der des Templates
plus â€ž- Defaultâ€œ (Standard). Um weitere Stilvarianten zu generieren,
das KontrollkÃ¤stchen des Standardstils markieren, die SchaltflÃ¤che
*Kopieren* in der Symbolleiste anklicken und die Kopie bearbeiten.

## Wie darauf zugreifen

- Im Administrator-MenÃ¼ die Option **System **→** Templates **→** Site
  Templates Stile** wÃ¤hlen oder ...
- im Administrator-MenÃ¼ die Option
  **System **→** Templates **→** Administrator Templates Stile**
  wÃ¤hlen. Dann ...
  - den Namen des zu bearbeitenden Template-Stils in der Spalte
    â€žStilâ€œ wÃ¤hlen.

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

- **Template-Name.** Der Name des Templates, das Indikatorfeld
  â€žSiteâ€œ oder â€žAdministratorâ€œ und eine kurze Beschreibung.
- **Standard**. Gibt an, ob der Stil der Standardstil fÃ¼r die Website
  ist oder nicht.
- **Template**. Der Name des Templates, von dem der Stil abstammt.

### Erweitert

Dieser Reiter ist mÃ¶glicherweise nicht bei allen Stilen vorhanden. Wenn
ein Stil, von dem einem Template abstammt, das konfigurierbare Optionen
besitzt, werden diese hier angezeigt. Es sind diese zusÃ¤tzlichen
konfigurierbaren Optionen, die es ermÃ¶glichen, mehrere verschiedene
Templates-Stile mit Varianten dieser Optionen zu nutzen. Die
verfÃ¼gbaren Optionen hÃ¤ngen davon ab, was der Template-Entwickler
bereitstellt.

### Atum Farbeinstellungen

Mit dem Standard-Template fÃ¼r den Administrator kann man mit
Farbvariationen experimentieren. Abspeichern und beobachten!

### Atum Bild-Einstellungen

Man kann ein Bild auswÃ¤hlen, welches das **Login-Logo** im
Anmeldeformular des Administrators und das **Firmenlogo** in der
Titelleiste des Administrators im erweiterten und im komprimierten Modus
ersetzt. StandardmÃ¤ÃŸig sind die Joomla Markenzeichen voreingestellt.
In der Titelleiste ist das Wort Joomla! in der **Brand Large** Version
vorhanden und in der **Brand Small** Version ausgelassen. Um die
Ã„nderung zu sehen, auf **Toggle Menu** klicken.

Wenn ein eigenes Markenzeichen (Brand Small) verwendet wird, muss die
Breite des Bildes ebenfalls angepasst werden. Hierzu legt man eine
user.css-Datei im Stammverzeichnis des Templates an und fÃ¼gt Folgendes
ein, wobei man 3rem durch eine passende Breite fÃ¼r das eigene Bild
ersetzt:

       .header .logo.small {
           width: 3rem;
       }

### MenÃ¼zugehÃ¶rigkeit

Dieser Reiter enthÃ¤lt alle auf der Joomla! Website konfigurierten
MenÃ¼eintrÃ¤ge. Um den aktuellen Stil auf die entsprechende Webseite
eines MenÃ¼punkts anzuwenden, das KÃ¤stchen neben dem MenÃ¼punkt
aktivieren. Die SchaltflÃ¤che *Auswahl umkehren* drÃ¼cken, um die
Auswahl der MenÃ¼punkte umzutauschen.

**Hinweis**: Wenn ein KontrollkÃ¤stchen ausgegraut ist und nicht
angekreuzt werden kann, kÃ¶nnte es daran liegen, dass der MenÃ¼eintrag
von einem anderen Benutzer verwendet wird. Um das zu Ã¼berprÃ¼fen, die
[MenÃ¼-Manager-Seite fÃ¼r das betreffende
MenÃ¼](https://docs.joomla.org/Help4.x:Menus:_Items/de "Help4.x:Menus: Items/de")
aufrufen. Wenn sich neben dem MenÃ¼eintrag ein Schloss-Symbol befindet,
wird der MenÃ¼eintrag gerade von einem anderen Benutzer verwendet.

## Werkzeugleiste

Das [Bildschirmfoto](#Bildschirmfoto) am Anfang der Seite zeigt die
Werkzeugleiste im oberen Bereich. Die Funktionen sind:

- **Speichern**. Speichert den Eintrag und bleibt auf der aktuellen
  Seite.

<!-- -->

- **Speichern & SchlieÃŸen**. Speichert den Eintrag und schlieÃŸt die
  aktuelle Seite.

<!-- -->

- **Als Kopie speichern**. Speichert Ã„nderungen in einer Kopie des
  aktuellen Eintrags. Der aktuelle Eintrag wird davon nicht beeinflusst.
  Dieses Symbol wird nicht angezeigt, wenn ein neuer Eintrag erstellt
  wird.

<!-- -->

- **Abbrechen**. SchlieÃŸt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Ã„nderungen zurÃ¼ck.

<!-- -->

- **Hilfe**. Ã–ffnet die Hilfeseite.

## Verwandte Informationen

- Um Templates zu installieren: [Erweiterungen:
  Installieren](https://docs.joomla.org/Help4.x:Extensions:_Install/de "Help4.x:Extensions: Install/de")
