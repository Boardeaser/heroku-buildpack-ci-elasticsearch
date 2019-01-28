Heroku buildpack for installing Elasticsearch inside a dyno
=========================

This is a fork of the official Heroku buildpack for Java.

After the regular installation of Java performed by the original buildpack, it downloads Elasticsearch and installs it.
This buildpack is useful for CI, especially when using Heroku CI Parallel Test Runs. It makes use of the buildpack cache.

License
-------

Licensed under the MIT License. See LICENSE file.
