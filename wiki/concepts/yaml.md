---
page_id: 'concept:yaml'
kind: concept
cssclasses:
  - swarmvault
  - sv-concept
title: yaml
source_class: first_party
tags:
  - concept
  - ci-cd
  - continuous-integration
  - devops
  - workflow-automation
  - yaml
source_ids:
  - 3-bleed-09df896e
  - auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79
  - ci-fab63fbd
  - go-work-f103c351
  - licenserc-40040b08
  - licenserc-5791d62b
project_ids: []
node_ids:
  - 'concept:yaml'
freshness: fresh
status: active
confidence: 0.95
created_at: '2026-05-03T03:56:35.852Z'
updated_at: '2026-05-03T05:32:23.367Z'
compiled_from:
  - 3-bleed-09df896e
  - auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79
  - ci-fab63fbd
  - go-work-f103c351
  - licenserc-40040b08
  - licenserc-5791d62b
managed_by: system
backlinks:
  - 'source:3-bleed-09df896e'
  - 'source:auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79'
  - 'source:ci-fab63fbd'
  - 'source:go-work-f103c351'
  - 'source:licenserc-40040b08'
  - 'source:licenserc-5791d62b'
  - 'output:source-briefs/github_repo-thumbrise-op-a16ed6ba'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  3-bleed-09df896e: 09df896ec6ba2b2cc3961058e470f26aac663052c5bd8129d47c4af34989a27a
  auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79: 4f36ba79c784d8d06983fd4c119f30d72326dbf29d71d5045d42a0664a7eecd1
  ci-fab63fbd: fab63fbd6c494e889ed302d48cdcff49880b708788bef27b34f2ea8884393185
  go-work-f103c351: f103c3510e3af47fa665357f618f57e16a373b315e4f2d837bbc50dd335e7a7a
  licenserc-40040b08: 40040b0866e793de67a8eeb8b3c232bfc232e6ebae82b3ae3c5ea1346c9b37af
  licenserc-5791d62b: 5791d62befde49bae75799fa5d04462fdf65eb73e7e42439e7283d2645d2b239
source_semantic_hashes:
  3-bleed-09df896e: 13209ed892c96cf5868b9321f2d489234bf3a3a55bbad99feeda470d024a566a
  auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79: 4f36ba79c784d8d06983fd4c119f30d72326dbf29d71d5045d42a0664a7eecd1
  ci-fab63fbd: fab63fbd6c494e889ed302d48cdcff49880b708788bef27b34f2ea8884393185
  go-work-f103c351: f103c3510e3af47fa665357f618f57e16a373b315e4f2d837bbc50dd335e7a7a
  licenserc-40040b08: 40040b0866e793de67a8eeb8b3c232bfc232e6ebae82b3ae3c5ea1346c9b37af
  licenserc-5791d62b: 5791d62befde49bae75799fa5d04462fdf65eb73e7e42439e7283d2645d2b239
---
# yaml

## Summary

Frequently referenced concept in #3 — Bleed.

## Seen In

