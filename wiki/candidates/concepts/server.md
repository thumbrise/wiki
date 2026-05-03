---
page_id: 'concept:server'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: server
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - rr-02e8677b
project_ids: []
node_ids:
  - 'concept:server'
freshness: fresh
status: candidate
confidence: 0.65
created_at: '2026-05-03T05:11:46.179Z'
updated_at: '2026-05-03T05:32:23.486Z'
compiled_from:
  - rr-02e8677b
managed_by: system
backlinks:
  - 'source:rr-02e8677b'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  rr-02e8677b: 02e8677ba0504b886295dd3260a794f26e74d233f559b079cc1615f735163677
source_semantic_hashes:
  rr-02e8677b: 02e8677ba0504b886295dd3260a794f26e74d233f559b079cc1615f735163677
---
# server

## Summary

Frequently referenced concept in .rr.

## Seen In

- [[sources/rr-02e8677b|.rr]]

## Source Claims

- .rr Format: YAML Top-level: object Size: 4 Nested depth: 4 ## Schema - version: string - rpc: object (1 keys) - http: object (4 keys) - server: object (2 keys) ## Preview yaml version: '3' rpc: listen: 'tcp://127.0.0.1:6001' http: address: '0.0.0.0:8080' middleware: - gzip - static static: dir: public forbid: - .php - .htaccess pool: num_workers: 1 supervisor: max_worker_memory: 100 server: command: 'php app.php' relay: pipes [source:rr-02e8677b]

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

