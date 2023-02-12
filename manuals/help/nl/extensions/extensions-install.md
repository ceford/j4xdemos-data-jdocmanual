<!-- Filename: Help4.x:Extensions:_Install / Display title: Extensies: Installeren -->

## Beschrijving

Extensies zijn toevoegingen die de functionaliteit van Joomla!
uitbreiden. Extensies worden gebruikt om mogelijkheden aan Joomla! toe
te voegen die niet bestaan in het standaard pakket. Honderden extensies
zijn beschikbaar voor Joomla!, terwijl er constant meer worden
ontwikkeld.

Extensies worden als volgt gecategoriseerd in vijf types:

- Een *Component* is een mini-applicatie welke de body van een pagina
  genereert. Voorbeelden van componenten zijn contactpersonen, de
  voorpagina en nieuwsfeeds.
- Een *Module* is een kleine extensie speciaal gebruikt om een klein
  element te genereren dat getoond wordt op meerdere pagina's.
  Voorbeelden van modules zijn Menu's en gerelateerde items.
- Een *Plugin* is een stukje code dat uitgevoerd wordt als een
  voorgedefinieerd binnen Joomla! plaats vindt. Bijvoorbeeld,
  tekstverwerkers zijn plugins die uitgevoerd worden als er een
  bewerk-sessie wordt gestart.
- De *Taal* extensie maakt het mogelijk op de website en in het
  beheergedeelte van Joomla! aanwezig te zijn voor iedere taal waarvoor
  de taalextensie bestaat. Op deze manier kan Joomla! uitgebracht worden
  in een nieuwe taal zonder aanpassingen in het core programma.
- Een *Template* bepaalt de manier waarop de inhoud van een website
  getoond wordt de plek en de lay-out van elementen, kleuren, fonts,
  enzovoort. Templates maken het mogelijk de weergave van de website te
  scheiden van de inhoud.

## Hoe toegang te krijgen

- Selecteer **Systeem **→** Installeren venster **→** Extensies** vanuit
  het beheermenu.

Er is een korte vertraging aangezien Joomla een initieel deel van
extensie-gegevens vanaf de Joomla Extensions Directory download.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/4/43/Help-4x-Extensions-Extension-Manager-Install-screen-nl.png/800px-Help-4x-Extensions-Extension-Manager-Install-screen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/43/Help-4x-Extensions-Extension-Manager-Install-screen-nl.png/1200px-Help-4x-Extensions-Extension-Manager-Install-screen-nl.png 1.5x, https://docs.joomla.org/images/4/43/Help-4x-Extensions-Extension-Manager-Install-screen-nl.png 2x"
data-file-width="1260" data-file-height="927" width="800" height="589"
alt="Help-4x-Extensions-Extension-Manager-Install-screen-nl.png" />

### Formulier velden

Joomla! extensies kunnen geïnstalleerd worden via één van de vier
methodes, zoals hieronder aangegeven. Slechts één methode is nodig om
een bepaalde extensie te installeren. De normale procedure voor het
installeren van een Joomla! extensie is als volgt:

1.  Download een of meer archief bestanden (normaliter ".zip" of
    "tar.gz" formaat) vanaf de website van de aanbieder van de extensie
    naar een lokale map op uw computer. Let op dat sommige extensies
    geïnstalleerd worden als één bestand (bijvoorbeeld, een component of
    module) terwijl andere extensies twee of meer bestanden kunnen
    hebben (bijvoorbeeld een component en een module). Als er twee of
    meer delen zijn, dan heeft ieder deel zijn eigen archief bestand.
2.  Kies een van de hieronder beschreven methodes (**meestal
    pakketbestand**)
3.  Als het klaar is, toont het scherm de boodschap "Installatie
    component succesvol". Als de installatie niet succesvol was wordt
    een foutboodschap getoond.
