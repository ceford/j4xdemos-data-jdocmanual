<!-- Filename: Help4.x:Media:_Options / Display title: Medien: Optionen -->

## Beschreibung

Die Optionen stellen Parameter ein, die global für Medien verwendet
werden. Sie steuern die zum Hochladen zugelassenen Dateitypen,
MIME-Typ-Prüfung, MIME-Typ-Blacklisting und weitere Optionen.

## Wie darauf zugreifen

**Inhalt **→** Medien**

- auf den Button **Optionen** der Werkzeugleiste klicken.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/3/35/Help-4x-Media-Options-screen-de.png/800px-Help-4x-Media-Options-screen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/3/35/Help-4x-Media-Options-screen-de.png/1200px-Help-4x-Media-Options-screen-de.png 1.5x, https://docs.joomla.org/images/thumb/3/35/Help-4x-Media-Options-screen-de.png/1600px-Help-4x-Media-Options-screen-de.png 2x"
data-file-width="2720" data-file-height="1700" width="800" height="500"
alt="Help-4x-Media-Options-screen-de.png" />

## Formular Felder

### Medien

- **Maximale Größe (in MB)**. Auf "0" setzen für unbegrenzt. Hinweis:
  Die Größe wird durch eingestellte Limits des Servers begrenzt.
- **Pfad zum Dateiverzeichnis**. Den Pfad zum Dateiverzeichnis, relativ
  zum Stammverzeichnis von Joomla, eingeben.Die Wahl eines anderen
  Pfades als des Standards 'images' kann Links ungültig machen. Der Pfad
  darf nicht mit einem Schrägstrich beginnen.
- **Pfad zum Bildverzeichnis**. Den Pfad zum Bildverzeichnis, relativ
  zum Stammverzeichnis von Joomla, eingeben.Der Pfad muß derselbe wie
  der 'Pfad zum Dateiverzeichnis' oder eines seiner Unterverzeichnisse
  sein. Der Pfad darf nicht mit einem Schrägstrich beginnen.
- **Eingeschränktes Hochladen**. Hier kann das Hochladen für
  Benutzerebenen niedriger als 'Manager' eingestellt werden, wenn
  Dateieigenschaften ('Fileinfo') oder 'MIME Magic' nicht installiert
  sind.
  - **Zulässige Erweiterungen**. Hier kann das Hochladen für
    Benutzerebenen niedriger als 'Manager' eingeschränkt werden. Gilt
    für Dateien in der Liste.
  - **Dateityp überprüfen**. Um die Dateitypen zu überprüfen, kann die
    Dateieigenschaften ('Fileinfo') oder 'MIME Magic' genutzt werden.
    Bei anhaltenden Fehlermeldungen kann probiert werden, diese Option
    zu deaktivieren.
