# Drupalcamp Cebu 2017

[![Build Status](https://travis-ci.org/Luukyb/drupalcampcebu2017.svg?branch=develop)](https://travis-ci.org/Luukyb/drupalcampcebu2017)

This project provides all the resources required for the development of the Drupal 8 website for Drupalcamp Cebu 2017.

## Usage

First you need a system to run Drupal according to the requirements on production: Nginx and PHP. Contact [@luukyb](https://github.com/Luukyb) for the exact details. We recommend you to use [Expresso PHP](https://github.com/expresso-php/expresso-php) a quick and simple docker setup for all your PHP development.

You will also need to [install composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx).

## What is inside this repo?

This repo contains:

* drush: Drush aliases and helpers for drush.
* scripts: Scripts used for development and by composer.
* static: Static version of the site. This is used for front-end development, and is symlinked 
  to Drupal's theme.
* web: Those are the files of Drupal 8, and the Drupal theme.

This project is based on [drupal-composer/drupal-project](https://github.com/drupal-composer/drupal-project) 
a Composer template for Drupal projects.

## About this project.

This project is made by the [Drupal Cebu User Group](https://www.facebook.com/groups/drupalcebu/)
and is Open Source under GNU General Public License v2.0.
