# Repolex Knowledge Graph of aio-libs/propcache

RDF knowledge graph data for [aio-libs/propcache](https://github.com/aio-libs/propcache), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download aio-libs/propcache
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5fc239491cfa0c068ec0bdfc04a7176db9293da8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5fc239491cfa0c068ec0bdfc04a7176db9293da8
│           └── chunk-001.nq.gz
├── blob
│   ├── 057b29f38d9eb2748425eed5d252bec0b8e13ee2.nq.gz
│   ├── 093f4020f4a49faf656f01a223a6232695f8923d.nq.gz
│   ├── 0e51cb3285782c3f54a2fbd703220ee3f1f254c1.nq.gz
│   ├── 11b10ff87616463c20afca4052d6db6bd631a2ef.nq.gz
│   ├── 11c776075eacafae5c6c0d070edbffede3fd00f8.nq.gz
│   ├── 137c809ac90afca73bf06188e02f5568e43a230c.nq.gz
│   ├── 1634e04608cdd37e9f29c4341c88e0814fefaea1.nq.gz
│   ├── 1ac9bdff44c49906d508d785faeacd57deb2fcfd.nq.gz
│   ├── 1dd3d084ca29f1b4dd47cc83f72f74d8680e7759.nq.gz
│   ├── 1e52895c151c952a100eeaab524fea2ef8d68f7e.nq.gz
│   ├── 22389e6337f8f77681b61de5e45d1ae6d474d39b.nq.gz
│   ├── 23705400953a7a671c2c42dd1439aee2f62c689d.nq.gz
│   ├── 2879ab2fdd3580dd4a1f12acccefd0b9bdc09cc9.nq.gz
│   ├── 2da41fdc133759d420c8c240fa07b8b0eebca16c.nq.gz
│   ├── 353c767cc5845a264cd1a7fc0d7dc83a7f325e09.nq.gz
│   ├── 4220673733c9cb28869f323065a903bb1884844a.nq.gz
│   ├── 517bc842721c006e527f0a4cef968e993a1e1097.nq.gz
│   ├── 517ecd235823cfe9e5b0dc606460612b62498b57.nq.gz
│   ├── 520a945a077da31c5dd7f732379df58609865343.nq.gz
│   ├── 5d5e8b68ec64334dbd49ae6515f51d90b5c2092d.nq.gz
│   ├── 609da02ea570d58e6f425854464f65628c0cce97.nq.gz
│   ├── 645d7dc1478e6a942efe45d763f23868bed38b4f.nq.gz
│   ├── 671a70c797594e6ab49640ebbfe85c9814e1257a.nq.gz
│   ├── 6b82d9b3a903c62b5ba6f0faf3d2b8ddfebec08a.nq.gz
│   ├── 6bcffe7faa6b5eb33d8671929117c569ea3e2dc1.nq.gz
│   ├── 6c8eeb57a06ca60a03f8c921daba0855f339da01.nq.gz
│   ├── 716001af5dd7931e1d24c2041da228b63141a1be.nq.gz
│   ├── 7170fd598b54ab66786a2838e2ae702a64852b6a.nq.gz
│   ├── 74149750d00a2ba7e9abbc63f91f448c734abfc8.nq.gz
│   ├── 74ae436973392f8859ac010016afd2474a0540a6.nq.gz
│   ├── 7ad33e74d8c7bbc63c05980884b5705d2bfe8a94.nq.gz
│   ├── 7b7de8fcf52545c3533f4a10a51c7c63d94325bc.nq.gz
│   ├── 7f8c6f8bb219c562c225577a7741e1a6462dfd4e.nq.gz
│   ├── 8029a7678c3a9864931fa9ca11e4e1a384d8a77c.nq.gz
│   ├── 82cb77f057c170d7ad1dabad8f112596859f0198.nq.gz
│   ├── 85378aa1dfa61e6e472ac2da64fd581f607fbb5b.nq.gz
│   ├── 85beec3606aa3ca64f84f35d03f1d071a462a994.nq.gz
│   ├── 8f6c767d6dfecaf48f2205e73607afb9450d6e28.nq.gz
│   ├── 967ed83d73cbc3ab1cb10bf977e30cc27db8db69.nq.gz
│   ├── 9940dc56fb2c98a1c0eb3a6c134ad5bbf2b11851.nq.gz
│   ├── 99d53bb5c785e3c1cdc12f8d6931d45e08f8684a.nq.gz
│   ├── 9bd0e90ae3ad5f570217edcb7ebf8a0932803b8c.nq.gz
│   ├── 9bd79938e40afbe32dba5cdc9061680b42afa397.nq.gz
│   ├── a4f84f8a262205725a2976a2282ad7f2dd8d25f2.nq.gz
│   ├── a5e90b2d6dab4f7662f7c44f502e2316e8455c39.nq.gz
│   ├── b2d83435eb2619fc32770609803212bbc1f376a7.nq.gz
│   ├── b61c5dd2bbd4d063ddf438bbea1d062554249be3.nq.gz
│   ├── b6560de20a16e365689a5c4cde914a279e712f76.nq.gz
│   ├── b8298a28dec59363a7d5467227ac2bcf31420f26.nq.gz
│   ├── b94c193410a2175a7c59c602f099c591bb3ed0fd.nq.gz
│   ├── ba6047c5a72c99a0cd31d380feff634b0df4900d.nq.gz
│   ├── c5a9b29a1f0b80c1edde0501604a892f5b7292b6.nq.gz
│   ├── d2071a589b699ac509caeade4333db768dd1e06a.nq.gz
│   ├── d31ef74403c514b99e1007e92dd2571a2903532b.nq.gz
│   ├── d3c25a7b7e7841f13e0ac4b926c031b19a48244a.nq.gz
│   ├── d479652102b9855e37cbce31ac2778d8352b44d7.nq.gz
│   ├── d6409a0dd82d0c0350c0faed16e26120efb5adef.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d7a1b820acbe6591bceeec699ad6dde47d2e01ce.nq.gz
│   ├── d8ce297f5e8bc0750de8848512020f0d6ee384aa.nq.gz
│   ├── da46c88ef435855e1a33169a4b63a02dbdab0826.nq.gz
│   ├── da569dcbf331b6cd334e5a5b881beea4b8ece0ce.nq.gz
│   ├── db5b8d6378f040b4ca6619d43e36f4bfc65dacf3.nq.gz
│   ├── dc99d0108fdb310dd8ab5b889d58afae53620569.nq.gz
│   ├── dcf2c804da5e19d617a03a6c68aa128d1d1f89a0.nq.gz
│   ├── e548c5640a6512a38b1dca0bc5d8ff53a0eedd74.nq.gz
│   ├── e5c7e5da09db88a0b0ecd040ea3219632cee6d3a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7362bc59c999d843e22b297e36dc9fbd1720f9a.nq.gz
│   ├── e84719b5a196cc9b67af89ce773fc34d2333d625.nq.gz
│   ├── e8a09ddfa709d90260dead7ea38eaf3534c269aa.nq.gz
│   ├── ea13c82ce0f1ecb131a6c5061036f4cce10e96b3.nq.gz
│   ├── ee0abfc93443d35ae76a8d2b3cbd0e35da2791a3.nq.gz
│   ├── f0413b8df561a9a49d8e0190fbca30dfc1f3b309.nq.gz
│   ├── f1d0b30039acc24c610c17bc67882ab38afda349.nq.gz
│   ├── f4ad80d23a57cfcf6460c18116da98c9f1da2a92.nq.gz
│   ├── f4dcb33d362bccd9cb4e04160ecdedcc64111ee3.nq.gz
│   ├── f601b193dd278edcd18f5931043e34732d7c107c.nq.gz
│   ├── f7c1b2182685a7abeab7ded2606ece20324b5304.nq.gz
│   ├── f80acd94bb2396d1a016c47c0c1e40eccff2751e.nq.gz
│   ├── fa53b2b138df881c4c95239d0e4bede831b36ab5.nq.gz
│   └── fd4692a04112803d9cf079a4ef33d7a9123723be.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5fc239491cfa0c068ec0bdfc04a7176db9293da8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 90 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[aio-libs/propcache](https://github.com/aio-libs/propcache)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
