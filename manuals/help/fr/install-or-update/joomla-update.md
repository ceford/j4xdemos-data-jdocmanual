<!-- Filename: Help4.x:Joomla_Update / Display title: Mise à jour de Joomla -->

## Description

Cet écran permet de mettre à jour Joomla ! rapidement en utilisant un
package de mise à jour du dépôt de code de Joomla !

## Comment y accéder ?

- Sélectionnez **Tableau de bord de la page d'accueil **→** panneau de
  vérification des mises à jour **→** Joomla ... icon** dans le menu
  Administrateur. Ou bien...
- Sélectionnez **Système **→** Tableau de bord **→** Joomla** dans le
  menu Administrateur..

## Capture d'écran

<img
src="https://docs.joomla.org/images/7/75/Help-4x-joomla-update-manager-screen-default-en.png"
decoding="async" data-file-width="800" data-file-height="243"
width="800" height="243"
alt="Help-4x-joomla-update-manager-screen-default-en.png" />

Vous êtes sur la dernière version de Joomla, donc aucune action requise.

## Fonctionnalités

- **Vérifier les mises à jour**. Cliquez sur le bouton de la barre
  d'outils pour voir si une mise à jour est disponible.

**L'écran de mise à jour lorsqu'une mise à jour est disponible.**

<a
href="https://docs.joomla.org/index.php?title=Special:Upload&amp;wpDestFile=Help-4x-joomla-update-manager-with-updates-screen-en.png"
class="new"
title="File:Help-4x-joomla-update-manager-with-updates-screen-en.png">800px</a>

### Mise à jour en direct

Si vous n'êtes PAS sur la dernière version de Joomla, vous pouvez
installer la dernière mise à jour à partir de cet écran. Pour ce faire,
sélectionnez le bouton *Installer la mise à jour'* dans la barre
d'outils et Joomla installera les derniers fichiers de base.

**L'écran en cours de mise à jour**.

<img
src="https://docs.joomla.org/images/0/05/Help-4x-joomla-update-manager-updating-screen-en.png"
decoding="async" data-file-width="800" data-file-height="173"
width="800" height="173"
alt="Help-4x-joomla-update-manager-updating-screen-en.png" />

### Téléchargement et mise à jour

**Vérifiez la taille du paquet de mise à jour !** S'il est plus grand
que votre taille PHP Upload Size ou POST size, il échouera. Vous pouvez
peut-être augmenter ces tailles. Sinon...

<img
src="https://docs.joomla.org/images/6/63/Help-4x-joomla-update-manager-screen-upload-en.png"
decoding="async" data-file-width="800" data-file-height="632"
width="800" height="632"
alt="Help-4x-joomla-update-manager-screen-upload-en.png" />

Vous pouvez utiliser cette fonction pour mettre à jour Joomla si votre
serveur se trouve derrière un pare-feu ou s'il est incapable de
contacter les serveurs de mise à jour. Téléchargez d'abord le paquet de
mise à jour de Joomla au format ZIP depuis la page officielle de
téléchargement de Joomla.

La méthode d'installation peut avoir les valeurs suivantes :

- Écriture directe de fichiers
- Hybride (utilisation du FTP uniquement si nécessaire)
- Ecriture de fichiers par FTP

La première méthode est conseillée.

## Pour les développeurs

Des options permettent de sélectionner le type de mise à jour :

- **Défaut**. Cette option doit être utilisée pour les sites de
  production.
- **Joomla Suivant**. Pour ...
- **Test**. Pour ...

<!-- -->

- **Url personnalisée**. Pour les développeurs.

Sélectionnez le bouton **Options** dans la barre d'outils pour vérifier
ou modifier la sélection actuelle.

Si vous définissez l'URL personnalisée dans les options de mise à jour
de Joomla, après avoir sélectionné **Vérifier les mises à jour**, vous
verrez un onglet supplémentaire, Vérification avant mise à jour :

<img
src="https://docs.joomla.org/images/5/54/Help-4x-joomla-update-manager-screen-en.png"
decoding="async" data-file-width="800" data-file-height="873"
width="800" height="873"
alt="Help-4x-joomla-update-manager-screen-en.png" />

Et le panneau de mise à jour en direct sera prêt à fonctionner :

<img
src="https://docs.joomla.org/images/6/63/Help-4x-joomla-update-manager-screen-customen.png"
decoding="async" data-file-width="800" data-file-height="464"
width="800" height="464"
alt="Help-4x-joomla-update-manager-screen-customen.png" />

## Astuces

- Vous pouvez consulter les [Joomla ! Icônes de mise à jour
  rapide](https://docs.joomla.org/Help4.x:Admin_Modules:_Quick_Icons/en "Help4.x:Admin Modules: Quick Icons/en")
  dans le panneau de configuration backend.
