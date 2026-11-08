# Repolex Knowledge Graph of canonical/sdcore-nssf-operator

RDF knowledge graph data for [canonical/sdcore-nssf-operator](https://github.com/canonical/sdcore-nssf-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/sdcore-nssf-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 589823f43566334e07c16938d0aa71a44e0cf574
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 589823f43566334e07c16938d0aa71a44e0cf574
│           └── chunk-001.nq.gz
├── blob
│   ├── 0023ef6f0bdb95e40d616457cecad35d3d7d114a.nq.gz
│   ├── 07e10a08514124ce2ce63de2bd3fccecb89797e1.nq.gz
│   ├── 09d6465c8ac821043b78550c8d38449f6f714d70.nq.gz
│   ├── 0b680d508757e960bfc1e7190cc29509514d1562.nq.gz
│   ├── 0d6ebe0639dd863c73d626d72d6af3587eb0ffdd.nq.gz
│   ├── 0ff992b299b3f0224c0a4575fb68ea04de62af99.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 2055a28de90818ffa33b0a2ff4e1fdbd93eb1473.nq.gz
│   ├── 2363e0938e0fa08ca6190e02fe17f47c013e5f2b.nq.gz
│   ├── 25f19c54399ad917c18b86fcc1c34c53c36bbd13.nq.gz
│   ├── 34cb63f999c3c5709fd095103dff8aadb62f0520.nq.gz
│   ├── 36d8637d3729b7e100917b4b2f225c19439d2129.nq.gz
│   ├── 3bcd8a9f726c1e7ff32172d0ed5d95ab6436a34c.nq.gz
│   ├── 46fdfb6ff31d8f845aa61ec8d9c441011982757c.nq.gz
│   ├── 4d394c33b8ea132a10ef09db97c9509d10e14fd1.nq.gz
│   ├── 4f71461f013a3a1bc2ea0949581da28f4451353d.nq.gz
│   ├── 5411236d6b63bc4bd54f36ff39cc6f7912a44507.nq.gz
│   ├── 58d795c24bdb80407335a77e19c94311427525f7.nq.gz
│   ├── 6063f72f417271a6cba967b4e767ccd955d209b3.nq.gz
│   ├── 624a349d409cf50d3bf162dd7e05f8395c263ed2.nq.gz
│   ├── 6c35980879b407f71f59e61c8d2e40887522ed81.nq.gz
│   ├── 757ebc0704dc2f34f141d4f198aa5599e49e2057.nq.gz
│   ├── 7bbbdf45bed96dd74d8c9566653b60262bd9277d.nq.gz
│   ├── 82d9c4ce5bf033502803c481079f191ef5cb7871.nq.gz
│   ├── 8588e735404dde06002ec57f110f846f04ed0c61.nq.gz
│   ├── 887298136a5fee6cc9f4a3a9e76927363daf380b.nq.gz
│   ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
│   ├── 9373f232046873177a8c824407d3f4350a389d6b.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── a81c4625c094f11963e67c498ab3809ecb84c1f2.nq.gz
│   ├── bacdac9601b5f6a4c853c51ae74f2e996a4f5b45.nq.gz
│   ├── bbe77cb69558e274639017d0079c3ebd6bc948a5.nq.gz
│   ├── bc4b5a46de8057cbc11051996964b8cca6173a9a.nq.gz
│   ├── bd418d4c38a2ac7224a9d96b73029764359b499a.nq.gz
│   ├── c6352d49ae8dccf12e9222ea0c8fed87494dc7b3.nq.gz
│   ├── d01d3ec218c3341b0efcc04120cea0290c5f3ca3.nq.gz
│   ├── d11341b62dcf755417eab88a830e313ae938327d.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── dae9ee87676ed020a050c2dd41e7055c2abfd6a7.nq.gz
│   ├── db4923631dff0275b601482cf535d3387109d762.nq.gz
│   ├── ed67d9f62e5efc1621f0c0e8ae8ee293fdde7856.nq.gz
│   ├── f0571dc2b05049fc3780efcdffbafae38febe7a8.nq.gz
│   └── f55e2ac0b7cdc745660d9a67fda82554165dd782.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 589823f43566334e07c16938d0aa71a44e0cf574.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[canonical/sdcore-nssf-operator](https://github.com/canonical/sdcore-nssf-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
