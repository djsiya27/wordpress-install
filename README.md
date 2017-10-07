# WordPress install using Docker and Composer

- Requirements
- Install
- Uninstall

## Requirements

- Docker Machine (Optional)
- Docker
- Docker Compose
- Composer

## Install

### Docker Machine (Optional)

Create and set the docker machine to the current shell

```
$ docker-machine create wordpress-install
$ docker-machine env wordpress-install
$ eval $(docker-machine env wordpress-install)
```
### Composer

### Docker Compose

## Uninstall

### Remove Docker Machine (Optional)

This will remove the Docker machine, delete any Docker images and containers
```
$ docker-machine rm -f wordpress-install
```

### Remove containers

### Remove images
