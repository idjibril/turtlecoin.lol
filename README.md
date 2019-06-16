[![Build Status](https://travis-ci.org/turtlecoin/turtlecoin.lol.svg?branch=master)](https://travis-ci.org/turtlecoin/turtlecoin.lol)

# watt.cash

### About

This project uses [Jekyll](https://jekyllrb.com) to generate a static website.

### Setup

1. Make sure you have [Ruby](https://www.ruby-lang.org/en) 2.3 or newer installed.
2. Run `gem install bundler` to install [bundler](http://bundler.io).
3. Run `bundle install` to install the dependencies of this project.
4. Run `bundle exec jekyll serve` to start the development server at `http://localhost:4000`. See [Jekyll documentation](https://jekyllrb.com/docs/home/) for more information.


## Deployment

Commits to `master` auto deploy via Travis CI to GitHub pages.

### Deploying manually

* `./scripts/build.sh`
* `./scripts/deploy.sh` 


## Localization

All translations live in the `_i18n` folder.

### Adding a new language

* Create a fork of this repository.
* Create a copy of `_i18n/en.yml` and name the file after the locale.
* Replace the English text with the translated version.
* Add the language details to the _Localization config_ in `_config.yml`.
* Submit a pull request. Find someone in the community familiar with that language to review it.

### Suggesting changes

* Create a fork of this repository.
* Find the right language in `_i18n`.
* Make your change. Submit a pull request.
* Ping the contributors of your language from below for a review.
