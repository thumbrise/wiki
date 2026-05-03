---
page_id: 'concept:string'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: string
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - 3d-pub-bar-role-game-the-krabby-patty-3de2f4ab
  - composer-c80b8ea8
  - dogshop-eb60bfe2
  - instruction-v1-e3a3cb1e
project_ids: []
node_ids:
  - 'concept:string'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.851Z'
updated_at: '2026-05-03T04:02:08.774Z'
compiled_from:
  - 3d-pub-bar-role-game-the-krabby-patty-3de2f4ab
  - composer-c80b8ea8
  - dogshop-eb60bfe2
  - instruction-v1-e3a3cb1e
managed_by: system
backlinks:
  - 'source:3d-pub-bar-role-game-the-krabby-patty-3de2f4ab'
  - 'source:composer-c80b8ea8'
  - 'source:dogshop-eb60bfe2'
  - 'source:instruction-v1-e3a3cb1e'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  3d-pub-bar-role-game-the-krabby-patty-3de2f4ab: 3de2f4abddf88f450cf3931c91d24227e64722e28109f88c16ede10d42f33d67
  composer-c80b8ea8: c80b8ea8d5b7cacc8b3e9212ae9a1f8582b0aa0407ad868af570f6d4796a4296
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
  instruction-v1-e3a3cb1e: e3a3cb1e9f7fddff5e421a4c2c7209456267bc665df1e3c3b04a6e746ec057ff
source_semantic_hashes:
  3d-pub-bar-role-game-the-krabby-patty-3de2f4ab: 7d56188c7435a0317a39ea49efb6bfc5fc205abc4d40375ed2714d57cdae5d10
  composer-c80b8ea8: c80b8ea8d5b7cacc8b3e9212ae9a1f8582b0aa0407ad868af570f6d4796a4296
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
  instruction-v1-e3a3cb1e: e3a3cb1e9f7fddff5e421a4c2c7209456267bc665df1e3c3b04a6e746ec057ff
---
# string

## Summary

Frequently referenced concept in #3d — Pub Bar Role Game: The Krabby Patty.

## Seen In

- [[sources/3d-pub-bar-role-game-the-krabby-patty-3de2f4ab|#3d — Pub Bar Role Game: The Krabby Patty]]
- [[sources/composer-c80b8ea8|composer]]
- [[sources/dogshop-eb60bfe2|dogshop]]
- [[sources/instruction-v1-e3a3cb1e|instruction.v1]]

## Source Claims

- composer Format: JSON Top-level: object Size: 6 Nested depth: 3 ## Schema - name: string - description: string - license: string - type: string - autoload: object (1 keys) - require: object (1 keys) ## Preview json { "name": "thumbrise/op", "description": "Operation Protocol SDK — PHP type definitions", "license": "Apache-2.0", "type": "library", "autoload": { "files": [ "op.php" ] }, "require": { "php": ">=8.1" } } [source:composer-c80b8ea8]
- dogshop Format: JSON Top-level: object Size: 3 Nested depth: 9 ## Schema - $schema: string - version: string - operations: array (6 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "id": "BuyDog", "comment": "Purchase a dog by breed with a budget limit. [source:dogshop-eb60bfe2]
- Demonstrates object composition, enum choice, and compound traits.", "input": [ { "id": "breed", "kind": "string", "required": true, "comment": "Exact breed name, e.g. [source:dogshop-eb60bfe2]
- \"labrador\"" }, { "id": "budget", "kind": "integer", "required": true, "comment": "Maximum price in cents" }, { "id": "express", "kind": "boolean", "comment": "Next-day delivery" }, { "id": "deliveryAddress", "kind": "object", "comment": "Where to deliver the dog", "of": [ {"id": "street", "kind": "string"}, {"id": "city", "kind": "string"}, {"id": "zip", "kind": "string", "comment": "Postal code, not an archive"}, {"id": "country", "kind": "string", "value": "US", "comment": "ISO 3166-1 alpha-2"} ] }, { "id": "preferredSize", "kind": "enum", "comment": "Desired dog size category", … [source:dogshop-eb60bfe2]
- instruction.v1 Format: JSON Top-level: object Size: 8 Nested depth: 6 ## Schema - $schema: string - $id: string - title: string - description: string - type: string - properties: object (2 keys) - required: array (2 items) - $defs: object (3 keys) ## Preview json { "$schema": "https://json-schema.org/draft/2020-12/schema", "$id": "https://thumbrise.github.io/op/schema/instruction.v1.json", "title": "OP", "description": "Operation Protocol Instruction. [source:instruction-v1-e3a3cb1e]
- One Term structure everywhere.", "type": "object", "properties": { "version": { "type": "string", "description": "Instruction format version. [source:instruction-v1-e3a3cb1e]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

