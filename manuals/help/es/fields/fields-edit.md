<!-- Filename: Help4.x:Fields:_Edit / Display title: Campos: Editar -->

## Descripción

This is where you can add and edit Fields in Articles, Contacts, and
Users.

The helpscreen show as example Users.

## Cómo Acceder

**Usuarios **→** Campos**

Para agregar un campo:

- Clic el botón **Nuevo** en la Barra de Herramientas

Para editar un campo:

- Seleccione un **Título** de campo en la lista.

## Captura de pantalla

<img
src="https://docs.joomla.org/images/thumb/d/d0/Help-4x-Fields-Edit-screen-es.png/800px-Help-4x-Fields-Edit-screen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/d0/Help-4x-Fields-Edit-screen-es.png/1200px-Help-4x-Fields-Edit-screen-es.png 1.5x, https://docs.joomla.org/images/thumb/d/d0/Help-4x-Fields-Edit-screen-es.png/1600px-Help-4x-Fields-Edit-screen-es.png 2x"
data-file-width="2720" data-file-height="1700" width="800" height="500"
alt="Help-4x-Fields-Edit-screen-es.png" />

## Campos del formulario

- **Título**. El Título para este campo.

### General

**Panel izquierdo**

Parámetros para todos los Campos Personalizados:

- **Tipo**. Si crea un campo, puede elegir uno de los 16 tipos de
  campos. Al guardar el campo, el tipo es permanente. No se puede
  cambiar más adelante. [Learn
  more.](https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field/en "J3.x:Adding custom fields/Calendar Field/en")
- **Nombre**. El nombre se utilizará para identificar el campo. Deje
  esto en blanco y Joomla completará el valor predeterminado con el
  título.
- **Etiqueta**. Utilice un texto descriptivo para la etiqueta del campo.
  Este texto no es traducible. Si no introduce ningún texto para una
  etiqueta, el texto del título también se usará como texto de la
  etiqueta.
- **Descripción**. La descripción del campo. Un texto que se mostrará
  cuando el usuario mueve el mouse sobre el cuadro de texto mientras lo
  usa en el Backend creando un artículo, un contacto o un componente de
  terceros que admite campos personalizados. Este texto no es
  traducible. No verá esta descripción en el Frontend.
- **Obligatorio**. ¿Es éste un campo personalizado obligatorio? En este
  caso, el campo debe rellenarse antes de enviar un artículo, un
  contacto o un componente de terceros que admita campos personalizados.

**Panel Derecho**

