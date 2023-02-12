<!-- Filename: J3.x:Adding_custom_fields/Checkboxes_Field / Display title: Ajout de champs personnalisés/Cases à cocher -->

<span id="section-portal-heading"></span>

## Champ Cases à cocher

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

## Le champ Cases à cocher

Fournit une case simple à cocher ou décocher.

#### Paramètres

Les paramètres spécifiques pour ce champ sont ː

- Valeurs de la case à cocher  
  Les valeurs des cases à cocher.

#### Informations connexes

Lisez [Type de champ de formulaire case à
cocher](https://docs.joomla.org/Checkbox_form_field_type "Special:MyLanguage/Checkbox form field type").

#### Captures d'écran

##### Créer le champ

Supposons que vous créez un champ avec les options présentées dans la
figure suivante.

<img
src="https://docs.joomla.org/images/thumb/d/d2/Checkbox_field_create-fr.png/800px-Checkbox_field_create-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/d2/Checkbox_field_create-fr.png/1200px-Checkbox_field_create-fr.png 1.5x, https://docs.joomla.org/images/d/d2/Checkbox_field_create-fr.png 2x"
data-file-width="1360" data-file-height="759" width="800" height="446"
alt="Checkbox field create-fr.png" />

##### Utiliser le champ en backend

Dans l'administration lors de la création d'un article ou d'un contact,
vous voyez le champ comme dans l'image suivante ː

<img
src="https://docs.joomla.org/images/thumb/7/72/Checkbox-fr.png/800px-Checkbox-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/7/72/Checkbox-fr.png 1.5x"
data-file-width="907" data-file-height="303" width="800" height="267"
alt="Checkbox-fr.png" />

##### Utiliser le champ en frontend

Sur le site public, vous pouvez voir le champ comme sur l'image
ci-dessous si seule l'option 2 est cochée. Le paramètre *Affichage
automatique* se charge de la position du champ et le modèle de site est
responsable du rendu du champ.  
Les champs sont uniquement visibles sur le site public lorsqu'ils sont
remplis avec des données dans l'article. Si le champ n'est pas requis,
pouvez-vous vous en passer ?

<img
src="https://docs.joomla.org/images/c/c2/Checkbox_field_frontend-fr.png"
decoding="async" data-file-width="800" data-file-height="180"
width="800" height="180" alt="Checkbox field frontend-fr.png" />

<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Calendar_Field"
id="content-button" class="button expand success">Précédent : Champ
calendrier</a>
<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/Color_Field"
id="content-button" class="button expand">Suivant : Champ Couleur</a>
