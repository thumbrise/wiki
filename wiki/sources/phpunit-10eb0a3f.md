---
page_id: 'source:phpunit-10eb0a3f'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: phpunit
source_class: first_party
tags:
  - source
source_ids:
  - phpunit-10eb0a3f
project_ids: []
node_ids:
  - 'source:phpunit-10eb0a3f'
  - 'concept:name'
  - 'concept:value'
  - 'concept:phpunit'
  - 'concept:directory'
  - 'concept:false'
  - 'concept:true'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T05:11:46.054Z'
updated_at: '2026-05-03T05:32:23.266Z'
compiled_from:
  - phpunit-10eb0a3f
managed_by: system
backlinks:
  - 'concept:name'
  - 'concept:value'
  - 'concept:phpunit'
  - 'concept:directory'
  - 'concept:false'
  - 'concept:true'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
source_semantic_hashes:
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
---
# phpunit

Source ID: `phpunit-10eb0a3f`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/op/poc/spiral-emit/phpunit.xml`

Source Class: `first_party`


## Source Details

- format: xml
- top level type: object
- top level size: 1
- nested depth: 3


## Summary

phpunit Format: XML Top-level: object Size: 1 Nested depth: 3 ## Schema - phpunit: object (4 keys) ## Preview xml <?xml version="1.0" encoding="UTF-8"?> <phpunit xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="vendor/phpunit/phpunit/phpunit.xsd" bootstrap="vendor/autoload.php" backupGlobals="false" colors="true" processIsolation="false" stopOnFailure="false" stopOnError="false" stderr="true" cacheDirectory="runtime/.phpunit.cache" backupStaticProperties="false" > <coverage/> <testsuites> <testsuite name="Unit"> <directory suffix="Test.php">tests/Unit</directory> </testsuite> <testsuite name="Feature"> <directory suffix="Test.php">tests/Feature</directory> </testsuite> </testsuites> <source> <include> <directory suffix=".php">app/src</directory> </include> </source> <php> <env name="DB_CONNECTION" value="sqlite" /> <env name="DB_LOG_QUERY_PARAMETERS" value="true" /> <env name="CYCLE_SCHEMA_CACHE" value="true" /> <env name="QUEUE_CONNECTION" value="sync" /> <env name="CACHE_STORAGE" value="local" /> <env name="APP_ENV" value="testing" /> <env name="TOKENIZER_CACHE_TARGETS" value="true" /> <env name="TELEMETRY_DRIVER" value="null" /> <env name="BROADCAST_DRIVER" value="log" /> <ini name="error_reporting" value="-1"/> <ini name="memory_limit" value="-1"/> </php> …

## Concepts

- [[concepts/name|name]]: Frequently referenced concept in phpunit.
- [[concepts/value|value]]: Frequently referenced concept in phpunit.
- [[concepts/phpunit|phpunit]]: Frequently referenced concept in phpunit.
- [[concepts/directory|directory]]: Frequently referenced concept in phpunit.
- [[concepts/false|false]]: Frequently referenced concept in phpunit.
- [[concepts/true|true]]: Frequently referenced concept in phpunit.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in phpunit.
- [[entities/top|Top-]]: Named entity mentioned in phpunit.
- [[entities/size|Size:]]: Named entity mentioned in phpunit.
- [[entities/nested|Nested]]: Named entity mentioned in phpunit.
- [[entities/schema|Schema -]]: Named entity mentioned in phpunit.
- [[entities/preview|Preview]]: Named entity mentioned in phpunit.

## Claims

- phpunit Format: XML Top-level: object Size: 1 Nested depth: 3 ## Schema - phpunit: object (4 keys) ## Preview xml <?xml version="1.0" encoding="UTF-8"?> <phpunit xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="vendor/phpunit/phpunit/phpunit.xsd" bootstrap="vendor/autoload.php" backupGlobals="false" colors="true" processIsolation="false" stopOnFailure="false" stopOnError="false" stderr="true" cacheDirectory="runtime/.phpunit.cache" backupStaticProperties="false" > <coverage/> <testsuites> <testsuite name="Unit"> <directory suffix="Test.php">tests/Unit</directory> </testsuite> <testsuite name="Feature"> <directory suffix="Test.php">tests/Feature</directory> </testsuite> </testsuites> <source> <include> <directory suffix=".php">app/src</directory> </include> </source> <php> <env name="DB_CONNECTION" value="sqlite" /> <env name="DB_LOG_QUERY_PARAMETERS" value="true" /> <env name="CYCLE_SCHEMA_CACHE" value="true" /> <env name="QUEUE_CONNECTION" value="sync" /> <env name="CACHE_STORAGE" value="local" /> <env name="APP_ENV" value="testing" /> <env name="TOKENIZER_CACHE_TARGETS" value="true" /> <env name="TELEMETRY_DRIVER" value="null" /> <env name="BROADCAST_DRIVER" value="log" /> <ini name="error_reporting" value="-1"/> <ini name="memory_limit" value="-1"/> </php> … [source:phpunit-10eb0a3f]

## Questions

- How does name relate to phpunit?
- How does value relate to phpunit?
- How does phpunit relate to phpunit?

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

