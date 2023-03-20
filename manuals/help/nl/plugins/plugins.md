<!-- Filename: Help4.x:Plugins / Display title: Plugins -->

## Beschrijving

Plugin beheer stelt u in staat Joomla! plugins te activeren en
deactiveren en de details en opties van een plugin te bewerken. Het is
ook handig om snel meerdere plugins tegelijk te activeren/deactiveren.

## Hoe toegang te krijgen

- Selecteer **Systeem **→** Beheren venster **→** Plugins** vanuit het
  beheermenu.
- Selecteer **Home Controlepaneel **→** Site venster **→** Plugins**
  vanuit het beheermenu.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/f/f4/Help-4x-Extensions-Plugin-Manager-screen-nl.png/800px-Help-4x-Extensions-Plugin-Manager-screen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/f/f4/Help-4x-Extensions-Plugin-Manager-screen-nl.png 1.5x"
data-file-width="1136" data-file-height="678" width="800" height="477"
alt="Help-4x-Extensions-Plugin-Manager-screen-nl.png" />

## Kolomkoppen

- **Selectievakje**. Vink dit vakje aan om één of meer items te
  selecteren. Vink het vakje in de kolomkop aan om alle selectievakjes
  aan te vinken. Nadat één of meer vakjes zijn aangevinkt kan op een
  werkbalkknop geklikt worden om een actie uit te voeren op de
  geselecteerde item(s). De meeste acties via de werkbak, zoals
  Publiceren en Depubliceren kunnen op meerdere items tegelijkertijd
  uitgevoerd worden. Andere, zoals Bewerken, werken alleen voor één
  item. Indien er meerdere items geselecteerd zijn en op Bewerken wordt
  geklikt, opent het het eerste item om het te bewerken.
- **Volgorde.** U kunt de volgorde van een item binnen een lijst als
  volgt veranderen:
  - Als het lijstfilter opties een positie filter hebben, selecteer dan
    de gewenste positie. Dit beperkt de lijst tot de items die toegekend
    zijn aan die positie.
  - Selecteer het volgorde icoon <img
    src="https://docs.joomla.org/images/e/ee/Help30-Ordering-colheader-icon.png"
    decoding="async" data-file-width="12" data-file-height="23" width="12"
    height="23" alt="Help30-Ordering-colheader-icon.png" /> in de
    tabelkop om het het actieve volgorde item te maken. De volgorde
    iconen in iedere rij veranderen van licht naar donker grijs en de
    pijl verandert in een sleepsymbool als u eroverheen gaat.
  - Selecteer één van de volgorde iconen <img
    src="https://docs.joomla.org/images/8/87/Help30-Ordering-colheader-grab-bar-icon.png"
    decoding="async" data-file-width="10" data-file-height="21" width="10"
    height="21" alt="Help30-Ordering-colheader-grab-bar-icon.png" /> en
    sleep het naar boven of beneden om de positie van die rij in de
    lijst te veranderen. De items worden in de nieuwe volgorde binnen de
    positie getoond.
- **Status.** Een groen vinkje of een rood kruis dat toont of het
  gebruik van de component ingeschakeld/uitgeschakeld is. Klik op het
  pictogram om te schakelen tussen ingeschakeld en uitgeschakeld.
- **Pluginnaam.** De naam van de plugin.
- **Type.** Het type plugin. Mogelijke types zijn: authentication,
  content, editors, editors-xtd, search, system, en user. Dit zijn ook
  de namen van de website sub-mappen waar de plugin-bestanden staan.
  Plugins van het type 'authentication' staan bijvoorbeeld in de website
  map 'plugins/authentication'.
- **Element.** De plugin map naam die de plugin bestanden bevat. Deze
  map staat in de map die correspondeert met zijn type. De
  'Authentication - Joomla' plugin is bijvoorbeeld van het type
  'Authentication' en element 'joomla'. De map op de website waar hij
  staat is dus 'plugins/authentication/joomla'
- **Toegang.** Welke gebruikers 'toegangsniveaus' hebben toegang tot dit
  item. U kunt het toegangsniveau van een item veranderen door op zijn
  naam te klikken om het te openen voor bewerken. De standaard
  'toegangsniveaus' die voor ingesteld met Joomla komen zijn:
  - Publiek: Iedereen heeft toegang inclusief website-bezoekers die niet
    zijn ingelogd
  - Geregistreerd: Alleen gebruikers met de geregistreerd status of
    hoger hebben toegang.
  - Speciaal: Alleen gebruikers met auteur status of hoger hebben
    toegang.
