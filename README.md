# baseimage [![Docker Automated build](https://img.shields.io/docker/automated/andrexus/baseimage.svg)](https://hub.docker.com/r/andrexus/baseimage/) [![Build Status](https://travis-ci.org/andrexus/baseimage.svg?branch=master)](https://travis-ci.org/andrexus/baseimage)


_minimalist docker base image to deploy services and applications._

Image `andrexus/baseimage:latest` designed as a lightweight, ready-to-use base for various services. It adds a few things to the regular [alpine image](https://hub.docker.com/_/alpine/).

* `ENTRYPOINT` runs `CMD` via [dumb-init](https://github.com/Yelp/dumb-init/)
* Packages `tzdata`, `curl` and `openssl`
* Adds user `app` (uid=1001)
