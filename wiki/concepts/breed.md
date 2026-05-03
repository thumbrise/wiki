---
page_id: 'concept:breed'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: breed
source_class: first_party
tags:
  - concept
source_ids:
  - dogshop-de2fc247
  - dogshop-eb60bfe2
project_ids: []
node_ids:
  - 'concept:breed'
freshness: fresh
status: active
confidence: 0.8
created_at: '2026-05-03T03:56:35.856Z'
updated_at: '2026-05-03T05:32:23.410Z'
compiled_from:
  - dogshop-de2fc247
  - dogshop-eb60bfe2
managed_by: system
backlinks:
  - 'source:dogshop-de2fc247'
  - 'source:dogshop-eb60bfe2'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dogshop-de2fc247: de2fc24762d03f20dfcdb9aa4b508bb3e5895ae3374e35358c24effaf36335ea
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
source_semantic_hashes:
  dogshop-de2fc247: de2fc24762d03f20dfcdb9aa4b508bb3e5895ae3374e35358c24effaf36335ea
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
---
# breed

## Summary

Frequently referenced concept in dogshop.

## Seen In

- [[sources/dogshop-de2fc247|dogshop]]
- [[sources/dogshop-eb60bfe2|dogshop]]

## Source Claims

- dogshop Format: JSON Top-level: object Size: 5 Nested depth: 9 ## Schema - id: string - comment: string - version: string - operations: array (6 items) - trait: array (0 items) ## Preview json { "id": "playground-instruction", "comment": "Playground demonstration instruction", "version": "1.0.0", "operations": [ { "id": "BuyDog", "comment": "Purchase a dog by breed with a budget limit. [source:dogshop-de2fc247]
- Demonstrates object composition, enum choice, and compound traits.", "input": [ { "id": "breed", "comment": "Exact breed name, e.g. [source:dogshop-de2fc247]
- dogshop Format: JSON Top-level: object Size: 3 Nested depth: 9 ## Schema - $schema: string - version: string - operations: array (6 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "id": "BuyDog", "comment": "Purchase a dog by breed with a budget limit. [source:dogshop-eb60bfe2]
- Demonstrates object composition, enum choice, and compound traits.", "input": [ { "id": "breed", "kind": "string", "required": true, "comment": "Exact breed name, e.g. [source:dogshop-eb60bfe2]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

