---
page_id: 'source:goreleaser-3530be9e'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: .goreleaser
source_class: first_party
tags:
  - source
source_ids:
  - goreleaser-3530be9e
project_ids: []
node_ids:
  - 'source:goreleaser-3530be9e'
  - 'concept:format'
  - 'concept:object'
  - 'concept:archives'
  - 'concept:array'
  - 'concept:builds'
  - 'concept:checksum'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T03:56:35.831Z'
updated_at: '2026-05-03T04:02:08.724Z'
compiled_from:
  - goreleaser-3530be9e
managed_by: system
backlinks:
  - 'concept:format'
  - 'concept:object'
  - 'concept:archives'
  - 'concept:array'
  - 'concept:builds'
  - 'concept:checksum'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  goreleaser-3530be9e: 3530be9e26af819c0c977d9ea4304d4f3b3a53e33f9b9bd9bb4cf03373c15ec8
source_semantic_hashes:
  goreleaser-3530be9e: 3530be9e26af819c0c977d9ea4304d4f3b3a53e33f9b9bd9bb4cf03373c15ec8
---
# .goreleaser

Source ID: `goreleaser-3530be9e`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/wiki/state/sources/github_repo-thumbrise-op-a16ed6ba/checkout/.goreleaser.yml`

Source Class: `first_party`


## Source Details

- format: yaml
- top level type: object
- top level size: 5
- nested depth: 5


## Summary

.goreleaser Format: YAML Top-level: object Size: 5 Nested depth: 5 ## Schema - version: number - builds: array (1 items) - archives: array (1 items) - checksum: object (1 keys) - release: object (1 keys) ## Preview yaml version: 2 builds: - main: . binary: op env: - CGO_ENABLED=0 goos: - linux - darwin - windows goarch: - amd64 - arm64 archives: - name_template: "{{ .ProjectName }}_{{ .Os }}_{{ .Arch }}" format_overrides: - goos: windows format: zip checksum: name_template: checksums.txt release: mode: append

## Concepts

- [[concepts/format|format]]: Frequently referenced concept in .goreleaser.
- [[concepts/object|object]]: Frequently referenced concept in .goreleaser.
- [[concepts/archives|archives]]: Frequently referenced concept in .goreleaser.
- [[concepts/array|array]]: Frequently referenced concept in .goreleaser.
- [[concepts/builds|builds]]: Frequently referenced concept in .goreleaser.
- [[concepts/checksum|checksum]]: Frequently referenced concept in .goreleaser.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in .goreleaser.
- [[entities/top|Top-]]: Named entity mentioned in .goreleaser.
- [[entities/size|Size:]]: Named entity mentioned in .goreleaser.
- [[entities/nested|Nested]]: Named entity mentioned in .goreleaser.
- [[entities/schema|Schema -]]: Named entity mentioned in .goreleaser.
- [[entities/preview|Preview]]: Named entity mentioned in .goreleaser.

## Claims

- .goreleaser Format: YAML Top-level: object Size: 5 Nested depth: 5 ## Schema - version: number - builds: array (1 items) - archives: array (1 items) - checksum: object (1 keys) - release: object (1 keys) ## Preview yaml version: 2 builds: - main: . [source:goreleaser-3530be9e]
- binary: op env: - CGO_ENABLED=0 goos: - linux - darwin - windows goarch: - amd64 - arm64 archives: - name_template: "{{ .ProjectName }}_{{ .Os }}_{{ .Arch }}" format_overrides: - goos: windows format: zip checksum: name_template: checksums.txt release: mode: append [source:goreleaser-3530be9e]

## Questions

- How does format relate to .goreleaser?
- How does object relate to .goreleaser?
- How does archives relate to .goreleaser?

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

