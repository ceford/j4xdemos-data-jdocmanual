<!-- Filename: J4.x:CLI_example_-_Onoffbydate / Display title: CLI example - Onoffbydate -->

Joomla!  4.x

## Introduction

There are occasions when a site needs to display or hide a module
depending on the date. One example might be a custom html module
displaying a message during winter. Another might be alternation of
custom modules depending on the day of the week. Say one for weekdays
and another for weekends. The example presented here uses a plugin, a
cli command and a cron to achieve the desired effect.

The code is available on github:
<a href="https://github.com/ceford/j4xdemos-plg-onoffbydate"
class="external text" target="_blank"
rel="nofollow noreferrer noopener">https://github.com/ceford/j4xdemos-plg-onoffbydate</a>

## Joomla 4 Standards

In earlier versions of Joomla the plugin system used an implementation
of the Observable/Observer pattern. As a result, every plugin being
loaded would immediately have all of its public methods registered as
observers. This could cause problems.

Joomla 4 uses the Joomla Framework Event package to handle plugin
Events. This provides for better performance and security. In practical
terms it means that the file structure of a Joomla 4 plugin is different
from Legacy plugin structure from earlier versions. And the layout for a
web application is likely to differ from a cli application as
illustrated here.

## The Plugin

The plugin is named **onoffbydate** because that is what it does. At the
moment the plugin is coded as a system plugin but it probably merits a
new cli type in due course. The files:

### onoffbydate.xml

This is the installation file - a standard item for any extension.


        plg_system_onoffbydate
        Clifford E Ford
        October 2021
        (C) Clifford E Ford
        GNU General Public License version 3 or later
        cliff@ford.myzen.co.uk
        0.2.0
        PLG_SYSTEM_ONOFFBYDATE_DESCRIPTION
        Joomla\Plugin\System\Onoffbydate
        
            onoffbydate.php
            services
            src
        
        
            language/en-GB/plg_system_onoffbydate.ini
            language/en-GB/plg_system_onoffbydate.sys.ini
        
        
        

Note in particular the **namespace** line. It tells Joomla where to find
the namespaced code for this plugin.

### onoffbydate.php

This is the standard entry point for a Legacy plugin but it is not used
at all for a Joola 4 plugin. However it needs to be present for the
Joomla Installer. Without it the install will fail.


    services/provider.php

    This is the entry point for the plugin code.

    set(
                    PluginInterface::class,

                    function (Container $container) {
                        $subject = $container->get(DispatcherInterface::class);
                        $config  = (array) PluginHelper::getPlugin('system', 'onoffbydate');

                        return new Onoffbydate($subject, $config);
                    }
                    );

        }
    };

Notice the call to create a **new Onoffbydate** class. That is located
in the src/Extension folder - the standard location to boot a Joomla 4
extension.

### src/Extension/Onoffbydate.php

This is the place where the plugin initialisation code is located.

    app->isClient('cli'))
            {
                return;
            }

            $this->registerCLICommands();
        }

        public static function getSubscribedEvents(): array
        {
            if ($this->app->isClient('cli'))
            {
                return [
                    Joomla\Application\ApplicationEvents\ApplicationEvents::BEFORE_EXECUTE => 'registerCLICommands',
                ];
            }
        }

        public function registerCLICommands()
        {
            $commandObject = new OnoffbydateCommand;
            $this->app->addCommand($commandObject);
        }
    }

Notice the call to create a **new OnoffbydateCommand** class. That is
located in the src/Console folder. Console is a personal choice - the
built in Joomla cli commands are located in a Console filder. The checks
for isClient('cli') are necessary or this plugin will kill the site. If
that happens find it in the **\#\_\_xtensions** table using phpMyAdmin
and set **enabled** to 0.

### language files

There are two language files used during installation and plugin
configuration. They are not covered here. Please view the code on
github.

Note also that the command output is seen only by you on your Joomla
installation so it is probably not worth making the output translatable.
That seems to be the case with most of the Joomla core cli commands.

