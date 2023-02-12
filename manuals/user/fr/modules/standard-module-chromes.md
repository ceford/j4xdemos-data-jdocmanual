<!-- Filename: Standard_Module_Chromes / Display title: Module Chromes standard -->

Notez que cet exemple comprend des ajouts de classes puisque les
exemples sont le résultat de l'utilisation de mod_mainmenu. Le suffixe
"\_menu" de la classe div ainsi que la classe "menu" de la balise ul ne
sont pas présents avec d'autres modules.

**Comparaison des modules Joomla! Chromes standards** Ceci est identique
de la série Joomla! 1.5 à la série 3.x.

Style

Sortie

Apparence

rounded (arrondi)  

      
        
          
            Main Menu
            
              
            
          
        
      

<img src="https://docs.joomla.org/images/8/8d/Module_chrome_rounded.png"
decoding="async" data-file-width="204" data-file-height="190"
width="204" height="190" alt="Module chrome rounded.png" />

none (aucun)

      

<img src="https://docs.joomla.org/images/1/18/Module_chrome_none.png"
decoding="async" data-file-width="204" data-file-height="150"
width="204" height="150" alt="Module chrome none.png" />

table (tableau)

      
        Main Menu

- 

<img src="https://docs.joomla.org/images/9/9d/Module_chrome_table.png"
decoding="async" data-file-width="204" data-file-height="160"
width="204" height="160" alt="Module chrome table.png" />

horz

      
        
          
            
              Main Menu

- 

<img src="https://docs.joomla.org/images/2/24/Module_chrome_horz.png"
decoding="async" data-file-width="204" data-file-height="170"
width="204" height="170" alt="Module chrome horz.png" />

xhtml

      Main Menu
      
        
      

<img src="https://docs.joomla.org/images/8/83/Module_chrome_xhtml.png"
decoding="async" data-file-width="206" data-file-height="165"
width="206" height="165" alt="Module chrome xhtml.png" />

html5

      Main Menu
      
        
      

<img src="https://docs.joomla.org/images/9/9f/Module_chrome_html5.png"
decoding="async" data-file-width="227" data-file-height="205"
width="227" height="205" alt="Module chrome html5.png" />

outline

      left[outline]
      
        
          
        
      

<img src="https://docs.joomla.org/images/1/12/Module_chrome_outline.png"
decoding="async" data-file-width="198" data-file-height="151"
width="198" height="151" alt="Module chrome outline.png" />

Notez que le module chrome ne va pas nécessairement changer de façon
substantielle l'apparence du module. Cela dépend principalment des CSS
utilisé par le template. Par exemple, les `none` et `horz` sont très
similaires, bien que le code HTML soit très différent.

Autres remarques : le `horiz` est juste la mise en page d'une `table`
incorporée dans une `table`, `tr` et `td`.

Depuis Joomla! 3 : Le logiciel va contrôler ceci dans le fichier
`/templates/system/html/modules.php`.

**Changes since Joomla! 4**

- The standard chromes `horz`, `rounded` and `xhtml` have been removed
  from core.
- The core module chromes are controlled by `JLayout` files in directory
  `/layouts/chromes/`.
