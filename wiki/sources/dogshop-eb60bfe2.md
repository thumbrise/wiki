---
page_id: 'source:dogshop-eb60bfe2'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: dogshop
source_class: first_party
tags:
  - source
source_ids:
  - dogshop-eb60bfe2
project_ids: []
node_ids:
  - 'source:dogshop-eb60bfe2'
  - 'concept:kind'
  - 'concept:comment'
  - 'concept:string'
  - 'concept:schema'
  - 'concept:breed'
  - 'concept:json'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T03:56:35.828Z'
updated_at: '2026-05-03T04:02:08.719Z'
compiled_from:
  - dogshop-eb60bfe2
managed_by: system
backlinks:
  - 'concept:kind'
  - 'concept:comment'
  - 'concept:string'
  - 'concept:schema'
  - 'concept:breed'
  - 'concept:json'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
source_semantic_hashes:
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
---
# dogshop

Source ID: `dogshop-eb60bfe2`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/wiki/state/sources/github_repo-thumbrise-op-a16ed6ba/checkout/universal/fixtures/dogshop.json`

Source Class: `first_party`


## Source Details

- format: json
- top level type: object
- top level size: 3
- nested depth: 9


## Summary

dogshop Format: JSON Top-level: object Size: 3 Nested depth: 9 ## Schema - $schema: string - version: string - operations: array (6 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "id": "BuyDog", "comment": "Purchase a dog by breed with a budget limit. Demonstrates object composition, enum choice, and compound traits.", "input": [ { "id": "breed", "kind": "string", "required": true, "comment": "Exact breed name, e.g. \"labrador\"" }, { "id": "budget", "kind": "integer", "required": true, "comment": "Maximum price in cents" }, { "id": "express", "kind": "boolean", "comment": "Next-day delivery" }, { "id": "deliveryAddress", "kind": "object", "comment": "Where to deliver the dog", "of": [ {"id": "street", "kind": "string"}, {"id": "city", "kind": "string"}, {"id": "zip", "kind": "string", "comment": "Postal code, not an archive"}, {"id": "country", "kind": "string", "value": "US", "comment": "ISO 3166-1 alpha-2"} ] }, { "id": "preferredSize", "kind": "enum", "comment": "Desired dog size category", …

## Concepts

- [[concepts/kind|kind]]: Frequently referenced concept in dogshop.
- [[concepts/comment|comment]]: Frequently referenced concept in dogshop.
- [[concepts/string|string]]: Frequently referenced concept in dogshop.
- [[concepts/schema|schema]]: Frequently referenced concept in dogshop.
- [[concepts/breed|breed]]: Frequently referenced concept in dogshop.
- [[concepts/json|json]]: Frequently referenced concept in dogshop.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in dogshop.
- [[entities/top|Top-]]: Named entity mentioned in dogshop.
- [[entities/size|Size:]]: Named entity mentioned in dogshop.
- [[entities/nested|Nested]]: Named entity mentioned in dogshop.
- [[entities/schema|Schema -]]: Named entity mentioned in dogshop.
- [[entities/preview|Preview]]: Named entity mentioned in dogshop.

## Claims

- dogshop Format: JSON Top-level: object Size: 3 Nested depth: 9 ## Schema - $schema: string - version: string - operations: array (6 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "id": "BuyDog", "comment": "Purchase a dog by breed with a budget limit. [source:dogshop-eb60bfe2]
- Demonstrates object composition, enum choice, and compound traits.", "input": [ { "id": "breed", "kind": "string", "required": true, "comment": "Exact breed name, e.g. [source:dogshop-eb60bfe2]
- \"labrador\"" }, { "id": "budget", "kind": "integer", "required": true, "comment": "Maximum price in cents" }, { "id": "express", "kind": "boolean", "comment": "Next-day delivery" }, { "id": "deliveryAddress", "kind": "object", "comment": "Where to deliver the dog", "of": [ {"id": "street", "kind": "string"}, {"id": "city", "kind": "string"}, {"id": "zip", "kind": "string", "comment": "Postal code, not an archive"}, {"id": "country", "kind": "string", "value": "US", "comment": "ISO 3166-1 alpha-2"} ] }, { "id": "preferredSize", "kind": "enum", "comment": "Desired dog size category", … [source:dogshop-eb60bfe2]

## Questions

- How does kind relate to dogshop?
- How does comment relate to dogshop?
- How does string relate to dogshop?

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

