# dockerized-docs-wiredtiger

# What is it?#
Dockerzied Wiredtiger site + developer documentation for offline use.

# Image description #
Base image: `httpd:2.4.23-alpine`.
The most current wiredtiger.github.com `master` branch is cloned.
Wiredtiger ocumentation directory (`/wiredtiger.github.com`) is linked to httpd `DocumentRoot` (`/usr/local/apache2/htdocs`).

# How to use this image #

```console
$ docker run -d genadipost/dockerized-docs-wiredtiger

```

You can test it by visiting http://container-ip:80
