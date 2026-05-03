---
page_id: 'source:chunk-7oikw5wk-js-e8520523'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: chunk-7OIKW5WK.js
source_class: first_party
tags:
  - source
source_ids:
  - chunk-7oikw5wk-js-e8520523
project_ids: []
node_ids:
  - 'source:chunk-7oikw5wk-js-e8520523'
  - 'concept:aaaa'
  - 'concept:caac'
  - 'concept:iaai'
  - 'concept:maam'
  - 'concept:saas'
  - 'concept:kaak'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T05:11:46.009Z'
updated_at: '2026-05-03T05:32:23.192Z'
compiled_from:
  - chunk-7oikw5wk-js-e8520523
managed_by: system
backlinks:
  - 'concept:aaaa'
  - 'concept:caac'
  - 'concept:iaai'
  - 'concept:maam'
  - 'concept:saas'
  - 'concept:kaak'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  chunk-7oikw5wk-js-e8520523: e8520523171ded7e71554e63e91c2cbcfd21a11d58350593194f0fd3bac2f0c3
source_semantic_hashes:
  chunk-7oikw5wk-js-e8520523: e8520523171ded7e71554e63e91c2cbcfd21a11d58350593194f0fd3bac2f0c3
---
# chunk-7OIKW5WK.js

Source ID: `chunk-7oikw5wk-js-e8520523`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/op/docs/.vitepress/cache/deps/chunk-7OIKW5WK.js.map`

Source Class: `first_party`


## Source Details

- format: json
- top level type: object
- top level size: 5
- nested depth: 2


## Summary

chunk-7OIKW5WK.js Format: JSON Top-level: object Size: 5 Nested depth: 2 ## Schema - version: number - sources: array (5 items) - sourcesContent: array (5 items) - mappings: string - names: array (42 items) ## Preview json { "version": 3, "sources": ["../../../node_modules/@vue/shared/dist/shared.esm-bundler.js", "../../../node_modules/@vue/reactivity/dist/reactivity.esm-bundler.js", "../../../node_modules/@vue/runtime-core/dist/runtime-core.esm-bundler.js", "../../../node_modules/@vue/runtime-dom/dist/runtime-dom.esm-bundler.js", "../../../node_modules/vue/dist/vue.runtime.esm-bundler.js"], "sourcesContent": ["/**\n* @vue/shared v3.5.31\n* (c) 2018-present Yuxi (Evan) You and Vue contributors\n* @license MIT\n**/\n// @__NO_SIDE_EFFECTS__\nfunction makeMap(str) {\n const map = /* @__PURE__ */ Object.create(null);\n for (const key of str.split(\",\")) map[key] = 1;\n return (val) => val in map;\n}\n\nconst EMPTY_OBJ = !!(process.env.NODE_ENV !== \"production\") ? Object.freeze({}) : {};\nconst EMPTY_ARR = !!(process.env.NODE_ENV !== \"production\") ? Object.freeze([]) : [];\nconst NOOP = () => {\n};\nconst NO = () => false;\nconst isOn = (key) => key.charCodeAt(0) === 111 && key.charCodeAt(1) === 110 && // uppercase letter\n(key.charCodeAt(2) > 122 || key.charCodeAt(2) < 97);\nconst isModelListener = (key) => key.startsWith(\"onUpdate:\");\nconst extend = Object.assign;\nconst remove = (arr, el) => {\n const i = arr.indexOf(el);\n if (i > -1) {\n arr.splice(i, 1);\n }\n};\nconst hasOwnProperty = Object.prototype.hasOwnProperty;\nconst hasOwn = (val, key) => hasOwnProperty.call(val, key);\nconst isArray = Array.isArray;\nconst isMap = (val) => toTypeString(val) === \"[object Map]\";\nconst isSet = (val) => toTypeString(val) === \"[object Set]\";\nconst isDate = (val) => toTypeString(val) === \"[object Date]\";\nconst isRegExp = (val) => toTypeString(val) === \"[object RegExp]\";\nconst isFunction = (val) => typeof val === \"function\";\nconst isString = (val) => typeof val === \"string\";\nconst isSymbol = (val) => typeof val === \"symbol\";\nconst isObject = (val) => val !== null && typeof val === \"object\";\nconst isPromise = (val) => {\n return (isObject(val) || isFunction(val)) && isFunction(val.then) && isFunction(val.catch);\n};\nconst objectToString = Object.prototype.toString;\nconst toTypeString = (value) => objectToString.call(value);\nconst toRawType = (value) => {\n return toTypeString(value).slice(8, -1);\n};\nconst isPlainObject = (val) => toTypeString(val) === \"[object Object]\";\nconst isIntegerKey = (key) => isString(key) && key !== \"NaN\" && key[0] !== \"-\" && \"\" + parseInt(key, 10) === key;\nconst isReservedProp = /* @__PURE__ */ makeMap(\n // the leading comma is intentional so empty string \"\" is also included\n \",key,ref,ref_for,ref_key,onVnodeBeforeMount,onVnodeMounted,onVnodeBeforeUpdate,onVnodeUpdated,onVnodeBeforeUnmount,onVnodeUnmounted\"\n);\nconst isBuiltInDirective = /* @__PURE__ */ makeMap(\n \"bind,cloak,else-if,else,for,html,if,model,on,once,pre,show,slot,text,memo\"\n);\nconst cacheStringFunction = (fn) => {\n const cache = /* @__PURE__ */ Object.create(null);\n return ((str) => {\n const hit = cache[str];\n return hit || (cache[str] = fn(str));\n });\n};\nconst camelizeRE = /-\\w/g;\nconst camelize = cacheStringFunction(\n (str) => {\n return str.replace(camelizeRE, (c) => c.slice(1).toUpperCase());\n }\n);\nconst hyphenateRE = /\\B([A-Z])/g;\nconst hyphenate = cacheStringFunction(\n (str) => str.replace(hyphenateRE, \"-$1\").toLowerCase()\n);\nconst capitalize = cacheStringFunction((str) => {\n return str.charAt(0).toUpperCase() + str.slice(1);\n});\nconst toHandlerKey = cacheStringFunction(\n (str) => {\n const s = str ?

## Concepts

- [[concepts/aaaa|aaaa]]: Frequently referenced concept in chunk-7OIKW5WK.js.
- [[concepts/caac|caac]]: Frequently referenced concept in chunk-7OIKW5WK.js.
- [[concepts/iaai|iaai]]: Frequently referenced concept in chunk-7OIKW5WK.js.
- [[concepts/maam|maam]]: Frequently referenced concept in chunk-7OIKW5WK.js.
- [[concepts/saas|saas]]: Frequently referenced concept in chunk-7OIKW5WK.js.
- [[concepts/kaak|kaak]]: Frequently referenced concept in chunk-7OIKW5WK.js.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in chunk-7OIKW5WK.js.
- [[entities/top|Top-]]: Named entity mentioned in chunk-7OIKW5WK.js.
- [[entities/size|Size:]]: Named entity mentioned in chunk-7OIKW5WK.js.
- [[entities/nested|Nested]]: Named entity mentioned in chunk-7OIKW5WK.js.
- [[entities/schema|Schema -]]: Named entity mentioned in chunk-7OIKW5WK.js.
- [[entities/preview|Preview]]: Named entity mentioned in chunk-7OIKW5WK.js.

## Claims

- chunk-7OIKW5WK.js Format: JSON Top-level: object Size: 5 Nested depth: 2 ## Schema - version: number - sources: array (5 items) - sourcesContent: array (5 items) - mappings: string - names: array (42 items) ## Preview json { "version": 3, "sources": ["../../../node_modules/@vue/shared/dist/shared.esm-bundler.js", "../../../node_modules/@vue/reactivity/dist/reactivity.esm-bundler.js", "../../../node_modules/@vue/runtime-core/dist/runtime-core.esm-bundler.js", "../../../node_modules/@vue/runtime-dom/dist/runtime-dom.esm-bundler.js", "../../../node_modules/vue/dist/vue.runtime.esm-bundler.js"], "sourcesContent": ["/**\n* @vue/shared v3.5.31\n* (c) 2018-present Yuxi (Evan) You and Vue contributors\n* @license MIT\n**/\n// @__NO_SIDE_EFFECTS__\nfunction makeMap(str) {\n const map = /* @__PURE__ */ Object.create(null);\n for (const key of str.split(\",\")) map[key] = 1;\n return (val) => val in map;\n}\n\nconst EMPTY_OBJ = !!(process.env.NODE_ENV !== \"production\") ? [source:chunk-7oikw5wk-js-e8520523]
- Object.freeze({}) : {};\nconst EMPTY_ARR = !!(process.env.NODE_ENV !== \"production\") ? [source:chunk-7oikw5wk-js-e8520523]
- Object.freeze([]) : [];\nconst NOOP = () => {\n};\nconst NO = () => false;\nconst isOn = (key) => key.charCodeAt(0) === 111 && key.charCodeAt(1) === 110 && // uppercase letter\n(key.charCodeAt(2) > 122 || key.charCodeAt(2) < 97);\nconst isModelListener = (key) => key.startsWith(\"onUpdate:\");\nconst extend = Object.assign;\nconst remove = (arr, el) => {\n const i = arr.indexOf(el);\n if (i > -1) {\n arr.splice(i, 1);\n }\n};\nconst hasOwnProperty = Object.prototype.hasOwnProperty;\nconst hasOwn = (val, key) => hasOwnProperty.call(val, key);\nconst isArray = Array.isArray;\nconst isMap = (val) => toTypeString(val) === \"[object Map]\";\nconst isSet = (val) => toTypeString(val) === \"[object Set]\";\nconst isDate = (val) => toTypeString(val) === \"[object Date]\";\nconst isRegExp = (val) => toTypeString(val) === \"[object RegExp]\";\nconst isFunction = (val) => typeof val === \"function\";\nconst isString = (val) => typeof val === \"string\";\nconst isSymbol = (val) => typeof val === \"symbol\";\nconst isObject = (val) => val !== null && typeof val === \"object\";\nconst isPromise = (val) => {\n return (isObject(val) || isFunction(val)) && isFunction(val.then) && isFunction(val.catch);\n};\nconst objectToString = Object.prototype.toString;\nconst toTypeString = (value) => objectToString.call(value);\nconst toRawType = (value) => {\n return toTypeString(value).slice(8, -1);\n};\nconst isPlainObject = (val) => toTypeString(val) === \"[object Object]\";\nconst isIntegerKey = (key) => isString(key) && key !== \"NaN\" && key[0] !== \"-\" && \"\" + parseInt(key, 10) === key;\nconst isReservedProp = /* @__PURE__ */ makeMap(\n // the leading comma is intentional so empty string \"\" is also included\n \",key,ref,ref_for,ref_key,onVnodeBeforeMount,onVnodeMounted,onVnodeBeforeUpdate,onVnodeUpdated,onVnodeBeforeUnmount,onVnodeUnmounted\"\n);\nconst isBuiltInDirective = /* @__PURE__ */ makeMap(\n \"bind,cloak,else-if,else,for,html,if,model,on,once,pre,show,slot,text,memo\"\n);\nconst cacheStringFunction = (fn) => {\n const cache = /* @__PURE__ */ Object.create(null);\n return ((str) => {\n const hit = cache[str];\n return hit || (cache[str] = fn(str));\n });\n};\nconst camelizeRE = /-\\w/g;\nconst camelize = cacheStringFunction(\n (str) => {\n return str.replace(camelizeRE, (c) => c.slice(1).toUpperCase());\n }\n);\nconst hyphenateRE = /\\B([A-Z])/g;\nconst hyphenate = cacheStringFunction(\n (str) => str.replace(hyphenateRE, \"-$1\").toLowerCase()\n);\nconst capitalize = cacheStringFunction((str) => {\n return str.charAt(0).toUpperCase() + str.slice(1);\n});\nconst toHandlerKey = cacheStringFunction(\n (str) => {\n const s = str ? [source:chunk-7oikw5wk-js-e8520523]
- `on${capitalize(str)}` : ``;\n return s;\n }\n);\nconst hasChanged = (value, oldValue) => !Object.is(value, oldValue);\nconst invokeArrayFns = (fns, ...arg) => {\n for (let i = 0; i < fns.length; i++) {\n fns[i](...arg);\n }\n};\nconst def = (obj, key, value, writable = false) => {\n Object.defineProperty(obj, key, {\n configurable: true,\n enumerable: false,\n writable,\n value\n });\n};\nconst looseToNumber = (val) => {\n const n = parseFloat(val);\n return isNaN(n) ? [source:chunk-7oikw5wk-js-e8520523]

## Questions

- How does aaaa relate to chunk-7OIKW5WK.js?
- How does caac relate to chunk-7OIKW5WK.js?
- How does iaai relate to chunk-7OIKW5WK.js?

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