4.  Afhankelijk van de extensie, kan het noodzakelijk zijn de extensie
    te activeren (bijvoorbeeld, in
    [Modules](https://docs.joomla.org/Help4.x:Modules/nl "Help4.x:Modules/nl")
    of
    [Plugins](https://docs.joomla.org/Help4.x:Plugins/nl "Help4.x:Plugins/nl")).

### Installeren vanaf web tabblad

Indien geïnstalleerd, ziet u het 'Installeren vanaf web' tabblad, zoals
in de afbeelding, om een extensie direct vanaf de Joomla Extension
Directory (JED) te installeren. U kunt extensies tonen op categorie of u
kunt op een gedeeltelijke van de naam zoeken.

### Upload pakketbestand tabblad

<img
src="https://docs.joomla.org/images/thumb/f/f0/Help-4x-Extensions-Manager-Install-UploadPackageFilescreen-nl.png/600px-Help-4x-Extensions-Manager-Install-UploadPackageFilescreen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f0/Help-4x-Extensions-Manager-Install-UploadPackageFilescreen-nl.png/900px-Help-4x-Extensions-Manager-Install-UploadPackageFilescreen-nl.png 1.5x, https://docs.joomla.org/images/f/f0/Help-4x-Extensions-Manager-Install-UploadPackageFilescreen-nl.png 2x"
data-file-width="938" data-file-height="479" width="600" height="306"
alt="Help-4x-Extensions-Manager-Install-UploadPackageFilescreen-nl.png" />

- 'Sleep en plaats' of blader naar de locatie waar u het archiefbestand
  van de extensie heeft gedownload.

De upload begint automatisch. Let op de **Maximum upload size: ‎X.00 MB**
in uw installatie. Indien u deze niet kunt verhogen, gebruik dan
"Installeren vanuit map".

### Installeer vanuit map tabblad

<img
src="https://docs.joomla.org/images/thumb/5/5b/Help-4x-Extensions-Manager-Install-InstallfromFolder-screen-nl.png/600px-Help-4x-Extensions-Manager-Install-InstallfromFolder-screen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/5b/Help-4x-Extensions-Manager-Install-InstallfromFolder-screen-nl.png/900px-Help-4x-Extensions-Manager-Install-InstallfromFolder-screen-nl.png 1.5x, https://docs.joomla.org/images/5/5b/Help-4x-Extensions-Manager-Install-InstallfromFolder-screen-nl.png 2x"
data-file-width="938" data-file-height="306" width="600" height="196"
alt="Help-4x-Extensions-Manager-Install-InstallfromFolder-screen-nl.png" />

1.  Maak een tijdelijke map aan op uw lokale harde schijf en pak het
    archiefbestand van de extensie hierin uit.
2.  Upload met behulp van FTP de inhoud van deze map (inclusief
    bestanden en submappen) naar de map op uw server.
3.  Geef In het *Installeren vanuit map* veld de map op de server aan
    waarnaar u uw bestanden en submappen van het pakket geüploadet
    heeft.
4.  Klik op de *Controleer en installeren* knop en Joomla! zal de inhoud
    uit de opgegeven map installeren.

Let op dat het goed gebruik is om de ingepakte extensie in de tmp map
van uw Joomla site te plaatsen.

### Installeren vanuit URL tabblad

<img
src="https://docs.joomla.org/images/thumb/8/80/Help-4x-Extensions-Manager-Install-InstallfromUrl-screen-nl.png/600px-Help-4x-Extensions-Manager-Install-InstallfromUrl-screen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/80/Help-4x-Extensions-Manager-Install-InstallfromUrl-screen-nl.png/900px-Help-4x-Extensions-Manager-Install-InstallfromUrl-screen-nl.png 1.5x, https://docs.joomla.org/images/8/80/Help-4x-Extensions-Manager-Install-InstallfromUrl-screen-nl.png 2x"
data-file-width="941" data-file-height="311" width="600" height="198"
alt="Help-4x-Extensions-Manager-Install-InstallfromUrl-screen-nl.png" />

Geef, in plaats van het downloaden van het archief bestand naar uw
lokale computer de URL van het doel archiefbestand in. Klik daarna op de
"Controleer en installeer" knop en Joomla! installeert automatisch het
direct vanaf deze URL. *Let op dat, met deze methode, u geen kopie van
het archiefbestand op uw lokale computer heeft.*

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#Schermafbeelding) hierboven. De functies zijn.

- **Opties.** Opent het venster Opties, waar instellingen zoals de
  standaard parameters kunnen worden bewerkt.

<!-- -->

- **Help**. Opent dit helpscherm.

## Links naar de andere schermen

- **Installeren.** Linkt naar het
  <span class="mw-selflink selflink">Extensies: Installeren</span>.
- **Update.** Linkt naar het [Extensies: Update
  scherm](https://docs.joomla.org/Help4.x:Extensions:_Update/nl "Help4.x:Extensions: Update/nl").
- **Beheren.** Linkt naar het [Beheren
  scherm](https://docs.joomla.org/Help4.x:Extensions:_Manage/nl "Help4.x:Extensions: Manage/nl").
- **Ontdekken.** Linkt naar het [Ontdekken
  scherm](https://docs.joomla.org/Help4.x:Extensions:_Discover/nl "Help4.x:Extensions: Discover/nl").
- **Database.** Linkt naar het [Database
  scherm](https://docs.joomla.org/Help4.x:Information:_Database/nl "Help4.x:Information: Database/nl").
- **Waarschuwingen.** Linkt naar het [Waarschuwingen
  scherm](https://docs.joomla.org/Help4.x:Information:_Warnings/nl "Help4.x:Information: Warnings/nl").
- **Installeer talen.** Linkt naar het [Installeer talen
  scherm](https://docs.joomla.org/Help4.x:Extensions:_Languages/nl "Help4.x:Extensions: Languages/nl").
- **Updatesites.** Linkt naar het <a
  href="https://docs.joomla.org/index.php?title=Help4.x:Extensions_Extension_Manager_Update_Sites/nl&amp;action=edit&amp;redlink=1"
  class="new"
  title="Help4.x:Extensions Extension Manager Update Sites/nl (page does not exist)">Updatesites
  scherm</a>.

## Snelle tips

- Vier alternatieve installatie methodes zijn beschikbaar, zoals boven
  aangegeven. De meest gebruikelijke is de "Upload pakketbestand"
  methode.
- Als u een module of plugin van derden wilt installeren die tot een
  component behoort, dan moet u in het algemeen de zowel de component
  als de module of plugin installeren om de module of plugin te
  gebruiken. Dit wordt normaliter gedocumenteerd in de installatie
  documentatie van de extensie op de website van de maker.
- Evenzo kunnen, als u een component van derden deïnstalleert, deze
  modules en plugins niet meer gebruikt worden. Het is daarom aanbevolen
  deze afhankelijke modules en plugins ook te deïnstalleren.
- Sommige componenten, ontwikkelt door derden kunnen hun eigen modules
  en plugins in hun installatie hebben zitten. In dit geval moet u er
  zeker van zijn dat deze module of plugin mappen beschrijfbaar zijn.
  Anders zullen de extensies niet juist werken.
- **VEILIGHEIDSWAARSCHUWING:** Er wordt aanbevolen dat u alleen die
  extensies van derden op uw site gebruikt die u echt nodig heeft.
  Gebruik uw live site niet voor testdoeleinden want het kan uw site en
  server in opspraak brengen. Test nieuwe extensies op een lokale test
  website voor ze toe te passen op uw live site.
- Installeer Joomla! extensies niet die gedownload zijn van warez sites
  want ze kunnen geïnfecteerd zijn met een virus of malware welke
  beschadigingen op de server kunnen veroorzaken en de computer van uw
  bezoekers besmetten
- Installeren vanuit een remote URL kan gevaarlijk zijn. Hierom wordt
  aanbevolen de "Installeren vanuit Web", "Upload pakketbestand" of
  "Installeren vanuit map" opties te gebruiken als u nieuwe extensies
  installeert.

## Verwante informatie

- Als u een component extensie installeert, zal het een plekje krijgen
  als nieuw menu-item in het *Componenten* menu.
- U kunt een menu-item toekennen aan een geïnstalleerde component
  extensie in [Menu-Item
  beheer](https://docs.joomla.org/Help4.x:Menus:_Items/nl "Help4.x:Menus: Items/nl")
  door te klikken op de *Nieuw* werkbalk knop. De nieuwe component zal
  getoond worden in de interne linklijst van menu-item types.
- Als u een module extensie installeert, wordt het toegevoegd aan de
  lijst met modules in
  [Modulelijst](https://docs.joomla.org/Help4.x:Modules/nl "Help4.x:Modules/nl"),
  waar u hem kunt activeren/deactiveren. U kunt ook zijn parameters
  aanpassen in het [Bewerk
  module](https://docs.joomla.org/Help4.x:Extensions_Module_Manager_Edit/nl "Help4.x:Extensions Module Manager Edit/nl")
  scherm.
- Een geïnstalleerde plugin extensie wordt toegevoegd aan de lijst in
  [Pluginbeheer](https://docs.joomla.org/Help4.x:Plugins/nl "Help4.x:Plugins/nl"),
  waar u hem kunt activeren/deactiveren. Door te klikken op de
  [Pluginnaam](https://docs.joomla.org/Help4.x:Plugins:_Name_of_Plugin/nl "Help4.x:Plugins: Name of Plugin/nl")
  kunt u de parameters op het volgende scherm aanpassen.
- Een geïnstalleerde Template extensie zal worden toegevoegd aan de Site
  od Administrator lijst van het [Template
  lijst](https://docs.joomla.org/Help4.x:Templates:_Styles/nl "Help4.x:Templates: Styles/nl")
  alwaar u het kunt toekennen aan alle pagina's of bepaalde pagina's. U
  kunt ook de parameters aanpassen, de HTML bewerken of de CSS bron, of
  de beschikbare module-posities bekijken.
- Een geïnstalleerde taalextensie zal worden toegevoegd aan de Site of
  Administrator lijst van
  [Taalbeheer](https://docs.joomla.org/Help4.x:Languages:_Installed/nl "Help4.x:Languages: Installed/nl"),
  afhankelijk van het client attribuut van de extensie. Dit scherm kan
  het u, indien gewenst, laten koppelen als standaard taal.
