<!-- Filename: Help4.x:Articles:_New_or_Edit_Category / Display title: Articles: Edit Category -->

## Description

Categories are are used to organize Articles, Contacts and other
components for ease of management and display. They can be organised
into tree-like structures like file systems. For example, category Pets
may be a parent to category Dogs, category Cats and Category Goldfish.
Categories can be nested to any level. All Articles must be assigned
either to a parent Category or a child Category or to the special
Category called 'Uncategorized'.

The edit form is used to create a new Category or to alter the
properties of an existing Category.

## How to Access

To add a new category, starting from the Administrator menu:

- Select **Home Dashboard **→** Site panel **→** Categories + button**.
  Or...
- Select **Content **→** Categories + button**. Or...
- Select **Content **→** Categories**. Then...
  - Select the **New** button in the Toolbar to create a new Category.
    Or...

To edit an existing Category:

- Select **Content **→** Categories**. Then...
  - Select a **Category title** From the list of categories.

## Screenshot

<img
src="https://docs.joomla.org/images/thumb/8/85/Help-4x-Components-Content-Categories-Edit-screen-en.png/800px-Help-4x-Components-Content-Categories-Edit-screen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/85/Help-4x-Components-Content-Categories-Edit-screen-en.png/1200px-Help-4x-Components-Content-Categories-Edit-screen-en.png 1.5x, https://docs.joomla.org/images/8/85/Help-4x-Components-Content-Categories-Edit-screen-en.png 2x"
data-file-width="1440" data-file-height="1132" width="800" height="629"
alt="Help-4x-Components-Content-Categories-Edit-screen-en.png" />

## Form Fields

