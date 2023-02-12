<!-- Filename: J3.x:Adding_custom_fields/Checkboxes_Field / Display title: Agregar campos personalizados - Campo de checkbox -->

<span id="section-portal-heading"></span>

## Campo de chequeo (checkbox)

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

## El campo de checkbox

Proporciona una casilla de verificación que puede estar seleccionada o
no.

#### Opciones

Las opciones especiales en este campo son:

- Valores del checkbox  
  Los valores de los checkbox.

#### Información relacionada

Ver [Campo de formulario - Tipo
checkbox](https://docs.joomla.org/Checkbox_form_field_type "Special:MyLanguage/Checkbox form field type")

#### Capturas de pantalla

##### Crear el campo

Supongamos que creas un campo con las opciones mostradas en la siguiente
imagen.

<img
src="https://docs.joomla.org/images/thumb/f/fd/Checkbox_field_create-en.png/800px-Checkbox_field_create-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/fd/Checkbox_field_create-en.png/1200px-Checkbox_field_create-en.png 1.5x, https://docs.joomla.org/images/f/fd/Checkbox_field_create-en.png 2x"
data-file-width="1291" data-file-height="663" width="800" height="411"
alt="Checkbox field create-en.png" />

##### Usar el campo en el administrador

Cuando creas un artículo o contacto en el administrador, puedes ver el
campo como en la siguiente imagen:

<img
src="https://docs.joomla.org/images/thumb/5/5a/Checkbox-en.png/800px-Checkbox-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/5a/Checkbox-en.png/1200px-Checkbox-en.png 1.5x, https://docs.joomla.org/images/5/5a/Checkbox-en.png 2x"
data-file-width="1291" data-file-height="663" width="800" height="411"
alt="Checkbox-en.png" />

##### Usar el campo en el sitio web

En el sitio web (frontend), puedes ver el campo tal y como se muestra en
la siguiente imagen, si está seleccionada sola la opción 2. La opción
"Visualización automática" es responsable de la posición del campo y tu
plantilla es responsable por el diseño del campo.  
Los campos solo se muestran en el sitio web si tienen algún valor en
dicho artículo.

<img
src="https://docs.joomla.org/images/thumb/b/b3/Checkbox_field_frontend-en.png/800px-Checkbox_field_frontend-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/b/b3/Checkbox_field_frontend-en.png/1200px-Checkbox_field_frontend-en.png 1.5x, https://docs.joomla.org/images/b/b3/Checkbox_field_frontend-en.png 2x"
data-file-width="1291" data-file-height="663" width="800" height="411"
alt="Checkbox field frontend-en.png" />

<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field"
id="content-button" class="button expand success">Anterior: Campo de
calendario</a>
<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/Color_Field"
id="content-button" class="button expand">Siguiente: Campo de color</a>
