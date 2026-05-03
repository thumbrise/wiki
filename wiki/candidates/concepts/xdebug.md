---
page_id: 'concept:xdebug'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: xdebug
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - local-2004a734
  - local-ini-4b243f68
project_ids: []
node_ids:
  - 'concept:xdebug'
freshness: fresh
status: candidate
confidence: 0.8
created_at: '2026-05-03T05:11:46.172Z'
updated_at: '2026-05-03T05:32:23.459Z'
compiled_from:
  - local-2004a734
  - local-ini-4b243f68
managed_by: system
backlinks:
  - 'source:local-2004a734'
  - 'source:local-ini-4b243f68'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  local-2004a734: 2004a734001f1d94282bdbe05962f099909ed613ad330f53b9c049f44c6a15df
  local-ini-4b243f68: 4b243f682b6769f98cd5e2277f7f0de4e1a6d87bc349c3d8f9b329d5945d6e7a
source_semantic_hashes:
  local-2004a734: 2004a734001f1d94282bdbe05962f099909ed613ad330f53b9c049f44c6a15df
  local-ini-4b243f68: 4b243f682b6769f98cd5e2277f7f0de4e1a6d87bc349c3d8f9b329d5945d6e7a
---
# xdebug

## Summary

Frequently referenced concept in local.

## Seen In

- [[sources/local-2004a734|local]]
- [[sources/local-ini-4b243f68|local.ini]]

## Source Claims

- local Format: INI Top-level: object Size: 8 Nested depth: 1 ## Schema - xdebug.mode: string - xdebug.client_host: string - xdebug.client_port: string - xdebug.start_with_request: string - xdebug.discover_client_host: string - xdebug.log_level: string - xdebug.log: string - xdebug.idekey: string ## Preview ini xdebug.mode=debug xdebug.client_host=host.docker.internal xdebug.client_port=9003 xdebug.start_with_request=trigger xdebug.discover_client_host=1 xdebug.log_level=0 xdebug.log="/var/www/runtime/xdebug.log" xdebug.idekey=PHPSTORM [source:local-2004a734]
- xdebug.mode=debug xdebug.client_host=host.docker.internal xdebug.client_port=9003 xdebug.start_with_request=trigger xdebug.discover_client_host=1 xdebug.log_level=0 xdebug.log="/var/www/html/xdebug.log" xdebug.idekey=PHPSTORM [source:local-ini-4b243f68]

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