- **Title.** The Title for this item. This may or may not display on the
  page, depending on the parameter values you choose.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces. [Learn
  more.](https://docs.joomla.org/Alias "Special:MyLanguage/Alias")

### Category Tab

**Left Panel**

- **Description**. The description for the item. Category, Subcategory
  and Web Link descriptions may be shown on web pages, depending on the
  parameter settings. These descriptions are entered using the same
  editor that is used for Articles.
- **Toggle Editor**. A Toggle Editor button show below the edit window.
  This button allows you to toggle between the TinyMCE editor and No
  Editor.

**Right Panel**

- **Parent.** The item (category, menu item, and so on) that is the
  parent of the item being edited.
- **Status.** (Published/Unpublished/Archived/Trashed) The published
  status of the item.
- **Access Level.** Who has access to this item. Default options are:
  - **Public:** Everyone has access
  - **Guest:** Everyone has access
  - **Registered:** Only registered users have access
  - **Special:** Only users with author status or higher have access
  - **Super Users:** Only super users have access
  - Enter the desired level using the drop-down list box. Custom Access
    Control Levels created will show if they exist.
- **Language.** Item language.
- **Tags.** Enter one or more optional tags for this item. You can
  select existing tags by entering in the first few letters. You may
  also create new tags by entering them here. Tags allow you to see
  lists of related items across content types (for example, articles,
  contacts, and categories).
- **Note.** Item note. This is normally for the site administrator's use
  (for example, to document information about this item) and does not
  show in the front end of the site.
- **Version Note.** Optional field to identify this version of the item
  in the item's [Version
  History](https://docs.joomla.org/Help4.x:Components_Version_History/en "Help4.x:Components Version History/en")
  window.

### Options

This shows Options for this Category, as shown below when tab is
clicked:

<img
src="https://docs.joomla.org/images/1/1b/Help-4x-Categories-Edit-screen-options-tab-en.png"
decoding="async" data-file-width="600" data-file-height="371"
width="600" height="371"
alt="Help-4x-Categories-Edit-screen-options-tab-en.png" />

- **Layout**. Use a different layout from the supplied components view
  or overrides in the templates.
- **Image**. Choose an image to be displayed with this item/category in
  the Frontend.
- **Alt Text**. Alternative text used for visitors without access to
  images.

### Workflow

<img
src="https://docs.joomla.org/images/3/38/Help-4x-Categories-Edit-screen-workflow-tab-en.png"
decoding="async" data-file-width="600" data-file-height="272"
width="600" height="272"
alt="Help-4x-Categories-Edit-screen-workflow-tab-en.png" />

- **Workflow.** Select from the drop-down list.

### Publishing

The grayed out fields are for information only and may not be edited.

- **Created Date.** Date the item(Article, Category, Weblink, etc.) was
  created.
- **Created by.** Optional, choose from a popup window of users. Select
  User by clicking on the user's name. Defaults to user creating new
  category if left blank.
- **Modified Date.** *(Informative only)* Date of last modification.
- **Modified By.** *(Informative only)* Username who performed the last
  modification.
- **Hits.** Number of hits on a Category view.
- **ID.** The unique ID number automatically assigned to this item by
  Joomla!. This number cannot be changed.
- **Meta Description.** An optional paragraph to be used as the
  description of the page in the HTML output. This will generally
  display in the results of search engines. If entered, this creates an
  HTML meta element with a name attribute of "description" and a content
  attribute equal to the entered text.
- **Meta Keywords.** Optional entry for keywords. Must be entered
  separated by commas (for example, "cats, dogs, pets") and may be
  entered in upper or lower case. (For example, "CATS" will match "cats"
  or "Cats"). Keywords can be used in several ways:
  - To help Search Engines and other systems classify the content of the
    Article.
  - In combination with Banner tags, to display specific Banners based
    on the Article content. For example, say you have one Banner with an
    ad for dog products and another Banner for cat products. You can
    have your dog Banner display when a User is viewing a dog-related
    Article and your cat Banner display for a cat-related Article. To do
    this, you would:
    - Add the keywords 'dog' and 'cat' to the appropriate Articles.
    - Add the Tags 'dog' and 'cat' to the appropriate Banners in the
      [Banner Manager
      New/Edit](https://docs.joomla.org/Help4.x:Banners:_Edit/en "Help4.x:Banners: Edit/en")
      screen.
    - Set the Banner module Parameter 'Search By Tags' to 'Yes in the
      [Banner Module
      Edit](https://docs.joomla.org/Help4.x:Site_Modules:_Banners/en "Help4.x:Site Modules: Banners/en")
      screen.
  - For articles only, in combination with the [Related
    Articles](https://docs.joomla.org/Help4.x:Site_Modules:_Articles_-_Related/en "Help4.x:Site Modules: Articles - Related/en")
    module, to display Articles that share at least one keyword in
    common. For example, if the current Article displayed has the
    keywords "cats, dogs, monkeys", any other Articles with at least one
    of these keywords will show in the Related Articles module.
- **Author.** Optional entry for an Author name within the metadata. If
  entered, this creates an HTML meta element with the name attribute of
  "author" and the content attribute as entered here.
- **Robots.** The instructions for web "robots" that browse to this
  page.
  - *Use Global*: Use the value set in the Componentâ†’Options for this
    component.
  - *Index, Follow*: Index this page and follow the links on this page.
  - *No index, Follow*: Do not index this page, but still follow the
    links on the page. For example, you might do this for a site map
    page where you want the links to be indexed but you don't want this
    page to show in search engines.
  - *Index, No follow*: Index this page, but do not follow any links on
    the page. For example, you might want to do this for an events
    calendar, where you want the page to show in search engines but you
    do not want to index each event.
  - *No index, no follow*: Do not index this page or follow any links on
    the page.

### Associations

This shows Associations for this Category, as shown below when tab is
clicked: <img
src="https://docs.joomla.org/images/7/73/Help-4x-Categories-Edit-screen-associations-tab-en.png"
decoding="async" data-file-width="600" data-file-height="238"
width="600" height="238"
alt="Help-4x-Categories-Edit-screen-associations-tab-en.png" />

- **Select a Category:** Select or Create a Category to associate.

### Permissions Tab

This section shows permissions for this category. The screen shows as
follows.

<img
src="https://docs.joomla.org/images/thumb/8/87/Help-4x-Categories-Edit-screen-permissions-tab-en.png/600px-Help-4x-Categories-Edit-screen-permissions-tab-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/8/87/Help-4x-Categories-Edit-screen-permissions-tab-en.png 1.5x"
data-file-width="800" data-file-height="432" width="600" height="324"
alt="Help-4x-Categories-Edit-screen-permissions-tab-en.png" />

  
To change the permissions for this extension, do the following.

- Select the **Group** by clicking its title located on the left.
- Find the desired **Action**. Possible Actions are:
  - **Configure ACL & Options.** Users can edit the options and
    permissions of this extension.
  - **Configure Options Only.** Users can edit the options except the
    permissions of this extension.
  - **Access Administration Interface.** Users can access user
    administration interface of this extension.
  - **Create.** Users can create content of this extension.
  - **Delete.** Users can delete content of this extension.
  - **Edit.** Users can edit content of this extension.
  - **Edit State.** User can change the published state and related
    information for content of this extension.
  - **Edit Own.** Users can edit own created content of this extension.
- Select the desired permission for the action you wish to change.
  Possible settings are:
  - ***Inherited.*** Inherited for users in this Group from the Global
    Configuration permissions of this extension.
  - ***Allowed.*** Allowed for users in this Group. Note that, if this
    action is Denied at one of the higher levels, the Allowed permission
    here will not take effect. A Denied setting cannot be overridden.
  - ***Denied.*** Denied for users in this Group.
- Click **Save** in **Toolbar** at top. When the screen refreshes, the
  Calculated Setting column will show the effective permission for this
  Group and Action.

## Toolbar

At the top of the page you will see the toolbar shown in the
[Screenshot](#Screenshot) above. The functions are:

- **Save**. Saves the item and stays in the current screen.
- **Save & Close**. Saves the item and closes the current screen.
- **Save & New**. Saves the item and keeps the editing screen open and
  ready to create another item.
- **Save as Copy**. Saves your changes to a copy of the current item.
  Does not affect the current item. This toolbar icon is not shown if
  you are creating a new item.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. Or
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. This
  toolbar icon is not shown if you are creating a new item.
- **Versions**. Opens the Item Version History window to show any prior
  versions of this item. This allows you to view older versions of this
  item and, if desired, restore from an older version. See [Version
  History](https://docs.joomla.org/Help40:Components_Version_History "Special:MyLanguage/Help40:Components Version History")
  for more information.
- **Help**. Opens this help screen.

## Related Information

- [TinyMCE and Code Mirror
  Editors](https://docs.joomla.org/Help4.x:Editors/en "Help4.x:Editors/en")
- To work with existing Categories: [Category
  Manager](https://docs.joomla.org/Help4.x:Articles:_Categories/en "Help4.x:Articles: Categories/en")
- To work with Articles: [Article
  Manager](https://docs.joomla.org/Help4.x:Articles/en "Help4.x:Articles/en")
