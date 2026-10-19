# Repolex Knowledge Graph of dry-python/stories

RDF knowledge graph data for [dry-python/stories](https://github.com/dry-python/stories), parsed by [repolex](https://repolex.ai).

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
rlex download dry-python/stories
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0754046098c3f7468ef5e05a48bcf46d44f871ce
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0754046098c3f7468ef5e05a48bcf46d44f871ce
│           └── chunk-001.nq.gz
├── blob
│   ├── 07cde86a81e9cb4f46aa525270eaa88963cad5ce.nq.gz
│   ├── 0826f31f415f55c710cb328c1a1836f25c4a517e.nq.gz
│   ├── 0e627061114a26d46f7a6312463e1cbc4f7b0b10.nq.gz
│   ├── 161ea27257ad8c6c44ea72379d6b9ba10129bda2.nq.gz
│   ├── 19a83d17c3164a474287765d6e4745ca6bd90b23.nq.gz
│   ├── 1c184a986d5e14fc4161d7bd6588f2622d73aea5.nq.gz
│   ├── 1c97e1759815267ee2c8ec0a2d6e147edd17a10c.nq.gz
│   ├── 1ea2dd31927ac604fac7f1e3e0b9a1f8b6cd0ef2.nq.gz
│   ├── 20d804d7415f7f707756d2087e3682a2cc69cdbc.nq.gz
│   ├── 237feba555f68b7a5d7e9e5e98990b804a135383.nq.gz
│   ├── 239c0e6923212712a96f1e8f4717e54690d3abe4.nq.gz
│   ├── 269f90abc49159b31f60495f6c2fb82035fef5d8.nq.gz
│   ├── 2ec3491824598ae5f71ce26ce13ac9c19b0e057d.nq.gz
│   ├── 302703cf243839b4db6fa72f9a96e00be5c6860c.nq.gz
│   ├── 33d54367ea230867889f9762e75457bc5d3d4ad5.nq.gz
│   ├── 362e85b1aed7658a50ab793dd9c21842a8b9e0b1.nq.gz
│   ├── 37bd579da0721180292dd90a7f8f197cb808e419.nq.gz
│   ├── 386d18eb00fe863f3307ebb958091f85d9990789.nq.gz
│   ├── 3e0bd18230bf45318b18d9bb32fad9caf2f5c18d.nq.gz
│   ├── 3e8c64c7b6980bcdeb98a5fc06fa7e3e6ff01ac6.nq.gz
│   ├── 44a057db01cbeebcbb434dc8ee981fd164de2568.nq.gz
│   ├── 46e67198c0c09c72146f2f4a6fcc87f5b016c4a0.nq.gz
│   ├── 47040209eb3b29d93a2ea94460d3d2d658da24f7.nq.gz
│   ├── 4b3b6ae973a037d9979ae1b63e2398eed9735dc5.nq.gz
│   ├── 5073c20db108a39520634648cb94f2926bfe4af9.nq.gz
│   ├── 51eb9a91bc1c842a49a138e56c243d898b83e903.nq.gz
│   ├── 54f56861a56f76f35385a1ff831dd346665ee614.nq.gz
│   ├── 578be8197b8c1ee009ca46b065320cb99a332a36.nq.gz
│   ├── 5bea05244fc61c19ebf32f89d7b212384733df6f.nq.gz
│   ├── 5fcde7a3550003dab418226b8a6cf606e9c039a5.nq.gz
│   ├── 6314f0dba29a9955e7ea7bfdfb828d8b7b421374.nq.gz
│   ├── 65eaf8141c69de39dc54be174a86cf421f74f071.nq.gz
│   ├── 6b7a6a692e547246dc3b233c06a2f1b9cacc2df4.nq.gz
│   ├── 6e888b67f08d56e28d71063d767fc997ede43f71.nq.gz
│   ├── 6fc30a06833b04bb9bb54630b5c66c63dfd4ee4d.nq.gz
│   ├── 78ca456c8911f04b29c8757c635bc42e8efc8a98.nq.gz
│   ├── 7a37e0bfd38c6cdd1245050ad2ff2485a0e05795.nq.gz
│   ├── 7c7352e01a0985de8e3412105938e9a468f4fed6.nq.gz
│   ├── 7d65920f1987f4c2c8f99ca863659e40e30ebda2.nq.gz
│   ├── 8397d333eb76295d90b4e4820084c858a739ea03.nq.gz
│   ├── 8e8826baa5b6dc5f95b0fe9e0a1eafc3d3b2415f.nq.gz
│   ├── 92c9798d8444e489de15edb0220dcc641030dba9.nq.gz
│   ├── 93c87275f1c60ad147388964fdcf9308a14cf760.nq.gz
│   ├── 9406dc93b6a57ea11f3f48511cc1079e7d98d528.nq.gz
│   ├── 9e1692702bedcdb77c765fe98d6b9c39024edc04.nq.gz
│   ├── 9fb23c5be68b9cb83a4a13dbf83bbddd96830526.nq.gz
│   ├── a0c3abdf5472da962f422155087b9b68e61b5170.nq.gz
│   ├── a0f026c2c1e28093d4a29ede131d55e7bb5b6933.nq.gz
│   ├── a184951cfb92c4287553c6be68dea2a6be86e7e9.nq.gz
│   ├── a705bf44b0d8a8e60dae2b1f93e50e09defa29df.nq.gz
│   ├── ac279d951ad25de8e3a8998370a5892b57b725f7.nq.gz
│   ├── b0e20ba93e3503106361584ffd8369691e588246.nq.gz
│   ├── b6f1f03d4ed4b4873aae926e9fe855ef46526515.nq.gz
│   ├── b8e1cff93cae565a0529934c9f93f0e8470e749c.nq.gz
│   ├── b90369e48f242a26ce7c789216fc288f05e0a7a4.nq.gz
│   ├── b94547b88b356d7954093df104f28dbb8cd6b041.nq.gz
│   ├── bee7a0b7cd45c6f01ab51d5738818cf337fa1324.nq.gz
│   ├── c7c53196e3d4126880735601cc9a197fb925b0a6.nq.gz
│   ├── c8baa026b4854dd7b58676695717c033c6a74501.nq.gz
│   ├── cb7670c5a8ec4d964053c704a86ae8429839dbd5.nq.gz
│   ├── cc55376f6cc651f898e165485706514e1f78a0ed.nq.gz
│   ├── d3d4c6e3c143a67de932a257dc3bdda262432d41.nq.gz
│   ├── ddbf0275e6437eb81ebeb05b10d3641cb5736a31.nq.gz
│   ├── e10b57a9a5eb6c793f6f47bfe0e4206b782f1665.nq.gz
│   ├── e3009834f1312b446bf2697bb035aa4520ef2e39.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e892330381ea9e9c1fd7409b174b66c146fdc448.nq.gz
│   ├── e8c6813c534f1bf887f021e247d5d9715f7fe13e.nq.gz
│   ├── e9da49265fcf8a2c4d0ca1fd53f8e689aecb8fad.nq.gz
│   ├── eafbdd76d8eedca069d18d5e58ce4db9c569180d.nq.gz
│   ├── eece86073c15a144b8d26de70d489e50451d83dd.nq.gz
│   ├── f89e72994034a944806a38d96af3fdcff678814a.nq.gz
│   └── fad42970e9d3a4a33cfe1043ce9af74f7edcf41d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0754046098c3f7468ef5e05a48bcf46d44f871ce.nq.gz
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

[dry-python/stories](https://github.com/dry-python/stories)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
