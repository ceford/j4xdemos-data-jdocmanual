<!-- Filename: Help4.x:Templates:_Edit_Style / Display title: Templates: Bewerk stijl -->

## Beschrijving

Hier bewerkt u de stijl van een template. Wanneer een template voor het
eerst geïnstalleerd wordt, wordt er een standaard stijl aangemaakt. De
standaard stijl voor het template heeft dezelfde naam als het template
met een - standaard achtervoegsel. Vink, om een andere versie van van de
standaard stijl aan te maken, de standaard stijl checkbox aan en druk op
het dupliceer icoon in de werkbalk. Bewerk daarna de kopie.

## Hoe toegang te krijgen

- Selecteer **Systeem **→** Templates venster **→** Website
  templatestijlen** vanuit het beheermenu. Of...
- Selecteer **Systeem **→** Templates venster **→** Beheer
  templatestijlen** vanuit het beheermenu. Dan...
  - Selecteer de naam van de templatestijl die bewerkt moeten worden in
    de stijl kolom.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/c/c7/Help-4x-Extensions-Template-Manager-Styles-Edit-screen-nl.png/800px-Help-4x-Extensions-Template-Manager-Styles-Edit-screen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c7/Help-4x-Extensions-Template-Manager-Styles-Edit-screen-nl.png/1200px-Help-4x-Extensions-Template-Manager-Styles-Edit-screen-nl.png 1.5x, https://docs.joomla.org/images/c/c7/Help-4x-Extensions-Template-Manager-Styles-Edit-screen-nl.png 2x"
data-file-width="1211" data-file-height="600" width="800" height="396"
alt="Help-4x-Extensions-Template-Manager-Styles-Edit-screen-nl.png" />

### Formulier velden

- **Stijlnaam.** De naam van de stijl. Dit is de naam die getoond wordt
  in de stijl kolom van het *Template: Stijlen* scherm.

### Gegevens tabblad

- **Templatenaam.** De naam van het template, Website of Beheerindicatie
  en een korte beschrijving.
- **Standaard.** Of de stijl al dan niet de standaard voor de locatie
  is.
- **Template.** De naam van het template waar de stijl van is afgeleid.

### Geavanceerde tabblad

Deze sectie hoeft niet aanwezig te zijn bij alle stijlen. Als een
template waarvan een stijl is afgeleid instelbare opties heeft, dan zijn
ze hier te vinden. Het zijn deze instelbare opties die de mogelijkheid
bieden verschillende stijlen van een template te hebben met
verschillende opties. De beschikbare opties variëren afhankelijk van
welke opties de template ontwikkelaar beschikbaar heeft gesteld.

### Atum kleurinstellingen

Het standaard beheer template geeft de mogelijkheid te experimenteren
met kleurvariaties. Opslaan en kijken!

### Atum afbeeldingsinstellingen

U kunt een afbeelding selecteren om het **Inloglogo** in het beheer
inlogformulier te vervangen en het **Merk logo** in de beheer titel balk
in uitgebrande modus en in compacte modus. De standaards zijn de Joomla
merk logo's. In de titel balk, is het woord Joomla! aanwezig in de
**Merk groot** versie en ontbreekt in de **Merk klein** versie.
Selecteer **Wissel menu** om de verandering te zien.

Indien u uw eigen 'Merk klein' heeft dan moet u ook zorgen voor een
override van de breedte. Creëer, om dat te doen, een user.css bestand in
de template root en voeg het volgende toe, maar vervang 3rem door een
geschikte breedte voor uw afbeelding:

       .header .logo.small {
           width: 3rem;
       }

### Menutoewijzing tabblad

Deze sectie bevat alle menu-items ingesteld in uw Joomla! website. Vink,
om de huidige stijl toe te wijzen aan de webpagina van een menu-item,
het vakje naast het menu-item aan. U kunt op de *Selectie omkeren* knop
drukken om de menu-item selectie om te keren.

**Let op**: Als een vakje grijs is en niet aangevinkt kan worden dan kan
dat zijn omdat het menu-item door een andere gebruiker gebruikt wordt. U
kunt zien of dit het geval is door te gaan naar het [menubeheer scherm
van het betreffende
menu](https://docs.joomla.org/Help4.x:Menus:_Items/nl "Help4.x:Menus: Items/nl").
Als er een hangslot symbool staat bij het menu-item, dan wordt het
momenteel gebruikt door een andere gebruiker.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#Schermafbeelding) hierboven. De functies zijn.

- **Opslaan**. Slaat item op en blijft op het huidige scherm.

<!-- -->

- **Opslaan & sluiten**. Slaat item op en sluit het huidige scherm.

<!-- -->

- **Opslaan als kopie**. Slaat uw wijzigingen op als een kopie van het
  huidige item. Beïnvloed het huidige item niet. Dit werkbalk icoon
  wordt niet getoond bij het aanmaken van een nieuw item.

<!-- -->

- **Annuleren/Sluiten**. Sluit het huidige scherm en keert terug naar
  het vorige scherm zonder wijzigingen die u misschien heeft gedaan op
  te slaan.

<!-- -->

- **Help**. Opent dit helpscherm.

## Verwante informatie

- Om templates te installeren: [Extensies:
  Installeren](https://docs.joomla.org/Help4.x:Extensions:_Install/nl "Help4.x:Extensions: Install/nl")
