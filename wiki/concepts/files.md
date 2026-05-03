---
page_id: 'concept:files'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: files
source_class: first_party
tags:
  - concept
source_ids:
  - auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79
  - package-945abd34
  - psalm-baseline-38ca50b0
project_ids: []
node_ids:
  - 'concept:files'
freshness: fresh
status: active
confidence: 0.95
created_at: '2026-05-03T03:56:35.852Z'
updated_at: '2026-05-03T05:32:23.388Z'
compiled_from:
  - auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79
  - package-945abd34
  - psalm-baseline-38ca50b0
managed_by: system
backlinks:
  - 'source:auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79'
  - 'source:package-945abd34'
  - 'source:psalm-baseline-38ca50b0'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79: 4f36ba79c784d8d06983fd4c119f30d72326dbf29d71d5045d42a0664a7eecd1
  package-945abd34: 945abd3421905b11b7471174be4411d2260d3273ea87a5fba0f499658fcd6a8f
  psalm-baseline-38ca50b0: 38ca50b050e42e0170902c7a4ec207d2d2481a287cb67f321ea346008bc78e08
source_semantic_hashes:
  auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79: 4f36ba79c784d8d06983fd4c119f30d72326dbf29d71d5045d42a0664a7eecd1
  package-945abd34: 945abd3421905b11b7471174be4411d2260d3273ea87a5fba0f499658fcd6a8f
  psalm-baseline-38ca50b0: 38ca50b050e42e0170902c7a4ec207d2d2481a287cb67f321ea346008bc78e08
---
# files

## Summary

Frequently referenced concept in Auto-detect text files and normalise line endings to LF..

## Seen In

- [[sources/auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79|Auto-detect text files and normalise line endings to LF.]]
- [[sources/package-945abd34|package]]
- [[sources/psalm-baseline-38ca50b0|psalm-baseline]]

## Source Claims

- Auto-detect text files and normalise line endings to LF. [source:auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79]
- * text=auto eol=lf # Go sources *.go text eol=lf diff=golang # Config / data *.yml text eol=lf *.yaml text eol=lf *.json text eol=lf *.toml text eol=lf # Documentation *.md text eol=lf *.txt text eol=lf # Scripts *.sh text eol=lf # Go module files go.mod text eol=lf go.sum text eol=lf # CI / tooling Taskfile.yaml text eol=lf Dockerfile text eol=lf .gitignore text eol=lf .gitattributes text eol=lf .golangci.yml text eol=lf .licenserc.yaml text eol=lf LICENSE text eol=lf # Binaries — no diff, no merge, no text conversion *.db binary *.exe binary *.wasm binary *.png binary *.jpg binary *.gif binary *.ico binary # Go workspace (local only, but normalize if committed by accident) go.work text eol=lf go.work.sum text eol=lf [source:auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79]
- { "name": "@thumbrise/op", "version": "0.0.0", "description": "Operation Protocol SDK — TypeScript type definitions", "license": "Apache-2.0", "type": "module", "main": "op.ts", "types": "op.ts", "files": [ "op.ts" ], "private": true } [source:package-945abd34]
- psalm-baseline Format: XML Top-level: object Size: 1 Nested depth: 2 ## Schema - files: object (0 keys) ## Preview xml <?xml version="1.0" encoding="UTF-8"?> <files> </files> [source:psalm-baseline-38ca50b0]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

