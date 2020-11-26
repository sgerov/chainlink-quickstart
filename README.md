# Chainlink node quickstart

This repo serves as the quickest way I found to spin up a chainlink node locally with Docker on kovan testnet.

## Pre-requisites

- Docker and Docker-compose
- Infura.io project created on kovan network

## Usage

* Clone this repo
* Set <PROJECT_ID> to an ID of an infura project you have created in `docker-compose.yml` file.
* Run `docker-compose up -d`
* Access `http://localhost:6688/` and login with `test@test.com`/`..test..`
