---
page_id: 'concept:cache'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: cache
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - 18-guards-569885ee
  - environment-prod-or-local-a93beb0c
  - gitignore-0262f82c
  - gitignore-b836fd5b
project_ids: []
node_ids:
  - 'concept:cache'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.856Z'
updated_at: '2026-05-03T05:32:23.351Z'
compiled_from:
  - 18-guards-569885ee
  - environment-prod-or-local-a93beb0c
  - gitignore-0262f82c
  - gitignore-b836fd5b
managed_by: system
backlinks:
  - 'source:18-guards-569885ee'
  - 'source:environment-prod-or-local-a93beb0c'
  - 'source:gitignore-0262f82c'
  - 'source:gitignore-b836fd5b'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  18-guards-569885ee: 569885ee79e5a22b2f1728422809d76055d8c259b108c4947b776a2a496aca64
  environment-prod-or-local-a93beb0c: a93beb0cbb31ac8ce316e5326fcd21a6b6b52911cea462777294ef0c6c8c7ffd
  gitignore-0262f82c: 0262f82c1bf94d9f9e3c5e32ca63a3829b9a50d698895364768165756c308bef
  gitignore-b836fd5b: b836fd5ba7bf40e4d13eef30d437f7dfae9e92d8ad4ffe6a1156779842ccf1d5
source_semantic_hashes:
  18-guards-569885ee: 77eeec8a373f02e820a5f79b6da4f62ca8470e7c7de1d2ae97368ecda0b65a9a
  environment-prod-or-local-a93beb0c: a93beb0cbb31ac8ce316e5326fcd21a6b6b52911cea462777294ef0c6c8c7ffd
  gitignore-0262f82c: 0262f82c1bf94d9f9e3c5e32ca63a3829b9a50d698895364768165756c308bef
  gitignore-b836fd5b: b836fd5ba7bf40e4d13eef30d437f7dfae9e92d8ad4ffe6a1156779842ccf1d5
---
# cache

## Summary

Frequently referenced concept in #18 — Guards.

## Seen In

- [[sources/18-guards-569885ee|#18 — Guards]]
- [[sources/environment-prod-or-local-a93beb0c|Environment (prod or local)]]
- [[sources/gitignore-0262f82c|.gitignore]]
- [[sources/gitignore-b836fd5b|.gitignore]]

## Source Claims

- title: #18 — Guards description: Hedge requests, cache stampede protection, circuit breakers, retry policies, backpressure, fallbacks. [source:18-guards-569885ee]
- Environment (prod or local) APP_ENV=local # Debug mode set to TRUE disables view caching and enables higher verbosity DEBUG=true # Verbosity level VERBOSITY_LEVEL=verbose # basic, verbose, debug # Set to an application specific value, used to encrypt/decrypt cookies etc ENCRYPTER_KEY={encrypt-key} # Monolog MONOLOG_DEFAULT_CHANNEL=default # Use "roadrunner" channel if you want to use RoadRunner logger MONOLOG_DEFAULT_LEVEL=DEBUG # DEBUG, INFO, NOTICE, WARNING, ERROR, CRITICAL, ALERT, EMERGENCY # Telemetry TELEMETRY_DRIVER=null # Tokenizer TOKENIZER_CACHE_TARGETS=false TOKENIZER_LOAD_CLASSES=true TOKENIZER_LOAD_ENUMS=true TOKENIZER_LOAD_INTERFACES=true # View component options VIEW_CACHE=false # Session SESSION_LIFETIME=86400 SESSION_COOKIE=sid # Authorization AUTH_TOKEN_TRANSPORT=cookie AUTH_TOKEN_STORAGE=session # Set to TRUE to disable confirmation in migrate commands SAFE_MIGRATIONS=true # Database connection options DB_CONNECTION=sqlite DB_LOG_QUERY_PARAMETERS=false DB_LOG_INTERPOLATED_QUERIES=false DB_WITH_DATETIME_MICROSECONDS=false DB_DATABASE=spiral DB_HOST=127.0.0.1 DB_PORT=3307 DB_USERNAME=root DB_PASSWORD=password # Cycle Bridge (Don't forget to set CYCLE_SCHEMA_CACHE to true in production) CYCLE_SCHEMA_CACHE=false CYCLE_SCHEMA_WARMUP=false # Internationalization LOCALE=en [source:environment-prod-or-local-a93beb0c]
- .vitepress/dist .vitepress/cache node_modules [source:gitignore-0262f82c]
- / !/.docker !/.github /vendor /runtime/ /runtime/ /rr /protoc-gen-php-grpc /.env /*.cache [source:gitignore-b836fd5b]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

