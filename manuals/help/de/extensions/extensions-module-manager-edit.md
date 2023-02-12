<!-- Filename: Help4.x:Extensions_Module_Manager_Edit / Display title: Erweiterungen: Module bearbeiten -->

## Beschreibung

Der Erweiterungs-Manager „Modul Bearbeiten“ ermöglicht die Bearbeitung
eines vorhandenen Moduls oder die Erstellung eines neuen Moduls
entsprechend dem gewählten Modultyp.

## Wie darauf zugreifen

- Im Administrator-Menü die Option **System **→** Verwalten **→** Site
  Module** wählen oder ...
- im Administrator-Menü die Option
  **System **→** Verwalten **→** Administrator Module** wählen. Dann ...
  - die Schaltfläche **„+ Neu“** in der Symbolleiste wählen, um ein
    neues Modul zu erstellen  
    oder ...
  - einen Modulnamen in der Spalte **Titel** auswählen, um dieses Modul
    zu bearbeiten.

Bei einem neuen Modul wird eine Liste mit allen installierten Modulen
für das Frontend (Site) oder das Backend (Administrator) angezeigt, die
zur Auswahl stehen:

<img
src="https://docs.joomla.org/images/thumb/3/37/Help-4x-extensions-module-manager-new-de.png/800px-Help-4x-extensions-module-manager-new-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/3/37/Help-4x-extensions-module-manager-new-de.png/1200px-Help-4x-extensions-module-manager-new-de.png 1.5x, https://docs.joomla.org/images/thumb/3/37/Help-4x-extensions-module-manager-new-de.png/1600px-Help-4x-extensions-module-manager-new-de.png 2x"
data-file-width="1647" data-file-height="1029" width="800" height="500"
alt="Help-4x-extensions-module-manager-new-de.png" />

Eines davon auswählen, um zum Bearbeitungsbildschirm zu wechseln.

## Bildschirmfoto

