# GPII DeveloperSpace

This repository contains the latest drush makefile for use in building a stand-alone instance of the GPII DeveloperSpace site. 

It also includes a sanitized database dump of the content. It is created using [drush sql-sanitize](https://drushcommands.com/drush-7x/sql/sql-sanitize/).

## Issues

* Updating the sanitized version of the databse is not yet fully automated. 
* The make file does not include some of the libraries that are set as dependencies for certain modules. 
* Some libraries and modules have been patched or modified on the staging server. These patches are not yet included in this make file. However, they can be found in the main gpii.net repository at https://github.com/Pushing7/gpii.net.
