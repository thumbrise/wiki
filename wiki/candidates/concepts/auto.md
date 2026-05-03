---
page_id: 'concept:auto'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: auto
source_class: first_party
tags:
  - concept
  - candidate
source_ids:
  - auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79
  - dependabot-auto-merge-a7978ddf
project_ids: []
node_ids:
  - 'concept:auto'
freshness: fresh
status: candidate
confidence: 0.8
created_at: '2026-05-03T03:56:35.852Z'
updated_at: '2026-05-03T04:02:08.777Z'
compiled_from:
  - auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79
  - dependabot-auto-merge-a7978ddf
managed_by: system
backlinks:
  - 'source:auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79'
  - 'source:dependabot-auto-merge-a7978ddf'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79: 4f36ba79c784d8d06983fd4c119f30d72326dbf29d71d5045d42a0664a7eecd1
  dependabot-auto-merge-a7978ddf: a7978ddfbcd48167f8dce26f54a83364aa5eea149e8f5f8abdc5acdafb82baa3
source_semantic_hashes:
  auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79: 4f36ba79c784d8d06983fd4c119f30d72326dbf29d71d5045d42a0664a7eecd1
  dependabot-auto-merge-a7978ddf: a7978ddfbcd48167f8dce26f54a83364aa5eea149e8f5f8abdc5acdafb82baa3
---
# auto

## Summary

Frequently referenced concept in Auto-detect text files and normalise line endings to LF..

## Seen In

- [[sources/auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79|Auto-detect text files and normalise line endings to LF.]]
- [[sources/dependabot-auto-merge-a7978ddf|dependabot-auto-merge]]

## Source Claims

- Auto-detect text files and normalise line endings to LF. [source:auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79]
- * text=auto eol=lf # Go sources *.go text eol=lf diff=golang # Config / data *.yml text eol=lf *.yaml text eol=lf *.json text eol=lf *.toml text eol=lf # Documentation *.md text eol=lf *.txt text eol=lf # Scripts *.sh text eol=lf # Go module files go.mod text eol=lf go.sum text eol=lf # CI / tooling Taskfile.yaml text eol=lf Dockerfile text eol=lf .gitignore text eol=lf .gitattributes text eol=lf .golangci.yml text eol=lf .licenserc.yaml text eol=lf LICENSE text eol=lf # Binaries — no diff, no merge, no text conversion *.db binary *.exe binary *.wasm binary *.png binary *.jpg binary *.gif binary *.ico binary # Go workspace (local only, but normalize if committed by accident) go.work text eol=lf go.work.sum text eol=lf [source:auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79]
- dependabot-auto-merge Format: YAML Top-level: object Size: 4 Nested depth: 6 ## Schema - name: string - on: string - permissions: object (2 keys) - jobs: object (1 keys) ## Preview yaml name: Dependabot auto-merge on: pull_request permissions: contents: write pull-requests: write jobs: dependabot: runs-on: ubuntu-latest if: github.actor == 'dependabot[bot]' steps: - name: Dependabot metadata id: metadata uses: dependabot/fetch-metadata@v3 with: github-token: "${{ secrets.GITHUB_TOKEN }}" - name: Enable auto-merge for Dependabot PRs if: steps.metadata.outputs.update-type == 'version-update:semver-minor' || steps.metadata.outputs.update-type == 'version-update:semver-patch' run: gh pr merge --auto --rebase "$PR_URL" env: PR_URL: ${{ github.event.pull_request.html_url }} GH_TOKEN: ${{ secrets.GITHUB_TOKEN }} [source:dependabot-auto-merge-a7978ddf]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]

