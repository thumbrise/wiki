---
page_id: 'concept:json'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: json
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - composer-c80b8ea8
  - dogshop-eb60bfe2
  - editorconfig-35e39de5
  - three-atoms-28e52786
project_ids: []
node_ids:
  - 'concept:json'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.854Z'
updated_at: '2026-05-03T04:02:08.785Z'
compiled_from:
  - composer-c80b8ea8
  - dogshop-eb60bfe2
  - editorconfig-35e39de5
  - three-atoms-28e52786
managed_by: system
backlinks:
  - 'source:composer-c80b8ea8'
  - 'source:dogshop-eb60bfe2'
  - 'source:editorconfig-35e39de5'
  - 'source:three-atoms-28e52786'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  composer-c80b8ea8: c80b8ea8d5b7cacc8b3e9212ae9a1f8582b0aa0407ad868af570f6d4796a4296
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
  editorconfig-35e39de5: 35e39de50d89bd305cd38bce05d3114d0df307f6d7445b6c2a81498807b939b6
  three-atoms-28e52786: 28e52786ebcc39448defbb5a4dc799086bb28b700f539fb9d0c6a6113655fc4c
source_semantic_hashes:
  composer-c80b8ea8: c80b8ea8d5b7cacc8b3e9212ae9a1f8582b0aa0407ad868af570f6d4796a4296
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
  editorconfig-35e39de5: 35e39de50d89bd305cd38bce05d3114d0df307f6d7445b6c2a81498807b939b6
  three-atoms-28e52786: 8fca0b33119b7c2e29e3805eb6fbefbef508f37dc42b48f1fe60047141018eed
---
# json

## Summary

Frequently referenced concept in composer.

## Seen In

- [[sources/composer-c80b8ea8|composer]]
- [[sources/dogshop-eb60bfe2|dogshop]]
- [[sources/editorconfig-35e39de5|.editorconfig]]
- [[sources/three-atoms-28e52786|Three Atoms]]

## Source Claims

- composer Format: JSON Top-level: object Size: 6 Nested depth: 3 ## Schema - name: string - description: string - license: string - type: string - autoload: object (1 keys) - require: object (1 keys) ## Preview json { "name": "thumbrise/op", "description": "Operation Protocol SDK — PHP type definitions", "license": "Apache-2.0", "type": "library", "autoload": { "files": [ "op.php" ] }, "require": { "php": ">=8.1" } } [source:composer-c80b8ea8]
- dogshop Format: JSON Top-level: object Size: 3 Nested depth: 9 ## Schema - $schema: string - version: string - operations: array (6 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "id": "BuyDog", "comment": "Purchase a dog by breed with a budget limit. [source:dogshop-eb60bfe2]
- [*.json] indent_style = space indent_size = 4 [source:editorconfig-35e39de5]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

