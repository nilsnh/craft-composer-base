# Craft CMS 2.x Composer base docker image.

[![Docker Automated build](https://img.shields.io/docker/automated/nilsnh/craft-composer-base.svg?style=flat-square)](https://hub.docker.com/r/nilsnh/craft-composer-base/)

Not for use in production. This is a development image for use when developing
locally. When building the container installs PHP support for: gd, mcrypt, mysql, imagick, redis and
enables mod_rewrite in Apache.

This image builds on the [official docker php image](https://hub.docker.com/_/php/).
