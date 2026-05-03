---
page_id: 'source:op-33cc57bb'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: op
source_class: first_party
tags:
  - source
  - computation-theory
  - protocol-design
  - api-design
  - software-architecture
  - systems-thinking
source_ids:
  - op-33cc57bb
project_ids: []
node_ids:
  - 'source:op-33cc57bb'
  - 'concept:operation-the-primitive'
  - 'concept:traits'
  - 'concept:instructions'
  - 'concept:convergent-evolution'
  - 'entity:op-protocol-structure'
  - 'entity:emitter'
  - 'entity:receiver'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T05:11:46.043Z'
updated_at: '2026-05-03T05:32:23.251Z'
compiled_from:
  - op-33cc57bb
managed_by: system
backlinks:
  - 'concept:operation-the-primitive'
  - 'concept:traits'
  - 'concept:instructions'
  - 'concept:convergent-evolution'
  - 'entity:op-protocol-structure'
  - 'entity:emitter'
  - 'entity:receiver'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  op-33cc57bb: 33cc57bbf0d775f6560a13186997522fd8c720ae5d7a763798c96322306bd3d1
source_semantic_hashes:
  op-33cc57bb: ae9ed0f42f4e94a512bc7eda80a7ef26d2f2fa0b6a368a1116ae3b393eee1d7a
---
# op

Source ID: `op-33cc57bb`
Source Kind: `markdown`
Source Path: `/Users/rk/GolandProjects/op/README.md`

Source Class: `first_party`


## Summary

Op is a proposed universal and formal protocol that defines the operation as a fundamental primitive of computation. It standardizes operations using five core fields (`id`, `comment`, `input`, `output`, `errors`) and external `Traits`, thereby creating an instruction format that transcends specific technologies, languages, or vendor-specific frameworks (like OpenAPI or gRPC).

## Concepts

- [[concepts/operation-the-primitive|Operation (The Primitive)]]: The fundamental, universal primitive of computation. This concept posits that every action—from a syscall to a biological reaction—is an operation, formalized by the structure of input, output, and potential error.
- [[concepts/traits|Traits]]: Namespaced key-value extensions attached externally to the core operation definition. Traits are considered 'opinions' (e.g., HTTP routes, gRPC services) that augment the operation without changing its underlying factual structure.
- [[concepts/instructions|Instructions]]: Versioned, fully resolved units that represent the operation flowing between two systems. These instructions are designed to facilitate a 'N + M' integration model, meaning new emitters or receivers can connect independently.
- [[concepts/convergent-evolution|Convergent Evolution]]: The finding that the concept of 'operation' has independently evolved across wildly disparate disciplines, including quantum mechanics, biology, neuroscience, and economics, suggesting a universal underlying pattern.

## Entities

- [[entities/op-protocol-structure|Op Protocol Structure]]: The defined formal structure for an operation, consisting of five required fields: `id`, `comment`, `input`, `output`, and `errors`.
- [[entities/emitter|Emitter]]: A system or mechanism responsible for generating an operation or instruction. Examples include DSL compilers, scrapers, or handwritten JSON sources.
- [[entities/receiver|Receiver]]: A system or mechanism responsible for consuming and understanding a generated operation instruction. Examples include framework compilers, documentation portals, or AI tool registries.

## Claims

- The operation is defined by five core fields: `id`, `comment`, `input`, `output`, and `errors`. [source:op-33cc57bb]
- Op attempts to name the universal form of the operation itself, independent of specific transports, languages, or vendors. [source:op-33cc57bb]
- The protocol suggests that integrating N emitters and M receivers should scale as N + M, rather than the traditional N × M. [source:op-33cc57bb]
- Op functions as a boundary between the physics of interaction and the layer of technological 'opinions' built above it; it is not itself a framework or compiler. [source:op-33cc57bb]
- The operation has been observed to evolve across fourteen different disciplines (e.g., quantum mechanics, biology, game theory, economics). [source:op-33cc57bb]

## Questions

- How does Op achieve cross-language and cross-platform compilation via Instructions?
- What are the practical constraints or limits placed on the definition of 'Traits'?
- How does Op Protocol handle the initial problem of bootstrapping adoption without a central authority?
- Can the formalization of the operation be shown to replace the necessity of existing industry standards (like OpenAPI)?
- What is the difference between 'The Operation' and 'The Instruction' in practical implementation?

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

