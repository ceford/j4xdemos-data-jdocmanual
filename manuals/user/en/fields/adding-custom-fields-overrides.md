<!-- Filename: J3.x:Adding_custom_fields/Overrides / Display title: Adding custom fields/Overrides -->

## How to use custom fields in your overrides

### Introduction

The real power of custom fields is that you can use it in your own
overrides. Here is a example of how you can do that.

### Getting custom fields in your override

Basically you have all the custom fields corresponding to the current
item accessible via a new property in your `$item` variable called
`jcfields`. The `$item->jcfields` property is an array that holds the
following data per field, where one field looks like this example:

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

### Render the field using the FieldsHelper

To render the field you can use `FieldsHelper::render()` by passing the
needed values.

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

#### Example code for the override using the FieldsHelper

```php
// Load the FieldsHelper
<?php JLoader::register('FieldsHelper', JPATH_ADMINISTRATOR . '/components/com_fields/helpers/fields.php'); ?>

<?php foreach ($this->item->jcfields as $field) : ?>
	// Render the field using the fields render method
	<?php echo FieldsHelper::render($field->context, 'field.render', array('field' => $field)); ?>
<?php endforeach ?>
```

#### Example code for a raw override

```php
<?php foreach ($this->item->jcfields as $field) : ?>
	// Render the field using the fields render method
	<?php echo $field->label . ':' . $field->value; ?>
<?php endforeach ?>
```

### `$item->jcfields` does not contain the fields I need

The `jcfields` property is generated using the plugin event
`onContentPrepare` by passing the context of the fields. The fields
plugin then reads the fields from the database and adds the values to
the jcfields property. So please make sure that the component you use
also implements the `onContentPrepare` event with the context you use
for the fields.

If you use the core components this should work out of the box.

### Loading individual fields

In order to add individual fields to your content, start by choosing
specific names for your custom fields, using the **Name** field, which
will be used to reference your field directly in the override code. In
the `Options` tab, select **No** in the `Automatic Display` field to
prevent it from being displayed automatically in any of the standard
positions.

Then, to enable direct access by name to custom fields in an override,
place the code below at the beginning of your file. You should do this
to every override PHP file that you want to place individual custom
fields on.

```php
<?php foreach($item->jcfields as $jcfield)
     {
          $item->jcFields[$jcfield->name] = $jcfield;
     }
?>
```

And lastly, you should add the field placement code at the spot you want
the field label or value to be shown.

To add the **label** of the field to your override, insert the code
below, replacing `name-of-field` with the name of the field.

```php
<?php echo $item->jcFields['name-of-field']->label; ?>
```

To add the **value** of the field to your override, insert the code
below, replacing `name-of-field` with the name of the field. Beware: in
the 3.x series the **value** is in fact the **rawvalue**
<a href="https://github.com/joomla/joomla-cms/issues/20216"
class="external free" target="_blank"
rel="nofollow noreferrer noopener">https://github.com/joomla/joomla-cms/issues/20216</a>

```php
<?php echo $item->jcFields['name-of-field']->rawvalue; ?>
```

You can add this code to any part of your override. Examples: The
content of a div, the src in an `img` tag, within a CSS class attribute,
etc.
