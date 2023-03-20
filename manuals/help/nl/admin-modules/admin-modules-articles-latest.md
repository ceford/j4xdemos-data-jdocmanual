<!-- Filename: Help4.x:Admin_Modules:_Articles_-_Latest / Display title: Modules: Nieuwste artikelen -->

## Beschrijving

Het **Nieuwste artikelen** moduletype wordt gebruikt om de "Recent
toegevoegde artikelen" in het controlepaneel te tonen.

## Hoe toegang te krijgen

- Selecteer **Systeem **→** Beheren venster **→** Beheerder modules**
  vanuit het beheermenu. Dan...
  - Om een nieuwe module aan te maken: selecteer de **Nieuw** knop uit
    de werkbalk. Dan...
    - Selecteer het gewenste moduletype.
  - Om een bestaande module te bewerken:
    - Zoek de module in de lijst met geïnstalleerde modules en selecteer
      de titel-link in de **Titel** kolom.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/3/32/Help-4x-modules-administrator-module-manager-articles-latest-nl.png/800px-Help-4x-modules-administrator-module-manager-articles-latest-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/3/32/Help-4x-modules-administrator-module-manager-articles-latest-nl.png 1.5x"
data-file-width="1096" data-file-height="862" width="800" height="629"
alt="Help-4x-modules-administrator-module-manager-articles-latest-nl.png" />

## Formulier velden

- **Titel.** De titel van de module. Dit is ook de titel die wordt
  weergegeven in de module afhankelijk van de *Toon Titel* formulierveld

### Module tabblad

**Linker venster**

- **Items om weer te geven.** Het aantal items dat getoond moet worden
  (standaard 5).
- **Volgorde.** (*Laatst toegevoegd eerst*/*Laatst bewerkt eerst*)
  Volgorde opties.
- **Categorie.** (*Elke categorie*/...) Selecteer artikelen vanuit een
  bepaald categorie of alle categorieën.