- **ID**. Dit is een uniek identificatienummer voor dit item,
  automatisch toegekend door Joomla!. Het wordt gebruikt om het item
  intern te identificeren en u kunt dit nummer niet veranderen. Als u
  een nieuw item aanmaakt, is dit veld "0" totdat u het opslaat, waarbij
  een nieuw ID toegekend wordt.

## Lijst filters

**Zoekbalk**. Bovenaan de pagina vind je de zoekbalk, zoals in
bovenstaande [Screenshot](#screenshot).

- **Zoeken op tekst**. Voer een deel van de zoekterm in en klik op het
  zoekicoon. *Hover* (muis boven item) om een *Tooltip* te zien dat
  aangeeft welke velden doorzocht worden.Om te **Zoeken op ID** geef je
  "id:x" op, waarbij "x" het item ID nummer is (bijvoorbeeld, "id:19").
- **Filteropties**. Klik om de extra filters te tonen.
- **Wissen.** om het filterveld te wissen en de lijst in zijn initiële
  status te zetten.
- **Sortering**. Toont het huidige weergave volgorde veld. Er zijn 2
  manieren om de volgorde aan te passen:
  - Selecteer uit de uitklaplijst. De volgorde kan oplopend of aflopend
    zijn.
  - Klik op een kolomkop.De kolomkop wisselt tussen een oplopend en
    aflopend volgorde.
- **Te tonen aantal.** Toont het aantal items in een lijst. Selecteer
  uit de uitklaplijst om het te tonen aantal te veranderen.De standaard
  voor een site is '20' maar dit kan veranderd worden bij de [Algemene
  instellingen](https://docs.joomla.org/Help4.x:Site_Global_Configuration/nl#defaultlistlimit "Special:MyLanguage/Help4.x:Site Global Configuration/nl").

De lijst met plugins welke verschijnt op dit scherm kan vrij groot zijn.
U kunt één van de beschikbare filters gebruiken of een combinatie ervan
om het aantal plugines dat getoond wordt te beperken tot uw
filter-parameters.

**Filteropties**

- **Selecteer status.** Select een status (Ingeschakeld of
  Uitgeschakeld) uit de drop-down lijst om alleen plugins met de
  selecteerde status te tonen.
- **Selecteer Type.** Selecteer een type uit de drop-down lijst om
  alleen de plugins met het geselecteerde type te tonen.
- **Selecteer Element.** Een lijst met elementen, die een nauwkeurige
  selectie mogelijk maken.
- **Selecteer Toegang.** Selecteer het 'Toegangsniveau' uit de drop-down
  ljist om alleen plugins toegankelijk door gebruikers met het
  geselecteerde 'Toegangsniveau' te tonen.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#Schermafbeelding) hierboven. De functies zijn.

- **Inschakelen**. Maakt de selecteerde plugin beschikbaar om te
  gebruiken op uw website. U kunt ook schakelen tussen 'Ingeschakeld' en
  'Uitgeschakeld' door op het icoon in de 'Status' kolom te drukken.
- **Uitschakelen**. Maakt de selecteerde plugins niet beschikbaar om te
  gebruiken op uw website. U kunt ook schakelen tussen 'Ingeschakeld' en
  'Uitgeschakeld' door op het icoon in de 'Status' kolom te drukken.
- **Inchecken**. Checkt de geselecteerde plugins in. Werkt bij één of
  meer plugins geselecteerd.
- **Opties.** Opent het venster Opties, waar instellingen zoals de
  standaard parameters kunnen worden bewerkt.
- **Help**. Opent dit helpscherm.

## Snelle tips

- Om een groep plugins in- of uit te schakelen vinkt u het aanvinkvakje
  voor de gewenste plugins aan en klik daarna op de Inschakelen of
  Uitschakelen knop in de werkbalk.
- Vanaf Joomla! 1.6 worden de instellingen van instelbare plugins
  'opties' genoemd. In eerdere versies van Joomla! werden deze
  instellingen 'parameters' genoemd. U kunt de termen 'opties' en
  'parameters' door elkaar gebruikt worden in help-documentatie en
  handleidingen.

## Verwante informatie

- Om de details of opties van een plugin te wijzigen: [Pluginbeheer -
  Bewerken](https://docs.joomla.org/Help4.x:Plugins:_Name_of_Plugin/nl "Help4.x:Plugins: Name of Plugin/nl")
- Om plugins te installeren: [Extensiebeheer -
  Installeren](https://docs.joomla.org/Help4.x:Extensions:_Install/nl "Help4.x:Extensions: Install/nl")
- Om plugins te deinstalleren: [Extensiebeheer -
  Beheer](https://docs.joomla.org/Help4.x:Extensions:_Manage/nl "Help4.x:Extensions: Manage/nl")
