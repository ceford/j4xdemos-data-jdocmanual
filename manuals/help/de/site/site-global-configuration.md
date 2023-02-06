<!-- Display title: Site Global Configuration -->

## Beschreibung

Der Bildschirm (globale) Konfiguration ermÃ¶glicht es, die
Joomla-Website mit persÃ¶nlichen Einstellungen zu konfigurieren. Die in
diesem Bildschirm vorgenommenen Einstellungen gelten fÃ¼r die gesamte
Website.

## Wie darauf zugreifen

- **System **→** Einstellungen **→** Konfiguration**

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/8/8d/Help-4x-global-configuration-screen-de.png/750px-Help-4x-global-configuration-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/8d/Help-4x-global-configuration-screen-de.png/1125px-Help-4x-global-configuration-screen-de.png 1.5x, https://docs.joomla.org/images/thumb/8/8d/Help-4x-global-configuration-screen-de.png/1500px-Help-4x-global-configuration-screen-de.png 2x"
data-file-width="2720" data-file-height="1700" width="750" height="469"
alt="Help-4x-global-configuration-screen-de.png" />

## Formular Felder

### Site

[VollstÃ¤ndiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Site/de "Help4.x:Site Global Configuration Site/de")

#### Site

- **Name der Website**. Den Name der Website eingeben. Er wird an
  verschiedenen Stellen verwendet (zum Beispiel in der Titelleiste des
  Browsers im Backend und den Offline-Seiten).
