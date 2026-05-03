---
page_id: 'concept:false'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: 'false'
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - environment-prod-or-local-a93beb0c
  - phpunit-10eb0a3f
  - psalm-06d502d6
project_ids: []
node_ids:
  - 'concept:false'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T05:11:46.144Z'
updated_at: '2026-05-03T05:32:23.419Z'
compiled_from:
  - environment-prod-or-local-a93beb0c
  - phpunit-10eb0a3f
  - psalm-06d502d6
managed_by: system
backlinks:
  - 'source:environment-prod-or-local-a93beb0c'
  - 'source:phpunit-10eb0a3f'
  - 'source:psalm-06d502d6'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  environment-prod-or-local-a93beb0c: a93beb0cbb31ac8ce316e5326fcd21a6b6b52911cea462777294ef0c6c8c7ffd
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
  psalm-06d502d6: 06d502d6ebda56bb50ee770bb94849e5dfcb849bd5fbd0b2a38eae9d5c25adcc
source_semantic_hashes:
  environment-prod-or-local-a93beb0c: a93beb0cbb31ac8ce316e5326fcd21a6b6b52911cea462777294ef0c6c8c7ffd
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
  psalm-06d502d6: 06d502d6ebda56bb50ee770bb94849e5dfcb849bd5fbd0b2a38eae9d5c25adcc
---
# false

## Summary

Frequently referenced concept in Environment (prod or local).

## Seen In

- [[sources/environment-prod-or-local-a93beb0c|Environment (prod or local)]]
- [[sources/phpunit-10eb0a3f|phpunit]]
- [[sources/psalm-06d502d6|psalm]]

## Source Claims

- Environment (prod or local) APP_ENV=local # Debug mode set to TRUE disables view caching and enables higher verbosity DEBUG=true # Verbosity level VERBOSITY_LEVEL=verbose # basic, verbose, debug # Set to an application specific value, used to encrypt/decrypt cookies etc ENCRYPTER_KEY={encrypt-key} # Monolog MONOLOG_DEFAULT_CHANNEL=default # Use "roadrunner" channel if you want to use RoadRunner logger MONOLOG_DEFAULT_LEVEL=DEBUG # DEBUG, INFO, NOTICE, WARNING, ERROR, CRITICAL, ALERT, EMERGENCY # Telemetry TELEMETRY_DRIVER=null # Tokenizer TOKENIZER_CACHE_TARGETS=false TOKENIZER_LOAD_CLASSES=true TOKENIZER_LOAD_ENUMS=true TOKENIZER_LOAD_INTERFACES=true # View component options VIEW_CACHE=false # Session SESSION_LIFETIME=86400 SESSION_COOKIE=sid # Authorization AUTH_TOKEN_TRANSPORT=cookie AUTH_TOKEN_STORAGE=session # Set to TRUE to disable confirmation in migrate commands SAFE_MIGRATIONS=true # Database connection options DB_CONNECTION=sqlite DB_LOG_QUERY_PARAMETERS=false DB_LOG_INTERPOLATED_QUERIES=false DB_WITH_DATETIME_MICROSECONDS=false DB_DATABASE=spiral DB_HOST=127.0.0.1 DB_PORT=3307 DB_USERNAME=root DB_PASSWORD=password # Cycle Bridge (Don't forget to set CYCLE_SCHEMA_CACHE to true in production) CYCLE_SCHEMA_CACHE=false CYCLE_SCHEMA_WARMUP=false # Internationalization LOCALE=en [source:environment-prod-or-local-a93beb0c]
- phpunit Format: XML Top-level: object Size: 1 Nested depth: 3 ## Schema - phpunit: object (4 keys) ## Preview xml <?xml version="1.0" encoding="UTF-8"?> <phpunit xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="vendor/phpunit/phpunit/phpunit.xsd" bootstrap="vendor/autoload.php" backupGlobals="false" colors="true" processIsolation="false" stopOnFailure="false" stopOnError="false" stderr="true" cacheDirectory="runtime/.phpunit.cache" backupStaticProperties="false" > <coverage/> <testsuites> <testsuite name="Unit"> <directory suffix="Test.php">tests/Unit</directory> </testsuite> <testsuite name="Feature"> <directory suffix="Test.php">tests/Feature</directory> </testsuite> </testsuites> <source> <include> <directory suffix=".php">app/src</directory> </include> </source> <php> <env name="DB_CONNECTION" value="sqlite" /> <env name="DB_LOG_QUERY_PARAMETERS" value="true" /> <env name="CYCLE_SCHEMA_CACHE" value="true" /> <env name="QUEUE_CONNECTION" value="sync" /> <env name="CACHE_STORAGE" value="local" /> <env name="APP_ENV" value="testing" /> <env name="TOKENIZER_CACHE_TARGETS" value="true" /> <env name="TELEMETRY_DRIVER" value="null" /> <env name="BROADCAST_DRIVER" value="log" /> <ini name="error_reporting" value="-1"/> <ini name="memory_limit" value="-1"/> </php> … [source:phpunit-10eb0a3f]
- psalm Format: XML Top-level: object Size: 1 Nested depth: 3 ## Schema - psalm: object (1 keys) ## Preview xml <?xml version="1.0"?> <psalm errorLevel="2" resolveFromConfigFile="true" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="https://getpsalm.org/schema/config" xsi:schemaLocation="https://getpsalm.org/schema/config vendor/vimeo/psalm/config.xsd" hoistConstants="true" findUnusedPsalmSuppress="false" findUnusedVariablesAndParams="true" findUnusedBaselineEntry="true" findUnusedCode="false" ensureArrayStringOffsetsExist="true" addParamDefaultToDocblockType="true" strictBinaryOperands="true" errorBaseline="psalm-baseline.xml" > <projectFiles> <directory name="app/src"/> <ignoreFiles> <directory name="vendor"/> </ignoreFiles> </projectFiles> </psalm> [source:psalm-06d502d6]

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

