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
  - release-33611003
  - the-operations-protocol-formalizing-the-missing-foundation-ff73b385
project_ids: []
node_ids:
  - 'concept:name'
freshness: fresh
status: candidate
confidence: 0.95
created_at: '2026-05-03T03:56:35.854Z'
updated_at: '2026-05-03T04:02:08.787Z'
compiled_from:
  - dependabot-auto-merge-a7978ddf
  - docs-16563f41
  - release-33611003
  - the-operations-protocol-formalizing-the-missing-foundation-ff73b385
managed_by: system
backlinks:
  - 'source:dependabot-auto-merge-a7978ddf'
  - 'source:docs-16563f41'
  - 'source:release-33611003'
  - 'source:the-operations-protocol-formalizing-the-missing-foundation-ff73b385'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  dependabot-auto-merge-a7978ddf: a7978ddfbcd48167f8dce26f54a83364aa5eea149e8f5f8abdc5acdafb82baa3
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
  release-33611003: 3361100365722fdfa39c8d57a7c1fbce9e584ad5ad2276364ee546e54792e9d4
  the-operations-protocol-formalizing-the-missing-foundation-ff73b385: ff73b38575ea2e2edff4f4d0e9560a275a7c89cb4b562ac55a9bdda77604e211
source_semantic_hashes:
  dependabot-auto-merge-a7978ddf: a7978ddfbcd48167f8dce26f54a83364aa5eea149e8f5f8abdc5acdafb82baa3
  docs-16563f41: 16563f417d008654e48c56da73fad8dbbf78d644421e55598d51e60d0e4498c7
  release-33611003: 3361100365722fdfa39c8d57a7c1fbce9e584ad5ad2276364ee546e54792e9d4
  the-operations-protocol-formalizing-the-missing-foundation-ff73b385: c6993d72948278892186071fffd2d959b84a2950a1ba657c78487787ca65d798
---
# name

## Summary

Frequently referenced concept in dependabot-auto-merge.

## Seen In

- [[sources/dependabot-auto-merge-a7978ddf|dependabot-auto-merge]]
- [[sources/docs-16563f41|docs]]
- [[sources/release-33611003|release]]
- [[sources/the-operations-protocol-formalizing-the-missing-foundation-ff73b385|The Operations Protocol: Formalizing the Missing Foundation]]

## Source Claims

- dependabot-auto-merge Format: YAML Top-level: object Size: 4 Nested depth: 6 ## Schema - name: string - on: string - permissions: object (2 keys) - jobs: object (1 keys) ## Preview yaml name: Dependabot auto-merge on: pull_request permissions: contents: write pull-requests: write jobs: dependabot: runs-on: ubuntu-latest if: github.actor == 'dependabot[bot]' steps: - name: Dependabot metadata id: metadata uses: dependabot/fetch-metadata@v3 with: github-token: "${{ secrets.GITHUB_TOKEN }}" - name: Enable auto-merge for Dependabot PRs if: steps.metadata.outputs.update-type == 'version-update:semver-minor' || steps.metadata.outputs.update-type == 'version-update:semver-patch' run: gh pr merge --auto --rebase "$PR_URL" env: PR_URL: ${{ github.event.pull_request.html_url }} GH_TOKEN: ${{ secrets.GITHUB_TOKEN }} [source:dependabot-auto-merge-a7978ddf]
- docs Format: YAML Top-level: object Size: 5 Nested depth: 6 ## Schema - name: string - on: object (2 keys) - permissions: object (3 keys) - concurrency: object (2 keys) - jobs: object (2 keys) ## Preview yaml name: Docs on: push: branches: [main] paths: - 'docs/**' workflow_dispatch: permissions: contents: read pages: write id-token: write concurrency: group: pages cancel-in-progress: false jobs: build: runs-on: ubuntu-latest steps: - uses: actions/checkout@v6 - uses: actions/setup-node@v6 with: node-version: 22 cache: npm cache-dependency-path: docs/package-lock.json - name: Install dependencies working-directory: docs run: npm ci - name: Build working-directory: docs run: npm run build - uses: actions/upload-pages-artifact@v5 with: … [source:docs-16563f41]
- release Format: YAML Top-level: object Size: 3 Nested depth: 6 ## Schema - name: string - on: object (1 keys) - jobs: object (1 keys) ## Preview yaml name: Release on: workflow_dispatch: jobs: release: name: Release runs-on: ubuntu-latest permissions: contents: write issues: write pull-requests: write steps: - name: Checkout uses: actions/checkout@v6 with: fetch-depth: 0 - name: Setup Node.js uses: actions/setup-node@v6 with: node-version: "lts/*" cache: npm - name: Install dependencies run: npm ci - name: Release env: GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }} run: npx semantic-release - name: Check for new tag id: tag run: | TAG=$(git describe --tags --exact-match 2>/dev/null || echo "") echo "new=$TAG" >> "$GITHUB_OUTPUT" - name: Setup Go if: steps.tag.outputs.new != '' … [source:release-33611003]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

