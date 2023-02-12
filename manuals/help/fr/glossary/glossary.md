<!-- Filename: Help4.x:Glossary / Display title: Glossaire -->

Le Glossaire Joomla! est très utile afin de comprendre les termes
communément utilisés dans les tutoriels Joomla, les écrans d'aide et la
documentation avancée.

## [Alias](https://docs.joomla.org/Alias "Special:MyLanguage/Alias")

## Ancres

Une ancre est créée en utilisant la balise en HTML. Une ancre vous
permet de placer un "marque-page" à l'intérieur d'une page HTML. Dans
Joomla!, vous pouvez placer une ancre à l'intérieur d'un article (par
exemple, en utilisant l'éditeur
[TinyMCE](https://docs.joomla.org/Content_editors#TinyMCE_editor "Special:MyLanguage/Content editors")).
Cela vous permet de créer un lien qui emmène directement à ce point de
l'article.

Le code source HTML d'une ancre ressemble à cela :

Vous pouvez créer un lien vers une ancre au sein d'une même page en
utilisant le code HTML

Cliquer sur ce lien vous amènera directement à l'emplacement de votre
balise d'ancrage.

Vous pouvez créer un lien vers une ancre située sur une autre page en
ajoutant un "#" + le nom de l'ancre à la fin de l'URL. Dans l'exemple
suivant, si l'URL de l'article était
`http://www.monsite.com/mon_article.html`, alors vous pourriez créer un
lien direct vers l'ancre de cette page avec cette URL
`http://www.monsite.com/mon_article.html#mon_ancre`.

## Catégorie

Un site propulsé par Joomla!, ou par n'importe quel autre type de CMS, a
besoin d'une méthode pour afficher et stocker son contenu de manière
logique. La méthode habituelle est d'utiliser les catégories et
sous-catégories. Joomla! propose de multiples possibilités pour afficher
et utiliser le contenu contrôlé par la catégorisation. Certains types de
contenu qui utilisent la catégorisation sont les
[articles](https://docs.joomla.org/Article "Special:MyLanguage/Article")
(contenu principal des pages web), les bannières, les contacts et les
liens web.

La catégorie par défaut, à laquelle sont assignés tous les types de
contenus, est la catégorie "Non-catégorisé". La catégorie
"non-catégorisé" n'est pas descriptive et devrait être utilisée pour les
types de contenus qui ne sont pas classés dans une catégorie spécifique.

Lorsque vous créez et assignez des catégories, vous devez définir une
structure. Par exemple, voici une possibilité pour catégoriser plusieurs
[articles](https://docs.joomla.org/Article "Special:MyLanguage/Article")
Joomla! parlant d'oiseaux. Créez deux catégories principales d'articles
nommés "Animaux" et "Plantes". Sous la catégorie "Animaux", vous
pourriez avoir des sous-catégories nommées "Oiseaux" et "Mammifères".
Sous la sous-catégorie "Oiseaux", vous pourriez avoir 3 articles nommés
"Aigles", "Perroquets" et "Hirondelles".

- Animaux
  - Oiseaux
    - Aigles
    - Perroquets
    - Hirondelles
  - Mammifères

L'exemple ci-dessus pourrait être étendu encore d'avantage avec des
articles spécifiques sur les différentes espèces d'Aigles, de Perroquets
et d'Hirondelles. Commencez en utilisant une catégorie parente
"Animaux". Placez les sous-catégories enfants "Oiseaux" et "Mammifères"
dans la catégorie parente "Animaux", et enfin placez les sous-catégories
enfants "Aigles", "Perroquets" et "Hirondelles" dans sa catégorie
parente "Oiseaux".

Vous pouvez désormais créer plusieurs articles dans les sous-catégories
Aigles, Perroquets et Hirondelles en utilisant les différents genres ou
les noms communs de ces trois races d'oiseaux.

Il est possible de gérer les catégories et les sous-catégories grâce au
gestionnaire de catégories, qui est accessible via l'interface
d'administration (Backend) en cliquant sur l'élément de menu "Contenu"
puis "Gestion des catégories".

**Voir également** :
[Article](https://docs.joomla.org/Article "Special:MyLanguage/Article")

## Chrome

Les caractéristiques de l'interface graphique d'une application sont
parfois appelées "chrome". Vous pouvez consulter [Mise en œuvre d'un
module personnalisé
Chrome](https://docs.joomla.org/Applying_custom_module_chrome "Special:MyLanguage/Applying custom module chrome")
pour plus d'informations sur la façon de modifier l'apparence des
modules.

## [Composant](https://docs.joomla.org/Component "Special:MyLanguage/Component")

## [Extension](https://docs.joomla.org/Extension "Special:MyLanguage/Extension")

## Feuilles de Style en Cascade (CSS)

Une Feuille de Style en Cascade ou CSS est utilisée pour contrôler la
présentation d'une page XHTML. Par exemple, un fichier CSS contrôlera
souvent la police, les marges, la couleur, les images de fond et
d'autres aspects de l'apparence d'une page web. Les CSS vous permettent
de séparer le contenu d'une page XHTML de son apparence. Dans Joomla!,
les fichiers CSS (par exemple, template.css) font normalement partie du
template.

**Voir également :**
[Template](https://docs.joomla.org/Template "Special:MyLanguage/Template"),
[Suffixe de Classe de
Page](https://docs.joomla.org/Page_Class_Suffix "Special:MyLanguage/Page Class Suffix"),
[Suffixe de Classe de
Module](https://docs.joomla.org/Module_Class_Suffix "Special:MyLanguage/Module Class Suffix")

## [LDAP](https://docs.joomla.org/LDAP "Special:MyLanguage/LDAP")

## Le Core (noyau)

Le mot "Core" (ou "noyau") dans Joomla! se rapporte à la distribution
des fichiers nécessaires à la création et la gestion d'un site web
propulsé par le CMS Joomla!. Ces fichiers peuvent être téléchargés sur
le site Joomla! :
<a href="http://www.joomla.org/download.html" class="external text"
target="_blank"
rel="noreferrer noopener">http://www.joomla.org/download.html</a>. Le
"Core" de Joomla! contient également quelques fonctionnalités de base
permettant à de nouvelles installations de Joomla! de fonctionner
rapidement et facilement. Sont inclus : les gestionnaires
d'utilisateurs, d'articles, de liens, de catégories, de contacts ainsi
que le gestionnaire de menu. Sont également présents : un gestionnaire
de
[template](https://docs.joomla.org/template "Special:MyLanguage/template")
contenant quelques templates de base permettant l'affichage du Frontend
(affichage du site web pour l'internaute), un gestionnaire des
[modules](https://docs.joomla.org/module "Special:MyLanguage/module") de
base, un gestionnaire des
[plugins](https://docs.joomla.org/plugin "Special:MyLanguage/plugin") de
base, et quelques autres
[extensions](https://docs.joomla.org/extension "Special:MyLanguage/extension")
permettant d'élargir les fonctionnalités d'une installation de base de
Joomla!. Ces extensions du Core ne doivent pas être confondues avec les
extensions tierces disponibles en téléchargement sur le JED (Joomla!
Extension Directory - Répertoire des extensions Joomla!).

**Voir également :**
<a href="http://extensions.joomla.org/" class="external text"
target="_blank" rel="noreferrer noopener">Répertoire des Extensions
Joomla! (JED)</a>.

## [Les Langues](https://docs.joomla.org/Language "Special:MyLanguage/Language")

Les langues sont peut-être les plus élémentaires et les plus importants
types
d'[extensions](https://docs.joomla.org/Extensions "Special:MyLanguage/Extensions").
Les langues sont intégrées soit comme un pack de langue de base soit en
un pack de langue pour extension. Ces packs sont constitués de fichiers
INI qui contiennent des paires clé/valeur. Ces paires clé/valeur
fournissent la traduction de chaînes de texte statiques du code source
de Joomla!. Cela permet aussi bien au Core de Joomla! qu'au composants
et modules tierces d'être traduits. Les packs de langue de base
comprennent également un méta fichier XML décrivant la langue ainsi que
des informations sur les polices à utiliser pour la génération de
contenu PDF.

## Liste de Contrôle d'Accès (ACL)

## Menus Split (Menus partagés)

Un [menu
split](https://docs.joomla.org/split_menus "Special:MyLanguage/split menus")
(menu partagé) ce sont les différents niveaux d'un même menu s'affichant
en deux endroits différents ou plus sur une même page.

Par exemple, une demande fréquente est que le menu de niveau principal
soit affiché en haut de la page. Lorsque l'un de ces éléments est
cliqué, l'utilisateur sera redirigé vers une page où un menu secondaire,
par exemple sur la partie gauche de la page, affichera les éléments du
second niveau en relation avec l'élément de menu de niveau supérieur.

Les menus apparaissent dans des zones séparées sur la page, mais sont
liées parce que l'une ne montre que des éléments du niveau principal
tandis que l'autre affiche des éléments de niveau secondaire. Cette
pratique peut être étendue pour inclure des menus de troisième niveau et
au-delà.

Avec Joomla!, ceci peut être mis en œuvre par l'utilisation d'un unique
menu à niveaux multiples et en créant des modules de menus, chacun étant
affecté à un niveau différent.

**Voir également** :
[Menu](https://docs.joomla.org/Menu "Special:MyLanguage/Menu")

## [Menu](https://docs.joomla.org/Menu "Special:MyLanguage/Menu")

Dans Joomla!, un **Menu** est un ensemble d'**éléments de menu** utilisé
pour naviguer sur un site web. Chaque élément de menu définit une URL
vers une page de votre site, ainsi que les paramètres qui contrôlent le
contenu (articles, listes de catégorie(s), éléments tagués, etc.) et le
style (module(s), mise en page) de cette page.

[Ajouter un nouveau
menu](https://docs.joomla.org/Adding_a_new_menu "Special:MyLanguage/Adding a new menu")
est plutôt simple. Dans le menu d'administration du back-end de votre
site Joomla!, choisissez :

Menus

 ajouter de nouveaux éléments de menu au menu.

Tout site web peut avoir plus d'un menu.

Un **Menu** ne s'affiche pas automatiquement sur le front-end du site.
Il vous faut créer un **module de menu** en utilisant le **[Gestionnaire
de
modules](https://docs.joomla.org/Help33:Extensions_Module_Manager "Special:MyLanguage/Help33:Extensions Module Manager")**
et indiquer au module quel **Menu** afficher. Par la suite, vous pouvez
sélectionner là où le module devra s'afficher sur le site, et ce en
choisissant une des **[positions de
module](https://docs.joomla.org/Module_Position "Special:MyLanguage/Module Position")**
du
**[template](https://docs.joomla.org/Getting_Started_with_Templates "Special:MyLanguage/Getting Started with Templates")**
actif.

Il existe encore plus de possibilités pour l'affichage du menu, en
ajustant les paramètres du module de menu. Ainsi, vous pouvez le
paramétrer afin qu'il s'affiche sur tout ou partie des pages (en
assignant le module sur les éléments de menu) ou qu'il soit visible à
tous ou uniquement à certains groupes d'utilisateurs (par exemple, les
utilisateurs enregistrés).

Il est également possible de créer des [Menus
partagés](https://docs.joomla.org/Split_menus "Special:MyLanguage/Split menus").

## [Module](https://docs.joomla.org/Module "Special:MyLanguage/Module")

## [Module chrome](https://docs.joomla.org/Module_chrome "Special:MyLanguage/Module chrome")

## Modèle-Vue-Contrôleur

Joomla! reprend largement dans sa conception l'architecture
<a href="http://fr.wikipedia.org/wiki/Mod%C3%A8le-vue-contr%C3%B4leur"
class="external text" target="_blank"
rel="nofollow noreferrer noopener">Modèle-Vue-Contrôleur</a>.

Lorsque Joomla! traite la requête d'un utilisateur, comme un "GET" pour
une page en particulier, ou un "POST" contenant des données de
formulaire, une des premières actions de Joomla! est d'analyser l'URL
pour déterminer quel composant devra traiter la demande et prendre le
contrôle de ce composant.

Si le composant a été conçu selon l'architecture MVC, la requête va
passer au contrôleur. Le contrôleur va alors analyser la demande et
déterminer quels Modèles seront nécessaires pour la traiter, et quelle
Vue devrait être utilisée pour retourner les résultats à l'utilisateur.

Le Modèle encapsule les données utilisées par le composant. Dans la
plupart des cas, ces données proviendront d'une base de données, soit la
base de données Joomla!, soit une base de données externe, mais il est
également possible au Modèle de récupérer des données provenant d'autres
sources, comme via une API de services Web s'exécutant sur un autre
serveur. Le Modèle est également, le cas échéant, chargé de la mise à
jour de la base de données. Le rôle du Modèle est d'isoler le Contrôleur
et la Vue des tâches de récupération ou de modification des données.

La Vue est en charge de la génération du rendu qui sera envoyé au
navigateur par le composant. Elle appelle le Modèle pour toute
information nécessaire et le met en forme de façon appropriée. Par
exemple, une liste de données extraites d'un Modèle pourra être intégrée
dans un tableau HTML généré par la Vue.

Joomla! étant conçu pour être hautement modulaire, le rendu d'un
composant ne représente généralement qu'une partie de la page web
complète que l'utilisateur verra au final. Une fois que la Vue a généré
le rendu, le composant rend le contrôle au Framework Joomla! qui va
charger et exécuter le template. Le template combine le rendu du
composant et de tous les modules actifs sur la page en cours, de sorte
que le navigateur puisse tout afficher sur une même page.

Afin de fournir plus de puissance et de flexibilité aux concepteurs de
sites web, généralement plus concernés par la création de nouveaux
designs que par la manipulation du code sous-jacent, Joomla! a divisé la
Vue traditionnelle en une Vue et une Mise en page (Layout). La Vue
récupère les données du Modèle, comme dans une architecture MVC
traditionnelle, mais rend simplement ces données disponibles pour la
mise en page, qui gère la mise en forme des données pour la présentation
à l'utilisateur. L'avantage de cette séparation est que le système de
template de Joomla! fournit, dans le template, un mécanisme simple pour
la substitution de mises en page. Ces substitutions de mise en page
(généralement nommées "template override" car faisant partie du
template, bien que seule la mise en page ne soit substituée) sont liées
au template et donnent au concepteur de template le contrôle total sur
tout le rendu provenant du Core Joomla! et de toutes les extensions
tierces installées et conformes à l'architecture MVC.

## Optimisation des URL pour les Moteurs de Recherche (Search Engine Friendly)

Les URL optimisées pour les moteurs de recherche sont communément
abrégées, y compris en français, en URL SEF ou simplement SEF (Search
Engine Friendly). Dans Joomla!, les URL ressemblent à ceci :

    http://www.votresite.org/index.php?option=com_content&view=section&id=3&Itemid=41

En option, il est possible de modifier l'affichage des URL pour les
faire ressembler à des URL de pages statiques en HTML comme ceci :

    http://www.votresite.org/faq.html

Depuis Joomla! 1.5, il existe des options intégrées pour générer des URL
SEF. Ces options peuvent être activées en modifiant les "Paramètres SEO"
(Optimisation pour les Moteurs de Recherche) dans l'onglet Site du
panneau de configuration globale dans l'interface d'administration de
Joomla!. Il existe également des extensions tierces permettant de
générer des URL SEF pour Joomla!.

## Paquet de Mise A Jour

Un Pack de Mise A Jour pour Joomla! est une archive qui contient les
fichiers qui ont été modifiés entre deux versions Joomla!. Lorsque cette
archive est décompressée, elle remplace les fichiers de l'ancienne
version par les fichiers modifiés pour la nouvelle version. Par exemple,
si 50 fichiers ont été modifiés entre la version 1.x.1 et 3.x.2, le pack
de mise à jour de 3.x.1 à 3.x.2 contiendra ces 50 fichiers et, une fois
décompressés, ils remplaceront les 50 fichiers obsolètes de la version
3.x.1.

Les paquets de mise à jour font parfois également référence à des
[Fichiers
Patch](https://docs.joomla.org/Patch "Special:MyLanguage/Patch"). Avant
d'installer un paquet de mise à jour, vous pouvez consulter les [notes
de
version](https://docs.joomla.org/Joomla_1.5_version_history "Special:MyLanguage/Joomla 1.5 version history")
ainsi que les [instructions de mise à
jour](https://docs.joomla.org/Upgrade_Instructions "Special:MyLanguage/Upgrade Instructions")
en lien avec le Paquet de mise à jour.

## [PHP](https://docs.joomla.org/PHP "Special:MyLanguage/PHP")

PHP est un langage de programmation libre utilisé principalement pour la
création de pages Web dynamiques. Le PHP est largement utilisé pour le
développement web et peut intégrer du code
[HTML](https://docs.joomla.org/Where_can_you_learn_about_HTML%3F "Special:MyLanguage/Where can you learn about HTML?").
Il est généralement traité par un serveur web qui reçoit le code PHP,
l'exécute et retourne la page Web. Joomla! est essentiellement écrit en
utilisant le langage PHP. Pour plus d'information vous pouvez consulter
l'article : [Où puis-je en apprendre plus sur le
PHP ?](https://docs.joomla.org/Where_can_you_learn_about_PHP "Special:MyLanguage/Where can you learn about PHP")

## [Position de Module](https://docs.joomla.org/Module_Position "Special:MyLanguage/Module Position")

## Préfixe de Table de Base De Données

Le préfixe de table de base de données est une chaîne de caractères
(contenant peu de caractères) ajoutée devant les noms des
[tables](https://docs.joomla.org/tables "Special:MyLanguage/tables") de
Joomla!. L'utilisation d'un préfixe vous permet d'exécuter plusieurs
installations de Joomla! à l'aide d'une base de données unique.

Le préfixe de table de la base de données peut être défini lors de
l'installation de Joomla!. Il est également possible de le modifier
ultérieurement mais nécessite un accès à la base de données par un
système externe à Joomla! ou par une extension comme Akeeba Admin Tools.

Les développeurs
d'[extension](https://docs.joomla.org/Extension "Special:MyLanguage/Extension")
doivent utiliser la chaîne de caractères `#__` comme préfixe. Cette
chaîne sera remplacée par le vrai préfixe de table lors de l'exécution
de la commande par Joomla!.

## [Suffixe de Classe de Module](https://docs.joomla.org/Module_Class_Suffix "Special:MyLanguage/Module Class Suffix")

Un Suffixe de Classe de Module dans Joomla! est un paramètre de module.
Il est configurable dans le Module : écran \[Modifier\] dans la section
"Paramètres Avancées". Il permet à Joomla! soit d'ajouter une nouvelle
classe CSS soit de modifier la classe CSS `div` existante d'un module
spécifique.

Lorsque Joomla! génère un module, une classe CSS nommée "moduletable"
est automatiquement créée, permettant de personnaliser l'affichage du
module -- par exemple :

Afin de créer une nouvelle classe, entrez le paramètre précédé d'un
espace. Par exemple, en saisissant espace + "maNouvelleClasse", une
nouvelle classe CSS nommée "maNouvelleClasse" est créée. Le HTML sera
alors modifié en

Pour changer le nom d'une classe existante, entrez le paramètre sans
espace. Par exemple, en saisissant "\_monSuffixe" (sans espace), le HTML
sera modifié en :

Généralement, il est recommandé d'utiliser un espace pour créer une
nouvelle classe. Ainsi, les styles CSS de ce module, qui utilise les
noms de classe standards, continueront de fonctionner. Vous pouvez
utiliser un nouveau nom de classe pour ajouter des styles au module sans
avoir besoin de recréer tout le code CSS existant. Attention, si vous
créez un nouveau nom de classe, assurez-vous que son nom soit unique et
n'entre pas en conflit avec un nom de classe existant.

Voir également : [Utilisation des Suffixes de
Classe](https://docs.joomla.org/Using_Class_Suffixes "Special:MyLanguage/Using Class Suffixes").

## [Suffixe de Classe de Page](https://docs.joomla.org/Page_Class_Suffix "Special:MyLanguage/Page Class Suffix")

Un suffixe de classe de page dans Joomla! est un paramètre présent dans
le contenu des éléments de Menu. Il est paramétrable dans l'élément de
Menu : écran \[Modifier\] dans la section "Paramètres Avancées". Il
permet à Joomla! soit d'ajouter une nouvelle classe CSS soit de modifier
la classe CSS existante afin d'obtenir un affichage spécifique à cet
élément de menu.

Lorsque Joomla! génère une page, les classes CSS pré-définies sont
automatiquement appliquées afin de permettre le rendu de la page. Par
exemple, une page peut contenir l'élément

Afin de créer une nouvelle classe, entrez le paramètre précédé d'un
espace. Par exemple, en saisissant espace + "maNouvelleClasse", une
nouvelle classe CSS nommée "maNouvelleClasse" est créée et s'intègre
alors comme classe aux éléments de cet Elément de Menu. Dans ce cas,
l'exemple ci-dessus deviendra :

Pour changer le nom d'une classe existante, entrez le paramètre sans
espace. Par exemple, en saisissant "\_monSuffixe" (sans espace), le HTML
sera modifié en :

Généralement, il est recommandé d'utiliser un espace pour créer une
nouvelle classe. Ainsi, les styles CSS de ce composant, qui utilise les
noms de classe standards, continueront de fonctionner. Vous pouvez
utiliser un nouveau nom de classe pour ajouter des styles au composant
sans avoir besoin de recréer tout le code CSS existant. Attention, si
vous créez un nouveau nom de classe, assurez-vous que son nom soit
unique et n'entre pas en conflit avec un nom de classe existant.

**Voir également** : [Utilisation des Suffixes de
Classe](https://docs.joomla.org/Using_Class_Suffixes "Special:MyLanguage/Using Class Suffixes"),
[Utilisation du Suffixe de Classe de Page dans le Code du
Template](https://docs.joomla.org/Using_the_Page_Class_Suffix_in_Template_Code "Special:MyLanguage/Using the Page Class Suffix in Template Code")

## [Template](https://docs.joomla.org/Template "Special:MyLanguage/Template")

Un Template est un type
d'[extension](https://docs.joomla.org/extension "Special:MyLanguage/extension")
pour Joomla! qui permet de modifier l'apparence de votre site Web. Il
existe deux types de template pour le CMS Joomla! : [les templates de
site
Front-end](https://docs.joomla.org/Template/fr#Les_Templates_de_Site_.28Front-end.29 "Special:MyLanguage/Template/fr")
et [les templates d'administration
Back-end](https://docs.joomla.org/Template/fr#Les_Templates_d.27Administration_.28Back-end.29 "Special:MyLanguage/Template/fr").
Les templates de site déterminent l'apparence du contenu de votre site
pour le visiteur. Les templates d'administration déterminent l'apparence
donnée aux fonctionnalités d'administration de votre site et disponibles
aux administrateurs du site. Cela concerne les fonctionnalités Joomla!
telles que : utilisateurs, menu, article, catégorie, module, composant,
plugin et gestion des templates.

**Voir également** :
[Composant](https://docs.joomla.org/Component "Special:MyLanguage/Component"),
[Module](https://docs.joomla.org/Module "Special:MyLanguage/Module"),
[Plugin](https://docs.joomla.org/Plugin "Special:MyLanguage/Plugin")
