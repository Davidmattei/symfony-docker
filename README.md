# Symfony 4 simple docker-compose setup

> This is a skeleton with a simple docker setup for symfony **4.2**

## Setup

* macOS Mojave 10.14
* [docker-for-mac](https://docs.docker.com/docker-for-mac/install/) 2.0.0.0-mac81 (29211)
* docker-compose version 1.23.2

## Install
* git clone this repository
* checkout project repository
* update **.gitignore** with project folder
* copy **.env.dist** to **.env** and set DIR variable to project folder


* docker-compose up -d
* docker-compose exec app php bin/console

Info | version
------------ | -------------
PHP | 7.2.13
Nginx | 1.15.8
PostgreSQL | 9.6.11

## Symfony Demo application

[symfony-demo](https://github.com/symfony/demo)

![GitHub Logo](https://github.com/Davidmattei/symfony-docker/blob/master/doc/screenshot.png)







