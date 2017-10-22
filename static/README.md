# Drupalcamp Cebu 2017 - Static

## Info
This static theme uses [Jekyll](https://jekyllrb.com) for better organization and maintainability.

## Requirements
1. [RVM](https://rvm.io) is recommended.
2. Please look at `.ruby-version` for the Ruby version used. It's also ideal to use the same version and RVM can help with that without affecting other project versions.

## Setup
1. Make sure to install [Bundler](http://bundler.io/) first.
2. Run `bundle install` to install the gems needed.
3. Once gem installation is successful, Run `bundle exec jekyll serve`. This will run the Jekyll gem installed for this project.

## Sitemap
* To update the sitemap.xml file to include more than the homepage, run `bundle exec jekyll build`.
* To exclude pages from the sitemap.xml file, just add `sitemap: false` in the Front Matter of the post/page.

Reference: [Jekyll Sitemap Generator Plugin](https://github.com/jekyll/jekyll-sitemap)
