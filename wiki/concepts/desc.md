---
page_id: 'concept:desc'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: desc
source_class: first_party
tags:
  - concept
source_ids:
  - taskfile-83d1d929
  - taskfile-f98ae8d6
project_ids: []
node_ids:
  - 'concept:desc'
freshness: fresh
status: active
confidence: 0.8
created_at: '2026-05-03T03:56:35.871Z'
updated_at: '2026-05-03T05:32:23.490Z'
compiled_from:
  - taskfile-83d1d929
  - taskfile-f98ae8d6
managed_by: system
backlinks:
  - 'source:taskfile-83d1d929'
  - 'source:taskfile-f98ae8d6'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
  taskfile-f98ae8d6: f98ae8d6dc3cd54def5c849666e49c7e28626b64e252ab0317e60019a677d5fc
source_semantic_hashes:
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
  taskfile-f98ae8d6: f98ae8d6dc3cd54def5c849666e49c7e28626b64e252ab0317e60019a677d5fc
---
# desc

## Summary

Frequently referenced concept in Taskfile.

## Seen In

- [[sources/taskfile-83d1d929|Taskfile]]
- [[sources/taskfile-f98ae8d6|Taskfile]]

## Source Claims

- Taskfile Format: YAML Top-level: object Size: 2 Nested depth: 4 ## Schema - version: string - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' tasks: lint: desc: Run lint with auto-fix where possible (dev workflow) cmds: - golangci-lint run --fix - go tool license-eye header fix lint:ci: desc: Run lint checks without auto-fix (CI workflow) cmds: - golangci-lint run - go tool license-eye header check test: desc: Run tests cmds: - go test ./... [source:taskfile-83d1d929]
- -v generate: desc: Fix license headers aliases: - gen cmds: - go tool license-eye header fix [source:taskfile-83d1d929]
- Taskfile Format: YAML Top-level: object Size: 4 Nested depth: 3 ## Schema - version: string - env: object (2 keys) - dotenv: array (1 items) - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' env: DOCKER_HOST_UID: sh: id -u DOCKER_HOST_GID: sh: id -g dotenv: [ '.env', ] tasks: c: desc: docker compose и аргументы. [source:taskfile-f98ae8d6]
- cmd: docker compose {{.CLI_ARGS}} bash: desc: Войти в терминал app. [source:taskfile-f98ae8d6]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

