<!-- Filename: J3.x:Adding_custom_fields/Parameters_for_all_Custom_Fields / Display title: Ajout de champs personnalisés/Paramètres pour tous les champs personnalisés -->

<span id="section-portal-heading"></span>

## Paramètres des champs personnalisés

**Les articles de cette série**

1.  [Introduction](https://docs.joomla.org/J3.x:Adding_custom_fields "Special:MyLanguage/J3.x:Adding custom fields")
2.  [Paramètres des champs
    personnalisés](https://docs.joomla.org/J3.x:Adding_custom_fields/Parameters_for_all_Custom_Fields "Special:MyLanguage/J3.x:Adding custom fields/Parameters for all Custom Fields")
3.  [Champ
    Calendrier](https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field "Special:MyLanguage/J3.x:Adding custom fields/Calendar Field")
4.  [Champ Cases à
    cocher](https://docs.joomla.org/J3.x:Adding_custom_fields/Checkboxes_Field "Special:MyLanguage/J3.x:Adding custom fields/Checkboxes Field")
5.  [Champ
    Couleur](https://docs.joomla.org/J3.x:Adding_custom_fields/Color_Field "Special:MyLanguage/J3.x:Adding custom fields/Color Field")
6.  [Champ
    Editeur](https://docs.joomla.org/J3.x:Adding_custom_fields/Editor_Field "Special:MyLanguage/J3.x:Adding custom fields/Editor Field")
7.  [Champ Entier
    relatif](https://docs.joomla.org/J3.x:Adding_custom_fields/Integer_Field "Special:MyLanguage/J3.x:Adding custom fields/Integer Field")
8.  [Champ
    Liste](https://docs.joomla.org/J3.x:Adding_custom_fields/List_Field "Special:MyLanguage/J3.x:Adding custom fields/List Field")
9.  [Champ Liste
    d'images](https://docs.joomla.org/J3.x:Adding_custom_fields/ListOfImages_Field "Special:MyLanguage/J3.x:Adding custom fields/ListOfImages Field")
10. [Champ
    Média](https://docs.joomla.org/J3.x:Adding_custom_fields/Media_Field "Special:MyLanguage/J3.x:Adding custom fields/Media Field")
11. [Champ Bouton
    Radio](https://docs.joomla.org/J3.x:Adding_custom_fields/Radio_Field "Special:MyLanguage/J3.x:Adding custom fields/Radio Field")
12. [Champ
    Répétabilité](https://docs.joomla.org/J3.x:Adding_custom_fields/Repeatable_Field "Special:MyLanguage/J3.x:Adding custom fields/Repeatable Field")
13. [Champ
    Sql](https://docs.joomla.org/J3.x:Adding_custom_fieldshttps://docs.joomla.org/J3.x:Adding%20custom%20fields/Sql%20Field)
14. [Champ
    Texte](https://docs.joomla.org/J3.x:Adding_custom_fields/Text_Field "Special:MyLanguage/J3.x:Adding custom fields/Text Field")
15. [Champ Zone de
    texte](https://docs.joomla.org/J3.x:Adding_custom_fields/Textarea_Field "Special:MyLanguage/J3.x:Adding custom fields/Textarea Field")
16. [Champ
    URL](https://docs.joomla.org/J3.x:Adding_custom_fields/Url_Field "Special:MyLanguage/J3.x:Adding custom fields/Url Field")
17. [Champ
    Utilisateur](https://docs.joomla.org/J3.x:Adding_custom_fields/User_Field "Special:MyLanguage/J3.x:Adding custom fields/User Field")
18. [Champ Groupe
    d'utilisateurs](https://docs.joomla.org/J3.x:Adding_custom_fields/Usergroup_Field "Special:MyLanguage/J3.x:Adding custom fields/Usergroup Field")
19. [Comment grouper les champs
    personnalisés](https://docs.joomla.org/J3.x:Adding_custom_fields/How%CC%9E_can_you_group_custom_fields "Special:MyLanguage/J3.x:Adding custom fields/How̞ can you group custom fields")
20. [Quels sont les composants supportant les champs
    personnalisés](https://docs.joomla.org/J3.x:Adding_custom_fields/What_components_are_supporting_custom_fields "Special:MyLanguage/J3.x:Adding custom fields/What components are supporting custom fields")
21. [Implémentation dans votre
    composant](https://docs.joomla.org/J3.x:Adding_custom_fields/Implement_into_your_component "Special:MyLanguage/J3.x:Adding custom fields/Implement into your component")
22. [Utiliser les champs personnalisés dans vos
    substitutions](https://docs.joomla.org/J3.x:Adding_custom_fields/Overrides "Special:MyLanguage/J3.x:Adding custom fields/Overrides")

## Paramètres pour tous les Champs personnalisés

La liste des champs personnalisés sera initialement vide. Cliquez sur
**Nouveau** pour ajouter un champ.  
Dans l'onglet **Général** , remplissez les données obligatoires:

- Titre  
  Le titre du champ. Le titre s'affichera dans la page du gestionnaire
  de champs où vous pourrez ouvrir le champ pour le modifier en cliquant
  sur le titre. Le titre ne s'affiche pas lorsque vous créez un article
  ou un contact, ni dans le site.
- Nom  
  Le nom sera utilisé pour identifier le champ. Laissez ce champ vide et
  Joomla! remplira automatiquement une valeur par défaut à partir du
  titre.
- Type  
  Si vous créez un champ, vous pouvez choisir l’un des 16 types de
  champs. Lorsque vous enregistrez le champ, ce type est permanent. Vous
  ne pouvez pas le changer plus tard.

Pour chaque champ, vous pouvez utiliser ces paramètres:

- Label  
  Utilisez un texte descriptif du champ pour le libellé du champ. Ce
  texte n'est pas traduisible. Si vous ne saisissez aucun texte pour un
  libellé, le titre sera également utilisé comme libellé.
- Description  
  La description du champ. Un texte qui sera affiché comme une
  info-bulle lorsque l'utilisateur déplacera la souris sur la zone de
  texte pendant qu'il l'utilisera dans l'administration en créant un
  article ou un contact ou un composant tiers prenant en charge les
  champs personnalisés. Ce texte n'est pas traduisible. Vous ne voyez
  pas cette description dans le site.
- Requis  
  Est-ce un champ personnalisé obligatoire? Dans ce cas, le champ doit
  être rempli avant de soumettre un article, un contact ou un composant
  tiers prenant en charge des champs personnalisés. Vous pouvez choisir
  les options *Oui* ou *Non*.
- Valeur par défaut  
  Ici, vous pouvez définir une valeur par défaut pour le champ
  personnalisé. Ce texte n'est pas traduisible. Notez que dans certains
  champs de la liste, vous devez entrer la valeur par défaut et dans
  d’autres, l’index.
- Statut  
  Vous pouvez définir un état de publication. Le champ est-il *Publié*,
  *Non publié*, *Archivé* ou *Dans la corbeille* ?
  - Publié : le champ est visible lors de la modification d'un article
    ou d'un contact. Et il est visible dans sur le site.
  - Non publié : le champ n'est pas visible par les utilisateurs lors de
    la modification d'un article ou d'un contact.
  - Archivé : le champ ne sera plus visible dans l'édition d'un article
    ou d'un contact. Vous pouvez l'ouvrir dans le gestionnaire de champs
    lorsque vous définissez le filtre sur archivé.
  - Dans la corbeille : L'élément est supprimé du site mais reste
    présent dans la base de données. Il peut être définitivement
    supprimé de la base de données lorsque vous videz la corbeille dans
    la gestion des champs.
- Groupe du champ  
  Vous pouvez affecter un champ personnalisé à un ou plusieurs groupes
  de champs.
- Categorie  
  Vous pouvez affecter un champ personnalisé à une ou plusieurs
  catégories de champs. Notez que la valeur par défaut 'Tout' n'inclut
  pas les articles 'Non catégorisés'.
- Accès  
  Le [Niveau
  d'accès](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/fr "Special:MyLanguage/Help4.x:Users: Viewing Access Levels/fr")
  pour le champ.
- Langue  
  Sélectionnez la langue pour le champ personnalisé. Si vous n'utilisez
  pas la [fonctionnalité
  multi-langue](https://docs.joomla.org/J3.x:Setup_a_Multilingual_Site/fr "J3.x:Setup a Multilingual Site/fr")
  de Joomlaǃ, gardez la valeur par défaut à *Toutes*.
- Note  
  Un champ facultatif pour indiquer un texte personnel pour le champ.

Dans l'onglet **Paramètres** vous pouvez utiliser les paramètres :

- Indice  
  Un texte par défaut qui va apparaître dans le champ personnalisé comme
  indice pour bien remplir le champ. Cet indice est actif dans le site
  d'administration lors de la création d'un article ou un contact ou un
  composant tierce partie qui supporte les champs personnalisés. Vous ne
  le verrez pas dans le site public.
- Classe du champ  
  L'attribut de classe du champ quand le champ est affiché. Si plusieurs
  classes sont requises, séparez les avec des espaces.
- Classe du label  
  L'attribut de classe du champ dans le formulaire d'édition. Si
  plusieurs classes sont requises, séparez les avec des espaces.
- Modifiable dans  
  Sur quelle partie du site le champ doit-il être affiché. Site,
  Administration ou les deux ?
- Label  
  Affiche ou masque le label quand le champ est affiché.
- Affichage automatique  
  Joomlaǃ offre des événements de contenus qui sont déclenchés durant le
  processus de création. Vous pouvez choisir entre 'Après le titre',
  'Avant l'affichage', 'Après l'affichage' ou 'Ne pas afficher
  automatiquement'.
- Désactivé  
  Le champ doit-il être désactivé dans le formulaire d'édition.
- Affichage qu'en lecture seule  
  Le champ doit-il être en lecture seule dans le formulaire d'édition.

<a href="https://docs.joomla.org/J3.x:Adding_custom_fields"
id="content-button" class="button expand success">Précédent ː
Introduction</a> <a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field"
id="content-button" class="button expand">Suivant : Champ calendrier</a>
