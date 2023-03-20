<!-- Filename: Help4.x:Menu_Item:_List_All_Categories / Display title: Menus : Liste des catégories d'une catégorie parente -->

## Description

The List All Categories menu item type is used to show Categories in a
hierarchical list. Depending on the selected options for this layout,
you can click on a category Title to show the articles in that category.

## Comment y accéder

**Menus **→** \[name of the menu\]**

Pour ajouter un nouvel élément de menu ː

1.  Cliquez sur le bouton **Nouveau** dans la barre d'outils.
2.  Cliquez sur le bouton **sélectionner** du type de lien de menu.
3.  select the **Articles** item.
4.  select the **List All Categories in an Article Category Tree** item.

To edit a Menu Item:

- Sélectionnez un **Titre** dans la liste.

## Capture d'écran

<img
src="https://docs.joomla.org/images/thumb/2/26/Help-4x-Menus-Item-Articles-List-All-Categories-screen-fr.png/800px-Help-4x-Menus-Item-Articles-List-All-Categories-screen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/26/Help-4x-Menus-Item-Articles-List-All-Categories-screen-fr.png/1200px-Help-4x-Menus-Item-Articles-List-All-Categories-screen-fr.png 1.5x, https://docs.joomla.org/images/thumb/2/26/Help-4x-Menus-Item-Articles-List-All-Categories-screen-fr.png/1600px-Help-4x-Menus-Item-Articles-List-All-Categories-screen-fr.png 2x"
data-file-width="2880" data-file-height="1381" width="800" height="384"
alt="Help-4x-Menus-Item-Articles-List-All-Categories-screen-fr.png" />

## Champs de formulaire

