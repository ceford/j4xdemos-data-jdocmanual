<!-- Filename: Help4.x:Users:_Options / Display title: Usuarios: Opciones -->

## Descripción

User Options set globally for all users include

- Captcha,
- registration allowed and type of registration,
- default user group for new users,
- reset password or username counter,
- new user registration email notice to administration and more.

## Cómo Acceder

**Usuarios **→** Gestionar**

- Clic el botón **Opciones** en la Barra de Herramientas.

## Captura de pantalla

<img
src="https://docs.joomla.org/images/thumb/c/c2/Help-4x-Users-Options-screen-es.png/800px-Help-4x-Users-Options-screen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c2/Help-4x-Users-Options-screen-es.png/1200px-Help-4x-Users-Options-screen-es.png 1.5x, https://docs.joomla.org/images/thumb/c/c2/Help-4x-Users-Options-screen-es.png/1600px-Help-4x-Users-Options-screen-es.png 2x"
data-file-width="2400" data-file-height="1500" width="800" height="500"
alt="Help-4x-Users-Options-screen-es.png" />

## Campos del formulario

### Opciones de usuario

- **Permitir el registro de usuarios**.
  - Sí: Users can register from the Frontend of the site using the
    'Create an Account' link provided on the
    <a href="https://docs.joomla.org/Help4.x:Site_Modules:_Login/es"
    class="new"
    title="Special:MyLanguage/Help4.x:Site Modules: Login/es (page does not exist)">Login
    module</a>.
  - No: The 'Create an Account' link will not show.
- **Grupo predeterminado de registro**. The
  <a href="https://docs.joomla.org/Help4.x:Users:_Groups/es" class="new"
  title="Special:MyLanguage/Help4.x:Users: Groups/es (page does not exist)">group</a>
  that users are assigned to by default when they register on the site.
  Defaults to 'Registered'.
- **Grupo para los invitados**. The group that guests are assigned to
  (Guests are visitors to the site who are not logged in). It is
  possible to create content on the site that is visible to guests but
  not visible to logged in users. <a
  href="https://magazine.joomla.org/all-issues/june-2021/explore-the-core-controlling-user-access?"
  class="external text" target="_blank" rel="noreferrer noopener">Aprende
  más.</a>
- **Enviar contraseña**. If set to 'Yes' the user's first password will
  be emailed to the user as part of the registration mail.
- **Activación de cuentas de usuario**.
  - Ninguno: Cuenta de usuario se activa inmediatamente con no se
    requiere ninguna acción.
  - Por sí mismo: El usuario recibirá un correo electrónico con un
    enlace de activación. La cuenta se activa cuando el usuario hace
    clic en el enlace de activación.
  - Administrador: El usuario recibirá un correo electrónico con un
    enlace de activación. Cuando el usuario hace clic en este enlace, la
    Administración del Sitio, será notificada a través de un correo
    electrónico y la Administración del Sitio debe activar la cuenta del
    usuario.
- **Enviar correo electrónico a los administradores**. Send email
  notification to administrators with 'New User Account Activation' set
  to 'None' or 'Self'.
