---
page_id: 'concept:actions'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: actions
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - docs-16563f41
project_ids: []
node_ids:
  - 'concept:actions'
freshness: fresh
status: candidate
confidence: 0.65
created_at: '2026-05-03T03:56:35.855Z'
updated_at: '2026-05-03T04:02:08.789Z'
compiled_from:
  - docs-16563f41
managed_by: system
backlinks:
  - 'source:docs-16563f41'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
source_semantic_hashes:
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
---
# actions

## Summary

Frequently referenced concept in docs.

## Seen In

- [[sources/docs-16563f41|docs]]

## Source Claims

- docs Format: YAML Top-level: object Size: 5 Nested depth: 6 ## Schema - name: string - on: object (2 keys) - permissions: object (3 keys) - concurrency: object (2 keys) - jobs: object (2 keys) ## Preview yaml name: Docs on: push: branches: [main] paths: - 'docs/**' workflow_dispatch: permissions: contents: read pages: write id-token: write concurrency: group: pages cancel-in-progress: false jobs: build: runs-on: ubuntu-latest steps: - uses: actions/checkout@v6 - uses: actions/setup-node@v6 with: node-version: 22 cache: npm cache-dependency-path: docs/package-lock.json - name: Install dependencies working-directory: docs run: npm ci - name: Build working-directory: docs run: npm run build - uses: actions/upload-pages-artifact@v5 with: … [source:docs-16563f41]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

