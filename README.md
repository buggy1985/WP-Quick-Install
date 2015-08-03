WP Quick Install 1.4.1
================


This is a one-file version of WP Quick Install.

Usage:
- copy install.php to an empty folder on your web server
- preconfigure the $data array
- open http://your-host/your-folder/install.php

This fork comes with following improvements:

- use preconfigured data in the setup form
- auto detect themes.zip and install it by default
- remove standard themes by default if a custom theme is installed
- always use current directory as install folder

Todo:
- self destroying install.php after successfully installed
