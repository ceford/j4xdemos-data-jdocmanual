<!-- Filename: Help4.x:Menus / Display title: Menüs -->

## Beschreibung

Menüs ermöglichen es dem Benutzer, auf der Website zu navigieren. Ein
Menü ist ein Objekt, das einen oder mehrere Menüeinträge enthält. Jeder
Menüeintrag verweist auf eine logische Seite auf der Website. Ein
Menümodul ist erforderlich, um das Menü auf der Seite zu platzieren. Ein
Menü kann mehr als ein Modul aufweisen. Ein Modul kann beispielsweise
nur die Menüpunkte der ersten Ebene anzeigen und ein zweites Modul kann
die Menüpunkte der Ebene 2 anzeigen.

Die Menüliste bietet einen Überblick über die auf einer Joomla-Seite
verfügbaren Menüs. Dazu gehören die Angaben über die Anzahl der
veröffentlichten, versteckten und gelöschten Einträge jedes einzelnen
Menüs sowie die Namen der verknüpften Module.

Der normale Ablauf zum Einrichten eines Menüs auf der Website ist wie
folgt:

1.  Ein neues Menü erstellen (diese Seite).
2.  Ein oder mehrere Menüeinträge in diesem Menü erstellen. Jeder
    Menüeintrag hat einen speziellen Menüeintragtyp.
3.  Erstellen von einem oder mehreren Menü-Modulen, um das Menü auf der
    Website anzuzeigen. In den Modulen wird eingestellt, welche
    Menüeinträge das Modul zeigen soll.

## Wie darauf zugreifen

- Im Administrator-Menü **Menüs **→** Verwalten** auswählen.

## Bildschirmfoto

<img
src="https://docs.joomla.org/images/thumb/a/a0/Help-4x-menus-menu-manager-menus-de.png/800px-Help-4x-menus-menu-manager-menus-de.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/a0/Help-4x-menus-menu-manager-menus-de.png/1200px-Help-4x-menus-menu-manager-menus-de.png 1.5x, https://docs.joomla.org/images/thumb/a/a0/Help-4x-menus-menu-manager-menus-de.png/1600px-Help-4x-menus-menu-manager-menus-de.png 2x"
data-file-width="1630" data-file-height="1105" width="800" height="542"
alt="Help-4x-menus-menu-manager-menus-de.png" />

## Spalten-Überschriften

Ein Klick auf den Titel einer Spalte sortiert die Tabellenansicht nach
dieser Spalte. Ein Abwärts-Pfeil neben dem Spaltentitel bedeutet
absteigende Sortierung während ein Aufwärts-Pfeil aufsteigende
Sortierung bedeutet. Als Standard wird nach der **ID**-Nummer
aufsteigend sortiert.

- **Checkbox**. Dieses Kästchen markieren, um einen oder mehrere
  Einträge auszuwählen. Um alle Einträge auszuwählen, das Kästchen im
  Spaltenkopf markieren. Nachdem ein oder mehrere Kästchen markiert
  sind, auf eine Schaltfläche in der Werkzeugleiste klicken, um eine
  Aktion für den ausgewählten Eintrag oder die ausgewählten Einträge
  durchzuführen. Viele Aktionen, wie z.B. Veröffentlichen und
  Verstecken, können mit mehreren Einträgen arbeiten. Andere, wie z.B.
  Bearbeiten, funktionieren gleichzeitig jeweils nur mit einem Eintrag.
  Wenn mehrere Einträge markiert sind und Sie auf „Bearbeiten“ drücken,
  wird der erste der markierten Einträge zur Bearbeitung geöffnet.
- **Titel**. Der Name des Menüs.
- **\# Veröffentlicht.** Anzahl der veröffentlichten Menüeinträge des
  Menüs
- **\# Versteckt.** Anzahl der versteckten Menüeinträge des Menüs
- **\# Im Papierkorb**. Anzahl der Menüeinträge des Menüs im Papierkorb.
- **Zugeordnete Module**. Zeigt jedes Menü-Modul, das dem Menü
  zugeordnet ist. Die Spalte zeigt den Namen des Moduls, seine
  Zugriffsebene und Position im Template.
- **ID**. Einmalig vergebene Identifikations-Nummer für den Eintrag. Sie
  wird von Joomla automatisch vergeben und dient zur internen
  Identifikation des Eintrages. Man kann die Nummer nicht ändern. Beim
  Neu-Erstellen eines Eintrags zeigt das Feld "0" an, bis man speichert,
  dabei wird dann die neue ID vergeben.

## Werkzeugleiste

