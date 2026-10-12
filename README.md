# Repolex Knowledge Graph of flask-restful/flask-restful

RDF knowledge graph data for [flask-restful/flask-restful](https://github.com/flask-restful/flask-restful), parsed by [repolex](https://repolex.ai).

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
rlex download flask-restful/flask-restful
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 88cce53a8cd65830bf1815185a42ba24e5db78c6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 88cce53a8cd65830bf1815185a42ba24e5db78c6
│           └── chunk-001.nq.gz
├── blob
│   ├── 01990763cdccc68092eb7f203699471aa134e47c.nq.gz
│   ├── 0364a5fbd99bcc92a39a7b1d94640ca46d6b0872.nq.gz
│   ├── 086a5a00ec2454d40a834289a9c03a596bf3e0b5.nq.gz
│   ├── 1a22d3d21dbf031a41d695a8d74011faeba18d00.nq.gz
│   ├── 1b1e6aa8d0a325bed777cbb5e4fc74d746e5e4fb.nq.gz
│   ├── 1b36c85e05eb0e37459db30a046fbf2f7ce0b499.nq.gz
│   ├── 1b6cb13ba08588db5a7d0ac98fe942a7b95176de.nq.gz
│   ├── 1d75e40429cf4c3f8d110c6ad00a9e21a5813980.nq.gz
│   ├── 1fd1a5b522e022899c472bcf46ff65a82caf7b88.nq.gz
│   ├── 2be683657f37b73c6f401ea123ed3545c6d63439.nq.gz
│   ├── 3134a61cf166b4b046e9059b088ae512dd23faee.nq.gz
│   ├── 3337f908168a466854a3aab0568cf1c3196b96e3.nq.gz
│   ├── 33f47449c11d241e36c83d7f95d819bbe56e2c8f.nq.gz
│   ├── 405e5a90c17b189d9be961b8c0c330317db53c0c.nq.gz
│   ├── 44ed5afd5a68df96a75c457b939ff7f5177dd842.nq.gz
│   ├── 4546e4d78b68af4aff4e6686ecde2b0c0e294021.nq.gz
│   ├── 46915c8b81dbea9e5fcc9a75de7c189bd954abc1.nq.gz
│   ├── 4897e779535d7b6382f5484b9624b0534a773b5d.nq.gz
│   ├── 4a2ac86363d10a135c49ea74e36f551a1b3e8da1.nq.gz
│   ├── 4a63675db0a9bda8b310f043448fb031b6c98a46.nq.gz
│   ├── 523a014e8d62b42762e7b07dd3efd366fff788f6.nq.gz
│   ├── 542b462515db7875ea5813c33181870ae06edff7.nq.gz
│   ├── 573484bb270d3ebaaeecb5355b1d23cd24ab20af.nq.gz
│   ├── 582ee5a3f855dcce6e67fce255c4a5ec1a38d26a.nq.gz
│   ├── 5dc461ec3d0e4c57ac3bdf881a1c00f037efeb53.nq.gz
│   ├── 66b6e4c2f3b55b25afd9716f9d3c5afb47b15d4e.nq.gz
│   ├── 677ab4e6ad19fa149c7c0606ece2d0dba15df5cb.nq.gz
│   ├── 6c0621dd0743bb315416a20ab15404a8a1333075.nq.gz
│   ├── 6cb9e9b54a02920e3ba238ed6f4a37bafbe67091.nq.gz
│   ├── 6cd555cfecff830af77aa96aae3a08772fcc5db2.nq.gz
│   ├── 70a54060c1815074505f825a5a1ec89a663931a6.nq.gz
│   ├── 7810d9252723b7c7ad16ac44e4bb01a9b7571b85.nq.gz
│   ├── 783b73de3d3ba473109c12edbf7ab415e20dc802.nq.gz
│   ├── 7d3b16d096476d027c9d0851b3c8bd1e0e30ce58.nq.gz
│   ├── 814a805985fed5eded5162a9e35590eb6c34c7bf.nq.gz
│   ├── 85fdc2e4d2e0ab3d994fe90ef055d0fcc1645cf6.nq.gz
│   ├── 89d72eaa25d326edbc9c6507503e36b9cec0b9bd.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8daab7ee6efe3b6f3c2a2594b711e7a9026eb5e2.nq.gz
│   ├── 8f267b9d21d0ea3643b6d426eb016518000f19fd.nq.gz
│   ├── 926e118e9cf846c52268a1cd58eb86f6b180dcac.nq.gz
│   ├── 972e289af91be2a3171e97cd59512b10b761e778.nq.gz
│   ├── 9bb30991461ad7d26ef50b44b6df8da06d3076a6.nq.gz
│   ├── a4236ac27a3bcb5940cd231b94885973ed828fc3.nq.gz
│   ├── ac0c23e9c15d9c95f29a552456797fe87a9cf051.nq.gz
│   ├── acd4a3a32632bd3f0b9130f4ebca5bb67fd120f5.nq.gz
│   ├── af62397e917ab79f6a96d90fff7f88d9de9d8385.nq.gz
│   ├── b30c4d84ce743f6be1b250068f818a27277692c8.nq.gz
│   ├── b3292bdff8ed5429eedd7f409839979d408beb6a.nq.gz
│   ├── b6a90319ed2c63e2e95f3a3cd0d06048b30bca4d.nq.gz
│   ├── bbcfb5c55fec38ab5bfb3a930e3b1ca9a82c94cb.nq.gz
│   ├── c01361133a30dde006b93fc1c2c6701dc5fb4c8b.nq.gz
│   ├── c12205fdf7ecb8427f9428a2f11a5b24514698f0.nq.gz
│   ├── c6a4f77ab2cfdb9385f8f0d1a9af3f822a80db41.nq.gz
│   ├── c998ba35ebf8ba2ed2cd3672b9f68ba3aae63586.nq.gz
│   ├── cb0487efddc70e27e17578e8eed94939b26e57af.nq.gz
│   ├── cc84719c2d858bd9c2c2d24f0255aa0fc874ee8b.nq.gz
│   ├── ccbe8b749e35897d15cfddaf817915ca036dc3e5.nq.gz
│   ├── df73a9a16908d6c6f60d8a0bfa4e0d9c6965d52f.nq.gz
│   ├── e8221ba9d95e2fdb3f5a6403f3540011f7f81334.nq.gz
│   └── f12b6175c125c2cec72a5a05cb0bc6f25a9d7523.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 88cce53a8cd65830bf1815185a42ba24e5db78c6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
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

[flask-restful/flask-restful](https://github.com/flask-restful/flask-restful)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
