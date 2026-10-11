# Repolex Knowledge Graph of pytest-dev/py

RDF knowledge graph data for [pytest-dev/py](https://github.com/pytest-dev/py), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6b219734fcd8d2f6489c2f50585a435b34c029c2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6b219734fcd8d2f6489c2f50585a435b34c029c2
│           └── chunk-001.nq.gz
├── blob
│   ├── 034eba609f19b52f0cedf3d061b4b0ad96168a33.nq.gz
│   ├── 0441c3215eb11667d312bbdc2e7ba79e89119981.nq.gz
│   ├── 0710931354312054004ca4ff293de49f47c37b61.nq.gz
│   ├── 0a0e89e01fe61e51f0c758b09267bc2052e41315.nq.gz
│   ├── 0c9d0928e7ae3a6d158e6fc40c940856a9a92da6.nq.gz
│   ├── 0c9f8760bdbad4b5d0b1db69d664aee3bcbfe221.nq.gz
│   ├── 0f956b3dd253d8b003fd1fbcf923a6826b8f234f.nq.gz
│   ├── 1022de6e9126f81609c92eca97c58f04d62711e6.nq.gz
│   ├── 1246879c4daac82abe554090e60e11fc2252f33b.nq.gz
│   ├── 12581eb7afbc231e02476c125ccb9e289e6f3024.nq.gz
│   ├── 1385a0398742b72fead43bbc64faae4d315f31d4.nq.gz
│   ├── 143556a0557f7d8dd11aebd8cbf4f5a675c168c2.nq.gz
│   ├── 15fbea5047da4f77fda9fb14e34d09eb7a6fab25.nq.gz
│   ├── 168233330b65d1fc209b220f4b5e47421173b396.nq.gz
│   ├── 18e8310b5f6caaf884473ba11c4c4d3b6f78c7d3.nq.gz
│   ├── 1b9a7923f6539a80e9ec21d7e90e256eff96642d.nq.gz
│   ├── 1bb70a875d059d664c6518701963864afad86593.nq.gz
│   ├── 1c285306884bf2f0310d8b4f94a4ae2f772fe04f.nq.gz
│   ├── 1c83545884390b724079d4c0532963a2a054f9be.nq.gz
│   ├── 1c9fa75604a5cf889b7ea8b61078f9fcd027bc4a.nq.gz
│   ├── 1ddab9601ea43988162102407172f519c8cf1879.nq.gz
│   ├── 235461953530439ba661a776bb6edc47778a8a66.nq.gz
│   ├── 2364e5fef504a6b20000efc9b2d47bff1defef27.nq.gz
│   ├── 287c60d552ae7fbf62b61d98b3c6389e9f330b59.nq.gz
│   ├── 28ec628b00d43615ad6bd9f81c2fc9c203f0afb2.nq.gz
│   ├── 2e10d438866861ebaf917cd412e01c9d0c72ae9a.nq.gz
│   ├── 309c29bac5de3a15546abc5562573549d9a9b020.nq.gz
│   ├── 31ecdfb1dbc54fb41999867884dad52a07eac2ca.nq.gz
│   ├── 31fe6ead810ce0cc4f93695ad6e716f8ea1daeb7.nq.gz
│   ├── 336693bd466ccbc0d5e730b5287a820ac09299f5.nq.gz
│   ├── 350d8c4b07a1334202b72b897ba2bd466eb78534.nq.gz
│   ├── 357b8b9c729f86703d61441ccc974931b0844e4e.nq.gz
│   ├── 36efec913a3bde0aea39efbef294a8b4e8045dd4.nq.gz
│   ├── 3c7d6015cfa75e6e02b24700420a0e38db9eb2c5.nq.gz
│   ├── 442ca2395e0a15e8cddf2da9565d02b2c807faaf.nq.gz
│   ├── 444a4ca52cc37cb8d379d5f738602c70728c8908.nq.gz
│   ├── 44b4f1ddeecaa4239eda4dd435cd7c1d4eb11c93.nq.gz
│   ├── 471de408a100ee51eb5e63246d424f3b3d7749b8.nq.gz
│   ├── 47c6fdb7a1750cf5a690fa1185fb368be94a4fa1.nq.gz
│   ├── 4b453482757a106a6f3fa440b7d40f024ce46a39.nq.gz
│   ├── 4f6a561447633a751a63166c5d14960473ee0459.nq.gz
│   ├── 51f3246f8070ff46342d3d9985fa384ac4e1d9f8.nq.gz
│   ├── 56969bcb58c3322248efc7de7a04fef96074fe65.nq.gz
│   ├── 5948ef0047a55b43b752f553e424a33fe99aaf41.nq.gz
│   ├── 599dfbed755f7ddecfc2a4ae2dc376217cf31030.nq.gz
│   ├── 5bf8ba22dc6990be77df56ab4c5ea8efd1b8bab4.nq.gz
│   ├── 5bff3fe02245ce0d01a8f0011cd0c5e1f411f01f.nq.gz
│   ├── 5c706d9b6ad34dc7931c4c2eceb3b82cb395db9f.nq.gz
│   ├── 5f25c2febfd94b62b56a225fa64aea342b93937f.nq.gz
│   ├── 654f033224fbd43fe1d1602dfcab19d311201180.nq.gz
│   ├── 6589a71d09e33b946c0d7c90c5945cdfc9c8a7a0.nq.gz
│   ├── 6662f68395a0f97fd09c71a4038b4fb894e2a6c8.nq.gz
│   ├── 66adb7b0239e290e9a32b5d7447dbf48262b7cd8.nq.gz
│   ├── 6ad9eaf868b073bb33aac5ee9814e4efe2e19da1.nq.gz
│   ├── 6d255b1a9e5b63504cdcd5ca4ba47f1f18681e57.nq.gz
│   ├── 6d374e1db9b3bc689bf85bcebcdd301934dab259.nq.gz
│   ├── 6d38aa0601b31c7f4c47ff3016173426df4e1d53.nq.gz
│   ├── 6ed72aa4183e83240475c1abe5e05f8f4e5c6540.nq.gz
│   ├── 6ef20d98a2dc0e7be240c593e0303c501ecb7835.nq.gz
│   ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
│   ├── 7a6d4934970872fc9f7da7e70569d14a2033279a.nq.gz
│   ├── 7bfbef3bd4cdff6aef92c741e86b7b23fadae709.nq.gz
│   ├── 7eea770a02bdb9b84a8fed46f92652eb61e71277.nq.gz
│   ├── 7fc7b23a96c32e603f1e678d5dad272e84a0e27d.nq.gz
│   ├── 80800b2b7ae7525389131aa72419ec9b8e9cc431.nq.gz
│   ├── 8340dc44557b228e3cf6f826c2880f965096a03b.nq.gz
│   ├── 835f01f3ab9dcb656dce1e580f0d98d7b8abfe3a.nq.gz
│   ├── 83e6a1fd8d95853b6301c0f1c4560e3769fc5866.nq.gz
│   ├── 84fb5c82694067fd162a58f2a06d44ffb63a6cd9.nq.gz
│   ├── 8518290efddecdc8524c642abbd5aba76dada44c.nq.gz
│   ├── 86c714ad1aed3b1b511d90c1e1ce6cb22d662ec3.nq.gz
│   ├── 8d94a9ca649cd3139c04e4adaecd26550436f9a2.nq.gz
│   ├── 8f506d49232704ee6d67897a02d8a45efaa93221.nq.gz
│   ├── 930ebb5eac234f622b88ed360b734ed265a3b134.nq.gz
│   ├── 93c79e3b2d8f39261dc0602d85812fb28e5bb136.nq.gz
│   ├── 95e3ef07b23b554ce4d89afe7a6e7dff47eb3e8e.nq.gz
│   ├── 96859e310f4c8749b3e6bd250b338857b1047945.nq.gz
│   ├── 97be1416fec6b467822f928129a7a2e26614d1c1.nq.gz
│   ├── 98463d906d151b0b8d375f5bbcdb2c0278335108.nq.gz
│   ├── 99225047502c6a7119caf136af06228235df9fd1.nq.gz
│   ├── 9c44480a5f3df15abc27e21c9515af4d2b939165.nq.gz
│   ├── 9c5dda9ceb0ea03a6972d863f0dd05f7b09a3e3e.nq.gz
│   ├── 9dda53692d2f44a97392cae823f8163d55ad4549.nq.gz
│   ├── a0a308588e20127cc7ad0ab58356b6b677391be1.nq.gz
│   ├── a1b589e38a32041e49332e5e81c2d363dc418d68.nq.gz
│   ├── a6375de9fa29b148e8883725f1fc385228b5c596.nq.gz
│   ├── aa5beb1789f057604d8f13433951ea092848c1f4.nq.gz
│   ├── aad44f2e66913be04d85a8a44317e59e0517177e.nq.gz
│   ├── ae0d9ab7e6d7494850b8117af192f0e8445311ed.nq.gz
│   ├── aef25ec239b54ecd8050b4958638af27cea793c2.nq.gz
│   ├── b0d6e2f51531e0b6aa03b17687451a935bc1244f.nq.gz
│   ├── b5b9d8d544a25253dab87a4f9d1bc3752f38ba06.nq.gz
│   ├── b61d01c696a1ea370a3d31b5713416356c359a41.nq.gz
│   ├── b6284bec3f65439b5020702cf09fac412d1e4917.nq.gz
│   ├── b733a60d379c60aef4921d7e42a113fdc28300dc.nq.gz
│   ├── b892ce1a2a6b5a743a78fb95766c2f9868b4d70b.nq.gz
│   ├── bdd8691da03e2e3a2f768d8a8877c7d4e410f382.nq.gz
│   ├── c078a7532fbbb182a4f327c8aa58de8bbd04fa03.nq.gz
│   ├── c11308a6d2859dff898503ff5ab674b058e8ad11.nq.gz
│   ├── c148ab8cfbd0b0e0358cae8c42558ac148c3edcf.nq.gz
│   ├── c156c8bdb33c06969f40c1e8bcbe2e90dc956c44.nq.gz
│   ├── c5b4e0e79fa23b21a985639c250793385b395515.nq.gz
│   ├── c62cb85905379970a5755f54e8e32c4539a25b19.nq.gz
│   ├── c643d9983fb4db6ec3b0b85dd873268274bb24be.nq.gz
│   ├── c700b17e9877bef5b20365b5b42ef71862611cc1.nq.gz
│   ├── c7819cad7a531a772fb5e32ba1fa9256a43314ac.nq.gz
│   ├── c9fc07463a726a3138d2ebd033b50e14dc0cea32.nq.gz
│   ├── ca60fcac250542577507d6c7018e6fabbc8be117.nq.gz
│   ├── ca9a42275cff29a7f370170e7107b25a224b8953.nq.gz
│   ├── cacf2fa71a104bd3a4c25582bded149faa0c1a9f.nq.gz
│   ├── cf97db0367a8f8071d6738b3372aac06a2998b79.nq.gz
│   ├── d03f29d870814283d3f2d537d91b8a527821ee1f.nq.gz
│   ├── d377e2405d55b77ef406ddedcf0553b03389326c.nq.gz
│   ├── d65e27cb73077bbd33bc0fad0d20a89e443bef9e.nq.gz
│   ├── d69a1c39d099034638a37e36bf6262900c10ead8.nq.gz
│   ├── dad796283fe64c89f5f99f2bc72adc4a7657d238.nq.gz
│   ├── ddc89fc7be6e4b9723e9dbf0b4ffbcb64320d610.nq.gz
│   ├── de4cbf8a46f1052f54713e2b51233351e13cd13a.nq.gz
│   ├── e2221c8f9e9639243d2bce2e9230b49d413b4521.nq.gz
│   ├── e2a7f90399845009e567e98da5fc698f814aa0d8.nq.gz
│   ├── e386ea0b2718340978f4200de3a2da10140f870a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6d84fbf7a18be7271c2dcd8b0a48fcb05f1e300.nq.gz
│   ├── f15acf85132113f090b1a53cdd0bac39af924d4d.nq.gz
│   ├── f3203507fd9e366590373870b068148a1f9c6438.nq.gz
│   ├── f83a2494029687038343de2900cc2ac7e19c8747.nq.gz
│   ├── f9c71a7fbc4d04390b183812d0ebfbe9762c90ba.nq.gz
│   ├── fa936f1596d0191e0e9a8f83638368157b77792f.nq.gz
│   ├── facca77b78b5139f2b6f3918ad75233f1faf9585.nq.gz
│   ├── fad62e960d4fc0d5faf479467aaa0bbf57008a52.nq.gz
│   ├── fb588e3ab742d06a9f9e0a49fbd5268c183fe41e.nq.gz
│   ├── fc0e82665f7ee9bfd894c90687b80c97dd6d72a5.nq.gz
│   ├── ff1643799c9e015a8e351b89958ae3eb8111d668.nq.gz
│   └── ff33b8f7ca0b1c05bb0bdc546aa760c8e78757be.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6b219734fcd8d2f6489c2f50585a435b34c029c2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 142 files
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

[pytest-dev/py](https://github.com/pytest-dev/py)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
