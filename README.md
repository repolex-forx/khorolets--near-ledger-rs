# Repolex Knowledge Graph of khorolets/near-ledger-rs

RDF knowledge graph data for [khorolets/near-ledger-rs](https://github.com/khorolets/near-ledger-rs), parsed by [repolex](https://repolex.ai).

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
rlex download khorolets/near-ledger-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2dc9ba9ef211a4ecc798f4fe089adf2065b37ee2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2dc9ba9ef211a4ecc798f4fe089adf2065b37ee2.nq.gz
│   └── repolex
│       └── 2dc9ba9ef211a4ecc798f4fe089adf2065b37ee2
│           └── chunk-001.nq.gz
├── blob
│   ├── 004c9ae62ab89f304e4c76fa756cc1cd6638cb46.nq.gz
│   ├── 005245e4925573c28fa1d45f2a06df5d9926c1dc.nq.gz
│   ├── 02440f225028e5b52c33f29cfdff819f307d1cbd.nq.gz
│   ├── 034e848032092eaf8ef96eac731b6ed5961987f3.nq.gz
│   ├── 0f1d7fea4eb89d5cf44bd0edb7cfba9c4b847007.nq.gz
│   ├── 151b654fa3bedd26fab907168da07a9400362a26.nq.gz
│   ├── 167a219ee29208425d9e15f24570d3a13884800b.nq.gz
│   ├── 2255e1cd0131ed03adfafe6ec1045ca588f5f291.nq.gz
│   ├── 2886a6caaa7090b832036b3c638c844bbdeac928.nq.gz
│   ├── 2bf5ad0447d3370461c6f32a0a5bc8a3177376aa.nq.gz
│   ├── 2e07a024fe9878f7903a8e3767e5835745b16a8a.nq.gz
│   ├── 2eb47c74f9e63ba6e312bed2e35048834cffaca8.nq.gz
│   ├── 35a1f37b2d244cff0c8f96e0f05df224501cb3d3.nq.gz
│   ├── 38d664add576e72fcb3bef4bd83c563628c137e3.nq.gz
│   ├── 3a645337af2184b60d29b11cf780ddf694648cd5.nq.gz
│   ├── 42904bc681d7d7d2a728fa008d256692a81ee943.nq.gz
│   ├── 43894210b458b002c55123c955a3c188c70b4fd9.nq.gz
│   ├── 52568a28891325e99e24628b4c00783a10b4f8eb.nq.gz
│   ├── 52f4972e4fc333aecc808cd7062637074b70c409.nq.gz
│   ├── 68ebee95b4baa10b056496c0bb08cdff348131e2.nq.gz
│   ├── 7e8dc3b4172b5b00914ae54a37392f5593f38973.nq.gz
│   ├── 7f99986259668edd90bff33d73e9eb941ffba1ec.nq.gz
│   ├── 84584cd1bddc25d4b08c3aa9c8000a24d3e3feed.nq.gz
│   ├── 86b5a47b81821fe966fd7284b069b7b3ca906ea6.nq.gz
│   ├── 8b94145ab7be1c587bc7eee13c1cf37d26ff8043.nq.gz
│   ├── 934ffada306eeeadc2b315b19c4236da4158b1d4.nq.gz
│   ├── 96ef6c0b944e24fc22f51f18136cd62ffd5b0b8f.nq.gz
│   ├── a26e821a0ab1d115fbfff674a41f12793da9afbc.nq.gz
│   ├── a9932c4d8dfc2e93a8710db830e9bb215fbb3e6c.nq.gz
│   ├── b54a2d2189394d1816eb47772d571f62f16bab47.nq.gz
│   ├── b7ef8ea28dc184f2cf5688a77af6e287238d1a56.nq.gz
│   ├── b863ba5a49dcc76f752d53d2ef4efeec7c18c823.nq.gz
│   ├── b956d8d07e2a0c97e060971854f4b458625a7095.nq.gz
│   ├── c77b387d4b7a104ae1ef4d8de413eecff8af299b.nq.gz
│   ├── c97b55b5158d4cd160cc839088e45d216f5f5970.nq.gz
│   ├── cab9ddf0a26a99c5ac7cd7cdb00fb06046ee915b.nq.gz
│   ├── d177a7f6e162e5a4e1440d145589d59daa40f249.nq.gz
│   ├── d6781a0cf1342cdfe815d7c91baf56cdd11f8914.nq.gz
│   ├── e7da4e3ec52808121197ce9f5c9d9d937917b300.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   └── f98f574f74bff26714775ab0342ae6c1f8eebcfc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 2dc9ba9ef211a4ecc798f4fe089adf2065b37ee2.nq.gz
├── filetree
│   └── 2dc9ba9ef211a4ecc798f4fe089adf2065b37ee2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 51 files
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

[khorolets/near-ledger-rs](https://github.com/khorolets/near-ledger-rs)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
