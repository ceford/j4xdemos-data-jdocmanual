<!-- Filename: J3.x:Adding_custom_fields/List_Field / Display title: Agregar campos personalizados/Campo de Lista -->

## Campo de lista

**Artículos en esta serie**

1.  [Introducción](https://docs.joomla.org/J3.x:Adding_custom_fields "Special:MyLanguage/J3.x:Adding custom fields")
2.  [Parámetros para todos los campos
    personalizados](https://docs.joomla.org/J3.x:Adding_custom_fields/Parameters_for_all_Custom_Fields "Special:MyLanguage/J3.x:Adding custom fields/Parameters for all Custom Fields")
3.  [Campo de
    calendario](https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field "Special:MyLanguage/J3.x:Adding custom fields/Calendar Field")
4.  [Campo de chequeo
    (checkbox)](https://docs.joomla.org/J3.x:Adding_custom_fields/Checkboxes_Field "Special:MyLanguage/J3.x:Adding custom fields/Checkboxes Field")
5.  [Campo de
    color](https://docs.joomla.org/J3.x:Adding_custom_fields/Color_Field "Special:MyLanguage/J3.x:Adding custom fields/Color Field")
6.  [Campo
    editor](https://docs.joomla.org/J3.x:Adding_custom_fields/Editor_Field "Special:MyLanguage/J3.x:Adding custom fields/Editor Field")
7.  [Campo de
    galería](https://docs.joomla.org/J3.x:Adding_custom_fields/Integer_Field "Special:MyLanguage/J3.x:Adding custom fields/Integer Field")
8.  [Campo de lista de
    imágenes](https://docs.joomla.org/J3.x:Adding_custom_fields/List_Field "Special:MyLanguage/J3.x:Adding custom fields/List Field")
9.  [Campo de
    media](https://docs.joomla.org/J3.x:Adding_custom_fields/ListOfImages_Field "Special:MyLanguage/J3.x:Adding custom fields/ListOfImages Field")
10. [Campo
    radio](https://docs.joomla.org/J3.x:Adding_custom_fields/Media_Field "Special:MyLanguage/J3.x:Adding custom fields/Media Field")
11. [Campo
    Sql](https://docs.joomla.org/J3.x:Adding_custom_fields/Radio_Field "Special:MyLanguage/J3.x:Adding custom fields/Radio Field")
12. [Campo
    repetible](https://docs.joomla.org/J3.x:Adding_custom_fields/Repeatable_Field "Special:MyLanguage/J3.x:Adding custom fields/Repeatable Field")
13. [Campo de
    texto](https://docs.joomla.org/J3.x:Adding_custom_fieldshttps://docs.joomla.org/J3.x:Adding%20custom%20fields/Sql%20Field)
14. [Campo de área de texto
    (textarea)](https://docs.joomla.org/J3.x:Adding_custom_fields/Text_Field "Special:MyLanguage/J3.x:Adding custom fields/Text Field")
15. [Campo de
    url](https://docs.joomla.org/J3.x:Adding_custom_fields/Textarea_Field "Special:MyLanguage/J3.x:Adding custom fields/Textarea Field")
16. [Campo de
    usuario](https://docs.joomla.org/J3.x:Adding_custom_fields/Url_Field "Special:MyLanguage/J3.x:Adding custom fields/Url Field")
17. [Campo de grupo de
    usuario](https://docs.joomla.org/J3.x:Adding_custom_fields/User_Field "Special:MyLanguage/J3.x:Adding custom fields/User Field")
18. [¿Cómo puedo agrupar campos
    personalizados?](https://docs.joomla.org/J3.x:Adding_custom_fields/Usergroup_Field "Special:MyLanguage/J3.x:Adding custom fields/Usergroup Field")
19. [¿Qué componentes soportan campos
    personalizados?](https://docs.joomla.org/J3.x:Adding_custom_fields/How%CC%9E_can_you_group_custom_fields "Special:MyLanguage/J3.x:Adding custom fields/How̞ can you group custom fields")
20. [Ejemplo](https://docs.joomla.org/J3.x:Adding_custom_fields/What_components_are_supporting_custom_fields "Special:MyLanguage/J3.x:Adding custom fields/What components are supporting custom fields")
21. [Implementación en tu
    componente](https://docs.joomla.org/J3.x:Adding_custom_fields/Implement_into_your_component "Special:MyLanguage/J3.x:Adding custom fields/Implement into your component")
22. [Utilizar campos personalizados en tus
    sustituciones](https://docs.joomla.org/J3.x:Adding_custom_fields/Overrides "Special:MyLanguage/J3.x:Adding custom fields/Overrides")

### Lista

El tipo de campo de formulario tipo lista proporciona una lista
desplegable o una lista de entradas definidas personalizadamente. Si el
campo tiene un valor guardado, se selecciona la primera vez que se carga
la página. De lo contrario, se selecciona el valor predeterminado (si
existe).

#### Opciones

Las opciones especiales dentro de este campo son:

- Múltiple  
  Permite que se seleccionen múltiples valores - si está activado.
- Valores de lista  
  Los valores de la lista.

#### Información relacionada

Ver [Campo de formulario - Tipo
Lista](https://docs.joomla.org/List_form_field_type/es "Special:MyLanguage/List form field type/es")

#### Capturas de pantalla

##### Crear el campo

Supongamos que creas un campo con las opciones mostradas en la siguiente
imagen. <img
src="https://docs.joomla.org/images/thumb/1/1d/List_field_create-en.png/800px-List_field_create-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/1d/List_field_create-en.png/1200px-List_field_create-en.png 1.5x, https://docs.joomla.org/images/1/1d/List_field_create-en.png 2x"
data-file-width="1291" data-file-height="663" width="800" height="411"
alt="List field create-en.png" />

##### Usar el campo en el administrador

Cuando creas un artículo o contacto en el administrador, puedes ver el
campo como en la siguiente imagen:

<img
src="https://docs.joomla.org/images/thumb/7/7a/List-en.png/800px-List-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/7a/List-en.png/1200px-List-en.png 1.5x, https://docs.joomla.org/images/7/7a/List-en.png 2x"
data-file-width="1291" data-file-height="663" width="800" height="411"
alt="List-en.png" />

##### Usar el campo en el sitio web

En el sitio web, puede ver el campo como se ve en la siguiente imagen.

<img
src="https://docs.joomla.org/images/thumb/a/a2/List_field_frontend-en.png/800px-List_field_frontend-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/a2/List_field_frontend-en.png/1200px-List_field_frontend-en.png 1.5x, https://docs.joomla.org/images/a/a2/List_field_frontend-en.png 2x"
data-file-width="1291" data-file-height="663" width="800" height="411"
alt="List field frontend-en.png" />

La opción *Visualización automática* es responsable de la posición del
campo y su plantilla es responsable del diseño del campo.  
Los campos solo se muestran en el sitio web si los ha llenado con datos
en el artículo. Si no es un campo obligatorio, ¿puedes olvidarlo?

<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Integer_Field"
id="content-button" class="button expand success">Anterior: Campo de
Entero</a> <a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/List_of_Images_Field"
id="content-button" class="button expand">Siguiente: Campo Lista de
Imágenes</a>
