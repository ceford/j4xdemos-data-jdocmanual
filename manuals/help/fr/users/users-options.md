<!-- Filename: Help4.x:Users:_Options / Display title: Utilisateurs : Paramètres -->

## Description

User Options set globally for all users include

- Captcha,
- registration allowed and type of registration,
- default user group for new users,
- reset password or username counter,
- new user registration email notice to administration and more.

## Comment y accéder ?

**Utilisateurs **→** Gestion**

- Cliquez sur le bouton **Paramètres** dans la barre d'outils.

## Capture d'écran

<img
src="https://docs.joomla.org/images/thumb/a/a4/Help-4x-Users-Options-screen-fr.png/800px-Help-4x-Users-Options-screen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/a4/Help-4x-Users-Options-screen-fr.png/1200px-Help-4x-Users-Options-screen-fr.png 1.5x, https://docs.joomla.org/images/thumb/a/a4/Help-4x-Users-Options-screen-fr.png/1600px-Help-4x-Users-Options-screen-fr.png 2x"
data-file-width="2400" data-file-height="1500" width="800" height="500"
alt="Help-4x-Users-Options-screen-fr.png" />

## Champs de formulaire

### Utilisateurs

- **Autoriser l'inscription**.
  - Oui: Users can register from the Frontend of the site using the
    'Create an Account' link provided on the
    <a href="https://docs.joomla.org/Help4.x:Site_Modules:_Login/fr"
    class="new"
    title="Special:MyLanguage/Help4.x:Site Modules: Login/fr (page does not exist)">Login
    module</a>.
  - Non: The 'Create an Account' link will not show.