- **Titre du lien**. Le titre qui sera affiché pour ce lien de menu.
- **Alias**. Le nom interne de lien de menu. Normalement, vous pouvez
  laisser ce champ vide et Joomla remplira une valeur par défaut Titre
  en minuscules et avec des tirets au lieu d'espaces. [Pour en savoir
  plus.](https://docs.joomla.org/Alias/fr "Alias/fr")

### Détails

**Left Panel**

- **Type de lien de menu**. Le type de lien de menu sélectionné lors de
  la création de ce lien de menu. Il peut s'agir d'un des types de liens
  de menu natifs ou d'un type de lien de menu fourni par une extension
  installée.
- **Sélectionner la catégorie principale**
  - Root: Include all article categories.
  - Otherwise, select the desired top-level category. All child
    categories of the selected category will show in the menu item.
- **URL du lien** : URL du lien de menu. Cette URL se créée
  automatiquement par le choix du type de lien et par ses paramètres. Ne
  peut être modifié et donné à titre d'information.
- **Fenêtre cible**. Sélectionnez dans la liste déroulante.
- **Style du template**. Sélectionnez dans la liste déroulante.

**Right Panel**

- **Menu**. Affiche dans quel menu le lien apparaîtra.

### Catégories

The Categories Options allow you to control various aspects of the menu
item.

<img
src="https://docs.joomla.org/images/thumb/6/63/Help-4x-Menus-Item-Articles-List-All-Categories-categories-subscreen-fr.png/600px-Help-4x-Menus-Item-Articles-List-All-Categories-categories-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/63/Help-4x-Menus-Item-Articles-List-All-Categories-categories-subscreen-fr.png/900px-Help-4x-Menus-Item-Articles-List-All-Categories-categories-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/6/63/Help-4x-Menus-Item-Articles-List-All-Categories-categories-subscreen-fr.png/1200px-Help-4x-Menus-Item-Articles-List-All-Categories-categories-subscreen-fr.png 2x"
data-file-width="2878" data-file-height="1344" width="600" height="280"
alt="Help-4x-Menus-Item-Articles-List-All-Categories-categories-subscreen-fr.png" />

Note: Options include "**Use Global**". If this is selected, the setting
from the [Articles:
Options](https://docs.joomla.org/Help4.x:Articles:_Options/en "Help4.x:Articles: Options/en")
will be used.

- **Top Level Category Description**. Show the description for the
  top-level category.
- **Alternative Description**. Enter an description to override the
  category description for the menu item.
- **Subcategory Levels**. Control how many levels of subcategories to
  show.
- **Empty Categories**. Show categories that don't contain any articles
  or subcategories.
- **Subcategories Descriptions**. Show the description for
  subcategories.
- **\# Articles in Category**. Show a count of the total number of
  articles in each category.

### Catégorie

The Options control the way that category information is shown in the
menu item.

<img
src="https://docs.joomla.org/images/thumb/4/47/Help-4x-Menus-Item-Articles-List-All-Categories-category-subscreen-fr.png/600px-Help-4x-Menus-Item-Articles-List-All-Categories-category-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/47/Help-4x-Menus-Item-Articles-List-All-Categories-category-subscreen-fr.png/900px-Help-4x-Menus-Item-Articles-List-All-Categories-category-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/4/47/Help-4x-Menus-Item-Articles-List-All-Categories-category-subscreen-fr.png/1200px-Help-4x-Menus-Item-Articles-List-All-Categories-category-subscreen-fr.png 2x"
data-file-width="2878" data-file-height="1344" width="600" height="280"
alt="Help-4x-Menus-Item-Articles-List-All-Categories-category-subscreen-fr.png" />

- **Category Title**. Show the title of the category.
- **Category Description**. Show the description for the category.
- **Category Image**. Show the category image.
- **Subcategory Levels**. Control how many levels of subcategories to
  show.
- **Empty Categories**. Show categories that don't contain any articles
  or subcategories.
- **No Articles Message**. Show a message "There are no articles in this
  category".
- **Subcategories Descriptions**. Show the descriptions for
  subcategories.
- **\# Articles in Category**. Show a count of the total number of
  articles in each category.

### Affichage du Blog

Blog Layout Options control the appearance of the category drill down if
that results in a blog layout.

Note: If there is a Category Blog menu item defined for a category, the
drill down will navigate to that menu item and the options for that menu
item will control the layout. The options here only take effect if there
is no menu item for a category.

<img
src="https://docs.joomla.org/images/thumb/8/84/Help-4x-Menus-Item-Articles-List-All-Categories-blog-layout-subscreen-fr.png/600px-Help-4x-Menus-Item-Articles-List-All-Categories-blog-layout-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/84/Help-4x-Menus-Item-Articles-List-All-Categories-blog-layout-subscreen-fr.png/900px-Help-4x-Menus-Item-Articles-List-All-Categories-blog-layout-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/8/84/Help-4x-Menus-Item-Articles-List-All-Categories-blog-layout-subscreen-fr.png/1200px-Help-4x-Menus-Item-Articles-List-All-Categories-blog-layout-subscreen-fr.png 2x"
data-file-width="2878" data-file-height="1334" width="600" height="278"
alt="Help-4x-Menus-Item-Articles-List-All-Categories-blog-layout-subscreen-fr.png" />

- **Classe de l'article principal**. Vous pouvez ajouter n'importe
  quelle classe CSS pour vos propres idées de style. Ajoutez une bordure
  en haut avec la classe 'boxed'.Pour la position de l'image, utilisez
  par exemple 'image-left', 'image-right'. Ajoutez 'image-alternate'
  pour un ordre alternatif des images d'intro.
- **Classe d'article**. Vous pouvez ajouter n'importe quelle classe CSS
  pour vos propres idées de style. Ajoutez une bordure en haut avec la
  classe 'boxed'.Pour la position de l'image, utilisez par exemple
  'image-left', 'image-right'. Ajoutez 'image-alternate' pour un ordre
  alternatif des images d'intro.
- **Articles en pleine largeur**. Nombre d'articles en pleine largeur à
  afficher dans le blog. "0" signifie qu'il n'y aura aucun article
  affiché en pleine largeur. Si un article a la coupure "Lire la
  suite...", seule la partie du texte avant la coupure (le texte
  d'introduction) sera affichée.
- **Introduction des articles**. Nombre d'articles dont seule
  l'introduction doit être affichée - ils seront affichés après les
  articles en pleine largeur s'il y en a. Les articles sont présentés en
  une ou plusieurs colonnes selon le paramètre "Nombre de colonnes"
  ci-dessous. Si un article a une coupure "Lire la suite...", seule la
  partie du texte avant la coupure (le texte d'introduction) sera
  affichée suivie d'un lien "Lire la suite...". L'ordre dans lequel
  s'affichent les articles est déterminé par l'Ordre de la Catégorie et
  le paramètre "Succession des articles" ci-dessous.
- **Titres avec lien**. Nombre d'articles dont seul le titre, sous forme
  de lien, doit être affiché. Ces liens permettent à un utilisateur
  d'avoir un lien vers des articles supplémentaires dans le cas où il y
  a plus d'articles que ceux affichés sur la première page du blog.
- **Inclure les sous-catégories**.
  - None: Only articles from the current category will show.
  - All: All articles from the current category and all subcategories
    will show.
  - 1-5: All articles from the current category and subcategories up to
    and including that level will show.
- **Ordre des catégories**.
  - No Order: Articles are ordered only by the Article Order, without
    regard to Category.
  - Alphabétique des titres : les articles sont affichés par titre, dans
    l'ordre alphabétique (A à Z).
  - Alphabétique inverse des titres : les articles sont affichés par
    titre, dans l'ordre alphabétique inverse (Z à A).
  - Category Order: Categories are ordered according to the Order column
    entered in [Articles:
    Categories](https://docs.joomla.org/Help4.x:Articles:_Categories/en#ordering "Help4.x:Articles: Categories/en").
- **Ordre des articles**.
  - Featured Articles Order: Articles are ordered according to the Order
    column entered in [Articles:
    Featured](https://docs.joomla.org/Help4.x:Articles:_Featured/en#ordering "Help4.x:Articles: Featured/en").
  - Most Recent First: Articles are displayed starting with the most
    recent and ending with the oldest.
  - Oldest First: Articles are displayed starting with the oldest and
    ending with the most recent.
  - Alphabétique des titres : les articles sont affichés par titre, dans
    l'ordre alphabétique (A à Z).
  - Alphabétique inverse des titres : les articles sont affichés par
    titre, dans l'ordre alphabétique inverse (Z à A).
  - Alphabétique des auteurs : les articles sont affichés par auteur,
    dans l'ordre alphabétique (A à Z).
  - Alphabétique inverse des auteurs : les articles sont affichés par
    auteur, dans l'ordre alphabétique inverse (Z à A).
  - Les plus populaires : les articles sont affichés selon le nombre de
    clics, de celui ayant le plus de clics à celui en ayant le moins.
  - Moins populaires : les articles sont affichés selon le nombre de
    clics, de celui ayant le moins de clics à celui en ayant le plus.
  - Article Order: Articles are ordered according to the Order column
    entered in
    [Articles](https://docs.joomla.org/Help4.x:Articles/en#ordering "Help4.x:Articles/en").
  - Article Reverse Order: Articles are ordered reverse to the according
    of the Order column entered in
    [Articles](https://docs.joomla.org/Help4.x:Articles/en#ordering "Help4.x:Articles/en").
- **Date for Ordering**. The date used when articles are sorted by date.
  - Créé : Utilisez la date de création de l'article.
  - Modifié : Utilisez la date de modification de l'article.
  - Publié : Utilisez la date de début de publication de l'article.

### Listes

The Options control the appearance of the category drill-down page when
that is presented as a Category List.

<img
src="https://docs.joomla.org/images/thumb/c/c8/Help-4x-Menus-Item-Articles-List-All-Categories-list-layouts-subscreen-fr.png/600px-Help-4x-Menus-Item-Articles-List-All-Categories-list-layouts-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c8/Help-4x-Menus-Item-Articles-List-All-Categories-list-layouts-subscreen-fr.png/900px-Help-4x-Menus-Item-Articles-List-All-Categories-list-layouts-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/c/c8/Help-4x-Menus-Item-Articles-List-All-Categories-list-layouts-subscreen-fr.png/1200px-Help-4x-Menus-Item-Articles-List-All-Categories-list-layouts-subscreen-fr.png 2x"
data-file-width="2878" data-file-height="1344" width="600" height="280"
alt="Help-4x-Menus-Item-Articles-List-All-Categories-list-layouts-subscreen-fr.png" />

- **Display Select**. Show the Display \# control that allows the user
  to select the number of articles to show.
- **Filter Field**. Show a text field in the Frontend where a user can
  filter the articles.Options in the Backend menu item edit.
  - Hide: Don't show a filter field.
  - Title: Filter on article title.
  - Author: Filter on the author's name.
  - Hits: Filter on the number of article hits.
- **Table Headings**. Show a heading in the article list in the
  Frontend.
- **Date**. Show a date in the list.
  - Hide: Don't show any date.
  - Created: Show the created date.
  - Modified: Show the date of the last modification.
  - Published: Show the start publishing date.
- **Date Format**. Optional format string to control the format of the
  date. [Quick Tip](#dateformat)
- **Hits**. Show the number of hits for articles.
- **Author**. Show the name of the author.
- **\# Articles to List**. Number of articles shown in the list.

### Paramètres partagés

The Shared Options apply for Shared Options in List, Blog and Featured
unless they are changed by the menu settings.

<img
src="https://docs.joomla.org/images/thumb/1/14/Help-4x-Menus-Item-Articles-List-All-Categories-shared-subscreen-fr.png/600px-Help-4x-Menus-Item-Articles-List-All-Categories-shared-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/14/Help-4x-Menus-Item-Articles-List-All-Categories-shared-subscreen-fr.png/900px-Help-4x-Menus-Item-Articles-List-All-Categories-shared-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/1/14/Help-4x-Menus-Item-Articles-List-All-Categories-shared-subscreen-fr.png/1200px-Help-4x-Menus-Item-Articles-List-All-Categories-shared-subscreen-fr.png 2x"
data-file-width="2878" data-file-height="890" width="600" height="186"
alt="Help-4x-Menus-Item-Articles-List-All-Categories-shared-subscreen-fr.png" />

- **Pagination**. Pagination provides page links at the bottom of the
  page that allow the User to navigate to additional pages. These are
  needed if the Articles will not fit on one page.
  - Hide: Pagination links not shown. Note: Users will not be able to
    navigate to additional pages.
  - Show: Pagination links shown if needed.
  - Auto: Pagination links shown if needed.
- **Pagination Summary**. Show the current page number and total pages
  (e.g., "Page 1 of 2") at the bottom of each page.

### Paramètres

The Options determine how the articles will show in the list menu item.

<img
src="https://docs.joomla.org/images/thumb/d/d1/Help-4x-Menus-Item-Articles-List-All-Categories-options-subscreen-fr.png/600px-Help-4x-Menus-Item-Articles-List-All-Categories-options-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/d1/Help-4x-Menus-Item-Articles-List-All-Categories-options-subscreen-fr.png/900px-Help-4x-Menus-Item-Articles-List-All-Categories-options-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/d/d1/Help-4x-Menus-Item-Articles-List-All-Categories-options-subscreen-fr.png/1200px-Help-4x-Menus-Item-Articles-List-All-Categories-options-subscreen-fr.png 2x"
data-file-width="2878" data-file-height="1325" width="600" height="276"
alt="Help-4x-Menus-Item-Articles-List-All-Categories-options-subscreen-fr.png" />

**Type de mise en page**

- **Choose a Layout**. Select from the dropdown list.
- **Title**. Show the Article's Title.
- **Linked Titles**. Show the title as a link to the article.
- **Texte d'introduction**.
  - Show: The Intro Text of the article will show when you drill down to
    the article.
  - Hide: Only the part of the article after the Read More break will
    show.

**Catégorie**

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

**Auteur**

- **Author**. Show the author of the Article.
- **Link to Author's Contact Page**. Show it as a link to a Contact
  layout for that author.Note: The author must be set up as a
  [Contact](https://docs.joomla.org/Help4.x:Contacts:_Edit/en "Help4.x:Contacts: Edit/en").
  Also, a link will not show if there is an [Author
  Alias](https://docs.joomla.org/Help4.x:Articles:_Edit/en#createdbyalias "Help4.x:Articles: Edit/en")
  value for the article.

**Date**

- **Create Date**. Show the Article's create date.
- **Modify Date**. Show the Article's modify date.
- **Publish Date**. Show the Article's start publishing date.

**Paramètres**

- **Navigation**. Show a navigation link 'Prev' or 'Next' when you drill
  down to the article.
- **"Read More" Link**. Show the Read More link to link from the part of
  the article before the Read More break to the rest of the Article.
- **Titre de l'article dans le lien**.
  - Show: The article title is part of the Read More link. The link will
    be in the format "Read More: \[article title\]".
  - Hide: The link will be "Read more".
- **Hits**. Show the number of times the article has been displayed by a
  user.
- **Liens non autorisés**.
  - Yes: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - No: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.

### Intégration

The Options determine whether a news feed will be available for the page
and what information it will show.

<img
src="https://docs.joomla.org/images/thumb/e/e2/Help-4x-Menus-Item-Articles-List-All-Categories-integration-subscreen-fr.png/600px-Help-4x-Menus-Item-Articles-List-All-Categories-integration-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/e2/Help-4x-Menus-Item-Articles-List-All-Categories-integration-subscreen-fr.png/900px-Help-4x-Menus-Item-Articles-List-All-Categories-integration-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/e/e2/Help-4x-Menus-Item-Articles-List-All-Categories-integration-subscreen-fr.png/1200px-Help-4x-Menus-Item-Articles-List-All-Categories-integration-subscreen-fr.png 2x"
data-file-width="2878" data-file-height="790" width="600" height="165"
alt="Help-4x-Menus-Item-Articles-List-All-Categories-integration-subscreen-fr.png" />

- **RSS Feed Link**. If set to Show, a Feed Link will show up as a feed
  icon in the address bar of most browsers.
- **Inclure dans le flux**
  - Intro Text: Only the article's intro text will show in the feed.
  - Full Text: The entire text of the article will show in the feed.

### Paramètres communs

See [Menus: New
Item](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/en "Help4.x:Menu Item: New Item/en")
for help on fields common to all Menu Item types, including:

- [Panneau de
  droite](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/fr#rightpanel "Help4.x:Menu Item: New Item/fr")
- [Type de
  liens](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/fr#linktype "Help4.x:Menu Item: New Item/fr")
- [Affichage de la
  page](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/fr#pagedisplay "Help4.x:Menu Item: New Item/fr")
- [Métadonnées](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/fr#metadata "Help4.x:Menu Item: New Item/fr")
- [Associations](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/fr#associations "Help4.x:Menu Item: New Item/fr")
- [Assignation de
  modules](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/fr#moduleassignment "Help4.x:Menu Item: New Item/fr")

## Barre d'outils

En haut de la page, vous verrez la barre d'outils présentée dans la
[capture d'écran](#screenshot) ci-dessus.

- **Enregistrer**. Enregistre le lien de menu et reste sur le même
  écran.
- **Enregistrer & Fermer**. Enregistre le lien de menu et ferme l'écran.
  - **Enregistrer & Nouveau**. Enregistre le lien de menu et conserve
    l'écran d'édition ouvert, prêt pour la création d'un autre lien de
    menu.
- **Annuler**. Ferme l'écran et retourne à l'écran précédent sans
  enregistrer les modifications que vous auriez faites.
- **Aide**. Ouvre l'écran d'aide.

## Astuces

- Categories can be "nested" into levels, similar to folders on a disk
  drive. In theory there is no absolute limit on the number of levels
  you can have. However, as a practical matter it is recommended to keep
  the levels to a minimum. The Show All Categories layout may not work
  correctly if the number of levels shown is greater than 5.
- If you set up category titles as linkable, the user can drill down on
  the category. When they do, they will normally see either a Category
  List or Category Blog menu item, depending on which option is
  selected. If there is a pre-existing menu item for this category (for
  example, a Category Blog menu item), then that menu item will show in
  the drill down and the options set for that menu item will control the
  page display. Otherwise, the options set for the current Show All
  Categories menu item will control the page display.
- You can set the option to drill down to a list or blog in 2 places.
  - In [Articles:
    Options](https://docs.joomla.org/Help4.x:Articles:_Options/en#choosealayout "Help4.x:Articles: Options/en")
    you can set the default value for all categories.
  - In [Category:
    Edit](https://docs.joomla.org/Help4.x:Articles:_Edit_Category/en#choosealayout "Help4.x:Articles: Edit Category/en")
    you can set a value for a specific category. If this is set, it
    overrides the default value.
- Customise 'Date Format': You can use D M Y for day month year or d-m-y
  for a short version for example 17-08-05 (see
  <a href="https://php.net/search.php?show=quickref&amp;pattern=date"
  class="extiw" title="php:date">PHP: Date - Examples</a>). If left
  blank, it uses DATE_FORMAT_LC1 from your language file.

## Informations connexes

- To create a new menu see
  [Menus.](https://docs.joomla.org/Help4.x:Menus/en "Help4.x:Menus/en")
- Ce
  [portail](https://docs.joomla.org/Portal:Joomla_4/fr "Portal:Joomla 4/fr")
  rassemble des informations liées spécifiquement à Joomla 4.

|                                                                                                                                               |                                                                                                                                                                                             |
|-----------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ecrans d'aide en relation                                                                                                                     | Description                                                                                                                                                                                 |
| [Articles : Paramètres](https://docs.joomla.org/Help4.x:Articles:_Options/fr "Help4.x:Articles: Options/fr")                                  | Used to set global defaults for menu items that display articles. These default values will be used when 'Use Global' is selected for an option in an Articles menu item.                   |
| [Articles](https://docs.joomla.org/Help4.x:Articles/fr "Help4.x:Articles/fr")                                                                 | The Article list is used to find, mark featured, add and edit articles.                                                                                                                     |
| [Articles : Edition](https://docs.joomla.org/Help4.x:Articles:_Edit/fr "Help4.x:Articles: Edit/fr")                                           | This is where you can add and edit Articles. You can also select the Category for an Article and indicate whether or not it is Published and if it is selected to appear on the Front Page. |
| [Articles : Articles épinglés](https://docs.joomla.org/Help4.x:Articles:_Featured/fr "Help4.x:Articles: Featured/fr")                         | Used to control which 'Featured Articles' are displayed on the Front Page and in what order they are displayed.                                                                             |
| [Articles : catégories](https://docs.joomla.org/Help4.x:Articles:_Categories/fr "Help4.x:Articles: Categories/fr")                            | The Articles Categories list is used to find, add, and edit articles categories.                                                                                                            |
| [Menus : Articles archivés](https://docs.joomla.org/Help4.x:Menu_Item:_Article_Archived/fr "Help4.x:Menu Item: Article Archived/fr")          | Shows a customised list of articles ordered by date or title. Archived articles are no longer published but are still stored on the site.                                                   |
| [Menus : Blog d'une catégorie](https://docs.joomla.org/Help4.x:Menu_Item:_Category_Blog/fr "Help4.x:Menu Item: Category Blog/fr")             | Used to show articles belonging to a specific Category in a blog layout. Controls the Leading Articles, Intro Articles and additional links to more Articles.                               |
| [Menus : Liste d'articles d'une catégorie](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/fr "Help4.x:Menu Item: Category List/fr") | Used to show articles belonging to a specific Category in a list layout.                                                                                                                    |
| [Menus : Créer un article](https://docs.joomla.org/Help4.x:Menu_Item:_Create_Article/fr "Help4.x:Menu Item: Create Article/fr")               | Allows users to submit an article. Normally this is available only to users who have logged in to the Frontend of the site. Users must have permission to create articles.                  |
| [Menus : Articles épinglés](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/fr "Help4.x:Menu Item: Featured Articles/fr")        | Used to show all Articles that have been tagged as Featured. Articles are shown in a Blog Layout.                                                                                           |
| <span class="mw-selflink selflink">Menus : Liste des catégories d'une catégorie parente</span>                                                | Used to show a hierarchical list of Categories. Depending on the selected options for this layout, you can click on a category Title to show the articles in that category.                 |
| [Menus : Article](https://docs.joomla.org/Help4.x:Menu_Item:_Single_Article/fr "Help4.x:Menu Item: Single Article/fr")                        | Used to show one article.                                                                                                                                                                   |
