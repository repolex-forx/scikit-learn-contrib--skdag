# Repolex Knowledge Graph of scikit-learn-contrib/skdag

RDF knowledge graph data for [scikit-learn-contrib/skdag](https://github.com/scikit-learn-contrib/skdag), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-learn-contrib/skdag
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a04f75f58b3126b98d304a5a03b49e3861108eff
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a04f75f58b3126b98d304a5a03b49e3861108eff
│           └── chunk-001.nq.gz
├── blob
│   ├── 12557a19f849b341bf158098f88bd5832e896f32.nq.gz
│   ├── 1411d92c8d658819e71f16cbe47f8a29bda6b1f8.nq.gz
│   ├── 17ff6422588e90ad7e3ecd2c489eadf3614cacd8.nq.gz
│   ├── 1b82b5f69fe29f55707cbb88594a1ba61c73b94e.nq.gz
│   ├── 1cf01bccadbe2c6c585449014da18c52695aedc2.nq.gz
│   ├── 21a28560021db05b13cd8f45850c3bf41a3583ec.nq.gz
│   ├── 277d732fface8e0296f22ac74bf0ede1cbc240c0.nq.gz
│   ├── 28344c34e4994eacbff999542b070f118b3c9aed.nq.gz
│   ├── 29aec1e6e08330ffa623da49d8a42fec51413fbd.nq.gz
│   ├── 364460032770ab32e7714018aa2d49401e7a07c8.nq.gz
│   ├── 3a908468997c5f267c5605013d8513359c8d4636.nq.gz
│   ├── 4800682e67d5d98a08b595d9261fdf32f506158c.nq.gz
│   ├── 48188572839f0c2e5e016a53b6eebe04ac69b5ca.nq.gz
│   ├── 484f57a17c4f6e54ceeb7b42349294b6e27b76e6.nq.gz
│   ├── 49ae19c6c1342d7e9bcd5889fb762d653335d4cf.nq.gz
│   ├── 4f78e5421fa2610e54e34b93203ade4756bdb01e.nq.gz
│   ├── 508376e44f20332a0a471b40ddf8c2484a99b015.nq.gz
│   ├── 582ac219d9c7d0cda7d8317dbb13a2be7f680063.nq.gz
│   ├── 6526deb4287620e5f1c9db3644c0e32520cd2983.nq.gz
│   ├── 6663c0bf41bd10d6937499191cc0832107c88212.nq.gz
│   ├── 704a7d0197711d2f6ac7bb4f350ceba726b6d21e.nq.gz
│   ├── 70a620ef8e635cb7735f01a0a8971ad6ed5e6c8e.nq.gz
│   ├── 76ba9d8c44e4504fd4dff4f54818a7cf0c85f712.nq.gz
│   ├── 79c1e1984b87bc0b5c10ae5cba2cc1a94a1051c3.nq.gz
│   ├── 7d3252d02e6cb7ce6f6b1d77e28ac52e01ae3da5.nq.gz
│   ├── 954d937abd028bb4ad56d1b153f99ab08a4bb060.nq.gz
│   ├── 9b672338d35e4fe3250060866278a47df4c72f38.nq.gz
│   ├── 9d863dd97ac2adc716170be67588f0c105bb2d5b.nq.gz
│   ├── a5d244b84164bf4bd7c8db775c84bcaec6e179cc.nq.gz
│   ├── a6d7588b83e17bf4f3ee8bdbc44e2c6fa5927f4c.nq.gz
│   ├── a7609c4e05f8ca1952114a4324e12c973de2eee5.nq.gz
│   ├── a96e39bcc02b592e246fc7e9e7dbe0a898a69dee.nq.gz
│   ├── af796eda31242cd4c1675c8d316dd2e2949b8cef.nq.gz
│   ├── b56fdccea22b45ffd831842b0e30e11335c0718e.nq.gz
│   ├── ba1c9e9919573bfe516f89e0b6fafd6927530d8f.nq.gz
│   ├── be5128db068fc5118e467e04900bdaa25798f496.nq.gz
│   ├── c494aac3c0f6c10c0250ea93608a125bc8e3d605.nq.gz
│   ├── c5f3b34086ec20a51938fe1621b8c3ab8726a4b6.nq.gz
│   ├── ca78214d3a0c2cf5d3831e39bbc3a3e76df170e0.nq.gz
│   ├── ce4cf6bb1cf61e53c00b7b22e183401008cfb7a0.nq.gz
│   ├── d383e164bbfb435c9396f4fcc84fd5e86364d91e.nq.gz
│   ├── d679f978d5e672a77d50a843ad6d9420b4a84705.nq.gz
│   ├── d87f56998175b91b21e7ee53ea806064fe0f78e1.nq.gz
│   ├── e47716e7517415d72e56e21ec3fd5289ba1fb4c7.nq.gz
│   ├── e5c14cbc4ed08084139274a1a2f8b3ac02ba3555.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f0390c0104003b2c2842dccf81350fdde096afce.nq.gz
│   ├── f0c44e3de6a1dcc7f3748e75f2bd59e16ca2d2c8.nq.gz
│   ├── f51f56d4cfb9c3830b1fda5ed0c757e0bdb68ce7.nq.gz
│   ├── f6569ebc5b0475a97227010dce467f8993426422.nq.gz
│   ├── fe03331887fbb70fcfcdbdc8aabedcf9446d9987.nq.gz
│   └── feebc58d4cce78af331e03565733275c86896482.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a04f75f58b3126b98d304a5a03b49e3861108eff.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[scikit-learn-contrib/skdag](https://github.com/scikit-learn-contrib/skdag)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
