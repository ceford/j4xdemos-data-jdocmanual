<!-- Filename: Help4.x:Media:_Options / Display title: Медиа-менеджер: Настройки -->

## Описание

Media Options configuration allows setting of parameters used globally
for Media. Control the file types allowed for uploading, MIME type
check, MIME type blacklisting, and more options.

## Как открыть

**Контент **→** Медиа-менеджер**

- click the **Options** toolbar button

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/5/5a/Help-4x-Media-Options-screen-ru.png/800px-Help-4x-Media-Options-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/5a/Help-4x-Media-Options-screen-ru.png/1200px-Help-4x-Media-Options-screen-ru.png 1.5x, https://docs.joomla.org/images/thumb/5/5a/Help-4x-Media-Options-screen-ru.png/1600px-Help-4x-Media-Options-screen-ru.png 2x"
data-file-width="2720" data-file-height="1700" width="800" height="500"
alt="Help-4x-Media-Options-screen-ru.png" />

## Form Fields

### Основные

- **Максимальный размер**. Введите максимальный размер файла для
  загрузки на сервер (Мбайт). Если установлено 0, будут сняты все
  ограничения.
- **Каталог файлов**. Введите путь к каталогу с файлами относительно
  корневого каталога сайта (по умолчанию images).Changing to another
  path than the default 'images' may break your links. Do not start the
  path with a slash.
- **Каталог изображений**. Введите путь к каталогу с изображениями
  относительно корневого каталога сайта (по умолчанию images).This path
  has to be the same as path to files (default) or to a subfolder of the
  path to file folder. Do not start the path with a slash.
- **Ограничение загрузки**. Включить или отключить функцию ограничения
  загрузки файлов для пользователей с правами ниже уровня Менеджер, если
  'Fileinfo' или 'MIME Magic' не установлены.
  - **Разрешенные расширения**. Введите разрешенные расширения файлов
    для загрузки на сервер. Обратите внимание, что пользователи с
    правами ниже уровня Менеджер не могут загружать файлы на сервер.
  - **Проверка MIME-типов**. Включить или отключить функцию проверки
    MIME-типов файлов с помощью 'Fileinfo' или 'MIME Magic'. Параметр
    необходимо отключить, если отображаются ошибки определения
    MIME-типа.
- **Legal Image Extensions (File Types)**. Введите разрешенные
  расширения изображений для загрузки на сервер. Параметр предназначен
  для проверки заголовков изображений.
- **Legal Audio Extensions (File Types)**. Введите разрешенные
  расширения аудио для загрузки на сервер. Параметр предназначен для
  проверки заголовков аудио.
- **Legal Video Extensions (File Types)**. Введите разрешенные
  расширения видео для загрузки на сервер. Параметр предназначен для
  проверки заголовков видео.
- **Legal Document Extensions (File Types)**. Введите разрешенные
  расширения документов для загрузки на сервер. Параметр предназначен
  для проверки заголовков документов.
- **Игнорируемые расширения**. Введите игнорируемые расширения файлов
  для проверки MIME-типа и ограничения загрузки на сервер.
- **Разрешенные MIME-типы.** Введите разрешенные MIME-типы файлов для
  загрузки на сервер.

### Права доступа

This section lets you set up the default [Access Control
List](https://docs.joomla.org/Access_Control_List/en "Access Control List/en")
permissions for all media.

<img
src="https://docs.joomla.org/images/thumb/1/1b/Help-4x-Media-Options-permissions-subscreen-ru.png/600px-Help-4x-Media-Options-permissions-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/1b/Help-4x-Media-Options-permissions-subscreen-ru.png/900px-Help-4x-Media-Options-permissions-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/1/1b/Help-4x-Media-Options-permissions-subscreen-ru.png/1200px-Help-4x-Media-Options-permissions-subscreen-ru.png 2x"
data-file-width="1979" data-file-height="1478" width="600" height="448"
alt="Help-4x-Media-Options-permissions-subscreen-ru.png" />

To change the permissions for media, do the following.

1.  Select the **Group** by clicking its title located on the left.
2.  Find the desired **Action**.
    - **Configure ACL & Options**. Users can edit the options and
      permissions.
    - **Configure Options Only**. Users can edit the options exept the
      permissions.
    - **Access Administration Interface**. Users can access user
      administration interface.
    - **Create**. Users can create media.
    - **Delete**. Users can delete media.
    - **Edit**. Users can edit media.
3.  Select the desired permission for the action you wish to change.
    - **Inherited**. Inherited for users in this Group from the [Global
      Configuration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/en#permissions "Help4.x:Site Global Configuration/en")
      permissions.
    - **Allowed**. Allowed for users in this Group. Note: If this action
      is Denied at one of the higher levels, the Allowed permission here
      will not take effect. A Denied setting cannot be overridden.
    - **Denied**. Denied for users in this Group.
4.  Click **Save** in **Toolbar** at top. When the screen refreshes, the
    Calculated Setting column will show the effective permission for
    this Group and Action.

## Панель инструментов

At the top of the page you will see the toolbar shown in the
[Screenshot](#screenshot) above.

- **Save**. Saves the Media options and stays in the current screen.
- **Save & Close**. Saves the Media options and closes the current
  screen.
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Toggle Inline Help**. Show help text below some options.
- **Help**. Opens this help screen.

## Быстрые советы

- If you are a beginning user, you can just keep the default values here
  until you learn more about using global options.
- If you are an advanced user, you can save time by creating good
  default values here.

## Связанная информация

- Related Help screen:
  [Media](https://docs.joomla.org/Help4.x:Media/en "Help4.x:Media/en").
- Tutorial: [Managing
  Media](https://docs.joomla.org/J4.x:Managing_Media/en "J4.x:Managing Media/en").
