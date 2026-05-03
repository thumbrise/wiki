---
page_id: 'concept:kind'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: kind
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - 18-the-fourth-rail-f496db69
  - 21-the-atoms-speak-72df059e
  - dogshop-eb60bfe2
  - dogshop-invalid-253ae2d9
  - the-operations-protocol-formalizing-the-missing-foundation-ff73b385
  - three-atoms-28e52786
project_ids: []
node_ids:
  - 'concept:kind'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.846Z'
updated_at: '2026-05-03T04:02:08.759Z'
compiled_from:
  - 18-the-fourth-rail-f496db69
  - 21-the-atoms-speak-72df059e
  - dogshop-eb60bfe2
  - dogshop-invalid-253ae2d9
  - the-operations-protocol-formalizing-the-missing-foundation-ff73b385
  - three-atoms-28e52786
managed_by: system
backlinks:
  - 'source:18-the-fourth-rail-f496db69'
  - 'source:21-the-atoms-speak-72df059e'
  - 'source:dogshop-eb60bfe2'
  - 'source:dogshop-invalid-253ae2d9'
  - 'source:the-operations-protocol-formalizing-the-missing-foundation-ff73b385'
  - 'source:three-atoms-28e52786'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  18-the-fourth-rail-f496db69: f496db6928de75bf0c47baad6b39a774ee6263ec366a82c73713783bfa4dbf3c
  21-the-atoms-speak-72df059e: 72df059e64851801fcaefe73fc9e7322504934f0578bf5e51ecc6887a373c643
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
  the-operations-protocol-formalizing-the-missing-foundation-ff73b385: ff73b38575ea2e2edff4f4d0e9560a275a7c89cb4b562ac55a9bdda77604e211
  three-atoms-28e52786: 28e52786ebcc39448defbb5a4dc799086bb28b700f539fb9d0c6a6113655fc4c
source_semantic_hashes:
  18-the-fourth-rail-f496db69: 9ed26794d6a1d8b75e0f1b394d68bcd83df036b4555f4c12d6cf366ad9ff8521
  21-the-atoms-speak-72df059e: 7f72433e89d6dccf441b0350ce5088e224c1d2be568abf04f159bf0fca499ca9
  dogshop-eb60bfe2: eb60bfe24e7f7738e400d532aa3e8e86030ef19b8d343f67af90f818436f034c
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
  the-operations-protocol-formalizing-the-missing-foundation-ff73b385: c6993d72948278892186071fffd2d959b84a2950a1ba657c78487787ca65d798
  three-atoms-28e52786: 8fca0b33119b7c2e29e3805eb6fbefbef508f37dc42b48f1fe60047141018eed
---
# kind

## Summary

Frequently referenced concept in #18 — The Fourth Rail.

## Seen In

- [[sources/18-the-fourth-rail-f496db69|#18 — The Fourth Rail]]
- [[sources/21-the-atoms-speak-72df059e|#21 — The Atoms Speak]]
- [[sources/dogshop-eb60bfe2|dogshop]]
- [[sources/dogshop-invalid-253ae2d9|dogshop_invalid]]
- [[sources/the-operations-protocol-formalizing-the-missing-foundation-ff73b385|The Operations Protocol: Formalizing the Missing Foundation]]
- [[sources/three-atoms-28e52786|Three Atoms]]

## Source Claims

- Demonstrates object composition, enum choice, and compound traits.", "input": [ { "id": "breed", "kind": "string", "required": true, "comment": "Exact breed name, e.g. [source:dogshop-eb60bfe2]
- \"labrador\"" }, { "id": "budget", "kind": "integer", "required": true, "comment": "Maximum price in cents" }, { "id": "express", "kind": "boolean", "comment": "Next-day delivery" }, { "id": "deliveryAddress", "kind": "object", "comment": "Where to deliver the dog", "of": [ {"id": "street", "kind": "string"}, {"id": "city", "kind": "string"}, {"id": "zip", "kind": "string", "comment": "Postal code, not an archive"}, {"id": "country", "kind": "string", "value": "US", "comment": "ISO 3166-1 alpha-2"} ] }, { "id": "preferredSize", "kind": "enum", "comment": "Desired dog size category", … [source:dogshop-eb60bfe2]
- dogshop_invalid Format: JSON Top-level: object Size: 3 Nested depth: 5 ## Schema - $schema: string - version: string - operations: array (3 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "comment": "Missing operation id — core schema violation.", "input": [ {"id": "breed", "kind": "string"} ], "output": [], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "POST"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "/dogs/buy"} ] }, { "id": "ListBreeds", "comment": "Unknown kind 'integere' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Missing leading slash in http/path — universal/http convention violation.", "input": [ {"id": "size", "kind": "integere"} ], "output": [ {"kind": "string"} ], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "FETCH"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "breeds"} ] }, { "id": "GetOrder", "comment": "Enum without 'of' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Term without id inside rail — core schema violation.", "input": [ {"id": "orderId", "kind": "string", "required": true} ], "output": [ { "id": "status", … [source:dogshop-invalid-253ae2d9]
- Nine kinds. [source:three-atoms-28e52786]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

