<!-- Filename: J3.x:Adding_custom_fields/Integer_Field / Display title: Toevoegen extra velden/Integer veld -->

## Integer veld

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

### Integer

Biedt een drop-down lijst met integers (gehele getallen) tussen een
minimum (eerste) en maximum (laatste) waarde.

#### Opties

Speciale opties bij dit veld zijn:

- Meerdere  
  Sta toe dat meerdere waarden geselecteerd worden.
- Eerste  
  Deze waarde is de laagste uit de lijst.
- Laatste  
  Deze waarde is de hoogste uit de lijst.
- **step** (verplicht) iedere optie zal de voorafgaande optie verhoogd
  met dit getal zijn, te beginnen met de **eerste** waarde totdat de
  **laatste** waarde is bereikt.

#### Verwante Informatie

Zie [Integer formulier
veldtype](https://docs.joomla.org/Integer_form_field_type "Special:MyLanguage/Integer form field type")

#### Schermafbeeldingen

##### Het veld aanmaken

Laten we zeggen dat u een veld maakt met de opties weergegeven in de
volgende afbeelding.

<img
src="https://docs.joomla.org/images/thumb/6/6d/Integer_field_create-nl.png/800px-Integer_field_create-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/6/6d/Integer_field_create-nl.png 1.5x"
data-file-width="1157" data-file-height="943" width="800" height="652"
alt="Integer field create-nl.png" />

##### Het veld in het beheergedeelte gebruiken

In het beheergedeelte ziet u het veld bij het aanmaken van een artikel
of contactpersoon als in de volgende afbeeldingː

<img
src="https://docs.joomla.org/images/thumb/6/6b/Integer-nl.png/800px-Integer-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/6/6b/Integer-nl.png 1.5x"
data-file-width="1157" data-file-height="947" width="800" height="655"
alt="Integer-nl.png" />

##### Het veld op de website gebruiken

Op de website ziet u het veld zoals u het ziet op de volgende
afbeelding. De optie *Automatische weergave* is verantwoordelijk voor de
positie van het veld en uw template is verantwoordelijk voor het ontwerp
van het veld.

<img
src="https://docs.joomla.org/images/thumb/9/9e/Integer_field_frontend-nl.png/800px-Integer_field_frontend-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/9/9e/Integer_field_frontend-nl.png 1.5x"
data-file-width="1012" data-file-height="654" width="800" height="517"
alt="Integer field frontend-nl.png" />

<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/Editor_Field"
id="content-button" class="button expand success">Vorig: Tekstverwerker
veld</a>
<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/List_Field"
id="content-button" class="button expand">Volgende: Lijst veld</a>
