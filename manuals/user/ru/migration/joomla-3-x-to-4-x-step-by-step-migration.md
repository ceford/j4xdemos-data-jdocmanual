<!-- Filename: Joomla_3.x_to_4.x_Step_by_Step_Migration / Display title: Пошаговая миграция с Joomla 3.x на 4.x -->

<img
src="https://docs.joomla.org/images/thumb/4/41/Stop_hand_nuvola.svg.png/25px-Stop_hand_nuvola.svg.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/41/Stop_hand_nuvola.svg.png/38px-Stop_hand_nuvola.svg.png 1.5x, https://docs.joomla.org/images/4/41/Stop_hand_nuvola.svg.png 2x"
data-file-width="40" data-file-height="40" width="25" height="25"
alt="Stop hand nuvola.svg.png" />Warning!

В этом руководстве предполагается, что у вас уже Joomla 3.10.x. Если вы
используете более раннюю версию, убедитесь, что вы обновились до Joomla
3.10, прежде чем переходить на Joomla 4. There is no rush. Make sure all
your extensions are ready for Joomla 4.x. Joomla 3.10.x will be
supported until 16 August 2023.

  
Ниже приведены пошаговые инструкции по переносу вашего сайта 3.10.x на
Joomla! 4.x. Хотя существуют сотни различных сценариев, это даст вам
базовое понятие, которому нужно следовать. Скорее всего миграция может
усложнится, если будут установлены сторонние расширения. Предлагаем вам
связаться с разработчиками сторонних расширений, установленных на вашем
сайте Joomla, чтобы узнать, как они могут перенести свои расширения.

## Вступление

