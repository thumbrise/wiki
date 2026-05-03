---
page_id: 'concept:object'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: object
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - composer-c80b8ea8
  - docs-16563f41
  - golangci-c8766e4f
  - goreleaser-3530be9e
  - licenserc-5791d62b
  - release-33611003
project_ids: []
node_ids:
  - 'concept:object'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.853Z'
updated_at: '2026-05-03T04:02:08.784Z'
compiled_from:
  - composer-c80b8ea8
  - docs-16563f41
  - golangci-c8766e4f
  - goreleaser-3530be9e
  - licenserc-5791d62b
  - release-33611003
managed_by: system
backlinks:
  - 'source:composer-c80b8ea8'
  - 'source:docs-16563f41'
  - 'source:golangci-c8766e4f'
  - 'source:goreleaser-3530be9e'
  - 'source:licenserc-5791d62b'
  - 'source:release-33611003'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  composer-c80b8ea8: c80b8ea8d5b7cacc8b3e9212ae9a1f8582b0aa0407ad868af570f6d4796a4296
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
  golangci-c8766e4f: c8766e4f7a3ad850d894ea447959c7e8acda25d36b6aa6274419a7a55abb1ed9
  goreleaser-3530be9e: 3530be9e26af819c0c977d9ea4304d4f3b3a53e33f9b9bd9bb4cf03373c15ec8
  licenserc-5791d62b: 5791d62befde49bae75799fa5d04462fdf65eb73e7e42439e7283d2645d2b239
  release-33611003: 3361100365722fdfa39c8d57a7c1fbce9e584ad5ad2276364ee546e54792e9d4
source_semantic_hashes:
  composer-c80b8ea8: c80b8ea8d5b7cacc8b3e9212ae9a1f8582b0aa0407ad868af570f6d4796a4296
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
  golangci-c8766e4f: c8766e4f7a3ad850d894ea447959c7e8acda25d36b6aa6274419a7a55abb1ed9
  goreleaser-3530be9e: 3530be9e26af819c0c977d9ea4304d4f3b3a53e33f9b9bd9bb4cf03373c15ec8
  licenserc-5791d62b: 5791d62befde49bae75799fa5d04462fdf65eb73e7e42439e7283d2645d2b239
  release-33611003: 3361100365722fdfa39c8d57a7c1fbce9e584ad5ad2276364ee546e54792e9d4
---
# object

## Summary

Frequently referenced concept in composer.

## Seen In

- [[sources/composer-c80b8ea8|composer]]
- [[sources/docs-16563f41|docs]]
- [[sources/golangci-c8766e4f|.golangci]]
- [[sources/goreleaser-3530be9e|.goreleaser]]
- [[sources/licenserc-5791d62b|.licenserc]]
- [[sources/release-33611003|release]]

## Source Claims

- composer Format: JSON Top-level: object Size: 6 Nested depth: 3 ## Schema - name: string - description: string - license: string - type: string - autoload: object (1 keys) - require: object (1 keys) ## Preview json { "name": "thumbrise/op", "description": "Operation Protocol SDK — PHP type definitions", "license": "Apache-2.0", "type": "library", "autoload": { "files": [ "op.php" ] }, "require": { "php": ">=8.1" } } [source:composer-c80b8ea8]
- docs Format: YAML Top-level: object Size: 5 Nested depth: 6 ## Schema - name: string - on: object (2 keys) - permissions: object (3 keys) - concurrency: object (2 keys) - jobs: object (2 keys) ## Preview yaml name: Docs on: push: branches: [main] paths: - 'docs/**' workflow_dispatch: permissions: contents: read pages: write id-token: write concurrency: group: pages cancel-in-progress: false jobs: build: runs-on: ubuntu-latest steps: - uses: actions/checkout@v6 - uses: actions/setup-node@v6 with: node-version: 22 cache: npm cache-dependency-path: docs/package-lock.json - name: Install dependencies working-directory: docs run: npm ci - name: Build working-directory: docs run: npm run build - uses: actions/upload-pages-artifact@v5 with: … [source:docs-16563f41]
- .golangci Format: YAML Top-level: object Size: 7 Nested depth: 6 ## Schema - version: string - run: object (2 keys) - output: object (2 keys) - linters: object (3 keys) - issues: object (2 keys) - severity: object (1 keys) - formatters: object (3 keys) ## Preview yaml version: "2" run: allow-parallel-runners: true allow-serial-runners: true output: formats: text: path: stderr print-linter-name: true print-issued-lines: true sort-order: - linter - severity - file linters: default: none enable: - asasalint - asciicheck - bidichk - canonicalheader - containedctx - contextcheck - copyloopvar - cyclop - decorder - dogsled - dupl - dupword - durationcheck - err113 - errcheck - errchkjson - errname - errorlint - exhaustive - fatcontext - forcetypeassert - funlen - ginkgolinter … [source:golangci-c8766e4f]
- .goreleaser Format: YAML Top-level: object Size: 5 Nested depth: 5 ## Schema - version: number - builds: array (1 items) - archives: array (1 items) - checksum: object (1 keys) - release: object (1 keys) ## Preview yaml version: 2 builds: - main: . [source:goreleaser-3530be9e]
- .licenserc Format: YAML Top-level: object Size: 1 Nested depth: 3 ## Schema - header: object (5 keys) ## Preview yaml header: license: spdx-id: Apache-2.0 copyright-owner: thumbrise copyright-year: '2026' software-name: op paths: - '**/*.go' - '**/*.php' - '**/*.ts' paths-ignore: - 'docs/**' - 'dist' - 'licenses' - '**/*.md' - '**/*.yaml' - '**/*.yml' - '**/testdata/**' - '**/go.mod' - '**/go.sum' - '**/package-lock.json' - '**/node_modules/**' - 'LICENSE' - 'NOTICE' - '.gitignore' - '.releaserc.js' - 'release-template.hbs' comment: on-failure license-location-threshold: 80 [source:licenserc-5791d62b]
- release Format: YAML Top-level: object Size: 3 Nested depth: 6 ## Schema - name: string - on: object (1 keys) - jobs: object (1 keys) ## Preview yaml name: Release on: workflow_dispatch: jobs: release: name: Release runs-on: ubuntu-latest permissions: contents: write issues: write pull-requests: write steps: - name: Checkout uses: actions/checkout@v6 with: fetch-depth: 0 - name: Setup Node.js uses: actions/setup-node@v6 with: node-version: "lts/*" cache: npm - name: Install dependencies run: npm ci - name: Release env: GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }} run: npx semantic-release - name: Check for new tag id: tag run: | TAG=$(git describe --tags --exact-match 2>/dev/null || echo "") echo "new=$TAG" >> "$GITHUB_OUTPUT" - name: Setup Go if: steps.tag.outputs.new != '' … [source:release-33611003]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

