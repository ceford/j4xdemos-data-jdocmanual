<!-- Filename: Help4.x:Articles:_Edit / Display title: Articles : Edition -->

## Description

Cet écran est utilisé pour modifier un article nouveau ou existant,
généralement à l'aide d'un éditeur Wysiwyg. L'éditeur par défaut est
TinyMCE mais si d'autres éditeurs sont installés, l'éditeur par défaut
peut être réglé sur autre chose pour l'ensemble du site ou pour des
utilisateurs individuels.

La plupart des paramètres ont des valeurs par défaut appropriées, mais
vous pouvez souhaiter définir une catégorie spécifique ou fournir des
métadonnées propres à un article.

## Comment y accéder

**Contenus **→** Articles**

Pour ajouter un article :

- Cliquez sur le bouton **Nouveau** dans la barre d'outils.

Pour modifier un article :

- Sélectionnez un article **Titre** dans la liste.

## Capture d'écran

<img
src="https://docs.joomla.org/images/thumb/4/41/Help-4x-content-article-manager-add-new-article-fr.png/800px-Help-4x-content-article-manager-add-new-article-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/41/Help-4x-content-article-manager-add-new-article-fr.png/1200px-Help-4x-content-article-manager-add-new-article-fr.png 1.5x, https://docs.joomla.org/images/thumb/4/41/Help-4x-content-article-manager-add-new-article-fr.png/1600px-Help-4x-content-article-manager-add-new-article-fr.png 2x"
data-file-width="2880" data-file-height="1576" width="800" height="438"
alt="Help-4x-content-article-manager-add-new-article-fr.png" />

## Champs de formulaire

