<!-- Filename: Help4.x:Redirects:_Links / Display title: Verwijzingen: Links -->

## Beschrijving

Deze component wordt gebruikt om URL's van webpagina's die niet meer
bestaan op uw website te verwijzen naar pagina's die bestaan. De URL
waar vandaan u wilt verwijzen mag geen werkende zijn op uw website die
echt een webpagina laadt. Het mag de URL naar een webpagina zijn die u
uitgeschakeld heeft. De *Verlopen URL* die u definieert als u de
verwijzing aanmaakt moet de volledige URL zijn, zoals u hem typt in uw
webbrowser. De component toont alleen het laatste deel van de bron URL
in de verwijzingen lijst. De *Nieuwe URL* die u opgeeft als u de
verwijzing aanmaakt moet ook een volledige URL zijn. U moet de *Gebruik
URL herschrijven* optie geactiveerd hebben om de verwijzingen die u
heeft aangemaakt te laten werken.

## Hoe toegang te krijgen

- Selecteer **Systeem **→** Beheren venster **→** Verwijzingen** vanuit
  het beheermenu.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/0/0e/Help-4x-Components-Redirect-Manager-screen-nl.png/800px-Help-4x-Components-Redirect-Manager-screen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/0e/Help-4x-Components-Redirect-Manager-screen-nl.png/1200px-Help-4x-Components-Redirect-Manager-screen-nl.png 1.5x, https://docs.joomla.org/images/0/0e/Help-4x-Components-Redirect-Manager-screen-nl.png 2x"
data-file-width="1299" data-file-height="518" width="800" height="319"
alt="Help-4x-Components-Redirect-Manager-screen-nl.png" />

## Kolomkoppen

Klik op de kolomkop om de lijst volgens deze kolom te sorteren.

- **Selectievakje**. Vink dit vakje aan om één of meer items te
  selecteren. Vink het vakje in de kolomkop aan om alle selectievakjes
  aan te vinken. Nadat één of meer vakjes zijn aangevinkt kan op een
  werkbalkknop geklikt worden om een actie uit te voeren op de
  geselecteerde item(s). De meeste acties via de werkbak, zoals
  Publiceren en Depubliceren kunnen op meerdere items tegelijkertijd
  uitgevoerd worden. Andere, zoals Bewerken, werken alleen voor één
  item. Indien er meerdere items geselecteerd zijn en op Bewerken wordt
  geklikt, opent het het eerste item om het te bewerken.
- **Status**: Publiceerstatus van het item. Mogelijke waarden zijn:
  - *Gepubliceerd*: Het item is gepubliceerd. Dit is de enige status de
    gewone website bezoekers in staat stelt dit item te bekijken.
  - *Gedepubliceerd*: Dit item is gedepubliceerd.
  - *Gearchiveerd*: Dit item is gearchiveerd.
  - *Verplaatst naar de prullenbak*: Dit item is naar de prullenbak
    verplaatst.
- **Verlopen URL.** De URL die verwezen wordt op uw website. Alleen het
  pagina gedeelte wordt getoond in deze lijst.
- **Nieuwe URL.** De doel URL voor de verwijzing.
- **Verwijzende pagina.** De aanroepende webpagina voor de verwijzing.
- **Aanmaakdatum.** Datum dat het item (artikel, categorie, weblink,
  etc.) aangemaakt is.
