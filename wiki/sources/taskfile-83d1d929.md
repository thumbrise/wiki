---
page_id: 'source:taskfile-83d1d929'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: Taskfile
source_class: first_party
tags:
  - source
source_ids:
  - taskfile-83d1d929
project_ids: []
node_ids:
  - 'source:taskfile-83d1d929'
  - 'concept:lint'
  - 'concept:cmds'
  - 'concept:desc'
  - 'concept:license'
  - 'concept:header'
  - 'concept:schema'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T03:56:35.836Z'
updated_at: '2026-05-03T05:32:23.280Z'
compiled_from:
  - taskfile-83d1d929
managed_by: system
backlinks:
  - 'concept:lint'
  - 'concept:cmds'
  - 'concept:desc'
  - 'concept:license'
  - 'concept:header'
  - 'concept:schema'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
source_semantic_hashes:
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
---
# Taskfile

Source ID: `taskfile-83d1d929`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/wiki/state/sources/github_repo-thumbrise-op-a16ed6ba/checkout/Taskfile.yaml`

Source Class: `first_party`


## Source Details

- format: yaml
- top level type: object
- top level size: 2
- nested depth: 4


## Summary

Taskfile Format: YAML Top-level: object Size: 2 Nested depth: 4 ## Schema - version: string - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' tasks: lint: desc: Run lint with auto-fix where possible (dev workflow) cmds: - golangci-lint run --fix - go tool license-eye header fix lint:ci: desc: Run lint checks without auto-fix (CI workflow) cmds: - golangci-lint run - go tool license-eye header check test: desc: Run tests cmds: - go test ./... -v generate: desc: Fix license headers aliases: - gen cmds: - go tool license-eye header fix

## Concepts

- [[concepts/lint|lint]]: Frequently referenced concept in Taskfile.
- [[concepts/cmds|cmds]]: Frequently referenced concept in Taskfile.
- [[concepts/desc|desc]]: Frequently referenced concept in Taskfile.
- [[concepts/license|license]]: Frequently referenced concept in Taskfile.
- [[concepts/header|header]]: Frequently referenced concept in Taskfile.
- [[concepts/schema|schema]]: Frequently referenced concept in Taskfile.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in Taskfile.
- [[entities/top|Top-]]: Named entity mentioned in Taskfile.
- [[entities/size|Size:]]: Named entity mentioned in Taskfile.
- [[entities/nested|Nested]]: Named entity mentioned in Taskfile.
- [[entities/schema|Schema -]]: Named entity mentioned in Taskfile.
- [[entities/preview|Preview]]: Named entity mentioned in Taskfile.

## Claims

- Taskfile Format: YAML Top-level: object Size: 2 Nested depth: 4 ## Schema - version: string - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' tasks: lint: desc: Run lint with auto-fix where possible (dev workflow) cmds: - golangci-lint run --fix - go tool license-eye header fix lint:ci: desc: Run lint checks without auto-fix (CI workflow) cmds: - golangci-lint run - go tool license-eye header check test: desc: Run tests cmds: - go test ./... [source:taskfile-83d1d929]
- -v generate: desc: Fix license headers aliases: - gen cmds: - go tool license-eye header fix [source:taskfile-83d1d929]

## Questions

- How does lint relate to Taskfile?
- How does cmds relate to Taskfile?
- How does desc relate to Taskfile?

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

