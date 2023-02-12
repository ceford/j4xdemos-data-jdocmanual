<!-- Filename: Help4.x:Fields:_Edit / Display title: Champs : Edition -->

## Description

Cet écran est utilisé pour ajouter un nouveau champ ou modifier un champ
existant dans les articles, les contacts et les utilisateurs.

The helpscreen show as example Users.

## Comment y accéder ?

**Utilisateurs **→** Champs**

Pour ajouter un champ :

- Cliquez sur le bouton **Nouveau** dans la barre d'outils.

Pour modifier un champ :

- Sélectionnez un **Titre** dans la liste.

## Capture d'écran

<img
src="https://docs.joomla.org/images/thumb/f/f6/Help-4x-Fields-Edit-screen-fr.png/800px-Help-4x-Fields-Edit-screen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f6/Help-4x-Fields-Edit-screen-fr.png/1200px-Help-4x-Fields-Edit-screen-fr.png 1.5x, https://docs.joomla.org/images/thumb/f/f6/Help-4x-Fields-Edit-screen-fr.png/1600px-Help-4x-Fields-Edit-screen-fr.png 2x"
data-file-width="2720" data-file-height="1700" width="800" height="500"
alt="Help-4x-Fields-Edit-screen-fr.png" />

## Champs de formulaire

- **Titre**. Le titre de cet champ.

### Général

**Left Panel**

Paramètres pour tous les Champs personnalisés:

- **Type**. Si vous créez un champ, vous pouvez choisir l’un des 16
  types de champs. Lorsque vous enregistrez le champ, ce type est
  permanent. Vous ne pouvez pas le changer plus tard. [Pour en savoir
  plus.](https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field/fr "J3.x:Adding custom fields/Calendar Field/fr")
- **Nom**. Le nom sera utilisé pour identifier le champ. Laissez ce
  champ vide et Joomla! remplira automatiquement une valeur par défaut à
  partir du titre.
- **Label**. Utilisez un texte descriptif du champ pour le libellé du
  champ. Ce texte n'est pas traduisible. Si vous ne saisissez aucun
  texte pour un libellé, le titre sera également utilisé comme libellé.
- **Description**. La description du champ. Un texte qui sera affiché
  comme une info-bulle lorsque l'utilisateur déplacera la souris sur la
  zone de texte pendant qu'il l'utilisera dans l'administration en
  créant un article ou un contact ou un composant tiers prenant en
  charge les champs personnalisés. Ce texte n'est pas traduisible. Vous
  ne voyez pas cette description dans le site.
- **Requis**. Est-ce un champ personnalisé obligatoire? Dans ce cas, le
  champ doit être rempli avant de soumettre un article, un contact ou un
  composant tiers prenant en charge des champs personnalisés. Vous
  pouvez choisir les options Oui ou Non.

**Right Panel**

