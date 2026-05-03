---
page_id: 'concept:allow'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: allow
source_class: first_party
tags:
  - concept
source_ids:
  - golangci-c8766e4f
project_ids: []
node_ids:
  - 'concept:allow'
freshness: fresh
status: active
confidence: 0.65
created_at: '2026-05-03T03:56:35.863Z'
updated_at: '2026-05-03T05:32:23.439Z'
compiled_from:
  - golangci-c8766e4f
managed_by: system
backlinks:
  - 'source:golangci-c8766e4f'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  golangci-c8766e4f: c8766e4f7a3ad850d894ea447959c7e8acda25d36b6aa6274419a7a55abb1ed9
source_semantic_hashes:
  golangci-c8766e4f: c8766e4f7a3ad850d894ea447959c7e8acda25d36b6aa6274419a7a55abb1ed9
---
# allow

## Summary

Frequently referenced concept in .golangci.

## Seen In

- [[sources/golangci-c8766e4f|.golangci]]

## Source Claims

- .golangci Format: YAML Top-level: object Size: 7 Nested depth: 6 ## Schema - version: string - run: object (2 keys) - output: object (2 keys) - linters: object (3 keys) - issues: object (2 keys) - severity: object (1 keys) - formatters: object (3 keys) ## Preview yaml version: "2" run: allow-parallel-runners: true allow-serial-runners: true output: formats: text: path: stderr print-linter-name: true print-issued-lines: true sort-order: - linter - severity - file linters: default: none enable: - asasalint - asciicheck - bidichk - canonicalheader - containedctx - contextcheck - copyloopvar - cyclop - decorder - dogsled - dupl - dupword - durationcheck - err113 - errcheck - errchkjson - errname - errorlint - exhaustive - fatcontext - forcetypeassert - funlen - ginkgolinter … [source:golangci-c8766e4f]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

