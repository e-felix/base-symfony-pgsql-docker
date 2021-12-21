# BASIC SYMFONY/POSTGRESQL DOCKER CONFIGURATION

> With an nginx config file for Heroku deploy

## Usage

### Build images and containers
```sh
docker-composer up -d
docker-composer exec server sh
```

### Run project commands
```sh
composer install
symfony serve -p 8080
```
