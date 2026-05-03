---
page_id: 'concept:cmds'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: cmds
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - taskfile-83d1d929
project_ids: []
node_ids:
  - 'concept:cmds'
freshness: fresh
status: candidate
confidence: 0.65
created_at: '2026-05-03T03:56:35.871Z'
updated_at: '2026-05-03T04:02:08.834Z'
compiled_from:
  - taskfile-83d1d929
managed_by: system
backlinks:
  - 'source:taskfile-83d1d929'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
source_semantic_hashes:
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
---
# cmds

## Summary

Frequently referenced concept in Taskfile.

## Seen In

- [[sources/taskfile-83d1d929|Taskfile]]

## Source Claims

- Taskfile Format: YAML Top-level: object Size: 2 Nested depth: 4 ## Schema - version: string - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' tasks: lint: desc: Run lint with auto-fix where possible (dev workflow) cmds: - golangci-lint run --fix - go tool license-eye header fix lint:ci: desc: Run lint checks without auto-fix (CI workflow) cmds: - golangci-lint run - go tool license-eye header check test: desc: Run tests cmds: - go test ./... [source:taskfile-83d1d929]
- -v generate: desc: Fix license headers aliases: - gen cmds: - go tool license-eye header fix [source:taskfile-83d1d929]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

