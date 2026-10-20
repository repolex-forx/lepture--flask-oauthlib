# Repolex Knowledge Graph of lepture/flask-oauthlib

RDF knowledge graph data for [lepture/flask-oauthlib](https://github.com/lepture/flask-oauthlib), parsed by [repolex](https://repolex.ai).

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
rlex download lepture/flask-oauthlib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 260a1d5e608ea6149e4f9e89c592eb1519943098
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 260a1d5e608ea6149e4f9e89c592eb1519943098
│           └── chunk-001.nq.gz
├── blob
│   ├── 018c131e975975b2f88769d1a9ff6029ba0df756.nq.gz
│   ├── 02a8d266c33f7db23095f23ee73a9421a3616b64.nq.gz
│   ├── 039c3aa9c7375dc3f44de1689caad87e805eb784.nq.gz
│   ├── 0694ace188c75dd6fe699244919ff7224e87fe44.nq.gz
│   ├── 090cd428ba15d491abd6c2d4a92b7c9c00acad38.nq.gz
│   ├── 09b67e88e60d31381e0ce0ac8304afcdf348f709.nq.gz
│   ├── 0a0fbdb49bbd0af98470c01c6c8db553b0f960ca.nq.gz
│   ├── 1352480c0399231614fb9a89b353853b875cc10f.nq.gz
│   ├── 13df6e33d1e722587140b9671351f9297ebbbafd.nq.gz
│   ├── 14a57af2b20b0de8abb3494b6d5678211a79de85.nq.gz
│   ├── 15e5e0003fb40b2240d0126f1cd4d4e17f13713b.nq.gz
│   ├── 16efa24d9be785e21da575d89a4311aaddb779e2.nq.gz
│   ├── 17f8e667daf92da75907ba1aa7064b361c3d7612.nq.gz
│   ├── 1aabf05508780493a5ee4771bacf5aa32f345c1b.nq.gz
│   ├── 1b0aee04288c841a39872cb08404e7727999e81d.nq.gz
│   ├── 1bd9011e2f0a31dfce9b5ad488bf6085c160bc07.nq.gz
│   ├── 1c26a8dd38bdb5688e1fcf4952ad570e017d4948.nq.gz
│   ├── 1cddd10c27f6c6379fda78e70b293f0834b67d52.nq.gz
│   ├── 23fe0c1e4ad878f1953a6da942ea315cdf9b46aa.nq.gz
│   ├── 257f9e3e3a725c8f9a7d711ea4770246e80ac64b.nq.gz
│   ├── 2c603613182a26ece7df224687e5047dcfe1a2e8.nq.gz
│   ├── 2fee2d22b18a91ae640fc34a5974c29ead9e32bf.nq.gz
│   ├── 317a50be4b61d8aa2fac9c4de02aef7e1344b37c.nq.gz
│   ├── 39cbb0bb66abeb30aaa9b7be7df72347dd73e2a9.nq.gz
│   ├── 3d6a6349935b678ae0ad3b03229e2b0a2f27b7b8.nq.gz
│   ├── 3da329dac44ee084ca5fdd7ef982d2aa02b2cba7.nq.gz
│   ├── 3e57597cd819e4fa9b6677f8f4496d5fc8f6c7ea.nq.gz
│   ├── 3f0934b179b44dd4bb773b6e1f20f846f28233c4.nq.gz
│   ├── 3fbef08901211081fd1f7cb958414847be5d5726.nq.gz
│   ├── 462818222b531ec0c2569ba4cac22bef11bacc88.nq.gz
│   ├── 4b777b4430dcbd3daf2326ea063c4e02dca552ae.nq.gz
│   ├── 4c2041370226fd95b3bcadda9568870da7ef5f8f.nq.gz
│   ├── 59946a7c2f1422d39a4384aa088b4abbf8544332.nq.gz
│   ├── 5c88f320e1a16ff819a692f3246de4dc22b4cfd9.nq.gz
│   ├── 5c8b9bfba6f679edcea8c10f71cd5bff8564beb0.nq.gz
│   ├── 63f8bde0e15309299f0c699c1061c2703e9e98aa.nq.gz
│   ├── 65f75e69ca49766e08628e5bf3eae85e1866c5d5.nq.gz
│   ├── 67c7552295cc58a618ddbe7a99015933af248069.nq.gz
│   ├── 6a1416b12e69a7af52a78ce5b6f9efb752fb33c9.nq.gz
│   ├── 6adb62e1955e64c28ab61372da3a7da746d5d632.nq.gz
│   ├── 715dc93e32a0b1a77a75bdc314b0f18c0ecf87d2.nq.gz
│   ├── 71af73b49db0deaac14ed815896d630ba555d8b7.nq.gz
│   ├── 746b6b9f80c71049f2a4eb84ff72d5d1bf77c62c.nq.gz
│   ├── 75bc88d452335b4cbed57a0057322e976a6f79f9.nq.gz
│   ├── 785fcef15ccef0f6486107cfeaa52dc75f0a7150.nq.gz
│   ├── 79487284c043e31677621fc3e79ac1555ae43c8c.nq.gz
│   ├── 79ceac56b94e61a29df0d147b7399722e3729d09.nq.gz
│   ├── 7d3b761a259148ca4951070c7386f62e955a6dc4.nq.gz
│   ├── 81d6489370a861a43350275a7dab2c985a4d2653.nq.gz
│   ├── 8b0469e66286b81980ccaa4aad40921e6bfd0feb.nq.gz
│   ├── 8c74b31d0e9f1bd28999d6027d134ec3978b6e55.nq.gz
│   ├── 917ed1e99e158dabcb73e83ba3457c59ce17841e.nq.gz
│   ├── a36404df751e680913877b5299d1047a33b9b7db.nq.gz
│   ├── a4c8404c30b483db6f02e72099a70151098ef0e5.nq.gz
│   ├── a8d492e380d5e735c0727407cd3063f02a0aea24.nq.gz
│   ├── af9f4eacd22128e618f08c50434a4e01b80f35bf.nq.gz
│   ├── b0929cb8fae83a69bb49ecf5e273b3954eba7e15.nq.gz
│   ├── b4497f46eb1bd77b2515b28cff00766ac4d5bfb0.nq.gz
│   ├── b792fabbfcf236bfb27e8dfd066ec5b58dd6a085.nq.gz
│   ├── b7e6822102bbc782ef44e6b5ab800f1bb21a627e.nq.gz
│   ├── c14bbb3a64bdda5a90ea99bfd4e029b55bfee966.nq.gz
│   ├── c3cb8f5addaafd8691912ba127d8941e208aaef5.nq.gz
│   ├── c9c17627e2334adadaff7d062e8322efb4a5b8a0.nq.gz
│   ├── ce7954ab12080e1cfb0583669a58267bea008a44.nq.gz
│   ├── d247215b9b7377c5f1dd62ebac75458112333a0e.nq.gz
│   ├── d3e1ffce7fab21f841629b4e1a71793254f0af84.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── de89839662789e437060f83feac27cdf5d53c82b.nq.gz
│   ├── e36582992f4949f7e39abe2aea5ae86394609b32.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7d8ab269a5ee1df23396acc48de13d0c7d7d16e.nq.gz
│   ├── ec517e199c04c4227a64e8c0699fb1124b81eefd.nq.gz
│   ├── ed7d0fe0e3c7953478259dd32e31809328047725.nq.gz
│   ├── ee7b360fb845732a423498d754cb013d47adc7d6.nq.gz
│   ├── f1c7842f2a60a95024cc3c232630931394d03713.nq.gz
│   ├── f464d862605ef1ed030e132fee1f9410ac5326cb.nq.gz
│   ├── f6381d3e92942ccdfd7d8a78a67be84cd913af81.nq.gz
│   └── f7688983ac65be66c602b0821dfaef68ecef30df.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 260a1d5e608ea6149e4f9e89c592eb1519943098.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 85 files
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

[lepture/flask-oauthlib](https://github.com/lepture/flask-oauthlib)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
