# Dante

Dante serves as an example of a fully-functioning implementation of [Bookshop 3.0](https://github.com/CloudCannon/bookshop) on a simple website.

![Dante template screenshot](site/images/_screenshot.png)

[![Deploy to CloudCannon](https://buttons.cloudcannon.com/deploy.svg)](https://app.cloudcannon.com/register#sites/connect/github/CloudCannon/dante-jekyll-bookshop-template)

## Features

* Live editing with [CloudCannon](http://cloudcannon.com/)
* Component library for website building
* Fully configurable Website
* Pre-built pages
* Pre-styled components
* Blog
* Portfolio
* Staff and author system
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* Search engine optimisation

## Setup

Dante was built with [Jekyll](http://jekyllrb.com/) version 4.2.0, but should support newer versions as well.

Install the dependencies for Bookshop:

~~~bash
$ npm install
~~~

Install the Jekyll dependencies with [Bundler](http://bundler.io/):

~~~bash
$ cd site
$ bundle install
~~~

Run the website:

~~~bash
$ cd ../
$ npm start
~~~

## Editing

Dante is already optimised for adding, updating and removing pages, and components within CloudCannon.

### Posts

* Add, update or remove a post in the *Posts* collection.
* The **Author Staff Member** field links to members in the **Staff Members** collection.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Forms

* The contact form isn't connected to any backend allowing you connect to your provider of choice. As this template is configured for CloudCannon we would reccomend using CloudCannon as your contact form provider. Documentation can be found here: https://cloudcannon.com/documentation/articles/creating-a-form-for-your-site-on-cloudcannon/ 

### Staff Members

* Reused around the site to save multiple editing locations.

### Navigation

* Managed as a data file to give clients better access.
* Set in the *Data > Navigation* section.

### Footer

* Managed as a data file to give clients better access.
* Set in the *Data > Footer* section.


