<!-- Filename: J4.x:Setting_Up_Your_Local_Environment / Display title: Setting Up Your Local Environment -->

<span id="main-portal-heading">Tutorial  
How to Setup a Local Environment for Joomla 4</span> Joomla!  4.x

With Joomla! 4 we have changed the development process. It is no longer
possible to clone the repository and have a usable Joomla installation.
We follow best practices and implement a build process for the CMS.

## Quick Start Guide

The steps to setup your development environment depend on your operating
system. We cannot write documentation for every operating system (OS),
please use your favorite search engine to find a HowTo.

### Tools You Need

1.  PHP - basically the same as you need for running a Joomla site, but
    you need the PHP CLI (command line interface) version. (See the
    [Configuring a LAMPP server for PHP
    development](https://docs.joomla.org/Configuring_a_LAMPP_server_for_PHP_development "Special:MyLanguage/Configuring a LAMPP server for PHP development")
    page.)
2.  Composer - for managing Joomla's PHP dependencies. For help
    installing Composer, read the documentation at
    <a href="https://getcomposer.org/doc/00-intro.md" class="external free"
    target="_blank"
    rel="nofollow noreferrer noopener">https://getcomposer.org/doc/00-intro.md</a>.
3.  Node.js - for compiling Joomla's JavaScript and SASS files. For help
    installing Node.js, please follow the instructions available on
    <a href="https://nodejs.org/en/" class="external free" target="_blank"
    rel="nofollow noreferrer noopener">https://nodejs.org/en/</a>. Note
    you will need NodeJS 12 or higher to install Joomla.
4.  Git - for version management.

### Steps to Setup the Local Environment

1.  Clone the repository
2.  Checkout branch *4.1-dev*
3.  Run `composer install` from the root of the git repo. (You can add
    *--ignore-platform-reqs* if you don't have the PHP-LDAP locally
    installed and you don't need it.)
4.  Run `npm ci` from the root of the git repo. (Note you need npm
    6.13.4 or higher for this. Run `npm install -g npm@lts` to upgrade
    your version of npm to the LTS version.)

Linux and OSX users can set up the following bash alias by placing the
following inside the *~/.bashrc file*:

    alias jclean="rm -rf administrator/templates/atum/css; \
    rm -rf templates/cassiopeia/css; \
    rm -rf administrator/templates/system/css; \
    rm -rf templates/system/css; \
    rm -rf media/; \
    rm -rf node_modules/; \
    rm -rf libraries/vendor/; \
    rm -f administrator/cache/autoload_psr4.php; \
    rm -rf installation/template/css"
    alias jinstall="jclean; composer install; npm ci"

This will delete all the compiled files in your system and run a fresh
install as one command by calling `jinstall` inside your Joomla install.
You can also use the `jclean` command to swap back to a Joomla 3.x
branch

## A Bit Longer Start Guide

Joomla is similar to many other web tools these days. It has a large PHP
part and it has more and more JavaScript code. While PHP coding doesn't
need so much preparation, JavaScript needs a lot tooling around. The
main reason is that nobody writes code in a way that every browser
understands, so the code needs transpiling from e.g. ES6 to a compatible
version of JavaScript. The same is true for CSS. For Joomla we are using
SASS and this will be converted to native CSS so that any browser
understands it. On the downside, setting up a development environment is
a bit more complicated but the tooling makes coding more convenient.
Thanks to watchers and browser auto reload, you can see your changes in
real time.

### PHP

It should be enough to run `composer install` as this will install PHP
dependencies saved in the *composer.lock* file. You can do this as many
times as you like. It will only install new packages when the
*composer.lock* file is changed. Don't run `composer update` as this
will update all packages to newer versions and update the
*composer.lock* file.

**Note:** You may need to run `composer install` with the
`--ignore-platform-reqs` option to ignore platform requirements
specified in Composer. That is, if you do not have PHP's LDAP extension
installed.

### Node/npm Scripts

Node.js comes with a package manager called NPM (in some ways the same
as Composer). NPM has a `run` command and we have prepared some scripts
to make your life easier. You have to run the commands for the root of
the repository when you changed JS or SASS files. Previously you need to
run `npm ci` once, to install dependencies.

#### npm run build:css

It will compile SASS files to CSS and also create the minified files.

#### npm run build:js

It will compile and transpile the JavaScript files to the correct format
and create minified files.

#### npm run watch

This is the same as the `build:js` command but will watch for changes
and automatically build updated files in the media directory. SASS files
are not included yet.

#### npm run lint:js

This will perform a syntax check on all ES6 JavaScript files against the
JavaScript code standard (for more information on the Joomla 4 codestyle
standard please read the the coding standards manual at <a
href="https://developer.joomla.org/coding-standards/introduction.html%7C"
class="external text" target="_blank" rel="noreferrer noopener">the
coding standards manual</a>.

#### npm run test

This will run a JavaScript testing suite.

## Possible Issues

When running composer install you can run into these errors

    Problem 1
        - Installation request for joomla/ldap 2.0.0-beta -> satisfiable by joomla/ldap[2.0.0-beta].
        - joomla/ldap 2.0.0-beta requires ext-ldap * -> the requested PHP extension ldap is missing from your system.
    Problem 2
        - Installation request for symfony/ldap v5.1.5 -> satisfiable by symfony/ldap[v5.1.5].
        - symfony/ldap v5.1.5 requires ext-ldap * -> the requested PHP extension ldap is missing from your system.

The solution is to run the composer install with the
`--ignore-platform-reqs` option to ignore platform requirements
specified in Composer. That is, if you do not have PHP's LDAP extension
installed.

    composer install --ignore-platform-reqs

If you receive a login error such as shown below, delete the
`administrator/cache/autoload_psr4.php` file.

<img
src="https://docs.joomla.org/images/thumb/b/b3/Install-error.png/400px-Install-error.png"
class="thumbborder" decoding="async"
srcset="https://docs.joomla.org/images/thumb/b/b3/Install-error.png/600px-Install-error.png 1.5x, https://docs.joomla.org/images/thumb/b/b3/Install-error.png/800px-Install-error.png 2x"
data-file-width="1920" data-file-height="1080" width="400" height="225"
alt="Login After Install Error" />
