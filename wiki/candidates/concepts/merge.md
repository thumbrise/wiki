---
page_id: 'concept:merge'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: merge
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - dependabot-auto-merge-a7978ddf
project_ids: []
node_ids:
  - 'concept:merge'
freshness: fresh
status: candidate
confidence: 0.65
created_at: '2026-05-03T03:56:35.854Z'
updated_at: '2026-05-03T04:02:08.786Z'
compiled_from:
  - dependabot-auto-merge-a7978ddf
managed_by: system
backlinks:
  - 'source:dependabot-auto-merge-a7978ddf'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dependabot-auto-merge-a7978ddf: a7978ddfbcd48167f8dce26f54a83364aa5eea149e8f5f8abdc5acdafb82baa3
source_semantic_hashes:
  dependabot-auto-merge-a7978ddf: a7978ddfbcd48167f8dce26f54a83364aa5eea149e8f5f8abdc5acdafb82baa3
---
# merge

## Summary

Frequently referenced concept in dependabot-auto-merge.

## Seen In

- [[sources/dependabot-auto-merge-a7978ddf|dependabot-auto-merge]]

## Source Claims

- dependabot-auto-merge Format: YAML Top-level: object Size: 4 Nested depth: 6 ## Schema - name: string - on: string - permissions: object (2 keys) - jobs: object (1 keys) ## Preview yaml name: Dependabot auto-merge on: pull_request permissions: contents: write pull-requests: write jobs: dependabot: runs-on: ubuntu-latest if: github.actor == 'dependabot[bot]' steps: - name: Dependabot metadata id: metadata uses: dependabot/fetch-metadata@v3 with: github-token: "${{ secrets.GITHUB_TOKEN }}" - name: Enable auto-merge for Dependabot PRs if: steps.metadata.outputs.update-type == 'version-update:semver-minor' || steps.metadata.outputs.update-type == 'version-update:semver-patch' run: gh pr merge --auto --rebase "$PR_URL" env: PR_URL: ${{ github.event.pull_request.html_url }} GH_TOKEN: ${{ secrets.GITHUB_TOKEN }} [source:dependabot-auto-merge-a7978ddf]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

