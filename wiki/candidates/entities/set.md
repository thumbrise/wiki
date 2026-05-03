---
page_id: 'entity:set'
kind: entity
cssclasses:
  - swarmvault
  - sv-entity
title: Set
source_class: first_party
tags:
  - entity
  - candidate
source_ids:
  - environment-prod-or-local-a93beb0c
project_ids: []
node_ids:
  - 'entity:set'
freshness: fresh
status: candidate
confidence: 0.65
created_at: '2026-05-03T05:11:46.293Z'
updated_at: '2026-05-03T05:32:23.598Z'
compiled_from:
  - environment-prod-or-local-a93beb0c
managed_by: system
backlinks:
  - 'source:environment-prod-or-local-a93beb0c'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  environment-prod-or-local-a93beb0c: a93beb0cbb31ac8ce316e5326fcd21a6b6b52911cea462777294ef0c6c8c7ffd
source_semantic_hashes:
  environment-prod-or-local-a93beb0c: a93beb0cbb31ac8ce316e5326fcd21a6b6b52911cea462777294ef0c6c8c7ffd
---
# Set

## Summary

Named entity mentioned in Environment (prod or local).

## Seen In

- [[sources/environment-prod-or-local-a93beb0c|Environment (prod or local)]]

## Source Claims

- Environment (prod or local) APP_ENV=local # Debug mode set to TRUE disables view caching and enables higher verbosity DEBUG=true # Verbosity level VERBOSITY_LEVEL=verbose # basic, verbose, debug # Set to an application specific value, used to encrypt/decrypt cookies etc ENCRYPTER_KEY={encrypt-key} # Monolog MONOLOG_DEFAULT_CHANNEL=default # Use "roadrunner" channel if you want to use RoadRunner logger MONOLOG_DEFAULT_LEVEL=DEBUG # DEBUG, INFO, NOTICE, WARNING, ERROR, CRITICAL, ALERT, EMERGENCY # Telemetry TELEMETRY_DRIVER=null # Tokenizer TOKENIZER_CACHE_TARGETS=false TOKENIZER_LOAD_CLASSES=true TOKENIZER_LOAD_ENUMS=true TOKENIZER_LOAD_INTERFACES=true # View component options VIEW_CACHE=false # Session SESSION_LIFETIME=86400 SESSION_COOKIE=sid # Authorization AUTH_TOKEN_TRANSPORT=cookie AUTH_TOKEN_STORAGE=session # Set to TRUE to disable confirmation in migrate commands SAFE_MIGRATIONS=true # Database connection options DB_CONNECTION=sqlite DB_LOG_QUERY_PARAMETERS=false DB_LOG_INTERPOLATED_QUERIES=false DB_WITH_DATETIME_MICROSECONDS=false DB_DATABASE=spiral DB_HOST=127.0.0.1 DB_PORT=3307 DB_USERNAME=root DB_PASSWORD=password # Cycle Bridge (Don't forget to set CYCLE_SCHEMA_CACHE to true in production) CYCLE_SCHEMA_CACHE=false CYCLE_SCHEMA_WARMUP=false # Internationalization LOCALE=en [source:environment-prod-or-local-a93beb0c]

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

