<!-- Filename: Standard_Module_Chromes / Display title: Módulo estándar Chromes -->

Observa que en este ejemplo se incluye la clase *additions* porque los
ejemplos son tomados mediante mod_mainmenu. El sufijo "\_menu" al div de
la clase y la clase "menú" en la etiqueta *ul* no están presentes con
otros módulos.

**Comparación del Módulo estándar chromes de Joomla!**

Estos son los mismos de Joomla! 1.5 a 3.3

Estilo

Salida

Apariencia

redondeado  

      
        
          
            Main Menu
            
              
            
          
        
      

<img src="https://docs.joomla.org/images/8/8d/Module_chrome_rounded.png"
decoding="async" data-file-width="204" data-file-height="190"
width="204" height="190" alt="Module chrome rounded.png" />

ninguno

      

<img src="https://docs.joomla.org/images/1/18/Module_chrome_none.png"
decoding="async" data-file-width="204" data-file-height="150"
width="204" height="150" alt="Module chrome none.png" />

tabla

      
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

esquema

      left[outline]
      
        
          
        
      

<img src="https://docs.joomla.org/images/1/12/Module_chrome_outline.png"
decoding="async" data-file-width="198" data-file-height="151"
width="198" height="151" alt="Module chrome outline.png" />

Ten en cuenta que el Módulo chrome no necesariamente cambia demasiado la
apariencia de todo - esto depende de las CSS que se utilizan en la
plantilla. Por ejemplo, los aspectos '`ninguno`' y '`horiz`' de chromes
son muy similares, aunque el código HTML subyacente es muy diferente.

Otras notas: El diseño `horiz` es sólo el diseño `tabla`, envuelto en
`table`, `tr`y `td`.

El software de control de estos se encuentra en el archivo

`/templates/system/html/modules.php`.

**Changes since Joomla! 4**

- The standard chromes `horz`, `rounded` and `xhtml` have been removed
  from core.
- The core module chromes are controlled by `JLayout` files in directory
  `/layouts/chromes/`.
