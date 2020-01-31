# meso-infrastructure

This repository holds logic / configuration files for deploying the meso platform on-prem in an ubuntu container.

Specifically it contains the following things:
- `config`: This folder is used to store any https configuration, and nginx configurations.
- `docker-compose.production.yml` The current copy of `docker-compose.yml` that we're using for production.
- `docker-compose.staging.yml` The current copy of `docker-compose.yml` that we're using for staging (in ec2).
- `init_letsencrypt.sh` A script that's run in order to generate a certificate automatically in order to get https working. This is taken directly from `https://github.com/wmnnd/nginx-certbot`


Instructions for how to set up the meso backend (with https, seed data, etc) on a Ubuntu box are in this doc:
https://docs.google.com/document/u/3/d/1LLBVZ_7XYROmF1Pi5QJEdYQ6gdY64uyAts-WTZ7XNlY/edit?usp=drive_web&ouid=108715148367395448292

