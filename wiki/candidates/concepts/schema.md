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
  - dogshop-invalid-17d19246
  - dogshop-invalid-253ae2d9
  - nota-v1-6168c974
  - psalm-06d502d6
  - taskfile-83d1d929
  - taskfile-f98ae8d6
  - three-atoms-28e52786
  - three-atoms-f9d1fbb2
project_ids: []
node_ids:
  - 'concept:schema'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.856Z'
updated_at: '2026-05-03T05:32:23.410Z'
compiled_from:
  - dogshop-eb60bfe2
  - dogshop-invalid-17d19246
  - dogshop-invalid-253ae2d9
  - nota-v1-6168c974
  - psalm-06d502d6
  - taskfile-83d1d929
  - taskfile-f98ae8d6
  - three-atoms-28e52786
  - three-atoms-f9d1fbb2
managed_by: system
backlinks:
  - 'source:dogshop-eb60bfe2'
  - 'source:dogshop-invalid-17d19246'
  - 'source:dogshop-invalid-253ae2d9'
  - 'source:nota-v1-6168c974'
  - 'source:psalm-06d502d6'
  - 'source:taskfile-83d1d929'
  - 'source:taskfile-f98ae8d6'
  - 'source:three-atoms-28e52786'
  - 'source:three-atoms-f9d1fbb2'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
  dogshop-invalid-17d19246: 17d19246552f4b4b92f9ad6f73cb2e449dd8ca281b76a2d8a526a5ec77631704
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
  nota-v1-6168c974: 6168c974c71a876245a77631eddf8c1ee434c2a36a1aeebb43fb798cc13f1edb
  psalm-06d502d6: 06d502d6ebda56bb50ee770bb94849e5dfcb849bd5fbd0b2a38eae9d5c25adcc
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
  taskfile-f98ae8d6: f98ae8d6dc3cd54def5c849666e49c7e28626b64e252ab0317e60019a677d5fc
  three-atoms-28e52786: 28e52786ebcc39448defbb5a4dc799086bb28b700f539fb9d0c6a6113655fc4c
  three-atoms-f9d1fbb2: f9d1fbb2d5c0986964b89d76796245fbceb62decf6b2bc8cb1986ceb630d40af
source_semantic_hashes:
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
  dogshop-invalid-17d19246: 17d19246552f4b4b92f9ad6f73cb2e449dd8ca281b76a2d8a526a5ec77631704
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
  nota-v1-6168c974: 6168c974c71a876245a77631eddf8c1ee434c2a36a1aeebb43fb798cc13f1edb
  psalm-06d502d6: 06d502d6ebda56bb50ee770bb94849e5dfcb849bd5fbd0b2a38eae9d5c25adcc
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
  taskfile-f98ae8d6: f98ae8d6dc3cd54def5c849666e49c7e28626b64e252ab0317e60019a677d5fc
  three-atoms-28e52786: 8fca0b33119b7c2e29e3805eb6fbefbef508f37dc42b48f1fe60047141018eed
  three-atoms-f9d1fbb2: fa06a5f23478302b62c0d41b964c41bf6327b63806b67bf2dfcfc744eade434a
---
# schema

## Summary

Frequently referenced concept in dogshop.

## Seen In

- [[sources/dogshop-eb60bfe2|dogshop]]
- [[sources/dogshop-invalid-17d19246|dogshop_invalid]]
- [[sources/dogshop-invalid-253ae2d9|dogshop_invalid]]
- [[sources/nota-v1-6168c974|nota.v1]]
- [[sources/psalm-06d502d6|psalm]]
- [[sources/taskfile-83d1d929|Taskfile]]
- [[sources/taskfile-f98ae8d6|Taskfile]]
- [[sources/three-atoms-28e52786|Three Atoms]]
- [[sources/three-atoms-f9d1fbb2|Three Atoms]]

## Source Claims

