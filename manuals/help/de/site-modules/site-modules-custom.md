<!-- Filename: Help4.x:Site_Modules:_Custom / Display title: Site Modul: Eigenes Modul -->

## Beschreibung

Das „eigene Modul“ ermöglicht es, Inhalte auf HTML-Basis zu erstellen
und diese dann an einer beliebigen Modulposition auf einer Seite zu
platzieren.

Es gibt viele Fälle, in denen Freiform-HTML in eine Webseite eingefügt
werden sollte. Beispielsweise könnte man eine HTML-Image-Map erstellen
oder HTML-Code von PayPal, Amazon oder einer anderen Website kopieren
wollen.

## Wie darauf zugreifen

- Im Administrator-Menü die Option **System **→** Verwalten **→** Site
  Module** wählen, dann...
  - ein neues Modul erstellen mit: Schaltfläche **Neu** in der
    Symbolleiste klicken, dann ...
    - den gewünschten Modultyp auswählen.
  - oder ein vorhandenes Modul bearbeiten:
    - das Modul in der Liste der installierten Module suchen und den
      Titel-Link in der Spalte **Titel** anklicken.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/f/fd/Help-4x-modules-site-module-manager-module-custom-html-de.png/800px-Help-4x-modules-site-module-manager-module-custom-html-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/fd/Help-4x-modules-site-module-manager-module-custom-html-de.png/1200px-Help-4x-modules-site-module-manager-module-custom-html-de.png 1.5x, https://docs.joomla.org/images/f/fd/Help-4x-modules-site-module-manager-module-custom-html-de.png 2x"
data-file-width="1456" data-file-height="1312" width="800" height="721"
alt="Help-4x-modules-site-module-manager-module-custom-html-de.png" />

## Formular Felder

- **Titel**. Der Titel des Moduls. Dies ist auch der Titel, der für das
  Modul angezeigt wird, falls das Formularfeld *Titel anzeigen*
  aktiviert ist.

### Modul

**Linke Seite**

- **Editor.** Der Editor lässt die Eingabe bestimmter HTML-Tags nicht
  zu. Um dies zu umgehen, kann der Editor des Benutzers vorübergehend
  auf "Kein Editor" gesetzt werden, das benutzerdefinierte HTML-Modul
  erstellt und dann der Editor wieder auf TinyMCE umgestellt werden.
  Eine weitere Möglichkeit ist die Verwendung eines Editors über eine
  Erweiterung, welcher die Eingabe von HTML-Code erlaubt. Eine andere
  Möglichkeit besteht darin (falls der Editor diese Option bietet), in
  den HTML-Modus zu wechseln, den Code einzugeben, zu speichern und
  wieder zur normalen Ansicht zu wechseln.

**Rechte Seite**

