# Opal Website

This repo holds the source of the [opalrb.org](http://opalrb.org/) website.

## Preparing

Clone this repo, and use bundler to get dependencies:

    $ bundle install

The website is built using [middleman](https://middlemanapp.com/).

## Run site/server

    $ bundle exec middleman server

Then visit `http://localhost:4567`.

## Publishing

    $ rake publish

