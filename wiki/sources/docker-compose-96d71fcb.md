---
page_id: 'source:docker-compose-96d71fcb'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: docker-compose
source_class: first_party
tags:
  - source
source_ids:
  - docker-compose-96d71fcb
project_ids: []
node_ids:
  - 'source:docker-compose-96d71fcb'
  - 'concept:docker'
  - 'concept:host'
  - 'concept:composer'
  - 'concept:object'
  - 'concept:volumes'
  - 'concept:8080'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T05:11:46.018Z'
updated_at: '2026-05-03T05:32:23.219Z'
compiled_from:
  - docker-compose-96d71fcb
managed_by: system
backlinks:
  - 'concept:docker'
  - 'concept:host'
  - 'concept:composer'
  - 'concept:object'
  - 'concept:volumes'
  - 'concept:8080'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  docker-compose-96d71fcb: 96d71fcbdbd666a33926a32e539a16943fe7eec4c3fd505fe4d1ea4720aabc12
source_semantic_hashes:
  docker-compose-96d71fcb: 96d71fcbdbd666a33926a32e539a16943fe7eec4c3fd505fe4d1ea4720aabc12
---
# docker-compose

Source ID: `docker-compose-96d71fcb`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/op/poc/spiral-emit/docker-compose.yml`

Source Class: `first_party`


## Source Details

- format: yaml
- top level type: object
- top level size: 3
- nested depth: 5


## Summary

docker-compose Format: YAML Top-level: object Size: 3 Nested depth: 5 ## Schema - name: string - services: object (2 keys) - volumes: object (1 keys) ## Preview yaml name: "op_poc_spiral-emit" services: php: build: args: DOCKER_HOST_UID: ${DOCKER_HOST_UID:?} DOCKER_HOST_GID: ${DOCKER_HOST_GID:?} context: ./ environment: TZ: "Europe/Moscow" XDG_CONFIG_HOME: "/var/www/.xdg" user: ${DOCKER_HOST_UID:?} extra_hosts: - "host.docker.internal:host-gateway" volumes: - ./:/var/www - ./.docker/php/conf.d/app.ini:/usr/local/etc/php/conf.d/app.ini - ./.docker/php/custom.d/:/usr/local/etc/php/custom.d/ - composer-cache:/composer working_dir: /var/www roadrunner: extends: service: php command: - sh - -c - | if [ ! -x ./rr ]; then composer install --no-interaction --prefer-dist chmod +x ./rr fi exec ./rr serve ports: - "8080:8080" volumes: composer-cache:

## Concepts

- [[concepts/docker|docker]]: Frequently referenced concept in docker-compose.
- [[concepts/host|host]]: Frequently referenced concept in docker-compose.
- [[concepts/composer|composer]]: Frequently referenced concept in docker-compose.
- [[concepts/object|object]]: Frequently referenced concept in docker-compose.
- [[concepts/volumes|volumes]]: Frequently referenced concept in docker-compose.
- [[concepts/8080|8080]]: Frequently referenced concept in docker-compose.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in docker-compose.
- [[entities/top|Top-]]: Named entity mentioned in docker-compose.
- [[entities/size|Size:]]: Named entity mentioned in docker-compose.
- [[entities/nested|Nested]]: Named entity mentioned in docker-compose.
- [[entities/schema|Schema -]]: Named entity mentioned in docker-compose.
- [[entities/preview|Preview]]: Named entity mentioned in docker-compose.

## Claims

- docker-compose Format: YAML Top-level: object Size: 3 Nested depth: 5 ## Schema - name: string - services: object (2 keys) - volumes: object (1 keys) ## Preview yaml name: "op_poc_spiral-emit" services: php: build: args: DOCKER_HOST_UID: ${DOCKER_HOST_UID:?} DOCKER_HOST_GID: ${DOCKER_HOST_GID:?} context: ./ environment: TZ: "Europe/Moscow" XDG_CONFIG_HOME: "/var/www/.xdg" user: ${DOCKER_HOST_UID:?} extra_hosts: - "host.docker.internal:host-gateway" volumes: - ./:/var/www - ./.docker/php/conf.d/app.ini:/usr/local/etc/php/conf.d/app.ini - ./.docker/php/custom.d/:/usr/local/etc/php/custom.d/ - composer-cache:/composer working_dir: /var/www roadrunner: extends: service: php command: - sh - -c - | if [ ! [source:docker-compose-96d71fcb]
- -x ./rr ]; then composer install --no-interaction --prefer-dist chmod +x ./rr fi exec ./rr serve ports: - "8080:8080" volumes: composer-cache: [source:docker-compose-96d71fcb]

## Questions

- How does docker relate to docker-compose?
- How does host relate to docker-compose?
- How does composer relate to docker-compose?

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

