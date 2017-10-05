Apache mod_include
================

Apache mod_include fork
This fork has the intent to add features in this module to work with Presslab CMS
Fature 1: On include errors return Apache error 500x instead include error msg;


INSTALLATION
============

Installation requires the Apache source tree 

1. copy mod_include.c to [apache source tree]/httpd-2.4.x/modules/filters
2. `apxs -ci [apache source tree]/httpd-2.4.x/modules/filters/mod_include.c`
3. change Directory or Location Apache VirtualHost configuration to add 'SSIErrorParser [on|off]'
4. restart Apache daemon


