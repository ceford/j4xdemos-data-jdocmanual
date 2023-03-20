<!-- Filename: Help4.x:Menu_Item:_Featured_Articles / Display title: Меню: Избранные материалы -->

## Описание

The Featured Articles menu item type is used to show all Articles that
have been tagged as Featured in a Blog Layout.

## Как открыть

**Menus **→** \[name of the menu\]**

To add a Menu Item:

1.  click the **New** toolbar button.
2.  click the Menu Item Type **Select** button.
3.  select the **Articles** item.
4.  select the **Featured Articles** item.

To edit a Menu Item:

- select a **Title** from the list

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/7/7e/Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png/800px-Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/7e/Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png/1200px-Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png 1.5x, https://docs.joomla.org/images/thumb/7/7e/Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png/1600px-Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png 2x"
data-file-width="2880" data-file-height="1449" width="800" height="403"
alt="Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png" />

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
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window**. Select from the dropdown list.
- **Template Style**. Select from the dropdown list.

**Right Panel**

- **Menu**. Shows which menu the link will appear in.

### Блог

The Options control the appearance of the blog menu item.

<img
src="https://docs.joomla.org/images/thumb/0/0e/Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/0e/Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/0/0e/Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1300" width="600" height="271"
alt="Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png" />

- **Select Categories**. Select the categories you want to include in
  this layout. Click the 'X' in the category box to remove category.
- **\# Leading Articles**. Number of Articles to show using the full
  width of the main display area. "0" means that no Articles will show
  when using the full width. If an Article has a "Read more..." break,
  only the part of the text before the break (the Intro text) will
  display.
- **Leading Article Class**. You can add any CSS class for your own
  styling ideas. Add a border on top with class boxed.For image position
  use for example image-left, image-right. Add image-alternate for
  alternate ordering of intro images.
- **\# Intro Articles**. Determines the number of Articles to display
  after the leading Article. These Articles will display in the number
  of columns set in the Columns parameter below. If an Article has a
  "Read more..." break, only the text before the break (Intro text) will
  display, followed by a "Read more..." link. The order in which to
  display the articles is determined by the Category Order and Article
  Order parameters below.
- **Article Class**. You can add any CSS class for your own styling
  ideas. Add a border on top with class boxed.For image position use for
  example image-left, image-right. Add image-alternate for alternate
  ordering of intro images.
- **\# Columns**. The number of columns to use in the Intro Articles
  area. This is normally between 1 and 3 (depending on the template you
  are using). If 1 is used, the Intro Articles will display using the
  full width of the display area, just like the Leading Articles.
- **Multi Column Direction**. In multi-column blog layouts, whether to
  order articles Down the columns or Across the columns.

<!-- -->

  - Down: Order articles going down the first column and then over to
    the next column, for example:

- 

<!-- -->

  - Across: Order articles going across the columns and then back to the
    first column, for example:

- 

<!-- -->

- **\# Links**. The number of Links to display in the Links area of the
  page. These links allow a User to link to additional Articles, if
  there are more Articles than can fit on the first page of the Blog
  Layout.
- **Linked Intro Image**. If Yes, a click on the intro image shows the
  article.
