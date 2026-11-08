# Repolex Knowledge Graph of UKPLab/aaai2026-spare-prm

RDF knowledge graph data for [UKPLab/aaai2026-spare-prm](https://github.com/UKPLab/aaai2026-spare-prm), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/aaai2026-spare-prm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d1076e02de3a326bca2a2c3dc92c8821c078175b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d1076e02de3a326bca2a2c3dc92c8821c078175b
│           └── chunk-001.nq.gz
├── blob
│   ├── 06ea706b540a405c6843e8b6b3a475279b0ad0b3.nq.gz
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 0f1b379f310add71a7e56b4efcb175e7c63f61f4.nq.gz
│   ├── 113691ce18d7ddf18147171251a7472610247207.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 14411fd93d699377c6e17280cabaf9a39d67dbdc.nq.gz
│   ├── 1793bfe8b27563450e1c5e44e6b9bf40aeb7738f.nq.gz
│   ├── 1bd4edb1d164d3cfe2c67ced6fba639500b5ee7b.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2692c3b6f179c1f0aa81ea34a287ffc65c080798.nq.gz
│   ├── 284ae9b02fa9d90e5d66b055d697ccd3d1fe62bb.nq.gz
│   ├── 28c684f591b9bb73371aa41b87dec820762112a1.nq.gz
│   ├── 29c0afdd69e9aa35c930b086823de22637e3de47.nq.gz
│   ├── 2e846fa8ae9ff3756de10a0a717c472c0ce5e9b7.nq.gz
│   ├── 34e9788ce5a2c7bb93de7ab968b6356aa8598685.nq.gz
│   ├── 3dc429a6613bf85898a47643fe31d4439fe9d973.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 4ea5168e21815a1e7fef656ed5d06afe84e450d7.nq.gz
│   ├── 5268611b7e7b750af3e14dd774a05b8ef31a0609.nq.gz
│   ├── 55d8445dab6984cd63088384fb1799d73c083ac7.nq.gz
│   ├── 56f446877d8554f0e09756d6cbe78cb2575e565e.nq.gz
│   ├── 68eb69b23434984ce6053d307b6b6b7f709a7e7e.nq.gz
│   ├── 698e9f972a96948e15606d89ceda254e571d2692.nq.gz
│   ├── 7545cc3d9372430d2faecca33f113d542d45cf55.nq.gz
│   ├── 768e3e5580705c5fb15e1a07793474874cc4f9bc.nq.gz
│   ├── 7e544fbe36762bada1df5e58139aeff3728ee891.nq.gz
│   ├── 80f9dedb22582266a9daa4b5a74a2b7ef60f99a4.nq.gz
│   ├── 8173d21c879e3707459b60a5ac58a83b07c6783e.nq.gz
│   ├── 82d2a4cc5460c96b23e150c5f00df0db56f4be41.nq.gz
│   ├── 854fdd40a3f3dddb2c7799f19f0de9d545318762.nq.gz
│   ├── 8871abfdc9c3745a372d1b55952f4d24481e3ea0.nq.gz
│   ├── 89fe1e57f1c911d776a04dcd3ed78e4fb355126c.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8b14d41f730e3642c5986d15e956bb8af5134367.nq.gz
│   ├── 8c66fb5fc0bf19f4622cd820bfc2216f79011d86.nq.gz
│   ├── 8d1994349b6ed17f1580041fad5f1dee7d7edeac.nq.gz
│   ├── 9277dd436472333b2169afd541e1c38ad30feaac.nq.gz
│   ├── 94a0ec8b1b1e4226fa0f4bd9e853902fff7f6769.nq.gz
│   ├── 9a77daf99d2386763352c9451c198cac73f00e6f.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── a03a6654cba7b7accde1f3a6f189b4950a7f3460.nq.gz
│   ├── a290d5446d6246dd948185b747f4274ae56055e6.nq.gz
│   ├── a2f79bb138cf29c8f8209f235bd9e1d7afb56b07.nq.gz
│   ├── a70d291241eea483a3e2ca58d7c779b17cc164b8.nq.gz
│   ├── a797b968cb9e469b9c7e9ec50297454ee8a503de.nq.gz
│   ├── a943fd464f884138a9a98974bed1a5388a474b1d.nq.gz
│   ├── acaed2d19290b2009f4151dbaa18c548d84b8e0a.nq.gz
│   ├── af7c0e850b767f557ec6e09b5bba1eb58ebe237c.nq.gz
│   ├── b499e6416e88bea8f6598dec6e96a10a7555563d.nq.gz
│   ├── b8726c3222dd355ffbe52ffb7da96fd8eb43fcbb.nq.gz
│   ├── bfdbda6eea92131541f6edc706e4ea246cc409e0.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c6eef5ba31ae01092db63e7c001abb7d8782ec18.nq.gz
│   ├── c947dc4e6e88f82caf67262b8b82bb020097a4ca.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── cdae2311408d55bb43bf6a557183904c79c8fc5a.nq.gz
│   ├── d18bc2cbd6cd561bf475068d2e11874efff1ef68.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── d6f8988b42b8353243aa99e885ad545c80af0dfa.nq.gz
│   ├── d83960d7f4bd1a734b4981a4573ffa1b59edd969.nq.gz
│   ├── db288d308f136db3c237c1d0cf84ab96a6d4b3b8.nq.gz
│   ├── e533556bd0ee47b425d0f48966fb87537a65683e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7286e8fed87a8a619da19eb41907740b771278e.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── ed76b596ea088aa0fe4db07f593f97b6b0808c1d.nq.gz
│   ├── f183d3d07255ca46e292030a13bb11c93061ea63.nq.gz
│   ├── f47c06cc18baa434989aa2d46756a0b678957242.nq.gz
│   └── f7394d4d75afc922d415ae277381478c9717d283.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d1076e02de3a326bca2a2c3dc92c8821c078175b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 81 files
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

[UKPLab/aaai2026-spare-prm](https://github.com/UKPLab/aaai2026-spare-prm)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
