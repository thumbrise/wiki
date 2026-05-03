---
page_id: 'source:operation-v1-f6c2a6fb'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: operation.v1
source_class: first_party
tags:
  - source
source_ids:
  - operation-v1-f6c2a6fb
project_ids: []
node_ids:
  - 'source:operation-v1-f6c2a6fb'
  - 'concept:json'
  - 'concept:rail'
  - 'concept:https'
  - 'concept:operation'
  - 'concept:description'
  - 'concept:github'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T05:11:46.046Z'
updated_at: '2026-05-03T05:32:23.254Z'
compiled_from:
  - operation-v1-f6c2a6fb
managed_by: system
backlinks:
  - 'concept:json'
  - 'concept:rail'
  - 'concept:https'
  - 'concept:operation'
  - 'concept:description'
  - 'concept:github'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  operation-v1-f6c2a6fb: f6c2a6fb02547a5c23c901951f58c5f9b955a807ec41ffa70e505b6eb794d9cd
source_semantic_hashes:
  operation-v1-f6c2a6fb: f6c2a6fb02547a5c23c901951f58c5f9b955a807ec41ffa70e505b6eb794d9cd
---
# operation.v1

Source ID: `operation-v1-f6c2a6fb`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/op/docs/reference/operation.v1.json`

Source Class: `first_party`


## Source Details

- format: json
- top level type: object
- top level size: 5
- nested depth: 5


## Summary

operation.v1 Format: JSON Top-level: object Size: 5 Nested depth: 5 ## Schema - $schema: string - $id: string - title: string - description: string - allOf: array (2 items) ## Preview json { "$schema": "https://json-schema.org/draft/2020-12/schema", "$id": "https://thumbrise.github.io/op/reference/operation.v1.json", "title": "OP Operation", "description": "An operation is the fundamental primitive of computation — a named unit of work with typed input, typed output, and the possibility of failure. The same structure appears at every level: transistors, syscalls, functions, services, legal proceedings, speech acts. Op does not invent this structure.

## Concepts

- [[concepts/json|json]]: Frequently referenced concept in operation.v1.
- [[concepts/rail|rail]]: Frequently referenced concept in operation.v1.
- [[concepts/https|https]]: Frequently referenced concept in operation.v1.
- [[concepts/operation|operation]]: Frequently referenced concept in operation.v1.
- [[concepts/description|description]]: Frequently referenced concept in operation.v1.
- [[concepts/github|github]]: Frequently referenced concept in operation.v1.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in operation.v1.
- [[entities/top|Top-]]: Named entity mentioned in operation.v1.
- [[entities/size|Size:]]: Named entity mentioned in operation.v1.
- [[entities/nested|Nested]]: Named entity mentioned in operation.v1.
- [[entities/schema|Schema -]]: Named entity mentioned in operation.v1.
- [[entities/preview|Preview]]: Named entity mentioned in operation.v1.

## Claims

- operation.v1 Format: JSON Top-level: object Size: 5 Nested depth: 5 ## Schema - $schema: string - $id: string - title: string - description: string - allOf: array (2 items) ## Preview json { "$schema": "https://json-schema.org/draft/2020-12/schema", "$id": "https://thumbrise.github.io/op/reference/operation.v1.json", "title": "OP Operation", "description": "An operation is the fundamental primitive of computation — a named unit of work with typed input, typed output, and the possibility of failure. [source:operation-v1-f6c2a6fb]
- The same structure appears at every level: transistors, syscalls, functions, services, legal proceedings, speech acts. [source:operation-v1-f6c2a6fb]
- Op does not invent this structure. [source:operation-v1-f6c2a6fb]
- Op formalizes it.", "allOf": [ { "$ref": "https://thumbrise.github.io/op/reference/nota.v1.json" }, { "type": "object", "properties": { "input": { "$ref": "https://thumbrise.github.io/op/reference/rail.v1.json", "description": "The input rail. [source:operation-v1-f6c2a6fb]

## Questions

- How does json relate to operation.v1?
- How does rail relate to operation.v1?
- How does https relate to operation.v1?

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

