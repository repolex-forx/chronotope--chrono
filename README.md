# Repolex Knowledge Graph of chronotope/chrono

RDF knowledge graph data for [chronotope/chrono](https://github.com/chronotope/chrono), parsed by [repolex](https://repolex.ai).

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
lexq download chronotope/chrono
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 45caaa970ce443b11106a710ee24bd2480e5ff99
│   │   │   └── chunk-001.nq.gz
│   │   └── c14b4599d07ef36ffa1f8a531fb0bc7eb3b42464
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 45caaa970ce443b11106a710ee24bd2480e5ff99.nq.gz
│   │   └── c14b4599d07ef36ffa1f8a531fb0bc7eb3b42464.nq.gz
│   └── repolex
│       └── 45caaa970ce443b11106a710ee24bd2480e5ff99
│           └── chunk-001.nq.gz
├── blob
│   ├── 0723c4866f69bec0451965428993a8882806a73b.nq.gz
│   ├── 0b47ca439ebb9e7d5355e4d94e251af0f5740fa6.nq.gz
│   ├── 0e942e02d5385af8afb98f16905b3f44e218b93a.nq.gz
│   ├── 123a78148583605cb3e82ce9edeaa75d2b35f810.nq.gz
│   ├── 15400ef27e5a9e10c6b74060a611d341e87d0480.nq.gz
│   ├── 18857a286ace737b14043b5cd5238dcc17f84cec.nq.gz
│   ├── 20dae08e9523baa56ed86fefd5af2c9348b31f0c.nq.gz
│   ├── 236a6f1da932b7d2195a7d912bc8bac8835e2a40.nq.gz
│   ├── 25fcbc138e210a27ecd9083280cc1292c5b4be32.nq.gz
│   ├── 272976a0152c56b15e576feb98c116d75998cbac.nq.gz
│   ├── 295700b4f71fe171b9858c020075b8786a1383c6.nq.gz
│   ├── 2bfdf28b3fb8cc8850b800eb63033e3c83f94433.nq.gz
│   ├── 2fe92c8a444922b5c09c2b65ee44b734bc97b4ee.nq.gz
│   ├── 30dbc6746b52fcff495f6366c8444a17007cc8b0.nq.gz
│   ├── 34c4fe442cbc0338182dc75664da33141431d846.nq.gz
│   ├── 3533e56d5698eedf55f8c6aa5aba68010004b3af.nq.gz
│   ├── 3746ba4d974571fc9b5327dd9f7c135bfc521ee7.nq.gz
│   ├── 4258f9d90c308de2be66a5f1a8272fa245e60972.nq.gz
│   ├── 450f0a2259617a320bc9b68b472c1024ecf11d1b.nq.gz
│   ├── 474034e27684456e153269fdfa0fd16d31cd3d77.nq.gz
│   ├── 480fdf7e47e0ea82eb5363bb52ef3b76ba41ba67.nq.gz
│   ├── 4af7d2ecc5562372865ec2b9242d01a12b6c7152.nq.gz
│   ├── 4c306b5e7f4c6e7c6711cb70076fdc966efc254d.nq.gz
│   ├── 4cc205595c5e8d0c703a8efe12d76d98cf8a56d6.nq.gz
│   ├── 50b6fa7590f6c659a3e92ebcb9e0a7e299ca4542.nq.gz
│   ├── 547dc46ad51a7c8e99cf6f06f421fb595a88fc83.nq.gz
│   ├── 55d575a99a998f5d8aa13f90d111467842061be7.nq.gz
│   ├── 572e03bdf321b6cc3a99488183436905cefd086d.nq.gz
│   ├── 5741d2410360e97e8c7ae1cb984e05208b632488.nq.gz
│   ├── 58e16f3c7f76b81404a5c76491403bbed03bfb1f.nq.gz
│   ├── 59cef0ef4361143e13b9eab2028fd0e1f215dafb.nq.gz
│   ├── 5a35aa38447c02d9d882697f5632f243dae9b093.nq.gz
│   ├── 5c16e2b1f0610c09e862974fa48a1fc980b5929f.nq.gz
│   ├── 5d83f4f146170356b7618b62356a89a05b9aaac0.nq.gz
│   ├── 5e51d7f73c7900be42e5a2c58b2dc20afcad2e9b.nq.gz
│   ├── 5fe42eb83fb39e86e13c32694ecb88028f8f7c19.nq.gz
│   ├── 604e6654c5175b3e804646271274dc3f26943721.nq.gz
│   ├── 67bee1049ec41a4c59993e9a271f352d7c0a3e80.nq.gz
│   ├── 6a38dcecba8a5ee1a86826eb632287aff79ebc85.nq.gz
│   ├── 6a7d395e29f3c96b0d67790e46ae65dca537af44.nq.gz
│   ├── 6ebdefaee530f0360afe876d0b0c758fc61111ed.nq.gz
│   ├── 764cd26a9c70e666a943f7af68b5261c2dd226ec.nq.gz
│   ├── 76cd26e2880d02f2faa501c0990e92e48d306e94.nq.gz
│   ├── 77497994aedfec909b35297ca5bf3ebcf87d4c0a.nq.gz
│   ├── 84c99063c15bfcd9cd499364d2a569005c6e423e.nq.gz
│   ├── 8791019f604b9fc60e26df7754202bbcfe178d6a.nq.gz
│   ├── 890d550456705c4a5897d864fdd8c87bce8ccc8c.nq.gz
│   ├── 9356dd052b36fcb6c68f7fa7a3fd0dc0f3f38db8.nq.gz
│   ├── 989131c2096a1ca138c3b80939e00663eabcec7c.nq.gz
│   ├── a544fcbfe73f264d644785c8b43db5ef24cd7922.nq.gz
│   ├── a622ab818e00bf937c25fde3880b999f8e03f691.nq.gz
│   ├── a8e53010b39217a4d46950cf2827419a4975a14a.nq.gz
│   ├── b1d4b976df0eedbad0994ab640598e93080ba285.nq.gz
│   ├── b2b96715a864b2bd4a87309e9c4c2dec80a2e81f.nq.gz
│   ├── bc00d674d0d829b32e227c37fd216812a6d65f83.nq.gz
│   ├── bfe4fc347f5ae928a784f058b305a7c1ae8ab855.nq.gz
│   ├── c1a27c85985b64243c79a7e425927bbbdf342b0c.nq.gz
│   ├── c615476c0cb5762c246d846d90adc796e6236a16.nq.gz
│   ├── c61a13f54983e8ac0e9cd35f24f2e625840a9d1e.nq.gz
│   ├── c8ac89ffcad6c13665d76999b7f93b24e71d0d2b.nq.gz
│   ├── c93c587157e22ab3581aa7d8da2b3969dd58fd46.nq.gz
│   ├── cb563b4ebbf78a4d74476a4a4ff9f39c5d461f7b.nq.gz
│   ├── ceb9b3de97d5f751037dcf9972a7bda7c9a07986.nq.gz
│   ├── d1df20cf1eb5b49c5a0b16882a472443da89a407.nq.gz
│   ├── d428395db0cfe759cb76e5dd92ebe8b842a7a7c6.nq.gz
│   ├── d6148d67998ecc64edd0cc5be0e1a888f64b5813.nq.gz
│   ├── d6b90a3179fdc7e2bea901cdf28f67f73c7c0b98.nq.gz
│   ├── d87371caaa8eb13a2c59f9160f6288f78c8c311d.nq.gz
│   ├── d93ef814c855d46cb06352e336be0bf63e460ef2.nq.gz
│   ├── d95c0acbef42b54a8abb006ef6510b8f11eedc41.nq.gz
│   ├── da4746b8ae58810ffd5b8f929f4d9a46b3fda604.nq.gz
│   ├── dcab6c44e607d74e44f69f6bc7be9f3a74f150aa.nq.gz
│   ├── dfa2b181b563169422252b0d47f54d4f141e5648.nq.gz
│   ├── e810c854fd8d67fb6efbf438379ce1dcae47288b.nq.gz
│   ├── e972e083111767c19db6e01c88f0c514aed8696b.nq.gz
│   ├── ec4beae4530cca72f2a23147dc4832c045ee60bc.nq.gz
│   ├── ed1b3b061a2e9f425f9b2637c506a37699789687.nq.gz
│   ├── f989181e4fc886800d0b05e14c7d700038de88b5.nq.gz
│   ├── f9b1dde2153c66bfe1591939334e02ac50af09bb.nq.gz
│   ├── ff0f95bc28875a8f673eda49837dd8a22e5955f8.nq.gz
│   └── ff94584c6e06f628da54b38f9ac479d5a25ad164.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 45caaa970ce443b11106a710ee24bd2480e5ff99.nq.gz
│   └── c14b4599d07ef36ffa1f8a531fb0bc7eb3b42464.nq.gz
├── filetree
│   ├── 45caaa970ce443b11106a710ee24bd2480e5ff99.nq.gz
│   └── c14b4599d07ef36ffa1f8a531fb0bc7eb3b42464.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

16 directories, 95 files
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

[chronotope/chrono](https://github.com/chronotope/chrono)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*
