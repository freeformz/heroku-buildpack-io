# What is this?

Build Pack for the [IO Language](http://www.iolanguage.com/)

The first push will suck because cmake, libevent  and IO needs to be compiled.
After that it is cached, at least until the version of IO changes.

# How to use

See [this](https://gist.github.com/fe7f04abbd9538b656c5), the buildpack
url is https://github.com/freeformz/heroku-buildpack-io.git

&tldr;
# Install ruby & rubygems
# gem install heroku
# heroku create -s cedar --buildpack https://github.com/freeformz/heroku-buildpack-io.git

# TODO
- don't cache cmake, just make it when necessary and throw it away
- use a cached install from S3, instead of building.
- deal with 'popular' packaging systems, should one become popular
