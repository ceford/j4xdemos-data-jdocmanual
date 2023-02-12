<!-- Filename: J3.x:Adding_custom_fields/Textarea_Field / Display title: Ajout de champs personnalisés/Champ Zone de texte -->

## Champ Zone de texte

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

### Zone de texte

Fournit une zone de texte pour la saisie de texte en multi-ligne.

#### Paramètres

Les paramètres spécifiques pour ce champ sont ː

- Lignes  
  La hauteur de la zone de texte visible en nombre de lignes. Si non
  précisé, la hauteur est déterminée par le navigateur. La valeur ne
  limite pas le nombre de lignes qui peuvent être saisies. Le nombre de
  lignes est actif dans le site d'administration lors de la création
  d'un article ou d'un contact ou pour un composant tierce partie qui
  supporte les champs personnalisés. Ce paramètre n'a pas d'impact sur
  la taille du champ sur le site public.
- Colonnes  
  La largeur de la zone de texte visible en nombre de caractères. Si non
  précisé, la hauteur est déterminée par le navigateur. La valeur ne
  limite pas le nombre de caractères qui peuvent être saisis. Le nombre
  de caractères est actif dans le site d'administration lors de la
  création d'un article ou d'un contact ou pour un composant tierce
  partie qui supporte les champs personnalisés. Ce paramètre n'a pas
  d'impact sur la taille du champ sur le site public.
- Longueur maximale  
  Le nombre de caractères maximum pouvant être saisis.
- Filtre  
  Autorise le système à sauvegarder certaines balises html ou des
  données brutes.

#### Informations connexes

Lisez [Type de champ de formulaire Zone de
texte](https://docs.joomla.org/Textarea_form_field_type "Special:MyLanguage/Textarea form field type").

#### Captures d'écran

##### Créer le champ

Supposons que vous créez un champ avec les options présentées dans la
figure suivante.

<img
src="https://docs.joomla.org/images/thumb/b/b0/Textarea_field_create-fr.png/800px-Textarea_field_create-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/b/b0/Textarea_field_create-fr.png 1.5x"
data-file-width="1006" data-file-height="761" width="800" height="605"
alt="Textarea field create-fr.png" />

##### Utiliser le champ en backend

Dans l'administration lors de la création d'un article ou d'un contact,
vous voyez le champ comme dans l'image suivante ː

<img
src="https://docs.joomla.org/images/thumb/0/04/Textarea-fr.png/800px-Textarea-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/0/04/Textarea-fr.png 1.5x"
data-file-width="997" data-file-height="626" width="800" height="502"
alt="Textarea-fr.png" />

##### Utiliser le champ en frontend

Sur le site public, vous pouvez voir le champ comme sur l'image
ci-dessous. Le paramètre *Affichage automatique* se charge de la
position du champ et le modèle de site est responsable du rendu du
champ.  
Les champs sont uniquement visibles sur le site public lorsqu'ils sont
remplis avec des données dans l'article. Si le champ n'est pas requis,
pouvez-vous vous en passer ?

<img
src="https://docs.joomla.org/images/3/3d/Textarea_field_frontend-fr.png"
decoding="async" data-file-width="800" data-file-height="176"
width="800" height="176" alt="Textarea field frontend-fr.png" />

<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/Text_Field"
id="content-button" class="button expand success">Précédent : Champ
Texte</a>
<a href="https://docs.joomla.org/J3.x:Adding_custom_fields/Url_Field"
id="content-button" class="button expand">Suivant : Champ URL</a>
