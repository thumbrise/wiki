# SwarmVault Share Card

> A local-first map of wiki: 361 sources compiled into 4156 graph nodes and 1466 wiki pages.

## Snapshot

- Sources: 361
- Wiki pages: 1466
- Graph nodes: 4156
- Graph edges: 16156
- Communities: 49
- First-party focus: 4155 nodes, 16091 edges, 1463 pages

## Highlights

- Top hubs: cytoscape module (931), _arrayLikeToArray (929), _arrayWithHoles (929), _arrayWithoutHoles (929), and _classCallCheck (929)
- Bridge nodes: chunk-BUSYA2B4 module, chunk-7OIKW5WK module, and vitepress___@vueuse_core module
- Surprising link: cytoscape module imports chunk-BUSYA2B4 module. it crosses communities community:cytoscape-module-14 and community:ajv-dist-2020-module-4; it spans different canonical pages; a bridge node is involved
- Surprising link: jsonc-parser module imports chunk-BUSYA2B4 module. it crosses communities community:jsonc-parser-module-26 and community:ajv-dist-2020-module-4; it spans different canonical pages; a bridge node is involved
- Surprising link: vitepress___@vue_devtools-api module imports chunk-BUSYA2B4 module. it crosses communities community:vitepress-vue-devtools-api-module-40 and community:ajv-dist-2020-module-4; it spans different canonical pages; a bridge node is involved

## Gaps To Strengthen

- 46 nodes are isolated or weakly connected — they may need additional source material.
- 28 of 49 communities have 2 or fewer nodes — the graph may be fragmented.

## Ask Next

- What sources would strengthen community 1a188f991280c3fa4fa22e8dfe41d8c5 module?
- What sources would strengthen community 1f31c89a9dcf3a7b2c81a466767f0697 module?
- What sources would strengthen community 20230222.132457_0_0_default_create_users module?
- What sources would strengthen community AppBootloader module?
- What sources would strengthen community base.dark module?

## Share Post

```text
I scanned wiki with SwarmVault: 361 sources -> 1466 wiki pages, 4156 graph nodes, 16156 edges.
Top hubs: cytoscape module, _arrayLikeToArray, and _arrayWithHoles.
Most surprising link: cytoscape module imports chunk-BUSYA2B4 module.
Everything stays local. Try: npm install -g @swarmvaultai/cli && swarmvault scan ./your-repo
```

## Reproduce

```bash
npm install -g @swarmvaultai/cli
swarmvault scan ./your-repo
swarmvault graph share --post
```
