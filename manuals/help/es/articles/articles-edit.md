<!-- Filename: Help4.x:Articles:_Edit / Display title: Artículos: Editar -->

## Descripción

Esta pantalla se usa para editar un artículo nuevo o ya existente,
generalmente usando un editor Wysiwyg. El editor predeterminado es
TinyMCE, pero si se instalan otros editores, el editor predeterminado
puede configurarse de otro modo para el sitio de forma global, o de
forma individual para cada usuario.

La mayoría de los parámetros tienen valores predeterminados adecuados,
pero es posible que desee establecer una categoría específica o
proporcionar Metadatos para un artículo específico.

## Cómo Acceder

**Content **→** Articles**

Para agregar un artículo:

- Clic el botón **Opciones** en la Barra de Herramientas.

Para editar un artículo:

- Seleccione un **Título** de artículo en la lista.

## Captura de pantalla

<img
src="https://docs.joomla.org/images/f/ff/Help-4x-content-article-manager-add-new-article-es.png"
decoding="async" data-file-width="800" data-file-height="471"
width="800" height="471"
alt="Help-4x-content-article-manager-add-new-article-es.png" />

## Campos de Formulario

- **Título**. El Título para este artículo.
- **Alias**. El alias se usará en la URL amigable. Si lo deja en blanco,
  Joomla! lo rellenará con un valor predeterminado obtenido a partir del
  título. [Learn more.](https://docs.joomla.org/Alias/en "Alias/en")

### Contenido

**Panel izquierdo**

- **Texto del artículo**. This is where you enter the contents of the
  article. Joomla includes 3 editors, the default [Editor -
  TinyMCE](https://docs.joomla.org/Help4.x:Editors/en#tinymce "Help4.x:Editors/en")
  is shown here.

<img
src="https://docs.joomla.org/images/thumb/7/79/Help-4x-Article-Editor-buttons-es.png/600px-Help-4x-Article-Editor-buttons-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/79/Help-4x-Article-Editor-buttons-es.png/900px-Help-4x-Article-Editor-buttons-es.png 1.5x, https://docs.joomla.org/images/thumb/7/79/Help-4x-Article-Editor-buttons-es.png/1200px-Help-4x-Article-Editor-buttons-es.png 2x"
data-file-width="1979" data-file-height="735" width="600" height="223"
alt="Help-4x-Article-Editor-buttons-es.png" />

El Editor WYSIWYG de Artículos es configurable y puede tener un conjunto
de botones diferente al que se muestra a continuación. La lista
desplegable Contenido de CMS proporciona acceso a funciones especiales.
[Learn
more.](https://docs.joomla.org/Help4.x:Editors/en#cmscontent "Help4.x:Editors/en")

- **Alternar editor**. A Toggle Editor button show below the edit
  window. This button allows you to toggle between TinyMCE and [Editor -
  None](https://docs.joomla.org/Help4.x:Editors/en#none "Help4.x:Editors/en").

**Panel Derecho**

- **Estado**. El estado de publicación de este artículo.
  - Publicado: Article is visible in the Frontend of the site.
  - Despublicado: Article is will not be visible to guests in the
    Frontend of the site. It may be visible to logged in users who have
    [edit state permission](#permissions) for the article.
  - Archivado: Article will no longer show on menu items [Category
    Blog](https://docs.joomla.org/Help4.x:Menu_Item:_Category_Blog/en "Help4.x:Menu Item: Category Blog/en")
    or [Category
    List.](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/en "Help4.x:Menu Item: Category List/en")
  - Movido a la papelera: Article is deleted from the site but still in
    the database. [Learn
    more.](https://docs.joomla.org/J4.x:Deleting_an_Article/en "J4.x:Deleting an Article/en")
- **Categoría**. Selecciona la Categoría para este Artículo.
- **Destacado**. Select Yes if article will be shown in the [Featured
  menu
  item.](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/en "Help4.x:Menu Item: Featured Articles/en")
- **Acceso**. Vea [Niveles de
  Acceso](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/es "Help4.x:Users: Viewing Access Levels/es")
  para este artículo.
- **Idioma**. Selecciona el idioma para este artículo. Si no estás
  utilizando la característica
  [multi-idioma](https://docs.joomla.org/Help4.x:Extensions:_Languages/es "Help4.x:Extensions: Languages/es")
  de Joomla!, mantén el valor predeterminado de 'Todos'.
- **Etiquetas**. Asignar etiquetas a artículo. Puede seleccionar una
  etiqueta de la [lista
  predefinida](https://docs.joomla.org/Help4.x:Tags/es "Help4.x:Tags/es")
  o ingresar una nueva etiqueta escribiendo el nombre en el campo y
  presionando enter.
- **Nota**. This is normally for the administrator's use (for example,
  to document information about this article) and does not show in the
  Frontend.
- **Nota de la versión**. Optional field to identify the version of this
  article in the article's [Version
  History](https://docs.joomla.org/Help4.x:Components_Version_History/en "Help4.x:Components Version History/en").

### Imágenes y Enlaces

**Nota**: Esto puede ser ocultado por un usuario con permisos de
administrador en el [Artículo:
Opciones](https://docs.joomla.org/Help4.x:Articles:_Options/es "Help4.x:Articles: Options/es").  
This section lets you display images and links in your articles using
standardised layouts.

<img
src="https://docs.joomla.org/images/thumb/6/62/Help-4x-screenshot-article-edit-images-links-es.png/600px-Help-4x-screenshot-article-edit-images-links-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/62/Help-4x-screenshot-article-edit-images-links-es.png/900px-Help-4x-screenshot-article-edit-images-links-es.png 1.5x, https://docs.joomla.org/images/thumb/6/62/Help-4x-screenshot-article-edit-images-links-es.png/1200px-Help-4x-screenshot-article-edit-images-links-es.png 2x"
data-file-width="2880" data-file-height="1425" width="600" height="297"
alt="Help-4x-screenshot-article-edit-images-links-es.png" />

**Imagen de introducción**

- **Imagen de introducción**. Click the Select button to select an image
  to be displayed in a fixed location in the Intro Text of this article.
  This will open a window that allows you to select an image from your
  images folder. [Learn
  more.](https://docs.joomla.org/Adding_an_image_to_an_article/en "Adding an image to an article/en")
- **Descripción de la imagen (texto alternativo)**. Set the alt
  attribute for this image. A few descriptive words for screen readers.
- **Sin descripción**. Check in the rare instance of a purely decorative
  image. Note that if the Image Description is empty and the No
  Description checkbox is unchecked then the image will fail to meet
  accessibility criteria. If an image description is present this
  checkbox has no effect.
- **Clase de la imagen**. Puede añadir cualquier clase CSS para sus
  propias ideas de estilo. Para posición de imagen use por ejemplo
  'float-star' y 'float-end'.
  <a href="https://cassiopeia.joomla.com/help" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">Learn more.</a>
- **Subtítulo**. Create a caption for this image.

**Imagen para mostrar un artículo al completo**

- **Imagen para mostrar un artículo al completo**. Click the Select
  button to select an image to be displayed in a fixed location in the
  Full Text of this article. This will open a window that allows you to
  select an image from your images folder. [Learn
  more.](https://docs.joomla.org/Adding_an_image_to_an_article/en "Adding an image to an article/en")
- **Descripción de la imagen (texto alternativo)**. Set the alt
  attribute for this image. A few descriptive words for screen readers.
- **Sin descripción**. Check in the rare instance of a purely decorative
  image. Note that if the Image Description is empty and the No
  Description checkbox is unchecked then the image will fail to meet
  accessibility criteria. If an image description is present this
  checkbox has no effect.
- **Clase de la imagen**. Puede añadir cualquier clase CSS para sus
  propias ideas de estilo. Para posición de imagen use por ejemplo
  'float-start' y 'float-end'.
  <a href="https://cassiopeia.joomla.com/help" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">Learn more.</a>
- **Subtítulo**. Enter an optional caption for this image.

**Enlace A**

- **Enlace A**. La dirección URL para el primer enlace que se muestre en
  una ubicación fija en el texto del artículo. Esta debe ser una URL
  completa, no relativa. Por ejemplo, normalmente comienzan con
  'https://'.
- **Texto del enlace 'A'**. The text used for Link A. If blank, the URL
  will be displayed.
- **Ventana URL de destino**. Sets the default value for the target for
  the first Link in this article. Choices are:
  - Misma ventana: Opens the in the main browser window, replacing the
    current Joomla article.
  - Nueva ventana: Opens the link in a new browser window.
  - En una ventana emergente: Opens the link in a pop-up browser window
    (without full navigation controls).
  - Modal: Opens the link in a modal pop-up window.

**Enlace B**, **Enlace C**: Same options as Link A.

### Opciones

**Nota**: Esto puede ser ocultado por un usuario con permisos de
administrador en el [Artículo:
Opciones](https://docs.joomla.org/Help4.x:Articles:_Options/es "Help4.x:Articles: Options/es").  
This is a set of options you can use to control how this article will
show in the Frontend.

<img
src="https://docs.joomla.org/images/thumb/e/eb/Help-4x-screenshot-article-edit-article-options-es.png/600px-Help-4x-screenshot-article-edit-article-options-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/eb/Help-4x-screenshot-article-edit-article-options-es.png/900px-Help-4x-screenshot-article-edit-article-options-es.png 1.5x, https://docs.joomla.org/images/thumb/e/eb/Help-4x-screenshot-article-edit-article-options-es.png/1200px-Help-4x-screenshot-article-edit-article-options-es.png 2x"
data-file-width="2880" data-file-height="1427" width="600" height="297"
alt="Help-4x-screenshot-article-edit-article-options-es.png" />

**Presentación**

- **Presentación**. Utilizar un diseño suministrado para la vista del
  artículo o [sobrescribir las
  plantillas](https://docs.joomla.org/Help4.x:Templates:_Customise/es "Help4.x:Templates: Customise/es").
- **Mostrar título**. Show the Article's Title.
- **Título enlazable**. Si el Título del Artículo se muestra, si se va a
  mostrar como un enlace al artículo.
- **Etiquetas**. Enter tags for this article. Select existing tags by
  entering in the first few letters or create new tags by entering them
  here. [Learn
  more.](https://docs.joomla.org/J4.x:How_To_Use_Content_Tags_in_Joomla/en "J4.x:How To Use Content Tags in Joomla/en")
- **Texto de introducción**.
  - Mostrar: The Intro Text of the article will show when you drill down
    to the article.
  - Ocultar: Only the part of the article after the Read More break will
    show.
- **Información de la posición del artículo**.
  - Encima: Puts the article information block above the text.
  - Debajo: Puts the article information block below the text.
  - Dividido: Splits the article information block into 2 separate
    blocks. One block is above and the other is below the text.
- **Título de información del artículo**. Muestra el título 'Información
  del artículo' en la parte superior del bloque de información del
  artículo.

**Categoría**

- **Categoría**. Show the Article's Category Title.
- **Categoría enlazable**. Si la categoría del artículo se muestra, si
  se va a mostrar como un enlace a un Diseño de categoría (lista o
  blog), para la Categoría.
- **Mostrar categoría principal**. Show the Article's Parent Category
  Title.
- **Categoría principal enlazable**. Si la categoría principal del
  artículo se muestra, si se va a mostrar como un enlace a un Diseño de
  categoría - (lista o blog), para la Categoría.

**Asociaciones**

- **Mostrar asociaciones**. Show the associated flags or Language Code.
  [Multilingual
  only.](https://docs.joomla.org/Help4.x:Multilingual_Associations/en "Help4.x:Multilingual Associations/en")

**Mostrar autor**

- **Mostrar autor**. Show the author of the Article.
- **Autor enlazable**. Si el autor del Artículo que se muestra, se va a
  mostrar como un enlace a un diseño de Contacto con el autor.Note: The
  author must be [set up as a
  Contact](https://docs.joomla.org/Help4.x:Contacts/en "Help4.x:Contacts/en").

**Fecha**

- **Mostrar la fecha de creación**. Show the Article's create date.
- **Mostrar fecha de modificación**. Show the Article's modify date.
- **Mostrar fecha de publicación**. Show the Article's start publishing
  date.

**Opciones**

- **Mostrar navegación**. Show a navigation link 'Prev' or 'Next' when
  you drill down to the article.
- **Mostrar impresiones**. Show the number of times the article has been
  displayed by a user.
- **Mostrar los enlaces no autorizados**. If Yes, the Intro Text for
  restricted articles will show. Clicking on the Read more link will
  require users to log in to view the full article content.
- **Posición de los enlaces.**
  - Encima: Links are shown above the content.
  - Debajo: Links are shown below the content.
- **Texto del 'Leer más...'**. Customise the text that shows for the
  default wording 'Read more'.
- **Título de página del navegador**. Texto opcional para el elemento
  "Título de la página del navegador" que se utilizará cuando se vea el
  artículo con un elemento del menú que no sea un artículo. Si está en
  blanco, se usa el título del artículo en su lugar.

### Campos

This section shows the [custom
fields](https://docs.joomla.org/Help4.x:Fields/en "Help4.x:Fields/en")
which are defined for this article.

<img
src="https://docs.joomla.org/images/thumb/2/22/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-es.png/600px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/22/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-es.png/900px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/2/22/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-es.png/1200px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-es.png 2x"
data-file-width="2880" data-file-height="570" width="600" height="119"
alt="Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-es.png" />

### Publicación

**Nota**: Esto puede ser ocultado por un usuario con permisos de
administrador en el [Artículo:
Opciones](https://docs.joomla.org/Help4.x:Articles:_Options/es "Help4.x:Articles: Options/es").  
This section allows you to enter parameters and
[Metadata](https://docs.joomla.org/Using_The_Meta_Description/en "Using The Meta Description/en")
for this Article.

<img
src="https://docs.joomla.org/images/thumb/0/04/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-es.png/600px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/04/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-es.png/900px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/0/04/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-es.png/1200px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-es.png 2x"
data-file-width="2880" data-file-height="1420" width="600" height="296"
alt="Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-es.png" />

**Publicación**

- **Inicio de la publicación**. Date and time to start publishing. Enter
  article ahead of time and then have it published automatically at a
  future time.
- **Finalización de la publicación**. Fecha y hora para terminar de
  publicar. Utiliza este campo si deseas que el contenido cambie
  automáticamente al estado de no publicado en una fecha futura (por
  ejemplo, cuando deja de ser aplicable).
- **Iniciar 'Destacado'**. Date and time to start featured state. Enter
  article ahead of time and then have it featured automatically at a
  future time.
- **Finalizar 'Destacado'**. Date and time to finish featured state. The
  article is automatically changed to Unfeatured state at a future time.
- **Fecha de creación**. Este campo de forma predeterminada toma la
  fecha y la hora actual cuando el Artículo fue creado. Puedes entrar
  una fecha y hora diferentes o hacer clic en el icono de calendario
  para encontrar la fecha deseada.
- **Creado por**. Nombre del usuario de Joomla! que creó este elemento.
  Esto será predeterminado por el usuario conectado actualmente. Si
  deseas cambiar a un usuario diferente, has clic en el botón
  Seleccionar Usuario para elegir un usuario diferente.
- **Creado por alias**. Este campo opcional te permite entrar un alias
  para este Autor de este Artículo. Esto te permite mostrar un nombre
  diferente del Autor de este Artículo.
- **Fecha de modificación**. Fecha de la última modificación.
- **Modificado por**. Nombre del Usuario que realizó la última
  modificación.
- **Revisión**. Number of revisions to this Article.
- **Veces visto**. El número de veces que un artículo ha sido visto.
- **ID**. Este es un número de identificación único para este elemento
  asignado automáticamente por Joomla!. Se utiliza para identificar el
  elemento internamente y no se puede cambiar este número. Al crear un
  nuevo elemento, este campo muestra "0" hasta que se guarda la nueva
  entrada, momento en el que se asigna un nuevo ID.

**Metadatos**

- **Metadescripción**. Un párrafo para ser utilizado como la descripción
  de la página. [Learn
  more.](https://docs.joomla.org/Using_The_Meta_Description/en "Using The Meta Description/en")
- **Metapalabras clave**. Entry for keywords. [Learn
  more.](https://docs.joomla.org/Using_Keywords/en "Using Keywords/en")
- **Robots**. The instructions for web 'robots' that browse to this
  page. Set 'Use Global' in [Global
  Configuration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/en#robots "Help4.x:Site Global Configuration/en").
- **Autor**. Entrada para un nombre de Autor dentro de los metadatos.
- **Derechos del contenido**. Describe what rights others have to use
  this content.

### Asociaciones

**Nota**: Esto puede ser ocultado por un usuario con permisos de
administrador en el [Artículo:
Opciones](https://docs.joomla.org/Help4.x:Articles:_Options/es "Help4.x:Articles: Options/es").  
Tab is shown on [Multilingual
Sites](https://docs.joomla.org/Help4.x:Multilingual_Associations/en "Help4.x:Multilingual Associations/en")
only.

<img
src="https://docs.joomla.org/images/thumb/d/d3/Help-4x-screenshot-article-edit-associations-es.png/600px-Help-4x-screenshot-article-edit-associations-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/d3/Help-4x-screenshot-article-edit-associations-es.png/900px-Help-4x-screenshot-article-edit-associations-es.png 1.5x, https://docs.joomla.org/images/thumb/d/d3/Help-4x-screenshot-article-edit-associations-es.png/1200px-Help-4x-screenshot-article-edit-associations-es.png 2x"
data-file-width="2880" data-file-height="1389" width="600" height="289"
alt="Help-4x-screenshot-article-edit-associations-es.png" />

### Opciones de la pantalla de edición

**Nota**: Esto puede ser ocultado por un usuario con permisos de
administrador en el [Artículo:
Opciones](https://docs.joomla.org/Help4.x:Articles:_Options/es "Help4.x:Articles: Options/es").

<img
src="https://docs.joomla.org/images/thumb/2/28/Help-4x-screenshot-article-edit-configure-edit-screen-es.png/600px-Help-4x-screenshot-article-edit-configure-edit-screen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/28/Help-4x-screenshot-article-edit-configure-edit-screen-es.png/900px-Help-4x-screenshot-article-edit-configure-edit-screen-es.png 1.5x, https://docs.joomla.org/images/thumb/2/28/Help-4x-screenshot-article-edit-configure-edit-screen-es.png/1200px-Help-4x-screenshot-article-edit-configure-edit-screen-es.png 2x"
data-file-width="2880" data-file-height="1022" width="600" height="213"
alt="Help-4x-screenshot-article-edit-configure-edit-screen-es.png" />

- **Opciones de publicación**. If Hide, the [Publishing Options
  tab](https://docs.joomla.org/Help4.x:Articles:_Edit/en#publishing "Help4.x:Articles: Edit/en")
  will not show in the Backend. This means that Backend users will not
  be able to edit the fields in this tab. These fields will always be
  set to their default values.
- **Opciones del artículo**. If Hide, the [Article Options
  tab](https://docs.joomla.org/Help4.x:Articles:_Edit/en#options "Help4.x:Articles: Edit/en")
  will not show in the Backend. This means that Backend users will not
  be able to edit the fields in this tab. These fields will always be
  set to their default values.
- **Mostrar las 'Opciones de imágenes y enlaces' desde la
  administración**. If Yes, the [Images and Links
  tab](https://docs.joomla.org/Help4.x:Articles:_Edit/en#imagesandlinks "Help4.x:Articles: Edit/en")
  will show.
- **Mostrar las 'Opciones de imágenes y enlaces' desde el sitio**. If
  Yes, the Images and Links tab will show in the Frontend article editor
  screen.

### Permisos

**Nota**: Esto puede ser ocultado por un usuario con permisos de
administrador en el [Artículo:
Opciones](https://docs.joomla.org/Help4.x:Articles:_Options/es "Help4.x:Articles: Options/es").  
This is where you can enter permissions for this article. [Learn
more.](https://docs.joomla.org/J3.x:Access_Control_List_Tutorial/en#hierarchylevels "J3.x:Access Control List Tutorial/en")

<img
src="https://docs.joomla.org/images/thumb/6/69/Help-4x-screenshot-article-edit-permissions-es.png/600px-Help-4x-screenshot-article-edit-permissions-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/69/Help-4x-screenshot-article-edit-permissions-es.png/900px-Help-4x-screenshot-article-edit-permissions-es.png 1.5x, https://docs.joomla.org/images/thumb/6/69/Help-4x-screenshot-article-edit-permissions-es.png/1200px-Help-4x-screenshot-article-edit-permissions-es.png 2x"
data-file-width="2880" data-file-height="1265" width="600" height="264"
alt="Help-4x-screenshot-article-edit-permissions-es.png" />

To change the permissions for this article, do the following.

1.  Select the **Group** by clicking its title located on the left.
2.  Find the desired **Action**.
    - **Borrar**. Users can delete this article.
    - **Editar**. Users can edit this article.
    - **Editar estado**. User can change the published state and related
      information for this article.
3.  Select the desired permission for the action you wish to change.
    - **Heredado**. Inherited for users in this Group from the [Global
      Configuration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/en#permissions "Help4.x:Site Global Configuration/en"),
      [Articles
      Options](https://docs.joomla.org/Help4.x:Articles:_Options/en#permissions "Help4.x:Articles: Options/en"),
      or [Articles
      Category](https://docs.joomla.org/Help4.x:Articles:_Edit_Category/en#permissions "Help4.x:Articles: Edit Category/en").
    - **Permitido**. Allowed for users in this Group.Note: If this
      action is Denied at one of the higher levels, the Allowed
      permission here will not take effect. A Denied setting cannot be
      overridden.
    - **Denegado**. Denied for users in this Group.
4.  Click **Save** in **Toolbar** at top. When the screen refreshes, the
    Calculated Setting column will show the effective permission for
    this Group and Action.

## Barra de herramientas

At the top of the page you will see the toolbar shown in the
[Screenshot](#screenshot) above.

- **Guardar**. Saves the article and stays in the current screen.
- **Guardar y cerrar**. Saves the article and closes the current screen.
  - **Guardar y nuevo**. Saves the article and keeps the editing screen
    open and ready to create another article.
  - **Guardar en el menú**. Saves the article to a menu item and opens
    the menu item screen.
  - **Guardar como copia**. Saves your changes to a copy of the current
    article. Does not affect the current article.
- **Cerrar**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Versiones**. Opens the Article Version History window to show any
  prior versions of this article. This allows you to view older versions
  of this article and, if desired, restore from an older version. [Learn
  more.](https://docs.joomla.org/Help4.x:Components_Version_History/en "Help4.x:Components Version History/en")
- **Previsualizar**. Opens a modal dialog showing a site view of this
  article. Requires [shared
  sessions](https://docs.joomla.org/Help4.x:Site_Global_Configuration/en#sharedsessions "Help4.x:Site Global Configuration/en")
  or being logged in into the Frontend.
- **Comprobación de accesibilidad**. Opens a window showing
  accessibility check results of the article.
- **Asociaciones**. With a specific language set for an article, allows
  side by side editing in another language. This icon is shown on
  [Multilingual
  Sites](https://docs.joomla.org/Help4.x:Multilingual_Associations/en "Help4.x:Multilingual Associations/en")
  only.
- **Alternar la ayuda interna**. Show help text below some options.
- **Ayuda**. Se abre esta pantalla de ayuda.

## Consejos Rápidos

- There are 2 methods to insert an image into article using the TinyMCE
  editor.
  1.  The [CMS
      Content](https://docs.joomla.org/Help4.x:Editors/en#cmscontent "Help4.x:Editors/en")
      dropdown list provides access to the [Media
      screen](https://docs.joomla.org/Help4.x:Media/en "Help4.x:Media/en")
      that lets you browse image files and upload images.
  2.  The 'Insert' dropdown list is a simple form for which you need to
      know the image url. It is used for external images.
- [Read
  more](https://docs.joomla.org/Help4.x:Editors/en#readmore "Help4.x:Editors/en")
  breaks allow you to save space on the Front Page or on any blog layout
  page by showing just the first portion of an Article. [Page
  break](https://docs.joomla.org/Help4.x:Editors/en#pagebreak "Help4.x:Editors/en")
  allow you to provide multi-page navigation for long Articles. You can
  use both on one Article, if desired.For example, you could put a Read
  more break after the first paragraph of a multi-page article, and have
  Page breaks after each page. No page navigation would display on the
  Front Page until the User selects the Read more link. At that time,
  the Article's table of contents would display showing links to every
  page.

## Información relacionada

- Este
  [portal](https://docs.joomla.org/Portal:Joomla_4/es "Portal:Joomla 4/es")
  reúne información específica relativa a Joomla 4.

|                                                                                                                                                                     |                                                                                                                                                                                             |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Pantallas de ayuda relacionadas                                                                                                                                     | Descripción                                                                                                                                                                                 |
| [Artículos: Opciones](https://docs.joomla.org/Help4.x:Articles:_Options/es "Help4.x:Articles: Options/es")                                                          | Used to set global defaults for menu items that display articles. These default values will be used when 'Use Global' is selected for an option in an Articles menu item.                   |
| [Artículos](https://docs.joomla.org/Help4.x:Articles/es "Help4.x:Articles/es")                                                                                      | The Article list is used to find, mark featured, add and edit articles.                                                                                                                     |
| <span class="mw-selflink selflink">Artículos: Editar</span>                                                                                                         | This is where you can add and edit Articles. You can also select the Category for an Article and indicate whether or not it is Published and if it is selected to appear on the Front Page. |
| [Artículos: Destacados](https://docs.joomla.org/Help4.x:Articles:_Featured/es "Help4.x:Articles: Featured/es")                                                      | Used to control which 'Featured Articles' are displayed on the Front Page and in what order they are displayed.                                                                             |
| [Artículos: Categorías](https://docs.joomla.org/Help4.x:Articles:_Categories/es "Help4.x:Articles: Categories/es")                                                  | The Articles Categories list is used to find, add, and edit articles categories.                                                                                                            |
| [Menús: Mostrar los artículos archivados](https://docs.joomla.org/Help4.x:Menu_Item:_Article_Archived/es "Help4.x:Menu Item: Article Archived/es")                  | Shows a customised list of articles ordered by date or title. Archived articles are no longer published but are still stored on the site.                                                   |
| [Menús: Mostrar una categoría en formato blog](https://docs.joomla.org/Help4.x:Menu_Item:_Category_Blog/es "Help4.x:Menu Item: Category Blog/es")                   | Used to show articles belonging to a specific Category in a blog layout. Controls the Leading Articles, Intro Articles and additional links to more Articles.                               |
| [Menús: Mostrar una categoría en formato lista](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/es "Help4.x:Menu Item: Category List/es")                  | Used to show articles belonging to a specific Category in a list layout.                                                                                                                    |
| [Menús: Mostrar el formulario para crear y enviar un artículo](https://docs.joomla.org/Help4.x:Menu_Item:_Create_Article/es "Help4.x:Menu Item: Create Article/es") | Allows users to submit an article. Normally this is available only to users who have logged in to the Frontend of the site. Users must have permission to create articles.                  |
| [Menús: Mostrar todos los artículos destacados](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/es "Help4.x:Menu Item: Featured Articles/es")          | Used to show all Articles that have been tagged as Featured. Articles are shown in a Blog Layout.                                                                                           |
| [Menús: Mostrar listado de todas las categorías](https://docs.joomla.org/Help4.x:Menu_Item:_List_All_Categories/es "Help4.x:Menu Item: List All Categories/es")     | Used to show a hierarchical list of Categories. Depending on the selected options for this layout, you can click on a category Title to show the articles in that category.                 |
| [Menús: Mostrar un solo artículo](https://docs.joomla.org/Help4.x:Menu_Item:_Single_Article/es "Help4.x:Menu Item: Single Article/es")                              | Used to show one article.                                                                                                                                                                   |
