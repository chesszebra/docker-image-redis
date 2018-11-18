# docker-image-redis

[![Build Status](https://travis-ci.org/chesszebra/docker-image-redis.svg?branch=master)](https://travis-ci.org/chesszebra/docker-image-redis)

A Docker image that runs a Redis server.

## Usage

```bash
docker pull chesszebra/redis
```

In docker-compose.yml:

```
volumes:
  volume-redis:

services:
  redis-server:
    image: chesszebra/redis
    volumes:
      - volume-redis:/data
```
