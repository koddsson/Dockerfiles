# Dockerfiles

Currently my Dockerfile are based off debian:jessie rather than ubuntu since I
think that those images are smaller. If anyone knows any different please let
me know.

## The images
* docker-debian-nodejs
  * A Debian Jessie image with node.js v.0.10.26 and npm.
* xen-orchestra
  * A Debian Jessie image (the base image is the docker-debian-nodejs image
    above) running xen-orchestra on port 80. Check it out at
    [xen-orchestra.com](https://xen-orchestra.com/).
