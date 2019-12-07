# LAPP built with Docker Compose

## Versions 
* PHP Version 7.3.12
* Apache Version 2.4
* POSTGRESQL version 12

## Config default  
* PostgreSQL PostgreSQL database and password settings are inside the .env file
* Apache2 vhost mapping are within .config / vhosts
* PHP a php file was left in the index to do some stack testing
* Virtualhost /var/www/html

## Images docker repository
* [DockerHub](https://hub.docker.com/u/eriktonon)
* [Github](https://github.com/eriktonon/docker-images)

### other versions of php inside the stack
* [7.0.33](https://github.com/eriktonon/lapp-docker/tree/7.0.33)
* [7.1.32](https://github.com/eriktonon/lapp-docker/tree/7.1.32)
* [7.2.25](https://github.com/eriktonon/lapp-docker/tree/7.2.25)
* [7.3.12](https://github.com/eriktonon/lapp-docker)
* [7.4.0](https://github.com/eriktonon/lapp-docker/tree/7.4.0)


## Installation

```shell 
git clone https://github.com/eriktonon/lapp-docker
cd lapp-docker
docker-compose up -d
```

You can access it via http://localhost.