- **Auteurs:** (*Iedereen*/*Toegevoegd of bewerkt door mijzelf*/*Niet
  toegevoegd of bewerkt door mijzelf*/*Gemaakt door*). Filter op auteur.

**Rechter venster**

- **Toon titel.** (Toon/Verberg) Kies of de moduletitel op de website
  getoond of verborgen moet worden. De titel wordt degene in het
  formulierveld hierboven.
- **Positie.** Kies de [module
  positie](https://docs.joomla.org/Module_Position/nl "Module Position/nl")
  waarop u wilt dat de module getoond wordt. Een aangepaste module
  positie mag opgegeven worden om te gebruiken met de [load positie
  plugin](https://docs.joomla.org/How_do_you_put_a_module_inside_an_article%3F/nl "How do you put a module inside an article?/nl")
  of er kan op de positie knop gedrukt worden om een module positie te
  selecteren uit het template.
- **Status**. De publicatiestatus van het item.
- **Toegang**. Het
  [Toegangsniveau](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/nl "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/nl")
  om het item te bekijken.
- **Module volgorde.** Dit toont een drop-down lijst met iedere module
  op de positie waar de huidige module op staat. Dit is de zowel
  volgorde waarin de modules getoond worden op de website als op de
  [Modulebeheer](https://docs.joomla.org/Help4.x:Modules/nl "Help4.x:Modules/nl")
  pagina.
- **Start publiceren**. Datum en tijd waarop de publicatie moet starten.
  Gebruik dit veld wanneer u voortijdig inhoud wilt toevoegen die
  automatisch op een bepaalde tijd in de toekomst gepubliceerd moet
  worden.
- **Beëindig publiceren**. Datum en tijd om te stoppen met publiceren.
  Gebruik dit veld als u inhoud automatisch de status gedepubliceerd
  wilt geven op een tijdstip in de toekomst (bijvoorbeeld wanneer het
  niet meer van toepassing is).
- **Taal**. Item taal.
- **Notitie**. Dit wordt normaal gesproken door de beheerder gebruikt
  (bijvoorbeeld om informatie te documenteren voor dit item) en is niet
  op de website zichtbaar.

### Geavanceerd tabblad

<img
src="https://docs.joomla.org/images/thumb/2/2a/Help-4x-modules-manager-admin-module-site-advanced-options-nl.png/600px-Help-4x-modules-manager-admin-module-site-advanced-options-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/2a/Help-4x-modules-manager-admin-module-site-advanced-options-nl.png/900px-Help-4x-modules-manager-admin-module-site-advanced-options-nl.png 1.5x, https://docs.joomla.org/images/2/2a/Help-4x-modules-manager-admin-module-site-advanced-options-nl.png 2x"
data-file-width="1003" data-file-height="532" width="600" height="318"
alt="Help-4x-modules-manager-admin-module-site-advanced-options-nl.png" />

- **Weergave.** Als u één of meer alternatieve lay-outs voor een module
  heeft gedefinieerd of in het template of in Joomla! core, dan kunt u
  de layout voor de module hier selecteren.
- **Module class.** Een achtervoegsel dat toegevoegd wordt aan de CSS
  class van de Module. Dit stelt u in staat aangepaste CSS stijlen aan
  te maken die alleen op deze module worden toegepast. U kunt dan het
  "user.css" bestand van uw template aanpassen om de stijl toe te voegen
  aan de nieuwe class. Geef deze parameter op met een voorafgaande
  spatie om een nieuwe CSS class voor deze module aan te maken. Geef de
  parameter zonder voorafgaande spatie om de CSS class naam voor deze
  module aan te passen.
- **Cachen.** Gebruik algemeen/Niet cachen. Of de inhoud van deze module
  al dan niet gecached moet worden. Het instellen van "Gebruik algemeen"
  zal de cache instellingen uit de Algemene instellingen gebruiken.
- **Cachetijd.** Het aantal seconden waarvoor de cache van het item
  lokaal wordt opgeslagen. Deze kan veilig op de standaardwaarde blijven
  staan.
- **Modulestijl.** U kunt deze optie gebruiken om de template-stijl voor
  deze positie te overschrijven.
- **Module-tag.** De HTML tag waar de module in geplaatst wordt. Dit is
  standaard een div tag maar andere HTML5 elementen kunnen ook worden
  gebruikt.
- **Bootstrap grootte.** (waarden 0 tot 12) Dit stelt u in staat de
  breedte van de module in te stellen via het span element uit
  bootstrap.
- **Koptekst-tag.** De HTML tag die gebruikt moet worden voor de header
  of titel van de module. Dit kan een h1, h2, h3, h4, h5, h6 of een p
  tag zijn. Let op dat u een module stijl (chrome) moet gebruiken met
  *html5* of uw eigen stijlen toevoegen in */html/modules.php*.
- **Koptekst class.** Hier kunt u optionele CSS classes toevoegen aan
  het header of titel element.

### Rechten tabblad

<img
src="https://docs.joomla.org/images/thumb/4/4f/Help-4x-modules-manager-admin-module-administrator-permissions-nl.png/600px-Help-4x-modules-manager-admin-module-administrator-permissions-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/4f/Help-4x-modules-manager-admin-module-administrator-permissions-nl.png/900px-Help-4x-modules-manager-admin-module-administrator-permissions-nl.png 1.5x, https://docs.joomla.org/images/4/4f/Help-4x-modules-manager-admin-module-administrator-permissions-nl.png 2x"
data-file-width="977" data-file-height="665" width="600" height="408"
alt="Help-4x-modules-manager-admin-module-administrator-permissions-nl.png" />

Doe, om de rechten te veranderen, het volgende.

- Selecteer de **Groep** door links op de titel te klikken.
- Zoek de gewenste **Actie**. Mogelijke acties zijn:
  - **Verwijderen**. Gebruikers kunnen deze categorie verwijderen.
  - **Bewerken**. Gebruikers kunnen de module bewerken.
  - **Bewerk status**. Gebruikers kunnen de gepubliceerde status en de
    verwante informatie van de module wijzigen.
- Selecteer de gewenste rechten voor de actie die u wilt wijzigen.
  Mogelijke instellingen zijn:
  - '**Overgenomen:'** Overgenomen van gebruikers in deze groep vanuit
    de Algemene instellingen, Artikelen: Opties of Categorie rechten.
  - '**Toegestaan:'** Toegestaan voor gebruikers in deze groep. Let op
    dat wanneer deze actie op één van de hogere niveaus Geweigerd is het
    'Toegestaan' recht hier geen effect heeft. Een instelling geweigerd
    kan niet worden overschreven.
  - '**Geweigerd:'** Geweigerd voor alle gebruikers in deze groep.
- Klik op **Opslaan** in de **werkbalk**. Wanneer het scherm wordt
  vernieuwd, tonen de berekende instellingen de effectieve rechten voor
  deze groep en actie.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#Schermafbeelding) hierboven. De functies zijn.

- **Opslaan**. Slaat item op en blijft op het huidige scherm.
- **Opslaan & sluiten**. Slaat item op en sluit het huidige scherm.
- **Opslaan & nieuw**. Slaat item op en houdt het bewerkscherm open,
  klaar voor het aanmaken van een ander item.
- **Opslaan als kopie**. Slaat uw wijzigingen op als een kopie van het
  huidige item. Beïnvloed het huidige item niet. Dit werkbalk icoon
  wordt niet getoond bij het aanmaken van een nieuw item.
- **Sluiten**. Sluit het huidige scherm en keert terug naar het vorige
  scherm zonder wijzigingen die u misschien heeft gedaan op te slaan.
  This toolbar icon is not shown if you are creating a new item.
- **Help**. Opent dit helpscherm.
