---
page_id: 'concept:phpunit'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: phpunit
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - phpunit-10eb0a3f
project_ids: []
node_ids:
  - 'concept:phpunit'
freshness: fresh
status: candidate
confidence: 0.65
created_at: '2026-05-03T05:11:46.176Z'
updated_at: '2026-05-03T05:32:23.480Z'
compiled_from:
  - phpunit-10eb0a3f
managed_by: system
backlinks:
  - 'source:phpunit-10eb0a3f'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
source_semantic_hashes:
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
---
# phpunit

## Summary

Frequently referenced concept in phpunit.

## Seen In

- [[sources/phpunit-10eb0a3f|phpunit]]

## Source Claims

- phpunit Format: XML Top-level: object Size: 1 Nested depth: 3 ## Schema - phpunit: object (4 keys) ## Preview xml <?xml version="1.0" encoding="UTF-8"?> <phpunit xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="vendor/phpunit/phpunit/phpunit.xsd" bootstrap="vendor/autoload.php" backupGlobals="false" colors="true" processIsolation="false" stopOnFailure="false" stopOnError="false" stderr="true" cacheDirectory="runtime/.phpunit.cache" backupStaticProperties="false" > <coverage/> <testsuites> <testsuite name="Unit"> <directory suffix="Test.php">tests/Unit</directory> </testsuite> <testsuite name="Feature"> <directory suffix="Test.php">tests/Feature</directory> </testsuite> </testsuites> <source> <include> <directory suffix=".php">app/src</directory> </include> </source> <php> <env name="DB_CONNECTION" value="sqlite" /> <env name="DB_LOG_QUERY_PARAMETERS" value="true" /> <env name="CYCLE_SCHEMA_CACHE" value="true" /> <env name="QUEUE_CONNECTION" value="sync" /> <env name="CACHE_STORAGE" value="local" /> <env name="APP_ENV" value="testing" /> <env name="TOKENIZER_CACHE_TARGETS" value="true" /> <env name="TELEMETRY_DRIVER" value="null" /> <env name="BROADCAST_DRIVER" value="log" /> <ini name="error_reporting" value="-1"/> <ini name="memory_limit" value="-1"/> </php> … [source:phpunit-10eb0a3f]

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

