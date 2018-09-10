# cogrammar-python

Assessment Python Developer by CoGrammar / Hyperiondev.com

The following tasks are:

## 1. Write a Python script that builds Magic Squares.

* Allow the user to enter N through standard input, where N is any positive odd
integer.
* Check that N is valid and prompt the user to enter another value for N if it is not.●
* Calculate a valid magic square for that value of N
* Print out the magic square, legibly
* Verify that the magic square is indeed valid
* Print “correct” if the verification step passes.

More on README_magic_squares.md

## Build a demo application that integrates with the Dropbox API

A simple application that check if there is secret files inside Dropbox.

More on README_dbx_cleaner.md

## Tell us what you consider important in software development

How I would develop a good web API.

More on README_web_API.md

# Docker

Since I use Docker for development, all my projects use Docker and I keep a Github
repository with a simple structure with Python, Django and Selenium to fasten the
creation of new experiments and always keep my computer clean.

After copy this repository:

`$ cp .env-example .env`

* Add or change you Django Key
* Check if you want to use the standard PSQL folder
* Add your Dropbox key(more on README_dbx_cleaner.md)

`$ docker-compose build`

## tests

`$ docker-compose run --rm django ./manage.py test`
