<!-- Filename: Help4.x:Menus / Display title: Menu's -->

## Beschrijving

Menu's geven gebruikers de mogelijkheid door de site te navigeren. Een
menu is een object dat één of meer menu-items bevat. Ieder menu-item
wijst naar een logische pagina op de site. Een menu module is
noodzakelijk om het menu op de pagina te plaatsen. Eén menu kan meer dan
een module hebben. Eén module kan bijvoorbeeld alleen de eerste niveau
menu-items tonen en de tweede module kan de menu-items van het tweede
niveaus tonen.

De menulijst biedt een overzicht van de menu's op een Joomla website.
Dit omvat de details van gepubliceerde, gedepubliceerde en items in de
prullenbak en de namen van gelinkte modules van ieder individueel menu.

Het proces voor het toevoegen van een menu aan de site is normaliter als
volgt:

1.  Maak een nieuw menu aan (via dit scherm).
2.  Maak een of meer nieuwe menu-items aan voor het menu. Ieder
    menu-item zal een specifiek menu-itemtype hebben.
3.  Maak een of meer menu modules aan om het menu op de site te tonen.
    Als u de modules aanmaakt, selecteert u op welke pagina's de modules
    getoond worden.

## Hoe toegang te krijgen

- Selecteer **Menu's **→** Beheren** vanuit het beheermenu.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/6/61/Help-4x-menus-menu-manager-menus-nl.png/800px-Help-4x-menus-menu-manager-menus-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/6/61/Help-4x-menus-menu-manager-menus-nl.png 1.5x"
data-file-width="1159" data-file-height="690" width="800" height="476"
alt="Help-4x-menus-menu-manager-menus-nl.png" />

## Kolomkoppen

Klikken op de titel van een kolom zal de tabelweergave sorteren op die
kolom. Een neer-pijl naast de kolomtitel betekent aflopend en een pijl
naar boven betekent een oplopende volgorde. De standaard sorteervolgorde
is op **ID#** in oplopende volgorde.

- **Selectievakje**. Vink dit vakje aan om één of meer items te
  selecteren. Vink het vakje in de kolomkop aan om alle selectievakjes
  aan te vinken. Nadat één of meer vakjes zijn aangevinkt kan op een
  werkbalkknop geklikt worden om een actie uit te voeren op de
  geselecteerde item(s). De meeste acties via de werkbak, zoals
  Publiceren en Depubliceren kunnen op meerdere items tegelijkertijd
  uitgevoerd worden. Andere, zoals Bewerken, werken alleen voor één
  item. Indien er meerdere items geselecteerd zijn en op Bewerken wordt
  geklikt, opent het het eerste item om het te bewerken.
- **Titel**. De naam van het menu.
- **\# Gepubliceerd**. Aantal gepubliceerde menu-items in dit menu.
- **\# Gedepubliceerd**. Aantal gedepubliceerde menu-items in dit menu.
- **\# Verplaatst naar prullenbak**. Aantal naar de prullenbak
  verplaatste menu-items in dit menu.
- **Gelinkte modules**. Toont menu modules gekoppeld aan het menu. De
  kolom toont de modulenaam, toegangsniveau en positie op het template.
- **ID**. Dit is een uniek identificatienummer voor dit item,
  automatisch toegekend door Joomla!. Het wordt gebruikt om het item
  intern te identificeren en u kunt dit nummer niet veranderen. Als u
  een nieuw item aanmaakt, is dit veld "0" totdat u het opslaat, waarbij
  een nieuw ID toegekend wordt.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#Schermafbeelding) hierboven. De functies zijn.

- **Nieuw**. Opent het bewerk scherm om een nieuwe menu te maken.
- **Bewerken**. Opent het scherm voor het bewerken van het geselecteerde
  menu. Als er meer dan één menu is geselecteerd (indien van
  toepassing), wordt alleen het eerste menu geopend. Het
  bewerkingsscherm kan ook worden geopend door te klikken op de Naam van
  het menu.
- **Verwijderen:** Verwijderd de geselecteerde menus. Werkt met één of
  meerdere menus geselecteerd. Het verwijderen van een menu verwijdert
  ook alle menu-items die het bevat en gekoppelde menu-modules. Bij het
  klikken op 'Verwijderen' wordt u gevraagd te bevestigen dat u de
  geselecteerde menu's wilt verwijderen. Klikken op de OK knop zal de
  menu's verwijderen. Klik op 'Annuleren' op het verwijderen af te
  breken.
- **Opnieuw opbouwen.** Ververst en stelt de menu tabel opnieuw samen.
  Normaal hoeft u de tabel *niet* opnieuw op te bouwen. Deze functie
  voorziet in het geval de data in de tabel corrupt raakt.
- **Opties.** Opent het venster Opties, waar instellingen zoals de
  standaard parameters kunnen worden bewerkt. Zie [Menus
  Configuration](https://docs.joomla.org/Help4.x:Components_Menus_Configuration "Special:MyLanguage/Help4.x:Components Menus Configuration").
- **Help**. Opent dit helpscherm.

## Snelle tips

- Het is raadzaam een beschrijvende titel aan nieuwe menu's te geven
  omdat u het in het *Beheren* menu ziet. Het is een goed idee het
  *Beschrijving* veld te vullen met informatie over het menu. Als u een
  korte titel in het *Module titel* veld invult, dan kunt u de
  menu-module identificeren met behulp van die titel in modulebeheer.
- Hoewel u een kopie van een geselecteerd menu kunt aanmaken door op de
  *Opslaan als kopie* werkbalk knop te drukken, kunt u ook in
  modulebeheer een andere instantie aanmaken.
- Gebruik, als u een nieuw menu aanmaakt, alleen alfanumerieke tekens
  zonder spaties in het *Unieke naam* veld. Het is verstandig alleen
  a-z, 0-9 en underscore (\_) tekens te gebruiken.
- Als u geen *Moduletitel* opgeeft, dan wordt er geen module aangemaakt
  en kan het menu niet getoond worden op de website. U kunt echter
  modulebeheer later gebruiken om een nieuwe mod_mainmenu module aan te
  maken en het aan het menu koppelen.
- Als u een bestaand menu verwijderd, vergeet dan niet dat alle
  menu-items van dat menu ook verwijderd worden.
- Het Hoofdmenu is uw standdard menu-item, het zou dan ook **niet
  verwijderd moeten worden**. Het standaard menu-item bepaalt de pagina
  die getoond wordt als u www.*uwsite*.top-domein bezoekt en uw site
  werkt niet als het verwijderd wordt. Het is normaliter uw Home menu
  item maar het kan worden ingesteld op ieder menu-item inclusief een
  menu-item in een verborgen menu. Als u het standaard menu-item
  verandert, zorg er dan voor dat u ook dat menu-item niet verwijdert!
  Het menu met het standaard menu-item wordt aangegeven door een
  sterretje (\*) in het *Menu's* menu.

## Verwante informatie

- Om nieuwe menu's toe te voegen: [Menu Beheer
  Nieuw/Bewerken](https://docs.joomla.org/Help4.x:Menus:_Edit/nl "Help4.x:Menus: Edit/nl")
- Om actie rechten voor menu's in te stellen: [Menu's
  instellingen](https://docs.joomla.org/Help4.x:Menus:_Options/nl "Help4.x:Menus: Options/nl")
- Om menu-items toe te voegen of te bewerken: [Menu-item
  beheer](https://docs.joomla.org/Help4.x:Menus:_Items/nl "Help4.x:Menus: Items/nl")
- Om menumodules toe te voegen of te bewerken: [Module
  beheer](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/nl "Help4.x:Menu Item: New Item/nl")
