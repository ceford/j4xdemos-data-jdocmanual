<!-- Filename: Help4.x:Media:_Options / Display title: Multimedia: Opciones -->

## Descripción

Media Options configuration allows setting of parameters used globally
for Media. Control the file types allowed for uploading, MIME type
check, MIME type blacklisting, and more options.

## Cómo Acceder

**Contenido **→** Multimedia**

- Clic el botón **Opciones** en la Barra de Herramientas.

## Captura de pantalla

<img
src="https://docs.joomla.org/images/thumb/0/09/Help-4x-Media-Options-screen-es.png/800px-Help-4x-Media-Options-screen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/09/Help-4x-Media-Options-screen-es.png/1200px-Help-4x-Media-Options-screen-es.png 1.5x, https://docs.joomla.org/images/thumb/0/09/Help-4x-Media-Options-screen-es.png/1600px-Help-4x-Media-Options-screen-es.png 2x"
data-file-width="2720" data-file-height="1700" width="800" height="500"
alt="Help-4x-Media-Options-screen-es.png" />

## Campos del formulario

### Multimedia

- **Peso máximo (en MB)**. Use el valor '0' para que sea ilimitado.
  Nota: El servidor también puede tener configurado un límite máximo, el
  cual, no lo controla Joomla.
- **Ruta al directorio de archivos**. Introduzca la ruta al directorio
  de archivos relativo al directorio raíz de su espacio web.Cambiándolo
  a otra ruta distinta a 'images' puede romper sus enlaces. No empiece
  la ruta con una barra.
- **Ruta al directorio de imágenes**. Introduzca la ruta al directorio
  de imágenes, relativo al directorio raíz de su espacio web.Esta ruta
  debe ser la misma que se usa para los archivos (predeterminado) o
  hacia una subcarpeta en ruta a la de archivos. No empiece la ruta con
  una barra.
- **Restringir subidas**. Se restringen las subidas, si el 'Fileinfo' o
  'MIME Magic' no están instalados, para que los usuarios con rango de
  usuario inferior a gestor puedan subir archivos del tipo imagen.
  - **Extensiones permitidas**. Restrinja las subidas a los archivos de
    la lista para los usuarios con nivel de acceso inferior al de
    gestor.
  - **Comprobar los tipos de MIME**. Usar el 'Fileinfo' o el 'MIME
    Magic' para intentar verificar archivos. Intente deshabilitarlo si
    recibe errores relacionados con los tipos de MIME.
- **Legal Image Extensions (File Types)**. Extensiones de imagen (tipos
  de archivo) permitidos para su subida (separados por una coma). Se usa
  para comprobar si los encabezados de la imagen son válidos.
- **Legal Audio Extensions (File Types)**. Extensiones de audio (tipos
  de archivo) que puede cargar (separadas por comas). Se utilizan para
  comprobar si hay encabezados de audio válidos.
- **Legal Video Extensions (File Types)**. Extensiones de video (tipos
  de archivo) que puede cargar (separadas por comas). Estos se utilizan
  para verificar los encabezados de video válidos.
- **Legal Document Extensions (File Types)**. Extensiones de documento
  (tipos de archivo) que puede cargar (separadas por comas). Se utilizan
  para comprobar si hay encabezados de documentos válidos.
- **Extensiones ignoradas**. Extensiones de archivo ignoradas para
  comprobar el tipo de MIME y las subidas restringidas.
- **Tipos de MIME permitidos.** Una lista de tipos de MIME permitidos
  para su subida.

### Permisos

This section lets you set up the default [Access Control
List](https://docs.joomla.org/Access_Control_List/en "Access Control List/en")
permissions for all media.

<img
src="https://docs.joomla.org/images/thumb/d/df/Help-4x-Media-Options-permissions-subscreen-es.png/600px-Help-4x-Media-Options-permissions-subscreen-es.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/df/Help-4x-Media-Options-permissions-subscreen-es.png/900px-Help-4x-Media-Options-permissions-subscreen-es.png 1.5x, https://docs.joomla.org/images/thumb/d/df/Help-4x-Media-Options-permissions-subscreen-es.png/1200px-Help-4x-Media-Options-permissions-subscreen-es.png 2x"
data-file-width="2001" data-file-height="1349" width="600" height="404"
alt="Help-4x-Media-Options-permissions-subscreen-es.png" />

To change the permissions for media, do the following.

1.  Selecciona el **Grupo** haciendo clic en el título que se encuentra
    a la izquierda.
2.  Find the desired **Action**.
    - **Configure ACL & Options**. Users can edit the options and
      permissions.
    - **Configure Options Only**. Users can edit the options exept the
      permissions.
    - **Acceso a la interfaz de administración**. Los usuarios pueden
      tener acceso a la interfaz de administración de usuarios.
    - **Create**. Users can create media.
    - **Delete**. Users can delete media.
    - **Edit**. Users can edit media.
3.  Select the desired permission for the action you wish to change.
    - **Inherited**. Inherited for users in this Group from the [Global
      Configuration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/en#permissions "Help4.x:Site Global Configuration/en")
      permissions.
    - **Permitido**. Permitido para los usuarios de este Grupo. Note: If
      this action is Denied at one of the higher levels, the Allowed
      permission here will not take effect. A Denied setting cannot be
      overridden.
    - **Denegado**. Denegado para los usuarios de este Grupo.
4.  Has clic en **Guardar** en la **Barra de herramientas** en la parte
    superior. Cuando la pantalla se actualiza, la columna Configuración
    Calculada mostrará el permiso efectivo para este Grupo y Acción.

## Barra de herramientas

At the top of the page you will see the toolbar shown in the
[Screenshot](#screenshot) above.

- **Save**. Saves the Media options and stays in the current screen.
- **Save & Close**. Saves the Media options and closes the current
  screen.
- **Cerrar**. Cierra la pantalla actual y vuelve a la pantalla anterior
  sin guardar las modificaciones realizadas.
- **Toggle Inline Help**. Show help text below some options.
- **Ayuda**. Se abre esta pantalla de ayuda.

## Consejos Rápidos

- If you are a beginning user, you can just keep the default values here
  until you learn more about using global options.
- If you are an advanced user, you can save time by creating good
  default values here.

## Información relacionada

- Related Help screen:
  [Media](https://docs.joomla.org/Help4.x:Media/en "Help4.x:Media/en").
- Tutorial: [Managing
  Media](https://docs.joomla.org/J4.x:Managing_Media/en "J4.x:Managing Media/en").
