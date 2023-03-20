<!-- Filename: Help4.x:Menu_Item:_Iframe_Wrapper / Display title: Menu-item: Iframe wrapper -->

## Beschrijving

De 'Iframe wrapper' wordt gebruikt om een pagina aan te maken met
opgenomen inhoudvia een
<a href="https://en.wikipedia.org/wiki/HTML_element#Frames"
class="extiw" title="wikipedia:HTML element">IFrame</a> met controle
over de iframe grootte, breedte en hoogte.

## Hoe toegang te krijgen

Om een nieuw 'Iframe wrapper' menu-item aan te maken:

- Selecteer **Menu's **→** \[naam van het menu\]** uit het drop-down
  menu in de back-end van uw Joomla! installatie (bijvoorbeeld
  **Menu's **→** Hoofdmenu**).
- Klik op de knop Nieuw in de werkbalk om een nieuw menu-item te maken.
- Klik op de Menu-itemtype selectie knop <img
  src="https://docs.joomla.org/images/8/8f/Help-4x-Menu-Item-Type-Select-Button-nl.png"
  decoding="async" data-file-width="124" data-file-height="43" width="124"
  height="43" alt="Help-4x-Menu-Item-Type-Select-Button-nl.png" /> en
  klik vervolgens op de 'Iframe wrapper' menu-item link onder Wrapper.

Om een bestaand 'Iframe wrapper' menu-item te bewerken, klikt u op de
titel in [Menubeheer:
Menu-items](https://docs.joomla.org/Help4.x:Menus:_Items/nl "Help4.x:Menus: Items/nl").

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/1/14/Help-4x-Menus-Menu-Item-Wrapper-nl.png/800px-Help-4x-Menus-Menu-Item-Wrapper-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/1/14/Help-4x-Menus-Menu-Item-Wrapper-nl.png 1.5x"
data-file-width="980" data-file-height="886" width="800" height="723"
alt="Help-4x-Menus-Menu-Item-Wrapper-nl.png" />

## Formulier velden

- **Titel**. De titel die wordt getoond voor dit menu item.
- **Alias**. De interne naam van het item. Normaliter, kunt u dit leeg
  laten en Joomla zal de standaardwaarde invullen. De standaard waarde
  is de titel of naam in kleine letters en streepjes in plaats van
  spaties. [Meer
  leren.](https://docs.joomla.org/Alias/nl "Special:MyLanguage/Alias/nl")

### Details tabblad

**Linker venster**

- **Menu-itemtype**. Het menu-item type dat geselecteerd is toen het
  mneu-item aangemaakt werd. Dit kan een van de core menu-item types
  zijn of een menu-item type geleverd door een geïnstalleerde extensie.
- **URL**. Veld om een URL in te vullen (website adres).

In het algemeen is het een goed idee altijd http:// of https:// toe te
voegen bij het opgeven van een URL. Er is een [Automatisch
toevoegen](https://docs.joomla.org/Help4.x:Menu_Item:_Iframe_Wrapper/nl#Geavanceerd_tabblad "Help4.x:Menu Item: Iframe Wrapper/nl")
functie om een URL te laten voorafgaan met http:// tenzij hij het
voorvoegsel in de URL ziet. *Let op - Gebruik het relatieve pad naar een
website adres in de Joomla installatie. als uw Joomla! website
`http://www.example.com` is, gebruik dan ` /html_docs/example.html`
zonder `http://www.example.com` en zorg dat de 'Automatisch toevoegen'
functie uitgeschakeld is.*

- **Link**. De door het systeem gegenereerde link voor dit menu-item.
  Dit veld kan niet veranderd worden en is alleen ter informatie.
- **Doelvenster.** Selecteer uit de uitklaplijst.
- **Templatestijl.** Selecteer uit de uitklaplijst.

**Rechter venster**

- **Menu:** (*Hoofdmenu*/*Gebruikersmenu*/...). Toont in welk menu een
  link wordt weergegeven.
- **Hoofditem:** (*Menu-item root*/...). Selecteer een hoofditem
- **Volgorde:** Volgorde is beschikbaar na opslaan
- **Status:** (*Gepubliceerd*/*Gedepubliceerd*/*Verplaatst naar
  prullenbak*). Stel publicatiestatus in.
- **Standaard pagina:** (*Ja*/*Nee*). Stel dit menu in als standaard of
  startpagina van de website. U dient altijd een standaard pagina
  ingesteld te hebben.
- **Toegang:** (*Gast*/*Publiek*/*Geregistreerd*/*Speciaal*/*Super
  gebruikers*). Toegangsniveau voor deze inhoud.
- **Taal:** (*Alle*/*English (en-GB)*/*Nederlands (NL)*). Wijs een taal
  toe aan dit menu-item
- **Notitie:** Een optionele notitie die getoond wordt in menubeheer.

### Instellingen scrollbalken tabblad

<img
src="https://docs.joomla.org/images/4/4a/Help-4x-Menus-Menu-Item-Wrapper-Scroll-Bar-parameters-screenshot-nl.png"
decoding="async" data-file-width="653" data-file-height="296"
width="653" height="296"
alt="Help-4x-Menus-Menu-Item-Wrapper-Scroll-Bar-parameters-screenshot-nl.png" />

- **Scrollbalken:** "(Nee/Ja/Automatisch)" Al dan niet opnemen van
  horizontale en verticale schuifbalken, nee of ja. Automatisch zal de
  schuifbalken automatisch toevoegen wanneer dat nodig door de omvang
  van de ingesloten pagina.
- **Breedte:** Breedte van het IFrame-venster. Voer een aantal pixels in
  of geef een percentage (%). Bijvoorbeeld, "550" betekend 550 pixels.
  "75%" betekent 75% van de breedte van de pagina.
- **Hoogte:** Hoogte van het IFrame-venster. Voer een aantal pixels in
  of geef een percentage (%). Bijvoorbeeld, "550" betekend 550 pixels.
  "75%" betekent 75% van de hoogte van de pagina.

### Geavanceerd tabblad

<img
src="https://docs.joomla.org/images/0/0b/Help-4x-Menus-Menu-Item-Wrapper-Advanced-options-screenshot-nl.png"
decoding="async" data-file-width="697" data-file-height="296"
width="697" height="296"
alt="Help-4x-Menus-Menu-Item-Wrapper-Advanced-options-screenshot-nl.png" />

- **Automatische hoogte**. Automatisch de hoogte instellen op de hoogte
  van de externe pagina. *Let op* - dit werkt alleen als de externe
  pagina op **hetzelfde domein** staat. Bijvoorbeeld,
  `http://www.example.com` de externe html moet in de `example.com` root
  bestandstructuur staan. Subdomeinen werken niet, aangezien een
  subdomein beschouwd wordt als een apart domein.
- **Automatisch toevoegen**. Automatisch het webadres laten voorafgaan
  door http://. Deze functie zal automatisch constateren of een URL al
  http:// of https:// bevat en deze niet toevoegen.
- **Framerand**. Voeg een rand toe rond het iframe venster.

### Linktype tabblad

Zie de [Menu's: Nieuw
Item](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/nl "Help4.x:Menu Item: New Item/nl")
pagina.

(ToDo - make chunk)

### Paginaweergave

Zie de [Menu's: Nieuw
item](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/nl "Help4.x:Menu Item: New Item/nl")
pagina.

(ToDo - make chunk)

### Metadata tabblad

Zie de [Menu's: Nieuw
Item](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/nl "Help4.x:Menu Item: New Item/nl")
pagina.

(ToDo - make chunk)

### Associaties tabblad

Als de taal in het 'Details tabblad' niet op 'Alle' staat verschijnt
hier een lijst met talen met de mogelijkheid om alternatieve talen te
selecteren waarin deze pagina getoond moet worden.

<img
src="https://docs.joomla.org/images/8/87/Help-4x-Menus-Menu-Item-Wrapper-Associations-screenshot-nl.png"
decoding="async" data-file-width="829" data-file-height="223"
width="829" height="223"
alt="Help-4x-Menus-Menu-Item-Wrapper-Associations-screenshot-nl.png" />

### Moduletoewijzing tabblad

Zie [Menu Item Manager: Nieuw
menu-item](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/nl "Help4.x:Menu Item: New Item/nl")
voor hulp met betrekking tot de
**[Moduletoewijzing](https://docs.joomla.org/Help4.x:Menu_Item:_New_Item/nl#Module_Assignment_Tab "Help4.x:Menu Item: New Item/nl")**
velden.

## Werkbalk

Bovenaan de pagina ziet u de werkbalk zoals in de
[afbeelding](#Schermafbeelding) hierboven. De functies zijn.

- **Opslaan**. Slaat item op en blijft op het huidige scherm.
- **Opslaan & sluiten**. Slaat item op en sluit het huidige scherm.
- **Opslaan & nieuw**. Slaat item op en houdt het bewerkscherm open,
  klaar voor het aanmaken van een ander item.
- **Opslaan als kopie**. Slaat uw wijzigingen op als een kopie van het
  huidige item. Beïnvloed het huidige item niet. Dit werkbalk icoon
  wordt niet getoond bij het aanmaken van een nieuw item.
- **Annuleren/Sluiten**. Sluit het huidige scherm en keert terug naar
  het vorige scherm zonder wijzigingen die u misschien heeft gedaan op
  te slaan.
- **Help**. Opent dit helpscherm.