- **404 hits.** Het aantal 404 hits dat er op de URL is geweest.
- **Statuscode.** De statuscode van de pagina.
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
  instellingen](https://docs.joomla.org/Help4.x:Site_Global_Configuration/nl#defaultlistlimit "Help4.x:Site Global Configuration/nl").

**Filteropties**

- Status
- HTTP statuscode

**Paginabesturing** Als het aantal items meer is dan een pagina, zie je
een paginabesturing bij de onderkant van de pagina zoals in bovenstaande
[Screenshot](#screenshot). Het huidige paginanummer heeft een donkere
achtergrond.

- **Begin**. Klik om naar de eerste pagina te gaan.
- **Vorig**. Klik om naar de voorafgaande pagina te gaan.
- **Paginanummers**. Klik om naar de gewenste pagina te gaan.
- **Volgende**. Klik om naar de volgende pagina te gaan.
- **Einde**. Klik om naar de laatste pagina te gaan.

## Batchproces

Onder de lijst met verwijzingen staat een sectie genaamd 'Nieuwe URL(s)
als batch verwerken'. Deze functie geeft u de mogelijkheid de 'Nieuwe
URL' voor geselecteerde items aan te passen.

<img
src="https://docs.joomla.org/images/thumb/b/b5/Help-4x-Components-Redirect-Manager-batch_update-subscreen-nl.png/400px-Help-4x-Components-Redirect-Manager-batch_update-subscreen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/b/b5/Help-4x-Components-Redirect-Manager-batch_update-subscreen-nl.png/600px-Help-4x-Components-Redirect-Manager-batch_update-subscreen-nl.png 1.5x, https://docs.joomla.org/images/b/b5/Help-4x-Components-Redirect-Manager-batch_update-subscreen-nl.png 2x"
data-file-width="696" data-file-height="248" width="400" height="143"
alt="Help-4x-Components-Redirect-Manager-batch update-subscreen-nl.png" />

- **Nieuwe URL.** De doel-URL om de geselecteerde verwijzingen op in te
  stellen.
- **Notitie.** De notitie die opgenomen moet worden bij de geselecteerde
  verwijzingen.
- **Update links.** Werk alle geselecteerde verwijzingen bij met de
  opgegeven *Nieuwe URL* en *Notitie*.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#Schermafbeelding) hierboven. De functies zijn.

- **Nieuw**. Opent het bewerk scherm om een nieuwe item te maken.
- **Acties:** Toont een lijst met acties voor geselecteerde items.. Vink
  een of meer items aan om de lijst te activeren.
- **Inschakelen**. Maakt de selecteerde items beschikbaar om te
  gebruiken op uw website.
- **Uitschakelen**. Maakt de selecteerde items niet beschikbaar om te
  gebruiken op uw website.
- **Archiveren**. Verandert de status van één van de geselecteerde items
  om aan te geven dat ze worden gearchiveerd. Gearchiveerde items kunnen
  terug naar de gepubliceerde of gedepubliceerde status gebracht worden
  door *Gearchiveerd* te selecteren in het Selecteer status filter en de
  status van de items te wijzigen naar Gepubliceerd of Gedepubliceerd.
- **Prullenbak**. Verandert de status van de selecteerde items om aan te
  geven dat ze in de prullenbak zitten. Items in de prullenbak kunnen
  hersteld worden door "Verplaatst naar prullenbak" te kiezen in het
  'Selecteer status' zoekmiddel filter en de status van de items te
  veranderen in Gepubliceerd of Gedepubliceerd zoals gewenst.Selecteer,
  om naar de prullenbak verplaatste items te verwijderen, voor
  "Verplaatst naar prullenbak" in het Selecteer status filter, selecteer
  de items die definitief verwijderd moeten worden en klik daarna op het
  'Prullenbak leegmaken' werkbalk icoon.
- **Prullenbak legen.** Selecteer een of meer artikelen en klik op deze
  knop om ze definitief te verwijderen.
- **Batchinvoer**. Nieuwe URL's toevoegen in batchverwerking.
- **Opschonen uitgeschakeld**. Verwijdert alle uitgeschakelde links.
  URL's die nog ingeschakeld zijn worden niet verwijderd.
- **Opties.** Opent het venster Opties, waar instellingen zoals de
  standaard parameters kunnen worden bewerkt.
- **Help**. Opent dit helpscherm.

## Opties

Klik op het
[Opties](https://docs.joomla.org/Help4.x:Redirect:_Options/nl "Help4.x:Redirect: Options/nl")
knop scherm om deze component in te stellen.

## Snelle tips

Om uw verwijzingen te laten werken moet u de optie **Gebruik URL
herschrijven** in de **Algemene instellingen** opties van uw Joomla!
installatie activeren. Let er op dat het activeren van de 'Gebruik URL
herschrijven' optie niet genoeg is. U moet de extra stap van het
hernoemen van het *htaccess.txt* bestand in de map waar u Joomla! heeft
geïnstalleerd in *.htaccess* uitvoeren, of welke naam uw Apache server
nodig heeft voor zijn extra instellingen. In het Apache instellingen
bestand heet deze instelling 'AccessFileName' en staat standaard op
'.htaccess'.
