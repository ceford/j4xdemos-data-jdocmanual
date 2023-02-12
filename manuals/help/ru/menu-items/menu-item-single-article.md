<!-- Filename: Help4.x:Menu_Item:_Single_Article / Display title: Меню: Материал -->

## Описание

The Single Article menu item type is used to show one article in the
Frontend of the site.

## Как открыть

**Menus **→** \[name of the menu\]**

To add a Menu Item:

1.  click the **New** toolbar button.
2.  click the Menu Item Type **Select** button.
3.  select the **Articles** item.
4.  select the **Single Article** item.

To edit a Menu Item:

- select a **Title** from the list

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/6/6b/Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png/800px-Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/6b/Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png/1200px-Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png 1.5x, https://docs.joomla.org/images/thumb/6/6b/Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png/1600px-Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png 2x"
data-file-width="2880" data-file-height="1452" width="800" height="403"
alt="Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png" />

## Form Fields

- **Title**. The title that will display for this menu item.
- **Alias**. The internal name of the menu item. Normally, you can leave
  this blank and Joomla will fill in a default value Title in lower case
  and with dashes instead of spaces. [Learn
  more.](https://docs.joomla.org/Alias/en "Alias/en")

### Подробности

**Left Panel**

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Select Article**. This field holds the article to be shown in the
  menu item. Press the **Select/Change** button to open the article
  selection window.This screen is similar to the
  [Articles](https://docs.joomla.org/Help4.x:Articles/en "Help4.x:Articles/en")
  page. You can use the Filter fields to find the desired article and
  then click on the article's Title to select it. At that point, the
  modal window will close and the title will show in the Select Article
  field.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window**. Select from the dropdown list.
- **Template Style**. Select from the dropdown list.

**Right Panel**

- **Menu**. Shows which menu the link will appear in.

### Параметры

The Options determine how the article will show on the Frontend Site
layout.

<img
src="https://docs.joomla.org/images/thumb/e/ea/Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/ea/Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/e/ea/Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1340" width="600" height="279"
alt="Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png" />

Note: Options include "**Use Global**". If this is selected, the setting
from the [Articles:
Options](https://docs.joomla.org/Help4.x:Articles:_Options/en "Help4.x:Articles: Options/en")
will be used.

**Макет**

- **Title**. Show the Article's Title.
- **Linked Titles**. Show the title as a link to the article.
- **Вводный текст**.
  - Show: The Intro Text of the article will show when you drill down to
    the article.
  - Hide: Only the part of the article after the Read More break will
    show.
- **Позиция информации о материале**.
  - Above: Puts the article information block above the text.
  - Below: Puts the article information block below the text.
  - Split: Splits the article information block into 2 separate blocks.
    One block is above and the other is below the text.
- **Article Info Title**. Displays 'Details' on top of the article
  information block.

**Категория**

- **Category**. Show the Article's Category Title.
- **Link Category**. Show the title as a link to that Category.Note: You
  can set this to be either a blog or list layout with the [Choose a
  Layout](https://docs.joomla.org/Help4.x:Articles:_Options/en#choosealayout "Help4.x:Articles: Options/en")
  option in the Category Tab.
- **Parent Category**. Show the Article's Parent Category Title.
- **Link Parent Category**. Show the title as a link to that
  Category.Note: You can set this to be either a blog or list layout
  with the [Choose a
  Layout](https://docs.joomla.org/Help4.x:Articles:_Options/en#choosealayout "Help4.x:Articles: Options/en")
  option in the Category Tab.

**Связи**

- **Associations**. Show the associated flags or Language Code.
  [Multilingual
  only.](https://docs.joomla.org/Help4.x:Multilingual_Associations/en "Help4.x:Multilingual Associations/en")

**Автор**

- **Author**. Show the author of the Article.
- **Link to Author's Contact Page**. Show it as a link to a Contact
  layout for that author.Note: The author must be set up as a
  [Contact](https://docs.joomla.org/Help4.x:Contacts:_Edit/en "Help4.x:Contacts: Edit/en").
  Also, a link will not show if there is an [Author
  Alias](https://docs.joomla.org/Help4.x:Articles:_Edit/en#createdbyalias "Help4.x:Articles: Edit/en")
  value for the article.

**Дата**

- **Create Date**. Show the Article's create date.
- **Modify Date**. Show the Article's modify date.
- **Publish Date**. Show the Article's start publishing date.

**Параметры**

- **Navigation**. Show a navigation link 'Prev' or 'Next' when you drill
  down to the article.
- **Hits**. Show the number of times the article has been displayed by a
  user.
- **Tags**. Show the tags for each article.
- **Неавторизованные ссылки**.
  - Yes: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - No: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.
- **Позиция ссылок**.
  - Above: Links are shown above the content.
  - Below: Links are shown below the content.

### Common Options

See [Menus: New
Item](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en "Help4.x:Menu Item: New Item/en")
for help on fields common to all Menu Item types, including:

- [Right
  Panel](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en#rightpanel "Help4.x:Menu Item: New Item/en")
- [Тип
  ссылки](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/ru#linktype "Help4.x:Menu Item: New Item/ru")
- [Страница](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/ru#pagedisplay "Help4.x:Menu Item: New Item/ru")
- [Метаданные](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/ru#metadata "Help4.x:Menu Item: New Item/ru")
- [Связи](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/ru#associations "Help4.x:Menu Item: New Item/ru")
- [Привязка
  модулей](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/ru#moduleassignment "Help4.x:Menu Item: New Item/ru")

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

## Быстрые советы

- If you have a Single Article Layout defined for an article, that
  layout will show any time a user drills down to that article. For
  example, if an article is shown on another menu item type (for
  example, in a Category Blog or List Layout or a Featured Articles
  Layout), the user will be taken to the Single Article Layout for that
  article (if defined).
- Archived articles are no longer published but are still stored on the
  site. Articles are Archived using the Articles screen. Note that
  Articles assigned to the 'Uncategorised' Section will not show on the
  Archived Article List layout.

## Связанная информация

- This
  [Portal](https://docs.joomla.org/Portal:Joomla_4/en "Portal:Joomla 4/en")
  brings together information related specifically to Joomla 4.

|                                                                                                                                        |                                                                                                                                                                                             |
|----------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Related Help Screens                                                                                                                   | Описание                                                                                                                                                                                    |
| [Материалы: Настройки](https://docs.joomla.org/Help4.x:Articles:_Options/ru "Help4.x:Articles: Options/ru")                            | Used to set global defaults for menu items that display articles. These default values will be used when 'Use Global' is selected for an option in an Articles menu item.                   |
| [Материалы](https://docs.joomla.org/Help4.x:Articles/ru "Help4.x:Articles/ru")                                                         | Список материалов используется для поиска, отметки избранных, добавления и редактирования материалов.                                                                                       |
| [Материалы: Создание материала](https://docs.joomla.org/Help4.x:Articles:_Edit/ru "Help4.x:Articles: Edit/ru")                         | This is where you can add and edit Articles. You can also select the Category for an Article and indicate whether or not it is Published and if it is selected to appear on the Front Page. |
| [Материалы: Избранные материалы](https://docs.joomla.org/Help4.x:Articles:_Featured/ru "Help4.x:Articles: Featured/ru")                | Used to control which 'Featured Articles' are displayed on the Front Page and in what order they are displayed.                                                                             |
| [Материалы: Категории](https://docs.joomla.org/Help4.x:Articles:_Categories/ru "Help4.x:Articles: Categories/ru")                      | The Articles Categories list is used to find, add, and edit articles categories.                                                                                                            |
| [Меню: Материалы в архиве](https://docs.joomla.org/Help4.x:Menu_Item:_Article_Archived/ru "Help4.x:Menu Item: Article Archived/ru")    | Shows a customised list of articles ordered by date or title. Archived articles are no longer published but are still stored on the site.                                                   |
| [Меню: Блог категории](https://docs.joomla.org/Help4.x:Menu_Item:_Category_Blog/ru "Help4.x:Menu Item: Category Blog/ru")              | Used to show articles belonging to a specific Category in a blog layout. Controls the Leading Articles, Intro Articles and additional links to more Articles.                               |
| [Меню: Материалы](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/ru "Help4.x:Menu Item: Category List/ru")                   | Used to show articles belonging to a specific Category in a list layout.                                                                                                                    |
| [Меню: Создать материал](https://docs.joomla.org/Help4.x:Menu_Item:_Create_Article/ru "Help4.x:Menu Item: Create Article/ru")          | Allows users to submit an article. Normally this is available only to users who have logged in to the Frontend of the site. Users must have permission to create articles.                  |
| [Меню: Избранные материалы](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/ru "Help4.x:Menu Item: Featured Articles/ru") | Used to show all Articles that have been tagged as Featured. Articles are shown in a Blog Layout.                                                                                           |
| [Меню: Категории](https://docs.joomla.org/Help4.x:Menu_Item:_List_All_Categories/ru "Help4.x:Menu Item: List All Categories/ru")       | Used to show a hierarchical list of Categories. Depending on the selected options for this layout, you can click on a category Title to show the articles in that category.                 |
| <span class="mw-selflink selflink">Меню: Материал</span>                                                                               | Used to show one article.                                                                                                                                                                   |
