---
page_id: 'concept:value'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: value
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - 18-the-fourth-rail-368f05dd
  - 18-the-fourth-rail-f496db69
  - phpunit-10eb0a3f
project_ids: []
node_ids:
  - 'concept:value'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.846Z'
updated_at: '2026-05-03T05:32:23.352Z'
compiled_from:
  - 18-the-fourth-rail-368f05dd
  - 18-the-fourth-rail-f496db69
  - phpunit-10eb0a3f
managed_by: system
backlinks:
  - 'source:18-the-fourth-rail-368f05dd'
  - 'source:18-the-fourth-rail-f496db69'
  - 'source:phpunit-10eb0a3f'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  18-the-fourth-rail-368f05dd: 368f05dd7499564b9adb53c6bb53de2359521ef1c3616dda5fe9b29a3c0efaf5
  18-the-fourth-rail-f496db69: f496db6928de75bf0c47baad6b39a774ee6263ec366a82c73713783bfa4dbf3c
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
source_semantic_hashes:
  18-the-fourth-rail-368f05dd: 7c51960bc6eb020ccc382192a3b352437432f9f8ec280923f277210d22e48f94
  18-the-fourth-rail-f496db69: 9ed26794d6a1d8b75e0f1b394d68bcd83df036b4555f4c12d6cf366ad9ff8521
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
---
# value

## Summary

Frequently referenced concept in #18 — The Fourth Rail.

## Seen In

- [[sources/18-the-fourth-rail-368f05dd|#18 — The Fourth Rail]]
- [[sources/18-the-fourth-rail-f496db69|#18 — The Fourth Rail]]
- [[sources/phpunit-10eb0a3f|phpunit]]

## Source Claims

- phpunit Format: XML Top-level: object Size: 1 Nested depth: 3 ## Schema - phpunit: object (4 keys) ## Preview xml <?xml version="1.0" encoding="UTF-8"?> <phpunit xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="vendor/phpunit/phpunit/phpunit.xsd" bootstrap="vendor/autoload.php" backupGlobals="false" colors="true" processIsolation="false" stopOnFailure="false" stopOnError="false" stderr="true" cacheDirectory="runtime/.phpunit.cache" backupStaticProperties="false" > <coverage/> <testsuites> <testsuite name="Unit"> <directory suffix="Test.php">tests/Unit</directory> </testsuite> <testsuite name="Feature"> <directory suffix="Test.php">tests/Feature</directory> </testsuite> </testsuites> <source> <include> <directory suffix=".php">app/src</directory> </include> </source> <php> <env name="DB_CONNECTION" value="sqlite" /> <env name="DB_LOG_QUERY_PARAMETERS" value="true" /> <env name="CYCLE_SCHEMA_CACHE" value="true" /> <env name="QUEUE_CONNECTION" value="sync" /> <env name="CACHE_STORAGE" value="local" /> <env name="APP_ENV" value="testing" /> <env name="TOKENIZER_CACHE_TARGETS" value="true" /> <env name="TELEMETRY_DRIVER" value="null" /> <env name="BROADCAST_DRIVER" value="log" /> <ini name="error_reporting" value="-1"/> <ini name="memory_limit" value="-1"/> </php> … [source:phpunit-10eb0a3f]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

