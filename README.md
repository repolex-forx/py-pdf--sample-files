# Repolex Knowledge Graph of py-pdf/sample-files

RDF knowledge graph data for [py-pdf/sample-files](https://github.com/py-pdf/sample-files), parsed by [repolex](https://repolex.ai).

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
rlex download py-pdf/sample-files
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 02b8203bf416db3dbdb03438bc8278dfcb0555f3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 02b8203bf416db3dbdb03438bc8278dfcb0555f3
│           └── chunk-001.nq.gz
├── blob
│   ├── 018fcd86c8a72e63b79ff99396bccfc0f31fd812.nq.gz
│   ├── 076b9ee5ae1c1c0161adc29f483af76b2d5d91cd.nq.gz
│   ├── 0bdebd2cb84d8b68c556bc16479549070f3007bb.nq.gz
│   ├── 0e3493824ea1906e315976def3785d79f1293087.nq.gz
│   ├── 0f9091920b39cc1c00dc094862fb8c0d6d3f2580.nq.gz
│   ├── 1255a57ba8fa84526cf86d51812362de8cee2f87.nq.gz
│   ├── 14c4e90ec3783d3919b30ca61c7c74b7a9e934e3.nq.gz
│   ├── 19e42395d99f4e9c3a06fc0de46cc118eb75f5a6.nq.gz
│   ├── 1b8b316ff9b742e498164f338568073d44918484.nq.gz
│   ├── 1c0a0c1b2ff8a1484d0a3807366953c6c6624c0b.nq.gz
│   ├── 1c258aafcd1f41ca90191000f1fd3ead5b25e2a4.nq.gz
│   ├── 21d10820bf9d5400ba439151eefed70f38a3fc4a.nq.gz
│   ├── 22155e1f8547a765076e0c010b7bf2ed58efb403.nq.gz
│   ├── 2987985f7e181f27b3aebc34ef1c6d5e055180aa.nq.gz
│   ├── 29af08a39fd033da506afae2759475d4cf90f0ed.nq.gz
│   ├── 329caa93b7d323d979eb40e30c76eefa3326711f.nq.gz
│   ├── 336c1db87d6dd8ac9518ac9004a7d362212fc838.nq.gz
│   ├── 351a0d5b012960a6471b0bcb22f96499476944eb.nq.gz
│   ├── 3722461ea79685bd87ce3e2737d9acd64e01a899.nq.gz
│   ├── 3769a3d7f2cbca55d683310df735b6ccb44d5953.nq.gz
│   ├── 3cdc19d6a99caac412a89d42ccdeae4b6f177c52.nq.gz
│   ├── 45bebee9de958e18512a68bee28d3031f620f4b6.nq.gz
│   ├── 46aabc0fc4aa9125f7bea9a67d748712d4663ba1.nq.gz
│   ├── 4a16e4aebaf7b25d79956541d20a729ec86d63da.nq.gz
│   ├── 4bc457346d6d1533c4e9f82dea70b2bb6d16fee3.nq.gz
│   ├── 5686652e59ece0109c624da74edc5502ad746fbc.nq.gz
│   ├── 569656b0b8707c5c346517b5b05739c84e30bc8a.nq.gz
│   ├── 57c3ff16c66c8e302a85524f1a56d67cf780c9f1.nq.gz
│   ├── 598edd2a15341730bfbb193bccbb4cdb34e06e97.nq.gz
│   ├── 5ac777328aefeaa3b35d9334732f6a8522007ebd.nq.gz
│   ├── 5dbcae38b1a8c8983a67cb6a444afcbb4515e694.nq.gz
│   ├── 61373cd81fd1fdad9dc4d36a9c8c169d153b748d.nq.gz
│   ├── 64ce51d4bb9f53777805daef7bcc2e36ae39638d.nq.gz
│   ├── 6d9da6992f298871d1dfe184a3eeb1d8ce48a6d7.nq.gz
│   ├── 7641b4d54a5cbb58de44b9b0f9f669ccddb4f868.nq.gz
│   ├── 77c1709ad1e3a95dfd0bef34c9048a798f63cb5a.nq.gz
│   ├── 78746e19b6c444fe27445c3c10f5c0a002f82868.nq.gz
│   ├── 7961b50c9230d433f7aac1adf81f6d9856d7d931.nq.gz
│   ├── 7a8746aa6aef9ce8193e2f3484d7d97861e59f83.nq.gz
│   ├── 7d4f96c54aa155a17387e64501c50b6a0469932c.nq.gz
│   ├── 7d74f9a921b3f7fc98b815104d85eede3f888c89.nq.gz
│   ├── 81fd7a1048079b2b79ce6a5a985a715bb438e8ba.nq.gz
│   ├── 8e6964fc043ef4b97e8221d5d754e2bee68b98c4.nq.gz
│   ├── 8f6bc2028ed1167878d2444bc5c26a286e6326ed.nq.gz
│   ├── 92912cf65b2ef3e152e71dd3a3933f6b094b10e0.nq.gz
│   ├── 9aed21885ba693cc69d5e89c01c1fb8f16405e3e.nq.gz
│   ├── 9ce89af857531d294c7bbe41e91d05a8fd6846d8.nq.gz
│   ├── 9d9c171f0010fc09f4317e14714097224bfe71ed.nq.gz
│   ├── 9f55509f8cd8c03338cf6a55c19c39a699ded288.nq.gz
│   ├── a27ca26451fdbdafad3b4fad4d85ba5eb6abea0a.nq.gz
│   ├── a2d0dcab927fbeb6a040dc3f10604ed454302d48.nq.gz
│   ├── a5951d1733230ce9dac7adaf01def555c456056c.nq.gz
│   ├── a5b13392a229a7442de81fb7a2d1e4cc432ecdc5.nq.gz
│   ├── af5e7324549276d1c28493c4d9f0429271e1da2b.nq.gz
│   ├── b134c9238726fcad35c3dba9450a67d7fe5f1b8b.nq.gz
│   ├── b14328100f117e8d8a5584680d8b9a37c0a92233.nq.gz
│   ├── b30d53443bdc184232f031fe2f3755f34e00557e.nq.gz
│   ├── b457ef9f91c6aff53c0194a91cc2cab27431e2b1.nq.gz
│   ├── b557ea059d42bf0b8078b6a2bbc0b0874184c110.nq.gz
│   ├── b57e07f25e1c99df822100e7d44e04e6c1ac8fe9.nq.gz
│   ├── b5e66a8ec0f24db6908e307227d2a8aa1521832b.nq.gz
│   ├── baad89d40e532f442c9ffe22ee105b93450a2329.nq.gz
│   ├── bf642488271730babed726735c21e194d6aa0c06.nq.gz
│   ├── bf93816a19bcc12a0a618522ff8e1ca738575b5b.nq.gz
│   ├── c023b3e75c59cf1c70949429db41beaa7a1bda11.nq.gz
│   ├── c0df4afdac8a9eca82200dabe041062c712c6f93.nq.gz
│   ├── c165372b6c6ab9f3379bbebc3c3b6ff3f680dc8e.nq.gz
│   ├── c4ea523b393dafe26423a9ee21ce5bb88801d868.nq.gz
│   ├── c54c152a49d11f0486f7f698ef49244d1ec5bc8d.nq.gz
│   ├── c90018c51650242aa748f7b2b5f3c48764463fcf.nq.gz
│   ├── c9913c40dfb1f4fcf5c4e0afe6455c18d8b214f4.nq.gz
│   ├── c9938e4248b50d3a7664e702349ec6a678283128.nq.gz
│   ├── ca3ebef4db4f4bfbba00f3eabdbad50a77330f5a.nq.gz
│   ├── d40b8c7a052878aceb8d2a8b525206ddf4408dd3.nq.gz
│   ├── d58f17623612cf39ed52a4542f5ceacfa32ca887.nq.gz
│   ├── d5d4334e8742ea7f23d6f6b98a79a24ead90ee22.nq.gz
│   ├── d6a58d58b22fb35d8120203c32bf0f16ec432887.nq.gz
│   ├── de3e0c1609eea268c2d5967d713cae893b51b4eb.nq.gz
│   ├── e185abd5c34c1f04328ea2ba2359279e48310245.nq.gz
│   ├── e38695c590f5bc7465e125d8893727a30cd51131.nq.gz
│   ├── e5cbe2043b0cb89540d2c2d746dc5eecdbcc1520.nq.gz
│   ├── e6057942d5f81f0605f9df3b918f5ddff079d52a.nq.gz
│   ├── ee85aa17d1eb5dc827120f329a8f282fb582f39a.nq.gz
│   ├── ef70edc78fd831ef73980cc7ced6e8a48c8b1773.nq.gz
│   ├── f97c590e7c8263a2f3822ed4d29e4eea3dbba64c.nq.gz
│   ├── fa8ceb4eb7f98e819c443b91088e4607c2a4e527.nq.gz
│   ├── fb33f104b811b70d9d8e134ff9eac10d3258577d.nq.gz
│   ├── fb6b8471c0fa78bf854e8f63c367ba52a2f5160f.nq.gz
│   └── fd1884c8c7fd2e41f371127e618cc1ea2f511fe4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 02b8203bf416db3dbdb03438bc8278dfcb0555f3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 97 files
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

[py-pdf/sample-files](https://github.com/py-pdf/sample-files)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
