Heroku buildpack: Stamp
=======================

Sets ENV['COMMIT_HASH'] to the released git commit id. Useful for
knowing exactly which version of your app is being served.

Getting started
-----

    $ heroku create --buildpack http://github.com/easelinc/heroku-buildpack-stamp.git
