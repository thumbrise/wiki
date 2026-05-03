---
page_id: 'concept:host'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: host
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - 27-build-link-runtime-2e7dc35f
  - docker-compose-96d71fcb
  - dockerfile-6442cd3d
  - local-2004a734
  - local-ini-4b243f68
project_ids: []
node_ids:
  - 'concept:host'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.849Z'
updated_at: '2026-05-03T05:32:23.365Z'
compiled_from:
  - 27-build-link-runtime-2e7dc35f
  - docker-compose-96d71fcb
  - dockerfile-6442cd3d
  - local-2004a734
  - local-ini-4b243f68
managed_by: system
backlinks:
  - 'source:27-build-link-runtime-2e7dc35f'
  - 'source:docker-compose-96d71fcb'
  - 'source:dockerfile-6442cd3d'
  - 'source:local-2004a734'
  - 'source:local-ini-4b243f68'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  27-build-link-runtime-2e7dc35f: 2e7dc35f05845b25457fe80f57746ca1470e46811de2d35b57e062135098f531
  docker-compose-96d71fcb: 96d71fcbdbd666a33926a32e539a16943fe7eec4c3fd505fe4d1ea4720aabc12
  dockerfile-6442cd3d: 6442cd3dc65d5cad222daa63716edbe249378c1c515eb8f3f7f678744ccda257
  local-2004a734: 2004a734001f1d94282bdbe05962f099909ed613ad330f53b9c049f44c6a15df
  local-ini-4b243f68: 4b243f682b6769f98cd5e2277f7f0de4e1a6d87bc349c3d8f9b329d5945d6e7a
source_semantic_hashes:
  27-build-link-runtime-2e7dc35f: 7aa621b01b4ee6e1aecaebdd211a3c6827953fce17f5f8e654c5b60321423a24
  docker-compose-96d71fcb: 96d71fcbdbd666a33926a32e539a16943fe7eec4c3fd505fe4d1ea4720aabc12
  dockerfile-6442cd3d: 6442cd3dc65d5cad222daa63716edbe249378c1c515eb8f3f7f678744ccda257
  local-2004a734: 2004a734001f1d94282bdbe05962f099909ed613ad330f53b9c049f44c6a15df
  local-ini-4b243f68: 4b243f682b6769f98cd5e2277f7f0de4e1a6d87bc349c3d8f9b329d5945d6e7a
---
# host

## Summary

Frequently referenced concept in #27 — Build, Link, Runtime.

## Seen In

- [[sources/27-build-link-runtime-2e7dc35f|#27 — Build, Link, Runtime]]
- [[sources/docker-compose-96d71fcb|docker-compose]]
- [[sources/dockerfile-6442cd3d|Dockerfile]]
- [[sources/local-2004a734|local]]
- [[sources/local-ini-4b243f68|local.ini]]

## Source Claims

- docker-compose Format: YAML Top-level: object Size: 3 Nested depth: 5 ## Schema - name: string - services: object (2 keys) - volumes: object (1 keys) ## Preview yaml name: "op_poc_spiral-emit" services: php: build: args: DOCKER_HOST_UID: ${DOCKER_HOST_UID:?} DOCKER_HOST_GID: ${DOCKER_HOST_GID:?} context: ./ environment: TZ: "Europe/Moscow" XDG_CONFIG_HOME: "/var/www/.xdg" user: ${DOCKER_HOST_UID:?} extra_hosts: - "host.docker.internal:host-gateway" volumes: - ./:/var/www - ./.docker/php/conf.d/app.ini:/usr/local/etc/php/conf.d/app.ini - ./.docker/php/custom.d/:/usr/local/etc/php/custom.d/ - composer-cache:/composer working_dir: /var/www roadrunner: extends: service: php command: - sh - -c - | if [ ! [source:docker-compose-96d71fcb]
- FROM php:8.3-cli ADD --chmod=0755 https://github.com/mlocati/docker-php-extension-installer/releases/download/2.7.5/install-php-extensions /usr/local/bin/ RUN apt-get update && apt-get install -y --no-install-recommends \ unzip \ git \ && rm -rf /var/lib/apt/lists/* RUN install-php-extensions \ @composer-2.8.5 \ sockets \ mbstring \ intl \ pcntl \ opcache \ xdebug ARG DOCKER_HOST_UID ARG DOCKER_HOST_GID RUN set -xe \ && delgroup dialout \ && groupadd --gid "$DOCKER_HOST_GID" app \ && useradd --uid "$DOCKER_HOST_UID" --gid "$DOCKER_HOST_GID" --create-home --shell /bin/bash app USER $DOCKER_HOST_UID:$DOCKER_HOST_GID WORKDIR /var/www EXPOSE 8080 [source:dockerfile-6442cd3d]
- local Format: INI Top-level: object Size: 8 Nested depth: 1 ## Schema - xdebug.mode: string - xdebug.client_host: string - xdebug.client_port: string - xdebug.start_with_request: string - xdebug.discover_client_host: string - xdebug.log_level: string - xdebug.log: string - xdebug.idekey: string ## Preview ini xdebug.mode=debug xdebug.client_host=host.docker.internal xdebug.client_port=9003 xdebug.start_with_request=trigger xdebug.discover_client_host=1 xdebug.log_level=0 xdebug.log="/var/www/runtime/xdebug.log" xdebug.idekey=PHPSTORM [source:local-2004a734]
- xdebug.mode=debug xdebug.client_host=host.docker.internal xdebug.client_port=9003 xdebug.start_with_request=trigger xdebug.discover_client_host=1 xdebug.log_level=0 xdebug.log="/var/www/html/xdebug.log" xdebug.idekey=PHPSTORM [source:local-ini-4b243f68]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

