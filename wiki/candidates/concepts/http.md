---
page_id: 'concept:http'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: http
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - 17-the-gallium-28cb4937
  - 2-research-trail-834ba4c9
  - 22-the-dream-layer-d04b39b6
  - 28-dobby-is-free-6542412c
  - dogshop-invalid-253ae2d9
  - universal-roadmap-8fa1b496
project_ids: []
node_ids:
  - 'concept:http'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.846Z'
updated_at: '2026-05-03T04:02:08.759Z'
compiled_from:
  - 17-the-gallium-28cb4937
  - 2-research-trail-834ba4c9
  - 22-the-dream-layer-d04b39b6
  - 28-dobby-is-free-6542412c
  - dogshop-invalid-253ae2d9
  - universal-roadmap-8fa1b496
managed_by: system
backlinks:
  - 'source:17-the-gallium-28cb4937'
  - 'source:2-research-trail-834ba4c9'
  - 'source:22-the-dream-layer-d04b39b6'
  - 'source:28-dobby-is-free-6542412c'
  - 'source:dogshop-invalid-253ae2d9'
  - 'source:universal-roadmap-8fa1b496'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  17-the-gallium-28cb4937: 28cb4937532b29517481f880be822bdc3e06e17cfe37f6144777c46b846bf53c
  2-research-trail-834ba4c9: 834ba4c932429a78418131c534ceeedfc10c87b8150571a61a66d4756374ebfc
  22-the-dream-layer-d04b39b6: d04b39b661d77ccee4c38261c816dcc64e58502164a3914b707641c9ded169e5
  28-dobby-is-free-6542412c: 6542412c650ff2e2872c9e5a44632db8ef11cd9012068f3862510db4dacf27e2
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
  universal-roadmap-8fa1b496: 8fa1b496bddaca96aeb1ec75f410a259e0a782001bd3674786339faf2530c390
source_semantic_hashes:
  17-the-gallium-28cb4937: 77d91ef13795c6408d26933851fd3c9865b14036a177f812ed6873b2e5bc51b4
  2-research-trail-834ba4c9: 3a63f60a01ea78134dfc591567a1eaeb24b7ca70f375b8a3f27a5ebcaa09c9ae
  22-the-dream-layer-d04b39b6: 69926a8647ec8013995a3ed108f6d4f4a249d98fe484087957f3bdd86f889843
  28-dobby-is-free-6542412c: 0cbac4e80d7201a12221f9add4708a66552f2cfcc912f48c18c50ff38ffe0c57
  dogshop-invalid-253ae2d9: 253ae2d9214ee8fe3f7f57795b7a407907a47dcec4feeb61c7036804e79a93cb
  universal-roadmap-8fa1b496: f7f33fa3382b59ef031c0a5f9bd8f6ca483e3e46bbc72a5762ecb5b74590f6ce
---
# http

## Summary

Frequently referenced concept in #17 — The Gallium.

## Seen In

- [[sources/17-the-gallium-28cb4937|#17 — The Gallium]]
- [[sources/2-research-trail-834ba4c9|#2 — Research Trail]]
- [[sources/22-the-dream-layer-d04b39b6|#22 — The Dream Layer]]
- [[sources/28-dobby-is-free-6542412c|#28 — Dobby Is Free]]
- [[sources/dogshop-invalid-253ae2d9|dogshop_invalid]]
- [[sources/universal-roadmap-8fa1b496|universal/ — roadmap]]

## Source Claims

- title: #22 — The Dream Layer description: A dream about a parallel universe where Op existed before HTTP. [source:22-the-dream-layer-d04b39b6]
- dogshop_invalid Format: JSON Top-level: object Size: 3 Nested depth: 5 ## Schema - $schema: string - version: string - operations: array (3 items) ## Preview json { "$schema": "https://thumbrise.github.io/op/schema/instruction.v1.json", "version": "1.0.0", "operations": [ { "comment": "Missing operation id — core schema violation.", "input": [ {"id": "breed", "kind": "string"} ], "output": [], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "POST"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "/dogs/buy"} ] }, { "id": "ListBreeds", "comment": "Unknown kind 'integere' — core schema violation. [source:dogshop-invalid-253ae2d9]
- Missing leading slash in http/path — universal/http convention violation.", "input": [ {"id": "size", "kind": "integere"} ], "output": [ {"kind": "string"} ], "error": [], "trait": [ {"id": "github.com/thumbrise/op/universal/http/method", "value": "FETCH"}, {"id": "github.com/thumbrise/op/universal/http/path", "value": "breeds"} ] }, { "id": "GetOrder", "comment": "Enum without 'of' — core schema violation. [source:dogshop-invalid-253ae2d9]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

