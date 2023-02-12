<!-- Filename: J4.x:Developing_an_MVC_Component/Adding_a_Model_to_the_Site_Part / Display title: Developing an MVC Component/Adding a Model to the Site Part -->

Joomla!  4.x \>Tutorial Adding a Model to the Site Part

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

Now that we have the "Controller" and "View" portions of the
Model-View-Controller design pattern in place, in this article we will
add a model to our Hello World component. The model will hold some
sample data for our template to render. To create a model we extend one
of the abstract models provided by Joomla! Several such models exist,
and can be found in the `Joomla\CMS\MVC\Model` namespace:

|     |                                   |                                                                                                                                                                                                              |
|-----|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | `Joomla\CMS\MVC\Model\AdminModel` | Despite its name, this model is not actually specific to the admin panel section of Joomla! It is actually for administering records of a particular type, allowing for batch update/delete operations, etc. |
| 2   | `Joomla\CMS\MVC\Model\BaseModel`  | The basic model from which other models inherit. If you don't require any additional functionality you can extend this model, but you likely don't want to.                                                  |
| 3   | `Joomla\CMS\MVC\Model\FormModel`  | Used in forms, allows for rows to be checked in or out for editing, and has methods for validation of form inputs.                                                                                           |
| 4   | `Joomla\CMS\MVC\Model\ItemModel`  | Represents a single database record, allows for basic database operations.                                                                                                                                   |
| 5   | `Joomla\CMS\MVC\Model\ListModel`  | Used to display paginated lists of records, with optional filtering.                                                                                                                                         |

Later in the tutorial we will back this model with a database query, so
we're going to use `ItemModel` as the base for our new model class.
Let's go ahead and create the new files we will need to add our model.

|     |                                                                                                               |                                                                                               |
|-----|---------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| 1   | Update: [`site/language/en-GB/en-GB.com_helloworld.ini`](#site.2Flanguage.2Fen-GB.2Fen-GB.com_helloworld.ini) | We'll add a new message to pull from the language system, to verify that our model is working |
| 2   | Create: [`site/src/Model/MessageModel.php`](#site.2Fsrc.2FModel.2FMessageModel.php)                           | Our new model, which will hold a message for display in the public web page                   |
| 3   | Update: [`site/src/Controller/DisplayController.php`](#site.2Fsrc.2FController.2FDisplayController.php)       | We'll tell the default display controller to fetch the new model                              |
| 4   | Update: [`site/tmpl/hello/default.php`](#site.2Ftmpl.2Fhello.2Fdefault.php)                                   | We'll add an output in the template to show the message from the model                        |
| 5   | Update: [`helloworld.xml`](#helloworld.xml)                                                                   | A simple version bump, for our new code                                                       |

## File Details

**site/language/en-GB/en-GB.com_helloworld.ini**

We'll (temporarily) put a new message in here that we can use to demo
the model.

    ; Hello World Admin Strings
    ; Copyright (C) 2020 John Smith. All rights reserved.

    COM_HELLOWORLD_MSG_HELLO_WORLD="Hello World!"
    COM_HELLOWORLD_MSG_GREETING="This message is coming from the item model!"

**site/src/Model/MessageModel.php**

The new single-item data model. The `getItem()` method is the only one
required when extending `ItemModel`. It returns an object that
represents the model's item. This "item" could be anything, but is
usually a database record. Until we hook this model up to the database
in a future part of the tutorial, we will return a basic object with our
new message in it, straight from the language system.

    message = Text::_('COM_HELLOWORLD_MSG_GREETING');
            return $item;
        }
            
    }

**site/src/Controller/DisplayController.php**

We're going to tell the `DisplayController` to add our new model to the
view as it is being loaded. As we currently have only one view, this
will do for now. As our component becomes more complex, our views will
gain their own controllers, and can load their own models independently.

    input->getCmd('view', 'login');
            $viewFormat = $document->getType();
            
            $view = $this->getView($viewName, $viewFormat);
            $view->setModel($this->getModel('Message'), true);
            
            $view->document = $document;
            $view->display();
        }
        
    }

**site/tmpl/hello/default.php**

The last functional change to make is to add the message output into our
site template. In the context of a component template, the `$this`
variable refers to the view object. Remember setting the model on the
view in the previous file? We retrieve it here, and display the message.

    <?= Text::_('COM_HELLOWORLD_MSG_HELLO_WORLD') ?>

    <?= $this->getModel()->getItem()->message; ?>

**helloworld.xml**

There's nothing new needed in the manifest file for these changes, so
this update isn't technically required. However, for consistency, we
will bump the component's version in the manifest file.



        Hello World
        
        December 2020
        
        John Smith
        https://smith.ca
        John Smith
        GPL v3
        
        0.0.5
        
        
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
            
        

## Testing the Component

Just as before, zip up your new component version and upload it into
your Joomla! install's admin panel. Once you have done so, go to the
front-end of your Joomla site. Click the "Hello World" link we created
in the menu. You should see the new message in the page template.

<img
src="https://docs.joomla.org/images/thumb/d/dd/Joomla_4.x_Component_Tutorial_0.0.5_Message_from_Model.png/300px-Joomla_4.x_Component_Tutorial_0.0.5_Message_from_Model.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/dd/Joomla_4.x_Component_Tutorial_0.0.5_Message_from_Model.png/450px-Joomla_4.x_Component_Tutorial_0.0.5_Message_from_Model.png 1.5x, https://docs.joomla.org/images/d/dd/Joomla_4.x_Component_Tutorial_0.0.5_Message_from_Model.png 2x"
data-file-width="466" data-file-height="302" width="300" height="194"
alt="The new language string, being passed to the template from the new model" />

Next, we'll learn how to add parameters to menu items, and how to read
them within the code. After that, we'll start wiring our component up to
the database.

<a
href="https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Language_Management"
id="content-button" class="button expand success">Prev: Language
Management</a> <a
href="https://docs.joomla.org/J4.x:Developing_an_MVC_Component/Adding_a_Request_Variable_in_the_Menu_Link"
id="content-button" class="button expand">Next: Adding a Request
Variable in the Menu Link</a>
