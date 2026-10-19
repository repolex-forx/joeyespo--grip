# Repolex Knowledge Graph of joeyespo/grip

RDF knowledge graph data for [joeyespo/grip](https://github.com/joeyespo/grip), parsed by [repolex](https://repolex.ai).

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
rlex download joeyespo/grip
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a3f0ab5c8942ac15cf68f790b80c0a43b3a4c71e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a3f0ab5c8942ac15cf68f790b80c0a43b3a4c71e
│           └── chunk-001.nq.gz
├── blob
│   ├── 01aa43d7756c645e161347d3573af41a7d893087.nq.gz
│   ├── 058473730c5f58569453ecd2ab948c39d3ded119.nq.gz
│   ├── 0bc1bbf019a482e05bf5290396ae6682d1a41c6c.nq.gz
│   ├── 0df66aab1c1bf1be4993a68f08069c19f33bc134.nq.gz
│   ├── 0f72493ee4b6c963c491e32c0286ccd29b04641f.nq.gz
│   ├── 149022d1b7d093d50cc34f7fceb9a5da118cbfd4.nq.gz
│   ├── 164f4b5dd880050ff7fa681e2b136c778feb863b.nq.gz
│   ├── 1685a8c6ef19626834d143eb570f6bfc65a18df8.nq.gz
│   ├── 243ab668e68071ec4c465d60db0a283a305a409c.nq.gz
│   ├── 25593bb99b8efe6460a0beefe5a60b60d40a7765.nq.gz
│   ├── 28ef0cd00fe2376850c5e06a3b683d7b9a4e4a90.nq.gz
│   ├── 324d5954f9b61df32d59bbb38964b7ac821030bf.nq.gz
│   ├── 33b6ce0f3d7da380a4b8b0971bb754821d304bf7.nq.gz
│   ├── 3efe08c4167c2fe54c9826371c667b8aaec18264.nq.gz
│   ├── 41cbd3f1fc9de1ffbc64566421c279ea1731e36f.nq.gz
│   ├── 4941f851bcc43587fa1dc5263573091c2ce278a2.nq.gz
│   ├── 632ae016d2d5e26e1ee95939ae191ff67d7bfab7.nq.gz
│   ├── 69e7b2a4044aab1229fb72eee8379df10f82e4cf.nq.gz
│   ├── 6cde6623f208463980f18eb6345e23bdb801bf7a.nq.gz
│   ├── 6f317f04532061791940e439af3365d2207cbd67.nq.gz
│   ├── 7504202d1e096bb183827e652134f8758a93fed0.nq.gz
│   ├── 7d8ba08deb68dfe2e7c2f265b920cd131f4396f0.nq.gz
│   ├── 8206a9c7c1f06ee4c853fb8c22c439280fbddd69.nq.gz
│   ├── 8859622f9a1bca75bf7d47b196b067b6ab63ddd6.nq.gz
│   ├── 8d0e0e9ed2d8e968d2347e0e89850ca1a51f51af.nq.gz
│   ├── 91e1dab46f7322fa965c63967d77e9191ae3c315.nq.gz
│   ├── 977e22814cb0f3db1b896017652e84eebfddd4be.nq.gz
│   ├── 9b7ac9de762cf1ffd07566a2cff0854222d11eb0.nq.gz
│   ├── a0ca7b60bec80c944a3dcd9c3e884b38037e9d7c.nq.gz
│   ├── a281321801ae93cb575dbd9d36903a6853ee72cb.nq.gz
│   ├── aefdda40580fbba0f25299ba018a367cda2ec512.nq.gz
│   ├── af466a638f10be591633db4b07f664eb20ac899c.nq.gz
│   ├── af58fdc3dec2e064514ca03f48bdbc6e01665128.nq.gz
│   ├── b4c7a989ae645fe4dcab1dea34cfffa8487b28c4.nq.gz
│   ├── be556d221872a3a718ce821aef49fcfcc05dbc18.nq.gz
│   ├── bfb5e352de05c6e40e82b331553130b08c83b07f.nq.gz
│   ├── c4b5342122f37a42322aadbe50ea4b31e9d6c7e9.nq.gz
│   ├── cb378a597438c062c0b3a885aafe18fcc28f6492.nq.gz
│   ├── d182551595f6f3612367d8bd0e193b41de473299.nq.gz
│   ├── d825e83aaf3949eb4d55ddc6fd70dfd85abb7977.nq.gz
│   ├── d923b2c2c05c2fe3c5be0028deb80883f9c7d7b4.nq.gz
│   ├── e65c4282e88f70e51d67ef3f5f2c154b9c1eee06.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f01cb85481454a2a888e32ce53f152752ec6eccc.nq.gz
│   ├── f713d3c4281bbf6de47c6acc4b247f1eab8565ea.nq.gz
│   ├── fc2028a71393143dcfa70d2c7c695917b74ffc18.nq.gz
│   └── ff0dda18470bed62d7090c8dd6762dba05e098c7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a3f0ab5c8942ac15cf68f790b80c0a43b3a4c71e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[joeyespo/grip](https://github.com/joeyespo/grip)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
