<!-- Filename: J3.x:Adding_custom_fields/Media_Field / Display title: Toevoegen extra velden/Media veld -->

## Media veld

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

### Media

Biedt modale toegang tot mediabeheer voor het invoegen van afbeeldingen
met upload-rechten voor gebruikers met de juiste machtigingen.

#### Opties

Speciale opties binnen dit veld zijn:

- Map  
  De standaard afbeeldingsmap voor dit veld. .Het media veld verwijst
  standaard naar de /images map, zodat alles ingegeven in het 'Map' veld
  binnen de /images map verwacht wordt. Als u dus wilt dat de standaard
  map https://docs.joomla.org/images/mijnafbeeldingen is, geef dan
  'mijnafbeeldingen' op in het 'Map' veld.
- Voorbeeld  
  Toont of verbergt de voorvertoning van de geselecteerde afbeelding.
- Class van de afbeelding  
  De class die toegevoegd wordt aan de afbeelding.

#### Verwante Informatie

Zie [Media formulier
veldtype](https://docs.joomla.org/Media_form_field_type "Special:MyLanguage/Media form field type")

#### Schermafbeeldingen

##### Het veld aanmaken

Laten we zeggen dat u een veld maakt met de opties weergegeven in de
volgende afbeelding.

<img
src="https://docs.joomla.org/images/thumb/4/4f/Media_field_create-nl.png/800px-Media_field_create-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/4/4f/Media_field_create-nl.png 1.5x"
data-file-width="1156" data-file-height="947" width="800" height="655"
alt="Media field create-nl.png" />

##### Het veld in het beheergedeelte gebruiken

In het beheergedeelte ziet u het veld bij het aanmaken van een artikel
of contactpersoon als in de volgende afbeeldingː

<img
src="https://docs.joomla.org/images/thumb/5/5d/Media-nl.png/800px-Media-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/5/5d/Media-nl.png 1.5x"
data-file-width="1154" data-file-height="942" width="800" height="653"
alt="Media-nl.png" />

En als u er op klikt, opent er een modaal scherm en u kunt hier een
afbeelding selecteren. <img
src="https://docs.joomla.org/images/thumb/9/97/Media_2-nl.png/800px-Media_2-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/9/97/Media_2-nl.png 1.5x"
data-file-width="943" data-file-height="521" width="800" height="442"
alt="Media 2-nl.png" />

##### Het veld op de website gebruiken

Op de website kunt u het veld zien zoals op de volgende afbeelding. De
optie *Automatisch tonen* is verantwoordelijk voor de positie van het
veld en uw template is verantwoordelijk voor het ontwerp van het veld.  
Velden worden alleen getoond op de website als er in het artikel
gegevens in staan. Als het geen verplicht veld is kunt u dat vergetenǃ

<img
src="https://docs.joomla.org/images/thumb/c/c1/Media_field_frontend-nl.png/800px-Media_field_frontend-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/c/c1/Media_field_frontend-nl.png 1.5x"
data-file-width="1094" data-file-height="807" width="800" height="590"
alt="Media field frontend-nl.png" />

<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/List_of_Images_Field"
id="content-button" class="button expand success">Vorig: Lijst met
afbeeldingen veld</a>
<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/Radio_Field"
id="content-button" class="button expand">Volgende: Keuzerondje veld</a>