- [[sources/3-bleed-09df896e|#3 — Bleed]]
- [[sources/auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79|Auto-detect text files and normalise line endings to LF.]]
- [[sources/ci-fab63fbd|ci]]
- [[sources/go-work-f103c351|go.work]]
- [[sources/licenserc-40040b08|.licenserc]]
- [[sources/licenserc-5791d62b|.licenserc]]

## Source Claims

- title: #3 — Bleed description: Opened .rr.yaml. [source:3-bleed-09df896e]
- * text=auto eol=lf # Go sources *.go text eol=lf diff=golang # Config / data *.yml text eol=lf *.yaml text eol=lf *.json text eol=lf *.toml text eol=lf # Documentation *.md text eol=lf *.txt text eol=lf # Scripts *.sh text eol=lf # Go module files go.mod text eol=lf go.sum text eol=lf # CI / tooling Taskfile.yaml text eol=lf Dockerfile text eol=lf .gitignore text eol=lf .gitattributes text eol=lf .golangci.yml text eol=lf .licenserc.yaml text eol=lf LICENSE text eol=lf # Binaries — no diff, no merge, no text conversion *.db binary *.exe binary *.wasm binary *.png binary *.jpg binary *.gif binary *.ico binary # Go workspace (local only, but normalize if committed by accident) go.work text eol=lf go.work.sum text eol=lf [source:auto-detect-text-files-and-normalise-line-endings-to-lf-4f36ba79]
- The CI format uses YAML and is structured as a top-level object. [source:ci-fab63fbd]
- cloud.google.com/go/compute/metadata v0.3.0 h1:Tz+eQXMEqDIKRsmY3cHTL6FVaynIjX2QxYC4trgAKZc= cloud.google.com/go/compute/metadata v0.3.0/go.mod h1:zFmK7XCadkQkj6TtorcaGlCW1hT1fIilQDwofLpJ20k= github.com/bwesterb/go-ristretto v1.2.3 h1:1w53tCkGhCQ5djbat3+MH0BAQ5Kfgbt56UZQ/JMzngw= github.com/bwesterb/go-ristretto v1.2.3/go.mod h1:fUIoIZaG73pV5biE2Blr2xEzDoMj7NFEuV9ekS419A0= github.com/cpuguy83/go-md2man/v2 v2.0.6 h1:XJtiaUW6dEEqVuZiMTn1ldk455QWwEIsMIJlo5vtkx0= github.com/golang/protobuf v1.5.4 h1:i7eJL8qZTpSEXOPTxNKhASYpMn+8e5Q6AdndVa1dWek= github.com/golang/protobuf v1.5.4/go.mod h1:lnTiLA8Wa4RWRcIUkrtSVa5nRhsEGBg48fD6rSs7xps= github.com/kr/pty v1.1.1 h1:VkoXIwSboBpnk99O/KFauAEILuNHv5DVFKZMBN/gUgw= github.com/russross/blackfriday/v2 v2.1.0 h1:JIOH55/0cWyOuilr9/qlrm0BSXldqnqwMsf35Ld67mk= github.com/stretchr/objx v0.5.2 h1:xuMeJ0Sdp5ZMRXx/aWO6RZxdr3beISkG5/G/aIRr3pY= github.com/stretchr/objx v0.5.2/go.mod h1:FRsXN1f5AsAjCGJKqEizvkpNtU+EGNCLh3NxZ/8L+MA= github.com/yuin/goldmark v1.4.13 h1:fVcFKWvrslecOb/tg+Cc05dkeYx540o0FuFt3nUVDoE= go.yaml.in/yaml/v3 v3.0.4 h1:tfq32ie2Jv2UxXFdLJdh3jXuOzWiL1fo0bu/FbuKpbc= golang.org/x/xerrors v0.0.0-20190717185122-a985d3407aa7 h1:9zdDQZ7Thm29KFXgAX/+yaf3eVbP7djjWp/dXAppNCc= google.golang.org/appengine v1.1.0 h1:igQkv0AAhEIvTEpD5LIpAfav2eeVO9HBTjvKHVJPRSs= google.golang.org/protobuf v1.33.0 h1:uNO2rsAINq/JlFpSdYEKIZ0uKD/R9cpdv0T+yoGwGmI= google.golang.org/protobuf v1.33.0/go.mod h1:c6P6GXX6sHbq/GpV6MGZEdwhWPcYBgnhAHhKbcUYpos= gopkg.in/yaml.v2 v2.4.0 h1:D8xgwECY7CYvx+Y2n4sBz93Jn9JRvxdiyyo8CTfuKaY= [source:go-work-f103c351]
- .licenserc Format: YAML Top-level: object Size: 1 Nested depth: 3 ## Schema - header: object (5 keys) ## Preview yaml header: license: spdx-id: Apache-2.0 copyright-owner: thumbrise copyright-year: '2026' software-name: op paths: - '**/*.go' - '**/*.php' - '**/*.ts' paths-ignore: - 'docs/**' - 'dist' - 'licenses' - 'poc/**' - '**/*.md' - '**/*.yaml' - '**/*.yml' - '**/testdata/**' - '**/go.mod' - '**/go.sum' - '**/package-lock.json' - '**/node_modules/**' - 'LICENSE' - 'NOTICE' - '.gitignore' - '.releaserc.js' - 'release-template.hbs' comment: on-failure license-location-threshold: 80 [source:licenserc-40040b08]
- .licenserc Format: YAML Top-level: object Size: 1 Nested depth: 3 ## Schema - header: object (5 keys) ## Preview yaml header: license: spdx-id: Apache-2.0 copyright-owner: thumbrise copyright-year: '2026' software-name: op paths: - '**/*.go' - '**/*.php' - '**/*.ts' paths-ignore: - 'docs/**' - 'dist' - 'licenses' - '**/*.md' - '**/*.yaml' - '**/*.yml' - '**/testdata/**' - '**/go.mod' - '**/go.sum' - '**/package-lock.json' - '**/node_modules/**' - 'LICENSE' - 'NOTICE' - '.gitignore' - '.releaserc.js' - 'release-template.hbs' comment: on-failure license-location-threshold: 80 [source:licenserc-5791d62b]

## Related Outputs

- [[outputs/source-briefs/github_repo-thumbrise-op-a16ed6ba|Source Brief: checkout]]
- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

