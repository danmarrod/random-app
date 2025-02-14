# Random-app

[![Build Status](https://travis-ci.org/pjmolina/random-app.svg?branch=master)](https://travis-ci.org/pjmolina/random-app)

[![Known Vulnerabilities](https://snyk.io/test/github/pjmolina/random-app/badge.svg?targetFile=package.json)](https://snyk.io/test/github/pjmolina/random-app?targetFile=package.json)

Demo *Random App* to illustrate some techniques on:
  - TDD
  - CI
  - Containers
  - Inmutable Infrastructure
  - Infrastructure as Code


## Variables de entorno para despliegue Terraform

 - AWS_ACCESS_KEY_ID = identificador de acceso AWS
 - AWS_SECRET_ACCESS_KEY = clave de acceso AWS
 - TF_VAR_PORTAINER_KEY = clave para configurar automáticamente cuenta admin de Portainer

## Install

```sh
npm i
```

## Run

```sh
npm start
```

## Docker build

```sh
./docker-build.sh
```

## Docker run

```sh
./docker-run.sh
```

