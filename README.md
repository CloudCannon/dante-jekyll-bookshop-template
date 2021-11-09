# Dante

Dante serves as an example of a fully-functioning implementation of [Bookshop 2.0](https://github.com/CloudCannon/bookshop) on a simple website.

![Dante template screenshot](site/images/_screenshot.png)

Find more templates, themes and step-by-step Jekyll tutorials at [CloudCannon Community](https://cloudcannon.com/community/).

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

* Preconfigured to work with CloudCannon, but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).
* Sends email to the address defined within the component.

### Staff Members

* Reused around the site to save multiple editing locations.

### Navigation

* Managed as a data file to give clients better access.
* Set in the *Data > Navigation* section.

### Footer

* Managed as a data file to give clients better access.
* Set in the *Data > Footer* section.
