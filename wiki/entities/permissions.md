---
page_id: 'entity:permissions'
kind: entity
cssclasses:
  - swarmvault
  - sv-entity
title: permissions
source_class: first_party
tags:
  - entity
  - ci-cd
  - continuous-integration
  - devops
  - workflow-automation
  - yaml
source_ids:
  - ci-fab63fbd
project_ids: []
node_ids:
  - 'entity:permissions'
freshness: fresh
status: active
confidence: 0.65
created_at: '2026-05-03T03:56:35.888Z'
updated_at: '2026-05-03T05:32:23.594Z'
compiled_from:
  - ci-fab63fbd
managed_by: system
backlinks:
  - 'source:ci-fab63fbd'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  ci-fab63fbd: fab63fbd6c494e889ed302d48cdcff49880b708788bef27b34f2ea8884393185
source_semantic_hashes:
  ci-fab63fbd: fab63fbd6c494e889ed302d48cdcff49880b708788bef27b34f2ea8884393185
---
# permissions

## Summary

Defines the scope of access the workflow runner has (e.g., contents, pull-requests). Requires at least two keys.

## Seen In

- [[sources/ci-fab63fbd|ci]]

## Source Claims

- The top-level schema must include keys for 'name' (string), 'on' (object), 'permissions' (object), 'env' (object), and 'jobs' (object). [source:ci-fab63fbd]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

