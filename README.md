# docker-rvm

💎 base image for ruby images

## Supported tags and respective `Dockerfile` links

* `1.29.12-focal`
* `1.29.12-bionic`
* `1.29.11-focal`
* `1.29.11-bionic`
* `1.29.10-focal`
* `1.29.10-bionic`
* `1.29.9-focal`
* `1.29.9-bionic`
* `1.29.8-focal`
* `1.29.8-bionic`

## Image Variants

### `indineroengineering/rvm:<version>-focal`

* Uses `buildpack-deps:focal` as its base image
* Uses a tarball of the release specified by `<version>` and installs it as specified in RVM's official [offline install docs][offline]

### `indineroengineering/rvm:<version>-bionic`

* Uses `buildpack-deps:bionic` as its base image
* Uses a tarball of the release specified by `<version>` and installs it as specified in RVM's official [offline install docs][offline]

## Links

* [GitHub][github]
* [Docker Hub][dockerhub]

[offline]: https://github.com/rvm/rvm-site/blob/master/content/rvm/offline.md
[github]: https://github.com/inDinero/docker-rvm
[dockerhub]: https://hub.docker.com/r/indineroengineering/rvm