- **Titre**. Le titre de cet article.
- **Alias**. Le nom interne de cet article. Normalement, vous pouvez
  laisser ce champ vide et Joomla remplira une valeur par défaut Titre
  en minuscules et avec des tirets au lieu d'espaces. [Pour en savoir
  plus.](https://docs.joomla.org/Alias/fr "Alias/fr")

### Contenu

**Left Panel**

- **Texte de l'article**. C'est ici que vous entrez le contenu de
  l'article. Joomla inclut des éditeurs , [Éditeur -
  TinyMCE](https://docs.joomla.org/Help4.x:Editors/en#tinymce "Help4.x:Editors/en")
  par défaut est montré ici.

<img
src="https://docs.joomla.org/images/thumb/6/6c/Help-4x-Article-Editor-buttons-fr.png/600px-Help-4x-Article-Editor-buttons-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/6c/Help-4x-Article-Editor-buttons-fr.png/900px-Help-4x-Article-Editor-buttons-fr.png 1.5x, https://docs.joomla.org/images/thumb/6/6c/Help-4x-Article-Editor-buttons-fr.png/1200px-Help-4x-Article-Editor-buttons-fr.png 2x"
data-file-width="1979" data-file-height="756" width="600" height="229"
alt="Help-4x-Article-Editor-buttons-fr.png" />

La liste déroulante du contenu du CMS permet d'accéder à un lien vers un
article, un contact, un champ, un média, un menu ou un module. [Pour en
savoir
plus.](https://docs.joomla.org/Help4.x:Editors/fr#cmscontent "Help4.x:Editors/fr")

- **Activer/Désactiver l'éditeur**. Un bouton Toggle Editor s'affiche
  sous la fenêtre d'édition. Ce bouton vous permet de basculer entre
  TinyMCE et [Éditeur - Non wysiwyg
  (Aucun)](https://docs.joomla.org/Help4.x:Editors/fr#none "Help4.x:Editors/fr").

**Right Panel**

- **Statut**. Le statut de publication de cet article.
  - Publié: L'article est visible sur le frontend du site.
  - Dépublié: L'articlet n'est pas visible pour les invités sur le
    frontend du site. Il peut être visible pour les utilisateurs
    connectés et autorisés à modifier l'article.
  - Archivé: L'article n'apparaîtra plus dans les liens de menu
    [blog](https://docs.joomla.org/Help4.x:Menu_Item:_Category_Blog/fr "Help4.x:Menu Item: Category Blog/fr")
    ou
    [liste.](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/fr "Help4.x:Menu Item: Category List/fr")
  - Dans la corbeille: L'article est supprimé du site mais reste dans la
    base de données. <a
    href="https://docs.joomla.org/index.php?title=.x:Deleting_an_Article/fr&amp;action=edit&amp;redlink=1"
    class="new" title=".x:Deleting an Article/fr (page does not exist)">Pour
    en savoir plus.</a>
- **Catégorie**. Sélectionnez la catégorie de cet article dans la zone
  de liste déroulante.
- **Épinglé**. Select Yes if article will be shown in the [Featured menu
  item.](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/en "Help4.x:Menu Item: Featured Articles/en")
- **Accès**. Le [Niveau
  d'accès](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/fr "Help4.x:Users: Viewing Access Levels/fr")
  pour voir cet élément.
- **Langue**. Sélectionnez la langue pour le champ personnalisé. Si vous
  n'utilisez pas la [fonctionnalité
  multi-langue](https://docs.joomla.org/Help4.x:Extensions:_Languages/fr "Help4.x:Extensions: Languages/fr")
  de Joomlaǃ, gardez la valeur par défaut à 'Toutes'.
- **Tags**. Attribuez des tags aux éléments de contenu. Vous pouvez
  sélectionner une étiquette ou tag dans la [liste
  prédéfinie](https://docs.joomla.org/Help4.x:Tags/fr "Help4.x:Tags/fr")
  ou en entrer une nouvelle en saisissant son nom dans le champ et en
  appuyant sur entrée.
- **Note**. Note à propos de l'élément. C'est normalement utilisé par
  l'administrateur du site (par exemple, pour indiquer des informations
  à propos de cet élément) et cela ne s'affiche pas sur le Frontend du
  site.
- **Note de version**. Optional field to identify the version of this
  article in the article's [Version
  History](https://docs.joomla.org/Help4.x:Components_Version_History/en "Help4.x:Components Version History/en").

### Images et liens

**Remarque**: Cet onglet peut être masqué par les utilisateurs disposant
d'une Permission d'Administrateur dans les [Options de
l'article](https://docs.joomla.org/Help4.x:Articles:_Options/fr "Help4.x:Articles: Options/fr").  
Cette section vous permet d'afficher des images et des liens dans vos
articles à l'aide d'une mise en page standardisée.

<img
src="https://docs.joomla.org/images/thumb/1/16/Help-4x-screenshot-article-edit-images-links-fr.png/600px-Help-4x-screenshot-article-edit-images-links-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/16/Help-4x-screenshot-article-edit-images-links-fr.png/900px-Help-4x-screenshot-article-edit-images-links-fr.png 1.5x, https://docs.joomla.org/images/thumb/1/16/Help-4x-screenshot-article-edit-images-links-fr.png/1200px-Help-4x-screenshot-article-edit-images-links-fr.png 2x"
data-file-width="2880" data-file-height="1290" width="600" height="269"
alt="Help-4x-screenshot-article-edit-images-links-fr.png" />

**Image de l'introduction**

- **Image de l'introduction**. Click the Select button to select an
  image to be displayed in a fixed location in the Intro Text of this
  article. This will open a window that allows you to select an image
  from your images folder. [Pour en savoir
  plus.](https://docs.joomla.org/Adding_an_image_to_an_article/fr "Adding an image to an article/fr")
- **Description d'image (balise alt)**. Set the alt attribute for this
  image. A few descriptive words for screen readers.
- **Aucune description**. Check in the rare instance of a purely
  decorative image. Note that if the Image Description is empty and the
  No Description checkbox is unchecked then the image will fail to meet
  accessibility criteria. If an image description is present this
  checkbox has no effect.
- **Classe de l'image**. Vous pouvez ajouter n'importe quelle classe CSS
  pour vos propres idées de style. Pour la position de l'image, utilisez
  par exemple 'float-start' et 'float-end'.
  <a href="https://cassiopeia.joomla.com/help" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">Pour en savoir
  plus.</a>
- **Légende**. Légende attachée à l'image.

**Image de l'article complet**

- **Image de l'article complet**. Click the Select button to select an
  image to be displayed in a fixed location in the Full Text of this
  article. This will open a window that allows you to select an image
  from your images folder. [Pour en savoir
  plus.](https://docs.joomla.org/Adding_an_image_to_an_article/fr "Adding an image to an article/fr")
- **Description d'image (balise alt)**. Set the alt attribute for this
  image. A few descriptive words for screen readers.
- **Aucune description**. Check in the rare instance of a purely
  decorative image. Note that if the Image Description is empty and the
  No Description checkbox is unchecked then the image will fail to meet
  accessibility criteria. If an image description is present this
  checkbox has no effect.
- **Classe de l'image**. Vous pouvez ajouter n'importe quelle classe CSS
  pour vos propres idées de style. Pour la position de l'image, utilisez
  par exemple 'float-start' et 'float-end'.
  <a href="https://cassiopeia.joomla.com" class="external text"
  target="_blank" rel="nofollow noreferrer noopener">Pour en savoir
  plus.</a>
- **Légende**. Légende attachée à l'image.

**Lien A**

- **Lien A**. Lien vers lequel les utilisateurs seront redirigés. Doit
  être une URL complète incluant l'entête 'https://'.
- **Texte du lien A**. Texte à afficher pour ce lien. Si laissé vide,
  l'URL sera affichée.
- **Cible de l'URL**. Fenêtre cible du navigateur lorsque le lien de
  menu est cliqué. Les choix sont :
  - Ouvrir dans la fenêtre parente: Ouvre le lien dans la fenêtre
    principale du navigateur, en remplacement de l'article de Joomla!
    actuel.
  - Ouvrir dans une nouvelle fenêtre: Ouvre le lien dans une nouvelle
    fenêtre du navigateur.
  - Ouvrir en pop-up: Ouvre le lien dans une nouvelle fenêtre pop-up du
    navigateur (sans les contrôles de navigation complets).
  - Modale: Ouvre le lien dans une fenêtre modale.

**Lien B**, **Lien C**: Same options as Link A.

### Paramètres

**Remarque**: Cet onglet peut être masqué par les utilisateurs disposant
d'une Permission d'Administrateur dans les [Options de
l'article](https://docs.joomla.org/Help4.x:Articles:_Options/fr "Help4.x:Articles: Options/fr").  
Il s'agit d'un ensemble d'options que vous pouvez utiliser pour
contrôler le mode d'affichage de cet article dans la présentation sous
forme de blog, En vedette ou Catégorie. Joomla vous permet de définir
ces options aux niveaux suivants:

<img
src="https://docs.joomla.org/images/thumb/0/0a/Help-4x-screenshot-article-edit-article-options-fr.png/600px-Help-4x-screenshot-article-edit-article-options-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/0a/Help-4x-screenshot-article-edit-article-options-fr.png/900px-Help-4x-screenshot-article-edit-article-options-fr.png 1.5x, https://docs.joomla.org/images/thumb/0/0a/Help-4x-screenshot-article-edit-article-options-fr.png/1200px-Help-4x-screenshot-article-edit-article-options-fr.png 2x"
data-file-width="2880" data-file-height="1290" width="600" height="269"
alt="Help-4x-screenshot-article-edit-article-options-fr.png" />

**Type de mise en page**

- **Type de mise en page**. Use a layout from the supplied article view
  or [overrides in the
  templates](https://docs.joomla.org/Help4.x:Templates:_Customise/en "Help4.x:Templates: Customise/en").
- **Titre de l'article**. Show the Article's Title.
- **Lien sur les titres**. Show the title as a link to the article.
- **Tags de l'article**. Enter tags for this article. Select existing
  tags by entering in the first few letters or create new tags by
  entering them here. [Learn
  more.](https://docs.joomla.org/J4.x:How_To_Use_Content_Tags_in_Joomla/en "J4.x:How To Use Content Tags in Joomla/en")
- **Texte d'introduction**.
  - Afficher: The Intro Text of the article will show when you drill
    down to the article.
  - Masquer: Only the part of the article after the Read More break will
    show.
- **Position des informations**.
  - Au-dessus: Puts the article information block above the text.
  - Au-dessous: Puts the article information block below the text.
  - Diviser: Splits the article information block into 2 separate
    blocks. One block is above and the other is below the text.
- **Titre d'informations d'article**. Displays 'Details' on top of the
  article information block.

**Catégorie**

- **Catégorie**. Show the Article's Category Title.
- **Lien sur les titres**. Show the title as a link to that Category.
- **Catégorie parente**. Show the Article's Parent Category Title.
- **Lien de catégorie parente**. Show the title as a link to that
  Category.

**Associations**

- **Associations multilingues**. Show the associated flags or Language
  Code. [Multilingual
  only.](https://docs.joomla.org/Help4.x:Multilingual_Associations/en "Help4.x:Multilingual Associations/en")

**Auteur**

- **Auteur**. Show the author of the Article.
- **Lien vers sa page de contact**. Activer le lien sur le nom de
  l'auteur vers sa page de contact.Note: The author must be [set up as a
  Contact](https://docs.joomla.org/Help4.x:Contacts/en "Help4.x:Contacts/en").

**Date**

- **Date de création**. Show the Article's create date.
- **Date de modification**. Show the Article's modify date.
- **Date de Publication**. Show the Article's start publishing date.

**Paramètres**

- **Navigation entre articles**. Afficher ou masquer un lien de
  navigation (par exemple, Suivant, Précédent) entre les articles.
- **Nombre d'affichages**. Show the number of times the article has been
  displayed by a user.
- **Liens non autorisés**. If Yes, the Intro Text for restricted
  articles will show. Clicking on the Read more link will require users
  to log in to view the full article content.
- **Positionnement des liens.**
  - Au-dessus: Links are shown above the content.
  - Au-dessous: Links are shown below the content.
- **Texte 'Lire la suite...'**. Customise the text that shows for the
  default wording 'Read more'.
- **Page de titre du navigateur**. Text for the Browser page title to be
  used when the article is viewed with a non-article menu item. If
  blank, the article's title is used instead.

### Champs

This section shows the [custom
fields](https://docs.joomla.org/Help4.x:Fields/en "Help4.x:Fields/en")
which are defined for this article.

<img
src="https://docs.joomla.org/images/thumb/8/82/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-fr.png/600px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/82/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-fr.png/900px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/8/82/Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-fr.png/1200px-Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-fr.png 2x"
data-file-width="2880" data-file-height="584" width="600" height="122"
alt="Help-4x-Content-Article-Manager-Edit-Fields-options-subscreen-fr.png" />

### Publication

**Remarque**: Cet onglet peut être masqué par les utilisateurs disposant
d'une Permission d'Administrateur dans les [Options de
l'article](https://docs.joomla.org/Help4.x:Articles:_Options/fr "Help4.x:Articles: Options/fr").  
This section allows you to enter parameters and
[Metadata](https://docs.joomla.org/Using_The_Meta_Description/en "Using The Meta Description/en")
for this Article.

<img
src="https://docs.joomla.org/images/thumb/e/e4/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-fr.png/600px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/e4/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-fr.png/900px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/e/e4/Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-fr.png/1200px-Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-fr.png 2x"
data-file-width="2880" data-file-height="1290" width="600" height="269"
alt="Help-4x-Content-Article-Manager-Edit-publishing-options-subscreen-fr.png" />

**Publication**

- **Début de publication**. Date et heure du début de publication.
  Utilisez ce champ si vous souhaitez intégrer du contenu à l'avance et
  le publier automatiquement à une date ultérieure.
- **Fin de publication**. Date and time to finish publishing. The
  article is automatically changed to Unpublished state at a future
  time.
- **Épingler**. Date and time to start featured state. Enter article
  ahead of time and then have it featured automatically at a future
  time.
- **Désépingler**. Date and time to finish featured state. The article
  is automatically changed to Unfeatured state at a future time.
- **Date de création**. Ce champ indique par défaut la date et l'heure
  de création de l'article. Vous pouvez indiquer une date et une heure
  différentes ou cliquer sur l'icône de calendrier pour trouver la daté
  souhaitée.
- **Créé par (auteur)**. Nom de l'utilisateur Joomla! qui a créé cet
  élément. Par défaut, l'utilisateur connecté. Si vous souhaitez
  indiquer un autre utilisateur, cliquez sur le bouton 'Sélectionner un
  utilisateur' pour sélectionner un utilisateur différent.
- **Créé par (alias)**. Enter in an alias for the Author of this
  Article. This allows you to display a different Author name.
- **Date de modification**. Date of last modification.
- **Modifié par**. Username who performed the last modification.
- **Révision**. Number of revisions to this Article.
- **Clics**. The number of times this Article has been viewed.
- **Id**. A unique identification number for this Article, you cannot
  change this number. When creating a new Article, this field displays
  "0" until you save the new entry.

**Métadonnées**

- **Description**. An paragraph to be used as the description of the
  page. [Pour en savoir
  plus.](https://docs.joomla.org/Using_The_Meta_Description/fr "Using The Meta Description/fr")
- **Mots clés**. Entry for keywords. [Pour en savoir
  plus.](https://docs.joomla.org/Using_Keywords/fr "Using Keywords/fr")
- **Robots**. The instructions for web 'robots' that browse to this
  page. Set 'Use Global' in [Global
  Configuration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/en#robots "Help4.x:Site Global Configuration/en").
- **Auteur**. Entry for an Author name within the metadata.
- **Droits légaux**. Describe what rights others have to use this
  content.

### Associations

**Remarque**: Cet onglet peut être masqué par les utilisateurs disposant
d'une Permission d'Administrateur dans les [Options de
l'article](https://docs.joomla.org/Help4.x:Articles:_Options/fr "Help4.x:Articles: Options/fr").  
Tab is shown on [Multilingual
Sites](https://docs.joomla.org/Help4.x:Multilingual_Associations/en "Help4.x:Multilingual Associations/en")
only.

<img
src="https://docs.joomla.org/images/thumb/f/f9/Help-4x-screenshot-article-edit-associations-fr.png/600px-Help-4x-screenshot-article-edit-associations-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f9/Help-4x-screenshot-article-edit-associations-fr.png/900px-Help-4x-screenshot-article-edit-associations-fr.png 1.5x, https://docs.joomla.org/images/thumb/f/f9/Help-4x-screenshot-article-edit-associations-fr.png/1200px-Help-4x-screenshot-article-edit-associations-fr.png 2x"
data-file-width="2880" data-file-height="1254" width="600" height="261"
alt="Help-4x-screenshot-article-edit-associations-fr.png" />

### Paramètres de création/modification

**Remarque**: Cet onglet peut être masqué par les utilisateurs disposant
d'une Permission d'Administrateur dans les [Options de
l'article](https://docs.joomla.org/Help4.x:Articles:_Options/fr "Help4.x:Articles: Options/fr").

<img
src="https://docs.joomla.org/images/thumb/1/15/Help-4x-screenshot-article-edit-configure-edit-screen-fr.png/600px-Help-4x-screenshot-article-edit-configure-edit-screen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/15/Help-4x-screenshot-article-edit-configure-edit-screen-fr.png/900px-Help-4x-screenshot-article-edit-configure-edit-screen-fr.png 1.5x, https://docs.joomla.org/images/thumb/1/15/Help-4x-screenshot-article-edit-configure-edit-screen-fr.png/1200px-Help-4x-screenshot-article-edit-configure-edit-screen-fr.png 2x"
data-file-width="2880" data-file-height="962" width="600" height="200"
alt="Help-4x-screenshot-article-edit-configure-edit-screen-fr.png" />

- **Paramètres de publication**. If Hide, the [Publishing Options
  tab](https://docs.joomla.org/Help4.x:Articles:_Edit/en#publishing "Help4.x:Articles: Edit/en")
  will not show in the Backend. This means that Backend users will not
  be able to edit the fields in this tab. These fields will always be
  set to their default values.
- **Paramètres d'article**. If Hide, the [Article Options
  tab](https://docs.joomla.org/Help4.x:Articles:_Edit/en#options "Help4.x:Articles: Edit/en")
  will not show in the Backend. This means that Backend users will not
  be able to edit the fields in this tab. These fields will always be
  set to their default values.
- **Images et liens en admin**. If Yes, the [Images and Links
  tab](https://docs.joomla.org/Help4.x:Articles:_Edit/en#imagesandlinks "Help4.x:Articles: Edit/en")
  will show.
- **Images et liens en frontal**. If Yes, the Images and Links tab will
  show in the Frontend article editor screen.

### Droits

**Remarque**: Cet onglet peut être masqué par les utilisateurs disposant
d'une Permission d'Administrateur dans les [Options de
l'article](https://docs.joomla.org/Help4.x:Articles:_Options/fr "Help4.x:Articles: Options/fr").  
This is where you can enter permissions for this article. [Pour en
savoir
plus.](https://docs.joomla.org/J3.x:Access_Control_List_Tutorial/fr#hierarchylevels "J3.x:Access Control List Tutorial/fr")

<img
src="https://docs.joomla.org/images/thumb/a/a7/Help-4x-screenshot-article-edit-permissions-fr.png/600px-Help-4x-screenshot-article-edit-permissions-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/a7/Help-4x-screenshot-article-edit-permissions-fr.png/900px-Help-4x-screenshot-article-edit-permissions-fr.png 1.5x, https://docs.joomla.org/images/thumb/a/a7/Help-4x-screenshot-article-edit-permissions-fr.png/1200px-Help-4x-screenshot-article-edit-permissions-fr.png 2x"
data-file-width="2880" data-file-height="1270" width="600" height="265"
alt="Help-4x-screenshot-article-edit-permissions-fr.png" />

To change the permissions for this article, do the following.

1.  Select the **Group** by clicking its title located on the left.
2.  Find the desired **Action**.
    - **Supprimer**. Users can delete this article.
    - **Modifier**. Users can edit this article.
    - **Modifier le statut**. Un utilisateur peut modifier le statut de
      publication et les informations connexes pour cette article.
3.  Sélectionnez l'autorisation souhaitée pour l'action que vous
    souhaitez modifier.
    - **Hérité**. Héritée pour les utilisateurs de ce groupe à partir
      des autorisations de [configuration
      globale](https://docs.joomla.org/Help4.x:Site_Global_Configuration/fr#permissions "Help4.x:Site Global Configuration/fr"),

[Articles
Options](https://docs.joomla.org/Help4.x:Articles:_Options/en#permissions "Help4.x:Articles: Options/en"),
or [d'options
d'articles](https://docs.joomla.org/Help4.x:Articles:_Edit_Category/fr#permissions "Help4.x:Articles: Edit Category/fr")
ou <a
href="https://docs.joomla.org/index.php?title=%245/fr%246&amp;action=edit&amp;redlink=1"
class="new" title="$5/fr$6 (page does not exist)">de catégories</a>.

1.  - **Autorisé**. Autorisé pour les utilisateurs de ce groupe.Note: If
      this action is Denied at one of the higher levels, the Allowed
      permission here will not take effect. A Denied setting cannot be
      overridden.
    - **Refusé**. Refusé pour les utilisateurs de ce groupe.

2.  Cliquez sur **Enregistrer** dans la barre d'outils située en haut à
    gauche. Lors de l'actualisation de l'écran, la colonne des Droits
    appliqués affichera les droits effectifs pour ce groupe et action.

## Barre d'outils

En haut de la page, vous verrez la barre d'outils présentée dans la
[capture d'écran](#screenshot) ci-dessus.

- **Enregistrer**. Saves the article and stays in the current screen.
- **Enregistrer & Fermer**. Saves the article and closes the current
  screen.
  - **Enregistrer & Nouveau**. Saves the article and keeps the editing
    screen open and ready to create another article.
  - **Enregistrer dans le menu**. Saves the article to a menu item and
    opens the menu item screen.
  - **Enregistrer une copie**. Saves your changes to a copy of the
    current article. Does not affect the current article.
- **Fermer**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Versions**. Opens the Article Version History window to show any
  prior versions of this article. This allows you to view older versions
  of this article and, if desired, restore from an older version. [Pour
  en savoir
  plus.](https://docs.joomla.org/Help4.x:Components_Version_History/fr "Help4.x:Components Version History/fr")
- **Aperçu**. Opens a modal dialog showing a site view of this article.
  Requires [shared
  sessions](https://docs.joomla.org/Help4.x:Site_Global_Configuration/en#sharedsessions "Help4.x:Site Global Configuration/en")
  or being logged in into the Frontend.
- **Vérification d'accessibilité**. Ouvre une fenêtre montrant les
  résultats du contrôle d'accessibilité de l'article.
- **Associations**. With a specific language set for an article, allows
  side by side editing in another language. This icon is shown on
  [Multilingual
  Sites](https://docs.joomla.org/Help4.x:Multilingual_Associations/en "Help4.x:Multilingual Associations/en")
  only.
- **Afficher/Masquer l'aide**. Show help text below some options.
- **Aide**. Ouvre l'écran d'aide.

## Astuces

- There are 2 methods to insert an image into article using the TinyMCE
  editor.
  1.  The [CMS
      Content](https://docs.joomla.org/Help4.x:Editors/en#cmscontent "Help4.x:Editors/en")
      dropdown list provides access to the [Media
      screen](https://docs.joomla.org/Help4.x:Media/en "Help4.x:Media/en")
      that lets you browse image files and upload images.
  2.  The 'Insert' dropdown list is a simple form for which you need to
      know the image url. It is used for external images.
- Les séparations '[Lire la
  suite...](https://docs.joomla.org/Help4.x:Editors/fr#readmore "Help4.x:Editors/fr")'
  vous permettent d'économiser de l'espace sur la page d'accueil ou sur
  toute page de mise en page du blog en affichant uniquement la première
  partie d'un article. '[Les sauts de
  page](https://docs.joomla.org/Help4.x:Editors/fr#pagebreak "Help4.x:Editors/fr")'
  vous permettent de proposer une navigation sur plusieurs pages pour
  les articles longs. Vous pouvez utiliser les deux sur un même article,
  si vous le souhaitez.Par exemple, vous pourriez placer un saut de page
  "Lire la suite..." après le premier paragraphe d'un article de
  plusieurs pages, et des sauts de page après chaque page. Aucune page
  de navigation ne s'affiche sur la page d'accueil jusqu'à ce que
  l'utilisateur sélectionne le lien "Lire la suite...". À ce moment-là,
  la table des matières de l'article s'affiche avec des liens vers
  chaque page.

## Informations connexes

- Ce
  [portail](https://docs.joomla.org/Portal:Joomla_4/fr "Portal:Joomla 4/fr")
  rassemble des informations liées spécifiquement à Joomla 4.

|                                                                                                                                                                       |                                                                                                                                                                                             |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ecrans d'aide en relation                                                                                                                                             | Description                                                                                                                                                                                 |
| [Articles : Paramètres](https://docs.joomla.org/Help4.x:Articles:_Options/fr "Help4.x:Articles: Options/fr")                                                          | Used to set global defaults for menu items that display articles. These default values will be used when 'Use Global' is selected for an option in an Articles menu item.                   |
| [Articles](https://docs.joomla.org/Help4.x:Articles/fr "Help4.x:Articles/fr")                                                                                         | The Article list is used to find, mark featured, add and edit articles.                                                                                                                     |
| <span class="mw-selflink selflink">Articles : Edition</span>                                                                                                          | This is where you can add and edit Articles. You can also select the Category for an Article and indicate whether or not it is Published and if it is selected to appear on the Front Page. |
| [Articles : Articles épinglés](https://docs.joomla.org/Help4.x:Articles:_Featured/fr "Help4.x:Articles: Featured/fr")                                                 | Used to control which 'Featured Articles' are displayed on the Front Page and in what order they are displayed.                                                                             |
| [Articles : catégories](https://docs.joomla.org/Help4.x:Articles:_Categories/fr "Help4.x:Articles: Categories/fr")                                                    | The Articles Categories list is used to find, add, and edit articles categories.                                                                                                            |
| [Menus : Articles archivés](https://docs.joomla.org/Help4.x:Menu_Item:_Article_Archived/fr "Help4.x:Menu Item: Article Archived/fr")                                  | Shows a customised list of articles ordered by date or title. Archived articles are no longer published but are still stored on the site.                                                   |
| [Menus : Blog d'une catégorie](https://docs.joomla.org/Help4.x:Menu_Item:_Category_Blog/fr "Help4.x:Menu Item: Category Blog/fr")                                     | Used to show articles belonging to a specific Category in a blog layout. Controls the Leading Articles, Intro Articles and additional links to more Articles.                               |
| [Menus : Liste d'articles d'une catégorie](https://docs.joomla.org/Help4.x:Menu_Item:_Category_List/fr "Help4.x:Menu Item: Category List/fr")                         | Used to show articles belonging to a specific Category in a list layout.                                                                                                                    |
| [Menus : Créer un article](https://docs.joomla.org/Help4.x:Menu_Item:_Create_Article/fr "Help4.x:Menu Item: Create Article/fr")                                       | Allows users to submit an article. Normally this is available only to users who have logged in to the Frontend of the site. Users must have permission to create articles.                  |
| [Menus : Articles épinglés](https://docs.joomla.org/Help4.x:Menu_Item:_Featured_Articles/fr "Help4.x:Menu Item: Featured Articles/fr")                                | Used to show all Articles that have been tagged as Featured. Articles are shown in a Blog Layout.                                                                                           |
| [Menus : Liste des catégories d'une catégorie parente](https://docs.joomla.org/Help4.x:Menu_Item:_List_All_Categories/fr "Help4.x:Menu Item: List All Categories/fr") | Used to show a hierarchical list of Categories. Depending on the selected options for this layout, you can click on a category Title to show the articles in that category.                 |
| [Menus : Article](https://docs.joomla.org/Help4.x:Menu_Item:_Single_Article/fr "Help4.x:Menu Item: Single Article/fr")                                                | Used to show one article.                                                                                                                                                                   |
