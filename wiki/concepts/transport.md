---
page_id: 'concept:transport'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: transport
source_class: first_party
tags:
  - concept
source_ids:
  - 23-the-vacant-cell-4774271c
  - 25-the-manifesto-ebee95e5
  - 26-the-compilers-528e2d40
project_ids: []
node_ids:
  - 'concept:transport'
freshness: fresh
status: active
confidence: 0.95
created_at: '2026-05-03T03:56:35.848Z'
updated_at: '2026-05-03T05:32:23.361Z'
compiled_from:
  - 23-the-vacant-cell-4774271c
  - 25-the-manifesto-ebee95e5
  - 26-the-compilers-528e2d40
managed_by: system
backlinks:
  - 'source:23-the-vacant-cell-4774271c'
  - 'source:25-the-manifesto-ebee95e5'
  - 'source:26-the-compilers-528e2d40'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  23-the-vacant-cell-4774271c: 4774271cc1bf1964123bd9509b70c087876d8c93e1cccafe2cba1b8f675a1201
  25-the-manifesto-ebee95e5: ebee95e5be890a0453ea6f134aac6ba3a1e7ed9805f1969f883fae31f58f7c36
  26-the-compilers-528e2d40: 528e2d40f810c4a70487e948c61ce13b7bb2371912e617da8f84ec7275ee4f0d
source_semantic_hashes:
  23-the-vacant-cell-4774271c: 51f351bfe72d5b0663faefd06285ececa5c6c002d96380dda5612cb885a6b42b
  25-the-manifesto-ebee95e5: 155d8377a8ba39fa4ebb49a0a734236cf5bf3937a1af986244a609d7ee43e7db
  26-the-compilers-528e2d40: c6ab47c3c5619fa69bfd08925eb3f579d70e7a22bc77a20dbd51ae18a4bc3618
---
# transport

## Summary

Frequently referenced concept in #23 — The Vacant Cell.

## Seen In

- [[sources/23-the-vacant-cell-4774271c|#23 — The Vacant Cell]]
- [[sources/25-the-manifesto-ebee95e5|#25 — The Manifesto]]
- [[sources/26-the-compilers-528e2d40|#26 — The Compilers]]

## Source Claims

- title: #23 — The Vacant Cell description: We asked: does a protocol exist that describes operations without opinion on transport, format, or consumer — and solves the expression problem? [source:23-the-vacant-cell-4774271c]
- URI + man pages + Transport + nothing. [source:25-the-manifesto-ebee95e5]
- # The Compilers ## N Worlds, M Contracts mermaid %%{init: {"flowchart": {"defaultRenderer": "elk"}}}%% graph LR TT1["auth/bearer"]:::trait TT2["otel/span"]:::trait TT3["cache/ttl"]:::trait T1["HTTP"]:::transport T2["gRPC"]:::transport T3["Kafka"]:::transport T4["WebSocket"]:::transport T5["MQTT"]:::transport T6["SMTP"]:::transport T7["stdin/stdout"]:::transport T8["carrier pigeon"]:::transport Core((("URI + Op"))) L1["Go"]:::lang L2["Rust"]:::lang L3["Python"]:::lang L4["TypeScript"]:::lang L5["PHP"]:::lang L6["Java"]:::lang BT1["cli/command"]:::trait BT2["http/method"]:::trait BT3["region/eu"]:::trait TT1 <-.-> Core TT2 <-.-> Core TT3 <-.-> Core T1 <-.-> Core T2 <-.-> Core T3 <-.-> Core T4 <-.-> Core T5 <-.-> Core T6 <-.-> Core T7 <-.-> Core T8 <-.-> Core Core <-.-> L1 Core <-.-> L2 Core <-.-> L3 Core <-.-> L4 Core <-.-> L5 Core <-.-> L6 Core <-.-> BT1 Core <-.-> BT2 Core <-.-> BT3 classDef transport fill:#4a9eff,color:#fff,stroke:#4a9eff classDef lang fill:#ffd43b,color:#000,stroke:#ffd43b classDef trait fill:#868e96,color:#fff,stroke:#868e96 style Core fill:#22c55e,color:#000,stroke:#000,stroke-width:4px The core is two atoms: URI + Op . [source:26-the-compilers-528e2d40]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

