<!-- Filename: Help4.x:Site_System_Information / Display title: Site Systeem informatie -->

## Beschrijving

Deze pagina biedt handige informatie over uw host server omgeving,
inclusief het operating systeem, database en PHP instellingen en mappen
informatie. Er zijn vijf verschillende tabblad schermen:
Systeeminformatie, PHP instellingen, Configuratiebestand, Maprechten en
PHP informatie. Elk scherm biedt gedetailleerde informatie over dat
aspect van uw Joomla! website. Deze informatie is erg behulpzaam als u
problemen onderzoekt met uw instellingen.

- Let op dat geen van deze instellingen veranderd kunnen worden vanaf
  deze schermen. Dit moet worden gedaan op verschillende plekken van uw
  Joomla! installatie, afhankelijk van de bepaalde instelling.
- Veel instellingen van het instellingen bestand scherm kunnen worden
  aangepast vanuit het [Algemene
  instellingen](https://docs.joomla.org/Help4.x:Site_Global_Configuration/nl "Help4.x:Site Global Configuration/nl")
  scherm. Enkele instellingen die hier getoond worden hangen af van uw
  host server configuratie en kunnen niet vanuit Joomla! veranderd
  worden.

## Hoe toegang te krijgen

- Selecteer **Systeem **→** Gegevens venster **→** Systeeminformatie**
  vanuit het Beheer menu.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/9/9f/Help-4x-system-system-information-nl.png/800px-Help-4x-system-system-information-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/9/9f/Help-4x-system-system-information-nl.png/1200px-Help-4x-system-system-information-nl.png 1.5x, https://docs.joomla.org/images/9/9f/Help-4x-system-system-information-nl.png 2x"
data-file-width="1266" data-file-height="934" width="800" height="590"
alt="Help-4x-system-system-information-nl.png" />

## Gegevens

- Systeem Informatie
- PHP instellingen
- Configuratiebestand
- Maprechten
- PHP informatie.

### Systeeminformatie tabblad

Dit scherm toont informatie over de omgeving van het operating systeem
van uw Joomla! site.

- **PHP gebouwd op:** Geeft details over het operating systeem van de
  webserver waar Joomla! op draait.
- **Databasetype:** Toont het type database dat gebruikt wordt bij de
  installatie van Joomla.
- **Database versie:** Toont de huidige versie van de MySQL database die
  gebruikt wordt bij de installatie van Joomla.
- **Database collatie:** Hoe de MySQL database gestructureerd is voor de
  informatie die door Joomla! gebruikt wordt.
- **Collatie van de databaseverbinding:** De tekenset en collatie van de
  database.
- **PHP versie:** Geeft de huidige versie van het PHP server-side script
  dat gebruikt wordt voor deze installatie van Joomla!.
- **Webserver:** Geeft het huidige type en de versie van de webserver
  van de installatie waarop Joomla! draait.
- **Webserver naar PHP interface:** Het script dat interactie geeft
  tussen de webserver (in de meeste gevallen, Apache) en de PHP
  scripting taal.
- **Joomla! versie:** Geeft de huidige versie van Joomla!. Het is
  aanbevolen deze altijd up-to-date te hebben en de huidige stabiele
  versie te gebruiken.
- **Gebruikersagent:**De samenvatting van het huidige lokale machine
  operating systeem van de gebruiker en de browser informatie die
  gebruikt wordt om een unieke sessie-ID aan te maken voor toegang en
  functies binnen de Joomla! website.

### PHP instellingen tabblad

<img
src="https://docs.joomla.org/images/thumb/6/6b/Help-4x-system-php-settings-nl.png/400px-Help-4x-system-php-settings-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/6/6b/Help-4x-system-php-settings-nl.png 1.5x"
data-file-width="508" data-file-height="620" width="400" height="488"
alt="Help-4x-system-php-settings-nl.png" />

Dit scherm toont de relevante PHP instelling informatie. Indien er iets
uitgelicht is als incorrect dan moet actie worden ondernomen de situatie
te herstellen.

- **Veilige modus:** Aanbevolen instelling: Uit
- **Open basedir:** Aanbevolen instelling: Hangt van site af
- **Toon fouten:** Aanbevolen instelling: Uit
- **Short Open Tags:** Aanbevolen instelling: Aan
- **Bestandsuploads:** Aanbevolen instelling: Aan
- **Magic Quotes:** Aanbevolen instelling: Uit
- **Register Globals:** Aanbevolen instelling: Uit
- **Uitvoer buffering:** Aanbevolen instelling: Uit
- **Sessie save path:** Aanbevolen instelling: Afhankelijk van de site
- **Sessie auto start:** Aanbevolen instelling: Uit
- **XML ingeschakeld:** Aanbevolen instelling: Ja
- **Zlib ingeschakeld:** Aanbevolen instelling: Ja
- **Native ZIP ingeschakeld:** Aanbevolen instelling: Ja
- **Uitgeschakelde functies:** Aanbevolen instelling: Afhankelijk van
  site
- **Multibyte String (mbstring) ingeschakeld:** Aanbevolen instelling:
  Ja
- **Iconv Beschikbaar:** Aanbevolen instelling: Ja
- **Maximale invoervariabelen:** Aanbevolen instelling: 2500

### Configuratiebestand tabblad

<img
src="https://docs.joomla.org/images/thumb/7/7f/Help-4x-system-configuration-file-nl.png/600px-Help-4x-system-configuration-file-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/7f/Help-4x-system-configuration-file-nl.png/900px-Help-4x-system-configuration-file-nl.png 1.5x, https://docs.joomla.org/images/7/7f/Help-4x-system-configuration-file-nl.png 2x"
data-file-width="961" data-file-height="757" width="600" height="473"
alt="Help-4x-system-configuration-file-nl.png" />

Dit scherm toont de inhoud van het huidige Joomla! *configuration.php*
bestand dat opgeslagen is in de hoofd **/joomla_root/** map. Dit bestand
is automatisch voor u aangemaakt als u Joomla! voor het eerst
installeert en waar de meeste wijzigingen van de globale instellingen
sectie van Joomla! zijn opgenomen. Denk er aan dat geen van deze
instellingen op deze pagina aangepast kan worden. Gebruik [Algemene
instellingen](https://docs.joomla.org/Help4.x:Site_Global_Configuration/nl "Help4.x:Site Global Configuration/nl")
om meer informatie over deze instellingen te zien en om aanpassingen te
doen.

### Maprechten tabblad

<img
src="https://docs.joomla.org/images/thumb/f/f2/Help-4x-system-folder-permissions-nl.png/600px-Help-4x-system-folder-permissions-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/f/f2/Help-4x-system-folder-permissions-nl.png 1.5x"
data-file-width="798" data-file-height="782" width="600" height="588"
alt="Help-4x-system-folder-permissions-nl.png" />

Dit scherm toont een lijst met mappen waar de webserver schrijfrechten
voor moet hebben. Denk eraan dat alle mappen op deze pagina
**Schrijfbaar** moeten zijn. Indien niet, dan moet u misschien de
rechten aanpassen, om Joomla! succesvol te installeren en gebruiken.

### PHP informatie tabblad

<img
src="https://docs.joomla.org/images/thumb/4/4b/Help-4x-system-php-information-nl.png/600px-Help-4x-system-php-information-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/4b/Help-4x-system-php-information-nl.png/900px-Help-4x-system-php-information-nl.png 1.5x, https://docs.joomla.org/images/4/4b/Help-4x-system-php-information-nl.png 2x"
data-file-width="983" data-file-height="760" width="600" height="464"
alt="Help-4x-system-php-information-nl.png" />

Dit scherm toont de volledige instelling van de PHP server side
script-taal waarop Joomla! draait, samen met alle gekoppelde systeem
informatie die wordt gebruikt bij het aanmaken van de webserver. Het is
de uitvoer van een geïntegreerd php.info script dat in Joomla! zit.

PHP is geïnstalleerd en draait op de server (vandaar bovenstaande server
side) en daarom zijn alle instellingen op de server ingesteld. De
bezoeker aan de website hoeft niets speciaals te draaien op hun lokale
machine om te kijken, of extra functionaliteit te hebben die PHP op de
website biedt.

Alle instellingen die mogelijk nodig zijn worden hier getoond.
Wijzigingen die noodzakelijk zijn moeten gedaan worden in de *php.ini*
en andere instellingsbestanden op de webserver.

Hoeveel controle de eigenaar van een website heeft over de informatie
hangt af van of ze eigenaar zijn van de server of dat de server-host
flexibel is in een gebruikersbenadering.

Het is goed de beperkingen van een bepaalde server-installatie te weten.
Deze schermuitvoer wordt gebruikt om gedetailleerde informatie over hoe
PHP is geïmplementeerd op de server.

Bezoek, voor volledige details over de informatie op het PHP Info
scherm:
<a href="http://php.net/phpinfo" class="external text" target="_blank"
rel="nofollow noreferrer noopener">http://php.net/phpinfo</a>.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#Schermafbeelding) hierboven. De functies zijn.

- **Downloaden als tekst:** Download de systeemgegevens als
  tekstbestand.
- **Downloaden als JSON:** Download de systeemgegevens als JSON bestand.
- **Help**. Opent dit helpscherm.

## Snelle tips

- Als u problemen heeft met het installeren van extensies, het uploaden
  van bestanden of het wijzigen van de instellingen opties, controleer
  dan het map rechten scherm om zeker te weten dat u de rechten heeft om
  bestanden te schrijven op uw webserver. De "Status" van de mappen
  zouden "Schrijfbaar" moeten zijn. Zo niet, dan kunt u geen bestanden
  uploaden of bewerken in deze mappen.
- Als u hulp zoekt bij instellingen problemen, bijvoorbeeld in een
  Joomla! webforum, is het handig specifieke informatie over uw Joomla!
  installatie te plaatsen. Dit scherm is een makkelijke manier om al
  deze informatie op één plek te vinden.