- **Groupe des inscrits**. The
  [group](https://docs.joomla.org/Help4.x:Users:_Groups/fr "Special:MyLanguage/Help4.x:Users: Groups/fr")
  that users are assigned to by default when they register on the site.
  Defaults to 'Registered'.
- **Groupe des visiteurs**. The group that guests are assigned to
  (Guests are visitors to the site who are not logged in). It is
  possible to create content on the site that is visible to guests but
  not visible to logged in users. <a
  href="https://magazine.joomla.org/all-issues/june-2021/explore-the-core-controlling-user-access?"
  class="external text" target="_blank" rel="noreferrer noopener">Pour en
  savoir plus.</a>
- **Envoyer le mot de passe**. Si 'Oui' est coché, le mot de passe
  initial de l'utilisateur sera inclus dans le mail envoyé lors de
  l'inscription.
- **Activation des comptes**.
  - Aucun: le nouvel inscrit est enregistré sans confirmation de la
    demande.
  - Auto activation: l'utilisateur reçoit un e-mail de confirmation de
    la demande d'inscription avec un lien sur lequel il doit cliquer
    pour activer son compte avant de se connecter.
  - Administration: l'utilisateur reçoit un e-mail de confirmation de la
    demande d'inscription avec un lien sur lequel il doit cliquer pour
    la valider. Puis, un message est envoyé aux utilisateurs des groupes
    ayant un droit de création de compte en administration du site pour
    qu'ils activent ce compte.
- **Notification administrateurs**. Send email notification to
  administrators with 'New User Account Activation' set to 'None' or
  'Self'.
- **Système Captcha**. Use
  [Captcha](https://docs.joomla.org/Help4.x:Site_Global_Configuration/fr#captcha "Special:MyLanguage/Help4.x:Site Global Configuration/fr")
  for User Account Registration, User Password reminder and Username
  reminder.
- **Paramètres dans le profil**.
  - Afficher: Users will be able to modify their
    <a href="https://docs.joomla.org/Help4.x:Users:_Edit_Profile/fr"
    class="new"
    title="Special:MyLanguage/Help4.x:Users: Edit Profile/fr (page does not exist)">Basic
    Settings</a> from the Frontend of the site.
  - Masquer: User will not be able to change these settings.
  - Langue espace frontal (Site). Default site language.
- **Modification de l'identifiant**. Allow user to change Username.

### Domaine d'e-mail

<img
src="https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-email-domain-subscreen-fr.png/600px-Help-4x-Users-Options-email-domain-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-email-domain-subscreen-fr.png/900px-Help-4x-Users-Options-email-domain-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-email-domain-subscreen-fr.png/1200px-Help-4x-Users-Options-email-domain-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="998" width="600" height="299"
alt="Help-4x-Users-Options-email-domain-subscreen-fr.png" />

- **Nom de domaine**. Vous pouvez saisir une liste de domaines d'e-mail
  autorisés et non autorisés. Par défaut tous les domaines sont
  autorisés.Les caractères génériques (\*) sont pris en charge. Par
  exemple :
  - \* (Astérisque): autorise ou interdit tous les domaines ,
  - \*.com: autorise ou interdit tous les domaines en '.com' ,
  - \*.joomla.org: autorise ou interdit tous les sous-domaines de
    'joomla.org'.
- **Règle** Autoriser ou non le domaine.

### Mots de passe

<img
src="https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-password-subscreen-fr.png/600px-Help-4x-Users-Options-password-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-password-subscreen-fr.png/900px-Help-4x-Users-Options-password-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/0/05/Help-4x-Users-Options-password-subscreen-fr.png/1200px-Help-4x-Users-Options-password-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="1181" width="600" height="354"
alt="Help-4x-Users-Options-password-subscreen-fr.png" />

- **Nbr de réinitialisations**. The maximum number of password resets
  allowed within the time period. Zero indicates no limit.
- **Temps de réinitialisation (heures)**. The time period, in hours, for
  the reset counter.
- **Longueur minimale du mot de passe**. Set the minimum lenght for a
  password.
- **Nbr minimum de chiffres**. Set the minimum number of integers that
  must be included in a password.
- **Nbr minimum de symboles**. Set the minimum number of symbols (such
  as !@#\$) required in a password.
- **Nbr minimum de majuscules**. Set the minimum number of upper case
  alphabetical characters required for a password.
- **Nbr minimum de minuscules**. Set the minimum number of lower case
  alphabetical characters required for a password.

### Authentification multifacteurs

<img
src="https://docs.joomla.org/images/thumb/0/03/Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png/600px-Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/03/Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png/900px-Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/0/03/Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png/1200px-Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="1518" width="600" height="455"
alt="Help-4x-Users-Options-multi-factor-authentication-subscreen-fr.png" />

- **Positions autorisées des modules en frontal du site**. Lors de
  l'affichage de la page d'authentification multifacteurs en frontal du
  site, tous les modules seront masqués sauf ceux qui se trouvent dans
  les positions sélectionnées ici.
- **Afficher le titre en frontal**. Devrais-je afficher un titre dans la
  page de vérification de l'authentification multifacteurs ? Notes : en
  administration le titre est toujours affiché. Si vous devez changer le
  titre, veuillez remplacer la clé de langue 'COM_USERS_HEADING_MFA' en
  utilisant le système de
  <a href="https://docs.joomla.org/Help4.x:Languages:_Overrides/fr"
  class="new"
  title="Special:MyLanguage/Help4.x:Languages: Overrides/fr (page does not exist)">Langues :
  Substitutions de traduction</a> côté administration.
- **Positions autorisées des modules en administration**. Lors de
  l'affichage de la page d'authentification multi-facteurs, tous les
  modules seront masqués sauf ceux des positions sélectionnées ici.
  Veuillez noter que les modules de la position 'title' sont toujours
  affichés : ceci est nécessaire pour afficher l'icône et le titre de la
  page d'administration.
- **Désactiver l'authentification multifacteurs**. N'importe quel
  utilisateur qui appartient à *n'importe lequel* des groupes
  d'utilisateurs suivants sera exempté de l'authentification
  multifacteurs. Même s'ils ont mis en place des méthodes
  d'authentification multifacteurs, il ne leur sera pas demandé de les
  utiliser lorsqu'ils se connecteront, ils ne seront pas non plus en
  mesure de les consulter, de les supprimer, ou de modifier leur
  configuration.
- **Imposer l'authentification multifacteurs**. N'importe quel
  utilisateur qui appartient à *n'importe quel* des groupes
  d'utilisateurs suivants sera requis pour activer l'authentification
  multifacteurs avant d'être en mesure d'utiliser le site.
- **Style du template du site**. Choisissez le style de template du site
  à utiliser dans la page d'authentification multifacteurs. 'Valeur par
  défaut' sélectionne le style de template par défaut.
- **Authentification multifacteurs après connexion silencieuse**.
  L'utilisateur doit-il passer par l'authentification multifacteurs
  après une connexion silencieuse ? La connexion silencieuse est celle
  qui ne nécessitent pas de nom d'utilisateur et mot de passe telle les
  fonctions 'Se souvenir de moi', 'WebAuthn', etc.
- **Types de réponse d'authentification en connexion silencieuse (pour
  les experts)**. Une liste séparée par des virgules des types de
  réponses d'authentification Joomla qui sont considérés comme des
  connexions silencieuses. La valeur par défaut est 'cookie'
  (fonctionnalité 'Se souvenir de moi') et 'passwordless' (WebAuthn).
- **Nouveaux utilisateurs intégrés**. Si l'utilisateur n'a pas encore
  configuré l'authentification multifacteurs et que cette option est
  activée, il sera redirigé vers la page de configuration de
  l'authentification multifacteurs ou l'URL personnalisée ci-dessous.
  Ceci est conçu pour être un moyen simple de faire savoir à vos
  utilisateurs que l'authentification multifacteurs est une option
  disponible sur votre site.
- **URL de redirection personnalisée**. Si indiquée, redirige vers l'URL
  au lieu de la page de configuration d'authentification multifacteurs
  lorsque l'option ci-dessus est activée.Attention !: Ceci doit être une
  URL interne au site, vous ne pouvez pas connecter un lien externe ou
  un sous-domaine.

### Versions

<img
src="https://docs.joomla.org/images/thumb/7/7e/Help-4x-Users-Options-user-notes-history-subscreen-fr.png/600px-Help-4x-Users-Options-user-notes-history-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/7e/Help-4x-Users-Options-user-notes-history-subscreen-fr.png/900px-Help-4x-Users-Options-user-notes-history-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/7/7e/Help-4x-Users-Options-user-notes-history-subscreen-fr.png/1200px-Help-4x-Users-Options-user-notes-history-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="516" width="600" height="155"
alt="Help-4x-Users-Options-user-notes-history-subscreen-fr.png" />

- **Activer l'historique**. Save version history for User Notes.
- **Nombre maximum de versions à conserver**.
  The maximum number of versions to store for a User Note. If a User
  Note is saved and the maximum number of versions has been reached, the
  oldest version will be deleted automatically. If set to 0, then
  versions will never be deleted automatically.Pour en savoir plus.

### Envoi en nombre

<img
src="https://docs.joomla.org/images/thumb/c/ce/Help-4x-Users-Options-mass-mail-users-subscreen-fr.png/600px-Help-4x-Users-Options-mass-mail-users-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/ce/Help-4x-Users-Options-mass-mail-users-subscreen-fr.png/900px-Help-4x-Users-Options-mass-mail-users-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/c/ce/Help-4x-Users-Options-mass-mail-users-subscreen-fr.png/1200px-Help-4x-Users-Options-mass-mail-users-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="803" width="600" height="241"
alt="Help-4x-Users-Options-mass-mail-users-subscreen-fr.png" />

- **Préfixe de l'objet**. Saisir un texte à insérer automatiquement
  avant l'objet des e-mails en masse (facultatif).
- **Suffixe du message**. Saisir un texte à insérer automatiquement à la
  fin du corps du message (par exemple, une signature) (facultatif).

### Intégration

<img
src="https://docs.joomla.org/images/thumb/0/09/Help-4x-Users-Options-integration-subscreen-fr.png/600px-Help-4x-Users-Options-integration-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/09/Help-4x-Users-Options-integration-subscreen-fr.png/900px-Help-4x-Users-Options-integration-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/0/09/Help-4x-Users-Options-integration-subscreen-fr.png/1200px-Help-4x-Users-Options-integration-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="517" width="600" height="155"
alt="Help-4x-Users-Options-integration-subscreen-fr.png" />

- **Intégration des champs**. Enable the creation of custom fields.

### Droits

This section lets you set up the default [Access Control
List](https://docs.joomla.org/Access_Control_List/fr "Special:MyLanguage/Access Control List/fr")
permissions for all users.

<img
src="https://docs.joomla.org/images/thumb/a/a2/Help-4x-Users-Options-permissions-subscreen-fr.png/600px-Help-4x-Users-Options-permissions-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/a2/Help-4x-Users-Options-permissions-subscreen-fr.png/900px-Help-4x-Users-Options-permissions-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/a/a2/Help-4x-Users-Options-permissions-subscreen-fr.png/1200px-Help-4x-Users-Options-permissions-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="1449" width="600" height="434"
alt="Help-4x-Users-Options-permissions-subscreen-fr.png" />

To change the permissions for users, do the following.

1.  Sélectionnez le groupe en cliquant sur son titre.
2.  Trouvez l'action souhaitée.
    - **Configurer les droits et paramètres**. Users can edit the
      options and permissions.
    - **Ne configurer que les paramètres**. Users can edit the options
      exept the permissions.
    - **Accès à l'interface d'administration**. Users can access user
      administration interface.
    - **Créer**. Users can create users.
    - **Supprimer**. Users can delete users.
    - **Modifier**. Users can edit users.
    - **Modifier le statut**. User can change the published state and
      related information.
    - **Modifier les valeurs des champs personnalisés**. Users can edit
      any value of custom fields submitted in users.
3.  Sélectionnez l'autorisation souhaitée pour l'action que vous
    souhaitez modifier.
    - **Hérité**. Inherited for users in this Group from the [Global
      Configuration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/fr#permissions "Special:MyLanguage/Help4.x:Site Global Configuration/fr")
      permissions.
    - **Autorisé**. Allowed for users in this Group.Note: If this action
      is Denied at one of the higher levels, the Allowed permission here
      will not take effect. A Denied setting cannot be overridden.
    - **Refusé**. Denied for users in this Group.
4.  Cliquez sur **Enregistrer** dans la barre d'outils située en haut à
    gauche. Lors de l'actualisation de l'écran, la colonne des Droits
    appliqués affichera les droits effectifs pour ce groupe et action.

## Barre d'outils

En haut de la page, vous verrez la barre d'outils présentée dans la
[capture d'écran](#screenshot) ci-dessus.

- **Enregistrer**. Saves the users options and stays in the current
  screen.
- **Enregistrer & Fermer**. Saves the users options and closes the
  current screen.
- **Fermer**. Ferme l'écran et retourne à l'écran précédent sans
  enregistrer les modifications que vous auriez faites.
- **Afficher/Masquer l'aide**. Show help text below some options.
- **Aide**. Ouvre l'écran d'aide.

## Astuces

Si vous êtes un utilisateur débutant, vous pouvez simplement conserver
les valeurs par défaut ici jusqu'à en savoir plus sur l'utilisation des
paramètres globaux.

## Informations connexes

|                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ecrans d'aide en relation                                                                                                                                         | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [Users: Options](https://docs.joomla.org/Help4.x:Users:_Options/en "Help4.x:Users: Options/en")                                                                   | User Options configuration allows setting of parameters used globally for all users. Control the use of Captcha, registration allowed and type of registration, default user group new users, reset password or username counter, and new user registration email notice to administration.                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [Utilisateurs](https://docs.joomla.org/Help4.x:Users/fr "Help4.x:Users/fr")                                                                                       | The Users list is used to find, add, and edit users.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [Users: Viewing Access Levels](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/en "Help4.x:Users: Viewing Access Levels/en")                         | In this screen you have the ability to look at a list of your Access Levels and sort them in different ways. You can also edit and create Access Levels.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| [Users: Edit Viewing Access Level](https://docs.joomla.org/Help4.x:Users:_Edit_Viewing_Access_Level/en "Help4.x:Users: Edit Viewing Access Level/en")             | Access levels control which users can view which objects on your site. Objects include menu items, modules, categories, and component items (articles, contacts, and so on). Each object in the site is assigned to one access level. User groups are also assigned to each access level.If a user is a member of a group that in turn has permission for an access level, then that user can view all objects assigned to that access level. It is important to understand that user groups can be arranged in a parent-child hierarchy. If so, then a child group has access to all access levels that the parent group has access to. So you don't need to assign a child group access to levels that its parent group already has access to. |
| [Permissions for Group](https://docs.joomla.org/Help4.x:Permissions_for_Group/en "Help4.x:Permissions for Group/en")                                              | The Debug Permissions report maps out the exact permissions for any given user group across all assets on your Joomla! installation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [Permissions for User](https://docs.joomla.org/Help4.x:Permissions_for_User/en "Help4.x:Permissions for User/en")                                                 | The Debug Permissions report allows you to map out the exact permissions for any given user across all extensions on your Joomla installation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [Users: Groups](https://docs.joomla.org/Help4.x:Users:_Groups/en "Help4.x:Users: Groups/en")                                                                      | User Groups control what actions a user may take on the site and which objects a user can view. This screen allows you to create, view, edit, and delete User Groups.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [Users: New or Edit Group](https://docs.joomla.org/Help4.x:Users:_New_or_Edit_Group/en "Help4.x:Users: New or Edit Group/en")                                     | User groups play a central role in what a user can do and see on the site. Creating user groups is normally the first step in setting up the security system for your site.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [Mass Mail Users](https://docs.joomla.org/Help4.x:Mass_Mail_Users/en "Help4.x:Mass Mail Users/en")                                                                | The Mass Mail screen allows Users who are members of the "Super Administrator" group to send an email message to registered users for the site. Users can be selected based on groups.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| [Users: Edit Profile](https://docs.joomla.org/Help4.x:Users:_Edit_Profile/en "Help4.x:Users: Edit Profile/en")                                                    | In this screen, you have the ability to create a new user (if you clicked on the 'New' button in the User Manager), or edit an existing user (if you selected a user and clicked on the 'Edit' button in the User Manager, or clicked on the name of a user).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [User Notes: Categories](https://docs.joomla.org/Help4.x:User_Notes:_Categories/en "Help4.x:User Notes: Categories/en")                                           | This screen allows you to look at a list of your user note categories and sort them in different ways. You can also edit and create user note categories and access levels.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [User Notes: New or Edit Category](https://docs.joomla.org/Help4.x:User_Notes:_New_or_Edit_Category/en "Help4.x:User Notes: New or Edit Category/en")             | This is where you can add a new Category or edit an existing Category. Categories are used to organize the User Notes. Categories allow you to display related User notes together on a page and to filter User Notes in the User Notes Manager. All User Notes are assigned either to a Category that you create or to the special Category called 'Uncategorized'.                                                                                                                                                                                                                                                                                                                                                                             |
| [User Notes](https://docs.joomla.org/Help4.x:User_Notes/en "Help4.x:User Notes/en")                                                                               | User notes are pieces of information which can be assigned to registered users on your Joomla! site. These notes can contain for example comments about 'offending' or 'difficult' users etc.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [User Notes:New or Edit](https://docs.joomla.org/Help4.x:User_Notes:_New_or_Edit/en "Help4.x:User Notes: New or Edit/en")                                         | In this screen you can create an user note or edit an user note. The 'editor' will be the chosen 'editor' for the user editing the note. Examples: TinyMCE - JCE - Codemirror.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [Menu Item: Password Reset](https://docs.joomla.org/Help4.x:Menu_Item:_Password_Reset/en "Help4.x:Menu Item: Password Reset/en")                                  | Used to create a form which allows a user to reset their password with an email sent to the user's email associated with the account.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| [Menu Item: User Profile](https://docs.joomla.org/Help4.x:Menu_Item:_User_Profile/en "Help4.x:Menu Item: User Profile/en")                                        | Used to create a form which allows a user to edit their profile settings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [Menu Item: Edit User Profile](https://docs.joomla.org/Help4.x:Menu_Item:_Edit_User_Profile/en "Help4.x:Menu Item: Edit User Profile/en")                         | Used to create a form which allows a user to edit their profile settings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [Menu Item: Registration Form](https://docs.joomla.org/Help4.x:Menu_Item:_Registration_Form/en "Help4.x:Menu Item: Registration Form/en")                         | Used to create a default User Registration form for user registration. Default form contains basic information: Name, Username, Password, and Email Address.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [Menu Item: Username Reminder Request](https://docs.joomla.org/Help4.x:Menu_Item:_Username_Reminder_Request/en "Help4.x:Menu Item: Username Reminder Request/en") | Used to create a form which allows a user to request an e-mail with their username.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
