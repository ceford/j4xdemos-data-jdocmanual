<!-- Filename: J4.x:Developing_an_MVC_Component/Adding_a_Request_Variable_in_the_Menu_Link / Display title: Developing an MVC Component/Adding a Request Variable in the Menu Link -->

Joomla!  4.x \>Tutorial Adding a Request Variable to the Menu Link

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

We now have a page in our Joomla installation's public front-end that
can render a greeting message, provided by a data model. Now we will add
a request variable to the menu link we created earlier, and learn how to
read the request variable inside the data model. Depending on the value
of the variable, we will show a different greeting.

## Required Changes

There are two primary changes we will need to make:

- Adding the request variable and its possible values to the menu link's
  XML definition
- Adding code to the model to read the request variable and choose an
  appropriate greeting

|     |                                                                                                                       |                                                                           |
|-----|-----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| 1   | Update: [site/tmpl/hello/default.xml](#site.2Ftmpl.2Fhello.2Fdefault.xml)                                             | Add the new parameter to the menu link's definition                       |
| 2   | Update: [site/src/Model/MessageModel.php](#site.2Fsrc.2FModel.2FMessageModel.php)                                     | Have the view's data model decide which greeting to return                |
| 3   | Update: [admin/language/en-GB/en-GB.com_helloworld.sys.ini](#admin.2Flanguage.2Fen-GB.2Fen-GB.com_helloworld.sys.ini) | Add the new language strings needed when configuring the menu link        |
| 4   | Update: [site/language/en-GB/en-GB.com_helloworld.ini](#site.2Flanguage.2Fen-GB.2Fen-GB.com_helloworld.ini)           | Swap our existing greeting string for two greetings we can choose between |
| 5   | Update: [helloworld.xml](#helloworld.xml)                                                                             | For consistency, we'll bump the component's version number                |

## File Details

**site/tmpl/hello/default.xml**

While this change may look fairly verbose, it's actually very
straightforward. We're adding a configurable request variable (called a
"field") to our menu link. When editing the menu entry in the Joomla
control panel, this field and its options will be displayed in the
configuration form.

Menu fields are organised into fieldsets, though we only need the one
here. We'll call our field `greetingType`, which will be appended to the
URL when the link is clicked. We're also pre-defining what values are
allowed for this field, as we want to be able to rely on their values in
the data model. We do this by using `type="list"` to tell Joomla it has
a list of values, and then providing them as child elements.

The `value` attribute of each is the actual value that will be appended
to the URL (such as `&greetingType=1`). The language string name inside
the element represents the label that will be shown in the configuration
form.


        
            COM_HELLOWORLD_MENU_HELLO_WORLD_DESC
        
        
            
                
                    COM_HELLOWORLD_MENU_HELLO_WORLD_PARAM_VALUE_HELLO
                    COM_HELLOWORLD_MENU_HELLO_WORLD_PARAM_VALUE_GOODBYE
                
            
        

**site/src/Model/MessageModel.php**

Here we read in the new request variable via the Joomla framework, and
decide which of our two greeting messages to show. This code illustrates
how to read request variables in Joomla 4:

1.  `Factory::getApplication()` returns the Joomla application object.
    You will use this code a lot when writing in Joomla, as your entry
    point to the Joomla runtime.
2.  `->getInput()` returns the `\Joomla\Input\Input` object for this
    request. This object can be used to read request variables in a safe
    and sanitised manner.
3.  `$input->getInt('greetingType', 1);` fetches the value of the
    'greetingType' request variable we defined earlier. If no value is
    defined, we have specified that it should return a default value of
    `1`.

**NOTE:** You should never use superglobals like `$_GET` or `$_POST` to
access request variables or other inputs. Use Joomla's framework to
access any passed or submitted data, to ensure that it is properly
handled and sanitised.

With the request variable read, we simply choose which of our two
possible greetings to return to the template.

    getInput();
            $greetingType = $input->getInt('greetingType', 1);

            $item = new \stdClass();
            
            switch($greetingType) {
                case 2:
                    $item->message = Text::_('COM_HELLOWORLD_MSG_GREETING_GOODBYE');
                    break;
                case 1:
                default:
                    $item->message = Text::_('COM_HELLOWORLD_MSG_GREETING_HELLO');
                    break;
            }
            
            return $item;
        }
            
    }

**admin/language/en-GB/en-GB.com_helloworld.sys.ini**

Here we define the language strings that will be used in the
configuration form for our menu link. Remember, even though the menu
link is defined in the site part of the component, the strings are
defined here because it is used in the Joomla control panel.

    ; Hello World Sys.ini
    ; Copyright (C) 2020 John Smith. All rights reserved.

    COM_HELLOWORLD_MENU_HELLO_WORLD_TITLE="Hello World!"
    COM_HELLOWORLD_MENU_HELLO_WORLD_DESC="My first Joomla! page"
    COM_HELLOWORLD_MENU_HELLO_WORLD_PARAM_LABEL="Greeting Type"
    COM_HELLOWORLD_MENU_HELLO_WORLD_PARAM_DESC="Select which type of greeting to show"
    COM_HELLOWORLD_MENU_HELLO_WORLD_PARAM_VALUE_HELLO="Say Hello"
    COM_HELLOWORLD_MENU_HELLO_WORLD_PARAM_VALUE_GOODBYE="Say Goodbye"

**site/language/en-GB/en-GB.com_helloworld.ini**

Here we switch out our existing greeting for two different greetings,
which the model will choose between based on the value of the
`greetingType` request variable.

    ; Hello World Public Site Strings
    ; Copyright (C) 2020 John Smith. All rights reserved.

    COM_HELLOWORLD_MSG_HELLO_WORLD="Hello World!"
    COM_HELLOWORLD_MSG_GREETING_GOODBYE="Goodbye from the item model!"
    COM_HELLOWORLD_MSG_GREETING_HELLO="Hello from the item model!"

**helloworld.xml**

As before, our last job is to bump the component's version number. None
of the changes made here require the version number to be bumped before
re-importing it, but we'll do it for consistency.



        Hello World
        
        December 2020
        
        John Smith
        https://smith.ca
        John Smith
        GPL v3
        
        0.0.6
        
        
            A hello world component!
        

        
        JohnSmith\Component\HelloWorld

        
            language
            src
            tmpl
        

        
            site/language/en-GB/en-GB.com_helloworld.ini
        

        
            
            Hello World
            
            
                language
                services
                src
                tmpl
            

            
                admin/language/en-GB/en-GB.com_helloworld.ini
                admin/language/en-GB/en-GB.com_helloworld.sys.ini
            
        

## Testing the Extension

Just as before, zip up your new component version and upload it into
your Joomla! install's admin panel. Once it has updated, open the main
menu setup from the left menu as you did before, then click your "Hello
World" link in the list of link on the right.

<img
src="https://docs.joomla.org/images/e/eb/Joomla_4.x_Component_Tutorial_0.0.6_Main_Menu_Link.png"
decoding="async" data-file-width="291" data-file-height="219"
width="291" height="219"
alt="Link to the main menu configuration in the Joomla control panel" />

You should see the menu link configuration form once again, but now
there should be a brand new drop-down selection box:

<img
src="https://docs.joomla.org/images/thumb/f/f1/Joomla_4.x_Component_Tutorial_0.0.6_Menu_Link_Configuration.png/300px-Joomla_4.x_Component_Tutorial_0.0.6_Menu_Link_Configuration.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f1/Joomla_4.x_Component_Tutorial_0.0.6_Menu_Link_Configuration.png/450px-Joomla_4.x_Component_Tutorial_0.0.6_Menu_Link_Configuration.png 1.5x, https://docs.joomla.org/images/thumb/f/f1/Joomla_4.x_Component_Tutorial_0.0.6_Menu_Link_Configuration.png/600px-Joomla_4.x_Component_Tutorial_0.0.6_Menu_Link_Configuration.png 2x"
data-file-width="879" data-file-height="369" width="300" height="126"
alt="Menu link configuration with custom fields added" />

Here you can see our new configuration option, "Greeting Type". This is
the field we defined in XML earlier, using the language strings we also
defined. To test your change, select one of the possible greeting types
and save the menu link. Once the link is saved, visit the public section
of your Joomla install and click the link. You should see the
appropriate greeting!

<img
src="https://docs.joomla.org/images/thumb/5/51/Joomla_4.x_Component_Tutorial_0.0.6_Message_from_Model.png/300px-Joomla_4.x_Component_Tutorial_0.0.6_Message_from_Model.png"
decoding="async"
srcset="https://docs.joomla.org/images/5/51/Joomla_4.x_Component_Tutorial_0.0.6_Message_from_Model.png 1.5x"
data-file-width="383" data-file-height="255" width="300" height="200"
alt="The greeting from the data model that matches the field in the menu link" />

To make sure that the request variable is working correctly, make sure
to switch the menu link's configuration back and forth a few times. The
message in the public page should change as appropriate.

Great! Now we have a page taking simple data from a model, *and* that
model can respond to request variables. Next, we'll finally get to
setting up our database, and wiring our data model up to it.

<a
href="https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Adding_a_Model_to_the_Site_Part"
id="content-button" class="button expand success">Prev: Adding a Model
to the Site Part</a> <a
href="https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Setting_up_the_Database"
id="content-button" class="button expand">Next: Setting up the
Database</a>
