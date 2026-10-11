# Repolex Knowledge Graph of sphinx-doc/sphinxext-rediraffe

RDF knowledge graph data for [sphinx-doc/sphinxext-rediraffe](https://github.com/sphinx-doc/sphinxext-rediraffe), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-doc/sphinxext-rediraffe
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 47273a20adad2e95732014fc0fecce13d31e36dc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 47273a20adad2e95732014fc0fecce13d31e36dc
│           └── chunk-001.nq.gz
├── blob
│   ├── 02990f1a673422d354ddea48c4b4a5a7ceea3a6d.nq.gz
│   ├── 08080d314b5fa1f5795aee17a636f04199b672b6.nq.gz
│   ├── 0eebb09dd76ab31b3e29bcf646f8eae93b0f2931.nq.gz
│   ├── 0fe2fa50e8e79f56b23267be86bde68d6f86195b.nq.gz
│   ├── 13796af27f728a6b1185edefd8dd77895679af74.nq.gz
│   ├── 16226d0c67922ba0281f95e23441bfb1088d4210.nq.gz
│   ├── 165a581fbde1fbc26de48a3e918d5c77e5426dba.nq.gz
│   ├── 1675f59040286484aa47224c0d4e00f8d9d473e7.nq.gz
│   ├── 18f5eb10fceca19a962ec989e90ce97ad002f8d9.nq.gz
│   ├── 1a22571a3629056ecdedc4d96b93ab31c8e31957.nq.gz
│   ├── 1e3715705906307b64011865f193132442d41277.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 22352d44dc4e97fafd7158b56bd47b1f61feb57a.nq.gz
│   ├── 2341d4436be10c8a37ce67c830bbf0b57bbf8453.nq.gz
│   ├── 2543c50910afe498c0b28a33ef5716bbdbc6a501.nq.gz
│   ├── 28d423dba9717c74fb9ea75f334518f20467baf1.nq.gz
│   ├── 2c91d316a057d50bad9481bc1748a5f0ad4ae61c.nq.gz
│   ├── 2ec85632a655b6052c92f006ebd2ecd79778e8b9.nq.gz
│   ├── 33de3fff7c91104959877a49834dea7d841e6f0b.nq.gz
│   ├── 39b7d337f957add3939af3892365637d99d31aad.nq.gz
│   ├── 3fd379e567a614f3b81bf9b2c547035fe4ac2ef7.nq.gz
│   ├── 4053ae244d5161621ea681c0b650b32b8e60519d.nq.gz
│   ├── 4053e48779faf135ac1fd7056db4d31f0068118b.nq.gz
│   ├── 49325580b3365485e5418e091cde6d73220648f7.nq.gz
│   ├── 4a705da94d5c64633180396c1308c2edc3f0514e.nq.gz
│   ├── 4ab4b86b611d267924aad407e58a4364321a5799.nq.gz
│   ├── 4ac385a2fdb564c336a0af53b0f911f91381fa89.nq.gz
│   ├── 4b39ecb40ef8a956ac9d0aee593b2702a6b04f00.nq.gz
│   ├── 51df9383767ab71291daa4284957ef57316154f8.nq.gz
│   ├── 523e6eb76e57f01f885a91fba61ed2e2599609b0.nq.gz
│   ├── 535c2e73a7901dade035e1b034c1912742cdc8db.nq.gz
│   ├── 5665d80c875ae06504f52df9d992f3396bedd0c7.nq.gz
│   ├── 5aae4f78aa2c6da727d918064c6c2ebdb5e7863d.nq.gz
│   ├── 5c70e0cea3b0f764e3520bfe2a400fe0393c3896.nq.gz
│   ├── 5d409bd072258781b18559d706526353db509da5.nq.gz
│   ├── 5d849a2807954eea190bf4e6391ed98bf77f12e1.nq.gz
│   ├── 688b2bef3293b9b63c6a6fdcbc268d81196f7f96.nq.gz
│   ├── 698208332c8ca08014b0bc774f4b5c85316fb7ca.nq.gz
│   ├── 6c838c27833a8e0446ad1268ff7e21934837fcde.nq.gz
│   ├── 7088d6e765a0f5f01825949343b31fcb3fbc4ba6.nq.gz
│   ├── 70f80fc4232606d2cfe5dc5af85d67bc9f38d371.nq.gz
│   ├── 740d315416a0dc0bacfbde622ea7fdbe88558268.nq.gz
│   ├── 844705a97cb0035c15ca8f52dd4b151d04dbefbb.nq.gz
│   ├── 883ad6e8ef9a7392b45f6fc9e7d53c88f502388b.nq.gz
│   ├── 8cfb08985a78be814b461a0cb8589eab2f163e4b.nq.gz
│   ├── 96f6998b2d8809ff332fcc1fd49982d92bdee97f.nq.gz
│   ├── 9b593af670f4c28e82ef45814415b5f9aa5263d2.nq.gz
│   ├── 9c4e6b1375eeddd7fe6078b62aa1b045a5630042.nq.gz
│   ├── 9cbe6ea56f225388ae614c419249bfc6d734cc30.nq.gz
│   ├── 9d9fff1f4dd39be081ae25a2b1ae59fbce5b41e5.nq.gz
│   ├── 9dd7ac90b565b3f0fcd68139afe00c22b8105103.nq.gz
│   ├── a419b854d5663f3f696c1ed8c3453bc4d22d7d83.nq.gz
│   ├── a76bfcc8000d89c36f6473566a92763c6ed98dda.nq.gz
│   ├── b282b6a3cd055d42b02ed1dec4470077e284c48d.nq.gz
│   ├── b494e93d33095a168b52dd12f6f81cd58f59007d.nq.gz
│   ├── baf72b1da3ee845c0543fe0acf4e02e1a031f397.nq.gz
│   ├── c42b1cd867775dd142cbcae03bd334eaa8e0d824.nq.gz
│   ├── ca5aa095ae141eee58d481b35d2196d8b9604b6c.nq.gz
│   ├── cc891f10d5ded3fe71a8f07074a6d77f52c02786.nq.gz
│   ├── cdcb28483da7783a8b505a074c50632a5481a69b.nq.gz
│   ├── d49eae99ee17c16a2d755505fec1717b7697766e.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d53a5413c90f9a00e9c2d587a5d602deb770cea1.nq.gz
│   ├── d5bf5e353572cf2bf9915ea08905dd096e18d484.nq.gz
│   ├── d6221f771f9ae3d2dacafb93073b814f2aebdba7.nq.gz
│   ├── d8321a035a390378b5dbf4f12cd01a3245a5c1a3.nq.gz
│   ├── dd0528bff62ea97e536c8591fe7229a3bff636e5.nq.gz
│   ├── e015da7d5c0f7bf8ec0e0b7f6b1d13323e293b46.nq.gz
│   ├── e5171a9255a07cf97c4551e5c7898572b1f690fd.nq.gz
│   ├── e5616f399cb32769ea6f75d22cd779ef955d9bb2.nq.gz
│   ├── e66c09083b8d1999e3b7f8aef54e56713e98d8d6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb764ce25ccedcc29c1f48f3b6a949379b82a93f.nq.gz
│   ├── f25711eb6bf512fa2869dc5e87f950510d24c75a.nq.gz
│   ├── f2f56a776fb2c7143320faf5393ed174c0393f74.nq.gz
│   ├── f3736ef0aae364e06fa9cb97e4e2ad0f3b61a007.nq.gz
│   ├── f63b3f473f0702ed31700c4ffd5e3dae2f9ad8ef.nq.gz
│   ├── f97d447c2ca1ed9316ce4e2b8200098a39e07e70.nq.gz
│   ├── fa7af8bf5fdd704f73beb3adc5612682a98e1af5.nq.gz
│   ├── fc27d5e0f7e6a92cd178a84a087c69cd4e94ce08.nq.gz
│   └── fda3443fde94add6ab8b546d5fd5cc0d1cebde1c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 47273a20adad2e95732014fc0fecce13d31e36dc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 89 files
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

[sphinx-doc/sphinxext-rediraffe](https://github.com/sphinx-doc/sphinxext-rediraffe)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
