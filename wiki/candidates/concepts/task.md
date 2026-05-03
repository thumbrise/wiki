---
page_id: 'concept:task'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: task
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - taskfile-f98ae8d6
project_ids: []
node_ids:
  - 'concept:task'
freshness: fresh
status: candidate
confidence: 0.65
created_at: '2026-05-03T05:11:46.184Z'
updated_at: '2026-05-03T05:32:23.491Z'
compiled_from:
  - taskfile-f98ae8d6
managed_by: system
backlinks:
  - 'source:taskfile-f98ae8d6'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  taskfile-f98ae8d6: f98ae8d6dc3cd54def5c849666e49c7e28626b64e252ab0317e60019a677d5fc
source_semantic_hashes:
  taskfile-f98ae8d6: f98ae8d6dc3cd54def5c849666e49c7e28626b64e252ab0317e60019a677d5fc
---
# task

## Summary

Frequently referenced concept in Taskfile.

## Seen In

- [[sources/taskfile-f98ae8d6|Taskfile]]

## Source Claims

- Taskfile Format: YAML Top-level: object Size: 4 Nested depth: 3 ## Schema - version: string - env: object (2 keys) - dotenv: array (1 items) - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' env: DOCKER_HOST_UID: sh: id -u DOCKER_HOST_GID: sh: id -g dotenv: [ '.env', ] tasks: c: desc: docker compose и аргументы. [source:taskfile-f98ae8d6]
- Рабочий пример [task c -- up -d]. [source:taskfile-f98ae8d6]

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

