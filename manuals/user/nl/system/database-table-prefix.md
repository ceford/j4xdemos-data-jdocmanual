<!-- Filename: Database_Table_Prefix / Display title: Database tabelvoorvoegsel -->

Het tabelvoorvoegsel in een database is een string (een paar tekens
lang) voorafgaand aan de naam van Joomla!'s
[tabellen](https://docs.joomla.org/tables "Special:MyLanguage/tables").
Met behulp van een voorvoegsel kunnen er meerdere installaties van
Joomla! draaien met behulp van een enkele database.

Het database tabelvoorvoegsel kan tijdens de installatie ingesteld
worden. Naderhand wijzigen is mogelijk, maar vereist toegang tot de
database via een niet-Joomla medium of een Joomla extensie zoals Akeeba
Admin Tools en kan leiden tot enige downtime.

[Extensie](https://docs.joomla.org/Extension "Special:MyLanguage/Extension")
ontwikkelaars moeten de string `#__` gebruiken als aanduiding van het
voorvoegsel. Dit zal door het werkelijke voorvoegsel vervangen worden
bij de verwerking in Joomla.

## Zie ook

- [Een database maken voor
  Joomla!](https://docs.joomla.org/Creating_a_Database_for_Joomla! "Special:MyLanguage/Creating a Database for Joomla!")
