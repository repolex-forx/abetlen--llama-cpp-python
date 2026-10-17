# Repolex Knowledge Graph of abetlen/llama-cpp-python

RDF knowledge graph data for [abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python), parsed by [repolex](https://repolex.ai).

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
rlex download abetlen/llama-cpp-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1652066e0af45f2313b339670ef9555e8a54e545
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1652066e0af45f2313b339670ef9555e8a54e545
│           └── chunk-001.nq.gz
├── blob
│   ├── 02cee8a88f3ce37bd6b65e7f10085aa3e40e6338.nq.gz
│   ├── 047bc14424303575f73af90611fec827334f54e8.nq.gz
│   ├── 057ac389eb460a75e772fcdec37b04a7707ce6fb.nq.gz
│   ├── 08ede642058216ffc8f58b03255d7bea25e4f034.nq.gz
│   ├── 0b36cd9c3a2b4c19f5b9e024a54e28e0cb2f427e.nq.gz
│   ├── 0bbf20ffe9affde296ab9a746917891e977bc4e9.nq.gz
│   ├── 10043f9c1ac5cff36e3bbea0f9526bf4b98464c1.nq.gz
│   ├── 13128be044b82279b6c072ad800bd043b1b8e131.nq.gz
│   ├── 1375e1392d2b1752b9c1d3416717b99a11f2b07a.nq.gz
│   ├── 13c5b6b0df5f67e80cbe584909b83777901265a1.nq.gz
│   ├── 14e2f8500f8b156405d70267cd698c90e6ffe43f.nq.gz
│   ├── 18c7279cf058f42d643300c4869af5c71f6bf1ec.nq.gz
│   ├── 199bd4ffbf88c68c98b52c05f388dfa92716f6b7.nq.gz
│   ├── 1d8f9e398daadf7d54bacb8784e3937808f89930.nq.gz
│   ├── 1f2c59017718bbc1b662866327b713389c7a7bf7.nq.gz
│   ├── 1f413816599a944e591e9a3948dbeba15a351d22.nq.gz
│   ├── 22b2335a3e4d0c251f5d9986672e5185adaa0e8d.nq.gz
│   ├── 2325dd303b261034fb053f202156eeb2706be76a.nq.gz
│   ├── 282333e5a8f850bdd0056c1c4629e7c4f3523d4e.nq.gz
│   ├── 2b6fa759e0db0f4cbd5cb4b13453ecccbcca122b.nq.gz
│   ├── 2cced5a89b597ce4a657a72196cbc22ddec90b57.nq.gz
│   ├── 31d89d0995aca2e1d321747fb536ecf2c63cc8fc.nq.gz
│   ├── 34ef2874dfc7b9babb3b5e949087400a5020b539.nq.gz
│   ├── 37e1002e8d3fc6908ece1afd5b88dcfe37aedab3.nq.gz
│   ├── 39dfb903ba43d89c83c7b5b2f7d93502716bb16a.nq.gz
│   ├── 3a1d7180d508818fe957923e00dcd8950938632d.nq.gz
│   ├── 3a5cde9cd2882edf89aee7612b290dc9df87cf76.nq.gz
│   ├── 3a6457dcdfd47e764654bacae0ba8347976b645a.nq.gz
│   ├── 3fc8016df8a8804bcdcd70ca1866646bbfc22c3c.nq.gz
│   ├── 416cd0cddf3708b03edd25a1eddfdebedf6ad079.nq.gz
│   ├── 43b0b31bb86f288d353d4f31ed3be6bf81e3b803.nq.gz
│   ├── 474503fdfc554d8caabee4f321a80427f8c7d696.nq.gz
│   ├── 4c904da78cd1ecd9bc35dafed43490df1f0c6735.nq.gz
│   ├── 52061bea6742b46760ec8c227f714932551887d8.nq.gz
│   ├── 5220c79337cfc503089ccb1f50be26adaaa9949a.nq.gz
│   ├── 59dc3558bf8855d682e4edb3c5186fefd0d301ad.nq.gz
│   ├── 5c34e2729e5383dfb72f7cfbee994c51e70f30fd.nq.gz
│   ├── 5ece01e032b567b2fe7af9b9759c3948b8305552.nq.gz
│   ├── 5ee667dc0d40a7c35431021c9d83de625cc721e3.nq.gz
│   ├── 5f350ffe99abe7297b2839f36fd0eaeb98887805.nq.gz
│   ├── 60bc7aef42aac0409cfdca666ad2ff6f516d7b5b.nq.gz
│   ├── 60ffd2a987b3a5e4b82fd60a3de1fa392fb0ea11.nq.gz
│   ├── 62e2364157205e7684c901df122177478126683c.nq.gz
│   ├── 646f1f719486ba942653fde316f0bbb3aa447578.nq.gz
│   ├── 64aaf040d76d34727a509e748c1f2f8e403d425f.nq.gz
│   ├── 6bf90273accd8f1a0cdfcb2c740d96c1d7629edf.nq.gz
│   ├── 6bfacf279ca98b19400eed5fe190db4c22511c83.nq.gz
│   ├── 6e338ba17ef1ff9b2ad294d0e46121569a407bd9.nq.gz
│   ├── 70a4a6e04d3e2efc292f52e86904c970598356b8.nq.gz
│   ├── 70ae5389afc0e325d3297b74d1d459ff7f58198d.nq.gz
│   ├── 70fca5edb7167314fd0ffcccf5c476269db90f39.nq.gz
│   ├── 747c6130e3cb1479d20e2013b1dd3db3379c2266.nq.gz
│   ├── 78dd7cdeb869d5c29988c9b0edb7328e6f752782.nq.gz
│   ├── 7ee8f748eab47180cea09c0ad8e75c3b991b4af4.nq.gz
│   ├── 822662c3fb980f53acea0403362eba871b89a8d4.nq.gz
│   ├── 82f7a8a7de3ed688c88496e500b2711aaa29c9ce.nq.gz
│   ├── 835962449244285617ae81ab4a436e23b6bb2f6d.nq.gz
│   ├── 8448ac1f7f3cad79a75e9d6ff821621d3c806548.nq.gz
│   ├── 871d8b09b58a05c3034484f4d3e50cecc9d6658e.nq.gz
│   ├── 8908ccdd6f98a61cab1a1c16b1e88e65373266e4.nq.gz
│   ├── 892787ee1f749b41a2f3c12a3f06442fce12e68c.nq.gz
│   ├── 89c12958c9f12df7bc65e5a771587d25ebc3d8b3.nq.gz
│   ├── 8aa929202cc75089ceccca48b77bff9b4869e1bf.nq.gz
│   ├── 8e258b9c030d7b5da8b55c1f246d37fa024bf263.nq.gz
│   ├── 94e5aede3af12a3a931be1fe03bd559d60453951.nq.gz
│   ├── 9c09a1f1cfb85d28dc479cf236c44b341827bf30.nq.gz
│   ├── 9f2d087539728c9a30890909039b8424a4df65b8.nq.gz
│   ├── 9fb3424ec04662b4b7c2892417da471a125f1a90.nq.gz
│   ├── a0212ff0d2c9f9baf55936c291f968c7e04cdfc1.nq.gz
│   ├── a02ec5af519ca34ecaefcb532af40aa4cec68036.nq.gz
│   ├── a409fb882dfa2d461b1cd055e905d41475dd5bd5.nq.gz
│   ├── a4b424eb63f4f32010b191f6da3782f1443f9836.nq.gz
│   ├── a755089b2a0f4da1ba4638eda646d8067f7f2f23.nq.gz
│   ├── a9ca424d199dff37cb4a4a412e9f770505bb8193.nq.gz
│   ├── ab51ef754e969bcaff26f004b63bcd7251e97c4b.nq.gz
│   ├── ac39181f909563592f01bc52856d1fe38edfdef0.nq.gz
│   ├── b2819a244fefda6ed553591131ac2255efaaafeb.nq.gz
│   ├── b45d34b2c4054e0cf26e4ff4a5d5f09b9efa4f18.nq.gz
│   ├── b91632f5bc787c1404600c894a6a4126359747d8.nq.gz
│   ├── ba34dda831bdbb8599643ac86e07f68d3c79fcd6.nq.gz
│   ├── ba74e4a41faa179cae094576dbcbc409357b34d7.nq.gz
│   ├── bbac4957e92e98b400452ec776264ff53caf25f3.nq.gz
│   ├── bbcbbe7d61558adde3cbfd0c7a63a67c27ed6d30.nq.gz
│   ├── c02df9eed0904ec7e0b490d4ad44bff74d0a62ac.nq.gz
│   ├── c1c16e30ca10005c3186e7cd79932e92352673c7.nq.gz
│   ├── c525598530365f1e6d687d649907f0c2f116ab8e.nq.gz
│   ├── c5b42d8b72b25f55b9a6211e4936795744b7161b.nq.gz
│   ├── c85e73d2b657bb05ed99309615d67bac93d9f86e.nq.gz
│   ├── c931ead34d9cf104047605b46b8e5dc749bebcfe.nq.gz
│   ├── c9f2ca944a9f0e69fec8a08a5e54bb33de26e940.nq.gz
│   ├── d0eda5664ba583d053205e1e01c2f4365648c7f2.nq.gz
│   ├── d28c9ca9c6938517dec964655ad9c9730f7d80c0.nq.gz
│   ├── d306efde48cfbed3c86315c6b7577da3a9995393.nq.gz
│   ├── d3329eec3bac6ce7e54c76b77ac9bf99fab0fe3f.nq.gz
│   ├── db45246c798e038cfbb9a6ddc1d3f2b4abf93031.nq.gz
│   ├── e006fc0a3c23c2a6599ab1a0213db971dddf88ff.nq.gz
│   ├── e072ab1b10a8db83e59bd1e764c8d5cd93727c70.nq.gz
│   ├── e41f375774e6945e445bfb179502b128fe22dda7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea9b216f7d2a4e9e078eb0fc8782a9fc60b430e0.nq.gz
│   ├── eb0fb9662e690d0f9de4632cddd321b3f872a725.nq.gz
│   ├── eda2b92801233829fe1b68134aeb1d58e81446f9.nq.gz
│   ├── edf292387da6e24686769e22a0738a4f9b81513d.nq.gz
│   ├── ee59767d651ac114bb580919eb578ddac16cca2a.nq.gz
│   ├── ef8b1c1eeaaa849caf3b908ff17f866d7bcacea2.nq.gz
│   ├── f05e66ef2a031ba8ff2c75f5a1074178b2af332c.nq.gz
│   ├── f56cca32df056033cc3de47757fcfad6ee0070a7.nq.gz
│   ├── f647822ff55a53965ef3c8a1fa51fbcb84ee3278.nq.gz
│   ├── f776fe159cfa5f8828aaf06f15e33c1fcd54aae3.nq.gz
│   ├── fab82673e5fa1d38f07fe7467c372e13fd7cabaf.nq.gz
│   ├── fd64c09b37947c97e58903ce570785c657d56722.nq.gz
│   ├── feb0ed68d94eac48b844fd587ddfb808649716a1.nq.gz
│   ├── ff3e950cd1110fe552912cea4c268c4023d2b737.nq.gz
│   └── ff773c668415e603581c74c0cf539095f737d5ef.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1652066e0af45f2313b339670ef9555e8a54e545.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 122 files
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

[abetlen/llama-cpp-python](https://github.com/abetlen/llama-cpp-python)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
