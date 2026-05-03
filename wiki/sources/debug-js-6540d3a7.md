---
page_id: 'source:debug-js-6540d3a7'
kind: source
cssclasses:
  - swarmvault
  - sv-source
title: debug.js
source_class: first_party
tags:
  - source
source_ids:
  - debug-js-6540d3a7
project_ids: []
node_ids:
  - 'source:debug-js-6540d3a7'
  - 'concept:aaaa'
  - 'concept:kaak'
  - 'concept:oaao'
  - 'concept:maca'
  - 'concept:maam'
  - 'concept:iaai'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
freshness: fresh
status: active
confidence: 1
created_at: '2026-05-03T05:11:46.016Z'
updated_at: '2026-05-03T05:32:23.215Z'
compiled_from:
  - debug-js-6540d3a7
managed_by: system
backlinks:
  - 'concept:aaaa'
  - 'concept:kaak'
  - 'concept:oaao'
  - 'concept:maca'
  - 'concept:maam'
  - 'concept:iaai'
  - 'entity:format'
  - 'entity:top'
  - 'entity:size'
  - 'entity:nested'
  - 'entity:schema'
  - 'entity:preview'
  - 'output:source-briefs/directory-op-597d97ce'
schema_hash: 874431dbbfdec0b254a4aa1bf002900574c9b485735a883690c2becb5f717720
source_hashes:
  debug-js-6540d3a7: 6540d3a7936fe403fca902ad37b56e9fcb6aaae1de33569b2c357b1caf1097ad
source_semantic_hashes:
  debug-js-6540d3a7: 6540d3a7936fe403fca902ad37b56e9fcb6aaae1de33569b2c357b1caf1097ad
---
# debug.js

Source ID: `debug-js-6540d3a7`
Source Kind: `data`
Source Path: `/Users/rk/GolandProjects/op/docs/.vitepress/cache/deps/debug.js.map`

Source Class: `first_party`


## Source Details

- format: json
- top level type: object
- top level size: 5
- nested depth: 2


## Summary

debug.js Format: JSON Top-level: object Size: 5 Nested depth: 2 ## Schema - version: number - sources: array (3 items) - sourcesContent: array (3 items) - mappings: string - names: array (0 items) ## Preview json { "version": 3, "sources": ["../../../../node_modules/ms/index.js", "../../../../node_modules/debug/src/common.js", "../../../../node_modules/debug/src/browser.js"], "sourcesContent": ["/**\n * Helpers.\n */\n\nvar s = 1000;\nvar m = s * 60;\nvar h = m * 60;\nvar d = h * 24;\nvar w = d * 7;\nvar y = d * 365.25;\n\n/**\n * Parse or format the given `val`.\n *\n * Options:\n *\n * - `long` verbose formatting [false]\n *\n * @param {String|Number} val\n * @param {Object} [options]\n * @throws {Error} throw an error if val is not a non-empty string or a number\n * @return {String|Number}\n * @api public\n */\n\nmodule.exports = function (val, options) {\n options = options || {};\n var type = typeof val;\n if (type === 'string' && val.length > 0) {\n return parse(val);\n } else if (type === 'number' && isFinite(val)) {\n return options.long ? fmtLong(val) : fmtShort(val);\n }\n throw new Error(\n 'val is not a non-empty string or a valid number. val=' +\n JSON.stringify(val)\n );\n};\n\n/**\n * Parse the given `str` and return milliseconds.\n *\n * @param {String} str\n * @return {Number}\n * @api private\n */\n\nfunction parse(str) {\n str = String(str);\n if (str.length > 100) {\n return;\n }\n var match = /^(-?(?:\\d+)?\\.?\\d+) *(milliseconds?|msecs?|ms|seconds?|secs?|s|minutes?|mins?|m|hours?|hrs?|h|days?|d|weeks?|w|years?|yrs?|y)?$/i.exec(\n str\n );\n if (!match) {\n return;\n }\n var n = parseFloat(match[1]);\n var type = (match[2] || 'ms').toLowerCase();\n switch (type) {\n case 'years':\n case 'year':\n case 'yrs':\n case 'yr':\n case 'y':\n return n * y;\n case 'weeks':\n case 'week':\n case 'w':\n return n * w;\n case 'days':\n case 'day':\n case 'd':\n return n * d;\n case 'hours':\n case 'hour':\n case 'hrs':\n case 'hr':\n case 'h':\n return n * h;\n case 'minutes':\n case 'minute':\n case 'mins':\n case 'min':\n case 'm':\n return n * m;\n case 'seconds':\n case 'second':\n case 'secs':\n case 'sec':\n case 's':\n return n * s;\n case 'milliseconds':\n case 'millisecond':\n case 'msecs':\n case 'msec':\n case 'ms':\n return n;\n default:\n return undefined;\n }\n}\n\n/**\n * Short format for `ms`.\n *\n * @param {Number} ms\n * @return {String}\n * @api private\n */\n\nfunction fmtShort(ms) {\n var msAbs = Math.abs(ms);\n if (msAbs >= d) {\n return Math.round(ms / d) + 'd';\n }\n if (msAbs >= h) {\n return Math.round(ms / h) + 'h';\n }\n if (msAbs >= m) {\n return Math.round(ms / m) + 'm';\n }\n if (msAbs >= s) {\n return Math.round(ms / s) + 's';\n }\n return ms + 'ms';\n}\n\n/**\n * Long format for `ms`.\n *\n * @param {Number} ms\n * @return {String}\n * @api private\n */\n\nfunction fmtLong(ms) {\n var msAbs = Math.abs(ms);\n if (msAbs >= d) {\n return plural(ms, msAbs, d, 'day');\n }\n if (msAbs >= h) {\n return plural(ms, msAbs, h, 'hour');\n }\n if (msAbs >= m) {\n return plural(ms, msAbs, m, 'minute');\n }\n if (msAbs >= s) {\n return plural(ms, msAbs, s, 'second');\n }\n return ms + ' ms';\n}\n\n/**\n * Pluralization helper.\n */\n\nfunction plural(ms, msAbs, n, name) {\n var isPlural = msAbs >= n * 1.5;\n return Math.round(ms / n) + ' ' + name + (isPlural ?

