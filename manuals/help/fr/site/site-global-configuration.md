<!-- Filename: Help4.x:Site_Global_Configuration / Display title: Configuration globale -->

## Description

L'écran de Configuration vous permet de configurer le site Joomla avec
vos paramètres personnels. Les réglages effectués dans cet écran
s'appliquent à l'ensemble du site.

## Comment y accéder

- **Système **→** Réglages **→** Configuration globale**

## Capture d'écran

<img
src="https://docs.joomla.org/images/thumb/1/1f/Help-4x-global-configuration-screen-fr.png/750px-Help-4x-global-configuration-screen-fr.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/1f/Help-4x-global-configuration-screen-fr.png/1125px-Help-4x-global-configuration-screen-fr.png 1.5x, https://docs.joomla.org/images/thumb/1/1f/Help-4x-global-configuration-screen-fr.png/1500px-Help-4x-global-configuration-screen-fr.png 2x"
data-file-width="2720" data-file-height="1700" width="750" height="469"
alt="Help-4x-global-configuration-screen-fr.png" />

## Champs de formulaire

### Site

[Complète capture
d'écran.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Site/fr "Help4.x:Site Global Configuration Site/fr")

#### Site

- **Nom du site**. Entrez le nom de votre site Web. Il sera utilisé à
  différents endroits (par exemple, la barre de titre du navigateur en
  backend et pour les pages Site hors-ligne).
- **Site hors-ligne**. Choisissez si l'accès du site en frontal doit
  être verrouillé au public. [Pour en savoir
  plus.](https://docs.joomla.org/J3.x:Taking_the_website_temporarily_offline/fr "J3.x:Taking the website temporarily offline/fr")
  - **Message hors-ligne**.
    - Message spécifique : Le message spécifique utilise la valeur
      définie dans le champ 'Message spécifique'.
    - Message défini par la langue du site : Le message de la langue par
      défaut du site est défini dans le fichier ini du pack de langue.
  - **Image hors ligne**. Sélectionnez une image à afficher sur la page
    par défaut du site lorsqu'il est hors ligne. Si vous utilisez le
    template par défaut de Joomla, assurez-vous que l'image n'excède pas
    400px de large.
- **Édition en frontal**. A sélectionnez si vous désirez des
  pictogrammes d'édition en mouse-over pour les modules et les liens de
  menus.
- **Editeur par défaut**. Sélectionnez l'éditeur de texte par défaut.
  Les utilisateurs enregistrés pourront modifier leur préférence dans
  leurs données personnelles.
- **Captcha par défaut**. Sélectionnez le captcha par défaut pour votre
  site. Vous devrez peut-être entrer les informations requises dans le
  plugin
  [captcha](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_CAPTCHA_Group/fr "Chunk4x:Extensions Plugin Manager Edit CAPTCHA Group/fr").
- **Niveau d'accès par défaut**. Sélectionnez le niveau d'accès par
  défaut pour les nouveaux éléments.
- **Limite de liste par défaut**. Définit la longueur par défaut des
  listes dans le Backend pour tous les utilisateurs.
- **Default Feed Limit**. Select the number of content items to show in
  the feeds.
- **Feed Email Address**. The RSS and Atom newsfeeds include the
  author's email address.
  - E-mail de l'auteur : Use each author's email from
    [Users](https://docs.joomla.org/Help4.x:Users/en "Help4.x:Users/en")
    in the news feed.
  - E-mail du site : Include the site [From Email](#fromemail) address
    for each article.

#### Métadonnées

- **Site Meta Description**. Enter a description of the overall website
  that is to be used by search engines.
- **Robots**. Robots instructions.
  - index, follow: Index this page and follow the links on this page.
  - noindex, follow: Do not index this page, but still follow the links
    on the page. For example, you might do this for a site map page
    where you want the links to be indexed but you don't want this page
    to show in search engines.
  - index, nofollow: Index this page, but do not follow any links on the
    page. For example, you might want to do this for an events calendar,
    where you want the page to show in search engines but you do not
    want to index each event.
  - noindex, nofollow: Do not index this page or follow any links on the
    page.
- **Droits légaux**. Describe what rights others have to use this
  content. This is conveyed to search engines using the 'rights' meta
  tag in the HTML head.
- **Author Meta Tag**. Show the author meta tag when viewing articles.
- **Version de Joomla**. Cette fonction contrôle si la balise méta
  'generator' présente dans l'en-tête du document HTML en frontal du
  site et dans les flux Atom inclut la version exacte de votre site
  Joomla ; il est recommandé de la masquer pour des raisons de sécurité.

#### SEO

- **Search Engine Friendly URLs**. Select if the URLs are optimised for
  Search Engines.
- **Réécriture au 'vol' des URL**.
  - Apache et Litespeed : renommez 'htaccess.txt' en '.htaccess'
    <a href="https://httpd.apache.org/docs/2.4/howto/htaccess.html"
    class="external text" target="_blank"
    rel="nofollow noreferrer noopener">Pour en savoir plus.</a>
  - IIS : renommer 'web.config.txt' en 'web.config'
  - NginX : vous devez [configurer votre
    serveur](https://docs.joomla.org/Nginx/fr "Nginx/fr")
  - Autres serveurs ou si vous n'êtes pas sûr : veuillez consulter votre
    hébergeur.
- **Add Suffix to URL**. If yes, the system will add a suffix to the URL
  based on the document type.
- **Unicode Aliases**. Choose between transliteration and unicode
  aliases. Transliteration is the default.
- **Site Name in Page Titles**. Begin or end all Page Titles with the
  site name (for example, "My Site Name - My Article Name").

#### Cookie

- **Domaine du cookie**. Domaine à utiliser lors de la configuration des
  cookies de session. Insérez un point (.) devant le nom de domaine si
  le cookie doit être valide pour tous les sous-domaines.
- **Chemin des cookies**. Chemin valide de l'espace utilisé pour stocker
  les cookies.

### Système

[Complète capture
d'écran.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_System/fr "Help4.x:Site Global Configuration System/fr")

#### Débogage

- **Débogage système**. Si cette option est activée, les informations de
  diagnostic, la traduction de langues et les erreurs SQL (le cas
  échéant) seront affichées. Les informations seront affichées au bas de
  chaque page que vous consultez dans le backend et le frontend Joomla.
  Il est recommandé de désactiver ce mode sur un site en production.
- **Débogage de langue**. Sélectionnez si les indicateurs de débogage
  \*\*...\*\* ou ??...?? pour les fichiers de langue Joomla! seront
  affichés. Le débogage de langue fonctionnera sans que le débogage
  système soit activé, mais vous n'obtiendrez pas les références
  détaillées supplémentaires qui vous aideront à corriger une éventuelle
  erreur.
  - **Affichage de langue**. Afficher la chaine de traduction ou la
    valeur de langue lors du débogage des chaînes de langue.

#### Cache

- **System Cache**. Enable caching and set caching level. [Pour en
  savoir plus.](https://docs.joomla.org/Cache/fr "Cache/fr")
  - Conservative level: smaller system cache.
  - Progressive level: faster, bigger system cache, includes module
    renderers cache. Not appropriate for extremely large sites.
  - **Gestion du cache**.
    - File: Native caching mechanism is file-based. Please make sure the
      cache folders are writable.
  - **Platform Specific Caching**. Enable when HTML output on mobile
    differs from other devices.
  - **Cache Time (minutes)**. The maximum length of time in minutes for
    a cache file to be stored before it is refreshed.
  - **Path to Cache Folder**. Specify a writable folder to store cache
    files if you do not wish to use the default folder.

#### Session

- **Session Handler**. The mechanism by which Joomla identifies a User
  once they are connected to the website using non-persistent cookies.
  - Database: The database session handler is the default handler
    because it is the only one that Joomla can fully configure and
    control on its own.
  - Filesystem: The filesystem handler will be slightly more performant
    than the database handler, but it requires PHP to be configured
    properly otherwise it will crash and Joomla will be totally
    unusable.
    - **Session Save Path**. Enter a full filesystem path. Ensure the
      path has appropriate permissions for PHP to read and write files,
      and if 'session garbage collection' is enabled to delete files
      from it.If this path is not set, Joomla will rely on the PHP
      session.save_path INI configuration or fallback to the system
      temporary directory (as defined by the sys_get_temp_dir() PHP
      function).If neither of those paths are configured or the
      permissions are wrong then it's game over. To recover, edit the
      configuration.php file and set \$session_handler = 'database'.
  - Other handlers (APCu, Memcached, Redis, and WinCache) all rely on
    optional PHP extensions and may be available if your system supports
    them. APCu or WinCache may be no better than the "plain" filesystem
    option. The Memcached and Redis handlers are overkill for Joomla in
    a typical shared hosting environment. Those types of handlers
    succeed if you are deploying Joomla in a load balanced environment
    where multiple servers are involved and you need the session data
    for the application to be available across all servers.
- **Session Lifetime (minutes)**. Auto log out a User after they have
  been inactive for the entered number of minutes. Do not set too high.
- **Shared Sessions**. When enabled, a user's session is shared between
  the Frontend and Backend sections of the site. Note that changing this
  value will invalidate all existing sessions on the site.This is not
  available when the [Force HTTPS](#forcehttps) option is set to
  'Administrator Only'.
- **Suivi des métadonnées de session**.
  - Oui : Si ce paramètre est activé, des métadonnées supplémentaires
    sur la session d'un utilisateur (y compris son nom d'utilisateur,
    son ID utilisateur et l'application avec laquelle il est connecté)
    seront consignées dans la table des sessions de la base de données.
  - Non : Si ce paramètre est désactivé, les fonctionnalités dépendant
    de ces données ne seront pas disponibles.

### Serveur

[Complète capture
d'écran.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Server/fr "Help4.x:Site Global Configuration Server/fr")

#### Serveur

- **Path to Temp Folder**. Please specify a writable folder to store
  temporary files.
- **Compression GZIP**.
  - Yes: Automatically compress the generated HTML pages with Gzip,
    making them smaller and increasing your site's speed score.
  - No: If your server is already doing that for you or if it conflicts
    with third party extensions.
- **Error Reporting**. This parameter sets the level of error reporting
  to be used by PHP on the Joomla site.
  - Système par défaut : Leaves the level of error reporting to that set
    up in the server.
  - Aucun : Switches off error reporting.
  - Simple : Override the server setting to give a basic level of
    reporting.
  - Maximum : Override the server setting to reporting of all
    errors.Should your Joomla site fail to the extent that it is not
    possible to use the administrator page to activate error reporting,
    you can switch on full error reporting by editing the
    'configuration.php' file. Changing the '\$error_reporting' parameter
    in that file to a value of 'maximum' is the equivalent to setting
    Error Reporting to 'Maximum'.
- **Force HTTPS**. Force site access in the selected areas to occur only
  with HTTPS (encrypted HTTP connections with the https:// protocol
  prefix) and also force the use of secure cookies. Note, you must have
  HTTPS enabled on your server to utilise this option.

#### Emplacement

- **Website Time Zone**. Choose a city in the list to configure the date
  and time for display.

#### Services web

- **Activer CORS**. Le partage des ressources entre origines
  (<a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">CORS</a>) permet aux scripts
  exécutés dans un navigateur d'interagir avec des ressources d'une
  origine différente.
  - **Access-Control-Allow-Origin**. Spécifie l'origine autorisée à
    accéder aux services web de ce site, renvoyé en réponse d'une
    demande préalable. Par défaut : \* (=all).
  - **Access-Control-Allow-Headers**. Spécifie l'(es)en-tête(s)
    renvoyée(s) en réponse à une demande d'accès aux services web de ce
    site. Par défaut : Content-Type,X-Joomla-Token.
  - **Access-Control-Allow-Methods**. Spécifie la(les) méthode(s) de
    service web autorisée(s) à accéder à ce site, renvoyée(s) en réponse
    d'une demande préalable. Par défaut : toutes les méthodes
    disponibles pour l'itinéraire demandé.

#### Proxy

- **Derrière l'équilibreur de charge**. Si votre site se trouve derrière
  un équilibreur de charge ou un proxy inverse, activez ce paramètre
  afin que les adresses IP et les autres configurations dans Joomla en
  tiennent automatiquement compte.
- **Activer le proxy sortant**. Certains hébergeurs, par défaut,
  n'autorisent pas l'accès au réseau extérieur depuis le site et
  demandent de configurer manuellement un proxy sortant.
  - **Hôte du Proxy sortant**. Nom de domaine de l'hébergement ou
    adresse IP.
  - **Port du proxy sortant**.
  - **Identifiant du proxy sortant**. Laissez vide si votre proxy
    sortant ne nécessite pas d'authentification.
  - **Mot de passe du proxy sortant**.

#### Base de données

- **Database Type**. The type of database in use, selected during the
  installation process.Ne modifiez ce champ que si nécessaire (par
  exemple lors du transfert de la base de données sur un nouveau
  serveur/hébergement).
- **Host**. The hostname for your database entered during the
  installation process.Ne modifiez ce champ que si nécessaire (par
  exemple lors du transfert de la base de données sur un nouveau
  serveur/hébergement).
- **Database Username**. The username for access to your database
  entered during the installation process.Ne modifiez ce champ que si
  nécessaire (par exemple lors du transfert de la base de données sur un
  nouveau serveur/hébergement).
- **Database Password**. The password to be used to access the
  database.Ne modifiez ce champ que si nécessaire (par exemple lors du
  transfert de la base de données sur un nouveau serveur/hébergement).
- **Database Name**. The name for your database entered during the
  installation process.Ne modifiez ce champ que si nécessaire (par
  exemple lors du transfert de la base de données sur un nouveau
  serveur/hébergement).
- **Database Tables Prefix**. The prefix used for your database tables,
  created during the installation process.Ne modifiez ce champ que si
  nécessaire (par exemple lors du transfert de la base de données sur un
  nouveau serveur/hébergement).
- **Cryptage de la connexion**.
  - Par défaut (contrôlé par le serveur)
  - Authentification à sens unique
    - **Vérifier le certificat du serveur**.
      - **Path to CA File**. File system path.
  - Double authentification
    - **Path to Private Key File**. File system location.
    - **Path to Certificate File**. File system location.
    - **Vérifier le certificat du serveur**.
      - **Path to CA File**. File system path.
    - **Supported Cipher Suite (optional)**. No entry required (only
      recommended for experienced users) – for more details, see the
      documentation of your database.

#### E-mail

- **Envoi d'e-mail**.
  - Yes: Turn on mail sending.
  - No: Turn off mail sending. It is recommended to put the site offline
    when disabling the mail function.
- **Désactiver l'envoi en nombre**.
  - Yes: Disable the Mass Mail Users function.
  - No: Make the Mass Mail Users function active.
- **From Email**. The email address that will be used to send site
  email.
- **From Name**. Text displayed in the header "From:" field when sending
  a site email. Usually the site name.
- **Reply To Email**. The email address that will be used to receive end
  user(s) reply.
- **Reply To Name**. Text displayed in the header "To:" field when end
  user(s) replying to received email.
- **Mailer**. Select which mailer for the delivery of site email.

### Journal (log)

[Complète capture
d'écran.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Logging/fr "Help4.x:Site Global Configuration Logging/fr")

#### Journal (log)

- **Dossier 'logs'**. Joomla peut éventuellement conserver un fichier
  journal de ses propres opérations et celles des extensions tierces.
  Pour cela vous devez fournir le chemin absolu vers un dossier qui est
  accessible en écriture par PHP ; attention, s'il est manquant ou n'est
  pas accessible en écriture, Joomla ne se chargera pas du tout. Pour
  des raisons de sécurité, vous ne devez pas utiliser un dossier avec un
  accès à l'échelle du système tel que '/tmp'.
- **Journaliser l'ensemble**. Journalise tout, sauf les API obsolètes.
- **Log Deprecated API**. Logs deprecated APIs.

#### Journalisation personnalisée

- **Log Priorities**. Can be used to manage custom logging. Select the
  events you want to see in the log file. Default is 'All'. The item(s)
  can be selected/deselected by clicking the dropdown list.
- **Catégories de journalisation**. Liste de catégories de
  journalisation à inclure ou exclure, séparées par des virgules. Les
  catégories de journalisation communes incluent les éléments suivants
  mais sans s'y limiter : 'database', 'databasequery', 'database-error',
  'deprecated' et 'jerror'. Si ce champ est laissé vide, la
  journalisation personnalisée est désactivée.
- **Log Category Mode**. Sets the mode for the list of log categories
  above.

### Filtres de texte

[Complète capture
d'écran.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Text_Filters/fr "Help4.x:Site Global Configuration Text Filters/fr")

Les paramètres de filtre de texte sont appliqués à tous les champs de
l'éditeur de texte des groupes sélectionnés.

Les options de filtrage permettent de mieux contrôler le code HTML
soumis par vos fournisseurs de contenu. Vous pouvez être aussi strict ou
libéral que vous le souhaitez pour répondre aux besoins de votre site.
Le filtrage et ses paramètres par défaut offrent une bonne protection
contre les balises généralement associées aux attaques de sites web. Le
filtrage s'effectue au moment de l'enregistrement, quel que soit
l'éditeur ou le mode d'affichage utilisé (wysiwyg ou code).

### Droits

[Complète capture
d'écran.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Permissions/fr "Help4.x:Site Global Configuration Permissions/fr")

Manage the permission settings for user groups.

- **Site Login**. Site Login for users in the selected group.
- **Administrator Login**. Administrator Login for users in the selected
  group.
- **Web Services Login**. Web Services Login for users in the selected
  group.
- **Offline Access**. Allows users in the selected group to access to
  the Frontend site when site is offline.
- **Super User**. Allows users in the selected selected group to perform
  any action over the whole site regardless of any other permission
  settings.
- **Configure Options Only**. Allows users in the group to edit the
  options except the permissions of any extension.
- **Access Administration Interface**. Allows users in the selected
  group to access all of the administration interface except Global
  Configuration.
- **Create**. Allows users in the selected group to create any content
  in any extension.
- **Delete**. Allows users in the selected group to delete any content
  in any extension.
- **Edit**. Allows users in the selected group to edit any content in
  any extension.
- **Edit State**. Allows users in the selected group to edit the state
  of any content in any extension.
- **Edit Own**. Allows users in the selected group to edit any content
  they own in any extension.
- **Edit Custom Field Value**. Allows users in the selected group to
  edit any value of custom fields submitted in any extension.

Les modifications des droits s'appliqueront à ce groupe ainsi qu'aux
groupes enfants, composants et contenus.

- **Refusé** l'emporte sur tout droit hérité, ainsi que tout droit d'un
  groupe enfant, composant ou contenu ; s'il y a conflit, **Refusé** est
  appliqué.
- **Non défini** est équivalent à **Refusé** mais peut être modifié dans
  les groupes enfants, composants et contenus.

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

- La plupart, sinon la totalité, de ces paramètres peuvent être réglés
  une seule fois, puis laissés de côté.
- Si des modifications majeures doivent être apportées, envisagez de
  mettre le site hors ligne pour le tester et vous assurer que tout
  fonctionne comme attendu.
- Les réglages sont sauvegardés dans '\[Joomla\]/configuration.php'.
  Vous devez soit activer la couche FTP, soit ouvrir en écriture le
  fichier 'configuration.php' pour enregistrer vos modifications.

## Informations connexes

- [Sauvegarde d'un site Joomla! - principes de
  base](https://docs.joomla.org/Backup_Basics_for_a_Joomla!_Web_Site/fr "Backup Basics for a Joomla! Web Site/fr")
- [Listes des contrôles de
  sécurité](https://docs.joomla.org/Security_Checklist/fr "Security Checklist/fr")
- <img src="https://docs.joomla.org/images/4/49/Compat_icon_3_x_long.png"
  decoding="async" data-file-width="75" data-file-height="16" width="75"
  height="16" alt="Joomla 3.x" />
