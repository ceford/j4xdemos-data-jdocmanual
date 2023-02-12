<!-- Filename: J3.x:Adding_custom_fields/Overrides / Display title: Añadir campos personalizados/Sobrescrituras -->

<span id="section-portal-heading"></span>

## Cómo usar campos personalizados en tus sobrescrituras (overrides)

**Articles in this Series**

1.  [Introduction](https://docs.joomla.org/J3.x:Adding_custom_fields "Special:MyLanguage/J3.x:Adding custom fields")
2.  [Parameters for all Custom
    Fields](https://docs.joomla.org/J3.x:Adding_custom_fields/Parameters_for_all_Custom_Fields "Special:MyLanguage/J3.x:Adding custom fields/Parameters for all Custom Fields")
3.  [Calendar
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field "Special:MyLanguage/J3.x:Adding custom fields/Calendar Field")
4.  [Checkboxes
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Checkboxes_Field "Special:MyLanguage/J3.x:Adding custom fields/Checkboxes Field")
5.  [Color
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Color_Field "Special:MyLanguage/J3.x:Adding custom fields/Color Field")
6.  [Editor
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Editor_Field "Special:MyLanguage/J3.x:Adding custom fields/Editor Field")
7.  [Integer
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Integer_Field "Special:MyLanguage/J3.x:Adding custom fields/Integer Field")
8.  [List
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/List_Field "Special:MyLanguage/J3.x:Adding custom fields/List Field")
9.  [List of Images
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/ListOfImages_Field "Special:MyLanguage/J3.x:Adding custom fields/ListOfImages Field")
10. [Media
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Media_Field "Special:MyLanguage/J3.x:Adding custom fields/Media Field")
11. [Radio
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Radio_Field "Special:MyLanguage/J3.x:Adding custom fields/Radio Field")
12. [Repeatable
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Repeatable_Field "Special:MyLanguage/J3.x:Adding custom fields/Repeatable Field")
13. [Sql
    Field](https://docs.joomla.org/J3.x:Adding_custom_fieldshttps://docs.joomla.org/J3.x:Adding%20custom%20fields/Sql%20Field)
14. [Text
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Text_Field "Special:MyLanguage/J3.x:Adding custom fields/Text Field")
15. [Textarea
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Textarea_Field "Special:MyLanguage/J3.x:Adding custom fields/Textarea Field")
16. [Url
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Url_Field "Special:MyLanguage/J3.x:Adding custom fields/Url Field")
17. [User
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/User_Field "Special:MyLanguage/J3.x:Adding custom fields/User Field")
18. [Usergroup
    Field](https://docs.joomla.org/J3.x:Adding_custom_fields/Usergroup_Field "Special:MyLanguage/J3.x:Adding custom fields/Usergroup Field")
19. [How can you group custom
    fields](https://docs.joomla.org/J3.x:Adding_custom_fields/How%CC%9E_can_you_group_custom_fields "Special:MyLanguage/J3.x:Adding custom fields/How̞ can you group custom fields")
20. [What components are supporting custom
    fields](https://docs.joomla.org/J3.x:Adding_custom_fields/What_components_are_supporting_custom_fields "Special:MyLanguage/J3.x:Adding custom fields/What components are supporting custom fields")
21. [Implementation into your
    component](https://docs.joomla.org/J3.x:Adding_custom_fields/Implement_into_your_component "Special:MyLanguage/J3.x:Adding custom fields/Implement into your component")
22. [Use custom fields in your
    overrides](https://docs.joomla.org/J3.x:Adding_custom_fields/Overrides "Special:MyLanguage/J3.x:Adding custom fields/Overrides")

## Cómo usar campos personalizados en tus sobrescrituras

### Introducción

El verdadero poder de los campos personalizados es que puedes usarlos en
tus sobrescrituras. A continuación un ejemplo de cómo puede hacerse.

## Cómo usar campos personalizados en tus sobrescrituras

Básicamente tienes todos los campos personalizados correspondientes al
elemento actual accesibles vía una nueva propiedad en tu `$item` en una
variable denominada `jcfields`. La propiedad `$item->jcfields` es un
array que contiene los datos de cada campo, donde un campo puede ser
como el siguiente ejemplo:

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

### Mostrando un campo usando FieldsHelper

Para mostrar un campo puedes usar `FieldsHelper::render()` pasando los
valores necesarios.

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

#### Ejemplo de código para la sobrescritura usando FieldsHelper

    // Load the FieldsHelper


    item->jcfields as $field) : ?>
        // Render the field using the fields render method
        context, 'field.render', array('field' => $field)); ?>

#### Ejemplo de código para una sobrescritura en bruto

    item->jcfields as $field) : ?>
        // Render the field using the fields render method
        label . ':' . $field->value; ?>

### jcfields_no_contiene_el_campo_que_necesito"\>`$item->jcfields` no contiene el campo que necesito

La propiedad `jcfields` es generada usando el evento `onContentPrepare`
y pasándole el contexto de los campos. El plugin de campos entonces lee
los campos de la base de datos y añade los valores a la propiedad
`jcfields`. Asegúrate por favor que el componente que usas implementa el
evento `onContentPrepare` con el contexto que usas para los campos.

Si usas los componentes del núcleo esto debe funcionar desde el primer
momento.

### Cargando campos individuales

Para añadir campos individuales a tu componente, comienza eligiendo los
nombres específicos para ellos, empleando el campo "Nombre", el cual
será usado para referenciar tu campo directamente en tu código de
sobrescritura. En la pestaña `Opciones`, selecciona "No" en campo de
`Mostrar automáticamente` para prevenir que se muestre automáticamente
en sus posiciones estándar.

A continuación, para habilitar el acceso directo por nombre a los campos
personalizados en una sobrescritura, sitúa el siguiente código al
principio de tu fichero. Debes hacer esto en cada archivo PHP de
sobrescritura en el que quieras ubicar campos personalizados en él.

    jcfields as $jcfield)
         {
              $item->jcFields[$jcfield->name] = $jcfield;
         }
    ?>

Y por último, debes añadir el código al lugar en el que desees mostrar
la etiqueta o el valor del campo.

Para añadir la **etiqueta** del campo a tu sobrescritura, inserta el
siguiente código, reemplazando `name-of-field` por el nombre de tu
campo.

    jcFields['name-of-field']->label; ?>

Para añadir el **valor** del campo a tu sobrescritura, inserta el código
siguiente, reemplazando `name-of-field` por el nombre del campo.
Cuidado: en las versiones 3.x el **valor** es de hecho el **rawvalue**
<a href="https://github.com/joomla/joomla-cms/issues/20216"
class="external free" target="_blank"
rel="nofollow noreferrer noopener">https://github.com/joomla/joomla-cms/issues/20216</a>

    jcFields['name-of-field']->rawvalue; ?>

Puedes añadir este código a cualquier parte de tu sobrescritura.
Ejemplos: En el contenido de un `div`, en el src de una etiqueta `img`,
como un atributo clase de CSS, etc.

<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Implement_into_your_component"
id="content-button" class="button expand success">Prev: Implementando en
tu código</a>