### The Command File: src/Console/OnoffbydateCommand.php

    cliInput = $input;
            $this->ioStyle = new SymfonyStyle($input, $output);
        }

        /**
         * Initialise the command.
         *
         * @return  void
         *
         * @since   4.0.0
         */
        protected function configure(): void
        {
            $this->addArgument('action',
                    InputArgument::REQUIRED,
                    'name of action');

            $this->addArgument('module_id',
                    InputArgument::REQUIRED,
                    'module id');

            $help = "%command.name% Toggles module Enabled/Disabled state
                \nUsage: php %command.full_name% action_id module_id
                \nwhere action_id is one of winter or weekend";

            $this->setDescription('Called by cron to set the enabled state of a module.');
            $this->setHelp($help);

        }

        /**
         * Internal function to execute the command.
         *
         * @param   InputInterface   $input   The input to inject into the command.
         * @param   OutputInterface  $output  The output to inject into the command.
         *
         * @return  integer  The command exit code
         *
         * @since   4.0.0
         */
        protected function doExecute(InputInterface $input, OutputInterface $output): int
        {
            $this->configureIO($input, $output);

            $action = $this->cliInput->getArgument('action');
            $module_id = $this->cliInput->getArgument('module_id');

            switch ($action) {
                case 'winter' :
                    $result = $this->winter($module_id);
                    break;
                case 'weekend' :
                    $result = $this->weekend($module_id);
                    break;
                default:
                    $this->ioStyle->error("Unknwon action: {$action}");
                    return 0;
            }

            return 1;
        }

        protected function weekend($module_id)
        {
            // get the day of the week
            $day = date('w');
            if (in_array($day, array(0,6)))
            {
                $msg = "Today is a weekend.";
                $published = 1;
            }
            else
            {
                $msg = "Today is not a weekend.";
                $published = 0;
            }

            $this->publish($module_id, $published);

            $state = empty($published) ? 'Unpublished' : 'Published';

            $this->ioStyle->success("That seemed to work. {$msg} Module {$module_id} has been {$state}");

        }

        protected function winter($module_id)
        {
            // get the month of the month
            $month = date('n');
            if (in_array($month, array(1,2,11,12)))
            {
                $msg = "Today is in winter.";
                $published = 0;
            }
            else
            {
                $msg = "Today is not in winter.";
                $published = 1;
            }

            $this->publish($module_id, $published);

            $state = empty($published) ? 'Unpublished' : 'Published';

            $this->ioStyle->success("That seemed to work. {$msg} Module {$module_id} has been {$state}");

        }

        protected function publish ($module_id, $published)
        {
            $db = Factory::getDbo();
            $query = $db->getQuery(true);
            $query->update('#__modules')
            ->set('published = ' . $published)
            ->where('id = ' . $module_id);
            $db->setQuery($query);
            $db->execute();
        }
    }

The **configure** function establishes that two command line arguments
are required:

- An action keyword
- A module id

The **doExecute** function is where the work gets done. Two action
options are illustrated:

- **winter** calls a function to publish a module in winter months.
- **weekend** calls a function to publish a module if the date a weekend
  day.

Clearly you can add as many date related actions as you need.

## The Module

This code simply changes the published state of a module depending on
some function of the date. So you need the module id as illustrated in
the right hand column of the Modules (Site) list page.

<img
src="https://docs.joomla.org/images/d/de/J4xdemos-onoffbydate-module.png"
decoding="async" data-file-width="800" data-file-height="328"
width="800" height="328" alt="The Site Module List" />

## The Command Line

If the code works you will see onoffbydate among the list of available
commands. Open a terminal window and enter:

    php cli/joomla.php list

If something goes wrong at this stage check that the php version invoked
is the command line version and not that used by the web server. If you
see onoffbydate among the list of commands you can invoke help to see
how it should be used:

    php cli/joomla.php onoffbydate:action --help     
    Usage:
      onoffbydate:action  

    Arguments:
      action                name of action
      module_id             module id

    Options:
      -h, --help            Display the help information
      -q, --quiet           Flag indicating that all output should be silenced
      -V, --version         Displays the application version
          --ansi            Force ANSI output
          --no-ansi         Disable ANSI output
      -n, --no-interaction  Flag to disable interacting with the user
      -v|vv|vvv, --verbose  Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

    Help:
      onoffbydate:action Toggles module Enabled/Disabled state
                    
      Usage: php cli/joomla.php onoffbydate:action action_id module_id
                    
      where action_id is one of winter or weekend

And then just try it out:

    php cli/joomla.php onoffbydate:action winter 130

                                                                                                                            
     [OK] That seemed to work. Today is not in winter. Module 130 has been Published                                        
                                                                                                                            

## The cron

The command can be tested in a terminal window but you probably want to
use it from a cron. The winter option could be run on the first day of
each month. The oddday option would be run daily. The important point is
that you can have as many crons as you need to change the published
state of as many modules as you like at any appropriate intervals. The
same code works for all.

On a hosting service you need to give the full paths to the php
executable and the joomla cli command. Example:

    /usr/local/bin/php /home/username/public_html/pathtojoomla/cli/joomla.php onoffbydate:action winter 130

Depending on how you have set up your cron and your system you may get a
comforting email containing exactly the same information you see in the
command line.

## Check

And of course: go to your home page and check that the module really has
been published or unpublished.
