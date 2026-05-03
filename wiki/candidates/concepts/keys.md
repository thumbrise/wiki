---
page_id: 'concept:keys'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: keys
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - docs-16563f41
  - golangci-c8766e4f
project_ids: []
node_ids:
  - 'concept:keys'
freshness: fresh
status: candidate
confidence: 0.8
created_at: '2026-05-03T03:56:35.855Z'
updated_at: '2026-05-03T04:02:08.789Z'
compiled_from:
  - docs-16563f41
  - golangci-c8766e4f
managed_by: system
backlinks:
  - 'source:docs-16563f41'
  - 'source:golangci-c8766e4f'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
  golangci-c8766e4f: c8766e4f7a3ad850d894ea447959c7e8acda25d36b6aa6274419a7a55abb1ed9
source_semantic_hashes:
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
  golangci-c8766e4f: c8766e4f7a3ad850d894ea447959c7e8acda25d36b6aa6274419a7a55abb1ed9
---
# keys

## Summary

Frequently referenced concept in docs.

## Seen In

- [[sources/docs-16563f41|docs]]
- [[sources/golangci-c8766e4f|.golangci]]

## Source Claims

- docs Format: YAML Top-level: object Size: 5 Nested depth: 6 ## Schema - name: string - on: object (2 keys) - permissions: object (3 keys) - concurrency: object (2 keys) - jobs: object (2 keys) ## Preview yaml name: Docs on: push: branches: [main] paths: - 'docs/**' workflow_dispatch: permissions: contents: read pages: write id-token: write concurrency: group: pages cancel-in-progress: false jobs: build: runs-on: ubuntu-latest steps: - uses: actions/checkout@v6 - uses: actions/setup-node@v6 with: node-version: 22 cache: npm cache-dependency-path: docs/package-lock.json - name: Install dependencies working-directory: docs run: npm ci - name: Build working-directory: docs run: npm run build - uses: actions/upload-pages-artifact@v5 with: … [source:docs-16563f41]
- .golangci Format: YAML Top-level: object Size: 7 Nested depth: 6 ## Schema - version: string - run: object (2 keys) - output: object (2 keys) - linters: object (3 keys) - issues: object (2 keys) - severity: object (1 keys) - formatters: object (3 keys) ## Preview yaml version: "2" run: allow-parallel-runners: true allow-serial-runners: true output: formats: text: path: stderr print-linter-name: true print-issued-lines: true sort-order: - linter - severity - file linters: default: none enable: - asasalint - asciicheck - bidichk - canonicalheader - containedctx - contextcheck - copyloopvar - cyclop - decorder - dogsled - dupl - dupword - durationcheck - err113 - errcheck - errchkjson - errname - errorlint - exhaustive - fatcontext - forcetypeassert - funlen - ginkgolinter … [source:golangci-c8766e4f]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

