---
page_id: 'concept:build'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: build
source_class: first_party
tags:
  - concept
source_ids:
  - 27-build-link-runtime-2e7dc35f
  - docs-16563f41
project_ids: []
node_ids:
  - 'concept:build'
freshness: fresh
status: active
confidence: 0.8
created_at: '2026-05-03T03:56:35.849Z'
updated_at: '2026-05-03T05:32:23.364Z'
compiled_from:
  - 27-build-link-runtime-2e7dc35f
  - docs-16563f41
managed_by: system
backlinks:
  - 'source:27-build-link-runtime-2e7dc35f'
  - 'source:docs-16563f41'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  27-build-link-runtime-2e7dc35f: 2e7dc35f05845b25457fe80f57746ca1470e46811de2d35b57e062135098f531
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
source_semantic_hashes:
  27-build-link-runtime-2e7dc35f: 7aa621b01b4ee6e1aecaebdd211a3c6827953fce17f5f8e654c5b60321423a24
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
---
# build

## Summary

Frequently referenced concept in #27 — Build, Link, Runtime.

## Seen In

- [[sources/27-build-link-runtime-2e7dc35f|#27 — Build, Link, Runtime]]
- [[sources/docs-16563f41|docs]]

## Source Claims

- title: #27 — Build, Link, Runtime description: Three plates of pasta. [source:27-build-link-runtime-2e7dc35f]
- # Build, Link, Runtime A reader asks a good vermicelli question. [source:27-build-link-runtime-2e7dc35f]
- docs Format: YAML Top-level: object Size: 5 Nested depth: 6 ## Schema - name: string - on: object (2 keys) - permissions: object (3 keys) - concurrency: object (2 keys) - jobs: object (2 keys) ## Preview yaml name: Docs on: push: branches: [main] paths: - 'docs/**' workflow_dispatch: permissions: contents: read pages: write id-token: write concurrency: group: pages cancel-in-progress: false jobs: build: runs-on: ubuntu-latest steps: - uses: actions/checkout@v6 - uses: actions/setup-node@v6 with: node-version: 22 cache: npm cache-dependency-path: docs/package-lock.json - name: Install dependencies working-directory: docs run: npm ci - name: Build working-directory: docs run: npm run build - uses: actions/upload-pages-artifact@v5 with: … [source:docs-16563f41]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

