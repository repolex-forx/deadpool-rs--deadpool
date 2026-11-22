# Repolex Knowledge Graph of deadpool-rs/deadpool

RDF knowledge graph data for [deadpool-rs/deadpool](https://github.com/deadpool-rs/deadpool), parsed by [repolex](https://repolex.ai).

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
rlex download deadpool-rs/deadpool
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 89f6ae48ae7e80dff697900868789120e01785d3
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 89f6ae48ae7e80dff697900868789120e01785d3.nq.gz
│   └── repolex
│       └── 89f6ae48ae7e80dff697900868789120e01785d3
│           └── chunk-001.nq.gz
├── blob
│   ├── 04fc5398d844cd41fa78a8adb6d89e41157c4d97.nq.gz
│   ├── 077166d743511553fc6c3a3e52175250ec072362.nq.gz
│   ├── 08bf657eed1aea5a854e77a9265e039589bd87ba.nq.gz
│   ├── 0b216f06d53629c9715f85c02511377e74d0c6b4.nq.gz
│   ├── 0b865c52350288c25e7981984fcd3a3d42be6dd1.nq.gz
│   ├── 0c93c70868b7113407777df7dee350880349ec6a.nq.gz
│   ├── 104b12f790abb2eb070699649b2b36097ba8cee9.nq.gz
│   ├── 10500883d3b6a4cbd470560866f997f257f29e88.nq.gz
│   ├── 11b0bf0e9c330aa7090c51c9fd781eecfe683ac2.nq.gz
│   ├── 11f1a79d661a00c4d4df0735b6cf4bf7152731a9.nq.gz
│   ├── 134e018c98db6a9d1321bfea3bcb7b4540835e1d.nq.gz
│   ├── 1c8b5730232c7804071b22a135f61ce911841039.nq.gz
│   ├── 21e9096e1d8893c6011bf387aa4ff126c1da9e8d.nq.gz
│   ├── 2344a49b888f63a493ea18d3a5ec9c178920a968.nq.gz
│   ├── 247d39b5fdb0b36ebe03df459f1c6196f230c55e.nq.gz
│   ├── 276162c06526caf0bdb40c16baca4e4cdd506a3a.nq.gz
│   ├── 29ffe4ee7bfc1f71a74e8b737b537c736649c2d9.nq.gz
│   ├── 2a8d2b3fd00894ef2d5c764d9c1905c791bfe9bb.nq.gz
│   ├── 2cb78849648ff402429841132f0ca56271388855.nq.gz
│   ├── 2d77808469510e29d8061eab75a52934b7302ab7.nq.gz
│   ├── 2f69aa8ea7cb7d7fd35addccbe2435363ff86af5.nq.gz
│   ├── 326ae45b7de7c0037cf9da80aaaf5d0f3e248486.nq.gz
│   ├── 3420ae785426faee0c8440ab086bb279a95210cd.nq.gz
│   ├── 354f783d82f00dacb93cb832c6eddebd7e96a9a3.nq.gz
│   ├── 3c35ade76aaecc43a2aa4393cc511d6d8e68c3a6.nq.gz
│   ├── 3d0f394904d571fe8d1d03257262fde44e913ef4.nq.gz
│   ├── 3f133f7be6194e6e143f49e436b0325b48cc0d93.nq.gz
│   ├── 432cc59e4a6b17ab8ca2422383013161451bb974.nq.gz
│   ├── 47023e19f47a9b9181262dcef66f0b793eb3d154.nq.gz
│   ├── 477dfd4ce0551f26fa94e1e80425188453ade4d9.nq.gz
│   ├── 47a24df7cc9721184bd623871020c52f69cefd53.nq.gz
│   ├── 4948a45ab0e091caf5173dcfb49c68396e238e9d.nq.gz
│   ├── 4e517c16c84e7c93b47bed976cf3a420049a5ea9.nq.gz
│   ├── 4e88b9485640f43e1c5c91bb13e58ee34ca6105b.nq.gz
│   ├── 4fc8c205ca53c043e3506e27044b7f8f0ed15696.nq.gz
│   ├── 5322db9169aec6046708900ec7ace2cbbe70c08d.nq.gz
│   ├── 56c36e5dc241c9c14f1acccc7af35c936475d75f.nq.gz
│   ├── 5889b23cfe00bc046c78628f3edfb8bffdf253ff.nq.gz
│   ├── 5cf9b71eea9c727b931f3f9ac3e637ee13d5b361.nq.gz
│   ├── 63a57d6f83edf0586761f96070054a4e9250f5fc.nq.gz
│   ├── 675d230e20e8481caf0bd6a3e314c0e15c9cf060.nq.gz
│   ├── 68ca595f51fa1b8d45d6853336e6126a981ef815.nq.gz
│   ├── 693699042b1a8ccf697636d3cd34b200f3a8278b.nq.gz
│   ├── 69781ecd17101870c343803a6fc25b76209d64ae.nq.gz
│   ├── 6b01608533ed264112136f7dc0678461c0e9ce6f.nq.gz
│   ├── 6b740b5c2feb7326674beec314aab000e63220be.nq.gz
│   ├── 6b992a83901dc60705bba01f3fbd869c17250f05.nq.gz
│   ├── 6bda82d1983aaead14fcd3786f20b11aa1be75a1.nq.gz
│   ├── 6cc3c8ae3524caa30c9f0d935eb09b8fa6b5f5c2.nq.gz
│   ├── 6d157f75574e866da0f57a506fb6e979bbc7f1d7.nq.gz
│   ├── 6f9d541fcfa96d8676133de8ef08943b265b89d8.nq.gz
│   ├── 707b8666c8b464eb74b43180d2d2efc1d2958d96.nq.gz
│   ├── 737bba96e6796e3d72238dcfd3ca292ade3aab15.nq.gz
│   ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
│   ├── 7b5379e90677e1fd2e7bee673348b698ed6c9bbb.nq.gz
│   ├── 7caac13a4984c226e21bed07e22094084c7d6c21.nq.gz
│   ├── 7e64b42aad92cae07fcea2775560b73f3a884c98.nq.gz
│   ├── 7f6ea4f3f606c92cdbb2278aa15fc48d3e361ae1.nq.gz
│   ├── 81f44544da6b775e39ec24c74d31bddd005e2f41.nq.gz
│   ├── 834833daeb662c6a9165795a7ebf6b3bf88f5754.nq.gz
│   ├── 83f3b6e8099ffd0ad3d3001eff48efd32d017cd8.nq.gz
│   ├── 84ed2954e8fd9d03e3aaf25e8d0e0392fca1bfb8.nq.gz
│   ├── 8553a2cce3a6d52f0b22bd9729f6c09ad0260bc4.nq.gz
│   ├── 869349bb6fc769687a19e4a52e63b06b07f5a958.nq.gz
│   ├── 8d2acdd64beb355bfabc11e5ea87ee1ae00580e0.nq.gz
│   ├── 8d768a2eaedae9f97e8fba3c14b8c5c6b51a4117.nq.gz
│   ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
│   ├── 98372e789b024f39299ab555afdf67f27413f78b.nq.gz
│   ├── 98ae85125af76d19b2c25845de66f28c1eb95353.nq.gz
│   ├── 9ad618d0c3ce4fd292c65451e5aca7f6dc5a8e17.nq.gz
│   ├── 9e7d5b6265ed45cae62008dfd8798be26d49acce.nq.gz
│   ├── 9ef736ba2941622a99daebf587ae33109bb1496a.nq.gz
│   ├── a0662012b9c91a8e9b37a1cfc4acd5e5d96174e3.nq.gz
│   ├── a575a6dafbbb6011ce67e6e46103d93604e09b4c.nq.gz
│   ├── a5ad4b94e8fdb4b2d6de625c8b01e4f536941c7e.nq.gz
│   ├── a6e09899545efa396831bc81f76ea6faa3a442e4.nq.gz
│   ├── a7a69a5187cca40889cc73434a932b504b7c3dd5.nq.gz
│   ├── a80204868a0f5cec28cfda5b0a926f14b5600572.nq.gz
│   ├── aaa60cce64b29be68c99f4196d438384abefa35c.nq.gz
│   ├── abb2ea6aad4b1d6ef1ae513731a9000bebb53e6c.nq.gz
│   ├── abe36ab4ada453ca93a8a2795f11e8a2dbbe75e7.nq.gz
│   ├── adf86132f9247d944b4f4b3ba81106f6bb3ba09e.nq.gz
│   ├── aed33e4f3e742b4f224f5d7ecb38aedd2e8fa72d.nq.gz
│   ├── af6be1e91739d08db8ec33a35dfc4e75a183fcc0.nq.gz
│   ├── b393d92e0bdaeabee66730e37e5c9b570ec3c68b.nq.gz
│   ├── b422632950a5984d17842b793c25146e9f2c7690.nq.gz
│   ├── b683e8bead875a975a8812a1da230be73d2216b9.nq.gz
│   ├── bb16d4a44bcafe71a368d4359fc0afcd9ae63732.nq.gz
│   ├── bcf8344e8c97bc2c735446835f585a8c9187c103.nq.gz
│   ├── bd430ecbc59d3850a84d9051a97cbed4f461f0d4.nq.gz
│   ├── c4d31f0b10d77cf744c70434df83c814a79019df.nq.gz
│   ├── c55b107c7b9972fad6a14bc0c5b8f007901a4585.nq.gz
│   ├── c5b90ca1629baa4153bfd1343d34437b49a95f3c.nq.gz
│   ├── c6ed2e8ae0b90d50bea851492da7ced2054ecd8b.nq.gz
│   ├── c9e44b99a21c575f0cf713d9dae818b33e200132.nq.gz
│   ├── cce62515580535cd7514e6e86134fe94f474b305.nq.gz
│   ├── cd88ea5956d61677408b8ee1f2083c3755fd88f1.nq.gz
│   ├── d45b91edd5261df0677bdc2dd2673ff38ad092be.nq.gz
│   ├── d6c39f3ebb2aa37aecaa64bbbe788b921c503666.nq.gz
│   ├── d8e85e1ea5d8716e0f316f0eaea98f8ae25ec29c.nq.gz
│   ├── db53229411da301037e0fc144c1bcbf155ce2f4c.nq.gz
│   ├── dba5eb77574fe37c14c81afb0fcdf01eb10e778b.nq.gz
│   ├── dc91ac02b435330e3ce80cdd9a12dc196871d598.nq.gz
│   ├── e05221da8ed59580228bf5611a9d45c302bc2dde.nq.gz
│   ├── e176fdf1c5c4b383595c83ebee511fba352dcff2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e87f12c86e9514c17fb009762e1cdee84a0ad9a5.nq.gz
│   ├── e9f1804d75109791af5ff38a2955ef038e949c1d.nq.gz
│   ├── eae9ec97b8efb9b749487a49433425ea086cc91a.nq.gz
│   ├── f618f90434410e5f503585b8299253a366e00e47.nq.gz
│   ├── fc41fd6f42f9c7c9a6cb74605f027cb92d888ce2.nq.gz
│   ├── fcd5e10d33d2dfa0596dfdf8604f67f2b5d93a53.nq.gz
│   └── ff038a293a2cd9689055d55baddf43babe61040a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 89f6ae48ae7e80dff697900868789120e01785d3.nq.gz
├── filetree
│   └── 89f6ae48ae7e80dff697900868789120e01785d3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 123 files
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

[deadpool-rs/deadpool](https://github.com/deadpool-rs/deadpool)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
