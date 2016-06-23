Oracle Server JRE 8 Docker image
========================

This image is built on top of the Alpine Linux image, which is only a 5MB image, and contains
[Oracle Server JRE 8](http://www.oracle.com/technetwork/java/javase/downloads/server-jre8-downloads-2133154.html).

This is based on the work at [frol/docker-alpine-oraclejdk8](https://github.com/frol/docker-alpine-oraclejdk8).  The main changes are it pulls down the Oracle Server JRE and makes no changes to the install.  This results in a larger docker container, but there are no concerns with accidentally removing needed files from the Oracle package.  The image is 65MB and the final on disk size is 168MB.
