---
page_id: 'concept:autoload'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: autoload
source_class: first_party
tags:
  - concept
source_ids:
  - composer-2fcc293f
  - composer-c80b8ea8
project_ids: []
node_ids:
  - 'concept:autoload'
freshness: fresh
status: active
confidence: 0.8
created_at: '2026-05-03T03:56:35.854Z'
updated_at: '2026-05-03T05:32:23.397Z'
compiled_from:
  - composer-2fcc293f
  - composer-c80b8ea8
managed_by: system
backlinks:
  - 'source:composer-2fcc293f'
  - 'source:composer-c80b8ea8'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  composer-2fcc293f: 2fcc293f44d6fe883ba10bb14484f8d3ec6ab635d4fbe74ea358a6346674bdcd
  composer-c80b8ea8: c80b8ea8d5b7cacc8b3e9212ae9a1f8582b0aa0407ad868af570f6d4796a4296
source_semantic_hashes:
  composer-2fcc293f: 2fcc293f44d6fe883ba10bb14484f8d3ec6ab635d4fbe74ea358a6346674bdcd
  composer-c80b8ea8: c80b8ea8d5b7cacc8b3e9212ae9a1f8582b0aa0407ad868af570f6d4796a4296
---
# autoload

## Summary

Frequently referenced concept in composer.

## Seen In

- [[sources/composer-2fcc293f|composer]]
- [[sources/composer-c80b8ea8|composer]]

## Source Claims

- composer Format: JSON Top-level: object Size: 15 Nested depth: 3 ## Schema - name: string - type: string - license: string - description: string - homepage: string - support: object (2 keys) - require: object (14 keys) - require-dev: object (4 keys) - autoload: object (1 keys) - autoload-dev: object (1 keys) - extra: object (1 keys) - config: object (2 keys) - scripts: object (8 keys) - minimum-stability: string - prefer-stable: boolean ## Preview json { "name": "spiral/app", "type": "project", "license": "MIT", "description": "Spiral Application installer", "homepage": "https://spiral.dev", "support": { "issues": "https://github.com/spiral/app/issues", "source": "https://github.com/spiral/app" }, "require": { "php": ">=8.1", "spiral/framework": "^3.15.7", "spiral/roadrunner-cli": "^2.5", "spiral/http": "^3.15", "ext-mbstring": "*", "spiral/nyholm-bridge": "^1.3", "spiral/roadrunner-bridge": "^4.0", "ext-sockets": "*", "spiral-packages/yii-error-handler-bridge": "^1.1", "spiral/cycle-bridge": "^2.11", "doctrine/collections": "^2.3", "spiral/validator": "^1.5", "spiral/stempler-bridge": "^3.15", "spiral/translator": "^3.15" }, "require-dev": { "spiral/code-style": "^2.2", "spiral/testing": "^2.3", "vimeo/psalm": "^6.10", "spiral/dumper": "^3.3.1" }, "autoload": { "psr-4": { "App\\": "app/src" } }, "autoload-dev": { "psr-4": { "Tests\\": "tests" … [source:composer-2fcc293f]
- composer Format: JSON Top-level: object Size: 6 Nested depth: 3 ## Schema - name: string - description: string - license: string - type: string - autoload: object (1 keys) - require: object (1 keys) ## Preview json { "name": "thumbrise/op", "description": "Operation Protocol SDK — PHP type definitions", "license": "Apache-2.0", "type": "library", "autoload": { "files": [ "op.php" ] }, "require": { "php": ">=8.1" } } [source:composer-c80b8ea8]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

