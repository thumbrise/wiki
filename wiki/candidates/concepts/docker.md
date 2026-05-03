---
page_id: 'concept:docker'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: docker
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - docker-compose-96d71fcb
  - dockerfile-6442cd3d
  - gitignore-b836fd5b
  - taskfile-f98ae8d6
project_ids: []
node_ids:
  - 'concept:docker'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T05:11:46.134Z'
updated_at: '2026-05-03T05:32:23.407Z'
compiled_from:
  - docker-compose-96d71fcb
  - dockerfile-6442cd3d
  - gitignore-b836fd5b
  - taskfile-f98ae8d6
managed_by: system
backlinks:
  - 'source:docker-compose-96d71fcb'
  - 'source:dockerfile-6442cd3d'
  - 'source:gitignore-b836fd5b'
  - 'source:taskfile-f98ae8d6'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  docker-compose-96d71fcb: 96d71fcbdbd666a33926a32e539a16943fe7eec4c3fd505fe4d1ea4720aabc12
  dockerfile-6442cd3d: 6442cd3dc65d5cad222daa63716edbe249378c1c515eb8f3f7f678744ccda257
  gitignore-b836fd5b: b836fd5ba7bf40e4d13eef30d437f7dfae9e92d8ad4ffe6a1156779842ccf1d5
  taskfile-f98ae8d6: f98ae8d6dc3cd54def5c849666e49c7e28626b64e252ab0317e60019a677d5fc
source_semantic_hashes:
  docker-compose-96d71fcb: 96d71fcbdbd666a33926a32e539a16943fe7eec4c3fd505fe4d1ea4720aabc12
  dockerfile-6442cd3d: 6442cd3dc65d5cad222daa63716edbe249378c1c515eb8f3f7f678744ccda257
  gitignore-b836fd5b: b836fd5ba7bf40e4d13eef30d437f7dfae9e92d8ad4ffe6a1156779842ccf1d5
  taskfile-f98ae8d6: f98ae8d6dc3cd54def5c849666e49c7e28626b64e252ab0317e60019a677d5fc
---
# docker

## Summary

Frequently referenced concept in docker-compose.

## Seen In

- [[sources/docker-compose-96d71fcb|docker-compose]]
- [[sources/dockerfile-6442cd3d|Dockerfile]]
- [[sources/gitignore-b836fd5b|.gitignore]]
- [[sources/taskfile-f98ae8d6|Taskfile]]

## Source Claims

- docker-compose Format: YAML Top-level: object Size: 3 Nested depth: 5 ## Schema - name: string - services: object (2 keys) - volumes: object (1 keys) ## Preview yaml name: "op_poc_spiral-emit" services: php: build: args: DOCKER_HOST_UID: ${DOCKER_HOST_UID:?} DOCKER_HOST_GID: ${DOCKER_HOST_GID:?} context: ./ environment: TZ: "Europe/Moscow" XDG_CONFIG_HOME: "/var/www/.xdg" user: ${DOCKER_HOST_UID:?} extra_hosts: - "host.docker.internal:host-gateway" volumes: - ./:/var/www - ./.docker/php/conf.d/app.ini:/usr/local/etc/php/conf.d/app.ini - ./.docker/php/custom.d/:/usr/local/etc/php/custom.d/ - composer-cache:/composer working_dir: /var/www roadrunner: extends: service: php command: - sh - -c - | if [ ! [source:docker-compose-96d71fcb]
- FROM php:8.3-cli ADD --chmod=0755 https://github.com/mlocati/docker-php-extension-installer/releases/download/2.7.5/install-php-extensions /usr/local/bin/ RUN apt-get update && apt-get install -y --no-install-recommends \ unzip \ git \ && rm -rf /var/lib/apt/lists/* RUN install-php-extensions \ @composer-2.8.5 \ sockets \ mbstring \ intl \ pcntl \ opcache \ xdebug ARG DOCKER_HOST_UID ARG DOCKER_HOST_GID RUN set -xe \ && delgroup dialout \ && groupadd --gid "$DOCKER_HOST_GID" app \ && useradd --uid "$DOCKER_HOST_UID" --gid "$DOCKER_HOST_GID" --create-home --shell /bin/bash app USER $DOCKER_HOST_UID:$DOCKER_HOST_GID WORKDIR /var/www EXPOSE 8080 [source:dockerfile-6442cd3d]
- / !/.docker !/.github /vendor /runtime/ /runtime/ /rr /protoc-gen-php-grpc /.env /*.cache [source:gitignore-b836fd5b]
- Taskfile Format: YAML Top-level: object Size: 4 Nested depth: 3 ## Schema - version: string - env: object (2 keys) - dotenv: array (1 items) - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' env: DOCKER_HOST_UID: sh: id -u DOCKER_HOST_GID: sh: id -g dotenv: [ '.env', ] tasks: c: desc: docker compose и аргументы. [source:taskfile-f98ae8d6]
- cmd: docker compose {{.CLI_ARGS}} bash: desc: Войти в терминал app. [source:taskfile-f98ae8d6]

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

