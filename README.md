# Drupal + vuejs todo
[![Build Status](https://travis-ci.org/alvar0hurtad0/drupal-vuejs-todo.svg?branch=master)](https://travis-ci.org/alvar0hurtad0/drupal-vuejs-todo)

This project is based on [drupal-composer/drupal-project](https://github.com/drupal-composer/drupal-project)

## Install backend

 * Make sure you have composer and all the stuff to run a drupal on you host. PHP 7.1 or higher is required
  (https://www.drupal.org/docs/8/system-requirements)
 * Copy `\example.settings.local.php` into `settings.local.php` and customize the values (at least related with database) 
 * Run `composer project-install`
 * Make all the changes required for your webserver to make `http://drupal-vue-todo.localhost` serve the `web` folder of this repo.

## Install frontend
 * Make sure you have node and yarn installed on your host
 * Go to `frontend` folder
 * run `yarn install`
 * run `yarn dev`

## Troubleshooting
### I can't serve the drupal in http://drupal-vue-todo.localhost
Just change the {BASE_API_URL} here: https://github.com/alvar0hurtad0/drupal-vuejs-todo/blob/master/frontend/webpack.config.js#L91

### I'm very interested but I can't do it run
I can provide some basic suppor on twitter: https://twitter.com/alvar0hurtad0
