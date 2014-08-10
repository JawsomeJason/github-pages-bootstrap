Setup
=======

Based on the following articles and repos:

* [Blogging With Jekyll, Haml and Sass On Github Pages](http://agelber.com/blog/jekyll-haml-sass-on-github-pages/)
* [Compass 1.0](http://beta.compass-style.org/help/)
* [Jekyll Now](https://github.com/barryclark/jekyll-now)

## Local Environment

Run the following to setup your local environment:

```bash
# install required gems
bundle
```

## Jekyll Setup

Edit the [Jekyll configuration](_config.yml)

## Site Content

Create and edit layout, content and post files

## Test Site and Content

Run the following commands to compile your site and test it locally

```bash
# preprocess Haml and SCSS into Github-friendly HTML and CSS
rake build

# start your local Jekyll server
jekyll serve
```

## Publishing

To take your changes live, just push to github