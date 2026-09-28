# Repolex Knowledge Graph of asimov-modules/asimov-imap-module

RDF knowledge graph data for [asimov-modules/asimov-imap-module](https://github.com/asimov-modules/asimov-imap-module), parsed by [repolex](https://repolex.ai).

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
rlex download asimov-modules/asimov-imap-module
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 25bb6dd5de984e56a81bff0e364dec365dd93383
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 25bb6dd5de984e56a81bff0e364dec365dd93383.nq.gz
│   └── repolex
│       └── 25bb6dd5de984e56a81bff0e364dec365dd93383
│           └── chunk-001.nq.gz
├── blob
│   ├── 0387631d46974d5af25ce2c77511a552518909bf.nq.gz
│   ├── 10b359dd05935c73efb064470f9ecda90f6d28aa.nq.gz
│   ├── 11808190d4b90b20fe074a2dad43af6c0c1427ee.nq.gz
│   ├── 17753627ebe6735a9eaba1c36a4f74c71ffc7542.nq.gz
│   ├── 1783fefc6625f2c3d5ddbd87f7534ba99b922620.nq.gz
│   ├── 18750a4f02ba265dfea2776d2cd1e54036649aae.nq.gz
│   ├── 20deb6ea3f91de7e8ea31e58181aa4939fd28aac.nq.gz
│   ├── 28bb31319fbda38283f76b7e656d15e19b519c78.nq.gz
│   ├── 36cd4ff3c21899f3c0b4e9f29efae6c4983f93f0.nq.gz
│   ├── 49d0573a5395f5689416b05404ddbc1dc2655a41.nq.gz
│   ├── 537d824718aae5db4b07ca33783d7d187ba6f3c2.nq.gz
│   ├── 580e027776ce95da32528f7ea960e88f38a5049b.nq.gz
│   ├── 61c617dd77c7c31d590240ef246b7bc3cd6935ac.nq.gz
│   ├── 643fdd07e69ca95acef1c16f186290536b7a76a5.nq.gz
│   ├── 6b23d61018f43b840f8d2ff3b45a1c02d76df38d.nq.gz
│   ├── 6ca183a01abe091d523279e0790ab4cc68422bbd.nq.gz
│   ├── 722e43b1b0deaa398422fed2355971c918151a52.nq.gz
│   ├── 75e3b65f99b29f48ab230e3eab3de8d0b7a9229f.nq.gz
│   ├── 789607812db5f8490c9473be4f581ec1115cae15.nq.gz
│   ├── 8de1b19ddb89e4a60a3b094aaa4378460e40f056.nq.gz
│   ├── 927244c5da2a5269bb422a74b804d701ad19d835.nq.gz
│   ├── 942fda5538bca437ad5d4e3449a53b187dfdca97.nq.gz
│   ├── 9fe50de16e59d550235aa6d7d15ee12ddf054414.nq.gz
│   ├── a8d1c907b4ab3b701eda6b3e97de8b7948f0308b.nq.gz
│   ├── acb1e9c5035fe02577d4e68d748ebca16961566e.nq.gz
│   ├── af9908b08f4b33c32a0080af73f53bc0fa0cdce4.nq.gz
│   ├── b16eeb3432ea59f3a5f70c704c35218d3e6c6ac7.nq.gz
│   ├── b38a53b0b70f6c40614e1e8ec1f1691e45e9d7e7.nq.gz
│   ├── b8f5df2aa8a56c73585ea90c7e0158b8a4a89c00.nq.gz
│   ├── c9df863ca6369e1d654b9b5e8a2111004ed01c01.nq.gz
│   ├── cf42f6893594e2f8be2b722de51123d65e4d61c4.nq.gz
│   ├── d29550c6ef0c7be8f3156827894e4165361f31f7.nq.gz
│   ├── e37695d9a20f959923eb987f8fb87bfa25963f1a.nq.gz
│   ├── e3e57a8ce4ccbf74759a6df8fa4a3980ff1c9209.nq.gz
│   ├── e6dc70dff5fc4180cd9c4ebfe8340f407174a86c.nq.gz
│   ├── e9418ec33e9513a0d337fde41a079087c4e911f8.nq.gz
│   ├── ee4d9362508d63f9e156fe9ee1b11ebc1a3e86d6.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   ├── f0e202e2e6ffffad4769acc66a67f096af467e54.nq.gz
│   ├── fbef3bce3ea751fe84438ecb5b46ee04ff2ae49c.nq.gz
│   ├── fcc50a4d264a594920c78ba5383781ddef3b7240.nq.gz
│   └── fcda3c4e516df6c46384dc4ebc89f00cdc28d0f2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 25bb6dd5de984e56a81bff0e364dec365dd93383.nq.gz
├── filetree
│   └── 25bb6dd5de984e56a81bff0e364dec365dd93383.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 52 files
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

[asimov-modules/asimov-imap-module](https://github.com/asimov-modules/asimov-imap-module)

---
*Parsed on 2026-09-28 by [repolex](https://repolex.ai)*
