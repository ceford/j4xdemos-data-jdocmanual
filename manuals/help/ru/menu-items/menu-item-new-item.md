<!-- Filename: Help4.x:Menu_Item:_New_Item / Display title: Меню: Создание пункта меню -->

## Описание

Menu Items are the core structure of a Joomla website. Each Menu Item is
a link to a webpage. The Menu Item Type determines the type of page that
will display when this menu choice is selected by the User.

In this screen, you will select the Menu Item Type for the Menu Item you
are creating and then fill in information about this specific Menu Item.
Some of these fields are common to all Menu Item Types and are
documented in this help screen.

In addition to these common fields, different Menu Item types may
require different fields unique to that type. These are documented in
the help screen for each type.

## Как открыть

To add a Menu Item:

- **Menus **→** \[name of the menu\]**
  1.  click the **New** toolbar button.
  2.  click the Menu Item Type **Select** button.

To edit a Menu Item:

- **Menus **→** \[name of the menu\]**
  - select a **Title** from the list

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/a/aa/Help-4x-Menus-New-Item-screen-ru.png/800px-Help-4x-Menus-New-Item-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/aa/Help-4x-Menus-New-Item-screen-ru.png/1200px-Help-4x-Menus-New-Item-screen-ru.png 1.5x, https://docs.joomla.org/images/a/aa/Help-4x-Menus-New-Item-screen-ru.png 2x"
data-file-width="1440" data-file-height="1343" width="800" height="746"
alt="Help-4x-Menus-New-Item-screen-ru.png" />

## Form Fields

- **Title**. The title that will display for this menu item.
- **Alias**. The internal name of the menu item. Normally, you can leave
  this blank and Joomla will fill in a default value Title in lower case
  and with dashes instead of spaces.Learn more.

### Подробности

**Left Panel**

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window**. Select from the dropdown list.
- **Template Style**. Select from the dropdown list.

**Right Panel**

- **Menu**. Shows which menu the link will appear in.
- **Parent Item**. The parent menu item for this menu item. Used to
  determine whether a Menu Item is a top-level item or a submenu item.
  Select 'Menu Item Root' (the default value) if this is a top-level
  Menu Item. Otherwise, select the Menu Item that is this item's parent.
- **Ordering**. Indicates the order of this menu item in the Menu. The
  default Order is to add the menu item to the end of the Menu. This
  menu item will moved to the order position just after the menu item
  selected from the dropdown list.Menus: Items.
- **Status**. The published status of the menu item.
- **Start Publishing**. Date and time to start publishing. Use this
  field if you want to enter the menu item ahead of time and then have
  it published automatically at a future time.
- **Finish Publishing**. Date and time to finish publishing. Use this
  field if you want to have the menu item automatically changed to
  Unpublished state at a future time (for example, when it is no longer
  applicable).
- **Default Page**. If Yes, this menu item is the default page for the
  site. There must be exactly one menu item set as the default page. You
  can change the default page in two ways:
  1.  Click on the Home column of the desired menu item in the
      <a href="https://docs.joomla.org/Help4.x:Menus:_Items/ru" class="new"
      title="Special:MyLanguage/Help4.x:Menus: Items/ru (page does not exist)">Menus:
      Items</a> screen.
  2.  Open the menu item for the new default page and change the Default
      Page setting to Yes.
- **Access**. The [viewing Access
  Level](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/ru "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/ru")
  for this menu item.
- **Language**. Menu items language.
- **Note**. This is normally for the site administrator's use and does
  not show in the Frontend of the site.

### Тип ссылки

<img
src="https://docs.joomla.org/images/thumb/a/a9/Help-4x-Menus-New-Item-link-type-subscreen-ru.png/600px-Help-4x-Menus-New-Item-link-type-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/a9/Help-4x-Menus-New-Item-link-type-subscreen-ru.png/900px-Help-4x-Menus-New-Item-link-type-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/a/a9/Help-4x-Menus-New-Item-link-type-subscreen-ru.png/1200px-Help-4x-Menus-New-Item-link-type-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1300" width="600" height="271"
alt="Help-4x-Menus-New-Item-link-type-subscreen-ru.png" />

- **Link Title Attribute**. An optional, custom description for the
  title attribute of the menu hyperlink.
- **CSS класс ссылки**. необязательный произвольный стиль CSS, который
  будет применен к гиперссылке пункта меню.
- **Link Icon Class**. If an icon class is entered, it takes precedence
  over the link image.
- **Link Image**. Select or upload an optional image to be used with the
  menu hyperlink.
- **Image Class**. An optional class to apply to the image.
- **Add Menu Title**. If the optional image is added, adds the menu
  title next to the image. Default is 'Yes'.
- **Display in Menu**. Select 'No' if you want to exclude this menu item
  from displaying in the menu.Note: Any submenu items will also be
  hidden.

### Страница

