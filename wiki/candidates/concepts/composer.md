---
page_id: 'concept:composer'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: composer
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - docker-compose-96d71fcb
project_ids: []
node_ids:
  - 'concept:composer'
freshness: fresh
status: candidate
confidence: 0.65
created_at: '2026-05-03T05:11:46.135Z'
updated_at: '2026-05-03T05:32:23.408Z'
compiled_from:
  - docker-compose-96d71fcb
managed_by: system
backlinks:
  - 'source:docker-compose-96d71fcb'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  docker-compose-96d71fcb: 96d71fcbdbd666a33926a32e539a16943fe7eec4c3fd505fe4d1ea4720aabc12
source_semantic_hashes:
  docker-compose-96d71fcb: 96d71fcbdbd666a33926a32e539a16943fe7eec4c3fd505fe4d1ea4720aabc12
---
# composer

## Summary

Frequently referenced concept in docker-compose.

## Seen In

- [[sources/docker-compose-96d71fcb|docker-compose]]

## Source Claims

- docker-compose Format: YAML Top-level: object Size: 3 Nested depth: 5 ## Schema - name: string - services: object (2 keys) - volumes: object (1 keys) ## Preview yaml name: "op_poc_spiral-emit" services: php: build: args: DOCKER_HOST_UID: ${DOCKER_HOST_UID:?} DOCKER_HOST_GID: ${DOCKER_HOST_GID:?} context: ./ environment: TZ: "Europe/Moscow" XDG_CONFIG_HOME: "/var/www/.xdg" user: ${DOCKER_HOST_UID:?} extra_hosts: - "host.docker.internal:host-gateway" volumes: - ./:/var/www - ./.docker/php/conf.d/app.ini:/usr/local/etc/php/conf.d/app.ini - ./.docker/php/custom.d/:/usr/local/etc/php/custom.d/ - composer-cache:/composer working_dir: /var/www roadrunner: extends: service: php command: - sh - -c - | if [ ! [source:docker-compose-96d71fcb]
- -x ./rr ]; then composer install --no-interaction --prefer-dist chmod +x ./rr fi exec ./rr serve ports: - "8080:8080" volumes: composer-cache: [source:docker-compose-96d71fcb]

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