- **Captcha**. Use
  [Captcha](https://docs.joomla.org/Help4.x:Site_Global_Configuration/es#captcha "Special:MyLanguage/Help4.x:Site Global Configuration/es")
  for User Account Registration, User Password reminder and Username
  reminder.
- **Perfil de usuario desde el sitio**.
  - Mostrar: Users will be able to modify their
    <a href="https://docs.joomla.org/Help4.x:Users:_Edit_Profile/es"
    class="new"
    title="Special:MyLanguage/Help4.x:Users: Edit Profile/es (page does not exist)">Basic
    Settings</a> from the Frontend of the site.
  - Ocultar: User will not be able to change these settings.
  - Idioma del sitio. Default site language.
- **Cambiar el nombre de usuario**. Allow user to change Username.

### Opciones de dominio de correo electrónico

<img
src="https://docs.joomla.org/images/thumb/d/d5/Help-4x-Users-Options-email-domain-subscreen-es.png/600px-Help-4x-Users-Options-email-domain-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/d5/Help-4x-Users-Options-email-domain-subscreen-es.png/900px-Help-4x-Users-Options-email-domain-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/d/d5/Help-4x-Users-Options-email-domain-subscreen-es.png/1200px-Help-4x-Users-Options-email-domain-subscreen-es.png 2x"
data-file-width="2002" data-file-height="1115" width="600" height="334"
alt="Help-4x-Users-Options-email-domain-subscreen-es.png" />

- **Nombre de dominio**. Ingrese una lista de dominios de correo
  electrónico permitidos y no permitidos. Predeterminadamente, todos los
  dominios están permitidos.Los comodines (\*) son compatibles. Por
  ejemplo:
  - \* (Asterisk): Permite o no permite el acceso a todos los dominios,
  - \*.com: ermite o no permite el acceso a todos los dominios '.com'
  - \*.joomla.org: ermite o no permite el acceso a todos los subdominios
    de 'joomla.org'
- **Regla** Seleccione si se permite o no el dominio.

### Opciones de contraseña

<img
src="https://docs.joomla.org/images/thumb/9/9e/Help-4x-Users-Options-password-subscreen-es.png/600px-Help-4x-Users-Options-password-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/9/9e/Help-4x-Users-Options-password-subscreen-es.png/900px-Help-4x-Users-Options-password-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/9/9e/Help-4x-Users-Options-password-subscreen-es.png/1200px-Help-4x-Users-Options-password-subscreen-es.png 2x"
data-file-width="2002" data-file-height="1285" width="600" height="385"
alt="Help-4x-Users-Options-password-subscreen-es.png" />

- **Solicitudes de restablecimiento**. The maximum number of password
  resets allowed within the time period. Zero indicates no limit.
- **Tiempo de restablecimiento (horas)**. The time period, in hours, for
  the reset counter.
- **Tamaño mínimo de la contraseña**. Set the minimum lenght for a
  password.
- **Cantidad mínima de números**. Set the minimum number of integers
  that must be included in a password.
- **Cantidad mínima de símbolos para contraseñas**. Set the minimum
  number of symbols (such as !@#\$) required in a password.
- **Mínimo de letras mayúsculas para contraseñas**. Set the minimum
  number of upper case alphabetical characters required for a password.
- **Mínimo de minúsculas**. Set the minimum number of lower case
  alphabetical characters required for a password.

### Autenticación multifactor

<img
src="https://docs.joomla.org/images/thumb/8/81/Help-4x-Users-Options-multi-factor-authentication-subscreen-es.png/600px-Help-4x-Users-Options-multi-factor-authentication-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/81/Help-4x-Users-Options-multi-factor-authentication-subscreen-es.png/900px-Help-4x-Users-Options-multi-factor-authentication-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/8/81/Help-4x-Users-Options-multi-factor-authentication-subscreen-es.png/1200px-Help-4x-Users-Options-multi-factor-authentication-subscreen-es.png 2x"
data-file-width="1978" data-file-height="1500" width="600" height="455"
alt="Help-4x-Users-Options-multi-factor-authentication-subscreen-es.png" />

- **Posiciones de módulo del sitio permitidas**. Al mostrar la página de
  Autenticación multifactor de la zona del sitio, se ocultarán todos los
  módulos menos los de las posiciones seleccionadas desde aquí.
- **Mostrar el título desde el sitio**. En la zona del sitio ¿Debo
  mostrar un título en la página de verificación de autenticación
  multifactor? Tenga en cuenta que, en la zona de la administración, el
  título siempre se va a mostrar. Si necesita cambiar el título, desde
  la administración, modifique la clave del idioma
  'COM_USERS_HEADING_MFA' accediendo a
  <a href="https://docs.joomla.org/Help4.x:Languages:_Overrides/es"
  class="new"
  title="Special:MyLanguage/Help4.x:Languages: Overrides/es (page does not exist)">Idiomas:
  Modificaciones</a>.
- **Posiciones de módulo de la administración permitidas**. Al mostrar
  la página de Autenticación multifactor de la zona de la
  administración, se ocultarán todos los módulos menos los de las
  posiciones seleccionadas desde aquí. Tenga en cuenta que los módulos
  en la posición 'title' siempre se muestran: esto es necesario para
  mostrar el icono y el título de la página de fondo.
- **Deshabilitar la autenticación multifactor**. Cualquier usuario que
  pertenezca a *cualquiera* de los siguientes grupos de usuarios estará
  exento de la autenticación multifactor. Incluso si se han configurado
  métodos de autenticación multifactor, no se les pedirá que los usen
  cuando inicien sesión, ni podrán verlos, eliminarlos o cambiar su
  configuración.
- **Forzar la autenticación multifactor**. Cualquier usuario que
  pertenezca a *cualquiera* de los siguientes grupos de usuarios deberá
  habilitar la autenticación multifactor antes de poder usar el sitio.
- **Estilo de plantilla del sitio**. Elija el estilo de plantilla del
  sitio a usar en la página de autenticación multifactor. Seleccione
  'Usar predeterminado' para usar el estilo de la plantilla del sitio
  predeterminado.
- **Autenticación multifactor después de inicio de sesión silencioso**.
  ¿Debería el usuario pasar por la autenticación multifactor después de
  un inicio de sesión de usuario silencioso? Los inicios de sesión
  silenciosos son aquellos que no requieren un nombre de usuario y
  contraseña. Por ejemplo: la función Recuérdeme, WebAuthn, etc.
- **Tipos de respuesta de autenticación de inicio de sesión silencioso
  (para expertos)**. Una lista separada por comas de los tipos de
  respuesta de autenticación de Joomla que se consideran inicios de
  sesión silenciosos. El valor predeterminado es 'cookie' (la función
  Recuérdeme) y 'passwordless' (WebAuthn).
- **Nuevos usuarios**. Si el usuario aún no ha configurado la
  autenticación multifactor y esta opción está habilitada, será
  redirigido a la página de configuración de la autenticación
  multifactor o a la URL personalizada que configuró a continuación.
  Esta pretende ser una forma sencilla de informar a sus usuarios que la
  autenticación multifactor es una opción en su sitio.
- **URL de redirección personalizada**. Si no está vacío, redirige a
  esta URL en lugar de a la página de configuración de autenticación
  multifactor cuando la opción anterior está habilitada.¡Advertencia!:
  Esta debe ser una URL dentro de su sitio. No puede iniciar sesión en
  un enlace externo o en un subdominio diferente.

### Historial de notas de usuario

<img
src="https://docs.joomla.org/images/thumb/5/53/Help-4x-Users-Options-user-notes-history-subscreen-es.png/600px-Help-4x-Users-Options-user-notes-history-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/53/Help-4x-Users-Options-user-notes-history-subscreen-es.png/900px-Help-4x-Users-Options-user-notes-history-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/5/53/Help-4x-Users-Options-user-notes-history-subscreen-es.png/1200px-Help-4x-Users-Options-user-notes-history-subscreen-es.png 2x"
data-file-width="2002" data-file-height="565" width="600" height="169"
alt="Help-4x-Users-Options-user-notes-history-subscreen-es.png" />

- **Guardar historial**. Save version history for User Notes.
- **Versiones máximas**.
  The maximum number of versions to store for a User Note. If a User
  Note is saved and the maximum number of versions has been reached, the
  oldest version will be deleted automatically. If set to 0, then
  versions will never be deleted automatically.Aprende más.

### Correo masivo de usuarios

<img
src="https://docs.joomla.org/images/thumb/b/b2/Help-4x-Users-Options-mass-mail-users-subscreen-es.png/600px-Help-4x-Users-Options-mass-mail-users-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/b/b2/Help-4x-Users-Options-mass-mail-users-subscreen-es.png/900px-Help-4x-Users-Options-mass-mail-users-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/b/b2/Help-4x-Users-Options-mass-mail-users-subscreen-es.png/1200px-Help-4x-Users-Options-mass-mail-users-subscreen-es.png 2x"
data-file-width="2002" data-file-height="878" width="600" height="263"
alt="Help-4x-Users-Options-mass-mail-users-subscreen-es.png" />

- **Prefijo del asunto**. Introduce un texto opcional que se insertará
  automáticamente antes que el asunto del correo electrónico.
- **Sufijo del texto de correo**. Escribe un texto opcional que se
  insertará automáticamente después del cuerpo del correo electrónico
  (por ejemplo, una firma).

### Integración

<img
src="https://docs.joomla.org/images/thumb/4/4c/Help-4x-Users-Options-integration-subscreen-es.png/600px-Help-4x-Users-Options-integration-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/4c/Help-4x-Users-Options-integration-subscreen-es.png/900px-Help-4x-Users-Options-integration-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/4/4c/Help-4x-Users-Options-integration-subscreen-es.png/1200px-Help-4x-Users-Options-integration-subscreen-es.png 2x"
data-file-width="2002" data-file-height="593" width="600" height="178"
alt="Help-4x-Users-Options-integration-subscreen-es.png" />

- **Habilitar campos personalizdos**. Enable the creation of custom
  fields.

### Permisos

This section lets you set up the default [Access Control
List](https://docs.joomla.org/Access_Control_List/es "Special:MyLanguage/Access Control List/es")
permissions for all users.

<img
src="https://docs.joomla.org/images/thumb/7/72/Help-4x-Users-Options-permissions-subscreen-es.png/600px-Help-4x-Users-Options-permissions-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/72/Help-4x-Users-Options-permissions-subscreen-es.png/900px-Help-4x-Users-Options-permissions-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/7/72/Help-4x-Users-Options-permissions-subscreen-es.png/1200px-Help-4x-Users-Options-permissions-subscreen-es.png 2x"
data-file-width="2002" data-file-height="1514" width="600" height="454"
alt="Help-4x-Users-Options-permissions-subscreen-es.png" />

To change the permissions for users, do the following.

1.  Selecciona el **Grupo** haciendo clic en el título que se encuentra
    a la izquierda.
2.  Find the desired **Action**.
    - **Configurar**. Users can edit the options and permissions.
    - **Solo opciones de configuración**. Users can edit the options
      exept the permissions.
    - **Acceso a la interfaz de administración**. Users can access user
      administration interface.
    - **Crear**. Users can create users.
    - **Borrar**. Users can delete users.
    - **Editar**. Users can edit users.
    - **Editar estado**. User can change the published state and related
      information.
    - **Editar valor de campo personalizado**. Users can edit any value
      of custom fields submitted in users.
3.  Select the desired permission for the action you wish to change.
    - **Heredado**. Inherited for users in this Group from the [Global
      Configuration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/es#permissions "Special:MyLanguage/Help4.x:Site Global Configuration/es")
      permissions.
    - **Permitido**. Allowed for users in this Group.Note: If this
      action is Denied at one of the higher levels, the Allowed
      permission here will not take effect. A Denied setting cannot be
      overridden.
    - **Denegado**. Denied for users in this Group.
4.  Has clic en **Guardar** en la **Barra de herramientas** en la parte
    superior. Cuando la pantalla se actualiza, la columna Configuración
    Calculada mostrará el permiso efectivo para este Grupo y Acción.

## Barra de herramientas

At the top of the page you will see the toolbar shown in the
[Screenshot](#screenshot) above.

- **Guardar**. Saves the users options and stays in the current screen.
- **Guardar y cerrar**. Saves the users options and closes the current
  screen.
- **Cerrar**. Cierra la pantalla actual y vuelve a la pantalla anterior
  sin guardar las modificaciones realizadas.
- **Alternar la ayuda interna**. Show help text below some options.
- **Ayuda**. Se abre esta pantalla de ayuda.

## Consejos Rápidos

If you are a beginning user, you can just keep the default values here
until you learn more about using global options.

## Información relacionada

|                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Pantallas de ayuda relacionadas                                                                                                                                   | Descripción                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [Users: Options](https://docs.joomla.org/Help4.x:Users:_Options/en "Help4.x:Users: Options/en")                                                                   | User Options configuration allows setting of parameters used globally for all users. Control the use of Captcha, registration allowed and type of registration, default user group new users, reset password or username counter, and new user registration email notice to administration.                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [Usuarios](https://docs.joomla.org/Help4.x:Users/es "Help4.x:Users/es")                                                                                           | The Users list is used to find, add, and edit users.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [Users: Viewing Access Levels](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/en "Help4.x:Users: Viewing Access Levels/en")                         | In this screen you have the ability to look at a list of your Access Levels and sort them in different ways. You can also edit and create Access Levels.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| [Users: Edit Viewing Access Level](https://docs.joomla.org/Help4.x:Users:_Edit_Viewing_Access_Level/en "Help4.x:Users: Edit Viewing Access Level/en")             | Access levels control which users can view which objects on your site. Objects include menu items, modules, categories, and component items (articles, contacts, and so on). Each object in the site is assigned to one access level. User groups are also assigned to each access level.If a user is a member of a group that in turn has permission for an access level, then that user can view all objects assigned to that access level. It is important to understand that user groups can be arranged in a parent-child hierarchy. If so, then a child group has access to all access levels that the parent group has access to. So you don't need to assign a child group access to levels that its parent group already has access to. |
| [Permissions for Group](https://docs.joomla.org/Help4.x:Permissions_for_Group/en "Help4.x:Permissions for Group/en")                                              | The Debug Permissions report maps out the exact permissions for any given user group across all assets on your Joomla! installation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [Permissions for User](https://docs.joomla.org/Help4.x:Permissions_for_User/en "Help4.x:Permissions for User/en")                                                 | The Debug Permissions report allows you to map out the exact permissions for any given user across all extensions on your Joomla installation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [Users: Groups](https://docs.joomla.org/Help4.x:Users:_Groups/en "Help4.x:Users: Groups/en")                                                                      | User Groups control what actions a user may take on the site and which objects a user can view. This screen allows you to create, view, edit, and delete User Groups.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [Users: New or Edit Group](https://docs.joomla.org/Help4.x:Users:_New_or_Edit_Group/en "Help4.x:Users: New or Edit Group/en")                                     | User groups play a central role in what a user can do and see on the site. Creating user groups is normally the first step in setting up the security system for your site.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [Mass Mail Users](https://docs.joomla.org/Help4.x:Mass_Mail_Users/en "Help4.x:Mass Mail Users/en")                                                                | The Mass Mail screen allows Users who are members of the "Super Administrator" group to send an email message to registered users for the site. Users can be selected based on groups.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| [Users: Edit Profile](https://docs.joomla.org/Help4.x:Users:_Edit_Profile/en "Help4.x:Users: Edit Profile/en")                                                    | In this screen, you have the ability to create a new user (if you clicked on the 'New' button in the User Manager), or edit an existing user (if you selected a user and clicked on the 'Edit' button in the User Manager, or clicked on the name of a user).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [User Notes: Categories](https://docs.joomla.org/Help4.x:User_Notes:_Categories/en "Help4.x:User Notes: Categories/en")                                           | This screen allows you to look at a list of your user note categories and sort them in different ways. You can also edit and create user note categories and access levels.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [User Notes: New or Edit Category](https://docs.joomla.org/Help4.x:User_Notes:_New_or_Edit_Category/en "Help4.x:User Notes: New or Edit Category/en")             | This is where you can add a new Category or edit an existing Category. Categories are used to organize the User Notes. Categories allow you to display related User notes together on a page and to filter User Notes in the User Notes Manager. All User Notes are assigned either to a Category that you create or to the special Category called 'Uncategorized'.                                                                                                                                                                                                                                                                                                                                                                             |
| [User Notes](https://docs.joomla.org/Help4.x:User_Notes/en "Help4.x:User Notes/en")                                                                               | User notes are pieces of information which can be assigned to registered users on your Joomla! site. These notes can contain for example comments about 'offending' or 'difficult' users etc.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [User Notes:New or Edit](https://docs.joomla.org/Help4.x:User_Notes:_New_or_Edit/en "Help4.x:User Notes: New or Edit/en")                                         | In this screen you can create an user note or edit an user note. The 'editor' will be the chosen 'editor' for the user editing the note. Examples: TinyMCE - JCE - Codemirror.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [Menu Item: Password Reset](https://docs.joomla.org/Help4.x:Menu_Item:_Password_Reset/en "Help4.x:Menu Item: Password Reset/en")                                  | Used to create a form which allows a user to reset their password with an email sent to the user's email associated with the account.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [Menu Item: User Profile](https://docs.joomla.org/Help4.x:Menu_Item:_User_Profile/en "Help4.x:Menu Item: User Profile/en")                                        | Used to create a form which allows a user to edit their profile settings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [Menu Item: Edit User Profile](https://docs.joomla.org/Help4.x:Menu_Item:_Edit_User_Profile/en "Help4.x:Menu Item: Edit User Profile/en")                         | Used to create a form which allows a user to edit their profile settings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [Menu Item: Registration Form](https://docs.joomla.org/Help4.x:Menu_Item:_Registration_Form/en "Help4.x:Menu Item: Registration Form/en")                         | Used to create a default User Registration form for user registration. Default form contains basic information: Name, Username, Password, and Email Address.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [Menu Item: Username Reminder Request](https://docs.joomla.org/Help4.x:Menu_Item:_Username_Reminder_Request/en "Help4.x:Menu Item: Username Reminder Request/en") | Used to create a form which allows a user to request an e-mail with their username.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