- **Gültige Bilddateiendungen (Dateitypen)**. Bilddateiendungen
  (Dateitypen), die zum Hochladen zugelassen sind (Komma separiert).
  Diese werden auf gültige Bild-Header geprüft und zur Auswahl von
  Bildern mit dem
  [Medienformularfeld](https://docs.joomla.org/Media_form_field_type "Special:MyLanguage/Media form field type")
  verwendet.
- **Gültige Audioerweiterungen (Dateitypen)**. Audioerweiterungen
  (Dateitypen), die zum Hochladen zugelassen sind (durch Komma
  getrennt). Diese werden auf gültige Audio-Header geprüft und zur
  Auswahl von Audiodateien mit dem
  [Medienformularfeld](https://docs.joomla.org/Media_form_field_type "Special:MyLanguage/Media form field type")
  verwendet.
- **Gültige Videoerweiterungen (Dateitypen)**. Videoerweiterungen
  (Dateitypen), die zum Hochladen zugelassen sind (durch Komma
  getrennt). Diese werden auf gültige Video-Header geprüft und zur
  Auswahl von Videodateien mit dem
  [Medienformularfeld](https://docs.joomla.org/Media_form_field_type "Special:MyLanguage/Media form field type")
  verwendet.
- **Gültige Dokumenterweiterungen (Dateitypen)**. Dokumenterweiterungen
  (Dateitypen), die zum Hochladen zugelassen sind (durch Komma
  getrennt). Diese werden auf gültige Dokument-Header geprüft und zur
  Auswahl von Dokumentdateien mit dem
  [Medienformularfeld](https://docs.joomla.org/Media_form_field_type "Special:MyLanguage/Media form field type")
  verwendet.
- **Ignorierte Dateiendungen**. Eine Komma separierte Liste von
  Dateitypen zum Hochladen.
- **Gültige Dateitypen.** Eine Komma separierte Liste von Dateitypen zum
  Hochladen.

### Berechtigungen

In diesem Teil werden die Standardwerte der
[Zugriffskontrollliste](https://docs.joomla.org/Access_Control_List/de "Access Control List/de")
für alle Medien eingestellt.

<img
src="https://docs.joomla.org/images/thumb/9/9d/Help-4x-Media-Options-permissions-subscreen-de.png/600px-Help-4x-Media-Options-permissions-subscreen-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/9/9d/Help-4x-Media-Options-permissions-subscreen-de.png/900px-Help-4x-Media-Options-permissions-subscreen-de.png 1.5x, https://docs.joomla.org/images/thumb/9/9d/Help-4x-Media-Options-permissions-subscreen-de.png/1200px-Help-4x-Media-Options-permissions-subscreen-de.png 2x"
data-file-width="2002" data-file-height="1349" width="600" height="404"
alt="Help-4x-Media-Options-permissions-subscreen-de.png" />

Um Berechtigungen für Medien zu ändern:

1.  Die **Gruppe** durch Anklicken des Namens auf der linken Seite
    auswählen.
2.  Die gewünschte **Aktion** aussuchen.
    - **ACL & Optionen konfigurieren**. Benutzern können Optionen und
      Berechtigungen bearbeiten.
    - **Nur Optionen konfigurieren**. Benutzer können Optionen
      ausgenommen der Berechtigungen bearbeiten.
    - **Administrationszugriff**. Benutzer haben Zugriff auf die
      Administration.
    - **Erstellen**. Benutzer können Beiträge und Kategorien erstellen.
    - **Löschen**. Benutzer können Medien löschen.
    - **Bearbeiten**. Benutzer können Medien bearbeiten.
3.  Die Berechtigungen der gewählten Aktion wählen.
    - **Vererbt**. Für Benutzer dieser Gruppe von der
      [Konfiguration](https://docs.joomla.org/Help4.x:Site_Global_Configuration/de#permissions "Help4.x:Site Global Configuration/de")
      vererbt .
    - **Erlaubt**. Für Benutzer dieser Gruppe erlaubt. Hinweis: Wenn die
      Aktion auf einer höheren Ebene 'Verweigert' wird, ist die
      'Erlaubt'-Berechtigung hier dadurch überschrieben. Eine
      'Verweigert'-Einstellung kann nicht überschrieben werden.
    - **Verweigert**. Für Benutzer dieser Gruppe verweigert .
4.  Auf **Speichern** in der **Werkzeugleiste** oben klicken. Danach
    aktualisiert sich die Anzeige, erst dann werden die errechneten
    Einstellungen angezeigt.

## Werkzeugleiste

Das [Bildschirmfoto](#screenshot) zeigt die Werkzeugleiste im oberen
Bereich.

- **Speichern**. Speichert die Medien-Optionen und bleibt auf der
  aktuellen Seite.
- **Speichern & Schließen**. Speichert die Medien-Optionen und schließt
  die aktuelle Seite.
- **Schließen**. Schließt die aktuelle Seite und kehrt zur vorherigen
  Seite ohne Speichern der Änderungen zurück.
- **Inline-Hilfe umschalten**. Hilfetext unter einigen Optionen ein-
  oder ausschalten.
- **Hilfe**. Öffnet die Hilfeseite.

## Tipps

- Unerfahrene Benutzer sollten die Standard-Werte belassen, bis sie mehr
  über die Verwendung Globaler Einstellungen wissen.
- Erfahrene Benutzer können mit geeigneten Standard-Werten Zeit sparen.

## Verwandte Informationen

- Verwandte Hilfeseite:
  [Medien](https://docs.joomla.org/Help4.x:Media/de "Help4.x:Media/de").
- Tutorial: [Medien
  verwalten](https://docs.joomla.org/J4.x:Managing_Media/de "J4.x:Managing Media/de").
