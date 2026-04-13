# Repolex Knowledge Graph of PyO3/setuptools-rust

RDF knowledge graph data for [PyO3/setuptools-rust](https://github.com/PyO3/setuptools-rust), parsed by [repolex](https://repolex.ai).

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
lexq download PyO3/setuptools-rust
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5be541f26b16b8bb6af74adb9aac790d79fafc1a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5be541f26b16b8bb6af74adb9aac790d79fafc1a.nq.gz
│   └── repolex
│       └── 5be541f26b16b8bb6af74adb9aac790d79fafc1a
│           └── chunk-001.nq.gz
├── blob
│   ├── 00942af974501663cb900c06bae66f3e00efd0a8.nq.gz
│   ├── 0bc7676af3932a09cf9cc53cfb182dfecaa4bf96.nq.gz
│   ├── 0c8a927b10072caf2703d8e9a4f090a47602e532.nq.gz
│   ├── 0f410bb16bfaef5e9a4a2565fc3f6879faa5b93c.nq.gz
│   ├── 15c3a0029f9e025f2b25f31ce5519ecf086ab63e.nq.gz
│   ├── 1aa5c08db42f53e0f3e8df5e48968b16473949d5.nq.gz
│   ├── 1c304ac231cc707e1d375170644818d2952a58e8.nq.gz
│   ├── 1c74473a3eb61a30d5c2e36dbda2a9eadeb8a9cd.nq.gz
│   ├── 1e45445513e4b293d87b648087d05880539aa097.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 23e6e098879eddd220e0bd3fc8a90b5f8a2279e1.nq.gz
│   ├── 24eaaf48ac4a454c27f74844c5608600880b7627.nq.gz
│   ├── 271da092e672dbe15392da6480d36386709bdc1b.nq.gz
│   ├── 28315649dc586014a6ebb27ced736223e459e150.nq.gz
│   ├── 2ede9f7dd80ffc8e17c43723ace391714f0ac052.nq.gz
│   ├── 3095c757f83297c56ad54b1aef7fab02ce999676.nq.gz
│   ├── 30f12921695e445cd017e9f42e4c0555f2162021.nq.gz
│   ├── 334afe90b79513b9b84dcc07166fdae0677b47bd.nq.gz
│   ├── 340b4dad5bdce66627654d5b0887332746fd1235.nq.gz
│   ├── 360400b3afd81aa44cd10279bdd3711833fb659a.nq.gz
│   ├── 3820519647ea825712cf0e9123e0c9d06fc3548a.nq.gz
│   ├── 3a72dc787839652ad8f108bd57b49d98444b59ef.nq.gz
│   ├── 3ba23bfb913f1444d08bd3771ab9de64db1c9e81.nq.gz
│   ├── 3c3b21d9888948a81ceaadd88be8254f17548ce7.nq.gz
│   ├── 41995db89dccb67d42227007ffc484b9549728f8.nq.gz
│   ├── 451bedaec21ea36474276ced4ad7260227f5b227.nq.gz
│   ├── 4621934c670a94886dd4d120e99d5869635143ed.nq.gz
│   ├── 46dd52c4534d2c0d79eb541cde94ed872f4b04bb.nq.gz
│   ├── 480d76dc6e271945187df39cf7e45dcf266924c9.nq.gz
│   ├── 4b5a004af14fabae1d07c69b194b42e061b76ced.nq.gz
│   ├── 4cb78b17ebbade4185f69e8c4efd929f652baa8f.nq.gz
│   ├── 53679dca0c350daac870883937ffbfe353f792eb.nq.gz
│   ├── 541ad8f46c1f1db0ebe5569abe087c5b3ab91967.nq.gz
│   ├── 5644273a09d6b9e238d1fd17211ff242998a3f33.nq.gz
│   ├── 5729cd148625ab58abe5fe139acc9fb894f171ed.nq.gz
│   ├── 57fe77ed0ca5a4f6feebbb18f390dd265f6f98df.nq.gz
│   ├── 58008409147fdb60f0cacf5d12d64162123af1b2.nq.gz
│   ├── 5877c7a1d874a74f7f7884f51ebd1fcf13d23afa.nq.gz
│   ├── 5bbc64f90f05084308ed9287974f1937c1a0a3d1.nq.gz
│   ├── 5d42f5bd8875e6ff4bd7374285402a171909c1ed.nq.gz
│   ├── 5e78bacac970aae81b3fa1e50f616ba03b5c69ea.nq.gz
│   ├── 60d681d18655ec9cff23016a0ed71e254b4e373b.nq.gz
│   ├── 62c7d72a71fb066e75e3a01a249c31fcdd11b078.nq.gz
│   ├── 689e08a28bba4c6899767bc52981ad55c4c92326.nq.gz
│   ├── 6a3f35411476dadfdf0587b2f62f0dee8dfbf1b4.nq.gz
│   ├── 6cfc18706ac3878c5afe7881179e05da61c45b81.nq.gz
│   ├── 71ddfbff5873bdc4f823e047729112d612a8bf1d.nq.gz
│   ├── 77702daf8a2a4d242345f3ff25d4805a239d88e7.nq.gz
│   ├── 77c65efda6848b5a01b309c12dad8e44212435f1.nq.gz
│   ├── 7afbac5495d1254b6318c2c842be09f7bb902016.nq.gz
│   ├── 7c4751733c1dcdd5e63f3340729d0dc51bc3e2d5.nq.gz
│   ├── 7c5fb39a30fece5396a90c705ca0db801c98c9ac.nq.gz
│   ├── 86969af519af1ab24ea8a44efa69cdaf23f8fbbf.nq.gz
│   ├── 88f0ec2d47a5282a6385acf9b281cc95d1baa376.nq.gz
│   ├── 8976f4eb361aa6a170b05ecb4f40ef4734185d69.nq.gz
│   ├── 89faa27aad766bf410aef51e6fafa6a09ccbdc11.nq.gz
│   ├── 8ac3e187fb7505036d907794d592b2d1a4f0c4c6.nq.gz
│   ├── 8c68e33eb607347839ae19352650b7fdd0e57942.nq.gz
│   ├── 8ea8f94dff0d2a436d14e1235b6fedc01001a317.nq.gz
│   ├── 9b7fe4020146997b3f81198e1e9871eb59b976e5.nq.gz
│   ├── 9fdb632a2191a9afadb2ba5a37c45236b0e243a6.nq.gz
│   ├── a288a58f715051eccc25e799bb367894916fd1d0.nq.gz
│   ├── a36267ccced7f9bff4d987823812d540d037cdbd.nq.gz
│   ├── a49f4d88b60db8925078899ba10b89acff077eb4.nq.gz
│   ├── aabcf93072a2723f6f51fdfd574b2730aa7ecdb5.nq.gz
│   ├── ab3097982a60dd118ef7d8f900347bda9ac304e7.nq.gz
│   ├── abf8eeeab13e83283087fbc7b3ed6d5c453e5ee5.nq.gz
│   ├── ace924d5363173ac584f168f4bd77236e0ad2db3.nq.gz
│   ├── ae85ccc490a964db73bf98ec4bdd553b1ae8d800.nq.gz
│   ├── afa01bde73dcf14254c70bc8542d5fc9a4065b16.nq.gz
│   ├── b4973c766ae5ec0c534c8702cb49490ddf44e666.nq.gz
│   ├── b731a702e4984f0fded90ececaabdc4c1ed96cb5.nq.gz
│   ├── ba81864bde88fb749043c6aa23ffea42cb25abb2.nq.gz
│   ├── bb12d18ab5ec273b8902beb30e6f8713cf3c3ed1.nq.gz
│   ├── bba3a0868b7bfc833a31764c3dc7e0e834c295cd.nq.gz
│   ├── bc1ee27cc3bdee83fb10f61efc947c204658f581.nq.gz
│   ├── bd38948b5c1a6ba58aa5ddc15faf6bd6793c90a5.nq.gz
│   ├── c0bf7f796154c8eca491826f56be130891514e80.nq.gz
│   ├── c3fec7689180f5eec1a7a39982e7a18e29f9b62e.nq.gz
│   ├── c79be56f5a472085e555205930afa2a805ecbfc7.nq.gz
│   ├── cbb4c1d0065cbd1fb6ed6beeb226bd4fedd02103.nq.gz
│   ├── cd874470f005b9e54c6a4f8308c045bb527dac23.nq.gz
│   ├── cf07e10b61bfc95c8a8ac236f69ad32c94799641.nq.gz
│   ├── cffca4b64d857318c71c04ac0f4e35dfc337caef.nq.gz
│   ├── d47f983e474f82916a52740b6a253006043c4410.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d74d315d9c4cceaeb3de7ae5be9b928ee923e983.nq.gz
│   ├── d8b9cc703d78edd91772f35bbaaf5400b29ec777.nq.gz
│   ├── d8d2dabe178989af0aa34b40c78cfd4eb9ad7f5d.nq.gz
│   ├── da1ddf1410e6d7c67d2d52669665c5e38581919f.nq.gz
│   ├── dbe702b3219729c0e0ccebe62873da0acc78cea1.nq.gz
│   ├── dc8ceed985415ffb32d25116ebce10c8e0c9b466.nq.gz
│   ├── e1a132c244264e69c56de837ebb3e55a650542c6.nq.gz
│   ├── e224694a10a8216dc62d1ded61a5dbac1640fc9a.nq.gz
│   ├── e6394c098508d3d11165ba31c6c67e4861458718.nq.gz
│   ├── e68d501eea4545e19b2f27f7072cae5b4242501c.nq.gz
│   ├── e6fac0e33242e9aedde48dd395b7d4ebd129e375.nq.gz
│   ├── e7a11a969c037e00a796aafeff6258501ec15e9a.nq.gz
│   ├── f5c8d51c69b7a725ead634f533e893811a1550fc.nq.gz
│   └── fa20f20054e16a27c8e16cfb508bee9a5d4892d5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 5be541f26b16b8bb6af74adb9aac790d79fafc1a.nq.gz
├── filetree
│   └── 5be541f26b16b8bb6af74adb9aac790d79fafc1a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 110 files
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

[PyO3/setuptools-rust](https://github.com/PyO3/setuptools-rust)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
