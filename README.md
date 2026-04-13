# Repolex Knowledge Graph of samuelcolvin/dirty-equals

RDF knowledge graph data for [samuelcolvin/dirty-equals](https://github.com/samuelcolvin/dirty-equals), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download samuelcolvin/dirty-equals
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e8cd329dfb910a9696edc9cb793e35c2de6c502e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e8cd329dfb910a9696edc9cb793e35c2de6c502e.nq.gz
│   └── repolex
│       └── e8cd329dfb910a9696edc9cb793e35c2de6c502e
│           └── chunk-001.nq.gz
├── blob
│   ├── 014a35bb6fc8cd972371a85983a311310e5ffb46.nq.gz
│   ├── 02462a66d5590d4cf4bce2f9d2a74ff83c4df6a4.nq.gz
│   ├── 032fbb0517070eff76f52dbe60e236fb28a1ef56.nq.gz
│   ├── 0b5620c032c2b645fb0af5bfa53580ef53d630a7.nq.gz
│   ├── 0d0140b35084375e30ee0c1128455520dbe19d85.nq.gz
│   ├── 0d5e8660a95609e9ec3bb8edb0c59f8549f9d420.nq.gz
│   ├── 11dd86e8f374a318d8f300bd495c92c46651cae3.nq.gz
│   ├── 167538e79e8a4099b79aa43c839e4db927ba03d2.nq.gz
│   ├── 16ad823c245b99dcdb36640cf23c172475935d58.nq.gz
│   ├── 174283f08205da877695c1c8e258e400b0a0c16d.nq.gz
│   ├── 18358654758c29443f88a06eb6a19c2c25b0b215.nq.gz
│   ├── 1f08ea06dcdbf10b0ef9f0c693bcbba2b6f85dad.nq.gz
│   ├── 1f3dc20abefe47cc81b4afa24ca4ef9c103fbf14.nq.gz
│   ├── 21331ba4706af92b945e897dc9a9d62edb529473.nq.gz
│   ├── 2a3ed8a3b408db1a05688abc1716dfb0aa1f90b9.nq.gz
│   ├── 37f8fba46037800d3b2bd91f7ee2609875cdd037.nq.gz
│   ├── 3d170298f92eda4e2f580c300bb3e9347cb3458c.nq.gz
│   ├── 40c596e9b68c5b5d9c6eec3836f001b59e6bbf74.nq.gz
│   ├── 455963f41782c79a8b56535770d474fc3decb00c.nq.gz
│   ├── 47de40dc06ba673d480a12ef728ce62fe43e3151.nq.gz
│   ├── 4ccf97be1c542fc75c2636be072d0a55954b4f95.nq.gz
│   ├── 501a2b7968b7815082503abf8dd59339a58dc758.nq.gz
│   ├── 50ab07b63f8e7e12978450e51c7823a97b0e788c.nq.gz
│   ├── 5398e7cff4a8678ad7dd561e1bfd7b73d9db3e5c.nq.gz
│   ├── 54558e34ee18d03e25f04549c00b1795fac8003f.nq.gz
│   ├── 559dc68ac7bcc5b64948a2a5de21ccd364f797c5.nq.gz
│   ├── 6b81735adf9dcef2194807a72d11ce209310e565.nq.gz
│   ├── 6e8f6779b6b9a551821a1e00e1349739eb8151f9.nq.gz
│   ├── 7125e57ec0f0f5992b0554d97bc1a919f6cb4322.nq.gz
│   ├── 8082afe8847e824f14c68683715373e20c0bd89d.nq.gz
│   ├── 80ba27e7a71b3b219c73ce0511d90edf56cdc68d.nq.gz
│   ├── 824a470d31b679baee99f46a9f3a5c72aa3b11eb.nq.gz
│   ├── 895c08e4bf3981431ba8d5b5799a35d2639f1dfc.nq.gz
│   ├── 8b0d7289a0323030073f7d22cd54c76fb0fcdf5e.nq.gz
│   ├── a23c98b37f61935ddb970103ed2f3557f8417f70.nq.gz
│   ├── a6d87beed4df3a97f242ec6e58afed60a2d16f8b.nq.gz
│   ├── a8b4368ff64f394fdac374f3dbdf6099f02e0da5.nq.gz
│   ├── b1052a6ad16452ee80204c514f2cdcb712b02dc9.nq.gz
│   ├── b22538a47e88e0106aa2a162a0bc3154e31250bb.nq.gz
│   ├── b817677a77a27e6d1e55be804e6670bdcf77099c.nq.gz
│   ├── be6ca2ff6562efdaf5af43cd2243e394c4ef4123.nq.gz
│   ├── c47652c20d4a96add491898a0d4e8fdd5a5ee4a6.nq.gz
│   ├── c879eb6063d619284bbdd82fb30140db03f040a9.nq.gz
│   ├── cb60b72bde968488e7f1b3874d03135023c95c07.nq.gz
│   ├── cdf27294d6d5432c00441a79e418e4cf0f86e26a.nq.gz
│   ├── ce2a6620da023cb2d605542d84a8326e9284423f.nq.gz
│   ├── d4feabec941c9317d411a7813243c5d4535b5781.nq.gz
│   ├── d89b60163205f536d043acf70e9ea8c5abc5b91b.nq.gz
│   ├── e2464103f5493a80893bc450b11caad900a5a437.nq.gz
│   ├── e338a16b4d21d280aa149e60373b7e8a9fa43800.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec30ed712334d778a6f14038338d060943f695bf.nq.gz
│   ├── f69e9bb68b4df6619c5b5aa6f248f5f34aafeece.nq.gz
│   ├── fa1803f38cc381e525c57db9cdbfb926c4640577.nq.gz
│   └── fa314bfccdcf24e2ea315cd3ea466980822220e6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e8cd329dfb910a9696edc9cb793e35c2de6c502e.nq.gz
├── filetree
│   └── e8cd329dfb910a9696edc9cb793e35c2de6c502e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 65 files
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

## Source repository

[samuelcolvin/dirty-equals](https://github.com/samuelcolvin/dirty-equals)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