- **Statut**. Le statut de publication de cet champ.
  - Publié : le champ est visible lors de la modification d'un article
    ou d'un contact. Et il est visible dans sur le site.
  - Non publié : le champ n'est pas visible par les utilisateurs lors de
    la modification d'un article ou d'un contact.
  - Archivé : le champ ne sera plus visible dans l'édition d'un article
    ou d'un contact. Vous pouvez l'ouvrir dans le gestionnaire de
    [champs](https://docs.joomla.org/Help4.x:Fields/fr#selectstatus "Help4.x:Fields/fr")
    lorsque vous définissez le filtre sur archivé.
  - Dans la corbeille : L'élément est supprimé du site mais reste
    présent dans la base de données. Il peut être définitivement
    supprimé de la base de données lorsque vous videz la corbeille dans
    la gestion des
    [champs](https://docs.joomla.org/Help4.x:Fields/fr#selectstatus "Help4.x:Fields/fr").
    [Pour en savoir
    plus.](https://docs.joomla.org/J4.x:Deleting_an_Article/fr "J4.x:Deleting an Article/fr")
- **Groupe du champ**. Vous pouvez affecter un champ personnalisé à un
  ou plusieurs groupes de champs.
- **Catégorie**. Vous pouvez affecter un champ personnalisé à une ou
  plusieurs catégories de champs. Notez que la valeur par défaut 'Tout'
  n'inclut pas les articles 'Non catégorisés'.
- **Accès**. Le [Niveau
  d'accès](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/fr "Help4.x:Users: Viewing Access Levels/fr")
  pour voir cet champ.
- **Langue**. Sélectionnez la langue de cet champ. Si vous n'utilisez
  pas la [fonctionnalité
  multilingue](https://docs.joomla.org/Help4.x:Extensions:_Languages/fr "Help4.x:Extensions: Languages/fr")
  de Joomla, conservez le paramètre par défaut 'Toutes'.
- **Note**. Un champ facultatif pour indiquer un texte personnel pour le
  champ.

### Paramètres

<img
src="https://docs.joomla.org/images/thumb/4/4b/Help-4x-Fields-Edit-options-subscreen-fr.png/600px-Help-4x-Fields-Edit-options-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/4b/Help-4x-Fields-Edit-options-subscreen-fr.png/900px-Help-4x-Fields-Edit-options-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/4/4b/Help-4x-Fields-Edit-options-subscreen-fr.png/1200px-Help-4x-Fields-Edit-options-subscreen-fr.png 2x"
data-file-width="2880" data-file-height="1378" width="600" height="287"
alt="Help-4x-Fields-Edit-options-subscreen-fr.png" />

**Options de formulaire**

- **Indice**. Un texte par défaut qui va apparaître dans le champ
  personnalisé comme indice pour bien remplir le champ. Cet indice est
  actif dans le site d'administration lors de la création d'un article
  ou un contact ou un composant tierce partie qui supporte les champs
  personnalisés. Vous ne le verrez pas dans le site public.
- **Classe du champ**. L'attribut de classe du champ quand le champ est
  affiché. Si plusieurs classes sont requises, séparez les avec des
  espaces.
- **Classe du label**. CSS class to apply to the field label when it is
  in edit mode (entering input into a field).
- **Modifiable dans**. Sur quelle partie du site le champ doit-il être
  affiché. Site, Administration ou les deux ?
- **Showon Attribute**. Conditionally show or hide the field depending
  on the value of other fields. The syntax to use here, for example:
  `list-of-items:value1[OR]list-of-items:value2`
  - list-of-items – It is the *name* of an already created field on
    which this field will depends to be show.
  - value1 – Is the value need have the field on which it depends to be
    show.
  - \[OR\] – To create a choice among multiple fields. In the example,
    this field will show when *list-of-items* field have the value:
    *value1* OR *value2*
  - \[AND\] – To combine multiple fields. This field will show only when
    *list-of-items* field have the value: *value1* AND *value2*
  - You can also use value 'does not equal' as in
    **list-of-items!:value1**. The syntax will show this field only when
    *list-of-items* is not equal to *value1*
  - To show this field when *list-of-items* field has been selected and
    have not a empty value, use the syntax *list-of-items!:* (without a
    value specified).

**Note:** Subform fields handle different the identifier *name* of
*list-of-items*. If you create a Subform custom field and you add this
conditional field you are creating to there, you need use *field\[ID\]*
instead of *list-of-items*, where ID is the id of the field
*list-of-items*. Therefore, the showon attribute for this conditional
field you are creating need be: `field36:value1[OR]field36:value2` where
36 is the ID of the field 'List of items'.

**Options d'affichage**

- **Classe d'affichage**. La classe du conteneur de champ utilisée lors
  de son affichage.
- **Classe de la valeur**. Classe de la valeur affichée du champ.
- **Label**. Show the label when the field renders.
- **Classe du label**. CSS class to apply to the field label when it is
  displayed (displaying the output of a field).
- **Affichage automatique**. Joomlaǃ offre des événements de contenus
  qui sont déclenchés durant le processus de création.
  - Après le titre
  - Avant l'affichage
  - Après l'affichage
  - Ne pas afficher automatiquement
- **Préfixe**. Fixed text to be displayed before a field, for example £.
- **Suffixe**. Fixed text to be displayed after a field, for example
  EUR.
- **Affichage**. If there is a custom layout then it would be selected
  here.
- **Afficher en lecture seule**. If the field is read only (perhaps the
  user doesn't have the access level) should the field be displayed or
  hidden.

### Publication

<img
src="https://docs.joomla.org/images/thumb/2/20/Help-4x-Fields-Edit-publishing-subscreen-fr.png/600px-Help-4x-Fields-Edit-publishing-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/20/Help-4x-Fields-Edit-publishing-subscreen-fr.png/900px-Help-4x-Fields-Edit-publishing-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/2/20/Help-4x-Fields-Edit-publishing-subscreen-fr.png/1200px-Help-4x-Fields-Edit-publishing-subscreen-fr.png 2x"
data-file-width="2880" data-file-height="980" width="600" height="204"
alt="Help-4x-Fields-Edit-publishing-subscreen-fr.png" />

- **Date de création**. Ce champ indique par défaut la date et l'heure
  de création de champ. Vous pouvez indiquer une date et une heure
  différentes ou cliquer sur l'icône de calendrier pour trouver la daté
  souhaitée.
- **Créé par**. Nom de l'utilisateur Joomla! qui a créé cet champ. Par
  défaut, l'utilisateur connecté. Si vous souhaitez indiquer un autre
  utilisateur, cliquez sur le bouton 'Sélectionner un utilisateur' pour
  sélectionner un utilisateur différent.
- **Date de modification**. Date of last modification.
- **Modifié par**. Username who performed the last modification.
- **ID**. A unique identification number for this field, you cannot
  change this number. When creating a new field, this field displays "0"
  until you save the new entry.

### Droits

C'est ici que vous pouvez saisir les autorisations pour ce champ. [Pour
en savoir
plus.](https://docs.joomla.org/J3.x:Access_Control_List_Tutorial/fr#hierarchylevels "J3.x:Access Control List Tutorial/fr")

<img
src="https://docs.joomla.org/images/thumb/e/ea/Help-4x-Fields-Edit-permissions-subscreen-fr.png/600px-Help-4x-Fields-Edit-permissions-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/ea/Help-4x-Fields-Edit-permissions-subscreen-fr.png/900px-Help-4x-Fields-Edit-permissions-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/e/ea/Help-4x-Fields-Edit-permissions-subscreen-fr.png/1200px-Help-4x-Fields-Edit-permissions-subscreen-fr.png 2x"
data-file-width="2880" data-file-height="1260" width="600" height="263"
alt="Help-4x-Fields-Edit-permissions-subscreen-fr.png" />

Pour modifier les autorisations de ce champ, procédez comme suit.

1.  Sélectionnez le groupe en cliquant sur son titre.
2.  Trouvez l'action souhaitée.
    - **Supprimer**. Les utilisateurs peuvent supprimer ce champ.
    - **Modifier**. Les utilisateurs peuvent modifier ce champ.
    - **Modifier le statut**. L'utilisateur peut modifier l'état publié
      et les informations connexes pour ce champ.
    - **Modifier les valeurs des champs personnalisés**. Les
      utilisateurs peuvent modifier la valeur du champ personnalisé.
3.  Sélectionnez l'autorisation souhaitée pour l'action que vous
    souhaitez modifier.
    - fr
    - **Autorisé**. Autorisé pour les utilisateurs de ce groupe.Note: If
      this action is Denied at one of the higher levels, the Allowed
      permission here will not take effect. A Denied setting cannot be
      overridden.
    - **Refusé**. Refusé pour les utilisateurs de ce groupe.
4.  Cliquez sur **Enregistrer** dans la barre d'outils située en haut à
    gauche. Lors de l'actualisation de l'écran, la colonne des Droits
    appliqués affichera les droits effectifs pour ce groupe et action.

## Barre d'outils

En haut de la page, vous verrez la barre d'outils présentée dans la
[capture d'écran](#screenshot) ci-dessus.

- **Save**. Saves the field and stays in the current screen.
- **Save & Close**. Saves the field and closes the current screen.
  - **Save & New**. Saves the field and keeps the editing screen open
    and ready to create another field.
  - **Save as Copy**. Saves your changes to a copy of the current field.
    Does not affect the current field.
- **Fermer**. Ferme l'écran actuel et retourne à l'écran précédent sans
  enregistrer les modifications que vous avez faites.
- **Aide**. Ouvre l'écran d'aide.

## Astuces

Si vous voulez savoir comment utiliser les champs personnalisés, cliquez
sur [Gestion des champs
personnalisés](https://docs.joomla.org/J3.x:Adding_custom_fields/fr "J3.x:Adding custom fields/fr").

## Informations connexes

- Ce
  [portail](https://docs.joomla.org/Portal:Joomla_4/fr "Portal:Joomla 4/fr")
  rassemble des informations liées spécifiquement à Joomla 4.

|                                                                                                                      |                                                                                                                                                      |
|----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ecrans d'aide en relation                                                                                            | Description                                                                                                                                          |
| [Champs](https://docs.joomla.org/Help4.x:Fields/fr "Help4.x:Fields/fr")                                              | Fields are used to display additional attributes of Articles, Contacts and Users. The data are entered in the Backend and displayed in the Frontend. |
| <span class="mw-selflink selflink">Champs : Edition</span>                                                           | This is where you can add and edit Fields in Articles, Contacts, and Users.                                                                          |
| [Groupes de champs](https://docs.joomla.org/Help4.x:Field_Groups/fr "Help4.x:Field Groups/fr")                       | The Field Groups screen is used to list, add and edit Field Groups.                                                                                  |
| [Groupes de champs : Edition](https://docs.joomla.org/Help4.x:Field_Groups:_Edit/fr "Help4.x:Field Groups: Edit/fr") | Field Groups are used to collect related fields under a named Tab in a data entry form.                                                              |
