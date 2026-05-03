---
page_id: 'concept:name'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: name
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - dependabot-auto-merge-a7978ddf
  - docs-16563f41
  - dogshop-de2fc247
  - nota-v1-6168c974
  - phpunit-10eb0a3f
  - release-33611003
  - the-observation-6da70cdd
  - the-operations-protocol-formalizing-the-missing-foundation-7457cddb
  - the-operations-protocol-formalizing-the-missing-foundation-ff73b385
project_ids: []
node_ids:
  - 'concept:name'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.854Z'
updated_at: '2026-05-03T05:32:23.404Z'
compiled_from:
  - dependabot-auto-merge-a7978ddf
  - docs-16563f41
  - dogshop-de2fc247
  - nota-v1-6168c974
  - phpunit-10eb0a3f
  - release-33611003
  - the-observation-6da70cdd
  - the-operations-protocol-formalizing-the-missing-foundation-7457cddb
  - the-operations-protocol-formalizing-the-missing-foundation-ff73b385
managed_by: system
backlinks:
  - 'source:dependabot-auto-merge-a7978ddf'
  - 'source:docs-16563f41'
  - 'source:dogshop-de2fc247'
  - 'source:nota-v1-6168c974'
  - 'source:phpunit-10eb0a3f'
  - 'source:release-33611003'
  - 'source:the-observation-6da70cdd'
  - 'source:the-operations-protocol-formalizing-the-missing-foundation-7457cddb'
  - 'source:the-operations-protocol-formalizing-the-missing-foundation-ff73b385'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dependabot-auto-merge-a7978ddf: a7978ddfbcd48167f8dce26f54a83364aa5eea149e8f5f8abdc5acdafb82baa3
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
  dogshop-de2fc247: de2fc24762d03f20dfcdb9aa4b508bb3e5895ae3374e35358c24effaf36335ea
  nota-v1-6168c974: 6168c974c71a876245a77631eddf8c1ee434c2a36a1aeebb43fb798cc13f1edb
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
  release-33611003: 3361100365722fdfa39c8d57a7c1fbce9e584ad5ad2276364ee546e54792e9d4
  the-observation-6da70cdd: 6da70cdd85d5dd12587b28ef0c8379961cb064bfa6391b1d3d47bb327482e715
  the-operations-protocol-formalizing-the-missing-foundation-7457cddb: 7457cddb2745304670ba23bec9d55dbd5191eb5f9e8a302e7a3f2d8dd7054f92
  the-operations-protocol-formalizing-the-missing-foundation-ff73b385: ff73b38575ea2e2edff4f4d0e9560a275a7c89cb4b562ac55a9bdda77604e211
source_semantic_hashes:
  dependabot-auto-merge-a7978ddf: a7978ddfbcd48167f8dce26f54a83364aa5eea149e8f5f8abdc5acdafb82baa3
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
  dogshop-de2fc247: de2fc24762d03f20dfcdb9aa4b508bb3e5895ae3374e35358c24effaf36335ea
  nota-v1-6168c974: 6168c974c71a876245a77631eddf8c1ee434c2a36a1aeebb43fb798cc13f1edb
  phpunit-10eb0a3f: 10eb0a3fd331c7dbc4b3984a40fd51ca02005e596c52a3d411eb84ff8a082a63
  release-33611003: 3361100365722fdfa39c8d57a7c1fbce9e584ad5ad2276364ee546e54792e9d4
  the-observation-6da70cdd: 8c2a962e7118d94f35b5378329335003ef4bd6b558a32757e7d1dc50fd0b47ad
  the-operations-protocol-formalizing-the-missing-foundation-7457cddb: d02fc6ac30aeeeef8b982b26d235ad25ef9705fb069a2056958fe1f6442886d9
  the-operations-protocol-formalizing-the-missing-foundation-ff73b385: c6993d72948278892186071fffd2d959b84a2950a1ba657c78487787ca65d798
---
# name

## Summary

Frequently referenced concept in dependabot-auto-merge.

## Seen In

- [[sources/dependabot-auto-merge-a7978ddf|dependabot-auto-merge]]
- [[sources/docs-16563f41|docs]]
- [[sources/dogshop-de2fc247|dogshop]]
- [[sources/nota-v1-6168c974|nota.v1]]
- [[sources/phpunit-10eb0a3f|phpunit]]
- [[sources/release-33611003|release]]
- [[sources/the-observation-6da70cdd|The Observation]]
- [[sources/the-operations-protocol-formalizing-the-missing-foundation-7457cddb|The Operations Protocol: Formalizing the Missing Foundation]]
- [[sources/the-operations-protocol-formalizing-the-missing-foundation-ff73b385|The Operations Protocol: Formalizing the Missing Foundation]]

## Source Claims

