<!-- Filename: J3.x:Adding_custom_fields/Url_Field / Display title: Toevoegen extra velden/URL veld -->

## URL veld

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

### URL

Biedt een URL-invoerveld.

#### Opties

Speciale opties bij dit veld zijn:

- Schema's  
  De toegestane schema's zijn HTTP, HTTPS, FTP, FTPS, MAILTO, URL en
  FILE. Dit extra veld is in wezen een tekst veld met het type URL in
  het beheergedeelte bij het aanmaken van een artikel, contactpersoon of
  component van derden die extra velden ondersteunt. Het is alleen
  mogelijk een volledige URL in te voeren - dat is er een met schema en
  domeinnaam zoals `http://voorbeeld.com`. De URL wordt vertaald naar
  <a href="https://en.wikipedia.org/wiki/Punycode" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">punycode</a> voor
  het opslaan. Dit zorgt ervoor dat de URL werkt zoals bedoelt, ongeacht
  de omgeving.
- Relatief  
  Gebruik deze optie om te bepalen of al dan niet relatieve URL's
  toegestaan zijn.

#### Verwante Informatie

Zie [URL formulier
veldtype](https://docs.joomla.org/URL_form_field_type "Special:MyLanguage/URL form field type")

#### Schermafbeeldingen

##### Het veld aanmaken

Laten we zeggen dat u een veld maakt met de opties weergegeven in de
volgende afbeelding.

<img
src="https://docs.joomla.org/images/thumb/c/cd/Url_field_create-nl.png/800px-Url_field_create-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/c/cd/Url_field_create-nl.png 1.5x"
data-file-width="1161" data-file-height="947" width="800" height="653"
alt="Url field create-nl.png" />

##### Het veld in het beheergedeelte gebruiken

In het beheergedeelte ziet u het veld bij het aanmaken van een artikel
of contactpersoon als in de volgende afbeeldingː

<img
src="https://docs.joomla.org/images/thumb/e/ed/URL-nl.png/800px-URL-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/e/ed/URL-nl.png 1.5x"
data-file-width="1157" data-file-height="943" width="800" height="652"
alt="URL-nl.png" />

##### Het veld op de website gebruiken

Op de website kunt u het veld zien zoals op de volgende afbeelding. De
optie *Automatisch tonen* is verantwoordelijk voor de positie van het
veld en uw template is verantwoordelijk voor het ontwerp van het veld.  
Velden worden alleen getoond op de website als er in het artikel
gegevens in staan. Als het geen verplicht veld is kunt u dat vergetenǃ

<img
src="https://docs.joomla.org/images/thumb/f/fe/Url_field_frontend-nl.png/800px-Url_field_frontend-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/f/fe/Url_field_frontend-nl.png 1.5x"
data-file-width="1066" data-file-height="648" width="800" height="486"
alt="Url field frontend-nl.png" />

<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Textarea_Field"
id="content-button" class="button expand success">Vorig: Tekstvak
veld</a>
<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/User_Field"
id="content-button" class="button expand">Volgende: Gebruiker veld</a>