- Порядок категорий**.**.
  - No Order: Articles are ordered only by the Article Order, without
    regard to Category.
  - Title Alphabetical: Categories are displayed in alphabetical order
    (A to Z).
  - Title Reverse Alphabetical: Categories are displayed in reverse
    alphabetical order (Z to A).
  - Category Order: Categories are ordered according to the Order column
    entered in [Articles:
    Categories](https://docs.joomla.org/Help4.x:Articles:_Categories/en#ordering "Help4.x:Articles: Categories/en").
- Порядок материалов**.**.
  - Featured Articles Order: Articles are ordered according to the Order
    column entered in [Articles:
    Featured](https://docs.joomla.org/Help4.x:Articles:_Featured/en#ordering "Help4.x:Articles: Featured/en").
  - Most Recent First: Articles are displayed starting with the most
    recent and ending with the oldest.
  - Oldest First: Articles are displayed starting with the oldest and
    ending with the most recent.
  - Title Alphabetical: Articles are displayed by Title in alphabetical
    order (A to Z).
  - Title Reverse Alphabetical: Articles are displayed by Title in
    reverse alphabetical order (Z to A).
  - Author Alphabetical: Articles are displayed by Author in
    alphabetical order (A to Z).
  - Author Reverse Alphabetical: Articles are displayed by Author in
    reverse alphabetical order (Z to A).
  - Most Hits: Articles are displayed by the number of hits, starting
    with the one with the most hits and ending with the one with the
    least hits.
  - Least Hits: Articles are displayed by the number of hits, starting
    with the one with the least hits and ending with the one with the
    most hits.
  - Random Order: Articles are displayed in random order.
  - Article Order: Articles are ordered according to the Order column
    entered in
    [Articles](https://docs.joomla.org/Help4.x:Articles/en#ordering "Help4.x:Articles/en").
  - Article Reverse Order: Articles are ordered reverse to the according
    of the Order column entered in
    [Articles](https://docs.joomla.org/Help4.x:Articles/en#ordering "Help4.x:Articles/en").
- **Date for Ordering**. The date used when articles are sorted by date.
  - Created: Use the article created date.
  - Modified: Use the article modified date.
  - Published: Use the article start publishing date.
  - Unpublished: Use the article unpublished date.
- **Pagination**. Pagination provides page links at the bottom of the
  page that allow the User to navigate to additional pages. These are
  needed if the Articles will not fit on one page.
  - Hide: Pagination links not shown. Note: Users will not be able to
    navigate to additional pages.
  - Show: Pagination links shown if needed.
  - Auto: Pagination links shown if needed.
- **Pagination Summary**. Show the current page number and total pages
  (e.g., "Page 1 of 2") at the bottom of each page.

### Отображение

The Options determine how the articles will show in the blog menu
item.  
Options include "Use Article Settings". If this is selected, the setting
from [Articles:
Edit](https://docs.joomla.org/Help4.x:Articles:_Edit/en "Help4.x:Articles: Edit/en")
will be used.

<img
src="https://docs.joomla.org/images/thumb/3/31/Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/3/31/Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/3/31/Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1274" width="600" height="265"
alt="Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png" />

Макет

- **Title**. Show the Article's Title.
- **Linked Titles**. Show the title as a link to the article.
- Вводный текст**.**.
  - Show: The Intro Text of the article will show when you drill down to
    the article.
  - Hide: Only the part of the article after the Read More break will
    show.
- Позиция информации о материале**.**.
  - Above: Puts the article information block above the text.
  - Below: Puts the article information block below the text.
  - Split: Splits the article information block into 2 separate blocks.
    One block is above and the other is below the text.
- **Article Info Title**. Displays 'Details' on top of the article
  information block.

Категория

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

Связи

- **Associations**. Show the associated flags or Language Code.
  [Multilingual
  only.](https://docs.joomla.org/Help4.x:Multilingual_Associations/en "Help4.x:Multilingual Associations/en")

Автор

- **Author**. Show the author of the Article.
- **Link to Author's Contact Page**. Show it as a link to a Contact
  layout for that author.Note: The author must be set up as a
  [Contact](https://docs.joomla.org/Help4.x:Contacts:_Edit/en "Help4.x:Contacts: Edit/en").
  Also, a link will not show if there is an [Author
  Alias](https://docs.joomla.org/Help4.x:Articles:_Edit/en#createdbyalias "Help4.x:Articles: Edit/en")
  value for the article.

Дата

- **Create Date**. Show the Article's create date.
- **Modify Date**. Show the Article's modify date.
- **Publish Date**. Show the Article's start publishing date.

Параметры

- **Navigation**. Show a navigation link 'Prev' or 'Next' when you drill
  down to the article.
- **"Read More" Link**. Show the Read More link to link from the part of
  the article before the Read More break to the rest of the Article.
- Заголовок со ссылкой "Подробнее"**.**.
  - Show: The article title is part of the Read More link. The link will
    be in the format "Read More: \[article title\]".
  - Hide: The link will be "Read more".
- **Hits**. Show the number of times the article has been displayed by a
  user.
- **Tags**. Show the tags for each article.
- Неавторизованные ссылки**.**.
  - Yes: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - No: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.

### Интеграция

The Options determine whether a news feed will be available for the page
and what information it will show.

<img
src="https://docs.joomla.org/images/thumb/2/2a/Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/2a/Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/2/2a/Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="820" width="600" height="171"
alt="Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png" />

- **RSS Feed Link**. If set to Show, a Feed Link will show up as a feed
  icon in the address bar of most browsers.
- Для материалов ленты показывать**.**.
  - Intro Text: Only the article's intro text will show in the feed.
  - Full Text: The entire text of the article will show in the feed.

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

- To see an example of the featured layout, install Joomla with the
  sample data and select the Home page.
- Featured articles are selected using [Articles:
  Featured](https://docs.joomla.org/Help4.x:Articles:_Featured/en "Help4.x:Articles: Featured/en").

## Связанная информация

- To create a new Category see [Articles: Edit
  Category](https://docs.joomla.org/Help4.x:Articles:_Edit_Category/en "Help4.x:Articles: Edit Category/en").

<!-- -->

- To create a new menu see
  [Menus](https://docs.joomla.org/Help4.x:Menus/en "Help4.x:Menus/en").

<!-- -->

- This
  [Portal](https://docs.joomla.org/Portal:Joomla_4/en "Portal:Joomla 4/en")
  brings together information related specifically to Joomla 4.

|                                                                                                                                     |                                                                                                                                                                                             |
|-------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Related Help Screens                                                                                                                | Описание                                                                                                                                                                                    |
| [Материалы: Настройки](https://docs.joomla.org/Help4.x:Articles:_Options/ru "Help4.x:Articles: Options/ru")                         | Used to set global defaults for menu items that display articles. These default values will be used when 'Use Global' is selected for an option in an Articles menu item.                   |
| [Материалы](https://docs.joomla.org/Help4.x:Articles/ru "Help4.x:Articles/ru")                                                      | Список материалов используется для поиска, отметки избранных, добавления и редактирования материалов.                                                                                       |
| [Материалы: Создание материала](https://docs.joomla.org/Help4.x:Articles:_Edit/ru "Help4.x:Articles: Edit/ru")                      | This is where you can add and edit Articles. You can also select the Category for an Article and indicate whether or not it is Published and if it is selected to appear on the Front Page. |
| [Материалы: Избранные материалы](https://docs.joomla.org/Help4.x:Articles:_Featured/ru "Help4.x:Articles: Featured/ru")             | Used to control which 'Featured Articles' are displayed on the Front Page and in what order they are displayed.                                                                             |
| [Материалы: Категории](https://docs.joomla.org/Help4.x:Articles:_Categories/ru "Help4.x:Articles: Categories/ru")                   | The Articles Categories list is used to find, add, and edit articles categories.                                                                                                            |
| [Меню: Материалы в архиве](https://docs.joomla.org/Help4.x:Menu_Item:_Article_Archived/ru "Help4.x:Menu Item: Article Archived/ru") | Shows a customised list of articles ordered by date or title. Archived articles are no longer published but are still stored on the site.                                                   |
| [Меню: Блог категории](https://docs.joomla.org/Help4.x:Menu_Item:_Category_Blog/ru "Help4.x:Menu Item: Category Blog/ru")           | Used to show articles belonging to a specific Category in a blog layout. Controls the Leading Articles, Intro Articles and additional links to more Articles.                               |
| [Меню: Материалы](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/ru "Help4.x:Menu Item: Category List/ru")                | Used to show articles belonging to a specific Category in a list layout.                                                                                                                    |
| [Меню: Создать материал](https://docs.joomla.org/Help4.x:Menu_Item:_Create_Article/ru "Help4.x:Menu Item: Create Article/ru")       | Allows users to submit an article. Normally this is available only to users who have logged in to the Frontend of the site. Users must have permission to create articles.                  |
| <span class="mw-selflink selflink">Меню: Избранные материалы</span>                                                                 | Used to show all Articles that have been tagged as Featured. Articles are shown in a Blog Layout.                                                                                           |
| [Меню: Категории](https://docs.joomla.org/Help4.x:Menu_Item:_List_All_Categories/ru "Help4.x:Menu Item: List All Categories/ru")    | Used to show a hierarchical list of Categories. Depending on the selected options for this layout, you can click on a category Title to show the articles in that category.                 |
| [Меню: Материал](https://docs.joomla.org/Help4.x:Menu_Item:_Single_Article/ru "Help4.x:Menu Item: Single Article/ru")               | Used to show one article.                                                                                                                                                                   |
