---
page_id: 'source:dockerfile-6442cd3d'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: Dockerfile
source_class: first_party
tags:
  - source
source_ids:
  - dockerfile-6442cd3d
project_ids: []
node_ids:
  - 'source:dockerfile-6442cd3d'
  - 'concept:docker'
  - 'concept:host'
  - 'concept:install'
  - 'concept:0755'
  - 'concept:3-cli'
  - 'concept:8080'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T05:11:46.018Z'
updated_at: '2026-05-03T05:32:23.219Z'
compiled_from:
  - dockerfile-6442cd3d
managed_by: system
backlinks:
  - 'concept:docker'
  - 'concept:host'
  - 'concept:install'
  - 'concept:0755'
  - 'concept:3-cli'
  - 'concept:8080'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dockerfile-6442cd3d: 6442cd3dc65d5cad222daa63716edbe249378c1c515eb8f3f7f678744ccda257
source_semantic_hashes:
  dockerfile-6442cd3d: 6442cd3dc65d5cad222daa63716edbe249378c1c515eb8f3f7f678744ccda257
---
# Dockerfile

Source ID: `dockerfile-6442cd3d`
Source Kind: `text`
Source Path: `/Users/rk/GolandProjects/op/poc/spiral-emit/Dockerfile`

Source Class: `first_party`


## Summary

FROM php:8.3-cli ADD --chmod=0755 https://github.com/mlocati/docker-php-extension-installer/releases/download/2.7.5/install-php-extensions /usr/local/bin/ RUN apt-get update && apt-get install -y --no-install-recommends \ unzip \ git \ && rm -rf /var/lib/apt/lists/* RUN install-php-extensions \ @composer-2.8.5 \ sockets \ mbstring \ intl \ pcntl \ opcache \ xdebug ARG DOCKER_HOST_UID ARG DOCKER_HOST_GID RUN set -xe \ && delgroup dialout \ && groupadd --gid "$DOCKER_HOST_GID" app \ && useradd --uid "$DOCKER_HOST_UID" --gid "$DOCKER_HOST_GID" --create-home --shell /bin/bash app USER $DOCKER_HOST_UID:$DOCKER_HOST_GID WORKDIR /var/www EXPOSE 8080

## Concepts

- [[concepts/docker|docker]]: Frequently referenced concept in Dockerfile.
- [[concepts/host|host]]: Frequently referenced concept in Dockerfile.
- [[concepts/install|install]]: Frequently referenced concept in Dockerfile.
- [[concepts/0755|0755]]: Frequently referenced concept in Dockerfile.
- [[concepts/3-cli|3-cli]]: Frequently referenced concept in Dockerfile.
- [[concepts/8080|8080]]: Frequently referenced concept in Dockerfile.

## Entities

- None detected.

## Claims

- FROM php:8.3-cli ADD --chmod=0755 https://github.com/mlocati/docker-php-extension-installer/releases/download/2.7.5/install-php-extensions /usr/local/bin/ RUN apt-get update && apt-get install -y --no-install-recommends \ unzip \ git \ && rm -rf /var/lib/apt/lists/* RUN install-php-extensions \ @composer-2.8.5 \ sockets \ mbstring \ intl \ pcntl \ opcache \ xdebug ARG DOCKER_HOST_UID ARG DOCKER_HOST_GID RUN set -xe \ && delgroup dialout \ && groupadd --gid "$DOCKER_HOST_GID" app \ && useradd --uid "$DOCKER_HOST_UID" --gid "$DOCKER_HOST_GID" --create-home --shell /bin/bash app USER $DOCKER_HOST_UID:$DOCKER_HOST_GID WORKDIR /var/www EXPOSE 8080 [source:dockerfile-6442cd3d]

## Questions

- How does docker relate to Dockerfile?
- How does host relate to Dockerfile?
- How does install relate to Dockerfile?

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

