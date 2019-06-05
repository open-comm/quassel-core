Static Apache Webserver Configuration
=====================================

Ready to use quassel server docker-compose configuration.

This configuration uses the linuxserver docker image:

* https://www.dockerheart.com/r/linuxserver/quassel-core


## Install

```
# clone repository
git clone https://gitlab.wachter-jud.net/docker/quassel-core.git

# move into directory
cd quassel-core

# start the quassel server
docker-compose up -d
```

### First Time Configuration

After starting the quassel server you need to configure it via the quassel client:

* Start the quassel client on your computer
* Connect quassel client to your server
* You will be guided through the quassel core configuration steps by your client, including:
  * create an administrative account
  * select a database type


## Docker-Compose Usage

```
# start quassel server
docker-compose up -d

# stop quassel server
docker-compose down

# upgrade container
docker-compose pull
```

