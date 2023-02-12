<!-- Filename: Help4.x:Components_Privacy_Outline / Display title: Componenten - Privacy overzicht -->

## Privacy overzicht

### Inhoud

Het Joomla privacy-hulpmiddel bestaat uit de volgende onderdelen:

- **Beheerder component.** Beheert gebruikersinformatie privacy
  verzoeken.
- **Module - Privacy Dashboard.** Plaatst een Privacy venster op het
  Home controlepaneel.
- **Module - Privacy Requests.** Plaatst een Privacy verzoeken venster
  op het Privacy dashboard.
- **Module - Privacy Status.** Plaatst een Privacy status venster op het
  Privacy dashboard.
- **Menu-item - Maak verzoek aan.** Toont een formulier om een
  informatieverzoek te tonen. Moet gemaakt worden.
- **Plugin - Systeem - Privacy toestemming.** Voegt toestemming velden
  toe aan persoonlijke informatie formulieren zoals registratie. Moet
  ingeschakeld worden.
- **Plugin - Gebruiker - Algemene voorwaarden.** Vraagt om toestemming
  aan gebruikers voor de Algemene voorwaarden van de website. Moet
  ingeschakeld worden.
- **Plugin - Inhoud - Bevestig toestemming.** Voegt een verplicht
  aanvinkhokje toe aan een formulier, bijvoorbeeld het core
  contactformulier. Moet ingeschakeld worden.
- **Plugin - Privacy - Divers.** Meer plugins, standaard ingeschakeld,
  zonder speciale parameters die ingesteld moeten worden.

Het privacy hulpmiddel is bij installatie geschikt voor gebruik in
beheer zonder plugins in te schakelen of menu-items aan te maken.

## Workflow

Dit is een typische volgorde van gebeurtenissen:

- Er komt een informatieverzoek binnen. Het moet een juist e-mailadres
  bevatten voor gegevens opvraging. Het onderwerp hoeft geen
  geregistreerde gebruiker te zijn. Het onderwerp mag bijvoorbeeld een
  contactpersoon zijn die is toegevoegd door de beheerder.
- Als het bericht niet ingestuurd is via een persoonlijk
  informatieformulier:
  - De beheerder gaat naar
    **Gebruikers **→** Privacy **→** Verzoeken **→** Nieuw** on een
    nieuw informatieverzoek aan te maken. Het bericht wordt verstuurd
    naar het e-mailadres opgegeven in het verzoek om te bevestigen dat
    het een legitiem verzoek is.
- Als het bericht verstuurd is via een persoonlijk informatieverzoek dan
  wordt automatisch een bevestiging verstuurd.
- De indiener opent de link in het e-mailbericht om het
  bevestigingsformulier te openen. Bij verzenden ziet de indiener een
  bevestigingsbericht.
- De beheerder ziet dat privéberichten in de titelbalk openstaande
  berichten heeft.Er zal ook een systeembericht zijn.
- De beheerder gaat naar **Gebruikers **→** Privacy **→** Verzoeken** en
  ziet dat de verzoekstatus veranderd is in **Bevestigd**.
- Voor een gegevens export verzoek zijn gelijksoortige export en e-mail
  knoppen.
  - De beheerder selecteert de export knop om de gegevens die
    geëxporteerd worden te bekijken. Dit is in XML formaat maat toont
    fatsoenlijk in Firefox.
  - De beheerder selecteert de e-mail knop om de geëxporteerde gegevens
    naar de aanvrager te versturen.
- Voor een gegevens verwijderverzoek is een gelijksoortige
  verwijderknop.
  - De beheerder selecteert de verwijderknop om de gegevens van de
    gebruiker te anonimiseren. De gebruiker kan niet meer inloggen.
- Selecteer het e-mailadres van de gegevensaanvrager om het
  informatieverzoek formulier te bekijken.
- Selecteer de **Voltooien** knop in de werkbalk.
- De informatieverzoek lijst toont de status als compleet en de
  actieknoppen zijn verdwenen.

Let op dat dit hulpmiddel geen cookie-toestemmingsformulier toont.
