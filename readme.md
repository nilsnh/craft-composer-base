# Craft CMS 2.x Composer base docker image.

Not for use in production. This is a development image for use when developing
locally. When building the container installs PHP support for: gd, mcrypt, mysql, imagick, redis and
enables mod_rewrite in Apache.

This image builds on the [official docker php image](https://hub.docker.com/_/php/).
