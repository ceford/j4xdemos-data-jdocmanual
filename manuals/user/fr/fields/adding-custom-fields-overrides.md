<!-- Filename: J3.x:Adding_custom_fields/Overrides / Display title: Champs personnalisés : les substitutions -->

<span id="section-portal-heading"></span>

## Comment utiliser les champs personnalisés dans vos substitutions

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

## Utiliser les champs personnalisés dans vos substitutions

### Introduction

Le véritable pouvoir des champs personnalisés réside dans le fait que
vous pouvez l’utiliser dans vos propres substitutions. Voici un exemple
de la manière de procéder.

## Utiliser les champs personnalisés dans vos substitutions

Classiquement, tous les champs personnalisés correspondant à l'élément
en cours sont accessibles via une nouvelle propriété dans la variable
`$item` appelée `jcfields`. La propriété `$item->jcfields` est un
tableau qui contient les données suivantes par champ, un champ
ressemblant à cet exemple:

    Array
    (
        [4] => stdClass Object
            (
                [id] => 4
                [title] => article-editor
                [name] => article-editor
                [checked_out] => 0
                [checked_out_time] => 0000-00-00 00:00:00
                [note] => 
                [state] => 1
                [access] => 1
                [created_time] => 2017-04-07 12:08:59
                [created_user_id] => 856
                [ordering] => 0
                [language] => *
                [fieldparams] => Joomla\Registry\Registry Object
                    (
                        [data:protected] => stdClass Object
                            (
                                [buttons] => 
                                [width] => 
                                [height] => 
                                [filter] => 
                            )

                        [initialized:protected] => 1
                        [separator] => .
                    )

                [params] => Joomla\Registry\Registry Object
                    (
                        [data:protected] => stdClass Object
                            (
                                [hint] => 
                                [render_class] => 
                                [class] => 
                                [showlabel] => 1
                                [disabled] => 0
                                [readonly] => 0
                                [show_on] => 
                                [display] => 2
                            )

                        [initialized:protected] => 1
                        [separator] => .
                    )

                [type] => editor
                [default_value] => 
                [context] => com_content.article
                [group_id] => 0
                [label] => article-editor
                [description] => 
                [required] => 0
                [language_title] => 
                [language_image] => 
                [editor] => 
                [access_level] => Public
                [author_name] => Super User
                [group_title] => 
                [group_access] => 
                [group_state] => 
                [value] => Bar
                [rawvalue] => Bar
            )

    )

### Rendre le champ à l'aide de FieldsHelper

Pour rendre le champ, vous pouvez utiliser `FieldsHelper::render()` en
transmettant les valeurs nécessaires.

    /**
     * Renders the layout file and data on the context and does a fall back to
     * Fields afterwards.
     *
     * @param   string  $context      The context of the content passed to the helper
     * @param   string  $layoutFile   layoutFile
     * @param   array   $displayData  displayData
     *
     * @return  NULL|string
     *
     * @since  3.7.0
     */
    public static function render($context, $layoutFile, $displayData)

#### Exemple de code pour la substitution à l'aide de FieldsHelper

    // Load the FieldsHelper


    item->jcfields as $field) : ?>
        // Render the field using the fields render method
        context, 'field.render', array('field' => $field)); ?>

#### Exemple de code pour un remplacement brut

    item->jcfields as $field) : ?>
        // Render the field using the fields render method
        label . ':' . $field->value; ?>

### jcfields_ne_contient_pas_les_champs_dont_j'ai_besoin"\>`$item->jcfields` ne contient pas les champs dont j'ai besoin

La propriété `jcfields` est générée à l'aide de l'événement du plug-in
`onContentPrepare` en passant le contexte des champs. Le plugin champs
lit ensuite les champs de la base de données et ajoute les valeurs à la
propriété jcfields. Assurez-vous donc que le composant que vous utilisez
implémente également l'événement `onContentPrepare` avec le contexte que
vous utilisez pour les champs.

Si vous utilisez les composants principaux, cela devrait fonctionner
immédiatement.

### Chargement de champs individuels

Pour ajouter des champs individuels à votre contenu, commencez par
choisir des noms spécifiques pour vos champs personnalisés, à l'aide du
champ Nom **Name**, qui servira à référencer votre champ directement
dans le code de substitution. Dans l'onglet **Paramètres**, sélectionnez
**Non** dans le champ `Affichage Automatique` pour empêcher son
affichage automatique dans l'une des positions standard.

Ensuite, pour activer l'accès direct par nom aux champs personnalisés
d'une substitution, placez le code ci-dessous au début de votre fichier.
Vous devriez le faire pour chaque fichier PHP de substitution sur lequel
vous souhaitez placer des champs personnalisés individuels.

    jcfields as $jcfield)
         {
              $item->jcFields[$jcfield->name] = $jcfield;
         }
    ?>

Enfin, vous devez ajouter le code d’emplacement du champ à l’endroit où
vous souhaitez afficher l’étiquette ou la valeur du champ.

Pour ajouter le **label** du champ à votre substitution, insérez le code
ci-dessous, en remplaçant `name-of-field` par le nom du champ.

    jcFields['name-of-field']->label; ?>

Pour ajouter la valeur **value** du champ à votre substitution, insérez
le code ci-dessous, en remplaçant `name-of-field` par le nom du champ.
Attention: dans la série 3.x, **value** est en fait la **rawvalue**
<a href="https://github.com/joomla/joomla-cms/issues/20216"
class="external free" target="_blank"
rel="nofollow noreferrer noopener">https://github.com/joomla/joomla-cms/issues/20216</a>

    jcFields['name-of-field']->rawvalue; ?>

Vous pouvez ajouter ce code dans n’importe quelle partie de votre
substitution. Exemples: Le contenu d'un div, le src dans une balise
`img`, dans un attribut de classe CSS, etc.

<a
href="https://docs.joomla.org/J3.x:Adding_custom_fields/Implement_into_your_component"
id="content-button" class="button expand success">Préc: Implémentation
dans votre composant</a>
