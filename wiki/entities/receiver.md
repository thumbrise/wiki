---
page_id: 'entity:receiver'
kind: entity
cssclasses:
  - swarmvault
  - sv-entity
title: Receiver
source_class: first_party
tags:
  - entity
  - api-design
  - compilers
  - computation-theory
  - distributed-systems
  - protocol-design
  - software-architecture
  - systems-thinking
source_ids:
  - 10-there-is-no-generation-35e5560a
  - op-33cc57bb
project_ids: []
node_ids:
  - 'entity:receiver'
freshness: fresh
status: active
confidence: 0.8
created_at: '2026-05-03T03:56:35.874Z'
updated_at: '2026-05-03T05:32:23.507Z'
compiled_from:
  - 10-there-is-no-generation-35e5560a
  - op-33cc57bb
managed_by: system
backlinks:
  - 'source:10-there-is-no-generation-35e5560a'
  - 'source:op-33cc57bb'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  10-there-is-no-generation-35e5560a: 35e5560a9d39aae053c80c25b8684c17a4e556a15efffebc3d8489f00837ed02
  op-33cc57bb: 33cc57bbf0d775f6560a13186997522fd8c720ae5d7a763798c96322306bd3d1
source_semantic_hashes:
  10-there-is-no-generation-35e5560a: 566d04e2b2efadd92bf08eff9c79a67d7f18d3704d4f7a45d021e1e2e19d6be6
  op-33cc57bb: ae9ed0f42f4e94a512bc7eda80a7ef26d2f2fa0b6a368a1116ae3b393eee1d7a
---
# Receiver

## Summary

A component that consumes a formal 'instruction' or 'operation' and compiles it into a specific implementation for a target platform (e.g., a REST API router or a GUI widget).

## Seen In

- [[sources/10-there-is-no-generation-35e5560a|#10 — There Is No Generation]]
- [[sources/op-33cc57bb|op]]

## Source Claims

- The Op model solves the N times M problem for operations, defining a common instruction format for N emitters and M receivers. [source:10-there-is-no-generation-35e5560a]
- In a system following this model, the backend and frontend communicate via compiled instructions, meaning nobody has to write manual bindings; two receivers read one instruction. [source:10-there-is-no-generation-35e5560a]
- The protocol suggests that integrating N emitters and M receivers should scale as N + M, rather than the traditional N × M. [source:op-33cc57bb]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

