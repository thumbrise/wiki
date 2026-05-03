---
page_id: 'concept:header'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: header
source_class: first_party
tags:
  - concept
source_ids:
  - licenserc-40040b08
  - licenserc-5791d62b
  - taskfile-83d1d929
project_ids: []
node_ids:
  - 'concept:header'
freshness: fresh
status: active
confidence: 0.95
created_at: '2026-05-03T03:56:35.865Z'
updated_at: '2026-05-03T05:32:23.458Z'
compiled_from:
  - licenserc-40040b08
  - licenserc-5791d62b
  - taskfile-83d1d929
managed_by: system
backlinks:
  - 'source:licenserc-40040b08'
  - 'source:licenserc-5791d62b'
  - 'source:taskfile-83d1d929'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  licenserc-40040b08: 40040b0866e793de67a8eeb8b3c232bfc232e6ebae82b3ae3c5ea1346c9b37af
  licenserc-5791d62b: 5791d62befde49bae75799fa5d04462fdf65eb73e7e42439e7283d2645d2b239
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
source_semantic_hashes:
  licenserc-40040b08: 40040b0866e793de67a8eeb8b3c232bfc232e6ebae82b3ae3c5ea1346c9b37af
  licenserc-5791d62b: 5791d62befde49bae75799fa5d04462fdf65eb73e7e42439e7283d2645d2b239
  taskfile-83d1d929: 83d1d929f9b10f7ba8c7c9594bd3c9ef211adab28c3b794d4da63c30c52fdae9
---
# header

## Summary

Frequently referenced concept in .licenserc.

## Seen In

- [[sources/licenserc-40040b08|.licenserc]]
- [[sources/licenserc-5791d62b|.licenserc]]
- [[sources/taskfile-83d1d929|Taskfile]]

## Source Claims

- .licenserc Format: YAML Top-level: object Size: 1 Nested depth: 3 ## Schema - header: object (5 keys) ## Preview yaml header: license: spdx-id: Apache-2.0 copyright-owner: thumbrise copyright-year: '2026' software-name: op paths: - '**/*.go' - '**/*.php' - '**/*.ts' paths-ignore: - 'docs/**' - 'dist' - 'licenses' - 'poc/**' - '**/*.md' - '**/*.yaml' - '**/*.yml' - '**/testdata/**' - '**/go.mod' - '**/go.sum' - '**/package-lock.json' - '**/node_modules/**' - 'LICENSE' - 'NOTICE' - '.gitignore' - '.releaserc.js' - 'release-template.hbs' comment: on-failure license-location-threshold: 80 [source:licenserc-40040b08]
- .licenserc Format: YAML Top-level: object Size: 1 Nested depth: 3 ## Schema - header: object (5 keys) ## Preview yaml header: license: spdx-id: Apache-2.0 copyright-owner: thumbrise copyright-year: '2026' software-name: op paths: - '**/*.go' - '**/*.php' - '**/*.ts' paths-ignore: - 'docs/**' - 'dist' - 'licenses' - '**/*.md' - '**/*.yaml' - '**/*.yml' - '**/testdata/**' - '**/go.mod' - '**/go.sum' - '**/package-lock.json' - '**/node_modules/**' - 'LICENSE' - 'NOTICE' - '.gitignore' - '.releaserc.js' - 'release-template.hbs' comment: on-failure license-location-threshold: 80 [source:licenserc-5791d62b]
- Taskfile Format: YAML Top-level: object Size: 2 Nested depth: 4 ## Schema - version: string - tasks: object (4 keys) ## Preview yaml #schema: https://taskfile.dev/schema.json version: '3.17' tasks: lint: desc: Run lint with auto-fix where possible (dev workflow) cmds: - golangci-lint run --fix - go tool license-eye header fix lint:ci: desc: Run lint checks without auto-fix (CI workflow) cmds: - golangci-lint run - go tool license-eye header check test: desc: Run tests cmds: - go test ./... [source:taskfile-83d1d929]
- -v generate: desc: Fix license headers aliases: - gen cmds: - go tool license-eye header fix [source:taskfile-83d1d929]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

