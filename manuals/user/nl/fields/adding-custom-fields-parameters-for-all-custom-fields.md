<!-- Filename: J3.x:Adding_custom_fields/Parameters_for_all_Custom_Fields / Display title: Toevoegen van extra velden/Parameters voor alle extra velden -->

## Parameters voor alle extra velden

**Artikelen in deze reeks**

1.  [Inleiding](https://docs.joomla.org/J3.x:Adding_custom_fields "Special:MyLanguage/J3.x:Adding custom fields")
2.  [Parameters voor alle extra
    velden](https://docs.joomla.org/J3.x:Adding_custom_fields/Parameters_for_all_Custom_Fields "Special:MyLanguage/J3.x:Adding custom fields/Parameters for all Custom Fields")
3.  [Kalender
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field "Special:MyLanguage/J3.x:Adding custom fields/Calendar Field")
4.  [Selectievakjes
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Checkboxes_Field "Special:MyLanguage/J3.x:Adding custom fields/Checkboxes Field")
5.  [Kleur
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Color_Field "Special:MyLanguage/J3.x:Adding custom fields/Color Field")
6.  [Tekstverwerker
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Editor_Field "Special:MyLanguage/J3.x:Adding custom fields/Editor Field")
7.  [Integer
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Integer_Field "Special:MyLanguage/J3.x:Adding custom fields/Integer Field")
8.  [Lijst
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/List_Field "Special:MyLanguage/J3.x:Adding custom fields/List Field")
9.  [Lijst met afbeeldingen
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/ListOfImages_Field "Special:MyLanguage/J3.x:Adding custom fields/ListOfImages Field")
10. [Media
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Media_Field "Special:MyLanguage/J3.x:Adding custom fields/Media Field")
11. [Keuzerondje
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Radio_Field "Special:MyLanguage/J3.x:Adding custom fields/Radio Field")
12. [Herhalend
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Repeatable_Field "Special:MyLanguage/J3.x:Adding custom fields/Repeatable Field")
13. [SQL
    veld](https://docs.joomla.org/J3.x:Adding_custom_fieldshttps://docs.joomla.org/J3.x:Adding%20custom%20fields/Sql%20Field)
14. [Tekst
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Text_Field "Special:MyLanguage/J3.x:Adding custom fields/Text Field")
15. [Tekstvak
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Textarea_Field "Special:MyLanguage/J3.x:Adding custom fields/Textarea Field")
16. [URL
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Url_Field "Special:MyLanguage/J3.x:Adding custom fields/Url Field")
17. [Gebruiker
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/User_Field "Special:MyLanguage/J3.x:Adding custom fields/User Field")
18. [Gebruikersgroep
    veld](https://docs.joomla.org/J3.x:Adding_custom_fields/Usergroup_Field "Special:MyLanguage/J3.x:Adding custom fields/Usergroup Field")
19. [Hoe kunt u extra velden
    groeperen](https://docs.joomla.org/J3.x:Adding_custom_fields/How%CC%9E_can_you_group_custom_fields "Special:MyLanguage/J3.x:Adding custom fields/How̞ can you group custom fields")
20. [Welke componenten ondersteunen extra
    velden](https://docs.joomla.org/J3.x:Adding_custom_fields/What_components_are_supporting_custom_fields "Special:MyLanguage/J3.x:Adding custom fields/What components are supporting custom fields")
21. [Implementatie in uw
    component](https://docs.joomla.org/J3.x:Adding_custom_fields/Implement_into_your_component "Special:MyLanguage/J3.x:Adding custom fields/Implement into your component")
22. [Extra velden gebruiken in uw
    overrides](https://docs.joomla.org/J3.x:Adding_custom_fields/Overrides "Special:MyLanguage/J3.x:Adding custom fields/Overrides")

## Parameters voor alle extra velden

De extra velden lijst zal initieel leeg zijn. Klik op **Nieuw** om een
veld toe te voegen.  
Op het tabblad **Algemeen** moet u de verplichte gegevens invullen:

- Titel  
  De titel van het veld. De titel wordt getoond op de veldbeheer pagina,
  waar u het veld kunt openen om te bewerken door op de titel te
  klikken. De titel is wordt niet getoond als u een artikel of een
  contactpersoon aanmaakt nog op de website.
- Naam  
  De naam die gebruikt wordt om het veld te definiëren. Indien deze leeg
  wordt gelaten zal Joomla! deze met een standaardwaarde vanuit de titel
  vullen.
- Type  
  Als u een veld aanmaakt kunt u één van de 16 veldtypes kiezen. Als het
  veld opgeslagen wordt staat het type vast. U kunt het later niet
  veranderen.

Voor ieder veld kunt u deze parameters gebruiken:

- Label  
  Gebruik een beschrijvende tekst van het veld voor het label van het
  veld. Deze tekst is niet vertaalbaar. Als u geen tekst voor het label
  opgeeft, dan wordt de titeltekst ook gebruikt als labeltekst.
- Beschrijving  
  De beschrijving van het veld. Een tekst die getoond wordt als tool-tip
  als de gebruiker de muis over de tekstbox beweegt in het
  beheergedeelte bij het aanmaken van een artikel of contactpersoon of
  een component van derden die extra velden ondersteund. Deze tekst is
  niet vertaalbaar. U ziet de beschrijving niet op de website.
- Verplicht  
  Is dit een verplicht veld? In dit geval moet het veld ingevuld worden
  voor het verzenden van een artikel, contactpersoon of component van
  derden die speciale velden ondersteunt. U kunt de opties *Ja* of *Nee*
  kiezen.
- Standaardwaarde  
  Hier kunt u een standaardwaarde opgeven voor het extra veld. Deze
  tekst is niet vertaalbaar. Merk op dat in sommige lijstvelden de
  waarde als standaard moet worden opgegeven en bij andere de index.
- Status  
  U kunt een publicatiestatus instellen. Is het veld *Gepubliceerd*,
  *Gedepubliceerd*, *Gearchiveerd* or *Verplaatst naar prullenbak*?
  - Gepubliceerd: Het veld is zichtbaar bij het bewerken van een artikel
    of contactpersoon en het is zichtbaar op de website.
  - Gedepubliceerd: Het veld wordt niet zichtbaar voor gebruikers bij
    het bewerken van een artikel of een contactpersoon.
  - Gearchiveerd: Het veld zal niet meer getoond worden bij het bewerken
    van een artikel of contactpersoon. U kunt het openen bij veldbeheer
    als u het filter op 'Gearchiveerd' zet.
  - Verplaatst naar prullenbak: Het veld is verwijderd maar nog in de
    database. Het kan definitief verwijderd worden uit de database via
    de 'Prullenbak legen' functie bij veldbeheer.
- Veldgroepen  
  U kunt een extra veld koppelen aan één of meer veldgroepen.
- Categorie  
  U kunt een speciaal veld koppelen aan één of meer categorieën. Bedenk
  dat de standaard 'Alle' niet de 'uncategorized' artikelen omvat.
- Toegang  
  Het
  [Toegangsniveau](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/nl "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/nl")
  voor dit item.
- Taal  
  Selecteer de taal voor dit extra veld. Als u geen [meertalige
  functie](https://docs.joomla.org/J3.x:Setup_a_Multilingual_Site "J3.x:Setup a Multilingual Site")
  van Joomla gebruikt, houd dan de standaard van *Alle*.
- Notitie  
  Een optioneel veld om persoonlijke notities voor het veld te maken.

Op het tabblad **Opties** kunt u de volgende opties gebruiken:

- Tijdelijke aanduiding  
  Een tijdelijke tekst die verschijnt binnen het extra veld als hint
  voor de invoer. De tijdelijke aanduiding is in het beheergedeelte
  actief bij het aanmaken van een artikel, contactpersoon of een
  component van derden die extra velden ondersteunt. U ziet het niet op
  de website.
- Veld class  
  Het class attribuut van het veld als het veld gegenereerd wordt.
  Indien verschillende classes nodig zijn, scheid ze dan door spaties.
- Bewerk class  
  De class attributen van het veld in het bewerkformulier. Als
  verschillende classes nodig zijn scheid ze dan door spaties.
- Bewerkbaar in  
  Op welk deel van de site moet het veld getoond worden. In het
  Beheergedeelte, op de website of beide?
- Label  
  Toon of verberg het label als het veld gegenereerd wordt.
- Automatische weergave  
  Joomlaǃ biedt inhoud-'events' die uitgevoerd worden tijdens het
  aanmaak-proces. Dit is de plek om aan te geven hoe extra velden in de
  inhoud moeten worden opgenomen. U kunt kiezen voor 'Na de titel',
  'Voor de weergave van inhoud', 'Na weergave van inhoud' of 'Niet
  automatisch weergeven'.
- Uitgeschakeld  
  Moet het veld uitgeschakeld zijn in het bewerkformulier.
- Alleen lezen  
  Moet het veld alleen-lezen zijn in het bewerkformulier.

<a href="https://docs.joomla.org/J3.x:Adding_custom_fields"
id="content-button" class="button expand success">Vorig: Inleiding</a>
<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field"
id="content-button" class="button expand">Volgende: Kalender veld</a>
