<!-- Filename: J4.x:Developing_an_MVC_Component/Adding_a_Menu_Type_to_the_Site_Part / Display title: Developing an MVC Component/Adding a Menu Type to the Site Part -->

Joomla!  4.x \>Tutorial Adding a Menu Type to the Site Part

**Articles in this Series**

1.  [Introduction](https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Introduction "Special:MyLanguage/J4.x:Developing an MVC Component/Introduction")
2.  [Developing a Basic
    Component](https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Developing_a_Basic_Component "Special:MyLanguage/J4.x:Developing an MVC Component/Developing a Basic Component")
3.  [Adding a View to the Site
    Part](https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Adding_a_View_to_the_Site_Part "Special:MyLanguage/J4.x:Developing an MVC Component/Adding a View to the Site Part")
4.  [Adding a Menu Type to the Site
    Part](https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Adding_a_Menu_Type_to_the_Site_Part "Special:MyLanguage/J4.x:Developing an MVC Component/Adding a Menu Type to the Site Part")
5.  [Language
    Management](https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Language_Management "Special:MyLanguage/J4.x:Developing an MVC Component/Language Management")
6.  [Adding a Model to the Site
    Part](https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Adding_a_Model_to_the_Site_Part "Special:MyLanguage/J4.x:Developing an MVC Component/Adding a Model to the Site Part")
7.  [Adding a Request Variable in the Menu
    Link](https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Adding_a_Request_Variable_in_the_Menu_Link "Special:MyLanguage/J4.x:Developing an MVC Component/Adding a Request Variable in the Menu Link")
8.  [Setting Up the
    Database](https://docs.joomla.org/J4.x:Developing_an_MVC_Componenthttps://docs.joomla.org/J4.x:Developing%20an%20MVC%20Component/Setting%20up%20the%20Database)

This article is part of the tutorial ["Developing an MVC Component for
Joomla
4.x"](https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Introduction "J4.x:Developing an MVC Component/Introduction").
It is intended to be a follow-along programming tutorial, so if you have
not read the previous parts of the tutorial you are encouraged to do so.

## Adding a Menu Item

In this article we will cover how to add a menu item to our Hello World
component. This is a very simple process, where we create a menu
configuration file alongside our page template with a matching name.
That file is then read by the Joomla! menu system, and our page will
become an available link target.

Let's go ahead and create the configuration file for our "Hello World"
template:

|     |                                                                           |                                                         |
|-----|---------------------------------------------------------------------------|---------------------------------------------------------|
| 1   | Create: [site/tmpl/hello/default.xml](#site.2Ftmpl.2Fhello.2Fdefault.xml) | The menu item description for the "Hello" page template |
| 2   | Update: [helloworld.xml](#helloworld.xml)                                 | New component's manifest version                        |

**site/tmpl/hello/default.xml**


        
            My first Joomla! page
        

**helloworld.xml**

And as always, we update our extension's manifest file with the new
version number.



        Hello World
        
        December 2020
        
        John Smith
        https://smith.ca
        John Smith
        GPL v3
        
        0.0.3
        
        
            A hello world component!
        

        
        JohnSmith\Component\HelloWorld

        
            src
            tmpl
        

        
            
            Hello World
            
            
                services
                src
                tmpl
            
        

## Testing the Menu Item

Zip up and install your extension as before. Once you have, expand the
"Menus" section of the left hand menu, and click the plus-sign icon next
to the Main Menu. This will take you to the "New Menu Item" screen.

<img
src="https://docs.joomla.org/images/thumb/e/ee/Joomla_4.x_Component_Tutorial_0.0.3_New_Menu_Item.png/300px-Joomla_4.x_Component_Tutorial_0.0.3_New_Menu_Item.png"
data-new="" data-menu="" data-item"="" data-button="" data-in=""
data-the="" data-joomla!="" data-admin="" data-panel's="" data-menu."=""
decoding="async"
srcset="https://docs.joomla.org/images/e/ee/Joomla_4.x_Component_Tutorial_0.0.3_New_Menu_Item.png 1.5x"
data-file-width="310" data-file-height="245" width="300" height="237"
alt="Where to find the " />

There are many options here, but the two that we care about are the
link's name and its type. Give the menu link a name like "Hello World",
then select the menu item's type. You will see a list of all the
available menu item types, organised by category.

<img
src="https://docs.joomla.org/images/0/07/Joomla_4.x_Component_Tutorial_0.0.3_Menu_Item_Type.png"
data-hello="" data-world"="" data-component's="" data-first=""
data-link,="" data-appearing="" data-in="" data-the="" list=""
data-of="" data-available="" data-menu="" data-item="" data-types."=""
decoding="async" data-file-width="244" data-file-height="363"
width="244" height="363" alt="The new " />

You should see our "Hello World" component as a new category. Expand
that category and our newly created link type should appear. Go ahead
and select it, then save the menu item. Head over to the public site
part of your Joomla! install and you should see the "Hello World" link
appear in the main menu. Clicking on it should take you to the "Hello
World" page we created in the last article.

See how easy that was!

<a
href="https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Adding_a_View_to_the_Site_Part"
id="content-button" class="button expand success">Prev: Adding a View to
the Site Part</a> <a
href="https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Language_Management"
id="content-button" class="button expand">Next: Language Management</a>
