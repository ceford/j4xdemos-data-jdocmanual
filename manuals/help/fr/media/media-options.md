<!-- Filename: Help4.x:Media:_Options / Display title: Médias : Paramètres -->

## Description

Media Options configuration allows setting of parameters used globally
for Media. Control the file types allowed for uploading, MIME type
check, MIME type blacklisting, and more options.

## Comment y accéder ?

**Contenus **→** Médias**

- Cliquez sur le bouton **Paramètres** dans la barre d'outils.

## Capture d'écran

<img
src="https://docs.joomla.org/images/thumb/b/b2/Help-4x-Media-Options-screen-fr.png/800px-Help-4x-Media-Options-screen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/b/b2/Help-4x-Media-Options-screen-fr.png/1200px-Help-4x-Media-Options-screen-fr.png 1.5x, https://docs.joomla.org/images/thumb/b/b2/Help-4x-Media-Options-screen-fr.png/1600px-Help-4x-Media-Options-screen-fr.png 2x"
data-file-width="2720" data-file-height="1700" width="800" height="500"
alt="Help-4x-Media-Options-screen-fr.png" />

## Champs de formulaire

### Médias

- **Taille maximale (en Mo)**. Utiliser '0' pour illimité. Note : le
  serveur a une limite maximale, une valeur supérieure ne sera pas prise
  en compte.
- **Dossier des fichiers**. Indiquer un dossier pour les fichiers avec
  un chemin d'accès relatif à la racine du site web.Attention, modifier
  le dossier 'images' par défaut peut créer des problèmes avec certaines
  extensions. Ne saisissez pas de / en début de chemin.
- **Dossier des images**. Indiquer un dossier pour les images avec un
  chemin d'accès relatif à la racine du site web.Attention, ce chemin
  doit être le même que celui des fichiers ou dans un sous-dossier de
  celui-ci. Ne saisissez pas de / en début de chemin.
- **Restreindre les envois**. Restreindre l'envoi de fichier images aux
  utilisateurs des groupes de niveaux inférieurs à celui du groupe
  'Gestionnaire' si 'Fileinfo' et/ou 'MIME Magic' ne sont pas installés.
  - **Extensions autorisées**. Restreindre l'envoi de fichiers pour les
    utilisateurs de niveau inférieur au groupe 'Gestionnaire'.
  - **Vérifier les types MIME**. Utiliser 'Fileinfo' ou 'MIME Magic'
    pour vérifier les fichiers. À désactiver en cas d'erreurs de type
    'mime non valide'.
- **Legal Image Extensions (File Types)**. Types de fichier image
  (extensions) autorisés d'envoi sur le serveur (séparés par des
  virgules). Utilisé pour valider les en-têtes d'images.
- **Legal Audio Extensions (File Types)**. Types de fichier audio
  (extensions) autorisés d'envoi sur le serveur (séparés par des
  virgules). Utilisé pour valider les en-têtes audio.
- **Legal Video Extensions (File Types)**. Types de fichier vidéo
  (extensions) autorisés d'envoi sur le serveur (séparés par des
  virgules). Utilisé pour valider les en-têtes vidéo.
- **Legal Document Extensions (File Types)**. Types de fichier document
  (extensions) autorisés d'envoi sur le serveur (séparés par des
  virgules). Utilisé pour valider les en-têtes de fichier.
- **Extensions ignorées**. Extensions de fichier ignorées pour la
  vérification du type MIME et les envois restreints.
- **Types MIME autorisés.** Liste des types MIME autorisés d'envoi sur
  le serveur, séparés par des virgules.

### Droits

This section lets you set up the default [Access Control
List](https://docs.joomla.org/Access_Control_List/en "Access Control List/en")
permissions for all media.

<img
src="https://docs.joomla.org/images/thumb/1/1e/Help-4x-Media-Options-permissions-subscreen-fr.png/600px-Help-4x-Media-Options-permissions-subscreen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/1e/Help-4x-Media-Options-permissions-subscreen-fr.png/900px-Help-4x-Media-Options-permissions-subscreen-fr.png 1.5x, https://docs.joomla.org/images/thumb/1/1e/Help-4x-Media-Options-permissions-subscreen-fr.png/1200px-Help-4x-Media-Options-permissions-subscreen-fr.png 2x"
data-file-width="2002" data-file-height="1359" width="600" height="407"
alt="Help-4x-Media-Options-permissions-subscreen-fr.png" />

To change the permissions for media, do the following.

1.  Sélectionnez le **Groupe** en cliquant sur son titre situé à gauche.
2.  Trouvez l'action souhaitée.
    - **Configure ACL & Options**. Users can edit the options and
      permissions.
    - **Configure Options Only**. Users can edit the options exept the
      permissions.
    - **Accès à l'interface d'administration**. Les utilisateurs peuvent
      accéder à l'interface d'administration utilisateur.
    - **Create**. Users can create media.
    - **Delete**. Users can delete media.
    - **Edit**. Users can edit media.
3.  Sélectionnez l'autorisation souhaitée pour l'action que vous
    souhaitez modifier.
    - **Inherited**. Inherited for users in this Group from the [Global
      Configuration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/en#permissions "Help4.x:Site Global Configuration/en")
      permissions.
    - **Autorisé**. Autorisé pour les utilisateurs de ce groupe. Note:
      If this action is Denied at one of the higher levels, the Allowed
      permission here will not take effect. A Denied setting cannot be
      overridden.
    - **Refusé**. Refusé pour les utilisateurs de ce groupe.
4.  Cliquez sur **Enregistrer** dans la barre d'outils située en haut à
    gauche. Lors de l'actualisation de l'écran, la colonne des Droits
    appliqués affichera les droits effectifs pour ce groupe et action.

## Barre d'outils

En haut de la page, vous verrez la barre d'outils présentée dans la
[capture d'écran](#screenshot) ci-dessus.

- **Enregistrer**. Enregistre les paramètres et reste sur l'écran
  actuel.
- **Enregistrer & Fermer**. Enregistre les paramètres et ferme l'écran.
- **Fermer**. Ferme l'écran actuel et retourne à l'écran précédent sans
  enregistrer les modifications que vous avez faites.
- **Toggle Inline Help**. Show help text below some options.
- **Aide**. Ouvre l'écran d'aide.

## Astuces

- Si vous êtes un utilisateur débutant, vous pouvez simplement conserver
  les valeurs par défaut ici jusqu'à en savoir plus sur l'utilisation
  des paramètres globaux.
- If you are an advanced user, you can save time by creating good
  default values here.

## Informations connexes

- Related Help screen:
  [Media](https://docs.joomla.org/Help4.x:Media/en "Help4.x:Media/en").
- Tutorial: [Managing
  Media](https://docs.joomla.org/J4.x:Managing_Media/en "J4.x:Managing Media/en").
