---
page_id: 'concept:format'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: format
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - 19-the-missing-format-37a6499f
  - 23-the-vacant-cell-4774271c
  - goreleaser-3530be9e
project_ids: []
node_ids:
  - 'concept:format'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.846Z'
updated_at: '2026-05-03T04:02:08.761Z'
compiled_from:
  - 19-the-missing-format-37a6499f
  - 23-the-vacant-cell-4774271c
  - goreleaser-3530be9e
managed_by: system
backlinks:
  - 'source:19-the-missing-format-37a6499f'
  - 'source:23-the-vacant-cell-4774271c'
  - 'source:goreleaser-3530be9e'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  19-the-missing-format-37a6499f: 37a6499ff47cbdd783870d4250e93c97e12c7d7496c7452f34ff9218c2127008
  23-the-vacant-cell-4774271c: 4774271cc1bf1964123bd9509b70c087876d8c93e1cccafe2cba1b8f675a1201
  goreleaser-3530be9e: 3530be9e26af819c0c977d9ea4304d4f3b3a53e33f9b9bd9bb4cf03373c15ec8
source_semantic_hashes:
  19-the-missing-format-37a6499f: 16274190945d15205017cff4b4b79a3250908278ad49d0c90f2369455235c953
  23-the-vacant-cell-4774271c: 51f351bfe72d5b0663faefd06285ececa5c6c002d96380dda5612cb885a6b42b
  goreleaser-3530be9e: 3530be9e26af819c0c977d9ea4304d4f3b3a53e33f9b9bd9bb4cf03373c15ec8
---
# format

## Summary

Frequently referenced concept in #19 — The Missing Format.

## Seen In

- [[sources/19-the-missing-format-37a6499f|#19 — The Missing Format]]
- [[sources/23-the-vacant-cell-4774271c|#23 — The Vacant Cell]]
- [[sources/goreleaser-3530be9e|.goreleaser]]

## Source Claims

- title: #19 — The Missing Format description: Fonts agreed on .ttf. [source:19-the-missing-format-37a6499f]
- title: #23 — The Vacant Cell description: We asked: does a protocol exist that describes operations without opinion on transport, format, or consumer — and solves the expression problem? [source:23-the-vacant-cell-4774271c]
- .goreleaser Format: YAML Top-level: object Size: 5 Nested depth: 5 ## Schema - version: number - builds: array (1 items) - archives: array (1 items) - checksum: object (1 keys) - release: object (1 keys) ## Preview yaml version: 2 builds: - main: . [source:goreleaser-3530be9e]
- binary: op env: - CGO_ENABLED=0 goos: - linux - darwin - windows goarch: - amd64 - arm64 archives: - name_template: "{{ .ProjectName }}_{{ .Os }}_{{ .Arch }}" format_overrides: - goos: windows format: zip checksum: name_template: checksums.txt release: mode: append [source:goreleaser-3530be9e]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

