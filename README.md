Looking Glass
=============

Easy to deploy Looking Glass made in PHP.

Requirements
------------

  * Webserver such as Apache 2, or Lighttpd, etc…
  * PHP (>= 5.2.0) module for the webserver (mod-php5 for Apache 2 for example)
  * SSH2 library for PHP libssh2-php

Description
-----------

This web application made in PHP is what we call a **Looking Glass**. This is a
tool used to get some information about networks by giving the opportunity to
execute some commands on routers. The output is sent back to the user.

For now this looking glass is quite simple. Here you have some features:

  * Interface using Javascript and AJAX calls (needs a decent browser)
  * Support of Juniper routers
  * Support of SSH connection to routers using password authentication
  * Configurable list of routers
  * Tweakable interface (title, logo, footer)
  * Log all commands in a file
  * Customizable output with regular expressions

And here is a list of what this looking glass should be able to do in the
future:

  * Support of Cisco, Quagga, BIRD and more routers
  * Support of various authentication types
  * Configurable list of allowed commands
  * More customizable interface

Configuration
-------------

Copy the configuration **config.php.example** file to create a **config.php**
file. It contains all the values (PHP variables) used to customize the looking
glass.

License
-------

Looking Glass is released under the terms of the GNU GPLv3. Please read the
LICENSE file for more informations.

Contact
-------

If you have any bugs, errors, improvements, patches, ideas, you can contact me
on my email address <gmazoyer@gravitons.in>. You are also welcome to fork and
make some pull requests.

If you use this looking glass in your company, please drop me a mail. I would
be glad to know that this project was helpful for you.
