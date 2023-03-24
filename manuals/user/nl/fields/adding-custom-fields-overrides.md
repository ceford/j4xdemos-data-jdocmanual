<!-- Filename: J3.x:Adding_custom_fields/Overrides / Display title: Toevoegen extra velden - Overrides -->

## Hoe extra velden gebruiken in uw overrides

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

## Hoe extra velden gebruiken in uw overrides

### Inleiding

De echte kracht van extra velden is dat u het kunt gebruiken in uw eigen
overrides. Hier is een voorbeeld hoe u dat kunt doen.

### Extra velden in uw overrides krijgen

In de basis heeft u alles over extra velden in relatie tot het huidige
item toegankelijk via een nieuw property in uw `$item` variabele genaamd
`jcfields`. Het `$item->jcfields` property is een array dat de volgende
gegevens per veld bevat, waarbij een veld eruit ziet als in dit
voorbeeld:

```php
    Array
    (
        [4] => stdClass Object
            (
                [id] => 4
                [title] => article-editor
                [name] => article-editor
                [checked_out] => 0
                [checked_out_time] => 0000-00-00 00:00:00
                [note] =>
                [state] => 1
                [access] => 1
                [created_time] => 2017-04-07 12:08:59
                [created_user_id] => 856
                [ordering] => 0
                [language] => *
                [fieldparams] => Joomla\Registry\Registry Object
                    (
                        [data:protected] => stdClass Object
                            (
                                [buttons] =>
                                [width] =>
                                [height] =>
                                [filter] =>
                            )

                        [initialized:protected] => 1
                        [separator] => .
                    )

                [params] => Joomla\Registry\Registry Object
                    (
                        [data:protected] => stdClass Object
                            (
                                [hint] =>
                                [render_class] =>
                                [class] =>
                                [showlabel] => 1
                                [disabled] => 0
                                [readonly] => 0
                                [show_on] =>
                                [display] => 2
                            )

                        [initialized:protected] => 1
                        [separator] => .
                    )

                [type] => editor
                [default_value] =>
                [context] => com_content.article
                [group_id] => 0
                [label] => article-editor
                [description] =>
                [required] => 0
                [language_title] =>
                [language_image] =>
                [editor] =>
                [access_level] => Public
                [author_name] => Super User
                [group_title] =>
                [group_access] =>
                [group_state] =>
                [value] => Bar
                [rawvalue] => Bar
            )

    )
```

### Render het veld met behulp van FieldsHelper

Om het veld te genereren kunt u `FieldsHelper::render()` gebruiken door
de noodzakelijke waarden door te geven.

```php
    /**
     * Renders the layout file and data on the context and does a fall back to
     * Fields afterwards.
     *
     * @param   string  $context      The context of the content passed to the helper
     * @param   string  $layoutFile   layoutFile
     * @param   array   $displayData  displayData
     *
     * @return  NULL|string
     *
     * @since  3.7.0
     */
    public static function render($context, $layoutFile, $displayData)
```

#### Voorbeeldcode voor de override met behulp van FieldsHelper

```php
// Load the FieldsHelper
<?php JLoader::register('FieldsHelper', JPATH_ADMINISTRATOR . '/components/com_fields/helpers/fields.php'); ?>

<?php foreach ($this->item->jcfields as $field) : ?>
	// Render the field using the fields render method
	<?php echo FieldsHelper::render($field->context, 'field.render', array('field' => $field)); ?>
<?php endforeach ?>
```

#### Voorbeeldcode voor een raw override

```php
<?php foreach ($this->item->jcfields as $field) : ?>
	// Render the field using the fields render method
	<?php echo $field->label . ':' . $field->value; ?>
<?php endforeach ?>
```

### jcfields_bevat_niet_de_velden_die_ik_nodig_heb"\>`$item->jcfields` bevat niet de velden die ik nodig heb

Het `jcfields` property wordt gegenereerd met behulp van het plugin
event `onContentPrepare` door de context van de velden door te geven. De
velden plugin leest dan de velden uit de database en voegt de waarden
toe aan het jcfields property. Let er alstublieft op dat de component
die u gebruikt ook het `onContentPrepare` event implementeert met de
context die u gebruikt voor de velden.

Als u core componenten gebruikt dan zou dit out-of-the-box moeten
werken.

### Individuele velden laden

Begin, om individuele velden aan uw inhoud toe te voegen, met het kiezen
van specifieke namen voor uw extra velden, door het gebruik van het
**Naam** veld, wat wordt gebruikt om direct te verwijzen naar uw veld in
de override code. Selecteer, op het `Opties` tabblad, **Nee** in het
`Automatisch tonen` veld om te voorkomen dat het automatisch getoond
wordt op een van de posities.

Plaats daarna, om direct toegang te hebben via de naam naar het extra
veld in de override code, de code aan het begin van uw bestand. Dit moet
u doen in ieder override PHP bestand waar u extra velden wilt plaatsen.

```php
<?php foreach($item->jcfields as $jcfield)
     {
          $item->jcFields[$jcfield->name] = $jcfield;
     }
?>
```

En als laatste moet u de plaats code zetten op de plek waar u het
veldlabel of de waarde getoond wil hebben.

Om het **label** van het veld toe te voegen in uw override, voegt u
onderstaande code toe door het vervangen van `name-of-field` door de
naam van het veld.

```php
<?php echo $item->jcFields['name-of-field']->label; ?>
```

Om de **waarde** van het veld toe te voegen in uw override, voegt u
onderstaande code toe door het vervangen van `name-of-field` door de
naam van het veld. Let op dat in de 3.x serie de **value** in de
praktijk de **rawvalue** is
<a href="https://github.com/joomla/joomla-cms/issues/20216"
class="external free" target="_blank"
rel="nofollow noreferrer noopener">https://github.com/joomla/joomla-cms/issues/20216</a>

```php
<?php echo $item->jcFields['name-of-field']->rawvalue; ?>
```

U kunt deze code toevoegen aan ieder deel van uw override. Bijvoorbeeld:
De inhoud van een div, de src in een `img` tag, binnen een CSS class
attribuut, etc.

<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Implement_into_your_component"
id="content-button" class="button expand success">Vorig: In uw component
implementeren</a>
