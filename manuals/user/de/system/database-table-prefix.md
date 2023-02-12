<!-- Filename: Database_Table_Prefix / Display title: Datenbanktabellenpräfix -->

Der Datenbanktabellenpräfix ist eine Zeichenkette (wenige Zeichen lang),
die vor den Namen der
Joomla!-[Tabelle](https://docs.joomla.org/tables "Special:MyLanguage/tables")
gesetzt wird. Die Nutzung des Präfix erlaubt es, mehrere
Joomla!-Installationen in nur einer Datenbank zu betreiben.

Der Datenbanktabellenpräfix kann während der Installation definiert
werden. Die nachträgliche Änderung ist möglich, setzt jedoch Zugang zur
Datenbank über ein externes Werkzeug oder durch eine
Joomla!-Erweiterung, wie Akeeba Admin Tools, voraus und könnte mit einer
Ausfallzeit verbunden sein.

Entwickler von
[Erweiterungen](https://docs.joomla.org/Extension "Special:MyLanguage/Extension")
benötigen die Zeichenkette `#__`, um den Präfix wiederzugeben. Dies wird
dann zur Laufzeit von Joomla! durch den richtigen Präfix ersetzt.

## Siehe auch

- [Erstellung einer Datenbank für
  Joomla](https://docs.joomla.org/Creating_a_Database_for_Joomla! "Special:MyLanguage/Creating a Database for Joomla!")
