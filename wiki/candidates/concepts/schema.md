---
page_id: 'concept:schema'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: schema
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - dogshop-eb60bfe2
  - dogshop-invalid-253ae2d9
  - taskfile-83d1d929
  - three-atoms-28e52786
project_ids: []
node_ids:
  - 'concept:schema'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.856Z'
updated_at: '2026-05-03T04:02:08.790Z'
compiled_from:
  - dogshop-eb60bfe2
  - dogshop-invalid-253ae2d9
  - taskfile-83d1d929
  - three-atoms-28e52786
managed_by: system
backlinks:
  - 'source:dogshop-eb60bfe2'
  - 'source:dogshop-invalid-253ae2d9'
  - 'source:taskfile-83d1d929'
  - 'source:three-atoms-28e52786'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
  three-atoms-28e52786: 28e52786ebcc39448defbb5a4dc799086bb28b700f539fb9d0c6a6113655fc4c
source_semantic_hashes:
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
  three-atoms-28e52786: 8fca0b33119b7c2e29e3805eb6fbefbef508f37dc42b48f1fe60047141018eed
---
# schema

## Summary

Frequently referenced concept in dogshop.

## Seen In

- [[sources/dogshop-eb60bfe2|dogshop]]
- [[sources/dogshop-invalid-253ae2d9|dogshop_invalid]]
- [[sources/taskfile-83d1d929|Taskfile]]
- [[sources/three-atoms-28e52786|Three Atoms]]

## Source Claims

- dogshop Format: JSON Top-level: object Size: 3 Nested depth: 9 ## Schema - $schema: string - version: string - operations: array (6 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "id": "BuyDog", "comment": "Purchase a dog by breed with a budget limit. [source:dogshop-eb60bfe2]
- dogshop_invalid Format: JSON Top-level: object Size: 3 Nested depth: 5 ## Schema - $schema: string - version: string - operations: array (3 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "comment": "Missing operation id — core schema violation.", "input": [ {"id": "breed", "kind": "string"} ], "output": [], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "POST"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "/dogs/buy"} ] }, { "id": "ListBreeds", "comment": "Unknown kind 'integere' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Output term without id — core schema violation. [source:dogshop-invalid-253ae2d9]
- Missing leading slash in http/path — universal/http convention violation.", "input": [ {"id": "size", "kind": "integere"} ], "output": [ {"kind": "string"} ], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "FETCH"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "breeds"} ] }, { "id": "GetOrder", "comment": "Enum without 'of' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Term without id inside rail — core schema violation.", "input": [ {"id": "orderId", "kind": "string", "required": true} ], "output": [ { "id": "status", … [source:dogshop-invalid-253ae2d9]
- Taskfile Format: YAML Top-level: object Size: 2 Nested depth: 4 ## Schema - version: string - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' tasks: lint: desc: Run lint with auto-fix where possible (dev workflow) cmds: - golangci-lint run --fix - go tool license-eye header fix lint:ci: desc: Run lint checks without auto-fix (CI workflow) cmds: - golangci-lint run - go tool license-eye header check test: desc: Run tests cmds: - go test ./... [source:taskfile-83d1d929]
- title: Three Atoms description: We formalized the schema. [source:three-atoms-28e52786]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

