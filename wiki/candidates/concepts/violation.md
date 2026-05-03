---
page_id: 'concept:violation'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: violation
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - dogshop-invalid-253ae2d9
project_ids: []
node_ids:
  - 'concept:violation'
freshness: fresh
status: candidate
confidence: 0.65
created_at: '2026-05-03T03:56:35.856Z'
updated_at: '2026-05-03T04:02:08.790Z'
compiled_from:
  - dogshop-invalid-253ae2d9
managed_by: system
backlinks:
  - 'source:dogshop-invalid-253ae2d9'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
source_semantic_hashes:
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
---
# violation

## Summary

Frequently referenced concept in dogshop_invalid.

## Seen In

- [[sources/dogshop-invalid-253ae2d9|dogshop_invalid]]

## Source Claims

- dogshop_invalid Format: JSON Top-level: object Size: 3 Nested depth: 5 ## Schema - $schema: string - version: string - operations: array (3 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "comment": "Missing operation id — core schema violation.", "input": [ {"id": "breed", "kind": "string"} ], "output": [], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "POST"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "/dogs/buy"} ] }, { "id": "ListBreeds", "comment": "Unknown kind 'integere' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Output term without id — core schema violation. [source:dogshop-invalid-253ae2d9]
- Missing leading slash in http/path — universal/http convention violation.", "input": [ {"id": "size", "kind": "integere"} ], "output": [ {"kind": "string"} ], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "FETCH"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "breeds"} ] }, { "id": "GetOrder", "comment": "Enum without 'of' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Term without id inside rail — core schema violation.", "input": [ {"id": "orderId", "kind": "string", "required": true} ], "output": [ { "id": "status", … [source:dogshop-invalid-253ae2d9]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

