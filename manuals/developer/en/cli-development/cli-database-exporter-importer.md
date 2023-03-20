<!-- Filename: J4.x:CLI_Database_Exporter_Importer / Display title: CLI Database Exporter Importer -->

## CLI Database Commands

The Joomla! 4.x Console provides commands for exporting (backing up) and
importing (restoring) your Joomla! database. Note that it doesn't backup
your filesystem which should be done separately

Before updating Joomla! or installing a third party extension,
it is strongly recommended that you back up your site.  

## Requirements

To use these commands, you need secure shell access (SSH) to the
host on which a PHP CLI (Command Line Interface) is installed.
You need basic knowledge of shell commands.

## Instructions

Log into your host and go to the root folder of your site.  
Use the Joomla 'tmp' folder in your site to have read/write
permissions.

- List all available commands of the Joomla Console:  
  `php cli/joomla.php list`
- Export the database to the folder:  
  `php cli/joomla.php database:export --folder `
- Import the database from folder:  
  `php cli/joomla.php database:import --folder `

You can also:

- Export the database as a .zip file:  
  `php cli/joomla.php database:export --zip`
- Export a table:  
  `php cli/joomla.php database:export --table `
- Export a table as a .zip file:  
  `php cli/joomla.php database:export --table --zip`
- Import a table:  
  `php cli/joomla.php database:import --table `
- If you need help:  
  `php cli/joomla.php database:export --help`
  `php cli/joomla.php database:import --help`

## Back up and restore

To make a full backup (with folders, files and database) of your site,
you can execute these commands:

1.  Archive your Joomla root directory:  
    `tar --exclude='./tmp/joomla_bak.*' -zcvf tmp/joomla_bak.tgz . > tmp/joomla_bak.log`
2.  Export all the Joomla database:  
    `php cli/joomla.php database:export --all --folder tmp/db_bak`

And to restore it, execute these commands:

1.  Import all the Joomla database:  
    `php cli/joomla.php database:import --all --folder tmp/db_bak`
2.  Extract the archive:  
    `tar --recursive-unlink -xvf tmp/joomla_bak.tgz .`
