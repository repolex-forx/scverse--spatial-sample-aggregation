# Repolex Knowledge Graph of scverse/spatial-sample-aggregation

RDF knowledge graph data for [scverse/spatial-sample-aggregation](https://github.com/scverse/spatial-sample-aggregation), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/spatial-sample-aggregation
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5fff32e623ace3770e2543120ee0ded5775e8f42
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5fff32e623ace3770e2543120ee0ded5775e8f42
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 04f1edcb76df13dc584511fe9580f0541ff2aa4b.nq.gz
│   ├── 0fbffefe3ab9d6fda9b0584a38e74c7ce0c0c279.nq.gz
│   ├── 19b0ac0b3fcc5348f5c64bbe028f298f6fb18b95.nq.gz
│   ├── 2175c16e6e0911f429ad3757f600d73dadf6ad73.nq.gz
│   ├── 31e10b3ea0930e8a0a9f6cbab9a2bc94459b578d.nq.gz
│   ├── 36d1874618b1d0099c4d192c8a90500d69bcc723.nq.gz
│   ├── 37bbee1bdc38cc98d134252f3b0d8571f930bff3.nq.gz
│   ├── 3af0cfcb4ba183065bec9523af5d9f9421dbf4d3.nq.gz
│   ├── 3b573618b1895d7b6fc95fc49eb5cb3925390768.nq.gz
│   ├── 4a9b2127e778b62f000b72ba5549eafe44e492e5.nq.gz
│   ├── 50d29702f42944ccb52aa17d8ee3d819fbf0d021.nq.gz
│   ├── 541543637cdade38c9c1c2099b278d4bd3b795c0.nq.gz
│   ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
│   ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
│   ├── 69897c3b379c4b6c25f7b7a4e62f653a37399557.nq.gz
│   ├── 76549aea89c38cbf9ed2c5f398b47e42d6dd4edd.nq.gz
│   ├── 7b4a0cf87d73bbe25166dd0330e358876a2f0756.nq.gz
│   ├── 81d87a9c9357a852ce9dbe4fb6f97c066d7603a7.nq.gz
│   ├── 841bd7c207030e263bef011117c231dfc7a7cb65.nq.gz
│   ├── 8b5f2982378a0098af77952f562b7b2f80862fff.nq.gz
│   ├── 9bcc29c5e7177407bcb7047fc073fda575773d7b.nq.gz
│   ├── 9ea2893cdc0c1c301f1395f0afec2d5323990345.nq.gz
│   ├── 9f5bed44ec106502c159a68e71e8308abddeb4f9.nq.gz
│   ├── a19466931072c78287c48ad45273cbdc4e55282d.nq.gz
│   ├── a5a20e68c8a77dd7eacbadf8336638dfbe0be957.nq.gz
│   ├── a7eabac63da57483cb1605e370e8421b3348d9f5.nq.gz
│   ├── aeeda3c374aab9d623229039f0d5601f79c8c4ae.nq.gz
│   ├── b57447d743f19dd94e5893439a23f374c3f76d81.nq.gz
│   ├── b8c8d47fa0a99101c675af913b08144664399119.nq.gz
│   ├── bfa2cf000e7714b0f0a9ff485808bd3c93a99e58.nq.gz
│   ├── bffc124ad07830b6320790ac4e2baf0f1b4480e3.nq.gz
│   ├── c1856287e0eba5452fcc7543339fa20231c0483f.nq.gz
│   ├── caaeb4f73220343cf55564c4b747c6434c231fd8.nq.gz
│   ├── d0c0e2917651ab1d38f689317e32f463c392c3d2.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d9e79ba64848091a9bccd21dc241c61c669dad7f.nq.gz
│   ├── e034b91f7a78ad40b1349f103363131423841d61.nq.gz
│   ├── e3521a9c71d52bcddc9549d96ae1d432115411e4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f3505433f5da041de0e6e97545c091c6c716b268.nq.gz
│   └── f50c02971609a35183bda650438ffebf726bf2a9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5fff32e623ace3770e2543120ee0ded5775e8f42.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 49 files
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

[scverse/spatial-sample-aggregation](https://github.com/scverse/spatial-sample-aggregation)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