## Concepts

- [[concepts/aaaa|aaaa]]: Frequently referenced concept in debug.js.
- [[concepts/kaak|kaak]]: Frequently referenced concept in debug.js.
- [[concepts/oaao|oaao]]: Frequently referenced concept in debug.js.
- [[concepts/maca|maca]]: Frequently referenced concept in debug.js.
- [[concepts/maam|maam]]: Frequently referenced concept in debug.js.
- [[concepts/iaai|iaai]]: Frequently referenced concept in debug.js.

## Entities

- [[entities/format|Format:]]: Named entity mentioned in debug.js.
- [[entities/top|Top-]]: Named entity mentioned in debug.js.
- [[entities/size|Size:]]: Named entity mentioned in debug.js.
- [[entities/nested|Nested]]: Named entity mentioned in debug.js.
- [[entities/schema|Schema -]]: Named entity mentioned in debug.js.
- [[entities/preview|Preview]]: Named entity mentioned in debug.js.

## Claims

- debug.js Format: JSON Top-level: object Size: 5 Nested depth: 2 ## Schema - version: number - sources: array (3 items) - sourcesContent: array (3 items) - mappings: string - names: array (0 items) ## Preview json { "version": 3, "sources": ["../../../../node_modules/ms/index.js", "../../../../node_modules/debug/src/common.js", "../../../../node_modules/debug/src/browser.js"], "sourcesContent": ["/**\n * Helpers.\n */\n\nvar s = 1000;\nvar m = s * 60;\nvar h = m * 60;\nvar d = h * 24;\nvar w = d * 7;\nvar y = d * 365.25;\n\n/**\n * Parse or format the given `val`.\n *\n * Options:\n *\n * - `long` verbose formatting [false]\n *\n * @param {String|Number} val\n * @param {Object} [options]\n * @throws {Error} throw an error if val is not a non-empty string or a number\n * @return {String|Number}\n * @api public\n */\n\nmodule.exports = function (val, options) {\n options = options || {};\n var type = typeof val;\n if (type === 'string' && val.length > 0) {\n return parse(val);\n } else if (type === 'number' && isFinite(val)) {\n return options.long ? [source:debug-js-6540d3a7]
- fmtLong(val) : fmtShort(val);\n }\n throw new Error(\n 'val is not a non-empty string or a valid number. [source:debug-js-6540d3a7]
- val=' +\n JSON.stringify(val)\n );\n};\n\n/**\n * Parse the given `str` and return milliseconds.\n *\n * @param {String} str\n * @return {Number}\n * @api private\n */\n\nfunction parse(str) {\n str = String(str);\n if (str.length > 100) {\n return;\n }\n var match = /^(-?(?:\\d+)?\\.?\\d+) *(milliseconds?|msecs?|ms|seconds?|secs?|s|minutes?|mins?|m|hours?|hrs?|h|days?|d|weeks?|w|years?|yrs?|y)?$/i.exec(\n str\n );\n if (!match) {\n return;\n }\n var n = parseFloat(match[1]);\n var type = (match[2] || 'ms').toLowerCase();\n switch (type) {\n case 'years':\n case 'year':\n case 'yrs':\n case 'yr':\n case 'y':\n return n * y;\n case 'weeks':\n case 'week':\n case 'w':\n return n * w;\n case 'days':\n case 'day':\n case 'd':\n return n * d;\n case 'hours':\n case 'hour':\n case 'hrs':\n case 'hr':\n case 'h':\n return n * h;\n case 'minutes':\n case 'minute':\n case 'mins':\n case 'min':\n case 'm':\n return n * m;\n case 'seconds':\n case 'second':\n case 'secs':\n case 'sec':\n case 's':\n return n * s;\n case 'milliseconds':\n case 'millisecond':\n case 'msecs':\n case 'msec':\n case 'ms':\n return n;\n default:\n return undefined;\n }\n}\n\n/**\n * Short format for `ms`.\n *\n * @param {Number} ms\n * @return {String}\n * @api private\n */\n\nfunction fmtShort(ms) {\n var msAbs = Math.abs(ms);\n if (msAbs >= d) {\n return Math.round(ms / d) + 'd';\n }\n if (msAbs >= h) {\n return Math.round(ms / h) + 'h';\n }\n if (msAbs >= m) {\n return Math.round(ms / m) + 'm';\n }\n if (msAbs >= s) {\n return Math.round(ms / s) + 's';\n }\n return ms + 'ms';\n}\n\n/**\n * Long format for `ms`.\n *\n * @param {Number} ms\n * @return {String}\n * @api private\n */\n\nfunction fmtLong(ms) {\n var msAbs = Math.abs(ms);\n if (msAbs >= d) {\n return plural(ms, msAbs, d, 'day');\n }\n if (msAbs >= h) {\n return plural(ms, msAbs, h, 'hour');\n }\n if (msAbs >= m) {\n return plural(ms, msAbs, m, 'minute');\n }\n if (msAbs >= s) {\n return plural(ms, msAbs, s, 'second');\n }\n return ms + ' ms';\n}\n\n/**\n * Pluralization helper.\n */\n\nfunction plural(ms, msAbs, n, name) {\n var isPlural = msAbs >= n * 1.5;\n return Math.round(ms / n) + ' ' + name + (isPlural ? [source:debug-js-6540d3a7]
- 's' : '');\n}\n", "\n/**\n * This is the common logic for both the Node.js and web browser\n * implementations of `debug()`.\n */\n\nfunction setup(env) {\n\tcreateDebug.debug = createDebug;\n\tcreateDebug.default = createDebug;\n\tcreateDebug.coerce = coerce;\n\tcreateDebug.disable = disable;\n\tcreateDebug.enable = enable;\n\tcreateDebug.enabled = enabled;\n\tcreateDebug.humanize = require('ms');\n\tcreateDebug.destroy = destroy;\n\n\tObject.keys(env).forEach(key => {\n\t\tcreateDebug[key] = env[key];\n\t});\n\n\t/**\n\t* The currently active debug mode names, and names to skip.\n\t*/\n\n\tcreateDebug.names = [];\n\tcreateDebug.skips = [];\n\n\t/**\n\t* Map of special \"%n\" handling functions, for the debug \"format\" argument.\n\t*\n\t* Valid key names are a single, lower or upper-case letter, i.e. [source:debug-js-6540d3a7]

## Questions

- How does aaaa relate to debug.js?
- How does kaak relate to debug.js?
- How does oaao relate to debug.js?

## Related Outputs

- [[outputs/source-briefs/directory-op-597d97ce|Source Brief: op]]