Die Registerkarte „Modul“ eines Bildschirmes zur Modulbearbeitung ist
abhängig vom Modultyp. Das Site-Modul "Breadcrumbs" (Navigationspfad)
ist hier abgebildet. Für andere Module siehe **[Verwandte
Informationen](#Verwandte_Informationen)** unten für Links zu bestimmten
Modultypen.

<img
src="https://docs.joomla.org/images/thumb/8/84/Help-4x-extensions-module-manager-edit-de.png/800px-Help-4x-extensions-module-manager-edit-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/84/Help-4x-extensions-module-manager-edit-de.png/1200px-Help-4x-extensions-module-manager-edit-de.png 1.5x, https://docs.joomla.org/images/8/84/Help-4x-extensions-module-manager-edit-de.png 2x"
data-file-width="1378" data-file-height="1254" width="800" height="728"
alt="Help-4x-extensions-module-manager-edit-de.png" />

## Formular Felder

- **Titel**. Der Titel des Eintrages. Er kann auf der Seite abhängig von
  den gewählten Parameterwerten angezeigt werden.

### Modul

**Linke Seite**

Der Aufbau des linken Bereichs hängt vom Modultyp ab und wird hier nicht
beschrieben.

**Rechte Seite**

Der rechte Bereich ist bei allen Modulen gleich.

- **Titel anzeigen**. Anzeigen oder Verbergen des Modultitels im
  Frontend.

<!-- -->

- **Position**. Die
  [Modul-Position](https://docs.joomla.org/Module_Position/de "Module Position/de")
  wählen, auf der dieses Modul angezeigt werden soll. Eine
  benutzerdefinierte Modulposition kann unter Verwendung mit dem
  [Load-Position-Plugin](https://docs.joomla.org/How_do_you_put_a_module_inside_an_article%3F/de "How do you put a module inside an article?/de")
  eingegeben werden. Alternativ kann die Positionstaste gedrückt werden,
  um eine Modulposition aus dem Template auszuwählen.

<!-- -->

- **Status**. Der Veröffentlichungs-Status des Eintrages.
  - *Veröffentlicht:* Der Eintrag ist im Frontend der Seite sichtbar.
  - *Versteckt:* Der Eintrag ist im Frontend der Seite für Besucher
    nicht sichtbar. Es kann für angemeldete Benutzer sichtbar sein, die
    eine Berechtigung zur Bearbeitung des Eintrags haben.
  - *Archiviert:* Der Eintrag wird nicht länger in Blog- oder
    Listen-Menüs angezeigt.
  - *Papierkorb:* Der Eintrag wurde gelöscht, befindet sich aber noch in
    der Datenbank. Dauerhaft wird es über den Button 'Papierkorb leeren'
    der Symbolleiste gelöscht (siehe auch [Einen Beitrag
    löschen](https://docs.joomla.org/Deleting_an_Article/de "Special:MyLanguage/Deleting an Article/de")).

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

- **Zugriffsebene**. Die angezeigte Zugriffsebene für diesen Eintrag aus
  dem Listenfeld auswählen. Welche Zugriffsebenen angezeigt werden,
  hängt davon ab, was für diese Site in [Benutzer →
  Zugriffsebenen](https://docs.joomla.org/Help40:Users:_Viewing_Access_Levels/de "Special:MyLanguage/Help40:Users: Viewing Access Levels/de")
  eingerichtet wurde. Bitte beachten, dass Zugriffsebenen nicht mit
  ACL-Berechtigungen gleichzusetzen sind. Zugriffsebenen steuern, was
  ein Benutzer sehen kann. ACL-Berechtigungen steuern, welche Aktionen
  ein Benutzer durchführen kann.

<!-- -->

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

<!-- -->

- **Sprache**. Die Sprache für diesen Eintrag wählen. Wird die Funktion
  Mehrsprachigkeit nicht verwendet, den Standardwert 'Alle' beibehalten.

<!-- -->

- **Notiz**. Die Notiz wird meist vom Site-Administrator verwendet, um
  beispielsweise Informationen über den Eintrag zu notieren. Die Notiz
  wird nicht im Frontend der Seite angezeigt.

### Menüzuweisung

Diese Registerkarten-Ansicht enthält alle Menüeinträge, die auf der
Joomla!-Website konfiguriert sind. Dadurch kann man auswählen, wo ein
Modul auf der mit dem Menüeintrag verbundenen Inhaltsseite angezeigt
werden soll.

<img
src="https://docs.joomla.org/images/thumb/e/ee/Help-4x-Module-Manager-Edit-menu-assignment-de.png/600px-Help-4x-Module-Manager-Edit-menu-assignment-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/ee/Help-4x-Module-Manager-Edit-menu-assignment-de.png/900px-Help-4x-Module-Manager-Edit-menu-assignment-de.png 1.5x, https://docs.joomla.org/images/thumb/e/ee/Help-4x-Module-Manager-Edit-menu-assignment-de.png/1200px-Help-4x-Module-Manager-Edit-menu-assignment-de.png 2x"
data-file-width="1232" data-file-height="1058" width="600" height="515"
alt="Help-4x-Module-Manager-Edit-menu-assignment-de.png" />

#### Modulzuweisung

- **Modulzuweisung**. Zur Auswahl der Modulzuordnung einfach hier
  klicken.

<!-- -->

- **Auf allen Seiten.** Das Modul wird auf allen Seiten in der gewählten
  Position gezeigt.
- **Auf keinen Seiten**. Module werden **auf keiner Seite** an der
  gewählten Modulposition angezeigt.
- **Nur auf den gewählten Seiten**. Das Modul wird nur auf den Seiten in
  der ausgewählten Modulposition angezeigt, wie sie durch den
  Menüeintragstyp (Titel) festgelegt wurde. Siehe **Menüauswahl** unten.
- **Auf allen, außer den gewählten Seiten**. Das Modul wird auf allen
  Seiten in der gewählten Position gezeigt, ausgenommen der in der
  Menüauswahl gewählten Seiten. Siehe **Menüauswahl** unten.

#### Menüauswahl

- **Menüauswahl**. Wird nur angezeigt, wenn in der **Modulzuweisung**,
  wie oben gezeigt, **Nur auf den gewählten Seiten** oder **Auf allen,
  außer den gewählten Seiten** eingestellt ist.

Um das Modul der entsprechenden Webseite (Titel) eines Menüeintrags
zuzuordnen, muss das Kontrollkästchen neben dem Menüeintrag aktiviert
werden.

- Zuordnen zu Menüeinträgen: *Alle* oder *Keine* anklicken, um die
  Auswahl der Menüeinträge zu verändern.
- Untermenüs aufklappen: *Alle* oder *Keine* anklicken, um die
  Strukturansicht für die Auswahl der Menüeinträge anzuzeigen.

**Hinweis**: Wenn ein Kontrollkästchen ausgegraut ist und nicht
angekreuzt werden kann, könnte es daran liegen, dass der Menüeintrag von
einem anderen Benutzer verwendet wird. Um das zu überprüfen, die
[Menü-Manager-Seite für das betreffende
Menü](https://docs.joomla.org/Help4.x:Menus:_Items/de "Help4.x:Menus: Items/de")
aufrufen. Wenn sich neben dem Menüeintrag ein Schloss-Symbol befindet,
wird der Menüeintrag gerade von einem anderen Benutzer verwendet.

### Erweitert

<img
src="https://docs.joomla.org/images/thumb/c/ce/Help-4x-Module-Manager-Edit-advanced-de.png/600px-Help-4x-Module-Manager-Edit-advanced-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/ce/Help-4x-Module-Manager-Edit-advanced-de.png/900px-Help-4x-Module-Manager-Edit-advanced-de.png 1.5x, https://docs.joomla.org/images/thumb/c/ce/Help-4x-Module-Manager-Edit-advanced-de.png/1200px-Help-4x-Module-Manager-Edit-advanced-de.png 2x"
data-file-width="1253" data-file-height="635" width="600" height="304"
alt="Help-4x-Module-Manager-Edit-advanced-de.png" />

### Modulberechtigungen

<img
src="https://docs.joomla.org/images/thumb/8/86/Help-4x-Module-Manager-Edit-permissions-de.png/600px-Help-4x-Module-Manager-Edit-permissions-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/86/Help-4x-Module-Manager-Edit-permissions-de.png/900px-Help-4x-Module-Manager-Edit-permissions-de.png 1.5x, https://docs.joomla.org/images/thumb/8/86/Help-4x-Module-Manager-Edit-permissions-de.png/1200px-Help-4x-Module-Manager-Edit-permissions-de.png 2x"
data-file-width="1258" data-file-height="788" width="600" height="376"
alt="Help-4x-Module-Manager-Edit-permissions-de.png" />

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

- **Abbrechen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück. Oder

<!-- -->

- **Schließen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück. Dieses Symbol wird nicht
  angezeigt, wenn ein neuer Eintrag erstellt wird.

<!-- -->

- **Hilfe**. Öffnet die Hilfeseite.

## Verwandte Informationen

<table class="wikitable">

<tbody>
<tr class="header">
<th>Verwandte Hilfeseiten</th>
<th>Beschreibung</th>
</tr>
&#10;<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Archived/de"
title="Help4.x:Site Modules: Articles - Archived/de">Site-Modul:
Beiträge – Archiv</a></td>
<td>Dieses Modul zeigt eine Liste der Kalendermonate, die archivierte
Beiträge enthalten. Nach dem Archivieren von Beiträgen wird diese Liste
automatisch generiert.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Categories/de"
title="Help4.x:Site Modules: Articles - Categories/de">Site-Modul:
Beiträge – Kategorien</a></td>
<td>Dieses Modul zeigt eine Liste aller Unterkategorien einer
übergeordneten Kategorie an.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Category/de"
title="Help4.x:Site Modules: Articles - Category/de">Site-Modul:
Beiträge – Kategorie</a></td>
<td>Dieses Modul zeigt eine Liste von Beiträgen aus einer oder mehreren
Kategorien an.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Newsflash/de"
title="Help4.x:Site Modules: Articles - Newsflash/de">Site-Modul:
Beiträge – Newsflash</a></td>
<td>Das Beitragsmodul „Newsflash“ zeigt eine feste Anzahl von Beiträgen
aus einer oder mehrerer Kategorien an.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Related/de"
title="Help4.x:Site Modules: Articles - Related/de">Site-Modul:
Verwandte Beiträge</a></td>
<td>Dieses Modul zeigt eine Liste von Beiträgen an, die mit dem aktuell
angesehenen Beitrag verwandt sind (z.B. ein Beitrags-Layout oder ein
Blog- oder Listen-Layout, bei dem der Benutzer auf einen Beitragslink
geklickt hat). Beiträge gelten als miteinander verwandt, wenn sie
mindestens ein Schlüsselwort in den Metadateninformationen des Beitrags
gemeinsam haben. Schlüsselwörter werden im Abschnitt mit den
Metadaten-Informationen von <a
href="https://docs.joomla.org/Help4.x:Content_Article_Manager_Edit#Ver.C3.B6ffentlichung.2Fde"
class="mw-redirect"
title="Help4.x:Content Article Manager Edit">Beiträge: Bearbeiten</a>
eingegeben.</td>
</tr>
<tr class="even">
<td><a href="https://docs.joomla.org/Help4.x:Site_Modules:_Banners/de"
title="Help4.x:Site Modules: Banners/de">Site-Modul: Banner</a></td>
<td>Das Bannermodul zeigt die aktiven Banner der Komponente an..</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Breadcrumbs/de"
title="Help4.x:Site Modules: Breadcrumbs/de">Site-Modul: Navigationspfad
(Breadcrumbs)</a></td>
<td>Dieses Modul zeigt eine Reihe von Navigationslinks an, welche die
Position auf der Site visualisieren und eine Rückwärtsnavigation
ermöglichen.</td>
</tr>
<tr class="even">
<td><a href="https://docs.joomla.org/Help4.x:Site_Modules:_Custom/de"
title="Help4.x:Site Modules: Custom/de">Site-Modul: Eigenes
Modul</a></td>
<td>Mit diesem Modul kann ein Modul erstellt werden, das beliebigen,
gültigen HTML-Code enthält. Es gibt viele Fälle, in denen Freiform-HTML
in eine Webseite eingefügt werden sollte. Beispielsweise könnte man eine
HTML-Image-Map erstellen oder HTML-Code von PayPal, Amazon oder einer
anderen Website kopieren wollen.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Feed_Display/de"
title="Help4.x:Site Modules: Feed Display/de">Site-Modul: Externen Feed
anzeigen</a></td>
<td>Dieses Modul zeigt einen RSS-News-Feed von einer Website an. Dieses
Modul steht in keinem Verhältnis zur News-Feeds-Komponente oder den
News-Feeds-Layouts und ist eine Alternative, mit der ein Feed auf einer
Modulposition angezeigt werden kann.</td>
</tr>
<tr class="even">
<td><a href="https://docs.joomla.org/Help4.x:Site_Modules:_Footer/de"
title="Help4.x:Site Modules: Footer/de">Site-Modul: Fußzeile</a></td>
<td>Dieses Modul zeigt die Copyright- und Joomla!-Lizenzinformationen
der Website an.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Language_Switcher/de"
title="Help4.x:Site Modules: Language Switcher/de">Site-Modul:
Sprachauswahl</a></td>
<td>Mit diesem Modul kann zwischen den verfügbaren Inhaltssprachen
gewechselt werden. Durch die Auswahl einer Sprache gelangt man zur
Startseite der jeweiligen Sprache.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Latest/de"
title="Help4.x:Site Modules: Articles - Latest/de">Site-Modul: Beiträge
– Neueste</a></td>
<td>Dieses Modul zeigt eine Liste der zuletzt veröffentlichten Beiträge
an.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Latest_Users/de"
title="Help4.x:Site Modules: Latest Users/de">Site-Modul: Benutzer –
Neueste</a></td>
<td>Dieses Modul zeigt die zuletzt registrierten Benutzer an, die sich
auf der Website angemeldet haben.</td>
</tr>
<tr class="even">
<td><a href="https://docs.joomla.org/Help4.x:Site_Modules:_Login/de"
title="Help4.x:Site Modules: Login/de">Site-Modul: Benutzer –
Anmeldung</a></td>
<td>Dieses Modul zeigt ein Login-Formular mit Benutzernamen und Passwort
an. Er zeigt auch einen Link zum Abrufen eines vergessenen Passworts an.
Wenn die Benutzerregistrierung in den Benutzereinstellungen des
Bildschirms „Konfiguration“ aktiviert ist, wird der Link „Registrieren“
angezeigt, um Benutzer zur Selbstregistrierung einzuladen.</td>
</tr>
<tr class="odd">
<td><a href="https://docs.joomla.org/Help4.x:Site_Modules:_Menu/de"
title="Help4.x:Site Modules: Menu/de">Site-Modul: Menü</a></td>
<td>Dieses Modul dient dazu, ein Menü an der gewünschten Position und
auf den gewünschten Webseiten zu positionieren. Jede Joomla!-Website hat
mindestens ein Menü, das auf der <a
href="https://docs.joomla.org/Help4.x:Menus/de"
title="Help4.x:Menus/de">Menü-Manager</a>-Seite erstellt wird. Mit dem
Menü-Modul lässt sich das ausgewählte Menü ganz oder teilweise an der
gewünschten Position und auf den vorgesehenen Web-Seiten
platzieren.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Most_Read/de"
title="Help4.x:Site Modules: Articles - Most Read/de">Site-Modul:
Beiträge – Beliebte</a></td>
<td>Dieses Modul zeigt eine Liste der Beiträge mit den höchsten
Besucherzahlen an.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Random_Image/de"
title="Help4.x:Site Modules: Random Image/de">Site-Modul:
Zufallsbild</a></td>
<td>Dieses Modul zeigt ein zufälliges Bild aus dem gewählten Verzeichnis
an.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/index.php?title=Help4.x:Extensions_Module_Manager_Search/en&amp;action=edit&amp;redlink=1"
class="new"
title="Help4.x:Extensions Module Manager Search/en (page does not exist)">Erweiterungen
Modulmanager Suche</a></td>
<td>Dieses Modul zeigt ein Eingabefeld für die Suche an, in das der
Benutzer einen Ausdruck eingeben und die Eingabetaste drücken kann, um
die Website zu durchsuchen.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Smart_Search/de"
title="Help4.x:Site Modules: Smart Search/de">Site-Modul:
Suchindex</a></td>
<td>Das Modul Suchindex ermöglicht eine erweiterte Suche auf der
Webseite.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Statistics/de"
title="Help4.x:Site Modules: Statistics/de">Site-Modul:
Statistiken</a></td>
<td>Das Statistikmodul zeigt Informationen über die Serverinstallation
zusammen mit Statistiken über die Website-Benutzer, die Anzahl der
Beiträge in der Datenbank und die Anzahl der bereitgestellten
Weblinks.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Syndication_Feeds/de"
title="Help4.x:Site Modules: Syndication Feeds/de">Site-Modul: Feeds –
Feed erzeugen</a></td>
<td>Dieses Modul erstellt einen RSS-Feed-Link für die Seite. Damit kann
ein Benutzer einen Newsfeed für die aktuelle Seite erstellen. Ein
Beispiel wird unten gezeigt.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Tags_-_Popular/de"
title="Help4.x:Site Modules: Tags - Popular/de">Site-Modul: Schlagwörter
– Beliebte</a></td>
<td>Stellt die auf einer Site verwendeten Tags in einer Tag-Wolke oder
Liste dar.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Tags_-_Similar/de"
title="Help4.x:Site Modules: Tags - Similar/de">Site-Modul: Schlagwörter
– Ähnliche</a></td>
<td>Zeigt Links zu anderen Einträgen mit ähnlichen Schlagwörtern
an.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/index.php?title=Help4.x:Extensions_Module_Manager_Weblinks/de&amp;action=edit&amp;redlink=1"
class="new"
title="Help4.x:Extensions Module Manager Weblinks/de (page does not exist)">Erweiterungen
Modulmanager Weblinks</a></td>
<td>Das Weblinks-Modul zeigt Weblinks aus der Weblinks-Komponente
an.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Who%27s_Online/en"
title="Help4.x:Site Modules: Who&#39;s Online/en">Site Modules: Who's
Online</a></td>
<td>The "Who's Online" module displays information about users that are
visiting your site at a particular moment.</td>
</tr>
<tr class="even">
<td><a href="https://docs.joomla.org/Help4.x:Site_Modules:_Wrapper/en"
title="Help4.x:Site Modules: Wrapper/en">Site Modules: Wrapper</a></td>
<td>The wrapper module allows you to display an external website in a
module. The functionality is the same to that of the 'iFrame Wrapper'
you can add as a menu item. If the page to which the wrapper is linked
is too big, bars will be shown below and to the right of the wrapper,
allowing you to "navigate" the page.</td>
</tr>
<tr class="odd">
<td><a href="https://docs.joomla.org/Help4.x:Modules/en"
title="Help4.x:Modules/en">Modules</a></td>
<td>The Module Manager is where you add and edit Joomla! Modules. In
Joomla!, Modules are used to display content and/or media around the
main content.
<p><strong>Module Facts:</strong> All Joomla! websites require at least
1 Menu Module All Other Module Types are Optional. (Examples: News,
Banner, Latest News) Every Menu is accompanied by a menu module.
(Example mod_mainmenu) Multiple occurrences of similar module types.</p>
<p><strong>Some Modules are linked to components.</strong> For example,
each Menu Module is related to one Menu component. To define a Menu in
Joomla!, you need to create the Menu and Menu Items using the Menus
screens and then create the Module for the Menu using this screen. Other
Modules, such as Custom and Breadcrumbs, do not depend on any other
content. See <a href="https://docs.joomla.org/screen.modules.edit.15"
title="Special:MyLanguage/screen.modules.edit.15">Module Manager -
New/Edit</a> for information about the different Module Types. The
Joomla! installation is accompanied with 20 module types, additional 3rd
party modules can be located at the <a
href="http://extensions.joomla.org/" class="external text"
target="_blank" rel="noreferrer noopener">JED</a>.</p></td>
</tr>
</tbody>
</table>