- **Titel anzeigen** (*Anzeigen*/*Verbergen*). Zeigt den Titel des
  Moduls an oder unterdrückt die Anzeige im Frontend. Der angezeigte
  Titel entspricht dem Titel im Formularfeld oben.

<!-- -->

- **Position**. Die
  [Modul-Position](https://docs.joomla.org/Module_Position/de "Module Position/de")
  wählen, auf der dieses Modul angezeigt werden soll. Eine
  benutzerdefinierte Modulposition kann unter Verwendung mit dem
  [Load-Position-Plugin](https://docs.joomla.org/How_do_you_put_a_module_inside_an_article%3F/de "How do you put a module inside an article?/de")
  eingegeben werden. Alternativ kann die Positionstaste gedrückt werden,
  um eine Modulposition aus dem Template auszuwählen.

<!-- -->

- **Status**. Der Veröffentlichungs-Status des Eintrags.

<!-- -->

- **Zugriffsebene**. Die [Zugriffsebene für die
  Anzeige](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/de "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/de")
  des Eintrags.

<!-- -->

- **Module Reihenfolge** Zeigt eine DropDown-Liste aller Module an der
  Position, an der sich das aktuelle Modul befindet. In dieser
  Reihenfolge werden die Module angezeigt, sowohl im Frontend als auch
  auf der
  [Module](https://docs.joomla.org/Help4.x:Modules/de "Help4.x:Modules/de")-Seite.

<!-- -->

- **Veröffentlichung starten**. Datum und Uhrzeit, um die
  Veröffentlichung zu starten. Dieses Feld verwenden, um Inhalt vor der
  Zeit zu erstellen und ihn später automatisch zu veröffentlichen.

<!-- -->

- **Veröffentlichung beenden**. Datum und Uhrzeit, um die
  Veröffentlichung zu beenden. Dieses Feld verwenden, um dem Inhalt
  automatisch den Status „Versteckt“ zuzuweisen (zum Beispiel, wenn der
  Inhalt nicht mehr aktuell ist).

<!-- -->

- **Sprache**. Die Sprachzuordnung des Eintrags.

<!-- -->

- **Notiz**. Die Notiz wird meist vom Site-Administrator verwendet, um
  beispielsweise Informationen über den Eintrag zu notieren. Die Notiz
  wird nicht im Frontend der Seite angezeigt.

### Menüzuweisung

<img
src="https://docs.joomla.org/images/thumb/e/e4/Help-4x-modules-manager-site-module-menu-assignment-tab-de.png/600px-Help-4x-modules-manager-site-module-menu-assignment-tab-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/e4/Help-4x-modules-manager-site-module-menu-assignment-tab-de.png/900px-Help-4x-modules-manager-site-module-menu-assignment-tab-de.png 1.5x, https://docs.joomla.org/images/thumb/e/e4/Help-4x-modules-manager-site-module-menu-assignment-tab-de.png/1200px-Help-4x-modules-manager-site-module-menu-assignment-tab-de.png 2x"
data-file-width="1330" data-file-height="1048" width="600" height="473"
alt="Help-4x-modules-manager-site-module-menu-assignment-tab-de.png" />

- **Menüzuweisung**. Eine der Optionen **Auf allen Seiten**, **Auf
  keiner Seite**, **Nur auf den gewählten Seiten** oder **Auf allen,
  außer den gewählten Seiten** aus der Liste wählen.

<!-- -->

- **Menüauswahl**. Wenn eine der beiden letztgenannten Optionen
  ausgewählt wird, erscheint eine Liste mit allen Menüeinträgen. Auf
  diese Weise kann man bestimmten Seiten Module zuweisen. Durch Auswahl
  der Menülinks, denen das Modul zugeordnet werden soll, kann man
  anpassen, auf welchen Seiten Module erscheinen/nicht erscheinen.
  Weitere Informationen sind unter [Wie wird ein Modul mit einer Seite
  verknüpft?](https://docs.joomla.org/How_do_you_assign_a_module_to_specific_pages%3F/de "How do you assign a module to specific pages?/de")
  zu finden.

### Optionen

- **Inhalte vorbereiten.** (*Ja*/*Nein*). Optional den Inhalt mit den
  aktivierten Inhaltsplugins vorbereiten.
- **Hintergrundbild auswählen** Wenn hier ein Bild ausgewählt ist, wird
  es automatisch als Inline-Stil für das umschließende div-Element
  eingefügt.

### Erweitert

<img
src="https://docs.joomla.org/images/thumb/c/ce/Help-4x-modules-manager-admin-module-site-advanced-options-de.png/600px-Help-4x-modules-manager-admin-module-site-advanced-options-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/ce/Help-4x-modules-manager-admin-module-site-advanced-options-de.png/900px-Help-4x-modules-manager-admin-module-site-advanced-options-de.png 1.5x, https://docs.joomla.org/images/c/ce/Help-4x-modules-manager-admin-module-site-advanced-options-de.png 2x"
data-file-width="1168" data-file-height="843" width="600" height="433"
alt="Help-4x-modules-manager-admin-module-site-advanced-options-de.png" />

- **Layout.** Wenn ein oder mehrere alternative Layouts für ein Modul
  definiert wurden, entweder im Template oder im Joomla!-Core, kann ein
  Layout für dieses Modul ausgewählt werden.
- **CSS-Klasse Modul**. Ein Suffix, das auf die CSS-Klasse des Moduls
  angewendet wird. Dadurch können benutzerdefinierte CSS-Stile erstellt
  werden, die nur für dieses Modul gelten. Anschließend müsste die Datei
  „user.css“ des Templates geändert werden, um das Styling für diese
  neue Klasse anzulegen. Diesen Parameter mit einem führenden
  Leerzeichen eingeben, um eine neue CSS-Klasse für dieses Modul zu
  erstellen. Ohne führendes Leerzeichen ist der Parameter einzugeben,
  wenn der CSS-Klassennamen für dieses Modul geändert werden soll.