<img
src="https://docs.joomla.org/images/thumb/1/1b/Help-4x-Menus-New-Item-page-display-subscreen-ru.png/600px-Help-4x-Menus-New-Item-page-display-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/1b/Help-4x-Menus-New-Item-page-display-subscreen-ru.png/900px-Help-4x-Menus-New-Item-page-display-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/1/1b/Help-4x-Menus-New-Item-page-display-subscreen-ru.png/1200px-Help-4x-Menus-New-Item-page-display-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1120" width="600" height="233"
alt="Help-4x-Menus-New-Item-page-display-subscreen-ru.png" />

Note: Options include "**Use Global**". If this is selected, the setting
from the
<a href="https://docs.joomla.org/Help4.x:Menus:_Options/ru" class="new"
title="Special:MyLanguage/Help4.x:Menus: Options/ru (page does not exist)">Menus:
Options</a> will be used.

- **Browser Page Title**. Optional text for the 'Browser page title'
  element. If blank, a default value is used based on the Menu Item
  Title.
- **Show Page Heading**. Show the Browser Page Title in the heading of
  the page (If no optional text entered - will default to value based on
  the Menu Item Title). The Page heading is usually displayed inside the
  HTML-tag 'H1'.
- **Page Heading**. Optional alternative text for the Page heading.
- **Page Class**. Optional CSS class to add to elements in this page.
  This allows CSS styling specific to this page.

### Метаданные

<img
src="https://docs.joomla.org/images/thumb/a/ac/Help-4x-Menus-New-Item-metadata-subscreen-ru.png/600px-Help-4x-Menus-New-Item-metadata-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/ac/Help-4x-Menus-New-Item-metadata-subscreen-ru.png/900px-Help-4x-Menus-New-Item-metadata-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/a/ac/Help-4x-Menus-New-Item-metadata-subscreen-ru.png/1200px-Help-4x-Menus-New-Item-metadata-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="930" width="600" height="194"
alt="Help-4x-Menus-New-Item-metadata-subscreen-ru.png" />

- **Meta Description**. An paragraph to be used as the description of
  the page.Learn more.
- **Robots**. The instructions for web 'robots' that browse to this
  page.Global Configuration.

### Связи

<img
src="https://docs.joomla.org/images/thumb/3/38/Help-4x-Menus-New-Item-associations-subscreen-ru.png/600px-Help-4x-Menus-New-Item-associations-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/3/38/Help-4x-Menus-New-Item-associations-subscreen-ru.png/900px-Help-4x-Menus-New-Item-associations-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/3/38/Help-4x-Menus-New-Item-associations-subscreen-ru.png/1200px-Help-4x-Menus-New-Item-associations-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="630" width="600" height="131"
alt="Help-4x-Menus-New-Item-associations-subscreen-ru.png" />

[Multilingual
only.](https://docs.joomla.org/Help4.x:Multilingual_Associations/ru "Special:MyLanguage/Help4.x:Multilingual Associations/ru")

### Привязка модулей

<img
src="https://docs.joomla.org/images/thumb/b/b8/Help-4x-Menus-New-Item-module-assignment-subscreen-ru.png/600px-Help-4x-Menus-New-Item-module-assignment-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/b/b8/Help-4x-Menus-New-Item-module-assignment-subscreen-ru.png/900px-Help-4x-Menus-New-Item-module-assignment-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/b/b8/Help-4x-Menus-New-Item-module-assignment-subscreen-ru.png/1200px-Help-4x-Menus-New-Item-module-assignment-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1300" width="600" height="271"
alt="Help-4x-Menus-New-Item-module-assignment-subscreen-ru.png" />

- **Unassigned Modules**. Show modules unassigned to this menu item
- **Unpublished Modules**. Show modules that are unpublished

## Панель инструментов

At the top of the page you will see the toolbar shown in the
[Screenshot](#screenshot) above.

- **Сохранить**. Saves the menu item and stays in the current screen.
- **Сохранить и закрыть**. Saves the menu item and closes the current
  screen.
  - **Сохранить и создать**. Saves the menu item and keeps the editing
    screen open and ready to create another menu item.
- **Закрыть**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Справка**. Opens this help screen.

Saved menu items have additional buttons:

- Dropdown 'Save & Close':
  - **Save as Copy**. Saves your changes to a copy of the current menu
    item. Does not affect the current menu item.
- **Associations**. With a specific language set for an menu item,
  allows side by side editing in another language.Multilingual only.
- **Close** instead 'Cancel', same function.

## Быстрые советы

- To add an menu item [Archived
  Articles](https://docs.joomla.org/Help4.x:Menu_Item:_Article_Archived/ru "Special:MyLanguage/Help4.x:Menu Item: Article Archived/ru").
- The core distribution of Joomla provides 38 different Menu Item types.
  If you install third-party extensions, these may add more menu types.

## Связанная информация

- Tutorial:
  <a href="https://docs.joomla.org/J4.x:Adding_a_New_Menu/ru" class="new"
  title="Special:MyLanguage/J4.x:Adding a New Menu/ru (page does not exist)">How
  to Add a New Menu</a>.
- This
  [Portal](https://docs.joomla.org/Portal:Joomla_4/ru "Special:MyLanguage/Portal:Joomla 4/ru")
  brings together information related specifically to Joomla 4.
