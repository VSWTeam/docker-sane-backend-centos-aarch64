## SANE Backend (with libusb1.0) build environment (CentOS - aarch64) Dockerfile


### Base Docker Image

* [centos:7](https://hub.docker.com/_/centos/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download : `docker pull vswteam/sane-backend-centos-aarch64`


### Usage

    docker run -it -v <sane-backend-volume>:/root/project vswteam/sane-backend-centos-aarch64 /bin/bash