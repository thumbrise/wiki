---
page_id: 'source:dependabot-auto-merge-a7978ddf'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: dependabot-auto-merge
source_class: first_party
tags:
  - source
source_ids:
  - dependabot-auto-merge-a7978ddf
project_ids: []
node_ids:
  - 'source:dependabot-auto-merge-a7978ddf'
  - 'concept:dependabot'
  - 'concept:github'
  - 'concept:metadata'
  - 'concept:auto'
  - 'concept:merge'
  - 'concept:name'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T03:56:35.827Z'
updated_at: '2026-05-03T05:32:23.218Z'
compiled_from:
  - dependabot-auto-merge-a7978ddf
managed_by: system
backlinks:
  - 'concept:dependabot'
  - 'concept:github'
  - 'concept:metadata'
  - 'concept:auto'
  - 'concept:merge'
  - 'concept:name'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dependabot-auto-merge-a7978ddf: a7978ddfbcd48167f8dce26f54a83364aa5eea149e8f5f8abdc5acdafb82baa3
source_semantic_hashes:
  dependabot-auto-merge-a7978ddf: a7978ddfbcd48167f8dce26f54a83364aa5eea149e8f5f8abdc5acdafb82baa3
---
# dependabot-auto-merge

Source ID: `dependabot-auto-merge-a7978ddf`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/wiki/state/sources/github_repo-thumbrise-op-a16ed6ba/checkout/.github/workflows/dependabot-auto-merge.yml`

Source Class: `first_party`


## Source Details

- format: yaml
- top level type: object
- top level size: 4
- nested depth: 6


## Summary

dependabot-auto-merge Format: YAML Top-level: object Size: 4 Nested depth: 6 ## Schema - name: string - on: string - permissions: object (2 keys) - jobs: object (1 keys) ## Preview yaml name: Dependabot auto-merge on: pull_request permissions: contents: write pull-requests: write jobs: dependabot: runs-on: ubuntu-latest if: github.actor == 'dependabot[bot]' steps: - name: Dependabot metadata id: metadata uses: dependabot/fetch-metadata@v3 with: github-token: "${{ secrets.GITHUB_TOKEN }}" - name: Enable auto-merge for Dependabot PRs if: steps.metadata.outputs.update-type == 'version-update:semver-minor' || steps.metadata.outputs.update-type == 'version-update:semver-patch' run: gh pr merge --auto --rebase "$PR_URL" env: PR_URL: ${{ github.event.pull_request.html_url }} GH_TOKEN: ${{ secrets.GITHUB_TOKEN }}

## Concepts

- [[concepts/dependabot|dependabot]]: Frequently referenced concept in dependabot-auto-merge.
- [[concepts/github|github]]: Frequently referenced concept in dependabot-auto-merge.
- [[concepts/metadata|metadata]]: Frequently referenced concept in dependabot-auto-merge.
- [[concepts/auto|auto]]: Frequently referenced concept in dependabot-auto-merge.
- [[concepts/merge|merge]]: Frequently referenced concept in dependabot-auto-merge.
- [[concepts/name|name]]: Frequently referenced concept in dependabot-auto-merge.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in dependabot-auto-merge.
- [[entities/top|Top-]]: Named entity mentioned in dependabot-auto-merge.
- [[entities/size|Size:]]: Named entity mentioned in dependabot-auto-merge.
- [[entities/nested|Nested]]: Named entity mentioned in dependabot-auto-merge.
- [[entities/schema|Schema -]]: Named entity mentioned in dependabot-auto-merge.
- [[entities/preview|Preview]]: Named entity mentioned in dependabot-auto-merge.

## Claims

- dependabot-auto-merge Format: YAML Top-level: object Size: 4 Nested depth: 6 ## Schema - name: string - on: string - permissions: object (2 keys) - jobs: object (1 keys) ## Preview yaml name: Dependabot auto-merge on: pull_request permissions: contents: write pull-requests: write jobs: dependabot: runs-on: ubuntu-latest if: github.actor == 'dependabot[bot]' steps: - name: Dependabot metadata id: metadata uses: dependabot/fetch-metadata@v3 with: github-token: "${{ secrets.GITHUB_TOKEN }}" - name: Enable auto-merge for Dependabot PRs if: steps.metadata.outputs.update-type == 'version-update:semver-minor' || steps.metadata.outputs.update-type == 'version-update:semver-patch' run: gh pr merge --auto --rebase "$PR_URL" env: PR_URL: ${{ github.event.pull_request.html_url }} GH_TOKEN: ${{ secrets.GITHUB_TOKEN }} [source:dependabot-auto-merge-a7978ddf]

## Questions

- How does dependabot relate to dependabot-auto-merge?
- How does github relate to dependabot-auto-merge?
- How does metadata relate to dependabot-auto-merge?

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