Переход с Joomla! 3.10.x на 4.x считается мини-миграцией. Это связано с
тем, что Встроенные в Joomla! расширения будут обновляться «в один клик»
через компонент обновления в административной части Joomla. Многие
сторонние расширения также можно обновить в один клик. Некоторые нет.
Вам нужно проверить каждое расширение что бы определить по какому пути
будет происходить его переход с 3.10 на 4.x. Если вы еще этого не
сделали, возможно, вам будет интересно перед выполнением следующих шагов
прочитать [Миграция шаг за шагом -
Самооценка](https://docs.joomla.org/Migration_Step_by_Step_Self_Assessment "Special:MyLanguage/Migration Step by Step Self Assessment")
and [Планирование миграции с 3.10 на
4.x](https://docs.joomla.org/Planning_for_Mini-Migration_-_Joomla_3.10.x_to_4.x "Special:MyLanguage/Planning for Mini-Migration - Joomla 3.10.x to 4.x").

Встроенные расширения Joomla!:

- Категории
- Материалы
- Меню
- Модули (основные модули - не сторонние)
- Баннеры
- Поля
- История контента
- Контакты
- Сообщения
- Ленты новостей
- Перенаправления
- Поиск (Убран в 4.x. В дальнейшем будет использоваться Умный поиск. См.
  Примечания в разделе «Оценка каждого расширения»)
- Умный поиск
- Теги
- Веб-ссылки (убран, но ваш сайт может их использовать, и он будет
  перенесен. См. Примечания в разделе «Оценка каждого расширения»)

## Шаг за шагом

### Настроить место разработки

1.  Прежде чем продолжить, убедитесь, что у вас установлена ​​последняя
    версия Joomla 3.10.x.
2.  Сделайте резервную копию вашего действующего сайта 3.10.x. Вы можете
    использовать рекомендованный инструмент (см. «Предлагаемые
    инструменты» внизу страницы) или сделайте это вручную.
    - [Joomla! Основы резервного
      копирования](https://docs.joomla.org/Backup_Basics_for_a_Joomla!_Web_Site "Special:MyLanguage/Backup Basics for a Joomla! Web Site")
    - [Основные рекомендации по резервному копированию
      сайтов?](https://docs.joomla.org/What_are_the_best_practices_for_site_backups%3F "Special:MyLanguage/What are the best practices for site backups?")
3.  Прежде чем продолжить, убедитесь, что ваша среда соответствует
    <a href="https://downloads.joomla.org/technical-requirements"
    class="external text" target="_blank"
    rel="noreferrer noopener">technical requirements for Joomla 4</a>.
4.  Создайте новую базу данных и пользователя для восстановления вашего
    сайта 3.10.x.
5.  Создайте тестовый сайт или зону сборки для работы и восстановите
    резервную копию вашего сайта 3.10.x в одном из следующих мест:
6.  \* Поддомен.
7.  \* Подкаталог.
8.  \* Локальное устройство. Joomla имеет подробное руководство по
    установке
    <a href="http://sourceforge.net/projects/xampp/" class="external text"
    target="_blank" rel="nofollow noreferrer noopener">XAMPP</a> в
    [XAMPP](https://docs.joomla.org/XAMPP "XAMPP").
    <a href="https://www.wampserver.com/en/" class="external text"
    target="_blank" rel="nofollow noreferrer noopener">WAMP</a>,
    <a href="https://www.mamp.info/en/windows/" class="external text"
    target="_blank" rel="nofollow noreferrer noopener">MAMP</a>,
    <a href="https://sourceforge.net/projects/lampas/" class="external text"
    target="_blank" rel="nofollow noreferrer noopener">LAMP</a> так же
    подходящие альтернативы.
9.  \* Новая учетная запись хостинга на временном домене в корне. (Если
    вы хотите сменить хосты в процессе миграции.)
10. \*\* Восстановление сайта на локальном устройстве. См. [Установка
    Joomla
    локально](https://docs.joomla.org/Installing_Joomla_locally "Special:MyLanguage/Installing Joomla locally")
    и [Настройка вашей рабочей станции для разработки
    Joomla](https://docs.joomla.org/Setting_up_your_workstation_for_Joomla_development "Special:MyLanguage/Setting up your workstation for Joomla development").
11. \*\* Восстановление сайта с помощью инструмента, указанного внизу
    страницы. (Прочтите документацию разработчика.)
12. В вашем тестовом месте обновите Joomla! 3.10.x до последней версии.
13. Убедитесь, что у вас установлена последняя схема базы данных,
    обновленная до последней версии 3.10.x, перейдя на вкладку
    **Менеджер расширений(Extension Manager) **→** Базы
    данных(Database)** Если ваша схема устарела, как показано на
    следующем изображении, нажмите кнопку «Исправить»:

<img
src="https://docs.joomla.org/images/thumb/6/61/J310-admin-extension-database-fix-en.png/800px-J310-admin-extension-database-fix-en.png"
class="thumbborder" decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/61/J310-admin-extension-database-fix-en.png/1200px-J310-admin-extension-database-fix-en.png 1.5x, https://docs.joomla.org/images/thumb/6/61/J310-admin-extension-database-fix-en.png/1600px-J310-admin-extension-database-fix-en.png 2x"
data-file-width="2560" data-file-height="812" width="800" height="254"
alt="J310-admin-extension-database-fix-en.png" />

1.  Пустая корзина: есть ли у вас материалы в корзине? Если да, удалите
    их (и любые соответствующие медиа файлы, которые могут быть связаны
    с ними, если они не используются где-либо еще на сайте). Оставленные
    в корзине материалы (категории и пункты меню) могут вызвать проблемы
    во время миграции.
2.  Тест.
3.  Сделайте резервную копию снова.

### Оцените каждое расширение

В своем <a
href="https://docs.joomla.org/index.php?title=Planning_for_Mini-Migration_-_Joomla_3.10_to_4.x&amp;action=edit&amp;redlink=1"
class="new"
title="Planning for Mini-Migration - Joomla 3.10 to 4.x (page does not exist)">Планирование
миграции с 3.10 на 4.x</a>, вы определили, какие сторонние расширения
останутся или будут использоваться и как они будут переноситься. В этой
части «Шаг за шагом» вы будете широко использовать два разных раздела
сайта; Проверка перед обновлением в
**Компоненты(Components) **→** Обновление Joomla!(Joomla! Update)** и
**Менеджер расширений(Extensions) **→** Менеджер
расширений(Manage) **→** Управление(Manage)**. Вы будете просматривать
каждое расширение, установленное на вашем сайте и определять, нужно ли
его обновить до последней версии или надо удалить.

1.  Using the **Pre-Update Check**: in order to use the Pre-Update
    Check, you will need to set the Joomla! Update component to
    Joomla 4. To do this follow:
2.  Go to **Components **→** Joomla Update**. (It should say no updates
    found. If it doesn’t, update Joomla to the latest version (must be
    3.10.x) and test. Then do another backup.) Click on the Options
    button at the top right corner.
3.  Select *Joomla Next* from the drop-down for Update Channel.<img
    src="https://docs.joomla.org/images/thumb/7/72/Migration_J3toJ4_update_channel-en.png/800px-Migration_J3toJ4_update_channel-en.png"
    class="thumbborder" decoding="async"
    srcset="https://docs.joomla.org/images/7/72/Migration_J3toJ4_update_channel-en.png 1.5x"
    data-file-width="1000" data-file-height="384" width="800" height="307"
    alt="Migration J3toJ4 update channel-en.png" />
4.  Click Save & Close
5.  You will then see your Installed Joomla Version, the latest Joomla!
    version and the URL for the update package. Joomla will show you the
    requirements again for Joomla 4. If it flags that you have either an
    incompatible system or extensions it will tell you here. Take a
    moment to review this page.<img
    src="https://docs.joomla.org/images/thumb/3/3a/J310-admin-update_to_4-pre_update_check-en.png/800px-J310-admin-update_to_4-pre_update_check-en.png"
    class="thumbborder" decoding="async"
    srcset="https://docs.joomla.org/images/3/3a/J310-admin-update_to_4-pre_update_check-en.png 1.5x"
    data-file-width="1200" data-file-height="559" width="800" height="373"
    alt="J310-admin-update to 4-pre update check-en.png" />
6.  Look at the Pre-Update Check and the Extension Pre-Update Check in
    the Pre-Update Check tab of the Joomla Update component. If any
    extension that isn’t in your planning is listed here, add it to your
    list of extensions to investigate.
7.  If you migrated from Joomla! 2.5 to 3.x in the past, there may be
    some leftover extensions that need to be cleaned up. The following
    are older 2.5 or 3.x extensions that need to be uninstalled before
    updating to Joomla 4:
    - plg_content_geshi
    - Bluestork Administrator Template
    - Beez_20
    - Beez5
    - Atomic

    1.  When it comes to templates, uninstall all core frontend or
        backend templates except Protostar and Beez3 (frontend
        templates) and Isis or Hathor (administrator templates). **NOTE:
        Protostar is NOT compatible with Joomla 4**. Upon migration it
        will disappear. You'll need to have one template selected as
        "default" and you can use Protostar or Beez3. Protostar will
        disappear upon migration to Joomla 4.x.
    2.  If you come across other files that need to be uninstalled,
        please add them to this page. This is a wiki so anyone can add
        to the page. Thank you in advance for your service.
8.  You will notice the tags for whether an extension is compatible or
    not. These tags generally tell a true story if they say No or Yes.
    If they say “Missing Compatibility Tag” it means that the extension
    developer didn’t use a tag in their extension so we don’t know if it
    is or isn’t compatible with Joomla 4. Talk to the developer to
    verify.
9.  **Update Extensions**: update any extensions that you will keep in
    your website. In Joomla! 3.10.x you can go to **Extension
    Manager **→** Update tab** and click **Find Updates** which will add
    a tooltip in the Version column, under the Manage tab, giving some
    compatibility information from the backend. This functionality only
    supports extensions that update via the Extension Manager Update
    tab. If you have extensions installed that do not use the Joomla
    extension update they need to be assessed manually as detailed
    below. The same goes for those extensions that have a tooltip. You
    will still need to check the type of package and migration path with
    the extension developer to verify how to upgrade/migrate.
10. Investigate and Uninstall Extensions Extensions: go to **Extension
    Manager **→** Manage**
11. Click the Button *Search Tools* to show the filter options
12. Select Package from the *Select Type* drop-down.<img
    src="https://docs.joomla.org/images/thumb/5/50/J310-admin-extension-manage-package-en.png/800px-J310-admin-extension-manage-package-en.png"
    decoding="async"
    srcset="https://docs.joomla.org/images/thumb/5/50/J310-admin-extension-manage-package-en.png/1200px-J310-admin-extension-manage-package-en.png 1.5x, https://docs.joomla.org/images/5/50/J310-admin-extension-manage-package-en.png 2x"
    data-file-width="1502" data-file-height="658" width="800" height="350"
    alt="J310-admin-extension-manage-package-en.png" />Selecting Package
    first is recommended because if there is something you need to
    uninstall in a package, it will automatically uninstall the
    associated Modules, Plugins, or anything else in the package at one
    time.
13. Uninstall any Packages that are no longer needed or will not be
    migrating to Joomla 4.
14. Repeat this process of going through the Manage tab for all Types in
    the drop-down: Component, File, Language, Library, Module, Plugin
    and Template. If the Author states Joomla! Project, then leave those
    extensions alone. For all others, make sure that you uninstall those
    not in use or not compatible with Joomla! 4.x. **NOTE!** You will
    not be able to uninstall any template that is set as default. You
    will need to select a Core supported template like Beez3 or
    Protostar and then uninstall the template if you need to do so.  
    *Another reminder:* **Protostar is not compatible with Joomla 4.x**.
    Upon migration it will disappear. Selecting it as default simply
    gets you to Joomla 4.x.
15. Make a note of any versions of Packages and Components currently
    running that you will be keeping on your site. You can copy/paste
    them into a document for reference.
16. For any extensions you are keeping but don't use the Extension
    Manager to one-click update
    (**Extensions **→** Manage **→** Update**) update all extensions to
    the latest versions.
17. Before and as you update, note if the extensions have both 3.10.x &
    4.x versions in the same package. If so, they will be fine to
    "one-click update." If not, and 3.10 and 4.x have different
    packages, you need to look at them case by case. They will normally
    fall into one of the following scenarios:
    - The extension has separate packages but upon upgrading to 4.x,
      they automatically detect this and still work. Make sure the
      developer confirms this.
    - The extension has separate packages that need to be uninstalled in
      3.10.x and then installed with the Joomla 4.x version once the
      site is migrated. An example of this might be a content plugin. It
      is very simple to uninstall it in 3.10.x and then install it again
      in 4.x.
    - See [Template
      Considerations](https://docs.joomla.org/Template_Considerations_During_Migration "Special:MyLanguage/Template Considerations During Migration")
      for more specific information on templates and [Converting a
      previous Joomla! Version
      template](https://docs.joomla.org/J3.x:Converting_A_Previous_Joomla!_Version_Template "Special:MyLanguage/J3.x:Converting A Previous Joomla! Version Template")

#### Notes on Search (com_search)

Search (com_search) will be decoupled in Joomla 4.x. Search (com_search)
will migrate to Joomla 4. After migration, you'll need to update it to
the Joomla 4.x version via com_installer. It will continue to be
maintained, but more the same way a third-party extension is by
receiving updates via com_installer. It is recommended to use Smart
Search (com_finder) going forward. Search will still be available at
<a href="https://extensions.joomla.org/category/official-extensions/"
class="external free" target="_blank"
rel="noreferrer noopener">https://extensions.joomla.org/category/official-extensions/</a>.

#### Notes on Weblinks

Weblinks was decoupled back in Joomla 3.4. If it was in use on a 2.5
site, the migration process would note this and migrate the Weblinks
component and data. For the migration from 3.10.x to 4.x, it will be the
same. It is still available and maintained on the JED at
<a href="https://extensions.joomla.org/category/official-extensions/"
class="external text" target="_blank" rel="noreferrer noopener">Official
Extensions</a>.

#### Notes on Legacy Routing

Legacy routing will not be available in Joomla 4.x. Only Modern will be
available. When you do the migration, if you are using Legacy routing,
the system will automatically change them to Modern routing. You will
want to run a broken link checker on your site after migrating to Joomla
4.x and *before you go live*.

### Going to Joomla! 4.x

Once you have either updated or uninstalled your third-party extensions
so that only those compatible with Joomla! 4 remain in your
installation, continue with the following steps:

1.  Go to **System **→** Global Configuration **→** Server tab** and
    turn Error Reporting from System Default to Maximum. Make sure to
    Save & Close. <img
    src="https://docs.joomla.org/images/thumb/8/84/J310-system-global-config-server-tab-en.png/500px-J310-system-global-config-server-tab-en.png"
    class="thumbborder" decoding="async"
    srcset="https://docs.joomla.org/images/thumb/8/84/J310-system-global-config-server-tab-en.png/750px-J310-system-global-config-server-tab-en.png 1.5x, https://docs.joomla.org/images/thumb/8/84/J310-system-global-config-server-tab-en.png/1000px-J310-system-global-config-server-tab-en.png 2x"
    data-file-width="1496" data-file-height="1002" width="500" height="335"
    alt="J310-system-global-config-server-tab-en.png" />
2.  Take another backup.
3.  Go to **Components **→** Joomla Update**. (It should say no updates
    found. If it doesn’t, update Joomla to the latest version and test.
    Then do another backup.) Click on the Options button at the top
    right corner.
4.  Select *Joomla Next* from the drop-down for Update Channel.<img
    src="https://docs.joomla.org/images/thumb/f/fd/J310-component-joomla-update-select-support-en.png/500px-J310-component-joomla-update-select-support-en.png"
    class="thumbborder" decoding="async"
    srcset="https://docs.joomla.org/images/thumb/f/fd/J310-component-joomla-update-select-support-en.png/750px-J310-component-joomla-update-select-support-en.png 1.5x, https://docs.joomla.org/images/thumb/f/fd/J310-component-joomla-update-select-support-en.png/1000px-J310-component-joomla-update-select-support-en.png 2x"
    data-file-width="1382" data-file-height="772" width="500" height="279"
    alt="J310-component-joomla-update-select-support-en.png" />
5.  Click Save & Close.
6.  You will then see your Installed Joomla Version, the Latest Joomla!
    version and the URL for the update package. Joomla will show you the
    requirements again for Joomla 4. If it flags that you have either an
    incompatible system or extensions it will tell you here. Take a
    moment to review this page.<img
    src="https://docs.joomla.org/images/thumb/a/a8/J310-to-j4-dev-update-found-en.png/800px-J310-to-j4-dev-update-found-en.png"
    class="thumbborder" decoding="async"
    srcset="https://docs.joomla.org/images/thumb/a/a8/J310-to-j4-dev-update-found-en.png/1200px-J310-to-j4-dev-update-found-en.png 1.5x, https://docs.joomla.org/images/a/a8/J310-to-j4-dev-update-found-en.png 2x"
    data-file-width="1466" data-file-height="1079" width="800" height="589"
    alt="J310-to-j4-dev-update-found-en.png" />
7.  If the update is not showing up, go to **Extension
    manager **→** Update** and press Purge Cache from the toolbar. Now
    the update to Joomla! 4 should show up.
8.  Cross your fingers, and make sure you have that backup available in
    case.
9.  Click the Install the Update button.
10. Make tea whilst the status bar loads to fully green. The amount of
    time this takes is dependent on your site, Internet connection and
    server speed. The process takes about two minutes. When the update
    is finished, you will probably be logged out of the Administrator.
    Sign in again. Twice.
11. If all goes well, you will get to a totally new look to the backend
    administrator panel.<img
    src="https://docs.joomla.org/images/thumb/5/53/J4-administrator-overview-en.png/800px-J4-administrator-overview-en.png"
    class="thumbborder" decoding="async"
    srcset="https://docs.joomla.org/images/thumb/5/53/J4-administrator-overview-en.png/1200px-J4-administrator-overview-en.png 1.5x, https://docs.joomla.org/images/thumb/5/53/J4-administrator-overview-en.png/1600px-J4-administrator-overview-en.png 2x"
    data-file-width="1640" data-file-height="752" width="800" height="367"
    alt="J4-administrator-overview-en.png" />
12. Go to **System **→** Maintenance **→** Database** and click *Fix* if
    any errors show.
13. In **System **→** Install **→** Discover** see if there are any
    extensions to install. (There shouldn't be any!)
14. Go to the frontend of your site and see if it shows up even if it’s
    not the right template. If so, continue. If not, see [common errors
    during
    migration](https://docs.joomla.org/Joomla_3.10_to_4.x_Common_Migration_Errors "Special:MyLanguage/Joomla 3.10 to 4.x Common Migration Errors").
15. Take a backup.
16. Install your new template or other extensions if you have them to
    install. Back up often.
17. Configure them. Back up often.
18. Run a broken link checker and fix any broken links.
19. Test everything. Back up often.
20. If everything works as expected, turn Error Reporting back to System
    Default (**System **→** Global Configuration **→** Server tab**).
    Make sure to Save & Close.

### Going Live with your Joomla! 4.x Site

1.  When you’re ready to go live, back up your 3.10 site for the last
    time. Restore it in a subdirectory or subdomain if you would like
    to.
2.  Back up your Joomla! 4.x site and move or restore your Joomla! 4.x
    site to the root (or change nameservers if you were building on a
    temporary domain at a new hosting account root).
3.  Test again.
4.  IF you have made security changes to .htaccess file in the past, you
    may need to change a line (or lines) in it in order to update to the
    next version of Joomla 4. Please go to
    <a href="https://docs.joomla.org/Htaccess_changes_after_joomla4.0.4"
    class="external text" target="_blank" rel="noreferrer noopener">Htaccess
    changes after joomla4.0.4</a> to determine if you need to change
    your file or not.
5.  Remove the Joomla! 3.10 site from the server within a couple of days
    unless you have edited your *robots.txt* file to block the search
    engine spiders.
6.  Remove all development sites you have been working with or keep them
    up-to-date if they are running a current version in order to ward
    off hack attempts on your server.

If you had data change on the 3.10 site while you were migrating to 4.x,
you will want to get that data moved over to the 4.x site before going
live. You can do this manually (make sure you keep the same user IDs -
go in order) or by using a <a
href="https://extensions.joomla.org/category/migration-a-conversion/data-import-a-export%20transfer%20tool/third-party%20extension/"
class="external text" target="_blank" rel="noreferrer noopener">third
party extension</a>.

## Suggested Tools

- <a
  href="http://extensions.joomla.org/extensions/access-a-security/site-security/backup/1606"
  class="external text" target="_blank" rel="noreferrer noopener">Akeeba
  Backup</a> is very popular for backup and restore. See more
  <a href="https://extensions.joomla.org/tags/backup/"
  class="external text" target="_blank" rel="noreferrer noopener">backup
  tools</a>.

## Related information

[Pre-Update_Check](https://docs.joomla.org/:Pre-Update_Check "Special:MyLanguage/:Pre-Update Check")
