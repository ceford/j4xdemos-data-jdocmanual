<!-- Filename: Help4.x:Menus / Display title: Меню -->

## Description

Menus allow a user to navigate through the site. A menu is an object
which contains one or more menu items. Each menu item points to a
logical page on the site. A menu module is required to place the menu on
the page. One menu can have more than one module. For example, one
module might show only the first level menu items and a second module
might show the level 2 menu items.

The Menus list provides an overview of the menus available on a Joomla
site. This includes the details of each individual menu's number of
items published, unpublished and trashed, and the names of linked
modules.

The process for adding a menu to the site is normally as follows:

1.  Create a new menu (using this screen).

<!-- -->

1.  Create one or more new menu items for the menu. Each menu item will
    have a specific menu item type.

<!-- -->

1.  Create one or more menu modules to display the menu on the site.
    When you create the modules, you will select which menu items
    (pages) the modules will show on.

## How to Access

- Select **Menus **→** Manage** from the Administrator menu.

## Screenshot

\[\[Image:Help-4x-menus-menu-manager-menus-

en

.png\|800px\]\]

## Column Headers

Clicking on the title of a column will sort the table view by the
column. A down arrow next to the column title means ascending order and
an up arrow means descending order. The default sort is by **ID#** in
ascending order.

{{:Chunk4x:Help screen column header Checkbox/

en

}}

- **Title**. The name of the menu.

<!-- -->

- **\# Published**. Number of published menu items in this menu.

<!-- -->

- **\# Unpublished**. Number of unpublished menu items in this menu.

<!-- -->

- **\# Trashed**. Number of trashed menu items in this menu.

<!-- -->

- **Linked Modules**. Lists any menu modules associated with the menu.
  The column shows the module's name, access level, and position on
  template.

{{:Chunk4x:Help screen column header Id/

en

}}

## Toolbar

{{safesubst:Chunk4x:Help_screen_toolbar_top_descriptor/

en

}} {{safesubst:Chunk4x:Help_screen_toolbar_icon_New/

en

\|menu}} {{safesubst:Chunk4x:Help_screen_toolbar_icon_Edit/

en

\|menu}} {{safesubst:Chunk4x:Help_screen_toolbar_icon_Delete/

en

\|menus}}

Deleting a menu also deletes all the menu items it contains and any
associated menu modules. On clicking Delete you will be asked to confirm
that you want to delete the selected menus. Clicking OK button will
delete the menus. Click Cancel to abort the deletion.

{{safesubst:Chunk4x:Help_screen_toolbar_icon_Rebuild/

en

\|menu}} {{safesubst:Chunk4x:Help_screen_toolbar_icon_Options/

en

}}

See

[Menus
Configuration](https://docs.joomla.org/Help4.x:Components_Menus_Configuration "Special:MyLanguage/Help4.x:Components Menus Configuration").
{{safesubst:Chunk4x:Help_screen_toolbar_icon_Help/

en

}}

## Quick Tips

- It is expedient to give a descriptive title for new menus because,
  later, you will see it in the *Backend Menus* menu. It is a good idea
  to fill in the *Description* field with information about the menu. If
  you enter a short title in the *Module title* field, you can identify
  the menu's module using that title in the Module Manager.

<!-- -->

- Though you can create a copy of a selected menu by clicking the *Copy*
  toolbar button, you can make another instance in the Module Manager as
  well.

<!-- -->

- When you create a new menu, use only English alphanumeric characters
  without space in the Unique Name field. It is a good idea using only
  a-z, 0-9 and underscore (\_) characters.

<!-- -->

- If you don't enter a *Module title*, no module will be created and the
  menu cannot be displayed in the front end. However you can use the
  Module Manager later to create a new mod_mainmenu module, and assign
  it to the menu.

<!-- -->

- If you delete an existing menu, do not forget that all the menu items
  of the respective menu will be also deleted.

<!-- -->

- The Main Menu has your default menu item, so it **should not be
  deleted**. The default menu item is defines the page that is displayed
  when you visit www.*yoursite*.com, and your site will not function if
  it is deleted. It is usually your Home menu item but it can be set to
  any menu item including a menu item in a hidden menu. If you change
  the default menu item, make sure that you don't delete that menu item
  either! The menu with the default menu item is marked with an asterisk
  (\*) in the *Menus* menu.

## Related Information

- To add new Menus: [Menu Manager
  New/Edit](https://docs.joomla.org/Help4.x:Menus:_Edit/en "Help4.x:Menus: Edit/en")

<!-- -->

- To set action permissions for menus: [Menus
  Configuration](https://docs.joomla.org/Help4.x:Menus:_Options/en "Help4.x:Menus: Options/en")

<!-- -->

- To add or edit Menu Items: [Menu Item
  Manager](https://docs.joomla.org/Help4.x:Menus:_Items/en "Help4.x:Menus: Items/en")

<!-- -->

- To add or edit Menu Modules: [Module
  Manager](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en "Help4.x:Menu Item: New Item/en")
