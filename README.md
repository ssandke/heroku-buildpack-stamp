Heroku buildpack: Stamp
=======================

Sets ENV['RELEASE'] to the released version. Useful for knowing exactly
which version of your app is being served.

NOTE: Simulatenous pushes could result in the incorrect value being
displayed. Please deploy serially.

Getting started
-----

    $ heroku create --buildpack http://github.com/easelinc/heroku-buildpack-stamp.git
