## Docker Php + Apache + Composer


This repository contains **Dockerfile** of Php, Apache and Composer for [Docker](https://www.docker.io/)'s published to the public [Docker Registry](https://index.docker.io/).


### Installation

1. Install [Docker](https://www.docker.io/).

2. Download [trusted build](https://index.docker.io/u/dynaum/php-apache-composer/) from public [Docker Registry](https://index.docker.io/): `docker pull dynaum/php-apache-composer`

   (alternatively, you can build an image from Dockerfile: `docker build -t="dynaum/php-apache-composer" github.com/dynaum/php-apache-composer`)


### Usage

    docker run -it --rm --name my-app -v "$(pwd)":/var/www/html dynaum/php-apache-composer