- **Website offline**. Zugriff auf das Frontend ermÃ¶glichen. [Mehr
  erfahren.](https://docs.joomla.org/J3.x:Taking_the_website_temporarily_offline/de "J3.x:Taking the website temporarily offline/de")
  - **Offline-Text**.
    - Eigenen Text benutzen: Den Text unter 'Eigener Text' eingeben.
    - Standardtext benutzen: Der Standardtext wird aus der Sprachdatei
      geladen.
  - **Offline-Bild**. Ein Bild, das auf der Standard Offline-Seite
    angezeigt wird. Es soll nicht breiter als 400 Pixel sein.
- **Frontend-Bearbeitung**. Die Bearbeitung von Modulen und
  MenÃ¼eintrÃ¤gen ermÃ¶glichen.
- **Standard Editor**. Den Standard-Texteditor wÃ¤hlen. Registrierte
  Benutzer kÃ¶nnen die Einstellung in ihrem Profil Ã¤ndern.
- **Standard Captcha**. Die Standard Captcha-Einstellung fÃ¼r die Site
  auswÃ¤hlen. Weitere Daten im
  [Captcha-Plugin](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_CAPTCHA_Group/de "Chunk4x:Extensions Plugin Manager Edit CAPTCHA Group/de")
  eingeben.
- **Standard Zugriffsebene**. Die Standard-Zugriffsebene fÃ¼r neue
  EintrÃ¤ge wÃ¤hlen.
- **Standard ListenlÃ¤nge**. Die Standard-ListenlÃ¤nge im Backend fÃ¼r
  alle Benutzer wÃ¤hlen.
- **Standard Feed-LÃ¤nge**. Die Anzahl der BeitrÃ¤ge wÃ¤hlen, die in
  Feeds gezeigt werden.
- **Feed-E-Mail**. Der RSS- und Atom-Feed enthalten die E-Mail-Adresse
  des Autors.
  - Autor-E-Mail: Nutzt die E-Mail-Adresse des Autors aus
    [Benutzer](https://docs.joomla.org/Help4.x:Users/de "Help4.x:Users/de").
  - Website-E-Mail: Nutzt fÃ¼r jeden Beitrag die
    [Absenderadresse](#fromemail).

#### Metadaten

- **Meta-Beschreibung**. Eine Beschreibung der gesamten Website fÃ¼r
  Suchmaschinen.
- **Robots**. Robots Anweisungen.
  - index, follow: Seite indizieren, den Links auf der Seite folgen.
  - noindex, follow: Seite nicht indizieren, den Links auf der Seite
    folgen. Beispiel ist eine Sitemap-Seite, deren Links indiziert, die
    Seite selbst aber nicht in Suchmaschinen gezeigt werden soll.
  - index, nofollow: Seite indizieren, den Links auf der Seite nicht
    folgen. Beispiel ist eine Seite mit einem Veranstaltungs-Kalender,
    die in Suchmaschinen gezeigt werden soll, aber nicht jede
    Veranstaltung soll indiziert werden.
  - noindex, nofollow: Seite nicht indizieren, den Links auf der Seite
    nicht folgen.
- **Inhaltsrechte**. Legt fest, welche Rechte andere Personen beim
  Gebrauch dieses Beitragsinhalts haben. Dies wird den Suchmaschinen mit
  Hilfe des Meta-Tags 'rights' im Header des HTML-Dokuments mitgeteilt.
- **Autor-Meta-Tag anzeigen**. Zeigt den Autor-Meta-Tag bei der Anzeige
  von BeitrÃ¤gen an.
- **Joomla-Version anzeigen**. Steuert, ob der Meta-Tag 'generator' im
  Header des HTML-Dokuments im Frontend und in Atom-Feeds die genaue
  Version der Joomla-Site enthÃ¤lt. Es wird empfohlen, diese Option aus
  SicherheitsgrÃ¼nden zu deaktivieren.

#### SEO

Suchmaschinenoptimierung

- **Suchmaschinen-freundliche URL**. Optimiert die Webadressen (URLs)
  fÃ¼r Suchmaschinen.
- **URL-Rewrite nutzen**.
  - Apache und Litespeed: 'htaccess.txt' in '.htaccess' umbenennen
    <a href="https://httpd.apache.org/docs/2.4/howto/htaccess.html"
    class="external text" target="_blank"
    rel="nofollow noreferrer noopener">Mehr erfahren.</a>
  - IIS: 'web.config.txt' in 'web.config' umbenennen
  - NginX: [Server
    konfigurieren](https://docs.joomla.org/Nginx/de "Nginx/de")
  - FÃ¼r andere Server oder wenn etwas unklar ist, bitte den
    Hosting-Provider kontaktieren.
- **Dateiendung an URL anfÃ¼gen**. In der Einstellung "Ja" fÃ¼gt das
  System eine zum Dokumenttyp passende Endung an die Webadresse an.
- **Unicode Aliase**. Eine Auswahl zwischen Umschreibung
  (transliteration) und Unicode-Aliase treffen. Die Standardeinstellung
  ist die Umschreibung von Aliasen.
- **Websitename auch im Seitentitel**. Alle Seitentitel mit dem
  Websitenamen beginnen oder beenden (zum Beispiel "Mein Websitename -
  Mein Beitragsname").

#### Cookies

- **Domaincookie**. Die Domain eingeben, die fÃ¼r Sitzungscookies
  genutzt werden soll. Mit einem Punkt '.' starten, wenn der
  Sitzungscookie auch fÃ¼r alle Subdomains gelten soll.
- **Cookie-Pfad**. Der Pfad, fÃ¼r den der Cookie gÃ¼ltig ist.

### System

[VollstÃ¤ndiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_System/de "Help4.x:Site Global Configuration System/de")

#### Fehlersuche

Debug

- **System debuggen**. Wenn aktiviert, werden, falls vorhanden,
  diagnostische Informationen, Ãœbersetzungen und SQL-Fehler angezeigt.
  Die Informationen werden am unteren Ende auf jeder Seite im
  Joomla!-Backend und Frontend angezeigt. Es wird ausdrÃ¼cklich davon
  abgeraten, den Debug-Modus auf einer Live-Seite anzuwenden.
- **Sprache debuggen**. AuswÃ¤hlen, ob die Fehleranzeiger
  \*\*...\*\*oder ??...?? fÃ¼r die Joomla-Sprachdateien angezeigt werden
  sollen. 'Sprache debuggen' funktioniert auch ohne die Aktivierung von
  'System debuggen', zeigt dann allerdings nicht die benÃ¶tigten
  zusÃ¤tzlichen Informationen an, die bei der Korrektur der Fehler
  hilfreich wÃ¤ren.
  - **Sprachanzeige**. AuswÃ¤hlen, ob die Sprachkonstante oder der
    Sprachwert angezeigt werden sollen, wenn die Sprache debuggt wird.

#### Cache

Zwischenspeicher

- **Cache**. Den Zwischenspeicher (Cache) aktivieren und den Cache-Level
  angeben. [Mehr erfahren.](https://docs.joomla.org/Cache/de "Cache/de")
  - Normales Caching: Kleiner System-Cache.
  - Erweitertes Caching: Schnellerer, grÃ¶ÃŸerer System-Cache, inklusive
    eines Modul-Caches. Nicht fÃ¼r extrem groÃŸe Webseiten zu empfehlen.
  - **Cache-Speicher**.
    - Datei: Der Caching-Mechanismus ist dateibasiert. Es muss darauf
      geachtet werden, dass die Cache-Verzeichnisse beschreibbar sind.
  - **Plattformspezifischer Cache**. Aktivieren, wenn sich die
    HTML-Ausgabe auf mobilen GerÃ¤ten von anderen GerÃ¤ten
    unterscheidet.
  - **Cache-Dauer**. Die maximale Dauer in Minuten, die eine Cache-Datei
    gespeichert bleibt, bevor sie aktualisiert wird.
  - **Cache-Verzeichnis**. Bitte ein beschreibbares Verzeichnis angeben,
    in dem die zwischengespeicherten (Cache)-Dateien abgelegt werden
    sollen.

#### Sitzung

Session

- **Sitzungsspeicher**. Der Mechanismus, mit dem Joomla! einen Benutzer
  identifiziert, sobald dieser mit der Website verbunden ist, wobei
  nicht-persistente Cookies verwendet werden.
  - Datenbank: Der Datenbank-Session-Handler ist der Standard-Handler,
    weil er der einzige ist, den Joomla vollstÃ¤ndig selbst
    konfigurieren und steuern kann.
  - Der Dateisystem-Handler ist etwas leistungsfÃ¤higer als der
    Datenbank-Handler, aber er erfordert, dass PHP richtig konfiguriert
    ist, sonst stÃ¼rzt er ab und Joomla ist vÃ¶llig unbrauchbar.
    - **Session-Speicherpfad**. Einen vollstÃ¤ndigen Dateisystempfad
      eingeben. Dieser Pfad muss die entsprechenden Rechte fÃ¼r PHP
      haben, um Dateien lesen und schreiben zu kÃ¶nnen. Wenn 'session
      garbage collection' aktiviert ist, kÃ¶nnen Dateien von diesem Pfad
      gelÃ¶scht werden.Falls dieser Pfad nicht gesetzt ist, verlÃ¤sst
      sich Joomla auf die PHP session.save_path INI-Konfiguration oder
      greift auf das temporÃ¤re Systemverzeichnis zurÃ¼ck (wie es durch
      die PHP-Funktion sys_get_temp_dir() definiert ist).Wenn keiner
      dieser Pfade konfiguriert ist oder die Berechtigungen falsch sind,
      ist alles zu Ende. Um das Problem zu beheben, muss die Datei
      configuration.php bearbeitet werden und der Wert \$session_handler
      = 'database' gesetzt werden.
  - Andere Handler (APCu, Memcached, Redis und WinCache) basieren alle
    auf optionalen PHP-Erweiterungen und sind mÃ¶glicherweise
    verfÃ¼gbar, falls das betreffende System sie unterstÃ¼tzt. APCu oder
    WinCache sind mÃ¶glicherweise nicht besser als die â€žeinfacheâ€œ
    Dateisystemoption. Die Memcached- und Redis-Handler sind Overkill
    fÃ¼r Joomla in einer typischen Shared-Hosting-Umgebung. Diese Arten
    von Handlern sind geeignet, wenn man Joomla in einer Umgebung mit
    Lastverteilung einsetzt, in der mehrere Server beteiligt sind und
    die Sitzungsdaten fÃ¼r die Anwendung auf allen Servern verfÃ¼gbar
    sein mÃ¼ssen.
- **SitzungslÃ¤nge**. Eine automatische Abmeldung, die nach Ablauf der
  eingegebenen Zeit (in Minuten) der InaktivitÃ¤t eines Benutzers
  durchgefÃ¼hrt wird. Ein zu groÃŸ gewÃ¤hlter Wert ist ein
  Sicherheitsrisiko.
- **Gemeinsame Sitzungen**. Wenn diese Option aktiviert ist, wird die
  Sitzung eines Benutzers zwischen dem Frontend- und dem
  Administrationsbereich der Site geteilt. Die Ã„nderung dieses Wertes
  macht alle bestehenden Sitzungen auf der Site ungÃ¼ltig.Die Option ist
  nicht verfÃ¼gbar, wenn die Option [HTTPS erzwingen](#forcehttps) auf
  'Nur Administrator' eingestellt ist.
- **Sitzungs-Metadaten verfolgen**.
  - Ja: ZusÃ¤tzliche Metadaten Ã¼ber die Sitzung eines Benutzers
    (einschlieÃŸlich seines Benutzernamens, seiner Benutzer-ID und der
    Anwendung, bei der er angemeldet ist) werden in der
    Sitzungsdatenbanktabelle protokolliert.
  - Nein: Von diesen Daten abhÃ¤ngige Funktionen sind nicht verfÃ¼gbar.

### Server

[VollstÃ¤ndiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Server/de "Help4.x:Site Global Configuration Server/de")

#### Server

- **Tempverzeichnis**. Bitte ein beschreibbares Verzeichnis fÃ¼r
  temporÃ¤re Dateien angeben.
- **Gzip-Komprimierung**.
  - Ja: Komprimiert die generierte HTML-Seite. JavaScript, CSS, Bilder
    etc. werden nicht komprimiert.
  - Nein: Wenn der Server komprimiert oder Konflikte mit Erweiterungen
    von Drittherstellern entstehen.
- **Fehler berichten**. Legt fest, wie ausfÃ¼hrlich Fehlermeldungen von
  PHP auf der Joomla-Website sind.
  - Standard: BelÃ¤sst die Stufe der Fehlermeldung so, wie sie auf dem
    Server eingestellt ist.
  - Keine: Schaltet die Fehlerausgabe aus.
  - Einfach: Setzt die Servereinstellung auÃŸer Kraft, sodass eine
    einfache Ausgabe mÃ¶glich ist.
  - Maximum: Setzt die Servereinstellung auÃŸer Kraft, sodass die
    Ausgabe aller Fehler mÃ¶glich ist.Sollte die Joomla-Seite so
    fehlerhaft sein, dass es nicht mÃ¶glich ist, die Fehlermeldungen
    Ã¼ber die Administrator-Seite zu aktivieren, kann man die volle
    Fehlerberichterstattung einschalten, indem man die Datei
    'configuration.php' bearbeitet. Das Ã„ndern des Parameters
    '\$error_reporting' in dieser Datei auf den Wert 'maximum' ist das
    Pendant zur Einstellung der Fehlermeldungen auf 'Maximum'.
- **HTTPS erzwingen**. Diese Option erzwingt, dass die Website in den
  ausgewÃ¤hlten Bereichen nur noch Ã¼ber HTTPS (verschlÃ¼sselte
  HTTP-Verbindungen mit dem ProtokollprÃ¤fix https://) aufgerufen werden
  kann und sichere Cookies verwendet werden. Hinweis: Auf dem Server
  muss das HTTPS-Protokoll aktiviert sein, um diese Option verwenden zu
  kÃ¶nnen.

#### Zeitzone

- **Websitezeitzone**. Den gewÃ¼nschten Ort auswÃ¤hlen, um die Anzeige
  fÃ¼r Datum und Uhrzeit einzurichten.

#### Web Services

- **CORS aktivieren**. Cross-Origin Resource Sharing
  (<a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">CORS</a>) ermÃ¶glicht es Skripten,
  die in einem Browser laufen, mit Ressourcen von einer anderen Domain
  zu interagieren.
  - **Access-Control-Allow-Origin**. Gibt die Origins an, welche auf die
    Web Services dieser Website zugreifen dÃ¼rfen. Standard: \* (keine
    EinschrÃ¤nkungen).
  - **Access-Control-Allow-Headers**. Gibt die Header an, die als
    Antwort auf eine Preflight-Anfrage zurÃ¼ckgesendet werden. Standard:
    Content-Type,X-Joomla-Token.
  - **Access-Control-Allow-Methods**. Gibt die Web Service-Methode(n)
    an, auf die zugegriffen werden darf. Standard: Alle fÃ¼r die
    angeforderte Route verfÃ¼gbaren Methoden.

#### Proxy

- **Load Balancer aktivieren**. Wenn die Website hinter einem Load
  Balancer oder Reverse Proxy liegt, diese Einstellung aktivieren, damit
  IP-Adressen und andere Konfigurationen innerhalb von Joomla dies
  automatisch berÃ¼cksichtigen.
- **Proxy aktivieren**. Sorgt dafÃ¼r, dass Joomla! einen Proxyserver zur
  Verbindung mit externen URLs nutzt. Dies ist in manchen
  Serverumgebungen notwendig, damit zum Beispiel die
  Joomla-Update-Komponente Daten abrufen kann.
  - **Hostname**. Den Namen oder die IP-Adresse des Proxy-Servers
    eingeben.
  - **Port**.
  - **Benutzer**. Der Benutzername fÃ¼r den Proxy-Server.
  - **Passwort**.

#### Datenbank

- **Typ**. Der verwendete Typ der Datenbank, der wÃ¤hrend der
  Installation eingegeben wurde.Dieses Feld sollte nicht verÃ¤ndert
  werden, auÃŸer in speziellen FÃ¤llen, wie beim Umzug der Datenbank zu
  einem neuen Webhoster.
- **Server**. Der Servername der Datenbank, der wÃ¤hrend der
  Installation eingegeben wurde.Dieses Feld sollte nicht verÃ¤ndert
  werden, auÃŸer in speziellen FÃ¤llen, wie beim Umzug der Datenbank zu
  einem neuen Webhoster.
- **Benutzer**. Der Benutzername fÃ¼r den Datenbankzugriff, der wÃ¤hrend
  der Installation eingegeben wurde.Dieses Feld sollte nicht verÃ¤ndert
  werden, auÃŸer in speziellen FÃ¤llen, wie beim Umzug der Datenbank zu
  einem neuen Webhoster.
- **Passwort**. Das Passwort, das fÃ¼r den Zugriff auf die Datenbank
  verwendet wird.Dieses Feld sollte nicht verÃ¤ndert werden, auÃŸer in
  speziellen FÃ¤llen, wie beim Umzug der Datenbank zu einem neuen
  Webhoster.
- **Datenbank**. Der Name der Datenbank, der wÃ¤hrend der Installation
  eingegeben wurde.Dieses Feld sollte nicht verÃ¤ndert werden, auÃŸer in
  speziellen FÃ¤llen, wie beim Umzug der Datenbank zu einem neuen
  Webhoster.
- **PrÃ¤fix**. Das PrÃ¤fix fÃ¼r die Datenbanktabellen. Es wurde wÃ¤hrend
  des Installationsvorgangs erstellt.Dieses Feld sollte nicht verÃ¤ndert
  werden, auÃŸer in speziellen FÃ¤llen, wie beim Umzug der Datenbank zu
  einem neuen Webhoster.
- **VerbindungsverschlÃ¼sselung**.
  - Standard (servergesteuert)
  - Einwege-Authentifizierung
    - **Server-Zertifikat verifizieren**.
      - **Pfad zur CA-Datei**. Pfad im Dateisystem.
  - Zwei-Wege-Authentifizierung
    - **Pfad zur privaten SchlÃ¼sseldatei**. Speicherort im Dateisystem.
    - **Pfad zur Zertifikatsdatei**. Speicherort im Dateisystem.
    - **Server-Zertifikat verifizieren**.
      - **Pfad zur CA-Datei**. Pfad im Dateisystem.
    - **UnterstÃ¼tzte Cipher Suite (optional)**. Kein Eintrag notwendig
      (nur fÃ¼r erfahrene User empfohlen) â€“ mehr Details sind in der
      Dokumentation zur Datenbank zu finden.

#### E-Mailing

- **Mails senden**.
  - Ja: Aktiviert das Versenden von E-Mails durch Joomla.
  - Nein: Deaktiviert das Versenden von E-Mails. Es wird empfohlen die
    Website offline zu nehmen, wenn die Mail-Funktion deaktiviert wird.
- **Serienmails deaktivieren**.
  - Ja: Die Serienmail-Funktion deaktivieren.
  - Nein: Die Funktion von berechtigten Benutzern verwendet werden.
- **Absenderadresse**. Diese E-Mail-Adresse erscheint bei den von der
  Website verschickten E-Mails.
- **Absendername**. Dieser Text wird zusÃ¤tzlich im "Von:"-Bereich einer
  vom System gesendeten E-Mail ergÃ¤nzt. Normalerweise der Site-Name.
- **Antwortadresse**. Die Standard-Antwortadresse, an die Antworten von
  Benutzern gesendet werden.
- **Antwortname** Dieser Text wird zusÃ¤tzlich im "An:"-Bereich einer
  vom System gesendeten E-Mail ergÃ¤nzt.
- **Mailer**. Die Mailerfunktion, mit der E-Mails verschickt werden.

### Protokollierung

[VollstÃ¤ndiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Logging/de "Help4.x:Site Global Configuration Logging/de")

#### Protokollierung

- **Protokollverzeichnis**. Joomla kann optional eine Protokolldatei
  Ã¼ber seine eigenen Operationen und die von Erweiterungen von
  Drittanbietern speichern. Einen absoluten Pfad zu einem Ordner
  angeben, der von PHP beschreibbar ist; wenn er fehlt oder nicht
  beschreibbar ist, wird Joomla Ã¼berhaupt nicht geladen. Aus
  SicherheitsgrÃ¼nden sollte kein Ordner mit systemweitem Zugriff wie
  '/tmp' verwendet werden.
- **Protokollieren**. Protokolliert alles auÃŸer veralteten APIs.
- **Veraltete (deprecated) API protokollieren**. Protokolliert veraltete
  APIs.

#### Benutzerdefiniert

- **ProtokollprioritÃ¤ten**. Kann zur Verwaltung der benutzerdefinierten
  Protokollierung verwendet werden. Die Ereignisse fÃ¼r die
  Protokolldatei wÃ¤hlen. Standard ist 'Alle'. Das Element kann durch
  Anklicken des Dropdown-Feldes aus- oder abgewÃ¤hlt werden.
- **Protokollkategorien**. Eine durch Kommas getrennte Liste von
  Protokollkategorien, die ein- oder ausgeschlossen werden sollen.
  Ãœbliche Protokollkategorien sind unter anderem: 'database',
  'databasequery', 'database-error', 'deprecated' und 'jerror'. Wenn
  leer, ist die benutzerdefinierte Protokollierung deaktiviert.
- **Protokollkategoriemodus**. Setzt den Modus fÃ¼r die Liste der
  Protokollkategorien oben.

### Textfilter

[VollstÃ¤ndiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Text_Filters/de "Help4.x:Site Global Configuration Text Filters/de")

Diese Textfiltereinstellungen werden auf alle Texteditorfelder
angewandt, die von Benutzern der gewÃ¤hlten Gruppe eingereicht werden.

Diese Einstellungen ermÃ¶glichen die Kontrolle Ã¼ber den HTML-Code, den
Beitragsautoren einreichen kÃ¶nnen. Die Voreinstellung bietet einen
brauchbaren Schutz gegen Ã¼bliche Angriffe auf die Website und deren
Code.

### Berechtigungen

[VollstÃ¤ndiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Permissions/de "Help4.x:Site Global Configuration Permissions/de")

Verwalten der Zugriffsrechte von Benutzergruppen.

- **Site-Anmeldung**. Die Anmeldung an der Website fÃ¼r Benutzer der
  gewÃ¤hlten Gruppe zulassen oder verweigern.
- **Administratoranmeldung**. Die Anmeldung als Administrator fÃ¼r
  Benutzer der gewÃ¤hlten Gruppe zulassen oder verweigern.
- **Web-Services-Anmeldung**. Die Anmeldung fÃ¼r Web-Services fÃ¼r
  Benutzer der gewÃ¤hlten Gruppe zulassen oder verweigern.
- **Offlinezugang**. Die Offline-Anmeldung fÃ¼r Benutzer der gewÃ¤hlten
  Gruppe zulassen oder verweigern. Erlaubt den Benutzern der Gruppe den
  Zugang zum Frontend, wenn die Site offline ist.
- **Super Benutzer**. Die Berechtigungen fÃ¼r 'Super-Benutzer' fÃ¼r
  Benutzer der gewÃ¤hlten Gruppe zulassen oder verweigern. Erlaubt den
  Benutzern der Gruppe, unabhÃ¤ngig von anderen
  Berechtigungseinstellungen, alle Aktionen auf der gesamten Site
  durchzufÃ¼hren.
- **Nur Optionen konfigurieren**. Nur die Konfiguration von Optionen
  fÃ¼r Benutzer der gewÃ¤hlten Gruppe zulassen oder verweigern. Erlaubt
  Benutzern der Gruppe, Optionen zu bearbeiten, mit Ausnahme der
  Berechtigungen fÃ¼r beliebige Erweiterungen.
- **Administrationszugriff**. Zugriff auf die AdministrationsoberflÃ¤che
  fÃ¼r Benutzer der gewÃ¤hlten Gruppe zulassen oder verweigern. Erlaubt
  den Benutzern der Gruppe den Zugriff auf die gesamte
  AdministrationsoberflÃ¤che mit Ausnahme der 'Konfiguration'.
- **Erstellen**. Erstellung fÃ¼r Benutzer der gewÃ¤hlten Gruppe zulassen
  oder verweigern. ErmÃ¶glicht Benutzern der Gruppe das Erstellen
  beliebiger Inhalte in beliebigen Erweiterungen.
- **LÃ¶schen**. Das LÃ¶schen fÃ¼r Benutzer der gewÃ¤hlten Gruppe
  zulassen oder verweigern. ErmÃ¶glicht Benutzern der Gruppe das
  LÃ¶schen beliebiger Inhalte in einer beliebigen Erweiterung.
- **Bearbeiten**. Die Bearbeitung fÃ¼r Benutzer der gewÃ¤hlten Gruppe
  zulassen oder verweigern. ErmÃ¶glicht Benutzern der Gruppe, jeden
  Inhalt in jeder Erweiterung zu bearbeiten.
- **Status bearbeiten**. Bearbeiten des Status fÃ¼r Benutzer der
  gewÃ¤hlten Gruppe zulassen oder verweigern. ErmÃ¶glicht es Benutzern
  der Gruppe, den Status eines beliebigen Inhalts in einer beliebigen
  Erweiterung zu bearbeiten.
- **Eigene Inhalte bearbeiten**. Die Bearbeitung eigener Inhalte fÃ¼r
  Benutzer der gewÃ¤hlten Gruppe zulassen oder verweigern. ErmÃ¶glicht
  Benutzern der Gruppe die Bearbeitung von Inhalten, die sie in einer
  beliebigen Erweiterung selbst erstellt haben.
- **Inhalt von eigenen Feldern bearbeiten**. Erlaubt Benutzern der
  gewÃ¤hlten Gruppe, jeden Wert von eigenen Feldern zu bearbeiten, die
  in einer beliebigen Erweiterung eingegeben wurden.

Hier vorgenommene Einstellungen wirken sich auf die aktuelle Gruppe,
Untergruppen, Komponenten und Inhalte aus.

- **Verweigert** sorgt dafÃ¼r, dass jede vererbte Einstellung und die
  Einstellungen jeder Untergruppe, Komponente oder Inhaltselementen
  Ã¼berschrieben wird. Im Falle eines Einstellungskonflikts wird
  **Verweigert** mit Vorrang behandelt.
- **Nicht gesetzt** ist vergleichbar mit **Verweigert**, kann aber in
  Untergruppen, Komponenten und Inhaltselementen geÃ¤ndert werden.

## Werkzeugleiste

Das [Bildschirmfoto](#screenshot) zeigt die Werkzeugleiste im oberen
Bereich.

- **Speichern**. Speichert die Konfigurations-Optionen und bleibt auf
  der aktuellen Seite.
- **Speichern & SchlieÃŸen**. Speichert die Konfigurations-Optionen und
  schlieÃŸt die aktuelle Seite.
- **SchlieÃŸen**. SchlieÃŸt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Ã„nderungen zurÃ¼ck.
- **Inline-Hilfe umschalten**. Hilfetext unter einigen Optionen ein-
  oder ausschalten.
- **Hilfe**. Ã–ffnet die Hilfeseite.

## Tipps

- Die meisten Einstellungen kÃ¶nnen einmal gesetzt und mÃ¼ssen nicht
  mehr aufgerufen werden.
- Wenn grÃ¶ÃŸere Ã„nderungen vorgenommen werden, sollte die Website
  offline genommen und getestet werden, ob alles in Ordnung ist.
- Die Einstellungen werden in '\[Joomla\]/configuration.php'
  gespeichert. Um Ã„nderungen speichern zu kÃ¶nnen, mÃ¼ssen FTP
  aktiviert oder fÃ¼r 'configuration.php' Schreibzugriff erlaubt sein.

## Verwandte Informationen

- [Backup-Grundlagen](https://docs.joomla.org/Backup_Basics_for_a_Joomla!_Web_Site/de "Backup Basics for a Joomla! Web Site/de")
- [Sicherheits-Checkliste](https://docs.joomla.org/Security_Checklist/de "Security Checklist/de")
- <img src="https://docs.joomla.org/images/4/49/Compat_icon_3_x_long.png"
  decoding="async" data-file-width="75" data-file-height="16" width="75"
  height="16" alt="Joomla 3.x" />
