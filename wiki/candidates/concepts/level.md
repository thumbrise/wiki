---
page_id: 'concept:level'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: level
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - env-d5128e48
  - local-2004a734
project_ids: []
node_ids:
  - 'concept:level'
freshness: fresh
status: candidate
confidence: 0.8
created_at: '2026-05-03T05:11:46.144Z'
updated_at: '2026-05-03T05:32:23.419Z'
compiled_from:
  - env-d5128e48
  - local-2004a734
managed_by: system
backlinks:
  - 'source:env-d5128e48'
  - 'source:local-2004a734'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  env-d5128e48: d5128e48558ed77f288c985e7a6a2e32828ceb4c23e5840981bce76018597f05
  local-2004a734: 2004a734001f1d94282bdbe05962f099909ed613ad330f53b9c049f44c6a15df
source_semantic_hashes:
  env-d5128e48: d5128e48558ed77f288c985e7a6a2e32828ceb4c23e5840981bce76018597f05
  local-2004a734: 2004a734001f1d94282bdbe05962f099909ed613ad330f53b9c049f44c6a15df
---
# level

## Summary

Frequently referenced concept in .env.

## Seen In

- [[sources/env-d5128e48|.env]]
- [[sources/local-2004a734|local]]

## Source Claims

- .env Format: ENV Top-level: object Size: 29 Nested depth: 1 ## Schema - APP_ENV: string - DEBUG: string - VERBOSITY_LEVEL: string - ENCRYPTER_KEY: string - MONOLOG_DEFAULT_CHANNEL: string - MONOLOG_DEFAULT_LEVEL: string - TELEMETRY_DRIVER: string - TOKENIZER_CACHE_TARGETS: string - TOKENIZER_LOAD_CLASSES: string - TOKENIZER_LOAD_ENUMS: string - TOKENIZER_LOAD_INTERFACES: string - VIEW_CACHE: string - SESSION_LIFETIME: string - SESSION_COOKIE: string - AUTH_TOKEN_TRANSPORT: string - AUTH_TOKEN_STORAGE: string - SAFE_MIGRATIONS: string - DB_CONNECTION: string - DB_LOG_QUERY_PARAMETERS: string - DB_LOG_INTERPOLATED_QUERIES: string ## Preview env # Environment (prod or local) APP_ENV=local # Debug mode set to TRUE disables view caching and enables higher verbosity DEBUG=true # Verbosity level VERBOSITY_LEVEL=verbose # basic, verbose, debug # Set to an application specific value, used to encrypt/decrypt cookies etc ENCRYPTER_KEY=def0000075753c94a66661fc6cb0f28448bf399ee667f921f8603c2f273e1bd8682f8de38f85ed992966d4bd3d0c5bf3a84770f19e49bca04662dbd0cef9f11a6974c6c6 # Monolog MONOLOG_DEFAULT_CHANNEL=default # Use "roadrunner" channel if you want to use RoadRunner logger MONOLOG_DEFAULT_LEVEL=DEBUG # DEBUG, INFO, NOTICE, WARNING, ERROR, CRITICAL, ALERT, EMERGENCY # Telemetry TELEMETRY_DRIVER=null # Tokenizer TOKENIZER_CACHE_TARGETS=false TOKENIZER_LOAD_CLASSES=true TOKENIZER_LOAD_ENUMS=true TOKENIZER_LOAD_INTERFACES=true # View component options VIEW_CACHE=false # Session SESSION_LIFETIME=86400 SESSION_COOKIE=sid # Authorization AUTH_TOKEN_TRANSPORT=cookie AUTH_TOKEN_STORAGE=session # Set to TRUE to disable confirmation in `migrate` commands SAFE_MIGRATIONS=true # Database connection options … [source:env-d5128e48]
- local Format: INI Top-level: object Size: 8 Nested depth: 1 ## Schema - xdebug.mode: string - xdebug.client_host: string - xdebug.client_port: string - xdebug.start_with_request: string - xdebug.discover_client_host: string - xdebug.log_level: string - xdebug.log: string - xdebug.idekey: string ## Preview ini xdebug.mode=debug xdebug.client_host=host.docker.internal xdebug.client_port=9003 xdebug.start_with_request=trigger xdebug.discover_client_host=1 xdebug.log_level=0 xdebug.log="/var/www/runtime/xdebug.log" xdebug.idekey=PHPSTORM [source:local-2004a734]

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

