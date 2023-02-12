<!-- Filename: Help4.x:Languages:_Edit_Override / Display title: Talen: Overrides bewerken -->

## Beschrijving

Overrides geven de mogelijkheid een 'core' Joomla taalstring te
overschrijven.

In de Joomla code wordt van teksten die verschijnen in de
gebruikersinterface, zowel op de website als op de beheerdersinterface,
verwacht dat ze als string worden worden opgenomen. Bijvoorbeeld, de
string *Uw sessie is verlopen. Log opnieuw in.* wordt weergegeven via
*JLIB_ENVIRONMENT_SESSION_EXPIRED*. De tekst kan vertaald worden in
welke taal dan ook. De standaard taal is Brits Engels. Er zitten
duizende van zulke strings in de Joomla installatie.

Als de string niet passend is voor uw site kunt u de taaloverride
functie gebruiken om het origineel te vervangen.

## Hoe toegang te krijgen

- Selecteer **Systeem **→** Beheren venster **→** Taal overrides**.
  Dan...
  - Selecteer een **Taal en website deel** vanuit de uitklaplijst.
    Dan...
- Selecteer de **Nieuw** knop in de werkbalk om een nieuwe override aan
  te maken. Of...
  - - Selecteer de constante link in de **Constante** kolom om een
      bestaande override te bewerken.

## Schermafbeelding

<img
src="https://docs.joomla.org/images/thumb/a/a1/Help-4x-Extensions-Language-Manager-Overrides-Edit-screen-nl.png/800px-Help-4x-Extensions-Language-Manager-Overrides-Edit-screen-nl.png"
decoding="async"
srcset="https://docs.joomla.org/images/a/a1/Help-4x-Extensions-Language-Manager-Overrides-Edit-screen-nl.png 1.5x"
data-file-width="1159" data-file-height="921" width="800" height="636"
alt="Help-4x-Extensions-Language-Manager-Overrides-Edit-screen-nl.png" />

### Formulier velden

**Rechter venster: Zoektekst die u wilt wijzigen**

- **Zoeken op.** Begin hier! U kent waarschijnlijk eerder de waarde
  (verlopen) dan de constante (\_EXPIRED). In alle gevallen, is de
  zoekopdracht hoofdletter ongevoelig voor de gedeeltelijke taalstring.
- **Zoektekst.** Voer de tekst in waarop gezocht moet worden en druk op
  de **Zoeken** knop.
- **Zoekresultaten.** Een lijst met taalstrings die de zoekterm bevatten
  verschijnen in een apart venster. Selecteer degene die u zoekt. De
  constante en tekst wordt gekopieerd naar het **Maak een nieuwe
  override** venster, met de tekst **Bewerk deze override** indien u een
  bestaande override bewerkt.

**Linker venster: Maak een nieuwe override aan of Bewerk deze override**

- **Taal constante.** Dit is de constante die in de code van de
  ontwikkelaar wordt gebruikt. Als de waarde niet bestaat in de code,
  dan wordt de string nooit gebruikt.
- **Tekst.** Dit is waar u de standaard waarde overschrijft met uw eigen
  versie.
- **Bestand.** Dit is waar het override-bestand staat in het
  bestandssysteem. U wilt dit misschien weten bij het oplossen van
  problemen.

## Werkbalk

Bovenaan de pagina ziet u de filterbalk zoals in de afbeelding
hierboven. De functies zijn:

- **Opslaan**. Slaat item op en blijft op het huidige scherm.

<!-- -->

- **Opslaan & sluiten**. Slaat item op en sluit het huidige scherm.

<!-- -->

- **Opslaan & nieuw**. Slaat item op en houdt het bewerkscherm open,
  klaar voor het aanmaken van een ander item.

<!-- -->

- **Annuleren/Sluiten**. Sluit het huidige scherm en keert terug naar
  het vorige scherm zonder wijzigingen die u misschien heeft gedaan op
  te slaan. Of

<!-- -->

- **Sluiten**. Sluit het huidige scherm en keert terug naar het vorige
  scherm zonder wijzigingen die u misschien heeft gedaan op te slaan.
  Dit werkbalk icoon wordt niet getoond als een nieuw item wordt
  aangemaakt.

<!-- -->

- **Help**. Opent dit helpscherm.
