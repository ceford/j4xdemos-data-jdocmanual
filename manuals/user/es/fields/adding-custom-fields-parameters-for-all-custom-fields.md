<!-- Filename: J3.x:Adding_custom_fields/Parameters_for_all_Custom_Fields / Display title: Agregar campos personalizados/parámetros para todos los Campos Personalizados -->

<span id="section-portal-heading"></span>

## Parámetros para todos los Campos Personalizados

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

## Parámetros para todos los Campos Personalizados

La lista de Campos Personalizados estará vacía inicialmente. Haga clic
en '*Nuevo* para agregar un campo.  
En la pestaña **General** rellene los datos obligatorios:

- Título  
  El título del campo. El título se mostrará en la página de
  administración del campo donde puede abrir el campo para editar
  haciendo clic en el título. El título no se muestra cuando se crea un
  artículo o un contacto ni en el frontend.
- Nombre  
  El nombre se utilizará para identificar el campo. Deje esto en blanco
  y Joomla completará el valor predeterminado con el título.
- Tipo  
  Si crea un campo, puede elegir uno de los 16 tipos de campos. Al
  guardar el campo, el tipo es permanente. No se puede cambiar más
  adelante.

Para cada campo, puede usar estos parámetros:

- Etiqueta  
  Utilice un texto descriptivo para la etiqueta del campo. Este texto no
  es traducible. Si no introduce ningún texto para una etiqueta, el
  texto del título también se usará como texto de la etiqueta.
- Descripción  
  La descripción del campo. Un texto que se mostrará cuando el usuario
  mueve el mouse sobre el cuadro de texto mientras lo usa en el backend
  creando un artículo, un contacto o un componente de terceros que
  admite campos personalizados. Este texto no es traducible. No verá
  esta descripción en el frontend.
- Obligatorio  
  ¿Es éste un campo personalizado obligatorio? En este caso, el campo
  debe rellenarse antes de enviar un artículo, un contacto o un
  componente de terceros que admita campos personalizados. Puede elegir
  las opciones *Sí* o *No*.
- Predeterminado  
  Aquí puede establecer un valor predeterminado para el campo
  personalizado. Este texto no es traducible. Tenga en cuenta que en
  algunos campos de lista debe ingresar el valor como predeterminado y
  en otros el índice.
- Estado  
  Puede establecer un estado de publicación. ¿El campo será "Publicado",
  "Despublicado", "Archivado" o en "Papelera"?
  - Publicado: El campo es visible al editar un artículo o un contacto.
    Y es visible en el Frontend.
  - Despublicado: El campo no será visible para los usuarios mientras
    editan un artículo o un contacto.
  - Archivado: El campo ya no mostrará en la edición un artículo o un
    contacto. Puede abrirlo en el administrador de campos cuando
    establezca el filtro en archivado.
  - Papelera: El campo se elimina pero aún está en la base de datos. Se
    puede eliminar permanentemente de la base de datos con la función
    Vaciar Papelera en el Administrador de Campos.
- Grupo de campos  
  Puede asignar un campo personalizado a uno o más grupos de campos.
- Categoría  
  Puede asignar un campo personalizado a una o más categorías de campos.
  Tenga en cuenta que el valor predeterminado 'Todos' no incluye
  artículos 'Sin Categoría'.
- Acceso  
  Vea [Niveles de
  Acceso](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/es "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/es")
  para este elemento.
- Idioma  
  Seleccione el idioma para este campo personalizado. Si no está
  utilizando la [configuración de sitio
  multiidioma](https://docs.joomla.org/J3.x:Setup_a_Multilingual_Site/es "J3.x:Setup a Multilingual Site/es")
  de Joomla, mantenga el valor predeterminado de *Todos*.
- Nota  
  Un campo opcional para hacer sus notas personales para el campo.

En el registro **Opciones** puede usar las opciones:

- Marcador de posición  
  Un texto que aparecerá dentro del campo personalizado como una
  sugerencia para la entrada. El marcador de posición está activo en el
  Backend al crear un artículo, un contacto o un componente de terceros
  que admite campos personalizados. Usted no lo verá en el Frontend.
- Clase del campo  
  La clase del campo cuando el campo es renderizado. Si se necesitan
  diferentes clases, sepárelas con espacios.
- Editar Clase  
  Los atributos de clase del campo en el formulario de edición. Si se
  necesitan diferentes clases, sepárelas con espacios.
- Editable en  
  En qué parte del sitio debe mostrarse el campo. En el Backend, en el
  Frontend o ambos.
- Etiqueta  
  Mostrar u ocultar la etiqueta cuando el campo se renderiza.
- Visualización automática  
  Joomlaǃ ofrece algunos eventos de contenido que se activan durante el
  proceso de creación de contenido. Este es el lugar para definir cómo
  los campos personalizados deben integrarse en el contenido. Puede
  elegir 'Después del título', 'Antes de mostrar contenido', 'Después de
  mostrar contenido' o 'No mostrar automáticamente'.
- Deshabilitado  
  En caso de que el campo esté deshabilitado en el formulario de
  edición.
- Sólo lectura  
  En caso de que el campo sea de sólo lectura en el formulario de
  edición.

<a href="https://docs.joomla.org/J3.x:Adding_custom_fields"
id="content-button" class="button expand success">Anterior:
Introducción</a> <a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field"
id="content-button" class="button expand">Siguiente: Campo de
Calendario</a>
