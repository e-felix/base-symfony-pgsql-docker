# BASIC SYMFONY/POSTGRESQL DOCKER CONFIGURATION

> With a nginx config file for Heroku deploy

## Usage

> Prior to running the commands, copy your project in the same folder of the `docker-compose.yml` file.

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
