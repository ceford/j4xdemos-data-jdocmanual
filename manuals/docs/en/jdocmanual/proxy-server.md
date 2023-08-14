<!-- Filename: Proxy_Server / Display title: Proxy Server -->

## Delivering Help Pages

In the Joomla configuration.php file is an entry that tells the installation where to find the Help pages.
It looks like this:

```php
	public $helpurl = 'https://help.joomla.org/proxy?keyref=Help{major}{minor}:{keyref}&lang={langcode}';
```
To fetch an individual Help page the items in curly braces are replaced with the parameters for a specific 
Help page. This is an example for the the Articles list:

```html
https://help.joomla.org/proxy?keyref=Help43:Articles&lang=en
```

The proxy server does some extra processing of a Help page to remove information not relevant in 
that context. For example, if the `lang` parameter is not `en` it checks to see if the page is available
in that language. If not, it delivers the `en` version (English). Also, it removes the links used to edit
sections of the source or the images.

## The Jdocmanual Proxy Server

There is a similar proxy server available with Jdocmanual. It is set up during installation using the
command line interface, which is also used for updates.

```bash
php joomla.php jdocmanual:action buildproxy all all
```
The proxy server is a simple php script (index.php) in a proxy subfolder of the installed site.
Subfolders are created for each available language. The Help pages are stored as individual
HTML files. The proxy script looks for the desired language and either sends the Help page in
that language or English if the original has not been translated.

To use your own proxy all you need to do is change the `configuration.php` file `helpurl`
domain to that where Jdocmanual is installed. At the moment it delivers the same Help
pages for Joomla 4 and Joomla 5. That will change when any differences become
apparent.

