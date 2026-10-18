# Repolex Knowledge Graph of snakers4/silero-vad

RDF knowledge graph data for [snakers4/silero-vad](https://github.com/snakers4/silero-vad), parsed by [repolex](https://repolex.ai).

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
rlex download snakers4/silero-vad
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1e261b036686cd0017d500ee96acd1c4ba572a9d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1e261b036686cd0017d500ee96acd1c4ba572a9d
│           └── chunk-001.nq.gz
├── blob
│   ├── 05497e74fce9451358e45248c32cbd96c78d4581.nq.gz
│   ├── 0ad7ee0820f0a9c51cbe6afff5fb28b0d2898e15.nq.gz
│   ├── 0b1b64ecd9b316445e06cfd5b6b709b0e5fcf18f.nq.gz
│   ├── 0bf5e90cac691b999d4a35044f97167d7bbbf0b9.nq.gz
│   ├── 0c5175b7c15766edefa2923b789d9cfe0d1cdd0a.nq.gz
│   ├── 0ced1942afa6e996154ec82cd82b442fed718683.nq.gz
│   ├── 11bed72c7eff7aff5b261874dc45c9cb5fbd0ac9.nq.gz
│   ├── 13a27ca8e1d7e005ca195a535e83ea2adbf29b5e.nq.gz
│   ├── 17db5a5f8404a45330d7b886a4242c8aa61e4e6a.nq.gz
│   ├── 18f01f3a9cd5bc9eb0980d216ef34a24347b98c2.nq.gz
│   ├── 1eed38e75b89483dae5ad6ba02cf36d53f066db9.nq.gz
│   ├── 1fb73e3945eb6b25c34809aece11404ea6980706.nq.gz
│   ├── 202dc7d83ec4588455306e5a7b11f5a097e0a2f9.nq.gz
│   ├── 249d7e34d0ac55f118e992dd0fd4f9a9885ee4e0.nq.gz
│   ├── 28ec56d70f7002c0dce99a94c2491ec13ca72356.nq.gz
│   ├── 2c83c07d7cc24f7514dfd873684570e3feae14e6.nq.gz
│   ├── 2de9f7c168813607a3e4962f173928a5f069d2dc.nq.gz
│   ├── 2f071ebcef11493438ca76045ed8c4d9eb45205e.nq.gz
│   ├── 364bdf65de84ad3b9057e06bc62cadf6a9a7b09c.nq.gz
│   ├── 364ce3ac3e5140ea6e93c7182ac3ad5fa8b90ba5.nq.gz
│   ├── 367975dcd8924bd8f17254f3da99361be0a3b928.nq.gz
│   ├── 36b41c8d74abd68c22e23f79a080ed48112ee556.nq.gz
│   ├── 38108c133aeeb4fa2e0ff6ffe99f9a1bcd90a53e.nq.gz
│   ├── 3bcb00bce7afca4fc18a8d4fca9e479ace4d6dec.nq.gz
│   ├── 3f774e70b5194e0cf1982639d1781ca26adeec5a.nq.gz
│   ├── 430b66aeee25dda74d4e1b458fe12c2810e7b2e5.nq.gz
│   ├── 450b51e0d52164164a87487021d9dce3740f143c.nq.gz
│   ├── 4517e2f93122d7f1c2ac054ca6e61f670a205d98.nq.gz
│   ├── 4706bda93a99aec51eb27d92bcd2a96215b05afd.nq.gz
│   ├── 48e89bae266c071b0ed84b6c3458258e5aa15a20.nq.gz
│   ├── 4b3bef714cae87a44381077ac0519fd1a0f45089.nq.gz
│   ├── 4b4758fdf979cbcfaaac922e863f54a660a8b629.nq.gz
│   ├── 4de7e2671a03ece555f9082aa4eba1da56e7a936.nq.gz
│   ├── 5040af23f042ca3831a17ce17b89c21ce6140614.nq.gz
│   ├── 527fa2ded5ca9a03921de103ee4b4f002cbf382b.nq.gz
│   ├── 5295d32adfc6cc9febe7b92d80112279a2cc3f25.nq.gz
│   ├── 53297cd495f90f11ba8f89a273a70f42d058d10c.nq.gz
│   ├── 538fbf95d503e912da123d619d41f04b8bcdb73e.nq.gz
│   ├── 563db0f9854a7ed91c5d2eeddde57e9935588cd3.nq.gz
│   ├── 56aca296ec0607275133576c5e9196e655fc5e7e.nq.gz
│   ├── 59c0ff0b6cb8b6a5055e09576d5f1ec8939377fa.nq.gz
│   ├── 5b6a97f6aa93ea51c33615152c1709db0f7f58d4.nq.gz
│   ├── 5c6988d663950a93a5f0d6c38c2fe024653ec552.nq.gz
│   ├── 5d71767d026fb5c8f3967299e87e60d7a28f51b7.nq.gz
│   ├── 625ad8909b1abdba2292f3a9a10db6864fd5d561.nq.gz
│   ├── 6633e58b23d2785b207956e6e3faca07fa6c8378.nq.gz
│   ├── 6ec529d551216a23780da4663e5115ed28cf87f4.nq.gz
│   ├── 7080d0ab9438c5c69ce1ad8927f44644c3313e82.nq.gz
│   ├── 71528117cc1fe886b6f2d3d5944387b834033aeb.nq.gz
│   ├── 74329418315aa40e44c9ea343aace426ea1dc137.nq.gz
│   ├── 74e56efd5d4ee79d45852e8a8dcc31b14a838e73.nq.gz
│   ├── 761f958b3e14f59525397ddacef768c3495b4082.nq.gz
│   ├── 78d6ad79925d1204ce4641884f90fca4075f4ea1.nq.gz
│   ├── 7a9cd1928877afc498f155cbbb7a5e1e9ef832c8.nq.gz
│   ├── 7b5977711b4fe905381b007b64e4bfb33a1c1fa9.nq.gz
│   ├── 80c5592ef1f4c9ede3e357bbd02eb863358a6a9d.nq.gz
│   ├── 810588722f5a0b61a25414fbd0b04fdc8d189f7a.nq.gz
│   ├── 83211480ac0ee06830f97331a1b6158a673a494b.nq.gz
│   ├── 88db3cf16beba65e88a5a2486fe1fc9d1f3f0cd2.nq.gz
│   ├── 88dc906edbf6ef1d72f7a3eeeac6a282f9081d52.nq.gz
│   ├── 893b6c0a34c971cba8ec492646be7b1a3762d3c6.nq.gz
│   ├── 8d4a11e1be79cef03639645ab1f7496db9b2aa67.nq.gz
│   ├── 8eba914660125c81713afc9a7d19f4dac20fdddc.nq.gz
│   ├── 910001a6233f9ba54c4ac41e94bddf8301d87557.nq.gz
│   ├── 93a6791599791948809cb430663fc0f4111a70c5.nq.gz
│   ├── 9519308dd12c501dcc5a9da036d3b80e59fb3011.nq.gz
│   ├── 951de2f5beaf661146006c2383abd7678087c702.nq.gz
│   ├── 95527041993375b5a8ede3b1020fc71c68d1e82f.nq.gz
│   ├── 97e39fb3543dfb78814af3943f059c6bbc969bd0.nq.gz
│   ├── 98982cc55ce7b289f3818bf4e0a2c7b1e1f9f5b7.nq.gz
│   ├── 99955ee6f37604c0164e381c55c37d0a2adec330.nq.gz
│   ├── 9bde98723183ea28678e3bac7d52d88aa1b15b0a.nq.gz
│   ├── a2714a4d355d4b896d02139e167bbcdea820288a.nq.gz
│   ├── af3202dcc348efe7eaa07dca5b67eb66edbebca2.nq.gz
│   ├── b37c33a1018a879d926ae0b5d16566488743a412.nq.gz
│   ├── b57d4648dc7a7765b56fc9565016a33bf102de00.nq.gz
│   ├── b673c80df3ec8255d4c6b2969f1b00cbe6be59a8.nq.gz
│   ├── b7588a47faccd3c39ea3d45956f5eddc8e4918fe.nq.gz
│   ├── b8b46dea7b9a4ad3391b5ac68783ee42093e20cf.nq.gz
│   ├── bb3b271f4206c55f6061b38266f395408a75671e.nq.gz
│   ├── be18ceeb383b8c0a3c86dd9e1a5c92bd39e90676.nq.gz
│   ├── bfe42a28ec7db1189dbb83cb2fc1edd21263567b.nq.gz
│   ├── c69125eba21369f1b00a5287e337e72a404e0aa2.nq.gz
│   ├── c83bb78ed8233e3a2f51086e2c8e81da4c4f75b8.nq.gz
│   ├── c8d43d5b8d9131607facfdd1cc6fa93670e7ca85.nq.gz
│   ├── cd55bb2bdb29889ae086783b4b571421bdece5d9.nq.gz
│   ├── d1efac06bc724ecf2adb833113fad7097bb8319a.nq.gz
│   ├── d567ee686f734f3e0899a9afa7c3386284463a0e.nq.gz
│   ├── d5ed6c8fdb9af9b646770a4fd111a965ba06e0cf.nq.gz
│   ├── d721c65021a3e22ff5e92b27a46da11985f2936e.nq.gz
│   ├── d83e8c1999e5df949102611e684d73c05ebaf1f1.nq.gz
│   ├── d8b85924bc4b8addab0d52809892fa3fa89f920f.nq.gz
│   ├── d8d3bc72b937e7cbd6163ac4257ac62908e3a312.nq.gz
│   ├── da8a0b7e5eb6ca74a007af587ca67853e6e20fd0.nq.gz
│   ├── db18ed29d6ac948e406862e37b93ca523b26a00e.nq.gz
│   ├── dbd86744a7e1c8e9f38161e89e75fb434762f0ba.nq.gz
│   ├── de5ef8c20246b998d1f5fdc30293b02032511a5e.nq.gz
│   ├── df3f58e2aafe271048bca4f9bcb0bbdde4d5daaf.nq.gz
│   ├── e03113c51c30ff58918d4b119597824e1151d697.nq.gz
│   ├── e509364426f5ba1887dc8f0726eee1385e42b19f.nq.gz
│   ├── e5686142638e573520a67298885bf955163c0bbd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ef44251a6bd6babb37d807d8bc2afb2bd050fb.nq.gz
│   ├── e75cb598e2757d1b94283c6ada5c922c530f9c20.nq.gz
│   ├── e794c3eeef74d5b8e6f601810f98b57e376cdc1a.nq.gz
│   ├── e7cc2931c4fb1f8a870c05c80541a5a9221bbfae.nq.gz
│   ├── eb915d631d155200a7ee40850689dac5f82148c4.nq.gz
│   ├── ec6203f7bad1084e0db0871cc67a9a20429b7fba.nq.gz
│   ├── f710dd205e43bb2cbcf9815e473c1255734ed636.nq.gz
│   ├── f9d85beda19bcf54b580603c844a01427f56b552.nq.gz
│   └── fd03e6b8ad26a5a9964b9c3629b2999fcc8233a5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1e261b036686cd0017d500ee96acd1c4ba572a9d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 119 files
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

[snakers4/silero-vad](https://github.com/snakers4/silero-vad)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
