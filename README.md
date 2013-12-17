Heroku buildpack: Perl
======================

This is a Heroku buildpack that runs Perl and xls2csv, a Perl script.

Usage
-----

Example usage:

    $ heroku create --stack cedar --buildpack https://github.com/staqapp/heroku-buildpack-perl.git

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Fetching custom buildpack
    -----> Perl/xls2csv app detected
    -----> Installing dependencies

