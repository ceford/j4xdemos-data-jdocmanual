<!-- Display title: Extensions Module Manager Edit -->

## Beschreibung

Der Erweiterungs-Manager â€žModul Bearbeitenâ€œ ermÃ¶glicht die
Bearbeitung eines vorhandenen Moduls oder die Erstellung eines neuen
Moduls entsprechend dem gewÃ¤hlten Modultyp.

## Wie darauf zugreifen

- Im Administrator-MenÃ¼ die Option **System **→** Verwalten **→** Site
  Module** wÃ¤hlen oder ...
- im Administrator-MenÃ¼ die Option
  **System **→** Verwalten **→** Administrator Module** wÃ¤hlen. Dann
  ...
  - die SchaltflÃ¤che **â€ž+ Neuâ€œ** in der Symbolleiste wÃ¤hlen, um
    ein neues Modul zu erstellen  
    oder ...
  - einen Modulnamen in der Spalte **Titel** auswÃ¤hlen, um dieses Modul
    zu bearbeiten.

Bei einem neuen Modul wird eine Liste mit allen installierten Modulen
fÃ¼r das Frontend (Site) oder das Backend (Administrator) angezeigt, die
zur Auswahl stehen:

<img
src="https://docs.joomla.org/images/thumb/3/37/Help-4x-extensions-module-manager-new-de.png/800px-Help-4x-extensions-module-manager-new-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/3/37/Help-4x-extensions-module-manager-new-de.png/1200px-Help-4x-extensions-module-manager-new-de.png 1.5x, https://docs.joomla.org/images/thumb/3/37/Help-4x-extensions-module-manager-new-de.png/1600px-Help-4x-extensions-module-manager-new-de.png 2x"
data-file-width="1647" data-file-height="1029" width="800" height="500"
alt="Help-4x-extensions-module-manager-new-de.png" />

Eines davon auswÃ¤hlen, um zum Bearbeitungsbildschirm zu wechseln.

## Bildschirmfoto