- dogshop Format: JSON Top-level: object Size: 3 Nested depth: 9 ## Schema - $schema: string - version: string - operations: array (6 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "id": "BuyDog", "comment": "Purchase a dog by breed with a budget limit. [source:dogshop-eb60bfe2]
- dogshop_invalid Format: JSON Top-level: object Size: 3 Nested depth: 5 ## Schema - $schema: string - version: string - operations: array (3 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/reference/instruction.v1.json", "version": "1.0.0", "operations": [ { "comment": "Missing operation id — core schema violation.", "input": [ {"id": "breed", "kind": "string"} ], "output": [], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "POST"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "/dogs/buy"} ] }, { "id": "ListBreeds", "comment": "Unknown kind 'integere' — core schema violation. [source:dogshop-invalid-17d19246]
- Output term without id — core schema violation. [source:dogshop-invalid-17d19246]
- Missing leading slash in http/path — universal/http convention violation.", "input": [ {"id": "size", "kind": "integere"} ], "output": [ {"kind": "string"} ], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "FETCH"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "breeds"} ] }, { "id": "GetOrder", "comment": "Enum without 'of' — core schema violation. [source:dogshop-invalid-17d19246]
- Term without id inside rail — core schema violation.", "input": [ {"id": "orderId", "kind": "string", "required": true} ], "output": [ { "id": "status", … [source:dogshop-invalid-17d19246]
- dogshop_invalid Format: JSON Top-level: object Size: 3 Nested depth: 5 ## Schema - $schema: string - version: string - operations: array (3 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "comment": "Missing operation id — core schema violation.", "input": [ {"id": "breed", "kind": "string"} ], "output": [], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "POST"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "/dogs/buy"} ] }, { "id": "ListBreeds", "comment": "Unknown kind 'integere' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Output term without id — core schema violation. [source:dogshop-invalid-253ae2d9]
- Missing leading slash in http/path — universal/http convention violation.", "input": [ {"id": "size", "kind": "integere"} ], "output": [ {"kind": "string"} ], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "FETCH"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "breeds"} ] }, { "id": "GetOrder", "comment": "Enum without 'of' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Term without id inside rail — core schema violation.", "input": [ {"id": "orderId", "kind": "string", "required": true} ], "output": [ { "id": "status", … [source:dogshop-invalid-253ae2d9]
- nota.v1 Format: JSON Top-level: object Size: 7 Nested depth: 3 ## Schema - $schema: string - $id: string - title: string - description: string - type: string - properties: object (2 keys) - required: array (2 items) ## Preview json { "$schema": "https://json-schema.org/draft/2020-12/schema", "$id": "https://thumbrise.github.io/op/reference/nota.v1.json", "title": "OP Nota", "description": "A Nota is the minimal act of recognition — an id and a comment together. [source:nota-v1-6168c974]
- psalm Format: XML Top-level: object Size: 1 Nested depth: 3 ## Schema - psalm: object (1 keys) ## Preview xml <?xml version="1.0"?> <psalm errorLevel="2" resolveFromConfigFile="true" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="https://getpsalm.org/schema/config" xsi:schemaLocation="https://getpsalm.org/schema/config vendor/vimeo/psalm/config.xsd" hoistConstants="true" findUnusedPsalmSuppress="false" findUnusedVariablesAndParams="true" findUnusedBaselineEntry="true" findUnusedCode="false" ensureArrayStringOffsetsExist="true" addParamDefaultToDocblockType="true" strictBinaryOperands="true" errorBaseline="psalm-baseline.xml" > <projectFiles> <directory name="app/src"/> <ignoreFiles> <directory name="vendor"/> </ignoreFiles> </projectFiles> </psalm> [source:psalm-06d502d6]
- Taskfile Format: YAML Top-level: object Size: 2 Nested depth: 4 ## Schema - version: string - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' tasks: lint: desc: Run lint with auto-fix where possible (dev workflow) cmds: - golangci-lint run --fix - go tool license-eye header fix lint:ci: desc: Run lint checks without auto-fix (CI workflow) cmds: - golangci-lint run - go tool license-eye header check test: desc: Run tests cmds: - go test ./... [source:taskfile-83d1d929]
- Taskfile Format: YAML Top-level: object Size: 4 Nested depth: 3 ## Schema - version: string - env: object (2 keys) - dotenv: array (1 items) - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' env: DOCKER_HOST_UID: sh: id -u DOCKER_HOST_GID: sh: id -g dotenv: [ '.env', ] tasks: c: desc: docker compose и аргументы. [source:taskfile-f98ae8d6]
- title: Three Atoms description: We formalized the schema. [source:three-atoms-28e52786]
- title: Three Atoms description: We formalized the schema. [source:three-atoms-f9d1fbb2]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

