---
page_id: 'concept:install'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: install
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - dockerfile-6442cd3d
project_ids: []
node_ids:
  - 'concept:install'
freshness: fresh
status: candidate
confidence: 0.65
created_at: '2026-05-03T05:11:46.135Z'
updated_at: '2026-05-03T05:32:23.409Z'
compiled_from:
  - dockerfile-6442cd3d
managed_by: system
backlinks:
  - 'source:dockerfile-6442cd3d'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dockerfile-6442cd3d: 6442cd3dc65d5cad222daa63716edbe249378c1c515eb8f3f7f678744ccda257
source_semantic_hashes:
  dockerfile-6442cd3d: 6442cd3dc65d5cad222daa63716edbe249378c1c515eb8f3f7f678744ccda257
---
# install

## Summary

Frequently referenced concept in Dockerfile.

## Seen In

- [[sources/dockerfile-6442cd3d|Dockerfile]]

## Source Claims

- FROM php:8.3-cli ADD --chmod=0755 https://github.com/mlocati/docker-php-extension-installer/releases/download/2.7.5/install-php-extensions /usr/local/bin/ RUN apt-get update && apt-get install -y --no-install-recommends \ unzip \ git \ && rm -rf /var/lib/apt/lists/* RUN install-php-extensions \ @composer-2.8.5 \ sockets \ mbstring \ intl \ pcntl \ opcache \ xdebug ARG DOCKER_HOST_UID ARG DOCKER_HOST_GID RUN set -xe \ && delgroup dialout \ && groupadd --gid "$DOCKER_HOST_GID" app \ && useradd --uid "$DOCKER_HOST_UID" --gid "$DOCKER_HOST_GID" --create-home --shell /bin/bash app USER $DOCKER_HOST_UID:$DOCKER_HOST_GID WORKDIR /var/www EXPOSE 8080 [source:dockerfile-6442cd3d]

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

