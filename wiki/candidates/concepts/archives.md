---
page_id: 'concept:archives'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: archives
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - goreleaser-3530be9e
project_ids: []
node_ids:
  - 'concept:archives'
freshness: fresh
status: candidate
confidence: 0.65
created_at: '2026-05-03T03:56:35.863Z'
updated_at: '2026-05-03T04:02:08.810Z'
compiled_from:
  - goreleaser-3530be9e
managed_by: system
backlinks:
  - 'source:goreleaser-3530be9e'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  goreleaser-3530be9e: 3530be9e26af819c0c977d9ea4304d4f3b3a53e33f9b9bd9bb4cf03373c15ec8
source_semantic_hashes:
  goreleaser-3530be9e: 3530be9e26af819c0c977d9ea4304d4f3b3a53e33f9b9bd9bb4cf03373c15ec8
---
# archives

## Summary

Frequently referenced concept in .goreleaser.

## Seen In

- [[sources/goreleaser-3530be9e|.goreleaser]]

## Source Claims

- .goreleaser Format: YAML Top-level: object Size: 5 Nested depth: 5 ## Schema - version: number - builds: array (1 items) - archives: array (1 items) - checksum: object (1 keys) - release: object (1 keys) ## Preview yaml version: 2 builds: - main: . [source:goreleaser-3530be9e]
- binary: op env: - CGO_ENABLED=0 goos: - linux - darwin - windows goarch: - amd64 - arm64 archives: - name_template: "{{ .ProjectName }}_{{ .Os }}_{{ .Arch }}" format_overrides: - goos: windows format: zip checksum: name_template: checksums.txt release: mode: append [source:goreleaser-3530be9e]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

