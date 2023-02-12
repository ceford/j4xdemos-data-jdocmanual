<!-- Filename: Help4.x:Site_Global_Configuration / Display title: Algemene instellingen -->

## Beschrijving

De Algemene instellingen scherm geeft u de mogelijkheid de Joomla site
in te stellen met uw persoonlijke instellingen. Instellingen op dit
scherm gelden voor de hele site.

## Hoe toegang te krijgen

- **Systeem **→** Instellingen **→** Algemene instellingen**

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/f/ff/Help-4x-global-configuration-screen-nl.png/750px-Help-4x-global-configuration-screen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/ff/Help-4x-global-configuration-screen-nl.png/1125px-Help-4x-global-configuration-screen-nl.png 1.5x, https://docs.joomla.org/images/thumb/f/ff/Help-4x-global-configuration-screen-nl.png/1500px-Help-4x-global-configuration-screen-nl.png 2x"
data-file-width="2720" data-file-height="1700" width="750" height="469"
alt="Help-4x-global-configuration-screen-nl.png" />

## Formulier velden

### Website

[Volledige
afbeelding.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Site/nl "Help4.x:Site Global Configuration Site/nl")

#### Website

- **Website naam**. Vul de naam van uw website in. Deze wordt gebruikt
  op diverse locaties (bijvoorbeeld op de administratie titelbalk in uw
  browser en Website offline pagina's).
- **Website offline**. Selecteer of de website bereikbaar is voor
  bezoekers. [Meer
  leren.](https://docs.joomla.org/J3.x:Taking_the_website_temporarily_offline/nl "J3.x:Taking the website temporarily offline/nl")
  - **Offline bericht**.
    - Gebruik aangepast bericht: Het aangepaste offline bericht gebruikt
      de waarde die gedefinieerd is in het 'Aangepast bericht' veld.
    - Gebruik standaard bericht van websitetaal: Het standaard offline
      bericht gebruikt de waarde die gedefinieerd is in het site ini
      taalbestand van de standaard ingestelde taal.
  - **Offline afbeelding**. Selecteer een afbeelding om weer te geven op
    de standaard offline pagina. Zorg dat de afbeelding minder dan 400px
    breed is.
- **Bewerken vanaf website**. Selecteer of er inline bewerkiconen
  gebruikt worden voor modules en menu-items.
- **Standaard tekstverwerker**. Selecteer de standaard WYSIWYG
  tekstverwerker. Geregistreerde gebruikers kunnen hun voorkeuren
  wijzigen in de persoonlijke gegevens wanneer u deze optie toestaat.
- **Standaard Captcha**. Selecteer de standaard captcha voor uw website.
  U kunt de vereiste informatie voor uw captcha plugin invullen in
  [Pluginbeheer](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_CAPTCHA_Group/nl "Chunk4x:Extensions Plugin Manager Edit CAPTCHA Group/nl").
- **Standaard toegangsniveau**. Selecteer het standaard toegangsniveau
  voor nieuwe items.
- **Standaard lijstlengte**. Stelt de standaard lijstlengte in op het
  Backend voor alle gebruikers.
- **Standaard feedlimiet**. Selecteer het aantal artikelen dat in de
  feed(s) moet worden weergegeven.
- **E-mailadres feed**. De RSS en Atom nieuwsfeeds bevatten het
  e-mailadres van de auteur.
  - Auteur e-mail: Selecteer e-mailadres auteur om het e-mailadres van
    elke auteur te gebruiken (uit
    [gebruikersbeheer](https://docs.joomla.org/Help4.x:Users/nl "Help4.x:Users/nl"))
    in de nieuwsfeed.
  - E-mailadres website: Selecteer e-mailadres website om het
    [e-mailadres](#fromemail) van de website toe te voegen aan ieder
    artikel.

#### Metadata

- **Algemene metabeschrijving van website**. Vul een algemene
  beschrijving van de website in die gebruikt kan worden door
  zoekmachines.
- **Robots**. Robots instructies.
  - index, follow: Indexeer deze pagina en volg de links op deze pagina.
  - noindex, follow: Indexeer deze pagina niet, maar volg de links op de
    pagina toch. U wilt dit bijvoorbeeld misschien doen op een pagina
    met sitemap waarvan u wilt dat de links geïndexeerd worden, maar dat
    de pagina zelf niet verschijnt in zoekmachines.
  - index, nofollow: Indexeer deze pagina, maar volg geen link op de
    pagina. U wilt dit bijvoorbeeld misschien voor een evenementen
    kalender, waarvan u wilt dat de pagina verschijnt in zoekmachines,
    maar waarvan elk evenementen niet geïndexeerd hoeft te worden.
  - noindex, nofollow: Indexeer deze pagina niet en volg geen link op
    deze pagina.
- **Inhoudsrechten**. Beschrijf welke rechten anderen hebben om deze
  inhoud te gebruiken. Dit wordt naar zoekmachines verzonden met behulp
  van de 'rights' meta tag in de HTML kop.
- **Auteur metatag**. Toon de auteur metatags wanneer artikelen bekeken
  worden.
- **Joomla! versie**. Bepaalt of de 'generator' meta tag in de koptekst
  van het HTML document in de Frontend en in Atom feeds de exacte versie
  van de Joomla website bevat. Om veiligheidsredenen wordt aangeraden om
  het te verbergen.

#### SEO

- **Zoekmachinevriendelijke URL's**. Selecteer of URL's geoptimaliseerd
  moeten worden voor zoekmachines.
- **Gebruik URL herschrijven**
  - Apache en Litespeed: Hernoem 'htaccess.txt' naar '.htaccess'
    <a href="https://httpd.apache.org/docs/2.4/howto/htaccess.html"
    class="external text" target="_blank"
    rel="nofollow noreferrer noopener">Meer leren.</a>
  - IIS: Hernoem 'web.config.txt' naar 'web.config'
  - NginX: de [configure your
    server](https://docs.joomla.org/Nginx/nl "Nginx/nl")
  - Andere servers of indien onbekend: Raadpleeg het hostingbedrijf.
- **Voeg een achtervoegsel (suffix) aan URL's toe**. Wanneer ja is
  ingesteld, wordt een achtervoegsel (suffix) aan de URL toegevoegd
  gebaseerd op het documenttype.
- **Unicode aliassen**. Kies tussen transliteratie en unicode aliassen.
  Transliteratie is standaard.
- **Websitenaam in paginatitels**. Laat alle paginatitels beginnen of
  eindigen met de websitenaam (bijvoorbeeld: "Naam van mijn website -
  Naam van het artikel").

#### Cookie

- **Cookie-domein**. Domeinnaam die gebruikt wordt voor de instellingen
  van sessie cookies. Laat de domeinnaam voorafgaan door '.' als de
  cookie ook voor subdomeinen geldig is.
- **Cookie-pad**. Pad waarvoor de cookie geldig is.

### Systeem

[Volledige
afbeelding.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_System/nl "Help4.x:Site Global Configuration System/nl")

#### Foutopsporing

- **Foutopsporing systeem**. Wanneer dit geactiveerd is worden
  diagnostische informatie, vertalingsfouten en SQL fouten weergegeven
  (indien aanwezig). De informatie wordt onderaan iedere pagina die u
  bekijkt in Joomla! weergegeven. Het wordt niet geadviseerd de
  foutenopsporing modus blijvend in te schakelen wanneer uw website
  online is.
- **Debug Language**. Selecteer of de foutopsporings indicatoren
  \*\*...\*\* of ??...?? voor de Joomla taalbestanden worden
  weergegeven. Taal foutopsporing werkt zonder dat systeem foutopsporing
  geactiveerd is, maar u krijgt niet de toegevoegde gedetailleerde
  verwijzingen die behulpzaam kunnen zijn bij het corrigeren van fouten.
  - **Taalweergave**. Selecteer of de taalconstante of de taalwaarde
    moet worden weergegeven bij het debuggen van de taalstrings.

#### Cache

- **Systeemcache**. In of uitschakelen cachen en instellen van
  cacheniveau. [Meer
  leren.](https://docs.joomla.org/Cache/nl "Cache/nl")
  - Conservatief cachen: kleinere systeemcache.
  - Progressief cachen: sneller, grotere systeemcache, inclusief het
    renderen van modulecache. Niet aan te bevelen voor extreem grote
    websites.
  - **Cache-afhandeling**.
    - Bestand: Het oorspronkelijke cache-mechanisme is bestand
      gebaseerd. Zorg ervoor dat de cache-mappen schrijfbaar zijn.
  - **Platform specifieke caching**. Inschakelen als HTML-uitvoer op
    mobiele apparaten van andere apparaten verschilt.
  - **Cachetijd (minuten)**. De maximum tijdsduur in minuten, om een
    cachebestand op te slaan voordat het vernieuwd wordt.
  - **Pad naar de cachemap**. Geef een beschrijfbare map op om
    cachebestanden in op te slaan, als u de standaard map niet wilt
    gebruiken.

#### Sessie

- **Sessie-afhandeling**. Het mechanisme waarmee Joomla een gebruiker
  identificeert wanneer deze verbonden is via de website gebruikmakend
  van tijdelijke cookies.
  - Database: De database sessieafhandeling is de standaard afhandeling
    omdat het de enige is die Joomla volledig zelf kan instellen en
    controleren.
  - Bestandssysteem: De bestandssyteem afhandeling zal wat sneller zijn
    als de database afhandeling, maar het heeft nodig dat PHP juist is
    ingesteld, anders crasht het en wordt Joomla volledig onbruikbaar.
    - **Session Save Path**. Selecteer, om het te gebruiken
      'Bestandssysteem' en voer daarna een volledig bestandssysteem pad
      in in het 'Sessie opslagpad' veld dat verschijnt. Zorg ervoor dat
      het pad voldoende rechten voor PHP heeft om bestanden te lezen en
      schrijven en of 'session garbage collection' ingeschakeld is om
      bestanden te verwijderen.Als dit pad niet ingeschakeld is, zal
      Joomla vertrouwen op de PHP session.save_path INI instelling of
      terugvallen op de temp map van het systeem (zoals gedefinieerd
      door de sys_get_temp_dir() PHP functie).Als geen van deze paden
      zijn ingesteld of dat de rechten fout zijn, dan is het over en
      uit. Om hier uit te komen moer het configuration.php bestand
      bewerkt worden en \$session_handler = 'database' ingesteld worden.
  - Andere handlers (APCu, Memcached, Redis, en WinCache) berusten alle
    op optionele PHP extensies en kunnen beschikbaar zijn als uw systeem
    ze ondersteund. APCu of WinCache hoeven niet beter te zijn dan de
    "plain" filesysteem optie. De Memcached en Redis handlers zijn
    overkill voor Joomla in een typische shared hosting omgeving. Dit
    type handlers zijn succesvol als u Joomla toepast in a load balanced
    omgeving waar meerdere servers zijn betrokken en de sessiegegevens
    voor de toepassing beschikbaar moeten zijn op alle servers.
- **Sessie levensduur (minuten)**. Gebruiker automatisch uitloggen nadat
  deze inactief is geweest voor het aantal ingestelde minuten. Stel dit
  niet te hoog in.
- **Shared (gedeelde) sessie**. Indien geactiveerd wordt de
  gebruikerssessie gedeeld tussen het frontend en het beheergedeelte van
  de site. Let op dat het wijzigen van deze waarde alle bestaande
  sessies op de site ongeldig maakt.Dit is niet beschikbaar als de
  [Forceer HTTPS](#forcehttps) optie staat op 'Alleen administrator'.
- **Volg sessie metadata**.
  - Wanneer ingeschakeld, zullen aanvullende metagegevens over een
    gebruikerssessie (met inbegrip van hun gebruikersnaam, gebruikers-ID
    en de toepassing waarmee zij zijn aangemeld) worden opgeslagen in de
    sessie-databasetabel.
  - Wanneer uitgeschakeld, zijn functies die afhankelijk zijn van deze
    gegevens niet beschikbaar.

### Server

[Volledige
afbeelding.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Server/nl "Help4.x:Site Global Configuration Server/nl")

#### Server

- **Pad naar map met tijdelijke opslag (tmp)**. Kies een schrijfbare map
  om tijdelijke bestanden op te slaan.
- **GZIP paginacompressie**.
  - Ja: Joomla kan de gegenereerde HTML-pagina's automatisch comprimeren
    met GZip, waardoor ze kleiner worden en de snelheid van de site
    wordt verhoogd.
  - Nee: Schakel het uit als de server dat al doet of als het conflicten
    geeft met extensies van derden.
- **Foutrapportage**. Deze parameter stelt het niveau van foutrapportage
  in dat door PHP gebruikt moet worden op de Joomla site.
  - Systeemstandaard: Leaves the level of error reporting to that set up
    in the server.
  - Geen: Switches off error reporting.
  - Eenvoudig: Override the server setting to give a basic level of
    reporting.
  - Maximum: Override the server setting to reporting of all
    errors.Should your Joomla site fail to the extent that it is not
    possible to use the administrator page to activate error reporting,
    you can switch on full error reporting by editing the
    'configuration.php' file. Changing the '\$error_reporting' parameter
    in that file to a value of 'maximum' is the equivalent to setting
    Error Reporting to 'Maximum'.
- **Forceer HTTPS**. Forceer toegang voor de geselecteerde delen om
  alleen met HTTPS (versleutelde HTTP verbindingen met het https://
  protocolvoorvoegsel) te verschijnen en forceer ook veilige cookies.
  Opmerking: HTTPS dient ingeschakeld te zijn op de server om gebruik te
  kunnen maken van deze optie.

#### Locatie

- **Tijdzone website**. Kies een stad uit de lijst om de weergave van
  datum en tijd in te stellen.

#### Webservices

- **CORS inschakelen**. Cross-Origin Resource Sharing
  (<a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">CORS</a>) stelt scripts die in een
  browser worden uitgevoerd in staat om te communiceren met bronnen van
  een andere oorsprong.
  - **Access-Control-Allow-Origin**. Bepaalt de oorsprong om webservices
    te benaderen op deze website, teruggestuurd als antwoord op een
    'preflight' verzoek. Standaard: \* (=all).
  - **Access-Control-Allow-Headers**. Bepaalt de header(s) die, in
    antwoord op een 'preflight' verzoek, teruggestuurd worden.
    Standaard: Content-Type,X-Joomla-Token.
  - **Access-Control-Allow-Methods**. Bepaalt de webservice-methode(s)
    die toegang hebben tot deze site, die teruggestuurd word(t)(en) als
    reactie op een 'preflight' verzoek. Standaard: alle beschikbare
    methodes voor de gevraagde route.

#### Proxy

- **Achter Load balancer**. Schakel, als de site zich achter een 'Load
  balancer' of 'Reverse-proxy' bevindt, deze instelling in zodat
  IP-adressen en andere instellingen binnen Joomla automatisch rekening
  houden met deze instelling.
- **Outbound proxy inschakelen**. Sommige hosts staan standaard geen
  netwerktoegang van de site naar de buitenwereld toe en eisen dat er
  handmatig een uitgaande proxy geconfigureerd wordt.
  - **Outbound proxy host**. Host (domein) naam of IP-adres.
  - **Outbound proxy poort**.
  - **Outbound proxy gebruikersnaam**. Laat dit leeg als de uitgaande
    proxy geen authenticatie vereist.
  - **Outbound proxy wachtwoord**.

#### Database

- **Databasetype**. Het gebruikte type database dat u tijdens de
  installatie hebt gekozen.Bewerk dit veld niet tenzij u moet migreren
  naar een ander type database, eventueel veroorzaakt door het verhuizen
  naar een andere hosting provider.
- **Host**. De hostnaam van uw database die u tijdens de installatie
  hebt ingevoerd.Bewerk dit veld niet tenzij u moet migreren naar een
  ander type database, eventueel veroorzaakt door het verhuizen naar een
  andere hosting provider.
- **Database gebruikersnaam**. De gebruikersnaam waarmee u toegang hebt
  tot uw database welke tijdens de installatie werd ingevoerd.Bewerk dit
  veld niet tenzij u moet migreren naar een ander type database,
  eventueel veroorzaakt door het verhuizen naar een andere hosting
  provider.
- **Database wachtwoord**. Het wachtwoord dat gebruikt moet worden om de
  database te benaderen.Bewerk dit veld niet tenzij u moet migreren naar
  een ander type database, eventueel veroorzaakt door het verhuizen naar
  een andere hosting provider.
- **Databasenaam**. De naam van uw database die u tijdens de installatie
  hebt ingevoerd.Bewerk dit veld niet tenzij u moet migreren naar een
  ander type database, eventueel veroorzaakt door het verhuizen naar een
  andere hosting provider.
- **Voorvoegsel databasetabel**. Het voorvoegsel (prefix) voor de
  databasetabel die u tijdens de installatie hebt ingevoerd.Bewerk dit
  veld niet tenzij u moet migreren naar een ander type database,
  eventueel veroorzaakt door het verhuizen naar een andere hosting
  provider.
- **Connectie encryptie**.
  - Standaard (server gecontroleerd)
  - Eén weg authenticatie
    - **Controleer servercertificaat**.
      - **Pad naar CA bestand**. Bestandssysteem pad.
  - Twee-traps authenticatie
    - **Pad naar privé sleutelbestand**. Bestandssysteem locatie.
    - **Pad naar certificaatbestand**. Bestandssysteem locatie.
    - **Controleer servercertificaat**.
      - **Pad naar CA bestand**. Bestandssysteem pad.
    - **Ondersteunde Cipher Suit: (optioneel)**. Niet verplicht (alleen
      aanbevolen voor ervaren gebruikers) – zie, voor meer details, de
      documentatie van uw database.

#### E-mail

- **Mail versturen**.
  - Ja: Selecteer ja om het verzenden van mail in te schakelen.
  - Nee: Selecteer nee om het verzenden van mail uit te schakelen.
    Aanbevolen wordt de website offline te zetten wanneer de
    mailverzending wordt uitgeschakeld.
- **Groepsmail uitschakelen**.
  - Ja: Selecteer ja om groepsmail uit te schakelen.
  - Nee: Selecteer nee om het te activeren.
- **E-mail afzender**. Het e-mailadres dat gebruikt wordt om e-mails van
  uw website te versturen.
- **Afzendernaam**. De tekst die weergegeven wordt in het veld "Van:"
  wanneer er e-mails vanaf de website verstuurd worden.
- **Beantwoorden aan e-mail**. Het e-mailadres dat gebruikt wordt om
  reacties van gebruik(s) te ontvangen.
- **Beantwoorden aan naam**. Tekst getoond in het "Aan:"-veld als
  gebruiker(s) reageren op ontvangen e-mail.
- **Mailer**. Selecteer de mailer om e-mails te versturen via de
  website.

### Loggen

[Volledige
afbeelding.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Logging/nl "Help4.x:Site Global Configuration Logging/nl")

#### Loggen

- **Pad naar logmap**. Joomla kan optioneel een logboekbestand bijhouden
  van activiteiten van zichzelf en extensies van derden. Geef het
  absoluut pad naar een map die beschrijfbaar is door PHP; als het
  ontbreekt of niet beschrijfbaar is, zal Joomla helemaal niet laden. Om
  veiligheidsredenen moet er geen map gebruikt worden met toegang tot
  systeembrede mappen zoals '/tmp'.
- **Log bijna alles**. Logt alles, behalve verouderde API's.
- **Log verouderde API**. Logt verouderde API's.

#### Aangepast loggen

- **Log prioriteiten**. Kan gebruikt worden om aangepast loggen te
  beheren. Selecteer de events die u in het logbestand wilt zien.
  Standaard is 'All'. De item(s) kunnen geselecteerd/niet-geselecteerd
  worden door op de uitklaplijst te klikken.
- **Log categorieën**. Een door komma's gescheiden lijst met log
  categorieën die opgenomen of uitgesloten moeten worden. Gebruikelijke
  log categorieën zijn, maar zijn niet beperkt tot: 'database',
  'databasequery', 'database-error', 'deprecated' en 'jerror'. Indien
  leeg is custom loggen uitgeschakeld.
- **Log categoriemodus**. Stelt de modus in van bovenstaande log
  categorieën.

### Tekstfilters

[Volledige
afbeelding.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Text_Filters/nl "Help4.x:Site Global Configuration Text Filters/nl")

Dit zijn de tekstfilters die toegepast worden op alle
tekstverwerkervelden in de geselecteerde groepen.

Met deze filteropties kan meer controle uitgeoefend worden op de HTML
die toegevoegd wordt. Dit kan zo streng en zo vrij ingesteld worden al
naar gelang het beste bij de website past. Het filteren gebeurt op basis
van opt-in en de standaard instellingen bieden een goede bescherming
tegen markup die gewoonlijk geassocieerd wordt met aanvallen op de
website.

### Rechten

[Volledige
afbeelding.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Permissions/nl "Help4.x:Site Global Configuration Permissions/nl")

Beheer de instellingen van de rechten voor onderstaande groepen.

- **Inloggen website**. Sta toe, of weiger het inloggen op de website
  voor gebruikers in de geselecteerde groep.
- **Inloggen beheer**. Sta toe, of weiger het inloggen op het
  beheergedeelte voor gebruikers in de geselecteerde groep.
- **Web services inloggen**. Sta Web services inloggen voor gebruikers
  in de geselecteerde groep al dan niet toe.
- **Offline toegang**. Sta toe, of weiger het inloggen als de site
  offline is voor gebruikers in de geselecteerde groep. Sta gebruikers
  in de groep toegang tot de website toe wanneer de website offline is.
- **Supergebruiker**. Sta gebruikers in de geselecteerde groep alle
  handelingen op de hele website toe ongeacht andere
  rechteninstellingen.
- **Alleen instellingenopties**. Sta toe of weiger de instellingenopties
  van gebruikers in de geselecteerde groep. De instelling staat
  gebruikers uit de groep toe om de opties van deze extensie te
  bewerken, uitgezonderd de rechten.
- **Toegang tot beheerdersinterface**. Sta gebruikers in de
  geselecteerde groep toegang toe tot alle beheerdersinterfaces behalve
  de algemene instellingen.
- **Maken**. Sta gebruikers in de geselecteerde groep toe om inhoud aan
  elke extensie toe te voegen.
- **Verwijderen**. Sta toe of weiger het verwijderen door gebruikers in
  de geselecteerde groep. Verwijderen staat gebruikers in deze groep toe
  om inhoud van elke extensie te verwijderen.
- **Bewerken**. Toestaan of weigeren voor Bewerken voor de gebruikers in
  deze groep. Bewerken staat de gebruikers in deze groep toe om inhoud
  van elke extensie te bewerken.
- **Bewerk status**. Sta toe of weiger de bewerk status voor gebruikers
  in de geselecteerde groep. Bewerk status staat gebruikers in de groep
  toe om de status van inhoud van elke extensie te bewerken.
- **Bewerk eigen**. Sta toe of weiger het bewerken van eigen inhoud door
  gebruikers in de geselecteerde groep. Bewerk eigen staat gebruikers in
  deze groep toe om inhoud van zichzelf te bewerken.
- **Bewerk waarde extra veld**. Sta gebruikers in de groep toe om elk
  waarde van een veld in elke extensie te bewerken.

Indien deze instelling wijzigen worden ze toegepast op deze en alle
subgroepen, componenten en inhoud.

- Merk op dat **Geweigerd** elke overgenomen instelling zal overrulen,
  evenals de instellingen in elke subgroep, component of inhoud. In
  conflictsituaties gaat **Weigeren** voor.
- **Niet ingesteld** is gelijk aan **Geweigerd** maar kan gewijzigd
  worden in de subgroepen, componenten en inhoud.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#screenshot) hierboven.

- **Opslaan**. Slaat de algemene instellingen opties op en blijft op het
  huidige scherm.
- **Opslaan & sluiten**. Slaat de algemene instellingen opties op en
  sluit het huidige scherm.
- **Sluiten**. Sluit het huidige scherm en keert terug naar het vorige
  scherm zonder wijzigingen die u misschien heeft gedaan op te slaan.
- **Inline help in-/uitschakelen**.
- **Help**. Opent dit helpscherm.

## Snelle tips

- De meeste, zo niet alle, instellingen kunnen eenmaal ingesteld worden
  en daarna zo blijven.
- Als er belangrijke wijzigingen aangebracht moeten worden, overweeg dan
  de site offline te halen om testen en zeker te weten dat alles goed
  werkt.
- De instellingen worden opgeslagen in '\[Joomla\]/configuration.php'. U
  moet of de FTP-layer activeren of het 'configuration.php' bestand
  schrijfbaar maken om uw wijzigingen op te slaan.

## Verwante informatie

- [Back-up beginselen voor een Joomla!
  website](https://docs.joomla.org/Backup_Basics_for_a_Joomla!_Web_Site/nl "Backup Basics for a Joomla! Web Site/nl")
- [Beveiliging
  checklist](https://docs.joomla.org/Security_Checklist/nl "Security Checklist/nl")
- <img src="https://docs.joomla.org/images/4/49/Compat_icon_3_x_long.png"
  decoding="async" data-file-width="75" data-file-height="16" width="75"
  height="16" alt="Joomla 3.x" />