- **Caching** *Globale Einstellung*/*Keine Zwischenspeicherung*. Legt
  fest, ob der Inhalt dieses Moduls zwischengespeichert werden soll oder
  nicht. Die globale Einstellung verwendet die Cache-Einstellungen aus
  der globalen Konfiguration.
- **Cache-Dauer**. Die Anzahl der Minuten bis der Zwischenspeicher
  (Cache) frühestens erneuert wird. Der Standardwert kann gefahrlos
  beibehalten werden.
- **Modulstil**. Mit dieser Option kann der Stil des Templates für die
  Modul-Position überschrieben werden.
- **Modul-Tag**. Das HTML-Tag für das Modul, in das es eingefügt werden
  soll. Standardmäßig ist dies ein div-Tag, aber es können auch andere
  HTML5-Elemente verwendet werden.
- **Bootstrap-Größe.** (Werte 0 bis 12) Damit kann die Breite des Moduls
  über das in Bootstrap verwendete span-Element festgelegt werden.
- **Header Tag.** Der HTML-Tag, der für den Modulkopf oder -titel
  verwendet werden soll. Dies kann ein Tag des Typs h1, h2, h3, h4, h5,
  h6 oder p sein. Dafür muss ein "html5"-Modul-Stil (Chrome) verwendet
  oder ein eigener Modul-Stil in der Datei *templates//html/modules.php*
  hinzugefügt werden.
- **CSS-Klasse Header**. Hier können optionale CSS-Klassen für den
  Modulkopf oder das Titelelement hinzugefügt werden.

### Modulberechtigungen

<img
src="https://docs.joomla.org/images/thumb/1/1d/Help-4x-modules-manager-admin-module-administrator-permissions-de.png/600px-Help-4x-modules-manager-admin-module-administrator-permissions-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/1d/Help-4x-modules-manager-admin-module-administrator-permissions-de.png/900px-Help-4x-modules-manager-admin-module-administrator-permissions-de.png 1.5x, https://docs.joomla.org/images/thumb/1/1d/Help-4x-modules-manager-admin-module-administrator-permissions-de.png/1200px-Help-4x-modules-manager-admin-module-administrator-permissions-de.png 2x"
data-file-width="1236" data-file-height="789" width="600" height="383"
alt="Help-4x-modules-manager-admin-module-administrator-permissions-de.png" />

Um die Berechtigungen zu ändern:

- Die **Gruppe** durch Anklicken des Namens auf der linken Seite
  auswählen.
- Die gewünschte **Aktion** aussuchen. Mögliche Aktionen sind:
  - **Löschen**. Benutzer können dieses Modul löschen.
  - **Bearbeiten**. Benutzer können dieses Modul bearbeiten.
  - **Status bearbeiten**. Benutzer können den Veröffentlichungs-Status
    und zugehörige Informationen dieses Moduls ändern.
- Die gewünschte Berechtigung der gewählten Aktion aussuchen. Mögliche
  Einstellungen sind:
  - ***Vererbt***. Die Berechtigungen werden für Benutzer in dieser
    Gruppe von der globalen Konfiguration, den Optionen des
    Beitrags-Managers oder der Kategorie vererbt.
  - ***Erlaubt:*** Erlaubt für Benutzer dieser Gruppe. *Hinweis:* Wenn
    diese Aktion auf einer der höheren Ebenen verweigert wird, ist die
    Berechtigung „Erlaubt“ hier nicht wirksam. Eine
    Verweigert-Einstellung kann nicht außer Kraft gesetzt werden.
  - ***Verweigert***. Verweigert für Benutzer dieser Gruppe.
- Auf **Speichern** in der **Symbolleiste** oben klicken. Danach
  aktualisiert sich die Anzeige, erst dann werden die errechneten
  Einstellungen angezeigt.

## Werkzeugleiste

Das [Bildschirmfoto](#Bildschirmfoto) am Anfang der Seite zeigt die
Werkzeugleiste im oberen Bereich. Die Funktionen sind:

- **Speichern**. Speichert den Eintrag und bleibt auf der aktuellen
  Seite.

<!-- -->

- **Speichern & Schließen**. Speichert den Eintrag und schließt die
  aktuelle Seite.

<!-- -->

- **Speichern & Neu**. Speichert den Eintrag und hält die Seite offen,
  damit ein neuer Eintrag erstellt werden kann.

<!-- -->

- **Als Kopie speichern**. Speichert Änderungen in einer Kopie des
  aktuellen Eintrags. Der aktuelle Eintrag wird davon nicht beeinflusst.
  Dieses Symbol wird nicht angezeigt, wenn ein neuer Eintrag erstellt
  wird.

<!-- -->

- **Schließen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück. Dieses Symbol wird nicht
  angezeigt, wenn ein neuer Eintrag erstellt wird.

<!-- -->

- **Hilfe**. Öffnet die Hilfeseite.

## Frontend-Ansicht

Ein Beispiel für eine benutzerdefinierte HTML-Nachricht ist nachstehend
abgebildet.

<img
src="https://docs.joomla.org/images/a/a1/Help-4x-Extensions-Module-Manager-Custom-Html-output-en.png"
decoding="async" data-file-width="300" data-file-height="120"
width="300" height="120"
alt="Help-4x-Extensions-Module-Manager-Custom-Html-output-en.png" />

In diesem Beispiel würde das benutzerdefinierte Modul nach dem
Software-Update „versteckt“ werden.
