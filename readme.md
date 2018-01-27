# Jeedom Docker

This is an unofficial, open-source and community-driven deployment of Jeedom solution

## Requirements

* Install Docker > 1.12
* Install Docker Compose > 1.11

Before anything, you need to make sure you have Docker properly setup in your environment. For that, refer to the official documentation for both Docker and Docker Compose. 

Also, if you're developing on Mac or Windows – yeah, maybe that's the case –, make sure you have Docker Machine properly setup.

## Warning

Lot of plugin use network broadcast and can not work in a docker container. It is recommended to run Jeedom in VM or physical machine like RPI.

## Usage

You are up and running in 1 step:
```sh
$ docker-compose up  -d 
```
Open in browser: http://localhost:8080/

Database hostname is "db"

User and password are admin/admin

Enjoy!
