# Repolex Knowledge Graph of swc-project/pkgs

RDF knowledge graph data for [swc-project/pkgs](https://github.com/swc-project/pkgs), parsed by [repolex](https://repolex.ai).

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
rlex download swc-project/pkgs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ab957ff226ac4695477435c6782355058c0d7b80
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ab957ff226ac4695477435c6782355058c0d7b80.nq.gz
│   └── repolex
│       └── ab957ff226ac4695477435c6782355058c0d7b80
│           └── chunk-001.nq.gz
├── blob
│   ├── 05c71dc1a5fb41abfd6a032e906fc56a2733b026.nq.gz
│   ├── 0cc479384ff880a8d90f0e1d3b581d3a792eeb9b.nq.gz
│   ├── 147213b6baf274860290d56bb952c7058e6458c5.nq.gz
│   ├── 1fbd5aa2b6f855b66cba4ca7a83f43408af51ee5.nq.gz
│   ├── 2200a117d8e830ebe3c88af6d4100374fda98d75.nq.gz
│   ├── 221fdfea3a9b9d0936b12e8ab5f64dedf4b4d186.nq.gz
│   ├── 24390c8277d6fda2531b406624ee6ea01dbb3b92.nq.gz
│   ├── 25fab71867a599a7d07d9995f6f55b6b89a7d318.nq.gz
│   ├── 27d99c8e5887a7c74626cbcf79654c1b9b5fc69b.nq.gz
│   ├── 28afed1afc06a5f249d1668e3435423cd6e5d988.nq.gz
│   ├── 2aae5b6098255ac120d15b4f2b61406f062d4546.nq.gz
│   ├── 2acbe489bcdd235f0712ec992a8f2bd840dfad25.nq.gz
│   ├── 2acd0456d05e1b0c874ead3733eff9734ea081ea.nq.gz
│   ├── 2cad8742b719b35b13a6fda8ed7a722055939bbd.nq.gz
│   ├── 31c75b5e75e23e9db491a99bd29693289fabd9fb.nq.gz
│   ├── 38ddac1f6e34380a6adcc4ecb21a2ae23a4f4620.nq.gz
│   ├── 39ce5289737b2e45a5a861396711b2aca49aecbe.nq.gz
│   ├── 4021bf81e675a9651a588c4fd8cac299af73a498.nq.gz
│   ├── 441cff2d85fd7b0cc7457640931aca8eafa10a99.nq.gz
│   ├── 44a52dccd5427f052205afacd903b96cf9d5cf4d.nq.gz
│   ├── 4a2bbdf52ba467fd43aa3e683dadab6e001279ac.nq.gz
│   ├── 4a302207549a8c314a43e41058ee2bbe8ef96c7c.nq.gz
│   ├── 4b5f8c4cf48997799a8c5c65ca8368f47d23c8d4.nq.gz
│   ├── 521e230193a34631c4b7858ee120158affef119f.nq.gz
│   ├── 525846c50dcf991746e0f026eaaff6829a1b6418.nq.gz
│   ├── 572db6f78249b7a4bc7074e1d31d0f645376a574.nq.gz
│   ├── 65fc6b82b72001b6daf8eadc4472e07ed9f38998.nq.gz
│   ├── 668485fc9db6cf13e9336af195693ba1657495bb.nq.gz
│   ├── 69c6acfac88f4451cbb8ba509f6d2785c425d34a.nq.gz
│   ├── 6a75957949c4325bb53d7cb43d67f99199679824.nq.gz
│   ├── 6ae4d14f8d484e49788f4bd5436eef7914c32af1.nq.gz
│   ├── 7c3340d600776a26895232afeb17508c190e1e37.nq.gz
│   ├── 7dd0191469c83876587f61a2c902255ea1ae570b.nq.gz
│   ├── 8f4e604091a7aba5182ec6326b58b6cc07939fc7.nq.gz
│   ├── 9ee6286ae464d8d5261548280ac324642f6f6a95.nq.gz
│   ├── a3b5b5e3075fc363a2070727a18392fc7bf0b648.nq.gz
│   ├── a8a18775ed3b2d06b36f50ace98aaf6cc6622f22.nq.gz
│   ├── a8ce5a889471bc272dff54ca70fdf0b8fa01dead.nq.gz
│   ├── aa9bbafc3a9288e64f236816f88324a420a42e26.nq.gz
│   ├── ab72bf5c119015daadc0e707a8af65e36b8d7cc5.nq.gz
│   ├── ad06ed5a3a24b3bc43c5a233acbe3d9523bc943f.nq.gz
│   ├── adca8fb36ec7a4d9097981ecb5827824bd70dbbb.nq.gz
│   ├── b8a0c6a3b18e2e46b2ebef01da6caea3c97cd1d1.nq.gz
│   ├── bb122278c846c5e341f12a6cd05ae1e4ff7be341.nq.gz
│   ├── bd5535a6035b27160c376132126242ab9dedc4de.nq.gz
│   ├── be496826ac6be06079265dc68f6015bd2798aaa9.nq.gz
│   ├── bf7cdebcb5cb7b1dea4b36db81bc160408c22246.nq.gz
│   ├── c0dded835360d6c2ec392fd298094a786a9365c9.nq.gz
│   ├── c2f3076ad6cbea655b70ce7b2137f2ca2693a0c9.nq.gz
│   ├── c3ed38698d4c6066e4e815f58e79e68f28f0ef68.nq.gz
│   ├── c6c53b844409f3334219fac23fcc95ec3d3b7477.nq.gz
│   ├── c87923672111b3f9ef8e6b0c99136bb512dd6b1d.nq.gz
│   ├── ca342b8193534077ef60f3aa23fcba74dcd5d8e7.nq.gz
│   ├── cc4c24c4fc20d4fc255304a4bfd80a6bbf6c7476.nq.gz
│   ├── ce9bbbbb9474c3732c9a8325ff425b64e6a39157.nq.gz
│   ├── cf586c7c0da1fae38e3ebb310a90f33a4434d048.nq.gz
│   ├── d0b8496337acfa7f5a0f18bf9d68e134c60a77e6.nq.gz
│   ├── d24fdfc601b9ffe8ccc3fca5d3b873109dc56c4a.nq.gz
│   ├── d2d17f9d897a6887a147644f902a8e16d3952138.nq.gz
│   ├── d3ec21af0931943f5dd440e64a0fd586659f713f.nq.gz
│   ├── d9bf34087a80dffd1409560353f8a2ab1d804644.nq.gz
│   ├── e8203239c058aac1a10ce9cd00ce9daeacc4b703.nq.gz
│   ├── eba42b1c4c4e144c25465f2cdbf804d9ef3323e9.nq.gz
│   ├── ed9d02821db2cdf1444dc094dc250da75faa89c8.nq.gz
│   ├── f536d057bc39c4b24802f913e7f69916dccaac4a.nq.gz
│   ├── f9d90981568eebfe96f68ead61c577a53b08a441.nq.gz
│   ├── fa4fdca9ac86c6b070d50eb729d18670d645a4ce.nq.gz
│   ├── fcf53fa5200989a6a000685b926b043555e8440c.nq.gz
│   ├── fd08096cc53f6afa635e44ba3dd346df634caacf.nq.gz
│   ├── fd97d5b984f352e62b3271850dd7816c72ff1e5b.nq.gz
│   ├── ff3fdb42c080f237121c304873334a197cbb79f8.nq.gz
│   └── fff1caa370337b6aef42e73090ca73edeabf8dce.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── ab957ff226ac4695477435c6782355058c0d7b80.nq.gz
├── filetree
│   └── ab957ff226ac4695477435c6782355058c0d7b80.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 82 files
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

[swc-project/pkgs](https://github.com/swc-project/pkgs)

---
*Parsed on 2026-11-21 by [repolex](https://repolex.ai)*
