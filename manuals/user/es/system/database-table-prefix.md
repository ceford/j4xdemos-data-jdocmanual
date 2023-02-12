<!-- Filename: Database_Table_Prefix / Display title: Prefijo de tabla de la Base de Datos -->

El prefijo de tabla de la base de datos es una cadena (de unos cuantos
caracteres) que se antepone al nombre de las
[tablas](https://docs.joomla.org/tables "Special:MyLanguage/tables") de
Joomla!. Usar un prefijo le permite tener varias instalaciones de
Joomla! usando una única base de datos.

El prefijo de tabla de la base de datos puede establecerse durante la
instalación. Es posible cambiarlo más tarde, pero requerirá acceso a la
base de datos a través de un medio externo a Joomla, o bien mediante
alguna extensión de Joomla como Akeeba Admin Tools. El cambio requerirá
que el sitio esté fuera de línea durante un tiempo (unos pocos minutos
como mucho, normalmente).

Los desarrolladores de
[extensiones](https://docs.joomla.org/Extension "Special:MyLanguage/Extension")
necesitarán usar la cadena `#__` para representar el prefijo. Joomla
reemplazará esto por el prefijo real durante la ejecución.

## Ver también

- [Creando una Base de Datos para
  Joomla!](https://docs.joomla.org/Creating_a_Database_for_Joomla! "Special:MyLanguage/Creating a Database for Joomla!")
