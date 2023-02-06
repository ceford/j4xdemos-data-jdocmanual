<!-- Display title: Users: Options -->

## Beschreibung

Zu den Benutzeroptionen, die global fÃ¼r alle Benutzer festgelegt
werden, gehÃ¶ren

- Captcha,
- erlaubte Eigen-Registrierung und Art der Registrierung,
- die Standardbenutzergruppe fÃ¼r neue Benutzer,
- ZÃ¤hler fÃ¼r ein zurÃ¼ckgesetztes Passwort oder Benutzernamen,
- E-Mail-Benachrichtigung an die Administration bei der Registrierung
  neuer Benutzer und mehr.

## Wie darauf zugreifen

**Benutzer **→** Verwalten**

- auf den Button **Optionen** der Werkzeugleiste klicken.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/4/47/Help-4x-Users-Options-screen-de.png/800px-Help-4x-Users-Options-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/47/Help-4x-Users-Options-screen-de.png/1200px-Help-4x-Users-Options-screen-de.png 1.5x, https://docs.joomla.org/images/thumb/4/47/Help-4x-Users-Options-screen-de.png/1600px-Help-4x-Users-Options-screen-de.png 2x"
data-file-width="2400" data-file-height="1500" width="800" height="500"
alt="Help-4x-Users-Options-screen-de.png" />

## Formular Felder

### Benutzeroptionen

