<!-- Filename: Help4.x:Fields:_Edit / Display title: Velden: Bewerken -->

## Beschrijving

Dit is het beheerscherm waar u velden kunt toevoegen en bewerken. U kunt
ook een veldgroep selecteren voor een veld en aangeven of het al dan
niet gepubliceerd is en of het gekoppeld is aan een of meer
artikelcategorieën.

The helpscreen show as example Users.

## Hoe toegang te krijgen

**Gebruikers **→** Velden**

Om een veld aan te maken:

- Klik de **Nieuw** werkbalk knop.

Om een veld te bewerken:

- Selecteer de **titel** in de lijst.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/9/9d/Help-4x-Fields-Edit-screen-nl.png/800px-Help-4x-Fields-Edit-screen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/9/9d/Help-4x-Fields-Edit-screen-nl.png/1200px-Help-4x-Fields-Edit-screen-nl.png 1.5x, https://docs.joomla.org/images/thumb/9/9d/Help-4x-Fields-Edit-screen-nl.png/1600px-Help-4x-Fields-Edit-screen-nl.png 2x"
data-file-width="2720" data-file-height="1700" width="800" height="500"
alt="Help-4x-Fields-Edit-screen-nl.png" />

## Formulier velden

- **Titel**. De titel van dit veld.

### Algemeen

**Linker venster**

Parameters voor alle extra velden:

- **Type**. Als u een veld aanmaakt kunt u één van de 16 veldtypes
  kiezen. Als het veld opgeslagen wordt staat het type vast. U kunt het
  later niet veranderen. [Meer
  leren.](https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field/nl "J3.x:Adding custom fields/Calendar Field/nl")
- **Naam**. De naam die gebruikt wordt om het veld te definiëren. Indien
  deze leeg wordt gelaten zal Joomla deze met een standaardwaarde vanuit
  de titel vullen.
- **Label**. Gebruik een beschrijvende tekst van het veld voor het label
  van het veld. Deze tekst is niet vertaalbaar. Als u geen tekst voor
  het label opgeeft, dan wordt de titeltekst ook gebruikt als
  labeltekst.
- **Beschrijving**. De beschrijving van het veld. Een tekst die getoond
  wordt als tool-tip als de gebruiker de muis over de tekstbox beweegt
  in het beheergedeelte bij het aanmaken van een artikel of
  contactpersoon of een component van derden die extra velden
  ondersteund. Deze tekst is niet vertaalbaar. U ziet de beschrijving
  niet op de website.
- **Verplicht**. Is dit een verplicht veld? In dit geval moet het veld
  ingevuld worden voor het verzenden van een artikel, contactpersoon of
  component van derden die speciale velden ondersteunt.

**Rechter venster**