Das [Bildschirmfoto](#Bildschirmfoto) am Anfang der Seite zeigt die
Werkzeugleiste im oberen Bereich. Die Funktionen sind:

- **Neu**: Öffnet das Bearbeitungs-Formular, um menu zu erstellen.
- **Bearbeiten:** Öffnet das Bearbeitungs-Formular für das ausgewählte
  menu. Falls mehr als ein menu ausgewählt wurde (wo anwendbar), wird
  nur das erste menu geöffnet. Das Bearbeitungs-Formular kann auch durch
  Klicken auf den menu-Namen geöffnet werden.
- **Löschen:** Löscht markierte menus. Funktioniert mit einem oder
  mehreren ausgewählten menus. Das Löschen eines Menüs löscht auch alle
  seine Menüeinträge und seine zugeordneten Module. Nach Klick auf
  "Löschen" wird man um Bestätigung der Löschung der gewählten Menüs
  gefragt. Ein Klick auf "OK" löscht die Menüs. Ein Klick auf
  "Abbrechen" unterbricht die Löschung.
- **Wiederherstellen.** Rekonstruiert und aktualisiert die menu-Tabelle.
  Üblicherweise muß diese Tabelle *nicht* wiederhergestellt werden. Die
  Funktion ist für den Fall einer beschädigten Tabelle gedacht.
- **Optionen.** Öffnet das Optionen-Fenster, in dem Einstellungen, wie
  die Standard-Parameter, bearbeitet werden können. Siehe auch [Menus
  Configuration](https://docs.joomla.org/Help4.x:Components_Menus_Configuration "Special:MyLanguage/Help4.x:Components Menus Configuration").
- **Hilfe**. Öffnet die Hilfeseite.

## Tipps

- Es ist ratsam, neuen Menüs einen aussagekräftigen Titel zu geben, da
  sie später im Menü *Administrator-Menüs* angezeigt werden. Es ist
  sinnvoll, das Feld *Beschreibung* mit Informationen über das Menü zu
  füllen. Ein kurzer Name im Feld *Modultitel* hilft, das Modul des
  Menüs im Modul-Manager mit diesem Titel zu identifizieren.
- Man kann zwar eine Kopie eines ausgewählten Menüs erstellen, indem man
  auf die Schaltfläche *Kopieren* in der Symbolleiste klickt, allerdings
  kann man auch eine weitere Instanz im Modulmanager erstellen.
- In neu angelegten Menüs sollte im Feld *Titel* der Name eindeutig sein
  und nur englische alphanumerische Zeichen ohne Leerzeichen verwendet
  werden. Es ist sinnvoll, nur die Zeichen a-z, 0-9 und den Unterstrich
  (\_) zu benutzen.
- Wird kein "Modul-Titel" eingegeben, kann das Modul nicht gespeichert
  und das Menü im Frontend nicht angezeigt werden. Allerdings kann
  später in der Modul-Verwaltung ein neues Menü-Modul erstellt und dem
  Menü zugeordnet werden.
- Wird ein existierendes Menü gelöscht, werden auch alle Menü-Elemente
  des Menüs gelöscht.
- Das Hauptmenü enthält das Standard-Menü, daher sollte es **nicht
  gelöscht** werden. Das Standard-Menü-Element definiert die Seite, die
  nach Aufruf von *www.meineseite.de* angezeigt wird. Die Site wird ohne
  das Standard-Menü-Element nicht funktionieren. Normalerweise ist dies
  der Menüpunkt „Home“, aber es kann jeder beliebige Menüpunkt
  eingestellt werden, einschließlich eines Menüpunkts in einem
  verborgenen Menü. Wird das Standard-Menü-Element gewechselt, sollte es
  genauso wenig gelöscht werden! Das Menü mit dem Standardmenüeintrag
  ist im Menü *Menüs* mit einem Sternchen (\*) gekennzeichnet.

## Verwandte Informationen

- Neue Menüs hinzufügen: [Menüs:
  Neu/Bearbeiten](https://docs.joomla.org/Help4.x:Menus:_Edit/de "Help4.x:Menus: Edit/de")
- Zum Einrichten von Berechtigungen für Aktionen in Menüs: [Menüs:
  Optionen](https://docs.joomla.org/Help4.x:Menus:_Options/de "Help4.x:Menus: Options/de")
- Menüeinträge neu/bearbeiten: [Menüs:
  Menü-Einträge](https://docs.joomla.org/Help4.x:Menus:_Items/de "Help4.x:Menus: Items/de")
- Zum Hinzufügen oder Bearbeiten von Menü-Modulen: [Neuer
  Menü-Eintrag](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/de "Help4.x:Menu Item: New Item/de")
