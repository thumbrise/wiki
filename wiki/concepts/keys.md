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
source_ids:
  - composer-2fcc293f
  - docs-16563f41
  - golangci-c8766e4f
  - rr-02e8677b
project_ids: []
node_ids:
  - 'concept:keys'
freshness: fresh
status: active
confidence: 0.95
created_at: '2026-05-03T03:56:35.855Z'
updated_at: '2026-05-03T05:32:23.396Z'
compiled_from:
  - composer-2fcc293f
  - docs-16563f41
  - golangci-c8766e4f
  - rr-02e8677b
managed_by: system
backlinks:
  - 'source:composer-2fcc293f'
  - 'source:docs-16563f41'
  - 'source:golangci-c8766e4f'
  - 'source:rr-02e8677b'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  composer-2fcc293f: 2fcc293f44d6fe883ba10bb14484f8d3ec6ab635d4fbe74ea358a6346674bdcd
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
  golangci-c8766e4f: c8766e4f7a3ad850d894ea447959c7e8acda25d36b6aa6274419a7a55abb1ed9
  rr-02e8677b: 02e8677ba0504b886295dd3260a794f26e74d233f559b079cc1615f735163677
source_semantic_hashes:
  composer-2fcc293f: 2fcc293f44d6fe883ba10bb14484f8d3ec6ab635d4fbe74ea358a6346674bdcd
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
  golangci-c8766e4f: c8766e4f7a3ad850d894ea447959c7e8acda25d36b6aa6274419a7a55abb1ed9
  rr-02e8677b: 02e8677ba0504b886295dd3260a794f26e74d233f559b079cc1615f735163677
---
# keys

## Summary

Frequently referenced concept in composer.

## Seen In

- [[sources/composer-2fcc293f|composer]]
- [[sources/docs-16563f41|docs]]
- [[sources/golangci-c8766e4f|.golangci]]
- [[sources/rr-02e8677b|.rr]]

## Source Claims

- composer Format: JSON Top-level: object Size: 15 Nested depth: 3 ## Schema - name: string - type: string - license: string - description: string - homepage: string - support: object (2 keys) - require: object (14 keys) - require-dev: object (4 keys) - autoload: object (1 keys) - autoload-dev: object (1 keys) - extra: object (1 keys) - config: object (2 keys) - scripts: object (8 keys) - minimum-stability: string - prefer-stable: boolean ## Preview json { "name": "spiral/app", "type": "project", "license": "MIT", "description": "Spiral Application installer", "homepage": "https://spiral.dev", "support": { "issues": "https://github.com/spiral/app/issues", "source": "https://github.com/spiral/app" }, "require": { "php": ">=8.1", "spiral/framework": "^3.15.7", "spiral/roadrunner-cli": "^2.5", "spiral/http": "^3.15", "ext-mbstring": "*", "spiral/nyholm-bridge": "^1.3", "spiral/roadrunner-bridge": "^4.0", "ext-sockets": "*", "spiral-packages/yii-error-handler-bridge": "^1.1", "spiral/cycle-bridge": "^2.11", "doctrine/collections": "^2.3", "spiral/validator": "^1.5", "spiral/stempler-bridge": "^3.15", "spiral/translator": "^3.15" }, "require-dev": { "spiral/code-style": "^2.2", "spiral/testing": "^2.3", "vimeo/psalm": "^6.10", "spiral/dumper": "^3.3.1" }, "autoload": { "psr-4": { "App\\": "app/src" } }, "autoload-dev": { "psr-4": { "Tests\\": "tests" … [source:composer-2fcc293f]
- docs Format: YAML Top-level: object Size: 5 Nested depth: 6 ## Schema - name: string - on: object (2 keys) - permissions: object (3 keys) - concurrency: object (2 keys) - jobs: object (2 keys) ## Preview yaml name: Docs on: push: branches: [main] paths: - 'docs/**' workflow_dispatch: permissions: contents: read pages: write id-token: write concurrency: group: pages cancel-in-progress: false jobs: build: runs-on: ubuntu-latest steps: - uses: actions/checkout@v6 - uses: actions/setup-node@v6 with: node-version: 22 cache: npm cache-dependency-path: docs/package-lock.json - name: Install dependencies working-directory: docs run: npm ci - name: Build working-directory: docs run: npm run build - uses: actions/upload-pages-artifact@v5 with: … [source:docs-16563f41]
- .golangci Format: YAML Top-level: object Size: 7 Nested depth: 6 ## Schema - version: string - run: object (2 keys) - output: object (2 keys) - linters: object (3 keys) - issues: object (2 keys) - severity: object (1 keys) - formatters: object (3 keys) ## Preview yaml version: "2" run: allow-parallel-runners: true allow-serial-runners: true output: formats: text: path: stderr print-linter-name: true print-issued-lines: true sort-order: - linter - severity - file linters: default: none enable: - asasalint - asciicheck - bidichk - canonicalheader - containedctx - contextcheck - copyloopvar - cyclop - decorder - dogsled - dupl - dupword - durationcheck - err113 - errcheck - errchkjson - errname - errorlint - exhaustive - fatcontext - forcetypeassert - funlen - ginkgolinter … [source:golangci-c8766e4f]
- .rr Format: YAML Top-level: object Size: 4 Nested depth: 4 ## Schema - version: string - rpc: object (1 keys) - http: object (4 keys) - server: object (2 keys) ## Preview yaml version: '3' rpc: listen: 'tcp://127.0.0.1:6001' http: address: '0.0.0.0:8080' middleware: - gzip - static static: dir: public forbid: - .php - .htaccess pool: num_workers: 1 supervisor: max_worker_memory: 100 server: command: 'php app.php' relay: pipes [source:rr-02e8677b]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

