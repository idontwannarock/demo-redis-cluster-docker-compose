# Intro

This project is to create a Redis Cluster.

## Pre-requisite

- Docker Engine
- Docker Compose

## Usage

```cmd
docker compose up -d
```

The default master nodes are:

- 127.0.0.1:7000
- 127.0.0.1:7001
- 127.0.0.1:7002

## Reference

- [Scaling with Redis Cluster](https://redis.io/docs/manual/scaling/)
- [Redis Cluster 介紹](https://isdaniel.github.io/redis-cluster-introduce-01/)
- [How to use Redis Cluster for caching](https://bpaulino.com/entries/how-to-use-redis-cluster-for-caching)
- [Github brunojppb/redis-cluster-demo](https://github.com/brunojppb/redis-cluster-demo)
- [Github mnadeem/local-redis-cluster](https://github.com/mnadeem/local-redis-cluster)
- [Building Redis Cluster with docker-compose](https://pierreabreu.medium.com/building-redis-cluster-with-docker-compose-9569ddb6414a)
