---
page_id: 'concept:tokenizer'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: tokenizer
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - env-d5128e48
  - environment-prod-or-local-a93beb0c
project_ids: []
node_ids:
  - 'concept:tokenizer'
freshness: fresh
status: candidate
confidence: 0.8
created_at: '2026-05-03T05:11:46.144Z'
updated_at: '2026-05-03T05:32:23.418Z'
compiled_from:
  - env-d5128e48
  - environment-prod-or-local-a93beb0c
managed_by: system
backlinks:
  - 'source:env-d5128e48'
  - 'source:environment-prod-or-local-a93beb0c'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  env-d5128e48: d5128e48558ed77f288c985e7a6a2e32828ceb4c23e5840981bce76018597f05
  environment-prod-or-local-a93beb0c: a93beb0cbb31ac8ce316e5326fcd21a6b6b52911cea462777294ef0c6c8c7ffd
source_semantic_hashes:
  env-d5128e48: d5128e48558ed77f288c985e7a6a2e32828ceb4c23e5840981bce76018597f05
  environment-prod-or-local-a93beb0c: a93beb0cbb31ac8ce316e5326fcd21a6b6b52911cea462777294ef0c6c8c7ffd
---
# tokenizer

## Summary

Frequently referenced concept in .env.

## Seen In

- [[sources/env-d5128e48|.env]]
- [[sources/environment-prod-or-local-a93beb0c|Environment (prod or local)]]

## Source Claims

- .env Format: ENV Top-level: object Size: 29 Nested depth: 1 ## Schema - APP_ENV: string - DEBUG: string - VERBOSITY_LEVEL: string - ENCRYPTER_KEY: string - MONOLOG_DEFAULT_CHANNEL: string - MONOLOG_DEFAULT_LEVEL: string - TELEMETRY_DRIVER: string - TOKENIZER_CACHE_TARGETS: string - TOKENIZER_LOAD_CLASSES: string - TOKENIZER_LOAD_ENUMS: string - TOKENIZER_LOAD_INTERFACES: string - VIEW_CACHE: string - SESSION_LIFETIME: string - SESSION_COOKIE: string - AUTH_TOKEN_TRANSPORT: string - AUTH_TOKEN_STORAGE: string - SAFE_MIGRATIONS: string - DB_CONNECTION: string - DB_LOG_QUERY_PARAMETERS: string - DB_LOG_INTERPOLATED_QUERIES: string ## Preview env # Environment (prod or local) APP_ENV=local # Debug mode set to TRUE disables view caching and enables higher verbosity DEBUG=true # Verbosity level VERBOSITY_LEVEL=verbose # basic, verbose, debug # Set to an application specific value, used to encrypt/decrypt cookies etc ENCRYPTER_KEY=def0000075753c94a66661fc6cb0f28448bf399ee667f921f8603c2f273e1bd8682f8de38f85ed992966d4bd3d0c5bf3a84770f19e49bca04662dbd0cef9f11a6974c6c6 # Monolog MONOLOG_DEFAULT_CHANNEL=default # Use "roadrunner" channel if you want to use RoadRunner logger MONOLOG_DEFAULT_LEVEL=DEBUG # DEBUG, INFO, NOTICE, WARNING, ERROR, CRITICAL, ALERT, EMERGENCY # Telemetry TELEMETRY_DRIVER=null # Tokenizer TOKENIZER_CACHE_TARGETS=false TOKENIZER_LOAD_CLASSES=true TOKENIZER_LOAD_ENUMS=true TOKENIZER_LOAD_INTERFACES=true # View component options VIEW_CACHE=false # Session SESSION_LIFETIME=86400 SESSION_COOKIE=sid # Authorization AUTH_TOKEN_TRANSPORT=cookie AUTH_TOKEN_STORAGE=session # Set to TRUE to disable confirmation in `migrate` commands SAFE_MIGRATIONS=true # Database connection options … [source:env-d5128e48]
- Environment (prod or local) APP_ENV=local # Debug mode set to TRUE disables view caching and enables higher verbosity DEBUG=true # Verbosity level VERBOSITY_LEVEL=verbose # basic, verbose, debug # Set to an application specific value, used to encrypt/decrypt cookies etc ENCRYPTER_KEY={encrypt-key} # Monolog MONOLOG_DEFAULT_CHANNEL=default # Use "roadrunner" channel if you want to use RoadRunner logger MONOLOG_DEFAULT_LEVEL=DEBUG # DEBUG, INFO, NOTICE, WARNING, ERROR, CRITICAL, ALERT, EMERGENCY # Telemetry TELEMETRY_DRIVER=null # Tokenizer TOKENIZER_CACHE_TARGETS=false TOKENIZER_LOAD_CLASSES=true TOKENIZER_LOAD_ENUMS=true TOKENIZER_LOAD_INTERFACES=true # View component options VIEW_CACHE=false # Session SESSION_LIFETIME=86400 SESSION_COOKIE=sid # Authorization AUTH_TOKEN_TRANSPORT=cookie AUTH_TOKEN_STORAGE=session # Set to TRUE to disable confirmation in migrate commands SAFE_MIGRATIONS=true # Database connection options DB_CONNECTION=sqlite DB_LOG_QUERY_PARAMETERS=false DB_LOG_INTERPOLATED_QUERIES=false DB_WITH_DATETIME_MICROSECONDS=false DB_DATABASE=spiral DB_HOST=127.0.0.1 DB_PORT=3307 DB_USERNAME=root DB_PASSWORD=password # Cycle Bridge (Don't forget to set CYCLE_SCHEMA_CACHE to true in production) CYCLE_SCHEMA_CACHE=false CYCLE_SCHEMA_WARMUP=false # Internationalization LOCALE=en [source:environment-prod-or-local-a93beb0c]

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

