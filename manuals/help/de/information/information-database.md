<!-- Display title: Information: Database -->

## Beschreibung

This screen checks that your database table structure is up to date with
your Joomla programs and lets you try to fix any problems that are
found.

In a normal Joomla version update, changes to the database table
structure (also called "schema") are done automatically to keep the
database version synchronized with the Joomla version.

If an update is done manually, or if some part of an automatic update
fails, the database schema might not be updated to match the version of
the Joomla program files. In this case you will see a list of database
problems on the screen. You can normally fix any problems by clicking on
the Fix button.

## How to Access

- Select **System **→** Information Panel **→** Database** from the
  Administrator menu.

## Screenshot

\[\[Image:Help-4x-extension_manager-database-screen-

en

.png\|800px\]\]

## Column Headers

<a
href="https://docs.joomla.org/index.php?title=Chunk4x:Help_screen_column_header&amp;action=edit&amp;redlink=1"
class="new"
title="Chunk4x:Help screen column header (page does not exist)">Chunk4x:Help
screen column header</a> <a
href="https://docs.joomla.org/index.php?title=Chunk4x:Help_screen_column_header&amp;action=edit&amp;redlink=1"
class="new"
title="Chunk4x:Help screen column header (page does not exist)">Chunk4x:Help
screen column header</a>

- **Location.** Specifies if this is a site or administrator extension.

<!-- -->

- **Type.** The extension type - module, plug-in, template, language.

<!-- -->

- **Problems.** Any problems will be mentioned here. A hover Tooltip
  provides more information.

<!-- -->

- **Database Version.** The version number of the Database.

<!-- -->

- **Manifest Version.** The version number of Joomla or Extension.

<!-- -->

- **Folder.** If the extension is a plug-in, the subdirectory of your
  Joomla! installation's /plugins directory where the extension is
  located.

<!-- -->

- **ID.** The ID number. This is a unique identification number for this
  item assigned automatically by Joomla!. It is used to identify the
  item internally, for example in internal links. You cannot change this
  number.

## List Filters

{{safesubst:Chunk4x:Help_screen_filters_Search_Bar_Filter/

en

}}

**Filter Options**

You can use one of the available filters or any combination of them to
limit the number of extensions displayed to just the extensions which
match your filter parameters.

- **-Select Location-.** Select Site, Administrator or API from the
  dropdown list of available locations.

<!-- -->

- **-Select Type-.** Select the extension type from the dropdown list
  box of available types.

<!-- -->

- **-Select Folder-.** Select a plug-in folder from the dropdown list
  box of available folders. There is a separate folder for each type of
  plug-in defined in your Joomla installation.

{{:Chunk4x:Help_screen_filters_Pagination/en}}

## Toolbar

{{safesubst:Chunk4x:Help_screen_toolbar_top_descriptor/

en

}}

- **Update Structure**. This program attempts to fix any database table
  structure problems found in the Database check. It runs any database
  schema change scripts (from the folder
  `administrator/components/com_admin/sql/updates`) that were not run
  during the version update. It then re-checks whether or not the
  database is up to date. If it is successful, the message "Database
  table structure is up to date" will show.

{{safesubst:Chunk4x:Help_screen_toolbar_icon_Options/

en

}} {{safesubst:Chunk4x:Help_screen_toolbar_icon_Help/

en

}}

## Quick Tips

- If you experience problems during an update, use this Database check
  to see if your database got updated correctly.

<!-- -->

- It is strongly recommended that you use the
  <a href="https://docs.joomla.org/Help4.x:Joomla_Update/de" class="new"
  title="Special:MyLanguage/Help4.x:Joomla Update/de (page does not exist)">Joomla
  Update</a> component to update your site. This way the database
  changes will be done automatically.

## Related Information

- You can check for available updates in the
  <a href="https://docs.joomla.org/Help4.x:Joomla_Update/de" class="new"
  title="Special:MyLanguage/Help4.x:Joomla Update/de (page does not exist)">Joomla
  Update</a> component or in the
  <a href="https://docs.joomla.org/Help4.x:Site_Control_Panel/de"
  class="new"
  title="Special:MyLanguage/Help4.x:Site Control Panel/de (page does not exist)">Control
  Panel</a>.

**Links to Other Screens**

- **Install.** Links to the [Install
  Screen](https://docs.joomla.org/Help4.x:Extensions:_Install/de "Special:MyLanguage/Help4.x:Extensions: Install/de").

<!-- -->

- **Update.** Links to the [Update
  Screen](https://docs.joomla.org/Help4.x:Extensions:_Update/de "Special:MyLanguage/Help4.x:Extensions: Update/de").

<!-- -->

- **Manage.** Links to the [Manage
  Screen](https://docs.joomla.org/Help4.x:Extensions:_Manage/de "Special:MyLanguage/Help4.x:Extensions: Manage/de").

<!-- -->

- **Discover.** Links to the [Discover
  Screen](https://docs.joomla.org/Help4.x:Extensions:_Discover/de "Special:MyLanguage/Help4.x:Extensions: Discover/de").

<!-- -->

- **Database.** Links to the [Database
  Screen](https://docs.joomla.org/Help4.x:Information:_Database/de "Special:MyLanguage/Help4.x:Information: Database/de").

<!-- -->

- **Warnings.** Links to the [Warnings
  Screen](https://docs.joomla.org/Help4.x:Information:_Warnings/de "Special:MyLanguage/Help4.x:Information: Warnings/de").

<!-- -->

- **Install Languages.** Links to the [Languages
  Screen](https://docs.joomla.org/Help4.x:Extensions_Extension_Manager_Languages/de "Special:MyLanguage/Help4.x:Extensions Extension Manager Languages/de").

<!-- -->

- **Update Sites.** Links to the [Update
  Sites](https://docs.joomla.org/Help4.x:Extensions:_Update/de "Special:MyLanguage/Help4.x:Extensions: Update/de").
