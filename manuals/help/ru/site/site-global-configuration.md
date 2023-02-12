<!-- Filename: Help4.x:Site_Global_Configuration / Display title: Общие настройки -->

## Описание

The Global Configuration screen allows you to configure the Joomla site
with your personal settings. Settings made in this screen apply to the
whole site.

## Как открыть

- **Система **→** Настройки **→** Общие настройки**

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/3/3e/Help-4x-global-configuration-screen-ru.png/750px-Help-4x-global-configuration-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/3/3e/Help-4x-global-configuration-screen-ru.png/1125px-Help-4x-global-configuration-screen-ru.png 1.5x, https://docs.joomla.org/images/thumb/3/3e/Help-4x-global-configuration-screen-ru.png/1500px-Help-4x-global-configuration-screen-ru.png 2x"
data-file-width="2720" data-file-height="1700" width="750" height="469"
alt="Help-4x-global-configuration-screen-ru.png" />

## Form Fields

### Cайт

[Complete
screenshot.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Site/en "Help4.x:Site Global Configuration Site/en")

#### Параметры сайта

- **Site Name**. Enter the name of the website. This will be used in
  various locations (for example the Backend browser title bar and Site
  Offline pages).
- **Site Offline**. Select whether access to the Frontend is available.
  [Learn
  more.](https://docs.joomla.org/J3.x:Taking_the_website_temporarily_offline/en "J3.x:Taking the website temporarily offline/en")
  - **Сообщение при выключенном сайте**.
    - Пользовательское сообщение The message uses the value defined in
      the 'Custom Message' field.
    - По умолчанию (из языкового файла) The message uses the value
      defined in the site language ini file.
  - **Offline Image**. Select an image to be displayed on the offline
    page. Make sure the image is less than 400px wide.
- **Frontend Editing**. Select editing for modules and menu items.
- **Default Editor**. Select the default text editor. Registered Users
  will be able to change their preference in their personal details.
- **Default Captcha**. Select the default captcha for your site. You may
  need to enter required information in the [captcha
  plugin](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_CAPTCHA_Group/en "Chunk4x:Extensions Plugin Manager Edit CAPTCHA Group/en").
- **Default Access Level**. Select the default access level for new
  items.
- **Default List Limit**. Sets the default length of lists in the
  Backend for all users.
- **Default Feed Limit**. Select the number of content items to show in
  the feeds.
- **Feed Email Address**. The RSS and Atom newsfeeds include the
  author's email address.
  - E-mail автора: Use each author's email from
    [Users](https://docs.joomla.org/Help4.x:Users/en "Help4.x:Users/en")
    in the news feed.
  - E-mail сайта: Include the site [From Email](#fromemail) address for
    each article.

#### Параметры метаданных

- **Site Meta Description**. Enter a description of the overall website
  that is to be used by search engines.
- **Robots**. Robots instructions.
  - index, follow: Index this page and follow the links on this page.
  - noindex, follow: Do not index this page, but still follow the links
    on the page. For example, you might do this for a site map page
    where you want the links to be indexed but you don't want this page
    to show in search engines.
  - index, nofollow: Index this page, but do not follow any links on the
    page. For example, you might want to do this for an events calendar,
    where you want the page to show in search engines but you do not
    want to index each event.
  - noindex, nofollow: Do not index this page or follow any links on the
    page.
- **Метатег Rights**. Describe what rights others have to use this
  content. This is conveyed to search engines using the 'rights' meta
  tag in the HTML head.
- **Author Meta Tag**. Show the author meta tag when viewing articles.
- **Метатег Generator**. Показывать или скрывать метатег 'generator' в
  HTML-разметке страницы сайта с информацией об используемой версии
  Joomla.

#### Параметры SEO

- **Search Engine Friendly URLs**. Select if the URLs are optimised for
  Search Engines.
- **Перенаправлять URL**.
  - Apache и Litespeed - переименуйте файл 'htaccess.txt' в '.htaccess'
    <a href="https://httpd.apache.org/docs/2.4/howto/htaccess.html"
    class="external text" target="_blank"
    rel="nofollow noreferrer noopener">Learn more.</a>
  - IIS: переименуйте файл 'web.config.txt' в 'web.config'
  - NginX: настройте сервер согласно
    [инструкции](https://docs.joomla.org/Nginx/ru "Nginx/ru")
  - Other servers or if unsure: please consult your hosting company
- **Add Suffix to URL**. If yes, the system will add a suffix to the URL
  based on the document type.
- **Unicode Aliases**. Choose between transliteration and unicode
  aliases. Transliteration is the default.
- **Site Name in Page Titles**. Begin or end all Page Titles with the
  site name (for example, "My Site Name - My Article Name").

#### Параметры Cookie

- **Cookie Domain**. Domain to use when setting session cookies. Precede
  domain with '.' if cookie should be valid for all subdomains.
- **Cookie Path**. Path the cookie should be valid for.

### Система

[Complete
screenshot.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_System/en "Help4.x:Site Global Configuration System/en")

#### Параметры отладки

- **Debug System**. If enabled, diagnostic information, language
  translation, and SQL errors (if present) will be displayed. The
  information will be displayed at the foot of every page you view
  within the Joomla Backend and Frontend. It is not advisable to leave
  the debug mode activated when running a live website.
- **Debug Language**. Select if the debugging indicators \*\*...\*\*
  or ??...?? for the Joomla Language files will be displayed. Debug
  Language will work without Debug System being activated, but you will
  not get the additional detailed references that will help you correct
  any errors.
  - **Режим отображения**. Выберите режим отображения языка при отладке.

#### Параметры кэша

- **System Cache**. Enable caching and set caching level. [Learn
  more.](https://docs.joomla.org/Cache/en "Cache/en")
  - Conservative level: smaller system cache.
  - Progressive level: faster, bigger system cache, includes module
    renderers cache. Not appropriate for extremely large sites.
  - **Обработчик кэша**.
    - File: Native caching mechanism is file-based. Please make sure the
      cache folders are writable.
  - **Platform Specific Caching**. Enable when HTML output on mobile
    differs from other devices.
  - **Cache Time (minutes)**. The maximum length of time in minutes for
    a cache file to be stored before it is refreshed.
  - **Path to Cache Folder**. Specify a writable folder to store cache
    files if you do not wish to use the default folder.

#### Параметры сессии

- **Session Handler**. The mechanism by which Joomla identifies a User
  once they are connected to the website using non-persistent cookies.
  - Database: The database session handler is the default handler
    because it is the only one that Joomla can fully configure and
    control on its own.
  - Filesystem: The filesystem handler will be slightly more performant
    than the database handler, but it requires PHP to be configured
    properly otherwise it will crash and Joomla will be totally
    unusable.
    - **Путь к каталогу файлов сессии**. Enter a full filesystem path.
      Ensure the path has appropriate permissions for PHP to read and
      write files, and if 'session garbage collection' is enabled to
      delete files from it.If this path is not set, Joomla will rely on
      the PHP session.save_path INI configuration or fallback to the
      system temporary directory (as defined by the sys_get_temp_dir()
      PHP function).If neither of those paths are configured or the
      permissions are wrong then it's game over. To recover, edit the
      configuration.php file and set \$session_handler = 'database'.
  - Other handlers (APCu, Memcached, Redis, and WinCache) all rely on
    optional PHP extensions and may be available if your system supports
    them. APCu or WinCache may be no better than the "plain" filesystem
    option. The Memcached and Redis handlers are overkill for Joomla in
    a typical shared hosting environment. Those types of handlers
    succeed if you are deploying Joomla in a load balanced environment
    where multiple servers are involved and you need the session data
    for the application to be available across all servers.
- **Session Lifetime (minutes)**. Auto log out a User after they have
  been inactive for the entered number of minutes. Do not set too high.
- **Shared Sessions**. When enabled, a user's session is shared between
  the Frontend and Backend sections of the site. Note that changing this
  value will invalidate all existing sessions on the site.This is not
  available when the [Force HTTPS](#forcehttps) option is set to
  'Administrator Only'.
- **Отслеживать метаданные сессии**.
  - Да: Если установлено Да, метаданные сессии (включая имя
    пользователя, его ID и расширение, в котором выполняется действие)
    будут регистрироваться в таблице базы данных.
  - Нет: Если установлено Нет, функции, которые зависят от метаданных,
    будут недоступны.

### Сервер

[Complete
screenshot.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Server/en "Help4.x:Site Global Configuration Server/en")

#### Параметры Сервер

- **Path to Temp Folder**. Please specify a writable folder to store
  temporary files.
- **Gzip-сжатие страниц**.
  - Yes: Automatically compress the generated HTML pages with Gzip,
    making them smaller and increasing your site's speed score.
  - No: If your server is already doing that for you or if it conflicts
    with third party extensions.
- **Error Reporting**. This parameter sets the level of error reporting
  to be used by PHP on the Joomla site.
  - По умолчанию для системы: Leaves the level of error reporting to
    that set up in the server.
  - Нет: Switches off error reporting.
  - Упрощенные: Override the server setting to give a basic level of
    reporting.
  - Максимальные: Override the server setting to reporting of all
    errors.Should your Joomla site fail to the extent that it is not
    possible to use the administrator page to activate error reporting,
    you can switch on full error reporting by editing the
    'configuration.php' file. Changing the '\$error_reporting' parameter
    in that file to a value of 'maximum' is the equivalent to setting
    Error Reporting to 'Maximum'.
- **Force HTTPS**. Force site access in the selected areas to occur only
  with HTTPS (encrypted HTTP connections with the https:// protocol
  prefix) and also force the use of secure cookies. Note, you must have
  HTTPS enabled on your server to utilise this option.

#### Параметры местоположения

- **Website Time Zone**. Choose a city in the list to configure the date
  and time for display.

#### Параметры веб-служб

- **Включить CORS**. Включить или отключить использование дополнительных
  заголовков Cross-Origin Resource Sharing
  (<a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">CORS</a>), которые позволяют
  запущенным в браузере скриптам взаимодействовать с ресурсами другого
  источника.
  - **Access-Control-Allow-Origin**. Введите адреса источников,
    отправляемые обратно в ответ на предварительный запрос (по умолчанию
    \*).
  - **Access-Control-Allow-Headers**. Введите заголовки, отправляемые
    обратно в ответ на предварительный запрос (по умолчанию
    Content-Type,X-Joomla-Token).
  - **Access-Control-Allow-Methods**. Введите заголовки методов,
    отправляемые обратно в ответ на предварительный запрос (по умолчанию
    пусто).

#### Параметры прокси-сервера

- **Балансировщик нагрузки**. Включить или отключить использование
  балансировщика нагрузки, если сайт находится за балансировщиком
  нагрузки или обратным прокси-сервером. Использование параметра
  позволяет получать реальный IP-адрес пользователя сайта, который может
  регистрироваться в логе действий пользователей.
- **Исходящий прокси-сервер**. Включить или отключить использование
  исходящего прокси-сервера для доступа к ресурсам в сети.
  - **Имя хоста прокси-сервера**. Введите имя хоста или IP-адрес
    прокси-сервера.
  - **Порт прокси-сервера**.
  - **Логин прокси-сервера**. Введите логин прокси-сервера, если
    используется аутентификация.
  - **Пароль прокси-сервера**.

#### Параметры базы данных

- **Database Type**. The type of database in use, selected during the
  installation process.Не изменяйте значение параметра без необходимости
  (может потребоваться в случае переноса сайта на другой сервер).
- **Host**. The hostname for your database entered during the
  installation process.Не изменяйте значение параметра без необходимости
  (может потребоваться в случае переноса сайта на другой сервер).
- **Database Username**. The username for access to your database
  entered during the installation process.Не изменяйте значение
  параметра без необходимости (может потребоваться в случае переноса
  сайта на другой сервер).
- **Database Password**. The password to be used to access the
  database.Не изменяйте значение параметра без необходимости (может
  потребоваться в случае переноса сайта на другой сервер).
- **Database Name**. The name for your database entered during the
  installation process.Не изменяйте значение параметра без необходимости
  (может потребоваться в случае переноса сайта на другой сервер).
- **Database Tables Prefix**. The prefix used for your database tables,
  created during the installation process.Не изменяйте значение
  параметра без необходимости (может потребоваться в случае переноса
  сайта на другой сервер).
- **Шифрование соединения**.
  - По умолчанию (контролируется сервером)
  - Односторонняя аутентификация
    - **Проверять сертификат сервера**.
      - **Path to CA File**. File system path.
  - Двусторонняя аутентификация
    - **Path to Private Key File**. File system location.
    - **Path to Certificate File**. File system location.
    - **Проверять сертификат сервера**.
      - **Path to CA File**. File system path.
    - **Supported Cipher Suite (optional)**. No entry required (only
      recommended for experienced users) – for more details, see the
      documentation of your database.

#### Параметры почты

- **Отправка почты**.
  - Yes: Turn on mail sending.
  - No: Turn off mail sending. It is recommended to put the site offline
    when disabling the mail function.
- **Отключить рассылку**.
  - Yes: Disable the Mass Mail Users function.
  - No: Make the Mass Mail Users function active.
- **From Email**. The email address that will be used to send site
  email.
- **From Name**. Text displayed in the header "From:" field when sending
  a site email. Usually the site name.
- **Reply To Email**. The email address that will be used to receive end
  user(s) reply.
- **Reply To Name**. Text displayed in the header "To:" field when end
  user(s) replying to received email.
- **Mailer**. Select which mailer for the delivery of site email.

### Логирование

[Complete
screenshot.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Logging/en "Help4.x:Site Global Configuration Logging/en")

#### Параметры логирования

- **Путь к каталогу логов**. Введите путь к каталогу для хранения файлов
  логов. Рекомендуется не использовать общесистемные каталоги из
  соображений безопасности (например, '/tmp').
- **Логировать все**. Включить или отключить функцию логирования событий
  по всем категориям, за исключением устаревшего API.
- **Log Deprecated API**. Logs deprecated APIs.

#### Дополнительные параметры

- **Log Priorities**. Can be used to manage custom logging. Select the
  events you want to see in the log file. Default is 'All'. The item(s)
  can be selected/deselected by clicking the dropdown list.
- Введите заголовки категорий для логирования ('например', 'database',
  'databasequery', 'database-error', 'deprecated', 'jerror', 'update',
  'updater'). Если поле оставить пустым, пользовательское логирование
  будет отключено.
- **Log Category Mode**. Sets the mode for the list of log categories
  above.

### Фильтры текста

[Complete
screenshot.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Text_Filters/en "Help4.x:Site Global Configuration Text Filters/en")

Параметры фильтров применяются ко всем полям текстового редактора для
выбранных групп пользователей.

С помощью фильтров текста вы можете обеспечить необходимый уровень
контроля над HTML-кодом страниц, которые создают пользователи. Вы можете
установить строгий или, например, более свободный уровень контроля. Как
правило, значения по умолчанию обеспечивают качественную защиту от
потенциальных атак.

### Права доступа

[Complete
screenshot.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Permissions/en "Help4.x:Site Global Configuration Permissions/en")

Manage the permission settings for user groups.

- **Site Login**. Site Login for users in the selected group.
- **Administrator Login**. Administrator Login for users in the selected
  group.
- **Web Services Login**. Web Services Login for users in the selected
  group.
- **Offline Access**. Allows users in the selected group to access to
  the Frontend site when site is offline.
- **Super User**. Allows users in the selected selected group to perform
  any action over the whole site regardless of any other permission
  settings.
- **Configure Options Only**. Allows users in the group to edit the
  options except the permissions of any extension.
- **Access Administration Interface**. Allows users in the selected
  group to access all of the administration interface except Global
  Configuration.
- **Create**. Allows users in the selected group to create any content
  in any extension.
- **Delete**. Allows users in the selected group to delete any content
  in any extension.
- **Edit**. Allows users in the selected group to edit any content in
  any extension.
- **Edit State**. Allows users in the selected group to edit the state
  of any content in any extension.
- **Edit Own**. Allows users in the selected group to edit any content
  they own in any extension.
- **Edit Custom Field Value**. Allows users in the selected group to
  edit any value of custom fields submitted in any extension.

Изменения значений действий применяются для данной и дочерних групп
пользователей, компонентов и всего содержимого сайта.

- **Запрещено** переопределяет любое унаследованное значение, а также
  значения во всех дочерних группах, компонентах и содержимом. В случае
  противоречия в значениях, **Запрещено** будет иметь приоритет.
- Суммарное значение действия, для которого выбрано **Не определено**,
  будет трактоваться как **Запрещено**, но его можно будет
  переопределить для дочерних групп, компонентов, категорий и элементов.

## Панель инструментов

At the top of the page you will see the toolbar shown in the
[Screenshot](#screenshot) above.

- **Сохранить**. Сохраняет данный пункт меню и оставляет данный экран
  открытым.
- **Сохранить и закрыть**. Сохраняет данный пункт меню и закрывает
  данный экран.
- **Закрыть**. Закрывает текущий экран и возвращает к предыдущему
  экрану, без сохранения внесенных изменений.
- **Toggle Inline Help**. Show help text below some options.
- **Справка**. Открывает экран помощи.

## Быстрые советы

- Most of these settings can be set once and then left alone.
- If major modifications need to be made, then consider taking the site
  offline to test it and to make sure everything is in working order.
- The settings are saved in '\[Joomla\]/configuration.php'. You have to
  either activate the FTP-layer or make the 'configuration.php' file
  writable to save your changes.

## Связанная информация

- [Joomla! Основы резервного
  копирования](https://docs.joomla.org/Backup_Basics_for_a_Joomla!_Web_Site/ru "Backup Basics for a Joomla! Web Site/ru")
- [Контрольный список по
  безопасности](https://docs.joomla.org/Security_Checklist/ru "Security Checklist/ru")
- <img src="https://docs.joomla.org/images/4/49/Compat_icon_3_x_long.png"
  decoding="async" data-file-width="75" data-file-height="16" width="75"
  height="16" alt="Joomla 3.x" />
