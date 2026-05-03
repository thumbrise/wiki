---
page_id: 'concept:directory'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: directory
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - dependabot-b88a7add
  - my-awesome-web-application-2e8617e5
  - phpunit-10eb0a3f
  - psalm-06d502d6
  - universal-first-vendors-not-a-standard-library-637ac699
  - universal-first-vendors-not-a-standard-library-f05eb450
project_ids: []
node_ids:
  - 'concept:directory'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.855Z'
updated_at: '2026-05-03T05:32:23.405Z'
compiled_from:
  - dependabot-b88a7add
  - my-awesome-web-application-2e8617e5
  - phpunit-10eb0a3f
  - psalm-06d502d6
  - universal-first-vendors-not-a-standard-library-637ac699
  - universal-first-vendors-not-a-standard-library-f05eb450
managed_by: system
backlinks:
  - 'source:dependabot-b88a7add'
  - 'source:my-awesome-web-application-2e8617e5'
  - 'source:phpunit-10eb0a3f'
  - 'source:psalm-06d502d6'
  - 'source:universal-first-vendors-not-a-standard-library-637ac699'
  - 'source:universal-first-vendors-not-a-standard-library-f05eb450'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dependabot-b88a7add: b88a7add900c2c89bf2506513ce1d00bea830b94f8cd0b3fe437700aa2e99307
  my-awesome-web-application-2e8617e5: 2e8617e52b1971e42586bb6259caa31ee85fe9d8957ba281d2b4656644cc1e2c
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
  psalm-06d502d6: 06d502d6ebda56bb50ee770bb94849e5dfcb849bd5fbd0b2a38eae9d5c25adcc
  universal-first-vendors-not-a-standard-library-637ac699: 637ac6996076125accfa674beeb9655b979a847b3945450ad721cd6d8f92df85
  universal-first-vendors-not-a-standard-library-f05eb450: f05eb4503f94918cd12b87765d9caf10ca0ff06934d06eee9d31df21838b3b91
source_semantic_hashes:
  dependabot-b88a7add: b88a7add900c2c89bf2506513ce1d00bea830b94f8cd0b3fe437700aa2e99307
  my-awesome-web-application-2e8617e5: f97c3d4dc3498343712f048001ea6f787abf50eecb352a7542f2644b110d2019
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
  psalm-06d502d6: 06d502d6ebda56bb50ee770bb94849e5dfcb849bd5fbd0b2a38eae9d5c25adcc
  universal-first-vendors-not-a-standard-library-637ac699: 3efef5f522a8a3f8a3ddd88ddbdf6b248d9db09ecd450117edc5e74267035a1e
  universal-first-vendors-not-a-standard-library-f05eb450: d10fca270d6ad6f4fc42b735825bd0fdd6581735e10c9aba1fdb41597b67e14f
---
# directory

## Summary

Frequently referenced concept in dependabot.

## Seen In

- [[sources/dependabot-b88a7add|dependabot]]
- [[sources/my-awesome-web-application-2e8617e5|My awesome Web application]]
- [[sources/phpunit-10eb0a3f|phpunit]]
- [[sources/psalm-06d502d6|psalm]]
- [[sources/universal-first-vendors-not-a-standard-library-637ac699|universal/ — first vendors, not a standard library]]
- [[sources/universal-first-vendors-not-a-standard-library-f05eb450|universal/ — first vendors, not a standard library]]

## Source Claims

- dependabot Format: YAML Top-level: object Size: 2 Nested depth: 6 ## Schema - version: number - updates: array (3 items) ## Preview yaml version: 2 updates: - package-ecosystem: github-actions directory: / schedule: interval: daily groups: actions: patterns: - "*" - package-ecosystem: gomod directory: / schedule: interval: daily groups: all-go-deps: patterns: - "*" - package-ecosystem: gomod directory: /_tools schedule: interval: daily groups: tools-deps: patterns: - "*" [source:dependabot-b88a7add]
- phpunit Format: XML Top-level: object Size: 1 Nested depth: 3 ## Schema - phpunit: object (4 keys) ## Preview xml <?xml version="1.0" encoding="UTF-8"?> <phpunit xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="vendor/phpunit/phpunit/phpunit.xsd" bootstrap="vendor/autoload.php" backupGlobals="false" colors="true" processIsolation="false" stopOnFailure="false" stopOnError="false" stderr="true" cacheDirectory="runtime/.phpunit.cache" backupStaticProperties="false" > <coverage/> <testsuites> <testsuite name="Unit"> <directory suffix="Test.php">tests/Unit</directory> </testsuite> <testsuite name="Feature"> <directory suffix="Test.php">tests/Feature</directory> </testsuite> </testsuites> <source> <include> <directory suffix=".php">app/src</directory> </include> </source> <php> <env name="DB_CONNECTION" value="sqlite" /> <env name="DB_LOG_QUERY_PARAMETERS" value="true" /> <env name="CYCLE_SCHEMA_CACHE" value="true" /> <env name="QUEUE_CONNECTION" value="sync" /> <env name="CACHE_STORAGE" value="local" /> <env name="APP_ENV" value="testing" /> <env name="TOKENIZER_CACHE_TARGETS" value="true" /> <env name="TELEMETRY_DRIVER" value="null" /> <env name="BROADCAST_DRIVER" value="log" /> <ini name="error_reporting" value="-1"/> <ini name="memory_limit" value="-1"/> </php> … [source:phpunit-10eb0a3f]
- psalm Format: XML Top-level: object Size: 1 Nested depth: 3 ## Schema - psalm: object (1 keys) ## Preview xml <?xml version="1.0"?> <psalm errorLevel="2" resolveFromConfigFile="true" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="https://getpsalm.org/schema/config" xsi:schemaLocation="https://getpsalm.org/schema/config vendor/vimeo/psalm/config.xsd" hoistConstants="true" findUnusedPsalmSuppress="false" findUnusedVariablesAndParams="true" findUnusedBaselineEntry="true" findUnusedCode="false" ensureArrayStringOffsetsExist="true" addParamDefaultToDocblockType="true" strictBinaryOperands="true" errorBaseline="psalm-baseline.xml" > <projectFiles> <directory name="app/src"/> <ignoreFiles> <directory name="vendor"/> </ignoreFiles> </projectFiles> </psalm> [source:psalm-06d502d6]
- universal/ — first vendors, not a standard library This directory holds the vendors we are bootstrapping for Op. [source:universal-first-vendors-not-a-standard-library-637ac699]
- universal/ — first vendors, not a standard library This directory holds the vendors we are bootstrapping for Op. [source:universal-first-vendors-not-a-standard-library-f05eb450]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

