# Gradle Build Cache Demo

## Docs

- https://docs.gradle.com/enterprise/admin/current/#build_cache
- https://docs.gradle.org/current/userguide/build_cache.html

## Setup

    docker swarm init
    docker volume create build-cache
    docker stack deploy -c docker-compose.yml gradle
