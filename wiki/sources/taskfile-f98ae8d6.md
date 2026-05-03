---
page_id: 'source:taskfile-f98ae8d6'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: Taskfile
source_class: first_party
tags:
  - source
source_ids:
  - taskfile-f98ae8d6
project_ids: []
node_ids:
  - 'source:taskfile-f98ae8d6'
  - 'concept:desc'
  - 'concept:docker'
  - 'concept:task'
  - 'concept:object'
  - 'concept:schema'
  - 'concept:bash'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T05:11:46.062Z'
updated_at: '2026-05-03T05:32:23.280Z'
compiled_from:
  - taskfile-f98ae8d6
managed_by: system
backlinks:
  - 'concept:desc'
  - 'concept:docker'
  - 'concept:task'
  - 'concept:object'
  - 'concept:schema'
  - 'concept:bash'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  taskfile-f98ae8d6: f98ae8d6dc3cd54def5c849666e49c7e28626b64e252ab0317e60019a677d5fc
source_semantic_hashes:
  taskfile-f98ae8d6: f98ae8d6dc3cd54def5c849666e49c7e28626b64e252ab0317e60019a677d5fc
---
# Taskfile

Source ID: `taskfile-f98ae8d6`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/op/poc/spiral-emit/Taskfile.yml`

Source Class: `first_party`


## Source Details

- format: yaml
- top level type: object
- top level size: 4
- nested depth: 3


## Summary

Taskfile Format: YAML Top-level: object Size: 4 Nested depth: 3 ## Schema - version: string - env: object (2 keys) - dotenv: array (1 items) - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' env: DOCKER_HOST_UID: sh: id -u DOCKER_HOST_GID: sh: id -g dotenv: [ '.env', ] tasks: c: desc: docker compose и аргументы. Рабочий пример [task c -- up -d]. -- обязательно.

## Concepts

- [[concepts/desc|desc]]: Frequently referenced concept in Taskfile.
- [[concepts/docker|docker]]: Frequently referenced concept in Taskfile.
- [[concepts/task|task]]: Frequently referenced concept in Taskfile.
- [[concepts/object|object]]: Frequently referenced concept in Taskfile.
- [[concepts/schema|schema]]: Frequently referenced concept in Taskfile.
- [[concepts/bash|bash]]: Frequently referenced concept in Taskfile.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in Taskfile.
- [[entities/top|Top-]]: Named entity mentioned in Taskfile.
- [[entities/size|Size:]]: Named entity mentioned in Taskfile.
- [[entities/nested|Nested]]: Named entity mentioned in Taskfile.
- [[entities/schema|Schema -]]: Named entity mentioned in Taskfile.
- [[entities/preview|Preview]]: Named entity mentioned in Taskfile.

## Claims

- Taskfile Format: YAML Top-level: object Size: 4 Nested depth: 3 ## Schema - version: string - env: object (2 keys) - dotenv: array (1 items) - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' env: DOCKER_HOST_UID: sh: id -u DOCKER_HOST_GID: sh: id -g dotenv: [ '.env', ] tasks: c: desc: docker compose и аргументы. [source:taskfile-f98ae8d6]
- Рабочий пример [task c -- up -d]. [source:taskfile-f98ae8d6]
- -- обязательно. [source:taskfile-f98ae8d6]
- cmd: docker compose {{.CLI_ARGS}} bash: desc: Войти в терминал app. [source:taskfile-f98ae8d6]

## Questions

- How does desc relate to Taskfile?
- How does docker relate to Taskfile?
- How does task relate to Taskfile?

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

