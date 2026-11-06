# Repolex Knowledge Graph of google-deepmind/dqn_zoo

RDF knowledge graph data for [google-deepmind/dqn_zoo](https://github.com/google-deepmind/dqn_zoo), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/dqn_zoo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 45061f4bbbcfa87d11bbba3cfc2305a650a41c26
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 45061f4bbbcfa87d11bbba3cfc2305a650a41c26
│           └── chunk-001.nq.gz
├── blob
│   ├── 008352dd410a88cdc671ee0f141d7f4d11695212.nq.gz
│   ├── 022484db8f79693a41eaf910a7551df06b2f98d0.nq.gz
│   ├── 069df1c80bf6bb68082c290f156c4e5a4d8a1758.nq.gz
│   ├── 082f94bf4551e7fd85bcad8b65b92b4a3c4d045c.nq.gz
│   ├── 0cf25673e09f925687f957dd26a25df349567dbb.nq.gz
│   ├── 1221ab5238529685d919ea1c1f05108d703343da.nq.gz
│   ├── 213912e9440b7804f4f47a2b127e159e340bfaa0.nq.gz
│   ├── 222c5c51676546a428781163a3816f157da2db30.nq.gz
│   ├── 24acb12ab0c706fdf4f88c6aa774a977b30b1eb7.nq.gz
│   ├── 25c0ba4cab22f0ce9224845f3002595aa2908835.nq.gz
│   ├── 310e19f0828888de1eb05bb25dcdc54a68ff4b97.nq.gz
│   ├── 31972ea56d13aa7eb095643814411a0bf4d07c84.nq.gz
│   ├── 35852138a108e748f786539bc194011f64042d61.nq.gz
│   ├── 4530f16fd15f5323fbae7e0ce80439d2c58810eb.nq.gz
│   ├── 4a776bc9638ae8c6e219abe6f5d3835bc67f002b.nq.gz
│   ├── 513f00e41d8b40533e9746461a6c41121863f52b.nq.gz
│   ├── 5a0d8c454a47be0d681a8bc1e6bea1660cedd9b4.nq.gz
│   ├── 6b376b25eae61f45c305589a4fcfa648d610ced7.nq.gz
│   ├── 6b66550f14d3b9151a0239e527ba1f013ffbe82e.nq.gz
│   ├── 70a403aced1c1e6fdafb4c1ae732e32048fe1ac8.nq.gz
│   ├── 741c1a06ee3a4a2fec1bcd4f0596d0ede3d27829.nq.gz
│   ├── 758f7daa14c5eae52b08922c275161d1d55c7dd2.nq.gz
│   ├── 7774de3f935d9d1058d9d6a45a959f74ef1f0b1c.nq.gz
│   ├── 81456ce936c77eb9585ae49f867560337619d96d.nq.gz
│   ├── 81956edc1301455e63c27da34d98c629d8c1b084.nq.gz
│   ├── a361a0dd7f341d696a99f3962da95d6ff29d6bb2.nq.gz
│   ├── a5fdf036cbc050a89254daa26d76dac921bb7769.nq.gz
│   ├── ac91c91121ed3be85c15e2cd729701d1969d1099.nq.gz
│   ├── b6319a521a39babcba4d78b3411aab75d49db6a7.nq.gz
│   ├── b7a7b7a15fdb099bd222f5a22c088b7ae84d0b8f.nq.gz
│   ├── bd732e2cb2feb3894d6f2229fe07f32fe31314cf.nq.gz
│   ├── c585e6873cb75f901aebc6c8a4c31669e62e6239.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d9032f877af0eb0b3618892664922472d1791d67.nq.gz
│   ├── deeb3b73ae6bc0da59c27f17952e151cdd507870.nq.gz
│   ├── e21775cef6164e7100bc014d8338caaed52b739b.nq.gz
│   ├── ea28898aca52167949a43f2d86e89ad0df917010.nq.gz
│   ├── eccb6a8c773b9055204d92da37af3efc9e378ac7.nq.gz
│   ├── eef29599e38fc6ba5a9123f8a9eae0aa186e470a.nq.gz
│   ├── f79cd0e90984cb1af5c61378740f7a345b7e7634.nq.gz
│   ├── f8a3c05bd1cb41ba84c5c0d26054d98f0aec6e19.nq.gz
│   ├── fd5a48226e58f9f6d210b49394a8ae4292433254.nq.gz
│   ├── fdf07d2050d210829a94450d72e1dcd4d823253c.nq.gz
│   └── ffa5978543e6a4c7eaf17d45c7346e3a68eb9233.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 45061f4bbbcfa87d11bbba3cfc2305a650a41c26.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[google-deepmind/dqn_zoo](https://github.com/google-deepmind/dqn_zoo)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
