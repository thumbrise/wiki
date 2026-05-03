---
page_id: 'entity:config'
kind: entity
cssclasses:
  - swarmvault
  - sv-entity
title: Config
source_class: first_party
tags:
  - entity
source_ids:
  - auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79
project_ids: []
node_ids:
  - 'entity:config'
freshness: fresh
status: active
confidence: 0.65
created_at: '2026-05-03T03:56:35.888Z'
updated_at: '2026-05-03T05:32:23.591Z'
compiled_from:
  - auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79
managed_by: system
backlinks:
  - 'source:auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79: 4f36ba79c784d8d06983fd4c119f30d72326dbf29d71d5045d42a0664a7eecd1
source_semantic_hashes:
  auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79: 4f36ba79c784d8d06983fd4c119f30d72326dbf29d71d5045d42a0664a7eecd1
---
# Config

## Summary

Named entity mentioned in Auto-detect text files and normalise line endings to LF..

## Seen In

- [[sources/auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79|Auto-detect text files and normalise line endings to LF.]]

## Source Claims

- * text=auto eol=lf # Go sources *.go text eol=lf diff=golang # Config / data *.yml text eol=lf *.yaml text eol=lf *.json text eol=lf *.toml text eol=lf # Documentation *.md text eol=lf *.txt text eol=lf # Scripts *.sh text eol=lf # Go module files go.mod text eol=lf go.sum text eol=lf # CI / tooling Taskfile.yaml text eol=lf Dockerfile text eol=lf .gitignore text eol=lf .gitattributes text eol=lf .golangci.yml text eol=lf .licenserc.yaml text eol=lf LICENSE text eol=lf # Binaries — no diff, no merge, no text conversion *.db binary *.exe binary *.wasm binary *.png binary *.jpg binary *.gif binary *.ico binary # Go workspace (local only, but normalize if committed by accident) go.work text eol=lf go.work.sum text eol=lf [source:auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