- dependabot-auto-merge Format: YAML Top-level: object Size: 4 Nested depth: 6 ## Schema - name: string - on: string - permissions: object (2 keys) - jobs: object (1 keys) ## Preview yaml name: Dependabot auto-merge on: pull_request permissions: contents: write pull-requests: write jobs: dependabot: runs-on: ubuntu-latest if: github.actor == 'dependabot[bot]' steps: - name: Dependabot metadata id: metadata uses: dependabot/fetch-metadata@v3 with: github-token: "${{ secrets.GITHUB_TOKEN }}" - name: Enable auto-merge for Dependabot PRs if: steps.metadata.outputs.update-type == 'version-update:semver-minor' || steps.metadata.outputs.update-type == 'version-update:semver-patch' run: gh pr merge --auto --rebase "$PR_URL" env: PR_URL: ${{ github.event.pull_request.html_url }} GH_TOKEN: ${{ secrets.GITHUB_TOKEN }} [source:dependabot-auto-merge-a7978ddf]
- docs Format: YAML Top-level: object Size: 5 Nested depth: 6 ## Schema - name: string - on: object (2 keys) - permissions: object (3 keys) - concurrency: object (2 keys) - jobs: object (2 keys) ## Preview yaml name: Docs on: push: branches: [main] paths: - 'docs/**' workflow_dispatch: permissions: contents: read pages: write id-token: write concurrency: group: pages cancel-in-progress: false jobs: build: runs-on: ubuntu-latest steps: - uses: actions/checkout@v6 - uses: actions/setup-node@v6 with: node-version: 22 cache: npm cache-dependency-path: docs/package-lock.json - name: Install dependencies working-directory: docs run: npm ci - name: Build working-directory: docs run: npm run build - uses: actions/upload-pages-artifact@v5 with: … [source:docs-16563f41]
- Demonstrates object composition, enum choice, and compound traits.", "input": [ { "id": "breed", "comment": "Exact breed name, e.g. [source:dogshop-de2fc247]
- \"labrador\"", "required": true, "kind": "string" }, { "id": "budget", "comment": "Maximum price in cents", "required": true, "kind": "integer" }, { "id": "express", "comment": "Next-day delivery", "kind": "boolean" }, { "id": "deliveryAddress", "comment": "Where to deliver the dog", "kind": "object", "of": [ { "id": "street", "comment": "Street name and number", "kind": "string" }, { "id": "city", "comment": "City name", "kind": "string" … [source:dogshop-de2fc247]
- phpunit Format: XML Top-level: object Size: 1 Nested depth: 3 ## Schema - phpunit: object (4 keys) ## Preview xml <?xml version="1.0" encoding="UTF-8"?> <phpunit xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="vendor/phpunit/phpunit/phpunit.xsd" bootstrap="vendor/autoload.php" backupGlobals="false" colors="true" processIsolation="false" stopOnFailure="false" stopOnError="false" stderr="true" cacheDirectory="runtime/.phpunit.cache" backupStaticProperties="false" > <coverage/> <testsuites> <testsuite name="Unit"> <directory suffix="Test.php">tests/Unit</directory> </testsuite> <testsuite name="Feature"> <directory suffix="Test.php">tests/Feature</directory> </testsuite> </testsuites> <source> <include> <directory suffix=".php">app/src</directory> </include> </source> <php> <env name="DB_CONNECTION" value="sqlite" /> <env name="DB_LOG_QUERY_PARAMETERS" value="true" /> <env name="CYCLE_SCHEMA_CACHE" value="true" /> <env name="QUEUE_CONNECTION" value="sync" /> <env name="CACHE_STORAGE" value="local" /> <env name="APP_ENV" value="testing" /> <env name="TOKENIZER_CACHE_TARGETS" value="true" /> <env name="TELEMETRY_DRIVER" value="null" /> <env name="BROADCAST_DRIVER" value="log" /> <ini name="error_reporting" value="-1"/> <ini name="memory_limit" value="-1"/> </php> … [source:phpunit-10eb0a3f]
- release Format: YAML Top-level: object Size: 3 Nested depth: 6 ## Schema - name: string - on: object (1 keys) - jobs: object (1 keys) ## Preview yaml name: Release on: workflow_dispatch: jobs: release: name: Release runs-on: ubuntu-latest permissions: contents: write issues: write pull-requests: write steps: - name: Checkout uses: actions/checkout@v6 with: fetch-depth: 0 - name: Setup Node.js uses: actions/setup-node@v6 with: node-version: "lts/*" cache: npm - name: Install dependencies run: npm ci - name: Release env: GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }} run: npx semantic-release - name: Check for new tag id: tag run: | TAG=$(git describe --tags --exact-match 2>/dev/null || echo "") echo "new=$TAG" >> "$GITHUB_OUTPUT" - name: Setup Go if: steps.tag.outputs.new != '' … [source:release-33611003]
- title: The Observation description: How we found Nota — the minimal act of recognition that humanity has always used, but never named. [source:the-observation-6da70cdd]
- # The Observation > "You cannot name something correctly without understanding it within the system. [source:the-observation-6da70cdd]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

