Heroku buildpack: Stamp
=======================

Sets two ENV variables

* ENV['SOURCE_VERSION'] - a git SHA for the deployed version
* ENV['BUILD_TIMESTAMP'] - a formatted timestamp of the build time

Getting started
-----

    $ heroku create --buildpack http://github.com/easelinc/heroku-buildpack-stamp.git
