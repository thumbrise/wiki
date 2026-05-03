---
page_id: 'concept:core'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: core
source_class: first_party
tags:
  - concept
source_ids:
  - 23-treaty-ba942823
  - 26-the-compilers-528e2d40
  - 28-dobby-is-free-6542412c
  - dogshop-invalid-17d19246
  - dogshop-invalid-253ae2d9
project_ids: []
node_ids:
  - 'concept:core'
freshness: fresh
status: active
confidence: 0.95
created_at: '2026-05-03T03:56:35.849Z'
updated_at: '2026-05-03T05:32:23.362Z'
compiled_from:
  - 23-treaty-ba942823
  - 26-the-compilers-528e2d40
  - 28-dobby-is-free-6542412c
  - dogshop-invalid-17d19246
  - dogshop-invalid-253ae2d9
managed_by: system
backlinks:
  - 'source:23-treaty-ba942823'
  - 'source:26-the-compilers-528e2d40'
  - 'source:28-dobby-is-free-6542412c'
  - 'source:dogshop-invalid-17d19246'
  - 'source:dogshop-invalid-253ae2d9'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  23-treaty-ba942823: ba942823fa87e6d0b955aee5914908ed6ea0378e741ce04f840066804ceef7b5
  26-the-compilers-528e2d40: 528e2d40f810c4a70487e948c61ce13b7bb2371912e617da8f84ec7275ee4f0d
  28-dobby-is-free-6542412c: 6542412c650ff2e2872c9e5a44632db8ef11cd9012068f3862510db4dacf27e2
  dogshop-invalid-17d19246: 17d19246552f4b4b92f9ad6f73cb2e449dd8ca281b76a2d8a526a5ec77631704
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
source_semantic_hashes:
  23-treaty-ba942823: e5375a34e9c460f4d0e86f6d2871549349902b640ec4ff74405042224c7bfa0e
  26-the-compilers-528e2d40: c6ab47c3c5619fa69bfd08925eb3f579d70e7a22bc77a20dbd51ae18a4bc3618
  28-dobby-is-free-6542412c: 0cbac4e80d7201a12221f9add4708a66552f2cfcc912f48c18c50ff38ffe0c57
  dogshop-invalid-17d19246: 17d19246552f4b4b92f9ad6f73cb2e449dd8ca281b76a2d8a526a5ec77631704
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
---
# core

## Summary

Frequently referenced concept in #23 — Treaty.

## Seen In

- [[sources/23-treaty-ba942823|#23 — Treaty]]
- [[sources/26-the-compilers-528e2d40|#26 — The Compilers]]
- [[sources/28-dobby-is-free-6542412c|#28 — Dobby Is Free]]
- [[sources/dogshop-invalid-17d19246|dogshop_invalid]]
- [[sources/dogshop-invalid-253ae2d9|dogshop_invalid]]

## Source Claims

- # The Compilers ## N Worlds, M Contracts mermaid %%{init: {"flowchart": {"defaultRenderer": "elk"}}}%% graph LR TT1["auth/bearer"]:::trait TT2["otel/span"]:::trait TT3["cache/ttl"]:::trait T1["HTTP"]:::transport T2["gRPC"]:::transport T3["Kafka"]:::transport T4["WebSocket"]:::transport T5["MQTT"]:::transport T6["SMTP"]:::transport T7["stdin/stdout"]:::transport T8["carrier pigeon"]:::transport Core((("URI + Op"))) L1["Go"]:::lang L2["Rust"]:::lang L3["Python"]:::lang L4["TypeScript"]:::lang L5["PHP"]:::lang L6["Java"]:::lang BT1["cli/command"]:::trait BT2["http/method"]:::trait BT3["region/eu"]:::trait TT1 <-.-> Core TT2 <-.-> Core TT3 <-.-> Core T1 <-.-> Core T2 <-.-> Core T3 <-.-> Core T4 <-.-> Core T5 <-.-> Core T6 <-.-> Core T7 <-.-> Core T8 <-.-> Core Core <-.-> L1 Core <-.-> L2 Core <-.-> L3 Core <-.-> L4 Core <-.-> L5 Core <-.-> L6 Core <-.-> BT1 Core <-.-> BT2 Core <-.-> BT3 classDef transport fill:#4a9eff,color:#fff,stroke:#4a9eff classDef lang fill:#ffd43b,color:#000,stroke:#ffd43b classDef trait fill:#868e96,color:#fff,stroke:#868e96 style Core fill:#22c55e,color:#000,stroke:#000,stroke-width:4px The core is two atoms: URI + Op . [source:26-the-compilers-528e2d40]
- title: #28 — Dobby Is Free description: Op core is schema. [source:28-dobby-is-free-6542412c]
- dogshop_invalid Format: JSON Top-level: object Size: 3 Nested depth: 5 ## Schema - $schema: string - version: string - operations: array (3 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/reference/instruction.v1.json", "version": "1.0.0", "operations": [ { "comment": "Missing operation id — core schema violation.", "input": [ {"id": "breed", "kind": "string"} ], "output": [], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "POST"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "/dogs/buy"} ] }, { "id": "ListBreeds", "comment": "Unknown kind 'integere' — core schema violation. [source:dogshop-invalid-17d19246]
- Output term without id — core schema violation. [source:dogshop-invalid-17d19246]
- Missing leading slash in http/path — universal/http convention violation.", "input": [ {"id": "size", "kind": "integere"} ], "output": [ {"kind": "string"} ], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "FETCH"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "breeds"} ] }, { "id": "GetOrder", "comment": "Enum without 'of' — core schema violation. [source:dogshop-invalid-17d19246]
- Term without id inside rail — core schema violation.", "input": [ {"id": "orderId", "kind": "string", "required": true} ], "output": [ { "id": "status", … [source:dogshop-invalid-17d19246]
- dogshop_invalid Format: JSON Top-level: object Size: 3 Nested depth: 5 ## Schema - $schema: string - version: string - operations: array (3 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "comment": "Missing operation id — core schema violation.", "input": [ {"id": "breed", "kind": "string"} ], "output": [], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "POST"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "/dogs/buy"} ] }, { "id": "ListBreeds", "comment": "Unknown kind 'integere' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Output term without id — core schema violation. [source:dogshop-invalid-253ae2d9]
- Missing leading slash in http/path — universal/http convention violation.", "input": [ {"id": "size", "kind": "integere"} ], "output": [ {"kind": "string"} ], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "FETCH"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "breeds"} ] }, { "id": "GetOrder", "comment": "Enum without 'of' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Term without id inside rail — core schema violation.", "input": [ {"id": "orderId", "kind": "string", "required": true} ], "output": [ { "id": "status", … [source:dogshop-invalid-253ae2d9]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

