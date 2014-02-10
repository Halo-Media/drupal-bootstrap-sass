SASSy Drupal Bootstrap
================

SASS version (w/slight modifications) of the Drupal Bootstrap theme
https://drupal.org/project/bootstrap

###BASIC INSTRUCTIONS:
Install Drupal Bootstrap theme and create a SUBTHEME

Replace the less dir from Drupal Bootstrap SUBTHEME with the sass folder here

Replace 'THEME_NAME' in bower.json with your theme's name - optionally add / remove packages here too

Run bower to generate dependencies

Edit the SUBTHEME.info file to add the Bootstrap scripts - e.g.

scripts[] = 'bower_components/bootstrap-sass/js/affix.js'.
scripts[] = 'bower_components/bootstrap-sass/js/alert.js'.
scripts[] = 'bower_components/bootstrap-sass/js/button.js'.
scripts[] = 'bower_components/bootstrap-sass/js/carousel.js'.
...etc.

or just the minified script

scripts[] = 'bower_components/bootstrap-sass/dist/js/bootstrap.min.js'

Use compass to monitor and build css