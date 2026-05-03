---
page_id: 'concept:release'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: release
source_class: first_party
tags:
  - concept
source_ids:
  - release-33611003
project_ids: []
node_ids:
  - 'concept:release'
freshness: fresh
status: active
confidence: 0.65
created_at: '2026-05-03T03:56:35.869Z'
updated_at: '2026-05-03T05:32:23.482Z'
compiled_from:
  - release-33611003
managed_by: system
backlinks:
  - 'source:release-33611003'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  release-33611003: 3361100365722fdfa39c8d57a7c1fbce9e584ad5ad2276364ee546e54792e9d4
source_semantic_hashes:
  release-33611003: 3361100365722fdfa39c8d57a7c1fbce9e584ad5ad2276364ee546e54792e9d4
---
# release

## Summary

Frequently referenced concept in release.

## Seen In

- [[sources/release-33611003|release]]

## Source Claims

- release Format: YAML Top-level: object Size: 3 Nested depth: 6 ## Schema - name: string - on: object (1 keys) - jobs: object (1 keys) ## Preview yaml name: Release on: workflow_dispatch: jobs: release: name: Release runs-on: ubuntu-latest permissions: contents: write issues: write pull-requests: write steps: - name: Checkout uses: actions/checkout@v6 with: fetch-depth: 0 - name: Setup Node.js uses: actions/setup-node@v6 with: node-version: "lts/*" cache: npm - name: Install dependencies run: npm ci - name: Release env: GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }} run: npx semantic-release - name: Check for new tag id: tag run: | TAG=$(git describe --tags --exact-match 2>/dev/null || echo "") echo "new=$TAG" >> "$GITHUB_OUTPUT" - name: Setup Go if: steps.tag.outputs.new != '' … [source:release-33611003]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