- **Status**. De publicatiestatus van dit veld.
  - Gepubliceerd: Het veld is zichtbaar bij het bewerken van een artikel
    of contactpersoon en het is zichtbaar op de website.
  - Gedepubliceerd: Het veld wordt niet zichtbaar voor gebruikers bij
    het bewerken van een artikel of een contactpersoon.
  - Gearchiveerd: Het veld zal niet meer getoond worden bij het bewerken
    van een artikel of contactpersoon. U kunt het openen bij
    [veldbeheer](https://docs.joomla.org/Help4.x:Fields/nl#selectstatus "Help4.x:Fields/nl")
    als u het filter op 'Gearchiveerd' zet.
  - Verplaatst naar prullenbak: Het veld is verwijderd maar nog in de
    database. Het kan definitief verwijderd worden uit de database via
    de 'Prullenbak legen' functie bij
    [veldbeheer](https://docs.joomla.org/Help4.x:Fields/nl#selectstatus "Help4.x:Fields/nl").
    [Meer
    leren.](https://docs.joomla.org/J4.x:Deleting_an_Article/nl "J4.x:Deleting an Article/nl")
- **Veldgroepen**. U kunt een extra veld koppelen aan één of meer
  veldgroepen.
- **Categorie**. U kunt een speciaal veld koppelen aan één of meer
  categorieën. Bedenk dat de standaard 'Alle' niet de 'uncategorized'
  artikelen omvat.
- **Toegang**. Selecteer het weergave toegangsniveau van dit veld. De
  toegangsniveaus hangen af van wat ingesteld is bij [Gebruikers:
  Toegangsniveaus](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/nl "Help4.x:Users: Viewing Access Levels/nl")
  .
- **Taal**. Selecteer de taal voor dit extra veld. Wanneer u de
  [meertalige
  functie](https://docs.joomla.org/Help4.x:Extensions:_Languages/nl "Help4.x:Extensions: Languages/nl")
  in Joomla niet gebruikt, laat dan de standaard ingevulde 'Alle'
  ongewijzigd.
- **Notitie**. Een optioneel veld om persoonlijke notities voor het veld
  te maken.

### Opties

<img
src="https://docs.joomla.org/images/thumb/e/e3/Help-4x-Fields-Edit-options-subscreen-nl.png/600px-Help-4x-Fields-Edit-options-subscreen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/e3/Help-4x-Fields-Edit-options-subscreen-nl.png/900px-Help-4x-Fields-Edit-options-subscreen-nl.png 1.5x, https://docs.joomla.org/images/thumb/e/e3/Help-4x-Fields-Edit-options-subscreen-nl.png/1200px-Help-4x-Fields-Edit-options-subscreen-nl.png 2x"
data-file-width="2880" data-file-height="1378" width="600" height="287"
alt="Help-4x-Fields-Edit-options-subscreen-nl.png" />

**Veld opties**

- **Tijdelijke aanduiding**. Een tijdelijke tekst die verschijnt binnen
  het extra veld als hint voor de invoer. De tijdelijke aanduiding is in
  het beheergedeelte actief bij het aanmaken van een artikel,
  contactpersoon of een component van derden die extra velden
  ondersteunt. U ziet het niet op de website.
- **Veld class**. Het class attribuut van het veld als het veld
  gegenereerd wordt. Indien verschillende classes nodig zijn, scheid ze
  dan door spaties.
- **Label class (formulier)**. CSS class to apply to the field label
  when it is in edit mode (entering input into a field).
- **Bewerkbaar in**. Op welk deel van de site moet het veld getoond
  worden. In het Beheergedeelte, op de website of beide?
- **Showon Attribute**. Conditionally show or hide the field depending
  on the value of other fields. The syntax to use here, for example:
  `list-of-items:value1[OR]list-of-items:value2`
  - list-of-items – It is the *name* of an already created field on
    which this field will depends to be show.
  - value1 – Is the value need have the field on which it depends to be
    show.
  - \[OR\] – To create a choice among multiple fields. In the example,
    this field will show when *list-of-items* field have the value:
    *value1* OR *value2*
  - \[AND\] – To combine multiple fields. This field will show only when
    *list-of-items* field have the value: *value1* AND *value2*
  - You can also use value 'does not equal' as in
    **list-of-items!:value1**. The syntax will show this field only when
    *list-of-items* is not equal to *value1*
  - To show this field when *list-of-items* field has been selected and
    have not a empty value, use the syntax *list-of-items!:* (without a
    value specified).

**Note:** Subform fields handle different the identifier *name* of
*list-of-items*. If you create a Subform custom field and you add this
conditional field you are creating to there, you need use *field\[ID\]*
instead of *list-of-items*, where ID is the id of the field
*list-of-items*. Therefore, the showon attribute for this conditional
field you are creating need be: `field36:value1[OR]field36:value2` where
36 is the ID of the field 'List of items'.

**Weergave opties**

- **Toon class**. De class van de veld container in de uitvoer.
- **Waarde class**. De class van de veldwaarde in de uitvoer.
- **Label**. Show the label when the field renders.
- **Label class (uitvoer)**. CSS class to apply to the field label when
  it is displayed (displaying the output of a field).
- **Automatische weergave**. Joomlaǃ biedt inhoud-'events' die
  uitgevoerd worden tijdens het aanmaak-proces. Dit is de plek om aan te
  geven hoe extra velden in de inhoud moeten worden opgenomen.
  - Na de titel
  - Voor de weergave van inhoud
  - Na weergave van inhoud
  - Niet automatisch weergeven
- **Voorvoegsel**. Fixed text to be displayed before a field, for
  example £.
- **Achtervoegsel**. Fixed text to be displayed after a field, for
  example EUR.
- **Weergave**. If there is a custom layout then it would be selected
  here.
- **Toon indien alleen-lezen**. If the field is read only (perhaps the
  user doesn't have the access level) should the field be displayed or
  hidden.

### Publiceren

<img
src="https://docs.joomla.org/images/thumb/0/0c/Help-4x-Fields-Edit-publishing-subscreen-nl.png/600px-Help-4x-Fields-Edit-publishing-subscreen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/0c/Help-4x-Fields-Edit-publishing-subscreen-nl.png/900px-Help-4x-Fields-Edit-publishing-subscreen-nl.png 1.5x, https://docs.joomla.org/images/thumb/0/0c/Help-4x-Fields-Edit-publishing-subscreen-nl.png/1200px-Help-4x-Fields-Edit-publishing-subscreen-nl.png 2x"
data-file-width="2880" data-file-height="980" width="600" height="204"
alt="Help-4x-Fields-Edit-publishing-subscreen-nl.png" />

- **Aanmaakdatum**. Het tijdstip waarop het veld gemaakt was. Voer een
  andere datum en tijd in of klik op het kalender icoon om de gewenste
  datum te selecteren.
- **Gemaakt door**. Naam van de gebruiker die dit veld gemaakt heeft.
  Dit is standaard de huidig ingelogde gebruiker. Klik op de knop
  selecteer gebruiker en selecteer een andere gebruiker indien dit
  aangepast moet worden naar een andere gebruiker.
- **Aanpassingsdatum**. Datum van laatste wijziging.
- **Aangepast door**. Gebruikersnaam wie de laatste aanpassing heeft
  gedaan.
- **ID**. Een uniek identificatienummer voor dit veld, men kan dit
  nummer niet veranderen. Als een nieuw veld wordt aangemaakt, is dit
  veld "0" totdat het wordt opgeslagen.

### Rechten

Hier kunt u rechten invoeren voor dit veld. [Meer
leren.](https://docs.joomla.org/J3.x:Access_Control_List_Tutorial/nl#hierarchylevels "J3.x:Access Control List Tutorial/nl")

<img
src="https://docs.joomla.org/images/thumb/f/fc/Help-4x-Fields-Edit-permissions-subscreen-nl.png/600px-Help-4x-Fields-Edit-permissions-subscreen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/fc/Help-4x-Fields-Edit-permissions-subscreen-nl.png/900px-Help-4x-Fields-Edit-permissions-subscreen-nl.png 1.5x, https://docs.joomla.org/images/thumb/f/fc/Help-4x-Fields-Edit-permissions-subscreen-nl.png/1200px-Help-4x-Fields-Edit-permissions-subscreen-nl.png 2x"
data-file-width="2880" data-file-height="1260" width="600" height="263"
alt="Help-4x-Fields-Edit-permissions-subscreen-nl.png" />

Om de rechten van dit veld te wijzigen moet u de volgende handelingen
uitvoeren.

1.  Selecteer de **Groep** door op de titel aan de linkerzijde te
    klikken.
2.  Zoek de gewenste **Actie**.
    - **Verwijderen**. Gebruikers kunnen dit veld verwijderen.
    - **Bewerken.** Gebruikers kunnen dit veld bewerken.
    - **Bewerk status**. Gebruikers kunnen de 'gepubliceerd' status en
      verwante informatie van dit veld wijzigen.
    - **Bewerk waarde extra veld.** Gebruikers kunnen de Extra veld
      waarde bewerken.
3.  Selecteer de gewenste rechten voor de actie die u wilt wijzigen.
    - **Overgenomen**. Neemt de rechten over voor deze groep zoals deze
      zijn ingesteld in de [Algemene
      instellingen](https://docs.joomla.org/Help4.x:Site_Global_Configuration/nl#permissions "Help4.x:Site Global Configuration/nl"),
      hoofdgroep en categorie.
    - **Toegestaan**. Toegestaan voor gebruikers in deze groep.Let op:
      Als deze actie 'Geweigerd' is op een van de hogere niveaus, dan
      heeft de 'Toegestaan' rechten hier geen effect. Een 'Geweigerd'
      instelling kan niet overschreven worden.
    - **Geweigerd**. Geweigerd voor alle gebruikers in deze groep.
4.  Klik op **Opslaan** in de **werkbalk** bovenin. Wanneer het scherm
    herladen wordt zal de nieuwe gecalculeerde rechten voor deze groep
    en actie weergegeven worden.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#screenshot) hierboven.

- **Opslaan**. Slaat veld op en blijft op het huidige scherm.
- **Opslaan & sluiten**. Slaat veld op en sluit het huidige scherm.
  - **Opslaan & nieuw**. Slaat veld op en houdt het bewerkscherm open,
    klaar voor het aanmaken van een ander veld.
  - **Opslaan als kopie**. Slaat uw wijzigingen op als een kopie van het
    huidige veld. Beïnvloed het huidige veld niet.
- **Sluiten**. Sluit het huidige scherm en keert terug naar het vorige
  scherm zonder wijzigingen die u misschien heeft gedaan op te slaan.
- **Help**. Opent dit helpscherm.

## Snelle tips

Klik, als u wilt weten hoe u extra velden kunt gebruiken op [Het beheren
van extra
velden](https://docs.joomla.org/J3.x:Adding_custom_fields/nl "J3.x:Adding custom fields/nl")

## Verwante informatie

- Dit
  [portaal](https://docs.joomla.org/Portal:Joomla_4/nl "Portal:Joomla 4/nl")
  brengt informatie specifiek gerelateerd aan Joomla 4 samen.

|                                                                                                                |                                                                                                                                                                                 |
|----------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Verwante helpschermen                                                                                          | Beschrijving                                                                                                                                                                    |
| [Velden](https://docs.joomla.org/Help4.x:Fields/nl "Help4.x:Fields/nl")                                        | Velden worden gebruikt om extra attributen van artikelen, contactpersonen of gebruikers te tonen. De gegevens worden ingevoerd in een beheerformulier en getoond op de website. |
| <span class="mw-selflink selflink">Velden: Bewerken</span>                                                     | Dit is waar velden in artikelen, contactpersonen en gebruikers kunnen worden toegevoegd en bewerkt.                                                                             |
| [Veldgroepen](https://docs.joomla.org/Help4.x:Field_Groups/nl "Help4.x:Field Groups/nl")                       | Het veldgroep scherm wordt gebruikt om een lijst met veldgroepen te tonen, ze toe te voegen en te bewerken.                                                                     |
| [Veldgroepen: Bewerken](https://docs.joomla.org/Help4.x:Field_Groups:_Edit/nl "Help4.x:Field Groups: Edit/nl") | Veldgroepen worden gebruikt om gerelateerde velden te verzamelen onder een apart tabblad op een invoerformulier                                                                 |
