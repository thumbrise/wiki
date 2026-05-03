---
page_id: 'source:dogshop-invalid-253ae2d9'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: dogshop_invalid
source_class: first_party
tags:
  - source
source_ids:
  - dogshop-invalid-253ae2d9
project_ids: []
node_ids:
  - 'source:dogshop-invalid-253ae2d9'
  - 'concept:schema'
  - 'concept:http'
  - 'concept:violation'
  - 'concept:core'
  - 'concept:github'
  - 'concept:kind'
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
updated_at: '2026-05-03T05:32:23.221Z'
compiled_from:
  - dogshop-invalid-253ae2d9
managed_by: system
backlinks:
  - 'concept:schema'
  - 'concept:http'
  - 'concept:violation'
  - 'concept:core'
  - 'concept:github'
  - 'concept:kind'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
source_semantic_hashes:
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
---
# dogshop_invalid

Source ID: `dogshop-invalid-253ae2d9`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/wiki/state/sources/github_repo-thumbrise-op-a16ed6ba/checkout/universal/fixtures/dogshop_invalid.json`

Source Class: `first_party`


## Source Details

- format: json
- top level type: object
- top level size: 3
- nested depth: 5


## Summary

dogshop_invalid Format: JSON Top-level: object Size: 3 Nested depth: 5 ## Schema - $schema: string - version: string - operations: array (3 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "comment": "Missing operation id — core schema violation.", "input": [ {"id": "breed", "kind": "string"} ], "output": [], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "POST"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "/dogs/buy"} ] }, { "id": "ListBreeds", "comment": "Unknown kind 'integere' — core schema violation. Output term without id — core schema violation. Missing leading slash in http/path — universal/http convention violation.", "input": [ {"id": "size", "kind": "integere"} ], "output": [ {"kind": "string"} ], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "FETCH"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "breeds"} ] }, { "id": "GetOrder", "comment": "Enum without 'of' — core schema violation.

## Concepts

- [[concepts/schema|schema]]: Frequently referenced concept in dogshop_invalid.
- [[concepts/http|http]]: Frequently referenced concept in dogshop_invalid.
- [[concepts/violation|violation]]: Frequently referenced concept in dogshop_invalid.
- [[concepts/core|core]]: Frequently referenced concept in dogshop_invalid.
- [[concepts/github|github]]: Frequently referenced concept in dogshop_invalid.
- [[concepts/kind|kind]]: Frequently referenced concept in dogshop_invalid.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in dogshop_invalid.
- [[entities/top|Top-]]: Named entity mentioned in dogshop_invalid.
- [[entities/size|Size:]]: Named entity mentioned in dogshop_invalid.
- [[entities/nested|Nested]]: Named entity mentioned in dogshop_invalid.
- [[entities/schema|Schema -]]: Named entity mentioned in dogshop_invalid.
- [[entities/preview|Preview]]: Named entity mentioned in dogshop_invalid.

## Claims

- dogshop_invalid Format: JSON Top-level: object Size: 3 Nested depth: 5 ## Schema - $schema: string - version: string - operations: array (3 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "comment": "Missing operation id — core schema violation.", "input": [ {"id": "breed", "kind": "string"} ], "output": [], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "POST"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "/dogs/buy"} ] }, { "id": "ListBreeds", "comment": "Unknown kind 'integere' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Output term without id — core schema violation. [source:dogshop-invalid-253ae2d9]
- Missing leading slash in http/path — universal/http convention violation.", "input": [ {"id": "size", "kind": "integere"} ], "output": [ {"kind": "string"} ], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "FETCH"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "breeds"} ] }, { "id": "GetOrder", "comment": "Enum without 'of' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Term without id inside rail — core schema violation.", "input": [ {"id": "orderId", "kind": "string", "required": true} ], "output": [ { "id": "status", … [source:dogshop-invalid-253ae2d9]

## Questions

- How does schema relate to dogshop_invalid?
- How does http relate to dogshop_invalid?
- How does violation relate to dogshop_invalid?

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