- **Estado**. El estado de publicación de este campo.
  - Publicado: El campo es visible al editar un artículo o un contacto.
    Y es visible en el Frontend.
  - Despublicado: El campo no será visible para los usuarios mientras
    editan un artículo o un contacto.
  - Archivado: El campo ya no mostrará en la edición un artículo o un
    contacto. Puede abrirlo en el administrador de
    [campos](https://docs.joomla.org/Help4.x:Fields/es#selectstatus "Help4.x:Fields/es")
    cuando establezca el filtro en archivado.
  - Papelera: El campo se elimina pero aún está en la base de datos. Se
    puede eliminar permanentemente de la base de datos con la función
    Vaciar Papelera en el Administrador de
    [Campos](https://docs.joomla.org/Help4.x:Fields/es#selectstatus "Help4.x:Fields/es").
    [Learn
    more.](https://docs.joomla.org/J4.x:Deleting_an_Article/en "J4.x:Deleting an Article/en")
- **Grupo de campos**. Puede asignar un campo personalizado a uno o más
  grupos de campos.
- **Categoría**. Puede asignar un campo personalizado a una o más
  categorías de campos. Tenga en cuenta que el valor predeterminado
  'Todos' no incluye artículos 'Sin Categoría'.
- **Acceso**. Vea [Niveles de
  Acceso](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/es "Help4.x:Users: Viewing Access Levels/es")
  para este campo.
- **Idioma**. Selecciona el idioma para este elemento. Si no estás
  utilizando la característica
  [multi-idioma](https://docs.joomla.org/Help4.x:Extensions:_Languages/es "Help4.x:Extensions: Languages/es")
  de Joomla!, mantén el valor predeterminado de 'Todos'.
- **Nota**. Un campo opcional para hacer sus notas personales para el
  campo.

### Opciones

<img
src="https://docs.joomla.org/images/thumb/d/d0/Help-4x-Fields-Edit-options-subscreen-es.png/600px-Help-4x-Fields-Edit-options-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/d0/Help-4x-Fields-Edit-options-subscreen-es.png/900px-Help-4x-Fields-Edit-options-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/d/d0/Help-4x-Fields-Edit-options-subscreen-es.png/1200px-Help-4x-Fields-Edit-options-subscreen-es.png 2x"
data-file-width="2880" data-file-height="1378" width="600" height="287"
alt="Help-4x-Fields-Edit-options-subscreen-es.png" />

**Opciones de formulario**

- **Marcador de posición**. Un texto que aparecerá dentro del campo
  personalizado como una sugerencia para la entrada. El marcador de
  posición está activo en el Backend al crear un artículo, un contacto o
  un componente de terceros que admite campos personalizados. Usted no
  lo verá en el Frontend.
- **Clase del campo**. La clase del campo cuando el campo es
  renderizado. Si se necesitan diferentes clases, sepárelas con
  espacios.
- **Clase de la etiqueta (Formulario)**. CSS class to apply to the field
  label when it is in edit mode (entering input into a field).
- **Editable en**. En qué parte del sitio debe mostrarse el campo. En el
  Backend, en el Frontend o ambos.
- **Showon Attribute**. Conditionally show or hide the field depending
  on the value of other fields. The syntax to use here, for example:
  `list-of-items:value1[OR]list-of-items:value2`
  - list-of-items – It is the *name* of an already created field on
    which this field will depends to be show.
  - value1 – Is the value need have the field on which it depends to be
    show.
  - \[OR\] – To create a choice among multiple fields. In the example,
    this field will show when *list-of-items* field have the value:
    *value1* OR *value2*
  - \[AND\] – To combine multiple fields. This field will show only when
    *list-of-items* field have the value: *value1* AND *value2*
  - You can also use value 'does not equal' as in
    **list-of-items!:value1**. The syntax will show this field only when
    *list-of-items* is not equal to *value1*
  - To show this field when *list-of-items* field has been selected and
    have not a empty value, use the syntax *list-of-items!:* (without a
    value specified).

**Note:** Subform fields handle different the identifier *name* of
*list-of-items*. If you create a Subform custom field and you add this
conditional field you are creating to there, you need use *field\[ID\]*
instead of *list-of-items*, where ID is the id of the field
*list-of-items*. Therefore, the showon attribute for this conditional
field you are creating need be: `field36:value1[OR]field36:value2` where
36 is the ID of the field 'List of items'.

**Opciones de visualización**

- **Clase de visualización**. La clase en la salida del contenedor del
  campo.
- **Clase del valor**. La clase del valor del campo en la salida.
- **Etiqueta**. Show the label when the field renders.
- **Clase de la etiqueta (Salida)**. CSS class to apply to the field
  label when it is displayed (displaying the output of a field).
- **Visualización automática**. Joomla ofrece algunos eventos de
  contenido que se activan durante el proceso de creación de contenido.
  Este es el lugar para definir cómo los campos personalizados deben
  integrarse en el contenido.
  - Después del título
  - Antes de mostrar contenido
  - Después de mostrar contenido
  - No mostrar automáticamente
- **Prefijo**. Fixed text to be displayed before a field, for example £.
- **Sufijo**. Fixed text to be displayed after a field, for example EUR.
- **Presentación**. If there is a custom layout then it would be
  selected here.
- **Mostrar cuando sean de sólo lectura**. If the field is read only
  (perhaps the user doesn't have the access level) should the field be
  displayed or hidden.

### Publicación

<img
src="https://docs.joomla.org/images/thumb/8/85/Help-4x-Fields-Edit-publishing-subscreen-es.png/600px-Help-4x-Fields-Edit-publishing-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/85/Help-4x-Fields-Edit-publishing-subscreen-es.png/900px-Help-4x-Fields-Edit-publishing-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/8/85/Help-4x-Fields-Edit-publishing-subscreen-es.png/1200px-Help-4x-Fields-Edit-publishing-subscreen-es.png 2x"
data-file-width="2880" data-file-height="980" width="600" height="204"
alt="Help-4x-Fields-Edit-publishing-subscreen-es.png" />

- **Fecha de creación** . Este campo de forma predeterminada toma la
  fecha y la hora actual cuando el campo fue creado. Puedes entrar una
  fecha y hora diferentes o hacer clic en el icono de calendario para
  encontrar la fecha deseada.
- **Creado por**. Nombre del usuario de Joomla! que creó este campo.
  Esto será predeterminado por el usuario conectado actualmente. Si
  deseas cambiar a un usuario diferente, has clic en el botón
  Seleccionar Usuario para elegir un usuario diferente.
- **Fecha de modificación**. Fecha de la última modificación.
- **Modificado por**. Nombre del Usuario que realizó la última
  modificación.
- **ID**. Este es un número de identificación único para este campo. Se
  utiliza para identificar el campo internamente y no se puede cambiar
  este número.

### Permisos

This is where you can enter permissions for this field.

[Learn
more.](https://docs.joomla.org/J3.x:Access_Control_List_Tutorial/en#hierarchylevels "J3.x:Access Control List Tutorial/en")

<img
src="https://docs.joomla.org/images/thumb/a/ad/Help-4x-Fields-Edit-permissions-subscreen-es.png/600px-Help-4x-Fields-Edit-permissions-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/ad/Help-4x-Fields-Edit-permissions-subscreen-es.png/900px-Help-4x-Fields-Edit-permissions-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/a/ad/Help-4x-Fields-Edit-permissions-subscreen-es.png/1200px-Help-4x-Fields-Edit-permissions-subscreen-es.png 2x"
data-file-width="2880" data-file-height="1260" width="600" height="263"
alt="Help-4x-Fields-Edit-permissions-subscreen-es.png" />

To change the permissions for this field, do the following.

1.  Select the **Group** by clicking its title located on the left.
2.  Find the desired **Action**.
    - **Delete**. Users can delete this field.
    - **Edit**. Users can edit this field.
    - **Edit State**. User can change the published state and related
      information for this field.
    - **Edit Custom Field Value.** Users can edit the field value.
3.  Select the desired permission for the action you wish to change.
    - **Inherited**. Inherited for users in this Group from the [Global
      Configuration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/en#permissions "Help4.x:Site Global Configuration/en"),
      parent group, or category.
    - **Allowed**. Allowed for users in this Group.Note: If this action
      is Denied at one of the higher levels, the Allowed permission here
      will not take effect. A Denied setting cannot be overridden.
    - **Denied**. Denied for users in this Group.
4.  Click **Save** in **Toolbar** at top. When the screen refreshes, the
    Calculated Setting column will show the effective permission for
    this Group and Action.

## Barra de herramientas

At the top of the page you will see the toolbar shown in the
[Screenshot](#screenshot) above.

- **Save**. Saves the field and stays in the current screen.
- **Save & Close**. Saves the field and closes the current screen.
  - **Save & New**. Saves the field and keeps the editing screen open
    and ready to create another field.
  - **Save as Copy**. Saves your changes to a copy of the current field.
    Does not affect the current field.
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help**. Opens this help screen.

## Consejos Rápidos

If you want to know how to use fields: [Managing Custom
Fields](https://docs.joomla.org/J3.x:Adding_custom_fields/en "J3.x:Adding custom fields/en").

## Información relacionada

- Este
  [portal](https://docs.joomla.org/Portal:Joomla_4/es "Portal:Joomla 4/es")
  reúne información específica relativa a Joomla 4.

|                                                                                                                  |                                                                                                                                                      |
|------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Pantallas de ayuda relacionadas                                                                                  | Descripción                                                                                                                                          |
| [Campos](https://docs.joomla.org/Help4.x:Fields/es "Help4.x:Fields/es")                                          | Fields are used to display additional attributes of Articles, Contacts and Users. The data are entered in the Backend and displayed in the Frontend. |
| <span class="mw-selflink selflink">Campos: Editar</span>                                                         | This is where you can add and edit Fields in Articles, Contacts, and Users.                                                                          |
| [Grupos de campo](https://docs.joomla.org/Help4.x:Field_Groups/es "Help4.x:Field Groups/es")                     | The Field Groups screen is used to list, add and edit Field Groups.                                                                                  |
| [Grupos de campo: Editar](https://docs.joomla.org/Help4.x:Field_Groups:_Edit/es "Help4.x:Field Groups: Edit/es") | Field Groups are used to collect related fields under a named Tab in a data entry form.                                                              |
