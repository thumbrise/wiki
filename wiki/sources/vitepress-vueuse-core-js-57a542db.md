---
page_id: 'source:vitepress-vueuse-core-js-57a542db'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: vitepress___@vueuse_core.js
source_class: first_party
tags:
  - source
source_ids:
  - vitepress-vueuse-core-js-57a542db
project_ids: []
node_ids:
  - 'source:vitepress-vueuse-core-js-57a542db'
  - 'concept:aaaa'
  - 'concept:caac'
  - 'concept:maam'
  - 'concept:qaaq'
  - 'concept:saas'
  - 'concept:oaao'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T05:11:46.073Z'
updated_at: '2026-05-03T05:32:23.300Z'
compiled_from:
  - vitepress-vueuse-core-js-57a542db
managed_by: system
backlinks:
  - 'concept:aaaa'
  - 'concept:caac'
  - 'concept:maam'
  - 'concept:qaaq'
  - 'concept:saas'
  - 'concept:oaao'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  vitepress-vueuse-core-js-57a542db: 57a542db4a2807c878cf335c0cb0c07e9f34b50786e69883614247b00ff75c3a
source_semantic_hashes:
  vitepress-vueuse-core-js-57a542db: 57a542db4a2807c878cf335c0cb0c07e9f34b50786e69883614247b00ff75c3a
---
# vitepress___@vueuse_core.js

Source ID: `vitepress-vueuse-core-js-57a542db`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/op/docs/.vitepress/cache/deps/vitepress___@vueuse_core.js.map`

Source Class: `first_party`


## Source Details

- format: json
- top level type: object
- top level size: 5
- nested depth: 2


## Summary

vitepress___@vueuse_core.js Format: JSON Top-level: object Size: 5 Nested depth: 2 ## Schema - version: number - sources: array (2 items) - sourcesContent: array (2 items) - mappings: string - names: array (25 items) ## Preview json { "version": 3, "sources": ["../../../node_modules/@vueuse/shared/index.mjs", "../../../node_modules/@vueuse/core/index.mjs"], "sourcesContent": ["import { shallowRef, watchEffect, readonly, watch, customRef, getCurrentScope, onScopeDispose, effectScope, getCurrentInstance, hasInjectionContext, inject, provide, ref, isRef, unref, toValue as toValue$1, computed, reactive, toRefs as toRefs$1, toRef as toRef$1, onBeforeMount, nextTick, onBeforeUnmount, onMounted, onUnmounted, isReactive } from 'vue';\n\nfunction computedEager(fn, options) {\n var _a;\n const result = shallowRef();\n watchEffect(() => {\n result.value = fn();\n }, {\n ...options,\n flush: (_a = options == null ? void 0 : options.flush) != null ? _a : \"sync\"\n });\n return readonly(result);\n}\n\nfunction computedWithControl(source, fn) {\n let v = void 0;\n let track;\n let trigger;\n const dirty = shallowRef(true);\n const update = () => {\n dirty.value = true;\n trigger();\n };\n watch(source, update, { flush: \"sync\" });\n const get = typeof fn === \"function\" ?

## Concepts

- [[concepts/aaaa|aaaa]]: Frequently referenced concept in vitepress___@vueuse_core.js.
- [[concepts/caac|caac]]: Frequently referenced concept in vitepress___@vueuse_core.js.
- [[concepts/maam|maam]]: Frequently referenced concept in vitepress___@vueuse_core.js.
- [[concepts/qaaq|qaaq]]: Frequently referenced concept in vitepress___@vueuse_core.js.
- [[concepts/saas|saas]]: Frequently referenced concept in vitepress___@vueuse_core.js.
- [[concepts/oaao|oaao]]: Frequently referenced concept in vitepress___@vueuse_core.js.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in vitepress___@vueuse_core.js.
- [[entities/top|Top-]]: Named entity mentioned in vitepress___@vueuse_core.js.
- [[entities/size|Size:]]: Named entity mentioned in vitepress___@vueuse_core.js.
- [[entities/nested|Nested]]: Named entity mentioned in vitepress___@vueuse_core.js.
- [[entities/schema|Schema -]]: Named entity mentioned in vitepress___@vueuse_core.js.
- [[entities/preview|Preview]]: Named entity mentioned in vitepress___@vueuse_core.js.

## Claims

- vitepress___@vueuse_core.js Format: JSON Top-level: object Size: 5 Nested depth: 2 ## Schema - version: number - sources: array (2 items) - sourcesContent: array (2 items) - mappings: string - names: array (25 items) ## Preview json { "version": 3, "sources": ["../../../node_modules/@vueuse/shared/index.mjs", "../../../node_modules/@vueuse/core/index.mjs"], "sourcesContent": ["import { shallowRef, watchEffect, readonly, watch, customRef, getCurrentScope, onScopeDispose, effectScope, getCurrentInstance, hasInjectionContext, inject, provide, ref, isRef, unref, toValue as toValue$1, computed, reactive, toRefs as toRefs$1, toRef as toRef$1, onBeforeMount, nextTick, onBeforeUnmount, onMounted, onUnmounted, isReactive } from 'vue';\n\nfunction computedEager(fn, options) {\n var _a;\n const result = shallowRef();\n watchEffect(() => {\n result.value = fn();\n }, {\n ...options,\n flush: (_a = options == null ? [source:vitepress-vueuse-core-js-57a542db]
- void 0 : options.flush) != null ? [source:vitepress-vueuse-core-js-57a542db]
- _a : \"sync\"\n });\n return readonly(result);\n}\n\nfunction computedWithControl(source, fn) {\n let v = void 0;\n let track;\n let trigger;\n const dirty = shallowRef(true);\n const update = () => {\n dirty.value = true;\n trigger();\n };\n watch(source, update, { flush: \"sync\" });\n const get = typeof fn === \"function\" ? [source:vitepress-vueuse-core-js-57a542db]
- fn : fn.get;\n const set = typeof fn === \"function\" ? [source:vitepress-vueuse-core-js-57a542db]

## Questions

- How does aaaa relate to vitepress___@vueuse_core.js?
- How does caac relate to vitepress___@vueuse_core.js?
- How does maam relate to vitepress___@vueuse_core.js?

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

