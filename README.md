# Repolex Knowledge Graph of napari/midi-app-controller

RDF knowledge graph data for [napari/midi-app-controller](https://github.com/napari/midi-app-controller), parsed by [repolex](https://repolex.ai).

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
rlex download napari/midi-app-controller
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2f650d9cd424590308f6b59c740e39a1f4f80a39
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2f650d9cd424590308f6b59c740e39a1f4f80a39
│           └── chunk-001.nq.gz
├── blob
│   ├── 0155706309f39aba4bbbaa6a874f6d63489b9c4b.nq.gz
│   ├── 053a8b8a79df978b3106e17e529b1dcdf4054337.nq.gz
│   ├── 0c2fe62fcb892d5b5980245a3bba39516fd3c2b6.nq.gz
│   ├── 0d2b72b4ce440812bf73fd6d17f29289ede19c09.nq.gz
│   ├── 171a3715ca84423814e3a7b1de74214f6cf64a7c.nq.gz
│   ├── 1a9deb07aca01c9580d3c358f9cfc754a88591ef.nq.gz
│   ├── 1bb6ea69ecf5972099d3e80bd45b37b012452473.nq.gz
│   ├── 1c1bf543c346739d029a4e2f96885ed99de2104c.nq.gz
│   ├── 2343772fa74948e33ebd3f57ef43d5ac89cfe7d0.nq.gz
│   ├── 30ee2fd3b7d313c34b6334b522905288873ddf09.nq.gz
│   ├── 368f54bdfdb9b5c25da1e5dd31598a949672a298.nq.gz
│   ├── 46ca9cae72c164a8d1aed3e82f584986f15bcd69.nq.gz
│   ├── 4974670bed518b8107309b0408a93a510722a35e.nq.gz
│   ├── 49db01fe23458c10ebb906ce6360663fac1a0195.nq.gz
│   ├── 4afd8a01a6e5d774eb2453b3d914bb5ca8eb1186.nq.gz
│   ├── 4df97df8ae5954342ad5d93851d617125c84f79d.nq.gz
│   ├── 4eb1a11a7e39b2232790f1ebae6bc4350f9fafc0.nq.gz
│   ├── 524e8c5de9aedce72ff5bb92686b81389ba73d3b.nq.gz
│   ├── 57187be54794b0923e57c270da02d45b03e64610.nq.gz
│   ├── 59f04104c7237ead150b83cccf99662158279a4c.nq.gz
│   ├── 5e9a970bab60adaa684c94da897102dbfa19fb96.nq.gz
│   ├── 67ff8349cbf35bc160788ed460d5c6ec4725f558.nq.gz
│   ├── 69a18ffbccb3205a6b53fdcf824edcab06371dc7.nq.gz
│   ├── 6a50c24182a717a33aaac5446c174b432f57b9d7.nq.gz
│   ├── 6e8c7112d39eeb5acaa9d7abc4d62e9544765ad6.nq.gz
│   ├── 6f99dd5ae36264b90977365fea371e2ae5aed84c.nq.gz
│   ├── 72b826f7ee2174b7ae793ef05c61eeeba36cf603.nq.gz
│   ├── 72d83e4fbbd853007a1b981ad332bc575c5d6d8f.nq.gz
│   ├── 77c235433d2d89d2b139e66360bfe60aec13bbd8.nq.gz
│   ├── 78091ac0f8476e6561d9503d0a4378b2247a1383.nq.gz
│   ├── 7c765536ef6a5dfb4546dc05025aaa5f8a1c71a8.nq.gz
│   ├── 8c95e99ff10282a77af2cf72d96bf5b7892cb698.nq.gz
│   ├── 8e9c98a5c52b0025e5c8b4a29d94abb4b5149383.nq.gz
│   ├── 920c8e7f92aea62124b98c5fdbf1ee0a041fe0d4.nq.gz
│   ├── a2aec3cb84d328ca469f3e08469636adea2d29bd.nq.gz
│   ├── aef584f5399d1a7b663b55966de89e2154ec78ed.nq.gz
│   ├── b46f0ad1ff1d839c5c9273c3cdcb1c09cd43f13b.nq.gz
│   ├── bf1ce6f6907661d951a5e497b805d7b455a9669f.nq.gz
│   ├── c91cf5630c7d1e18ecfc88df8efe331634cfad92.nq.gz
│   ├── ca44497dfc342e94e559eee2c2eeb5922a7328c5.nq.gz
│   ├── cb1540e991624a3503a10a9a7c49937bd94c04c0.nq.gz
│   ├── ce0ab3d67ae4fa0a984c532830ddecb15e5b0995.nq.gz
│   ├── cf158f936074e1d5aa00576d76ae4b152ef71e73.nq.gz
│   ├── d813fa3726cdd95385b999955939aec12430f2be.nq.gz
│   ├── dd62149d6b942c2737172f3771eee9d366e6ee5c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7dcf7e4ec968fa411e3518188df796b9c9d3bd4.nq.gz
│   ├── ec85eb0d4f2f2f76d0777dccd72bc3e9c10f14b9.nq.gz
│   ├── ef622c1ed6ac7fdcc004f4d66afe39f20effc906.nq.gz
│   ├── ef659a9c986ce872578e1f639fa898a884ac5fe8.nq.gz
│   ├── f380066c08c1a21f11db188aa535e34c45527b57.nq.gz
│   ├── f451a9cce1bac7ba7fe8be68ba01fc437320ed5e.nq.gz
│   └── f67a284ff76a2f3668da9409ddc07d9d053e2d06.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2f650d9cd424590308f6b59c740e39a1f4f80a39.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[napari/midi-app-controller](https://github.com/napari/midi-app-controller)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
