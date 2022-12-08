# brentlab_straindb

[![Build Status](https://travis-ci.org/cmatKhan/brentlab_straindb.svg?branch=master)](https://travis-ci.org/cmatKhan/brentlab_straindb)
[![Built with](https://img.shields.io/badge/Built_with-Cookiecutter_Django_Rest-F7B633.svg)](https://github.com/agconti/cookiecutter-django-rest)

A DRF database to store Brent lab strain data . Check out the project's [documentation](http://cmatKhan.github.io/brentlab_straindb/).

# Prerequisites

- [Docker](https://docs.docker.com/docker-for-mac/install/)  

# Local Development

Start the dev server for local development:
```bash
docker-compose up
```

Run a command inside the docker container:

```bash
docker-compose run --rm web [command]
```
