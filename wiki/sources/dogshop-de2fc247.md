---
page_id: 'source:dogshop-de2fc247'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: dogshop
source_class: first_party
tags:
  - source
source_ids:
  - dogshop-de2fc247
project_ids: []
node_ids:
  - 'source:dogshop-de2fc247'
  - 'concept:comment'
  - 'concept:kind'
  - 'concept:string'
  - 'concept:breed'
  - 'concept:name'
  - 'concept:object'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T05:11:46.019Z'
updated_at: '2026-05-03T05:32:23.220Z'
compiled_from:
  - dogshop-de2fc247
managed_by: system
backlinks:
  - 'concept:comment'
  - 'concept:kind'
  - 'concept:string'
  - 'concept:breed'
  - 'concept:name'
  - 'concept:object'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dogshop-de2fc247: de2fc24762d03f20dfcdb9aa4b508bb3e5895ae3374e35358c24effaf36335ea
source_semantic_hashes:
  dogshop-de2fc247: de2fc24762d03f20dfcdb9aa4b508bb3e5895ae3374e35358c24effaf36335ea
---
# dogshop

Source ID: `dogshop-de2fc247`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/op/universal/fixtures/dogshop.json`

Source Class: `first_party`


## Source Details

- format: json
- top level type: object
- top level size: 5
- nested depth: 9


## Summary

dogshop Format: JSON Top-level: object Size: 5 Nested depth: 9 ## Schema - id: string - comment: string - version: string - operations: array (6 items) - trait: array (0 items) ## Preview json { "id": "playground-instruction", "comment": "Playground demonstration instruction", "version": "1.0.0", "operations": [ { "id": "BuyDog", "comment": "Purchase a dog by breed with a budget limit. Demonstrates object composition, enum choice, and compound traits.", "input": [ { "id": "breed", "comment": "Exact breed name, e.g. \"labrador\"", "required": true, "kind": "string" }, { "id": "budget", "comment": "Maximum price in cents", "required": true, "kind": "integer" }, { "id": "express", "comment": "Next-day delivery", "kind": "boolean" }, { "id": "deliveryAddress", "comment": "Where to deliver the dog", "kind": "object", "of": [ { "id": "street", "comment": "Street name and number", "kind": "string" }, { "id": "city", "comment": "City name", "kind": "string" …

## Concepts

- [[concepts/comment|comment]]: Frequently referenced concept in dogshop.
- [[concepts/kind|kind]]: Frequently referenced concept in dogshop.
- [[concepts/string|string]]: Frequently referenced concept in dogshop.
- [[concepts/breed|breed]]: Frequently referenced concept in dogshop.
- [[concepts/name|name]]: Frequently referenced concept in dogshop.
- [[concepts/object|object]]: Frequently referenced concept in dogshop.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in dogshop.
- [[entities/top|Top-]]: Named entity mentioned in dogshop.
- [[entities/size|Size:]]: Named entity mentioned in dogshop.
- [[entities/nested|Nested]]: Named entity mentioned in dogshop.
- [[entities/schema|Schema -]]: Named entity mentioned in dogshop.
- [[entities/preview|Preview]]: Named entity mentioned in dogshop.

## Claims

- dogshop Format: JSON Top-level: object Size: 5 Nested depth: 9 ## Schema - id: string - comment: string - version: string - operations: array (6 items) - trait: array (0 items) ## Preview json { "id": "playground-instruction", "comment": "Playground demonstration instruction", "version": "1.0.0", "operations": [ { "id": "BuyDog", "comment": "Purchase a dog by breed with a budget limit. [source:dogshop-de2fc247]
- Demonstrates object composition, enum choice, and compound traits.", "input": [ { "id": "breed", "comment": "Exact breed name, e.g. [source:dogshop-de2fc247]
- \"labrador\"", "required": true, "kind": "string" }, { "id": "budget", "comment": "Maximum price in cents", "required": true, "kind": "integer" }, { "id": "express", "comment": "Next-day delivery", "kind": "boolean" }, { "id": "deliveryAddress", "comment": "Where to deliver the dog", "kind": "object", "of": [ { "id": "street", "comment": "Street name and number", "kind": "string" }, { "id": "city", "comment": "City name", "kind": "string" … [source:dogshop-de2fc247]

## Questions

- How does comment relate to dogshop?
- How does kind relate to dogshop?
- How does string relate to dogshop?

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