Die Registerkarte â€žModulâ€œ eines Bildschirmes zur Modulbearbeitung
ist abhÃ¤ngig vom Modultyp. Das Site-Modul "Breadcrumbs"
(Navigationspfad) ist hier abgebildet. FÃ¼r andere Module siehe
**[Verwandte Informationen](#Verwandte_Informationen)** unten fÃ¼r Links
zu bestimmten Modultypen.

<img
src="https://docs.joomla.org/images/thumb/8/84/Help-4x-extensions-module-manager-edit-de.png/800px-Help-4x-extensions-module-manager-edit-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/84/Help-4x-extensions-module-manager-edit-de.png/1200px-Help-4x-extensions-module-manager-edit-de.png 1.5x, https://docs.joomla.org/images/8/84/Help-4x-extensions-module-manager-edit-de.png 2x"
data-file-width="1378" data-file-height="1254" width="800" height="728"
alt="Help-4x-extensions-module-manager-edit-de.png" />

## Formular Felder

- **Titel**. Der Titel des Eintrages. Er kann auf der Seite abhÃ¤ngig
  von den gewÃ¤hlten Parameterwerten angezeigt werden.

### Modul

**Linke Seite**

Der Aufbau des linken Bereichs hÃ¤ngt vom Modultyp ab und wird hier
nicht beschrieben.

**Rechte Seite**

Der rechte Bereich ist bei allen Modulen gleich.

- **Titel anzeigen**. Anzeigen oder Verbergen des Modultitels im
  Frontend.

<!-- -->

- **Position**. Die
  [Modul-Position](https://docs.joomla.org/Module_Position/de "Module Position/de")
  wÃ¤hlen, auf der dieses Modul angezeigt werden soll. Eine
  benutzerdefinierte Modulposition kann unter Verwendung mit dem
  [Load-Position-Plugin](https://docs.joomla.org/How_do_you_put_a_module_inside_an_article%3F/de "How do you put a module inside an article?/de")
  eingegeben werden. Alternativ kann die Positionstaste gedrÃ¼ckt
  werden, um eine Modulposition aus dem Template auszuwÃ¤hlen.

<!-- -->

- **Status**. Der VerÃ¶ffentlichungs-Status des Eintrages.
  - *VerÃ¶ffentlicht:* Der Eintrag ist im Frontend der Seite sichtbar.
  - *Versteckt:* Der Eintrag ist im Frontend der Seite fÃ¼r Besucher
    nicht sichtbar. Es kann fÃ¼r angemeldete Benutzer sichtbar sein, die
    eine Berechtigung zur Bearbeitung des Eintrags haben.
  - *Archiviert:* Der Eintrag wird nicht lÃ¤nger in Blog- oder
    Listen-MenÃ¼s angezeigt.
  - *Papierkorb:* Der Eintrag wurde gelÃ¶scht, befindet sich aber noch
    in der Datenbank. Dauerhaft wird es Ã¼ber den Button 'Papierkorb
    leeren' der Symbolleiste gelÃ¶scht (siehe auch [Einen Beitrag
    lÃ¶schen](https://docs.joomla.org/Deleting_an_Article/de "Special:MyLanguage/Deleting an Article/de")).

<!-- -->

- **VerÃ¶ffentlichung starten**. Datum und Uhrzeit, um die
  VerÃ¶ffentlichung zu starten. Dieses Feld verwenden, um Inhalt vor der
  Zeit zu erstellen und ihn spÃ¤ter automatisch zu verÃ¶ffentlichen.

<!-- -->

- **VerÃ¶ffentlichung beenden**. Datum und Uhrzeit, um die
  VerÃ¶ffentlichung zu beenden. Dieses Feld verwenden, um dem Inhalt
  automatisch den Status â€žVerstecktâ€œ zuzuweisen (zum Beispiel, wenn
  der Inhalt nicht mehr aktuell ist).

<!-- -->

- **Zugriffsebene**. Die angezeigte Zugriffsebene fÃ¼r diesen Eintrag
  aus dem Listenfeld auswÃ¤hlen. Welche Zugriffsebenen angezeigt werden,
  hÃ¤ngt davon ab, was fÃ¼r diese Site in [Benutzer →
  Zugriffsebenen](https://docs.joomla.org/Help40:Users:_Viewing_Access_Levels/de "Special:MyLanguage/Help40:Users: Viewing Access Levels/de")
  eingerichtet wurde. Bitte beachten, dass Zugriffsebenen nicht mit
  ACL-Berechtigungen gleichzusetzen sind. Zugriffsebenen steuern, was
  ein Benutzer sehen kann. ACL-Berechtigungen steuern, welche Aktionen
  ein Benutzer durchfÃ¼hren kann.

<!-- -->

- **Reihenfolge.** Die Reihenfolge eines Eintrags innerhalb einer Liste
  kann wie folgt geÃ¤ndert werden:
  - Wenn die Liste Filter-Optionen einen Positions-Filter enthÃ¤lt, dann
    wÃ¤hlt man die gewÃ¼nschte Position aus. Dadurch wird die Liste auf
    Positionen beschrÃ¤nkt, die dieser Position zugeordnet sind.
  - Das Reihenfolge-Symbol <img
    src="https://docs.joomla.org/images/e/ee/Help30-Ordering-colheader-icon.png"
    decoding="async" data-file-width="12" data-file-height="23" width="12"
    height="23" alt="Help30-Ordering-colheader-icon.png" /> in der
    TabellenÃ¼berschrift anklicken, um diese Spalte zur aktiven
    Sortierung zu machen. Die Ordnungssymbole in jeder Zeile Ã¤ndern
    sich von hellgrau zu dunkelgrau, und der Mauszeiger verwandelt sich
    beim Ãœberfahren in einen Ziehpfeil.
  - Eines der Reihenfolge-Symbole <img
    src="https://docs.joomla.org/images/8/87/Help30-Ordering-colheader-grab-bar-icon.png"
    decoding="async" data-file-width="10" data-file-height="21" width="10"
    height="21" alt="Help30-Ordering-colheader-grab-bar-icon.png" />
    wÃ¤hlen und es nach oben oder unten ziehen, um die Position dieser
    Zeile in der Liste zu Ã¤ndern. Die EintrÃ¤ge werden in der neuen
    Reihenfolge innerhalb der Position angezeigt.

<!-- -->

- **Sprache**. Die Sprache fÃ¼r diesen Eintrag wÃ¤hlen. Wird die
  Funktion Mehrsprachigkeit nicht verwendet, den Standardwert 'Alle'
  beibehalten.

<!-- -->

- **Notiz**. Die Notiz wird meist vom Site-Administrator verwendet, um
  beispielsweise Informationen Ã¼ber den Eintrag zu notieren. Die Notiz
  wird nicht im Frontend der Seite angezeigt.

### MenÃ¼zuweisung

Diese Registerkarten-Ansicht enthÃ¤lt alle MenÃ¼eintrÃ¤ge, die auf der
Joomla!-Website konfiguriert sind. Dadurch kann man auswÃ¤hlen, wo ein
Modul auf der mit dem MenÃ¼eintrag verbundenen Inhaltsseite angezeigt
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

- **Auf allen Seiten.** Das Modul wird auf allen Seiten in der
  gewÃ¤hlten Position gezeigt.
- **Auf keinen Seiten**. Module werden **auf keiner Seite** an der
  gewÃ¤hlten Modulposition angezeigt.
- **Nur auf den gewÃ¤hlten Seiten**. Das Modul wird nur auf den Seiten
  in der ausgewÃ¤hlten Modulposition angezeigt, wie sie durch den
  MenÃ¼eintragstyp (Titel) festgelegt wurde. Siehe **MenÃ¼auswahl**
  unten.
- **Auf allen, auÃŸer den gewÃ¤hlten Seiten**. Das Modul wird auf allen
  Seiten in der gewÃ¤hlten Position gezeigt, ausgenommen der in der
  MenÃ¼auswahl gewÃ¤hlten Seiten. Siehe **MenÃ¼auswahl** unten.

#### MenÃ¼auswahl

- **MenÃ¼auswahl**. Wird nur angezeigt, wenn in der **Modulzuweisung**,
  wie oben gezeigt, **Nur auf den gewÃ¤hlten Seiten** oder **Auf allen,
  auÃŸer den gewÃ¤hlten Seiten** eingestellt ist.

Um das Modul der entsprechenden Webseite (Titel) eines MenÃ¼eintrags
zuzuordnen, muss das KontrollkÃ¤stchen neben dem MenÃ¼eintrag aktiviert
werden.

- Zuordnen zu MenÃ¼eintrÃ¤gen: *Alle* oder *Keine* anklicken, um die
  Auswahl der MenÃ¼eintrÃ¤ge zu verÃ¤ndern.
- UntermenÃ¼s aufklappen: *Alle* oder *Keine* anklicken, um die
  Strukturansicht fÃ¼r die Auswahl der MenÃ¼eintrÃ¤ge anzuzeigen.

**Hinweis**: Wenn ein KontrollkÃ¤stchen ausgegraut ist und nicht
angekreuzt werden kann, kÃ¶nnte es daran liegen, dass der MenÃ¼eintrag
von einem anderen Benutzer verwendet wird. Um das zu Ã¼berprÃ¼fen, die
[MenÃ¼-Manager-Seite fÃ¼r das betreffende
MenÃ¼](https://docs.joomla.org/Help4.x:Menus:_Items/de "Help4.x:Menus: Items/de")
aufrufen. Wenn sich neben dem MenÃ¼eintrag ein Schloss-Symbol befindet,
wird der MenÃ¼eintrag gerade von einem anderen Benutzer verwendet.

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

- **Speichern & SchlieÃŸen**. Speichert den Eintrag und schlieÃŸt die
  aktuelle Seite.

<!-- -->

- **Speichern & Neu**. Speichert den Eintrag und hÃ¤lt die Seite offen,
  damit ein neuer Eintrag erstellt werden kann.

<!-- -->

- **Als Kopie speichern**. Speichert Ã„nderungen in einer Kopie des
  aktuellen Eintrags. Der aktuelle Eintrag wird davon nicht beeinflusst.
  Dieses Symbol wird nicht angezeigt, wenn ein neuer Eintrag erstellt
  wird.

<!-- -->

- **Abbrechen**. SchlieÃŸt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Ã„nderungen zurÃ¼ck. Oder

<!-- -->

- **SchlieÃŸen**. SchlieÃŸt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Ã„nderungen zurÃ¼ck. Dieses Symbol wird nicht
  angezeigt, wenn ein neuer Eintrag erstellt wird.

<!-- -->

- **Hilfe**. Ã–ffnet die Hilfeseite.

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
BeitrÃ¤ge â€“ Archiv</a></td>
<td>Dieses Modul zeigt eine Liste der Kalendermonate, die archivierte
BeitrÃ¤ge enthalten. Nach dem Archivieren von BeitrÃ¤gen wird diese
Liste automatisch generiert.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Categories/de"
title="Help4.x:Site Modules: Articles - Categories/de">Site-Modul:
BeitrÃ¤ge â€“ Kategorien</a></td>
<td>Dieses Modul zeigt eine Liste aller Unterkategorien einer
Ã¼bergeordneten Kategorie an.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Category/de"
title="Help4.x:Site Modules: Articles - Category/de">Site-Modul:
BeitrÃ¤ge â€“ Kategorie</a></td>
<td>Dieses Modul zeigt eine Liste von BeitrÃ¤gen aus einer oder mehreren
Kategorien an.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Newsflash/de"
title="Help4.x:Site Modules: Articles - Newsflash/de">Site-Modul:
BeitrÃ¤ge â€“ Newsflash</a></td>
<td>Das Beitragsmodul â€žNewsflashâ€œ zeigt eine feste Anzahl von
BeitrÃ¤gen aus einer oder mehrerer Kategorien an.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Related/de"
title="Help4.x:Site Modules: Articles - Related/de">Site-Modul:
Verwandte BeitrÃ¤ge</a></td>
<td>Dieses Modul zeigt eine Liste von BeitrÃ¤gen an, die mit dem aktuell
angesehenen Beitrag verwandt sind (z.B. ein Beitrags-Layout oder ein
Blog- oder Listen-Layout, bei dem der Benutzer auf einen Beitragslink
geklickt hat). BeitrÃ¤ge gelten als miteinander verwandt, wenn sie
mindestens ein SchlÃ¼sselwort in den Metadateninformationen des Beitrags
gemeinsam haben. SchlÃ¼sselwÃ¶rter werden im Abschnitt mit den
Metadaten-Informationen von <a
href="https://docs.joomla.org/Help4.x:Content_Article_Manager_Edit#Ver.C3.B6ffentlichung.2Fde"
class="mw-redirect"
title="Help4.x:Content Article Manager Edit">BeitrÃ¤ge: Bearbeiten</a>
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
Position auf der Site visualisieren und eine RÃ¼ckwÃ¤rtsnavigation
ermÃ¶glichen.</td>
</tr>
<tr class="even">
<td><a href="https://docs.joomla.org/Help4.x:Site_Modules:_Custom/de"
title="Help4.x:Site Modules: Custom/de">Site-Modul: Eigenes
Modul</a></td>
<td>Mit diesem Modul kann ein Modul erstellt werden, das beliebigen,
gÃ¼ltigen HTML-Code enthÃ¤lt. Es gibt viele FÃ¤lle, in denen
Freiform-HTML in eine Webseite eingefÃ¼gt werden sollte. Beispielsweise
kÃ¶nnte man eine HTML-Image-Map erstellen oder HTML-Code von PayPal,
Amazon oder einer anderen Website kopieren wollen.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Feed_Display/de"
title="Help4.x:Site Modules: Feed Display/de">Site-Modul: Externen Feed
anzeigen</a></td>
<td>Dieses Modul zeigt einen RSS-News-Feed von einer Website an. Dieses
Modul steht in keinem VerhÃ¤ltnis zur News-Feeds-Komponente oder den
News-Feeds-Layouts und ist eine Alternative, mit der ein Feed auf einer
Modulposition angezeigt werden kann.</td>
</tr>
<tr class="even">
<td><a href="https://docs.joomla.org/Help4.x:Site_Modules:_Footer/de"
title="Help4.x:Site Modules: Footer/de">Site-Modul: FuÃŸzeile</a></td>
<td>Dieses Modul zeigt die Copyright- und Joomla!-Lizenzinformationen
der Website an.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Language_Switcher/de"
title="Help4.x:Site Modules: Language Switcher/de">Site-Modul:
Sprachauswahl</a></td>
<td>Mit diesem Modul kann zwischen den verfÃ¼gbaren Inhaltssprachen
gewechselt werden. Durch die Auswahl einer Sprache gelangt man zur
Startseite der jeweiligen Sprache.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Latest/de"
title="Help4.x:Site Modules: Articles - Latest/de">Site-Modul: BeitrÃ¤ge
â€“ Neueste</a></td>
<td>Dieses Modul zeigt eine Liste der zuletzt verÃ¶ffentlichten
BeitrÃ¤ge an.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Latest_Users/de"
title="Help4.x:Site Modules: Latest Users/de">Site-Modul: Benutzer â€“
Neueste</a></td>
<td>Dieses Modul zeigt die zuletzt registrierten Benutzer an, die sich
auf der Website angemeldet haben.</td>
</tr>
<tr class="even">
<td><a href="https://docs.joomla.org/Help4.x:Site_Modules:_Login/de"
title="Help4.x:Site Modules: Login/de">Site-Modul: Benutzer â€“
Anmeldung</a></td>
<td>Dieses Modul zeigt ein Login-Formular mit Benutzernamen und Passwort
an. Er zeigt auch einen Link zum Abrufen eines vergessenen Passworts an.
Wenn die Benutzerregistrierung in den Benutzereinstellungen des
Bildschirms â€žKonfigurationâ€œ aktiviert ist, wird der Link
â€žRegistrierenâ€œ angezeigt, um Benutzer zur Selbstregistrierung
einzuladen.</td>
</tr>
<tr class="odd">
<td><a href="https://docs.joomla.org/Help4.x:Site_Modules:_Menu/de"
title="Help4.x:Site Modules: Menu/de">Site-Modul: MenÃ¼</a></td>
<td>Dieses Modul dient dazu, ein MenÃ¼ an der gewÃ¼nschten Position und
auf den gewÃ¼nschten Webseiten zu positionieren. Jede Joomla!-Website
hat mindestens ein MenÃ¼, das auf der <a
href="https://docs.joomla.org/Help4.x:Menus/de"
title="Help4.x:Menus/de">MenÃ¼-Manager</a>-Seite erstellt wird. Mit dem
MenÃ¼-Modul lÃ¤sst sich das ausgewÃ¤hlte MenÃ¼ ganz oder teilweise an
der gewÃ¼nschten Position und auf den vorgesehenen Web-Seiten
platzieren.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Most_Read/de"
title="Help4.x:Site Modules: Articles - Most Read/de">Site-Modul:
BeitrÃ¤ge â€“ Beliebte</a></td>
<td>Dieses Modul zeigt eine Liste der BeitrÃ¤ge mit den hÃ¶chsten
Besucherzahlen an.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Random_Image/de"
title="Help4.x:Site Modules: Random Image/de">Site-Modul:
Zufallsbild</a></td>
<td>Dieses Modul zeigt ein zufÃ¤lliges Bild aus dem gewÃ¤hlten
Verzeichnis an.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/index.php?title=Help4.x:Extensions_Module_Manager_Search/en&amp;action=edit&amp;redlink=1"
class="new"
title="Help4.x:Extensions Module Manager Search/en (page does not exist)">Erweiterungen
Modulmanager Suche</a></td>
<td>Dieses Modul zeigt ein Eingabefeld fÃ¼r die Suche an, in das der
Benutzer einen Ausdruck eingeben und die Eingabetaste drÃ¼cken kann, um
die Website zu durchsuchen.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Smart_Search/de"
title="Help4.x:Site Modules: Smart Search/de">Site-Modul:
Suchindex</a></td>
<td>Das Modul Suchindex ermÃ¶glicht eine erweiterte Suche auf der
Webseite.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Statistics/de"
title="Help4.x:Site Modules: Statistics/de">Site-Modul:
Statistiken</a></td>
<td>Das Statistikmodul zeigt Informationen Ã¼ber die Serverinstallation
zusammen mit Statistiken Ã¼ber die Website-Benutzer, die Anzahl der
BeitrÃ¤ge in der Datenbank und die Anzahl der bereitgestellten
Weblinks.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Syndication_Feeds/de"
title="Help4.x:Site Modules: Syndication Feeds/de">Site-Modul: Feeds â€“
Feed erzeugen</a></td>
<td>Dieses Modul erstellt einen RSS-Feed-Link fÃ¼r die Seite. Damit kann
ein Benutzer einen Newsfeed fÃ¼r die aktuelle Seite erstellen. Ein
Beispiel wird unten gezeigt.</td>
</tr>
<tr class="even">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Tags_-_Popular/de"
title="Help4.x:Site Modules: Tags - Popular/de">Site-Modul:
SchlagwÃ¶rter â€“ Beliebte</a></td>
<td>Stellt die auf einer Site verwendeten Tags in einer Tag-Wolke oder
Liste dar.</td>
</tr>
<tr class="odd">
<td><a
href="https://docs.joomla.org/Help4.x:Site_Modules:_Tags_-_Similar/de"
title="Help4.x:Site Modules: Tags - Similar/de">Site-Modul:
SchlagwÃ¶rter â€“ Ã„hnliche</a></td>
<td>Zeigt Links zu anderen EintrÃ¤gen mit Ã¤hnlichen SchlagwÃ¶rtern
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
