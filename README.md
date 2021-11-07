# Netzwerk-NRW neos website

This repository is a [Neos](https://www.neos.io/) distribution with site package containing the Neos CMS website [netzwerk-nrw.info](https://www.netzwerk-nrw.info).

Feel free to use the site package as base / template for your own Neos website.

## How to run

### Restrictions

Not tested on Windows.

### Prerequirements

- Docker
- npm

### Start

Follow these steps:
1. Clone repository
2. Run `./docker-compose.sh update` to use a dockerized composer (you do not have to install it locally!) and install all dependencies
3. Run `docker-compose up` (or `docker-compose up -d` for running process in background) to start up the Docker containers (Neos app + MariaDB)
4. Run `cd DistributionPackages/NetzwerkNRW.Site/Resources/Public/Frontend && npm install && npm start` to start up the [Bulma](https://bulma.io/) SCSS/JS watcher
5. Browse to http://127.0.0.1:8081 and follow the set-up instructions. For database access, enter the docker container name + username "root" and password "db"