- **Benutzerregistrierung**.
  - Ja: Benutzer kÃ¶nnen sich Ã¼ber das Frontend mit dem
    "Registrieren"-Link des Moduls
    [Anmeldung](https://docs.joomla.org/Help4.x:Site_Modules:_Login/de "Special:MyLanguage/Help4.x:Site Modules: Login/de")
    registrieren.
  - Nein: Der 'Registrieren'-Link wird nicht angezeigt.
- **Gruppe fÃ¼r neue Benutzer**. Zu dieser
  [Gruppe](https://docs.joomla.org/Help4.x:Users:_Groups/de "Special:MyLanguage/Help4.x:Users: Groups/de")
  werden Benutzer automatisch hinzugefÃ¼gt, die sich Ã¼ber das Frontend
  registrieren. Standard ist 'Registriert'.
- **Gast Benutzergruppe**. Zu dieser Standard-Benutzergruppe zÃ¤hlen
  alle als Gast bezeichneten (nicht angemeldeten) Benutzer. Inhalt kann
  fÃ¼r GÃ¤ste, aber nicht fÃ¼r eingewÃ¤hlte Benutzer sichtbar sein. <a
  href="https://magazine.joomla.org/all-issues/june-2021/explore-the-core-controlling-user-access?"
  class="external text" target="_blank" rel="noreferrer noopener">Mehr
  erfahren.</a>
- **Passwort mitsenden**. Ist 'Ja' gewÃ¤hlt, enthÃ¤lt die E-Mail nach
  der Registrierung auch das vergebene Passwort.
- **Kontenaktivierung durch**.
  - Keine: Der Benutzer kann sich sofort selbst registrieren.
  - Benutzer: Dem Benutzer wird per E-Mail ein Link gesendet, mit dem er
    sein Benutzerkonto freischalten kann.
  - Administrator: Dem Benutzer wird per E-Mail ein Link gesendet, mit
    dem er seine eigene E-Mail-Adresse bestÃ¤tigen kann, anschlieÃŸend
    werden alle Benutzer, die System-E-Mails erhalten dÃ¼rfen und die
    Berechtigung haben neue Benutzer anzulegen, Ã¼ber den neuen Benutzer
    informiert und gebeten, dessen Benutzerkonto freizuschalten.
- **Informationsmail an Administratoren**. Wenn 'Kontenaktivierung
  durch' auf 'Keine' oder 'Benutzer' eingestellt wurde, eine
  Informationsmail an Administratoren versenden.
- **Captcha**.
  [Captcha](https://docs.joomla.org/Help4.x:Site_Global_Configuration/de#captcha "Special:MyLanguage/Help4.x:Site Global Configuration/de")
  fÃ¼r 'Registrieren', 'Passwort vergessen' und 'Benutzername vergessen'
  verwenden.
- **Einstellungen im Frontend**.
  - Anzeigen: Benutzer kÃ¶nnen die
    [Basiseinstellungen](https://docs.joomla.org/Help4.x:Users:_Edit_Profile/de#basicssettings "Special:MyLanguage/Help4.x:Users: Edit Profile/de")
    im Frontend Ã¤ndern.
  - Verbergen: Benutzer kÃ¶nnen diese Einstellungen nicht Ã¤ndern.
  - Frontend-Sprache. Die Standard-Seitensprache.
- **Benutzername verÃ¤nderbar**. Erlaubt Benutzern, ihren Benutzernamen
  zu Ã¤ndern.

### E-Mail-Domainoptionen

<img
src="https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-email-domain-subscreen-de.png/600px-Help-4x-Users-Options-email-domain-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-email-domain-subscreen-de.png/900px-Help-4x-Users-Options-email-domain-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-email-domain-subscreen-de.png/1200px-Help-4x-Users-Options-email-domain-subscreen-de.png 2x"
data-file-width="2002" data-file-height="1073" width="600" height="322"
alt="Help-4x-Users-Options-email-domain-subscreen-de.png" />

- **Domainname**. Eine Liste der erlaubten und nicht erlaubten
  E-Mail-Domains eingeben. StandardmÃ¤ÃŸig sind alle Domains
  erlaubt.Wildcards (\*) werden unterstÃ¼tzt. Beispiele:
  - \* (Sternchen): Erlaubt oder nicht erlaubt alle Domains,
  - \*.com: Erlaubt oder nicht erlaubt alle '.com' Domains
  - \*.joomla.org: Erlaubt oder nicht erlaubt alle 'joomla.org'
    Subdomains.
- **Regel** AuswÃ¤hlen, ob die Domain erlaubt oder nicht erlaubt werden
  soll.

### Passwortoptionen

<img
src="https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-password-subscreen-de.png/600px-Help-4x-Users-Options-password-subscreen-de.png.jpeg"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-password-subscreen-de.png/900px-Help-4x-Users-Options-password-subscreen-de.png.jpeg 1.5x, https://docs.joomla.org/images/thumb/8/86/Help-4x-Users-Options-password-subscreen-de.png/1200px-Help-4x-Users-Options-password-subscreen-de.png.jpeg 2x"
data-file-width="2002" data-file-height="1257" width="600" height="377"
alt="Help-4x-Users-Options-password-subscreen-de.png" />

- **ZurÃ¼cksetzungsmaximum**. Die maximale Anzahl von
  PasswortrÃ¼cksetzungen, die im angegebenen Zeitraum erlaubt sind. Bei
  *0* gibt es keine EinschrÃ¤nkungen.
- **ZurÃ¼cksetzungsdauer (Stunden)**. Die Zeitspanne, innerhalb der die
  maximalen PasswortzurÃ¼cksetzungen erlaubt sind.
- **Minimale PasswortlÃ¤nge**. Legt die minimale LÃ¤nge eines Passworts
  fest.
- **Minimal enthaltene Ziffern**. Legt die minimale Anzahl von Ziffern
  im Passwort fest.
- **Minimal enthaltene Sonderzeichen**. Legt die minimale Anzahl von
  Sonderzeichen (wie !@#\$) im Passwort fest.
- **Minimal enthaltene GroÃŸbuchstaben**. Legt die minimale Anzahl von
  GroÃŸbuchstaben im Passwort fest.
- **Minimal enthaltene Kleinbuchstaben**. Legt die minimale Anzahl von
  Kleinbuchstaben im Passwort fest.

### Multi-Faktor-Authentifizierung

<img
src="https://docs.joomla.org/images/thumb/7/7d/Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png/600px-Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/7d/Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png/900px-Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/7/7d/Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png/1200px-Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png 2x"
data-file-width="2002" data-file-height="1518" width="600" height="455"
alt="Help-4x-Users-Options-multi-factor-authentication-subscreen-de.png" />

- **Erlaubte Site-Modulpositionen**. Auf der
  Multifaktor-Authentifizierungsseite der Website werden alle Module
  ausgeblendet, mit Ausnahme derjenigen, die sich an den hier
  ausgewÃ¤hlten Positionen befinden.
- **Titel im Frontend anzeigen**. Soll im Frontend der Titel zur
  ÃœberprÃ¼fung der Multi-Faktor-Authentifizierung gezeigt werden?
  Hinweis: Der Titel wird im Backend immer angezeigt. Wenn der Titel
  geÃ¤ndert werden soll, muss der SprachschlÃ¼ssel
  'COM_USERS_HEADING_MFA' in [Sprachen:
  Overrides](https://docs.joomla.org/Help4.x:Languages:_Overrides/de "Special:MyLanguage/Help4.x:Languages: Overrides/de")
  Ã¼berschrieben werden.
- **Erlaubte Administrator-Modulpositionen**. Auf der
  Multifaktor-Authentifizierungsseite der Administration werden alle
  Module ausgeblendet, mit Ausnahme derjenigen, die sich an den hier
  gewÃ¤hlten Positionen befinden. Bitte beachten, dass Module an der
  Position 'title' immer gezeigt werden: Dies ist notwendig, um das
  Symbol und den Titel der Administration anzuzeigen.
- **Multi-Faktor-Authentifizierung deaktivieren**. Jeder Benutzer, der
  *einer* der gewÃ¤hlten Benutzergruppen angehÃ¶rt, wird von der
  Multi-Faktor-Authentifizierung ausgenommen. Selbst wenn diese Benutzer
  bereits die Multi-Faktor-Authentifizierung eingerichtet hatten, werden
  sie nicht aufgefordert, diese bei der Anmeldung zu verwenden. Die
  Benutzer kÃ¶nnen die Multi-Faktor-Authentifizierung weder anzeigen,
  entfernen noch ihre Konfiguration Ã¤ndern.
- **Multi-Faktor-Authentifizierung erzwingen**. Jeder Benutzer, der
  *einer* der gewÃ¤hlten Benutzergruppen angehÃ¶rt, muss die
  Multi-Faktor-Authentifizierung aktivieren, bevor er die Website nutzen
  kann.
- **Site Template Stil**. Der Template-Stil fÃ¼r das Frontend, der auf
  der Seite der Multi-Faktor-Authentifizierung verwendet werden soll.
  Die Option "Standard verwenden" ermÃ¶glicht die Verwendung des
  Standard-Templates der Website.
- **Multi-Faktor-Authentifizierung nach stiller Anmeldung**. Soll der
  Benutzer nach einer stillen Anmeldung die
  Multi-Faktor-Authentifizierung durchlaufen mÃ¼ssen? Stille Anmeldungen
  sind Anmeldungen, die keinen Benutzernamen und kein Kennwort
  erfordern, zum Beispiel die Funktion 'Angemeldet bleiben', WebAuthn
  usw.
- **Antworttypen der unbeaufsichtigten (silent) Anmeldeauthentifizierung
  (fÃ¼r Experten)**. Eine durch Kommas getrennte Liste von
  Joomla-Authentifizierungsantworttypen, die als stille Anmeldungen
  gelten. Die Standardeinstellung ist 'cookie' (Funktion 'Angemeldet
  bleiben') und 'passwordless' (WebAuthn).
- **Einbindung neuer Benutzer**. Wenn der Benutzer die
  Multi-Faktor-Authentifizierung noch nicht eingerichtet hat und diese
  Option aktiviert ist, wird er zur Einrichtungsseite der
  Multi-Faktor-Authentifizierung oder zur unten eingerichteten URL
  weitergeleitet. Auf diese Weise kann den Nutzern auf einfache Weise
  mitgeteilt werden, dass die Multi-Faktor-Authentifizierung eine Option
  auf dieser Website ist.
- **Benutzerdefinierte Weiterleitungs-URL**. Wenn das Feld nicht leer
  ist, wird auf diese URL umgeleitet anstatt auf die Seite zur
  Einrichtung der Multi-Faktor-Authentifizierung, falls die Option oben
  aktiviert ist.Warnung!: Dies muss eine URL innerhalb der Website sein.
  Eine Anmeldung Ã¼ber einen externen Link oder in einer anderen
  Subdomain ist nicht mÃ¶glich.

### Verlauf Benutzerhinweise

<img
src="https://docs.joomla.org/images/thumb/c/c3/Help-4x-Users-Options-user-notes-history-subscreen-de.png/600px-Help-4x-Users-Options-user-notes-history-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/c3/Help-4x-Users-Options-user-notes-history-subscreen-de.png/900px-Help-4x-Users-Options-user-notes-history-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/c/c3/Help-4x-Users-Options-user-notes-history-subscreen-de.png/1200px-Help-4x-Users-Options-user-notes-history-subscreen-de.png 2x"
data-file-width="2002" data-file-height="565" width="600" height="169"
alt="Help-4x-Users-Options-user-notes-history-subscreen-de.png" />

- **Versionen speichern**. Versionen fÃ¼r Benutzerhinweise speichern.
- **Anzahl Versionen**. Maximale Anzahl der zu speichernden Versionen
  eines Benutzerhinweises. Wird ein Benutzerhinweise gespeichert und die
  maximale Anzahl der Versionen ist erreicht, wird die Ã¤lteste Version
  automatisch gelÃ¶scht. Wird '0' eingetragen, werden die alten
  Versionen nicht gelÃ¶scht. [Mehr
  erfahren.](https://docs.joomla.org/Help4.x:Components_Version_History/de "Special:MyLanguage/Help4.x:Components Version History/de")

### Serienmail-Benutzer

<img
src="https://docs.joomla.org/images/thumb/9/9e/Help-4x-Users-Options-mass-mail-users-subscreen-de.png/600px-Help-4x-Users-Options-mass-mail-users-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/9/9e/Help-4x-Users-Options-mass-mail-users-subscreen-de.png/900px-Help-4x-Users-Options-mass-mail-users-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/9/9e/Help-4x-Users-Options-mass-mail-users-subscreen-de.png/1200px-Help-4x-Users-Options-mass-mail-users-subscreen-de.png 2x"
data-file-width="2002" data-file-height="879" width="600" height="263"
alt="Help-4x-Users-Options-mass-mail-users-subscreen-de.png" />

- **BetreffprÃ¤fix**. Dieser optionale PrÃ¤fix wird vor jedem
  E-Mail-Betreff eingefÃ¼gt.
- **Signatur**. Optionaler Text, der automatisch hinter dem Hauptteil
  der E-Mail eingefÃ¼gt wird (z.B. eine Signatur).

### Integration

<img
src="https://docs.joomla.org/images/thumb/e/e9/Help-4x-Users-Options-integration-subscreen-de.png/600px-Help-4x-Users-Options-integration-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/e9/Help-4x-Users-Options-integration-subscreen-de.png/900px-Help-4x-Users-Options-integration-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/e/e9/Help-4x-Users-Options-integration-subscreen-de.png/1200px-Help-4x-Users-Options-integration-subscreen-de.png 2x"
data-file-width="2002" data-file-height="593" width="600" height="178"
alt="Help-4x-Users-Options-integration-subscreen-de.png" />

- **Eigene Felder aktivieren**. Erstellen eigener Felder aktivieren.

### Berechtigungen

In diesem Teil werden die Standardwerte der
[Zugriffskontrollliste](https://docs.joomla.org/Access_Control_List/de "Special:MyLanguage/Access Control List/de")
fÃ¼r alle Benutzer eingestellt.

<img
src="https://docs.joomla.org/images/thumb/3/32/Help-4x-Users-Options-permissions-subscreen-de.png/600px-Help-4x-Users-Options-permissions-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/3/32/Help-4x-Users-Options-permissions-subscreen-de.png/900px-Help-4x-Users-Options-permissions-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/3/32/Help-4x-Users-Options-permissions-subscreen-de.png/1200px-Help-4x-Users-Options-permissions-subscreen-de.png 2x"
data-file-width="2002" data-file-height="1510" width="600" height="453"
alt="Help-4x-Users-Options-permissions-subscreen-de.png" />

Um Berechtigungen fÃ¼r Benutzer zu Ã¤ndern:

1.  Die **Gruppe** durch Anklicken des Namens auf der linken Seite
    auswÃ¤hlen.
2.  Die gewÃ¼nschte **Aktion** aussuchen.
    - **ACL & Optionen konfigurieren**. Benutzer kÃ¶nnen Optionen und
      Berechtigungen bearbeiten.
    - **Nur Optionen konfigurieren**. Benutzer kÃ¶nnen Optionen
      ausgenommen der Berechtigungen bearbeiten.
    - **Administrationszugriff**. Benutzer haben Zugriff auf die
      Administration.
    - **Erstellen**. Benutzer kÃ¶nnen Benutzer erstellen.
    - **LÃ¶schen**. Benutzer kÃ¶nnen Benutzer lÃ¶schen.
    - **Bearbeiten**. Benutzer kÃ¶nnen Benutzer bearbeiten.
    - **Status bearbeiten**. Benutzer kÃ¶nnen den Status und verwandte
      Informationen bearbeiten.
    - **Inhalt von eigenen Feldern bearbeiten**. Benutzer kÃ¶nnen eigene
      Felder in Benutzern bearbeiten.
3.  Die Berechtigungen der gewÃ¤hlten Aktion wÃ¤hlen.
    - **Vererbt**. FÃ¼r Benutzer dieser Gruppe von der
      [Konfiguration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/de#permissions "Special:MyLanguage/Help4.x:Site Global Configuration/de")
      vererbt .
    - **Erlaubt**. FÃ¼r Benutzer dieser Gruppe erlaubt.Hinweis: Wenn die
      Aktion auf einer hÃ¶heren Ebene 'Verweigert' wird, ist die
      'Erlaubt'-Berechtigung hier dadurch Ã¼berschrieben. Eine
      'Verweigert'-Einstellung kann nicht Ã¼berschrieben werden.
    - **Verweigert**. Verweigert fÃ¼r Benutzer dieser Gruppe.
4.  Auf **Speichern** in der **Werkzeugleiste** oben klicken. Danach
    aktualisiert sich die Anzeige, erst dann werden die errechneten
    Einstellungen angezeigt.

## Werkzeugleiste

Das [Bildschirmfoto](#screenshot) zeigt die Werkzeugleiste im oberen
Bereich.

- **Speichern**. Speichert die Benutzer-Optionen und bleibt auf der
  aktuellen Seite.
- **Speichern & SchlieÃŸen**. Speichert die Benutzer-Optionen und
  schlieÃŸt die aktuelle Seite.
- **SchlieÃŸen**. SchlieÃŸt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Ã„nderungen zurÃ¼ck.
- **Inline-Hilfe umschalten**. Hilfetext unter einigen Optionen ein-
  oder ausschalten.
- **Hilfe**. Ã–ffnet die Hilfeseite.

## Tipps

Unerfahrene Benutzer sollten die Standard-Werte belassen, bis sie mehr
Ã¼ber die Verwendung Globaler Einstellungen wissen.

## Verwandte Informationen

|                                                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Verwandte Hilfeseiten                                                                                                                                                          | Beschreibung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| <span class="mw-selflink selflink">Benutzer: Optionen</span>                                                                                                                   | Benutzer Optionen setzen Parameter, die global fÃ¼r alle Benutzer verwendet werden. Sie ermÃ¶glichen die Kontrolle Ã¼ber die Verwendung von Captcha, Benutzerregistrierung gestattet oder nicht, die Art der Registrierung, die Standard-Gruppe fÃ¼r neue Benutzer, Passwort zurÃ¼cksetzen oder des ZÃ¤hlers der Benutzernamen und eine Informations-E-Mail an Administratoren bei neuen Benutzerregistrierungen.                                                                                                                                                                                                                                                                                                                                                                         |
| [Benutzer](https://docs.joomla.org/Help4.x:Users/de "Help4.x:Users/de")                                                                                                        | Die Benutzerliste wird verwendet, um Benutzer zu finden, hinzuzufÃ¼gen und zu bearbeiten.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [Benutzer: Zugriffsebenen anzeigen](https://docs.joomla.org/Help4.x:Users:_Viewing_Access_Levels/de "Help4.x:Users: Viewing Access Levels/de")                                 | Hier hat man die MÃ¶glichkeit, eine Liste der Zugriffsebenen anzusehen und sie auf unterschiedliche Weise zu sortieren, ebenso wie das Bearbeiten und Erstellen von Zugriffsebenen.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| [Benutzer: Zugriffsebenen anzeigen und bearbeiten](https://docs.joomla.org/Help4.x:Users:_Edit_Viewing_Access_Level/de "Help4.x:Users: Edit Viewing Access Level/de")          | Zugriffsebenen kontrollieren, welche Objekte der Seite welcher Benutzer sieht. Objekte sind etwa MenÃ¼-Elemente, Module, Kategorien und Komponenten-Elemente (BeitrÃ¤ge, Kontakte, usw.). Jedes Objekt der Seite ist einer Zugriffsebene zugeordnet. Benutzergruppen sind ebenfalls einer Zugriffsebene zugeordnet.Ist ein Benutzer Mitglied einer Gruppe, die der Zugriffsebene zugeordnet ist, sieht der Benutzer jedes Objekt der Zugriffsebene. Es ist hilfreich zu verstehen, dass Benutzergruppen hierarchisch in Unter-Gruppen angeordnet werden kÃ¶nnen. Dann hat eine Unter-Gruppe Zugriff auf alle Zugriffsebenen der Ã¼bergeordneten Benutzergruppen. Damit mÃ¼ssen einer Unter-Gruppe keine Zugriffsebene zugeordnet werden, die die Ã¼bergeordnete Benutzergruppe schon hat. |
| [Berechtigungen fÃ¼r Gruppen](https://docs.joomla.org/Help4.x:Permissions_for_Group/de "Help4.x:Permissions for Group/de")                                                     | Der erweiterte Berechtigungsbericht bildet die exakten Berechtigungen jeder Gruppe Ã¼ber alle Erweiterungen der Joomla! Installation hinweg ab.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| [Berechtigungen fÃ¼r Benutzer](https://docs.joomla.org/Help4.x:Permissions_for_User/de "Help4.x:Permissions for User/de")                                                      | Der Debug-Bericht Ã¼ber die Berechtigungen ermÃ¶glicht es, die genauen Berechtigungen fÃ¼r einen bestimmten Benutzer Ã¼ber alle Erweiterungen der Joomla! Installation hinweg abzubilden.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [Benutzer: Gruppen](https://docs.joomla.org/Help4.x:Users:_Groups/de "Help4.x:Users: Groups/de")                                                                               | Benutzergruppen steuern, welche Aktionen ein Benutzer auf der Website durchfÃ¼hren darf und welche Objekte ein Benutzer sehen kann. Ãœber diese OberflÃ¤che kann man Benutzergruppen erstellen, ansehen, bearbeiten und lÃ¶schen.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| [Benutzer: Gruppe neu erstellen oder bearbeiten](https://docs.joomla.org/Help4.x:Users:_New_or_Edit_Group/de "Help4.x:Users: New or Edit Group/de")                            | Benutzergruppen spielen eine zentrale Rolle, was ein Benutzer der Seite sehen oder machen darf. Benutzergruppen erstellen ist Ã¼blicherweise der erste Schritt, das Sicherheitssystem der Seite einzurichten.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [Serien-Mail an Benutzer](https://docs.joomla.org/Help4.x:Mass_Mail_Users/de "Help4.x:Mass Mail Users/de")                                                                     | Die Serien-Mail-Funktion erlaubt Mitgliedern der "Super Benutzer"-Gruppe, E-Mails an registrierte Benutzer der Seite zu senden. Benutzer kÃ¶nnen, basierend auf ihrer Gruppe, ausgewÃ¤hlt werden.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| [Benutzer: Profil bearbeiten](https://docs.joomla.org/Help4.x:Users:_Edit_Profile/de "Help4.x:Users: Edit Profile/de")                                                         | Auf dieser Seite kann man einen neuen Benutzer anlegen (auf den "Neu"-Button bei "Benutzer" klicken) oder einen bestehenden Benutzer bearbeiten (einen Benutzer auswÃ¤hlen und auf den "Bearbeiten"-Button klicken oder auf den Namen des Benutzers klicken).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [Benutzerhinweise: Kategorien](https://docs.joomla.org/Help4.x:User_Notes:_Categories/de "Help4.x:User Notes: Categories/de")                                                  | Auf dieser Seite kann eine Liste der Kategorien der Benutzerhinweise angezeigt und auf verschiedene Weise sortiert werden. So kann man auch Benutzerhinweis-Kategorien und Zugriffsebenen bearbeiten und anlegen.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| [Benutzerhinweise: Kategorie neu erstellen oder bearbeiten](https://docs.joomla.org/Help4.x:User_Notes:_New_or_Edit_Category/de "Help4.x:User Notes: New or Edit Category/de") | Hier kann eine neue Kategorie erstellt oder eine bestehende Kategorie bearbeitet werden. Kategorien werden zum Organisieren der Benutzerhinweise verwendet. Kategorien erlauben das Anzeigen zusammengehÃ¶render Benutzerhinweise auf einer Seite und das Filtern von Benutzerhinweisen. Alle Benutzerhinweise werden selbst erstellten Kategorien oder der speziellen Kategorie 'Unkategorisiert' zugewiesen.                                                                                                                                                                                                                                                                                                                                                                            |
| [Benutzerhinweise](https://docs.joomla.org/Help4.x:User_Notes/de "Help4.x:User Notes/de")                                                                                      | Benutzerhinweise sind Informationen, die einem registrierten Benutzer der Joomla!-Site zugewiesen werden kÃ¶nnen. Diese Hinweise kÃ¶nnen zum Beispiel Kommentare Ã¼ber â€žbeleidigendeâ€œ oder â€žschwierigeâ€œ, Benutzer usw. enthalten.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [Benutzerhinweise: neu erstellen oder bearbeiten](https://docs.joomla.org/Help4.x:User_Notes:_New_or_Edit/de "Help4.x:User Notes: New or Edit/de")                             | Auf dieser Seite kÃ¶nnen Benutzer-Hinweise erstellt oder bearbeitet werden. Der â€žEditorâ€œ fÃ¼r die Hinweise ist der gewÃ¤hlte globale Editor. Beispiele: TinyMCE, JCE, CodeMirror.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [MenÃ¼eintrag: Passwort zurÃ¼cksetzen](https://docs.joomla.org/Help4.x:Menu_Item:_Password_Reset/de "Help4.x:Menu Item: Password Reset/de")                                    | Dient zum Erstellen eines Formulars, mit dem ein Benutzer sein Passwort zurÃ¼cksetzen kann. Dazu wird eine E-Mail an die mit dem Konto verbundene E-Mail-Adresse des Benutzers gesendet.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| [MenÃ¼eintrag: Benutzerprofil](https://docs.joomla.org/Help4.x:Menu_Item:_User_Profile/de "Help4.x:Menu Item: User Profile/de")                                                | Dient zur Erstellung eines Formulars, mit dem ein Benutzer seine Profileinstellungen bearbeiten kann.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [MenÃ¼eintrag: Benutzerprofil bearbeiten](https://docs.joomla.org/Help4.x:Menu_Item:_Edit_User_Profile/de "Help4.x:Menu Item: Edit User Profile/de")                           | Zeigt ein Formular, damit Benutzer ihr Profil bearbeiten kÃ¶nnen.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| [MenÃ¼eintrag: Registrierungsformular](https://docs.joomla.org/Help4.x:Menu_Item:_Registration_Form/de "Help4.x:Menu Item: Registration Form/de")                              | Zeigt ein Registrierungsformular, damit sich Benutzer an der Website registrieren kÃ¶nnen. Das Standardformular enthÃ¤lt grundsÃ¤tzliche Informationen: Name, Benutzername, Passwort und die E-Mail-Adresse.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| [MenÃ¼eintrag: Benutzername erneut zusenden](https://docs.joomla.org/Help4.x:Menu_Item:_Username_Reminder_Request/de "Help4.x:Menu Item: Username Reminder Request/de")        | Wird verwendet, um ein Formular zu erstellen, das es einem Benutzer ermÃ¶glicht, eine E-Mail mit seinem Benutzernamen anzufordern.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
