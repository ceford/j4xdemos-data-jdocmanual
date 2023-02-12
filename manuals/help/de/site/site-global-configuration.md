<!-- Filename: Help4.x:Site_Global_Configuration / Display title: Konfiguration -->

## Beschreibung

Der Bildschirm (globale) Konfiguration ermöglicht es, die Joomla-Website
mit persönlichen Einstellungen zu konfigurieren. Die in diesem
Bildschirm vorgenommenen Einstellungen gelten für die gesamte Website.

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

[Vollständiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Site/de "Help4.x:Site Global Configuration Site/de")

#### Site

- **Name der Website**. Den Name der Website eingeben. Er wird an
  verschiedenen Stellen verwendet (zum Beispiel in der Titelleiste des
  Browsers im Backend und den Offline-Seiten).
- **Website offline**. Zugriff auf das Frontend ermöglichen. [Mehr
  erfahren.](https://docs.joomla.org/J3.x:Taking_the_website_temporarily_offline/de "J3.x:Taking the website temporarily offline/de")
  - **Offline-Text**.
    - Eigenen Text benutzen: Den Text unter 'Eigener Text' eingeben.
    - Standardtext benutzen: Der Standardtext wird aus der Sprachdatei
      geladen.
  - **Offline-Bild**. Ein Bild, das auf der Standard Offline-Seite
    angezeigt wird. Es soll nicht breiter als 400 Pixel sein.
- **Frontend-Bearbeitung**. Die Bearbeitung von Modulen und
  Menüeinträgen ermöglichen.
- **Standard Editor**. Den Standard-Texteditor wählen. Registrierte
  Benutzer können die Einstellung in ihrem Profil ändern.
- **Standard Captcha**. Die Standard Captcha-Einstellung für die Site
  auswählen. Weitere Daten im
  [Captcha-Plugin](https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_CAPTCHA_Group/de "Chunk4x:Extensions Plugin Manager Edit CAPTCHA Group/de")
  eingeben.
- **Standard Zugriffsebene**. Die Standard-Zugriffsebene für neue
  Einträge wählen.
- **Standard Listenlänge**. Die Standard-Listenlänge im Backend für alle
  Benutzer wählen.
- **Standard Feed-Länge**. Die Anzahl der Beiträge wählen, die in Feeds
  gezeigt werden.
- **Feed-E-Mail**. Der RSS- und Atom-Feed enthalten die E-Mail-Adresse
  des Autors.
  - Autor-E-Mail: Nutzt die E-Mail-Adresse des Autors aus
    [Benutzer](https://docs.joomla.org/Help4.x:Users/de "Help4.x:Users/de").
  - Website-E-Mail: Nutzt für jeden Beitrag die
    [Absenderadresse](#fromemail).

#### Metadaten

- **Meta-Beschreibung**. Eine Beschreibung der gesamten Website für
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
  von Beiträgen an.
- **Joomla-Version anzeigen**. Steuert, ob der Meta-Tag 'generator' im
  Header des HTML-Dokuments im Frontend und in Atom-Feeds die genaue
  Version der Joomla-Site enthält. Es wird empfohlen, diese Option aus
  Sicherheitsgründen zu deaktivieren.

#### SEO

Suchmaschinenoptimierung

- **Suchmaschinen-freundliche URL**. Optimiert die Webadressen (URLs)
  für Suchmaschinen.
- **URL-Rewrite nutzen**.
  - Apache und Litespeed: 'htaccess.txt' in '.htaccess' umbenennen
    <a href="https://httpd.apache.org/docs/2.4/howto/htaccess.html"
    class="external text" target="_blank"
    rel="nofollow noreferrer noopener">Mehr erfahren.</a>
  - IIS: 'web.config.txt' in 'web.config' umbenennen
  - NginX: [Server
    konfigurieren](https://docs.joomla.org/Nginx/de "Nginx/de")
  - Für andere Server oder wenn etwas unklar ist, bitte den
    Hosting-Provider kontaktieren.
- **Dateiendung an URL anfügen**. In der Einstellung "Ja" fügt das
  System eine zum Dokumenttyp passende Endung an die Webadresse an.
- **Unicode Aliase**. Eine Auswahl zwischen Umschreibung
  (transliteration) und Unicode-Aliase treffen. Die Standardeinstellung
  ist die Umschreibung von Aliasen.
- **Websitename auch im Seitentitel**. Alle Seitentitel mit dem
  Websitenamen beginnen oder beenden (zum Beispiel "Mein Websitename -
  Mein Beitragsname").

#### Cookies

- **Domaincookie**. Die Domain eingeben, die für Sitzungscookies genutzt
  werden soll. Mit einem Punkt '.' starten, wenn der Sitzungscookie auch
  für alle Subdomains gelten soll.
- **Cookie-Pfad**. Der Pfad, für den der Cookie gültig ist.

### System

[Vollständiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_System/de "Help4.x:Site Global Configuration System/de")

#### Fehlersuche

Debug

- **System debuggen**. Wenn aktiviert, werden, falls vorhanden,
  diagnostische Informationen, Übersetzungen und SQL-Fehler angezeigt.
  Die Informationen werden am unteren Ende auf jeder Seite im
  Joomla!-Backend und Frontend angezeigt. Es wird ausdrücklich davon
  abgeraten, den Debug-Modus auf einer Live-Seite anzuwenden.
- **Sprache debuggen**. Auswählen, ob die Fehleranzeiger
  \*\*...\*\*oder ??...?? für die Joomla-Sprachdateien angezeigt werden
  sollen. 'Sprache debuggen' funktioniert auch ohne die Aktivierung von
  'System debuggen', zeigt dann allerdings nicht die benötigten
  zusätzlichen Informationen an, die bei der Korrektur der Fehler
  hilfreich wären.
  - **Sprachanzeige**. Auswählen, ob die Sprachkonstante oder der
    Sprachwert angezeigt werden sollen, wenn die Sprache debuggt wird.

#### Cache

Zwischenspeicher

- **Cache**. Den Zwischenspeicher (Cache) aktivieren und den Cache-Level
  angeben. [Mehr erfahren.](https://docs.joomla.org/Cache/de "Cache/de")
  - Normales Caching: Kleiner System-Cache.
  - Erweitertes Caching: Schnellerer, größerer System-Cache, inklusive
    eines Modul-Caches. Nicht für extrem große Webseiten zu empfehlen.
  - **Cache-Speicher**.
    - Datei: Der Caching-Mechanismus ist dateibasiert. Es muss darauf
      geachtet werden, dass die Cache-Verzeichnisse beschreibbar sind.
  - **Plattformspezifischer Cache**. Aktivieren, wenn sich die
    HTML-Ausgabe auf mobilen Geräten von anderen Geräten unterscheidet.
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
    weil er der einzige ist, den Joomla vollständig selbst konfigurieren
    und steuern kann.
  - Der Dateisystem-Handler ist etwas leistungsfähiger als der
    Datenbank-Handler, aber er erfordert, dass PHP richtig konfiguriert
    ist, sonst stürzt er ab und Joomla ist völlig unbrauchbar.
    - **Session-Speicherpfad**. Einen vollständigen Dateisystempfad
      eingeben. Dieser Pfad muss die entsprechenden Rechte für PHP
      haben, um Dateien lesen und schreiben zu können. Wenn 'session
      garbage collection' aktiviert ist, können Dateien von diesem Pfad
      gelöscht werden.Falls dieser Pfad nicht gesetzt ist, verlässt sich
      Joomla auf die PHP session.save_path INI-Konfiguration oder greift
      auf das temporäre Systemverzeichnis zurück (wie es durch die
      PHP-Funktion sys_get_temp_dir() definiert ist).Wenn keiner dieser
      Pfade konfiguriert ist oder die Berechtigungen falsch sind, ist
      alles zu Ende. Um das Problem zu beheben, muss die Datei
      configuration.php bearbeitet werden und der Wert \$session_handler
      = 'database' gesetzt werden.
  - Andere Handler (APCu, Memcached, Redis und WinCache) basieren alle
    auf optionalen PHP-Erweiterungen und sind möglicherweise verfügbar,
    falls das betreffende System sie unterstützt. APCu oder WinCache
    sind möglicherweise nicht besser als die „einfache“
    Dateisystemoption. Die Memcached- und Redis-Handler sind Overkill
    für Joomla in einer typischen Shared-Hosting-Umgebung. Diese Arten
    von Handlern sind geeignet, wenn man Joomla in einer Umgebung mit
    Lastverteilung einsetzt, in der mehrere Server beteiligt sind und
    die Sitzungsdaten für die Anwendung auf allen Servern verfügbar sein
    müssen.
- **Sitzungslänge**. Eine automatische Abmeldung, die nach Ablauf der
  eingegebenen Zeit (in Minuten) der Inaktivität eines Benutzers
  durchgeführt wird. Ein zu groß gewählter Wert ist ein
  Sicherheitsrisiko.
- **Gemeinsame Sitzungen**. Wenn diese Option aktiviert ist, wird die
  Sitzung eines Benutzers zwischen dem Frontend- und dem
  Administrationsbereich der Site geteilt. Die Änderung dieses Wertes
  macht alle bestehenden Sitzungen auf der Site ungültig.Die Option ist
  nicht verfügbar, wenn die Option [HTTPS erzwingen](#forcehttps) auf
  'Nur Administrator' eingestellt ist.
- **Sitzungs-Metadaten verfolgen**.
  - Ja: Zusätzliche Metadaten über die Sitzung eines Benutzers
    (einschließlich seines Benutzernamens, seiner Benutzer-ID und der
    Anwendung, bei der er angemeldet ist) werden in der
    Sitzungsdatenbanktabelle protokolliert.
  - Nein: Von diesen Daten abhängige Funktionen sind nicht verfügbar.

### Server

[Vollständiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Server/de "Help4.x:Site Global Configuration Server/de")

#### Server

- **Tempverzeichnis**. Bitte ein beschreibbares Verzeichnis für
  temporäre Dateien angeben.
- **Gzip-Komprimierung**.
  - Ja: Komprimiert die generierte HTML-Seite. JavaScript, CSS, Bilder
    etc. werden nicht komprimiert.
  - Nein: Wenn der Server komprimiert oder Konflikte mit Erweiterungen
    von Drittherstellern entstehen.
- **Fehler berichten**. Legt fest, wie ausführlich Fehlermeldungen von
  PHP auf der Joomla-Website sind.
  - Standard: Belässt die Stufe der Fehlermeldung so, wie sie auf dem
    Server eingestellt ist.
  - Keine: Schaltet die Fehlerausgabe aus.
  - Einfach: Setzt die Servereinstellung außer Kraft, sodass eine
    einfache Ausgabe möglich ist.
  - Maximum: Setzt die Servereinstellung außer Kraft, sodass die Ausgabe
    aller Fehler möglich ist.Sollte die Joomla-Seite so fehlerhaft sein,
    dass es nicht möglich ist, die Fehlermeldungen über die
    Administrator-Seite zu aktivieren, kann man die volle
    Fehlerberichterstattung einschalten, indem man die Datei
    'configuration.php' bearbeitet. Das Ändern des Parameters
    '\$error_reporting' in dieser Datei auf den Wert 'maximum' ist das
    Pendant zur Einstellung der Fehlermeldungen auf 'Maximum'.
- **HTTPS erzwingen**. Diese Option erzwingt, dass die Website in den
  ausgewählten Bereichen nur noch über HTTPS (verschlüsselte
  HTTP-Verbindungen mit dem Protokollpräfix https://) aufgerufen werden
  kann und sichere Cookies verwendet werden. Hinweis: Auf dem Server
  muss das HTTPS-Protokoll aktiviert sein, um diese Option verwenden zu
  können.

#### Zeitzone

- **Websitezeitzone**. Den gewünschten Ort auswählen, um die Anzeige für
  Datum und Uhrzeit einzurichten.

#### Web Services

- **CORS aktivieren**. Cross-Origin Resource Sharing
  (<a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">CORS</a>) ermöglicht es Skripten,
  die in einem Browser laufen, mit Ressourcen von einer anderen Domain
  zu interagieren.
  - **Access-Control-Allow-Origin**. Gibt die Origins an, welche auf die
    Web Services dieser Website zugreifen dürfen. Standard: \* (keine
    Einschränkungen).
  - **Access-Control-Allow-Headers**. Gibt die Header an, die als
    Antwort auf eine Preflight-Anfrage zurückgesendet werden. Standard:
    Content-Type,X-Joomla-Token.
  - **Access-Control-Allow-Methods**. Gibt die Web Service-Methode(n)
    an, auf die zugegriffen werden darf. Standard: Alle für die
    angeforderte Route verfügbaren Methoden.

#### Proxy

- **Load Balancer aktivieren**. Wenn die Website hinter einem Load
  Balancer oder Reverse Proxy liegt, diese Einstellung aktivieren, damit
  IP-Adressen und andere Konfigurationen innerhalb von Joomla dies
  automatisch berücksichtigen.
- **Proxy aktivieren**. Sorgt dafür, dass Joomla! einen Proxyserver zur
  Verbindung mit externen URLs nutzt. Dies ist in manchen
  Serverumgebungen notwendig, damit zum Beispiel die
  Joomla-Update-Komponente Daten abrufen kann.
  - **Hostname**. Den Namen oder die IP-Adresse des Proxy-Servers
    eingeben.
  - **Port**.
  - **Benutzer**. Der Benutzername für den Proxy-Server.
  - **Passwort**.

#### Datenbank

- **Typ**. Der verwendete Typ der Datenbank, der während der
  Installation eingegeben wurde.Dieses Feld sollte nicht verändert
  werden, außer in speziellen Fällen, wie beim Umzug der Datenbank zu
  einem neuen Webhoster.
- **Server**. Der Servername der Datenbank, der während der Installation
  eingegeben wurde.Dieses Feld sollte nicht verändert werden, außer in
  speziellen Fällen, wie beim Umzug der Datenbank zu einem neuen
  Webhoster.
- **Benutzer**. Der Benutzername für den Datenbankzugriff, der während
  der Installation eingegeben wurde.Dieses Feld sollte nicht verändert
  werden, außer in speziellen Fällen, wie beim Umzug der Datenbank zu
  einem neuen Webhoster.
- **Passwort**. Das Passwort, das für den Zugriff auf die Datenbank
  verwendet wird.Dieses Feld sollte nicht verändert werden, außer in
  speziellen Fällen, wie beim Umzug der Datenbank zu einem neuen
  Webhoster.
- **Datenbank**. Der Name der Datenbank, der während der Installation
  eingegeben wurde.Dieses Feld sollte nicht verändert werden, außer in
  speziellen Fällen, wie beim Umzug der Datenbank zu einem neuen
  Webhoster.
- **Präfix**. Das Präfix für die Datenbanktabellen. Es wurde während des
  Installationsvorgangs erstellt.Dieses Feld sollte nicht verändert
  werden, außer in speziellen Fällen, wie beim Umzug der Datenbank zu
  einem neuen Webhoster.
- **Verbindungsverschlüsselung**.
  - Standard (servergesteuert)
  - Einwege-Authentifizierung
    - **Server-Zertifikat verifizieren**.
      - **Pfad zur CA-Datei**. Pfad im Dateisystem.
  - Zwei-Wege-Authentifizierung
    - **Pfad zur privaten Schlüsseldatei**. Speicherort im Dateisystem.
    - **Pfad zur Zertifikatsdatei**. Speicherort im Dateisystem.
    - **Server-Zertifikat verifizieren**.
      - **Pfad zur CA-Datei**. Pfad im Dateisystem.
    - **Unterstützte Cipher Suite (optional)**. Kein Eintrag notwendig
      (nur für erfahrene User empfohlen) – mehr Details sind in der
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
- **Absendername**. Dieser Text wird zusätzlich im "Von:"-Bereich einer
  vom System gesendeten E-Mail ergänzt. Normalerweise der Site-Name.
- **Antwortadresse**. Die Standard-Antwortadresse, an die Antworten von
  Benutzern gesendet werden.
- **Antwortname** Dieser Text wird zusätzlich im "An:"-Bereich einer vom
  System gesendeten E-Mail ergänzt.
- **Mailer**. Die Mailerfunktion, mit der E-Mails verschickt werden.

### Protokollierung

[Vollständiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Logging/de "Help4.x:Site Global Configuration Logging/de")

#### Protokollierung

- **Protokollverzeichnis**. Joomla kann optional eine Protokolldatei
  über seine eigenen Operationen und die von Erweiterungen von
  Drittanbietern speichern. Einen absoluten Pfad zu einem Ordner
  angeben, der von PHP beschreibbar ist; wenn er fehlt oder nicht
  beschreibbar ist, wird Joomla überhaupt nicht geladen. Aus
  Sicherheitsgründen sollte kein Ordner mit systemweitem Zugriff wie
  '/tmp' verwendet werden.
- **Protokollieren**. Protokolliert alles außer veralteten APIs.
- **Veraltete (deprecated) API protokollieren**. Protokolliert veraltete
  APIs.

#### Benutzerdefiniert

- **Protokollprioritäten**. Kann zur Verwaltung der benutzerdefinierten
  Protokollierung verwendet werden. Die Ereignisse für die
  Protokolldatei wählen. Standard ist 'Alle'. Das Element kann durch
  Anklicken des Dropdown-Feldes aus- oder abgewählt werden.
- **Protokollkategorien**. Eine durch Kommas getrennte Liste von
  Protokollkategorien, die ein- oder ausgeschlossen werden sollen.
  Übliche Protokollkategorien sind unter anderem: 'database',
  'databasequery', 'database-error', 'deprecated' und 'jerror'. Wenn
  leer, ist die benutzerdefinierte Protokollierung deaktiviert.
- **Protokollkategoriemodus**. Setzt den Modus für die Liste der
  Protokollkategorien oben.

### Textfilter

[Vollständiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Text_Filters/de "Help4.x:Site Global Configuration Text Filters/de")

Diese Textfiltereinstellungen werden auf alle Texteditorfelder
angewandt, die von Benutzern der gewählten Gruppe eingereicht werden.

Diese Einstellungen ermöglichen die Kontrolle über den HTML-Code, den
Beitragsautoren einreichen können. Die Voreinstellung bietet einen
brauchbaren Schutz gegen übliche Angriffe auf die Website und deren
Code.

### Berechtigungen

[Vollständiges
Bildschirmfoto.](https://docs.joomla.org/Help4.x:Site_Global_Configuration_Permissions/de "Help4.x:Site Global Configuration Permissions/de")

Verwalten der Zugriffsrechte von Benutzergruppen.

- **Site-Anmeldung**. Die Anmeldung an der Website für Benutzer der
  gewählten Gruppe zulassen oder verweigern.
- **Administratoranmeldung**. Die Anmeldung als Administrator für
  Benutzer der gewählten Gruppe zulassen oder verweigern.
- **Web-Services-Anmeldung**. Die Anmeldung für Web-Services für
  Benutzer der gewählten Gruppe zulassen oder verweigern.
- **Offlinezugang**. Die Offline-Anmeldung für Benutzer der gewählten
  Gruppe zulassen oder verweigern. Erlaubt den Benutzern der Gruppe den
  Zugang zum Frontend, wenn die Site offline ist.
- **Super Benutzer**. Die Berechtigungen für 'Super-Benutzer' für
  Benutzer der gewählten Gruppe zulassen oder verweigern. Erlaubt den
  Benutzern der Gruppe, unabhängig von anderen
  Berechtigungseinstellungen, alle Aktionen auf der gesamten Site
  durchzuführen.
- **Nur Optionen konfigurieren**. Nur die Konfiguration von Optionen für
  Benutzer der gewählten Gruppe zulassen oder verweigern. Erlaubt
  Benutzern der Gruppe, Optionen zu bearbeiten, mit Ausnahme der
  Berechtigungen für beliebige Erweiterungen.
- **Administrationszugriff**. Zugriff auf die Administrationsoberfläche
  für Benutzer der gewählten Gruppe zulassen oder verweigern. Erlaubt
  den Benutzern der Gruppe den Zugriff auf die gesamte
  Administrationsoberfläche mit Ausnahme der 'Konfiguration'.
- **Erstellen**. Erstellung für Benutzer der gewählten Gruppe zulassen
  oder verweigern. Ermöglicht Benutzern der Gruppe das Erstellen
  beliebiger Inhalte in beliebigen Erweiterungen.
- **Löschen**. Das Löschen für Benutzer der gewählten Gruppe zulassen
  oder verweigern. Ermöglicht Benutzern der Gruppe das Löschen
  beliebiger Inhalte in einer beliebigen Erweiterung.
- **Bearbeiten**. Die Bearbeitung für Benutzer der gewählten Gruppe
  zulassen oder verweigern. Ermöglicht Benutzern der Gruppe, jeden
  Inhalt in jeder Erweiterung zu bearbeiten.
- **Status bearbeiten**. Bearbeiten des Status für Benutzer der
  gewählten Gruppe zulassen oder verweigern. Ermöglicht es Benutzern der
  Gruppe, den Status eines beliebigen Inhalts in einer beliebigen
  Erweiterung zu bearbeiten.
- **Eigene Inhalte bearbeiten**. Die Bearbeitung eigener Inhalte für
  Benutzer der gewählten Gruppe zulassen oder verweigern. Ermöglicht
  Benutzern der Gruppe die Bearbeitung von Inhalten, die sie in einer
  beliebigen Erweiterung selbst erstellt haben.
- **Inhalt von eigenen Feldern bearbeiten**. Erlaubt Benutzern der
  gewählten Gruppe, jeden Wert von eigenen Feldern zu bearbeiten, die in
  einer beliebigen Erweiterung eingegeben wurden.

Hier vorgenommene Einstellungen wirken sich auf die aktuelle Gruppe,
Untergruppen, Komponenten und Inhalte aus.

- **Verweigert** sorgt dafür, dass jede vererbte Einstellung und die
  Einstellungen jeder Untergruppe, Komponente oder Inhaltselementen
  überschrieben wird. Im Falle eines Einstellungskonflikts wird
  **Verweigert** mit Vorrang behandelt.
- **Nicht gesetzt** ist vergleichbar mit **Verweigert**, kann aber in
  Untergruppen, Komponenten und Inhaltselementen geändert werden.

## Werkzeugleiste

Das [Bildschirmfoto](#screenshot) zeigt die Werkzeugleiste im oberen
Bereich.

- **Speichern**. Speichert die Konfigurations-Optionen und bleibt auf
  der aktuellen Seite.
- **Speichern & Schließen**. Speichert die Konfigurations-Optionen und
  schließt die aktuelle Seite.
- **Schließen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück.
- **Inline-Hilfe umschalten**. Hilfetext unter einigen Optionen ein-
  oder ausschalten.
- **Hilfe**. Öffnet die Hilfeseite.

## Tipps

- Die meisten Einstellungen können einmal gesetzt und müssen nicht mehr
  aufgerufen werden.
- Wenn größere Änderungen vorgenommen werden, sollte die Website offline
  genommen und getestet werden, ob alles in Ordnung ist.
- Die Einstellungen werden in '\[Joomla\]/configuration.php'
  gespeichert. Um Änderungen speichern zu können, müssen FTP aktiviert
  oder für 'configuration.php' Schreibzugriff erlaubt sein.

## Verwandte Informationen

- [Backup-Grundlagen](https://docs.joomla.org/Backup_Basics_for_a_Joomla!_Web_Site/de "Backup Basics for a Joomla! Web Site/de")
- [Sicherheits-Checkliste](https://docs.joomla.org/Security_Checklist/de "Security Checklist/de")
- <img src="https://docs.joomla.org/images/4/49/Compat_icon_3_x_long.png"
  decoding="async" data-file-width="75" data-file-height="16" width="75"
  height="16" alt="Joomla 3.x" />
