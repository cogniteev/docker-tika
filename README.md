## Docker Tika Dockerfile

This repository contains **Dockerfile** of [Tika](https://tika.apache.org/) for [Docker](https://www.docker.com/) [automated build](https://registry.hub.docker.com/u/cogniteev/tika/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).

### Base Docker Image

* [cogniteev/oracle-java:java8](https://registry.hub.docker.com/cogniteev/oracle-java)

### Installation

1. Install [Docker](https://www.docker.com/)

2. Download [automated build](https://registry.hub.docker.com/u/cogniteev/tika/): `docker pull cogniteev/tika`

### Usage

    docker run cogniteev/tika

* Exposed port is 10000

### Content

Tika API is enriched with  the snacktory implementation of readability. 
Source code is hosted on GitHub, see
[cogniteev/tika](https://github.com/cogniteev/tika) repository.

### License

The `cogniteev/tika` image is licensed under the Apache License, Version 2.0. See LICENSE for full license text.
