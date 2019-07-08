# docker-rvm

💎 base image for ruby images

## Supported tags and respective `Dockerfile` links

* `1.29.8-bionic` _(1.29.7/bionic/Dockerfile)_
* `1.29.7-stretch` _(1.29.7/stretch/Dockerfile)_

## Image Variants

### `bxggs/rvm:<version>-bionic`

* Uses `buildpack-deps:bionic` as its base image
* Uses a tarball of the release specified by `<version>` and installs it as specified in RVM's official [offline install docs][offline]

### `bxggs/rvm:<version>-stretch`

* Uses Debian Stretch as its base image
* Uses a tarball of the release specified by `<version>` and installs it as specified in RVM's official [offline install docs][offline]

## Links

* [GitHub][github]
* [Docker Hub][dockerhub]

[offline]: https://github.com/rvm/rvm-site/blob/master/content/rvm/offline.md
[github]: https://github.com/b-ggs/docker-rvm
[dockerhub]: https://hub.docker.com/r/bxggs/rvm
