---
page_id: 'concept:type'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: type
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - composer-c80b8ea8
  - instruction-v1-e3a3cb1e
  - package-945abd34
  - review-guidelines-0fa832f7
  - the-contract-that-wouldn-t-break-fa2e5b4e
  - the-operations-protocol-formalizing-the-missing-foundation-ff73b385
project_ids: []
node_ids:
  - 'concept:type'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.854Z'
updated_at: '2026-05-03T04:02:08.784Z'
compiled_from:
  - composer-c80b8ea8
  - instruction-v1-e3a3cb1e
  - package-945abd34
  - review-guidelines-0fa832f7
  - the-contract-that-wouldn-t-break-fa2e5b4e
  - the-operations-protocol-formalizing-the-missing-foundation-ff73b385
managed_by: system
backlinks:
  - 'source:composer-c80b8ea8'
  - 'source:instruction-v1-e3a3cb1e'
  - 'source:package-945abd34'
  - 'source:review-guidelines-0fa832f7'
  - 'source:the-contract-that-wouldn-t-break-fa2e5b4e'
  - 'source:the-operations-protocol-formalizing-the-missing-foundation-ff73b385'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  composer-c80b8ea8: c80b8ea8d5b7cacc8b3e9212ae9a1f8582b0aa0407ad868af570f6d4796a4296
  instruction-v1-e3a3cb1e: e3a3cb1e9f7fddff5e421a4c2c7209456267bc665df1e3c3b04a6e746ec057ff
  package-945abd34: 945abd3421905b11b7471174be4411d2260d3273ea87a5fba0f499658fcd6a8f
  review-guidelines-0fa832f7: 0fa832f778609962f503d542a7b3935fed1b19e696adfc0a25c9c449fdec1671
  the-contract-that-wouldn-t-break-fa2e5b4e: fa2e5b4ebf76fc46bd8cc00c8d78e58853a39644954c11effa864806f9281324
  the-operations-protocol-formalizing-the-missing-foundation-ff73b385: ff73b38575ea2e2edff4f4d0e9560a275a7c89cb4b562ac55a9bdda77604e211
source_semantic_hashes:
  composer-c80b8ea8: c80b8ea8d5b7cacc8b3e9212ae9a1f8582b0aa0407ad868af570f6d4796a4296
  instruction-v1-e3a3cb1e: e3a3cb1e9f7fddff5e421a4c2c7209456267bc665df1e3c3b04a6e746ec057ff
  package-945abd34: 945abd3421905b11b7471174be4411d2260d3273ea87a5fba0f499658fcd6a8f
  review-guidelines-0fa832f7: 7aafafffc8141da2d86fcc392ab37fb5e6705985bc66d62b99c01e6ba2d95f35
  the-contract-that-wouldn-t-break-fa2e5b4e: 7cec547ab787f621de98dedd007328cee05b1aa46b45f3d28aca2076cf9f54d0
  the-operations-protocol-formalizing-the-missing-foundation-ff73b385: c6993d72948278892186071fffd2d959b84a2950a1ba657c78487787ca65d798
---
# type

## Summary

Frequently referenced concept in composer.

## Seen In

- [[sources/composer-c80b8ea8|composer]]
- [[sources/instruction-v1-e3a3cb1e|instruction.v1]]
- [[sources/package-945abd34|package]]
- [[sources/review-guidelines-0fa832f7|Review Guidelines]]
- [[sources/the-contract-that-wouldn-t-break-fa2e5b4e|The Contract That Wouldn't Break]]
- [[sources/the-operations-protocol-formalizing-the-missing-foundation-ff73b385|The Operations Protocol: Formalizing the Missing Foundation]]

## Source Claims

- composer Format: JSON Top-level: object Size: 6 Nested depth: 3 ## Schema - name: string - description: string - license: string - type: string - autoload: object (1 keys) - require: object (1 keys) ## Preview json { "name": "thumbrise/op", "description": "Operation Protocol SDK — PHP type definitions", "license": "Apache-2.0", "type": "library", "autoload": { "files": [ "op.php" ] }, "require": { "php": ">=8.1" } } [source:composer-c80b8ea8]
- instruction.v1 Format: JSON Top-level: object Size: 8 Nested depth: 6 ## Schema - $schema: string - $id: string - title: string - description: string - type: string - properties: object (2 keys) - required: array (2 items) - $defs: object (3 keys) ## Preview json { "$schema": "https://json-schema.org/draft/2020-12/schema", "$id": "https://thumbrise.github.io/op/schema/instruction.v1.json", "title": "OP", "description": "Operation Protocol Instruction. [source:instruction-v1-e3a3cb1e]
- One Term structure everywhere.", "type": "object", "properties": { "version": { "type": "string", "description": "Instruction format version. [source:instruction-v1-e3a3cb1e]
- { "name": "@thumbrise/op", "version": "0.0.0", "description": "Operation Protocol SDK — TypeScript type definitions", "license": "Apache-2.0", "type": "module", "main": "op.ts", "types": "op.ts", "files": [ "op.ts" ], "private": true } [source:package-945abd34]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

