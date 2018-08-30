# Craft CMS 2.x Composer base docker image.

[![Docker Automated build](https://img.shields.io/docker/automated/nilsnh/craft-composer-base.svg?style=flat-square)](https://hub.docker.com/r/nilsnh/craft-composer-base/)

Not for use in production, only development. When starting up the user `www-data` is given heightened privileges (usermod uid set to 1000), this was done to help ease local development on Linux.

When building the container installs PHP support for a number of php extensions, including: gd, mcrypt, mysql, imagick, redis and enables mod_rewrite in Apache.

This image builds on the [official docker php image](https://hub.docker.com/_/php/).

## Simple testing

1.  Run `docker run -p 8080:80 --rm -it -v "$PWD/test":/var/www/html/public craft-test`
2.  Visit `localhost:8080` in your browser.
3.  Editing `test/index.php` will affect the output when refreshing the browser.
