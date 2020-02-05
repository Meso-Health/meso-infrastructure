# meso-infrastructure

This repository holds logic and configuration files for deploying the Meso platform via docker-compose

Specifically it contains the following things:
- `config`: Contains nginx configuration file templates
- `docker-compose.production.yml` - Configuration for deploying the platform to a production environment
- `docker-compose.staging.yml` - Configuration for deploying the platform to a staging environment
- `init_letsencrypt.sh` A script to generate an SSL/TLS certificate using the Let's Encrypt service - it is based off of the following repository: `https://github.com/wmnnd/nginx-certbot`
