<!-- Filename: J4.x:MVC_Anatomy:_Manifest_File / Display title: MVC Anatomy: Manifest File -->

## Metadata

The component manifest file must be named manifest.xml or
componentname.xml, in this case countrybase.xml. Note that the com\_
part is not included. The first part of the file contains metadata:


        countrybase
        Clifford E Ford
        john.doe@example.com
        example.com
        2022-05-10
        (C) 2022 Clifford E Ford
        GNU General Public License version 2 or later; see LICENSE.txt
        0.1.0
        COM_COUNTRYBASE_DESCRIPTION
        J4xdemos\Component\Countrybase

Most of the metadata is self-evident. Items to note:

- The extension type in this case is **component**. There are other
  extensions types, such as module or plugin.
- The method can be install or upgrade. The latter allows
  re-installation after code update.
- The version number is important! It should make it impossible to
  reinstall an older version. And it is used to control whether database
  updates are required.
- The namespace path src has three parts:
  - The first part is a supplier defined prefix, so Joomla for Joomla
    supplied code, Acme for code supplied by the Acme third party
    extension supplier, and in this case J4xdemos, a name I chose for
    all my Joomla 4 code demonstrations.
  - The second part indicates the type of extension. It could be
    Component or Module or Plugin or ...
  - The third part is the specific extension name, in this case
    Countrybase.

## Database

The manifest file defines the locations of any installation, update or
removal sql files. They end up in an sql folder in the administrator
folder.

       
            
                sql/install.mysql.sql
            
        
        
            
                sql/uninstall.mysql.sql
            
        
        
            
                sql/updates/mysql
            
        

## Script File

A script file may be used for pre-flight or post-flight purposes. For
example, it could be used to check minimum system requirements before
installation or to set parameters after installation.

## Media Files

The com_countrybase component does not need any component specific css
or javascript but the code to install them is included just in case. The
files are empty.

       script.php

        
            joomla.asset.json
            css
            js
        

Note that the joomla.asset.json file is used by the web asset manager,
usually called from a template file.

## Site Files

These are the files that are copied to root/components/com_countrybase.
Note that the language folder is copied to the component folder and not
the administrator/language folder:

       
            language
            forms
            src
            tmpl
        

## Administrator Files

There are more files in the administration part of the manifest file
because it has more to do:

       
            
                access.xml
                config.xml
                forms
                help
                language
                layouts
                services
                sql
                src
                tmpl
            
            countrybase
            
                
                
                    COM_COUNTRYBASE_COUNTRIES
                
                
                    COM_COUNTRYBASE_CURRENCIES
                
            
        

Note the method to create the Joomla Administrator menu items. There is
a menu item that does not have a link. And two menu items that link to
the two available administration views: the Countries list and the
Currencies list. Also the string key translations need to be in the
com_countrybase.sys.ini file.

## Update Server

The update server code tells Joomla where to find update information. It
is executed at regular intervals to see if there is an update available.
Leave out this section if you are not using an update server for your
own component.

       
            
            https://raw.githubusercontent.com/ceford/j4xdemos-com-countrybase/master/manifest.xml
        

## Related Tutorials

### MVC Anatomy

- [Getting
  Started](https://docs.joomla.org/J4.x:MVC_Anatomy:_Getting_Started "Special:MyLanguage/J4.x:MVC Anatomy: Getting Started")
- [File
  Structure](https://docs.joomla.org/J4.x:MVC_Anatomy:_File_Structure "Special:MyLanguage/J4.x:MVC Anatomy: File Structure")
- [Manifest
  File](https://docs.joomla.org/J4.x:MVC_Anatomy:_Manifest_File "Special:MyLanguage/J4.x:MVC Anatomy: Manifest File")
- [Site
  Files](https://docs.joomla.org/J4.x:MVC_Anatomy:_Site_Files "Special:MyLanguage/J4.x:MVC Anatomy: Site Files")
- [Administrator Startup
  Files](https://docs.joomla.org/J4.x:MVC_Anatomy:_Administrator_Startup_Files "Special:MyLanguage/J4.x:MVC Anatomy: Administrator Startup Files")
- [Administrator Edit
  Files](https://docs.joomla.org/J4.x:MVC_Anatomy:_Administrator_Edit_Files "Special:MyLanguage/J4.x:MVC Anatomy: Administrator Edit Files")
