# Repolex Knowledge Graph of vmagamedov/grpclib

RDF knowledge graph data for [vmagamedov/grpclib](https://github.com/vmagamedov/grpclib), parsed by [repolex](https://repolex.ai).

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
rlex download vmagamedov/grpclib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0d27158f98aa939493009e6844576d81ec7d8254
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0d27158f98aa939493009e6844576d81ec7d8254
│           └── chunk-001.nq.gz
├── blob
│   ├── 00075030225bbecbfbba39f80e32e108f65b10c0.nq.gz
│   ├── 0013ec965de9f73ab9300fce0c46687884ac95fb.nq.gz
│   ├── 05a5ce349166c7f61e9e7c555b96d34319472ae4.nq.gz
│   ├── 08c692f8cc46cbce9270970990f604ce2e62d028.nq.gz
│   ├── 0914fb9dd1f07a0cc7f350504ccea35ee0505f1a.nq.gz
│   ├── 0955490794d8b3400dd1846cacedbc43db0036e2.nq.gz
│   ├── 0b265dc7ca7b422eba012d18fa82508eda4060ab.nq.gz
│   ├── 0bf6149d7d72fd4e32768e0e6b5df10e3a02052f.nq.gz
│   ├── 0e862d03152364f9170db9cd83e0c406f88eb0cd.nq.gz
│   ├── 10715404c02b9b96658910b15b5339df1e885ba5.nq.gz
│   ├── 1094003f1cf399bc375d5dee1721ccbd92b3a6b1.nq.gz
│   ├── 121a39f5f2396a29f551d56ecbb2214d900120b6.nq.gz
│   ├── 140d2e850a572c5b82f69358a903e69605bae4d4.nq.gz
│   ├── 15b7fd41dc2ac4f52edac424d91c32589e4ae713.nq.gz
│   ├── 15c68f1c05989d2fa71369381adf8b5f4e483dbd.nq.gz
│   ├── 17b2c1a2589104ddfc144c8dfef90f368dfa2c4d.nq.gz
│   ├── 19a27f22cb9568b78a0ae028d324a2e793fcbe1f.nq.gz
│   ├── 1a2ceedc3d2810d317cf8c7f1bada0852b2d603c.nq.gz
│   ├── 22ccc907642a1606f786cb78da8e6c73dd313827.nq.gz
│   ├── 24dbc56003938ebe483b4c96c2de2b916da580f2.nq.gz
│   ├── 270ad2e890cc0aeacf59c6843c8cc0def9b87f11.nq.gz
│   ├── 288debcf957b93fa61318db75b8b6ba15a65b52c.nq.gz
│   ├── 2daea87259c965375dd6b1eba956f57b1930eceb.nq.gz
│   ├── 30fa88e5288dc83817138762470ec3f06430723f.nq.gz
│   ├── 3163a0b8401a1c829bec5e9fa79304a211aaa570.nq.gz
│   ├── 386f4ac1bcd560c9a992092c59ee524ce777835c.nq.gz
│   ├── 38843ff1e73ac3ad339b16f551c9b9806a7f02a6.nq.gz
│   ├── 3d882bab79bcfe4153e9826f625ed6802ec385f2.nq.gz
│   ├── 3e32c3837427a8485a9a261305a291cf515231de.nq.gz
│   ├── 3ef13565a95afd6e471a8e74c63729b2660651e1.nq.gz
│   ├── 407a746bcb13ca72b0d87e5d258a870183d1b621.nq.gz
│   ├── 42816ae304b8937123bd01dae66f8e8d1b4ad60a.nq.gz
│   ├── 42af448a38e73bad126782e6ce945f11fffc9f06.nq.gz
│   ├── 42ffb9cbbc90f70e115649b1fac3465ea763a02c.nq.gz
│   ├── 4a0a442b281b1480eed5639f7ec35354710e0758.nq.gz
│   ├── 4a328717439530cc45b8d2cc956bfe991f188691.nq.gz
│   ├── 4ade3fa3e4449e6a1c15d97247f793d96640248c.nq.gz
│   ├── 5649ee03aebfcb82aae810deb23d8b0ce2b5566c.nq.gz
│   ├── 57474999b302c12cfaeb73a74b26209760171431.nq.gz
│   ├── 57c07884213ed5232583540a24b93a52ca9d5f8f.nq.gz
│   ├── 57e4a2728d38cd4b99dc2c689620cbf52ace10cf.nq.gz
│   ├── 58bca88811bc3c977359c6f6ee7344ea973d2c90.nq.gz
│   ├── 598d2f2afbd56b449308d914e8205e5f9ed3fa9a.nq.gz
│   ├── 5b2b89a3edaacf1e4323c7aaa036f31b5c6d08aa.nq.gz
│   ├── 5be9f26de6af333eb67a20b404d44bb3e0c29177.nq.gz
│   ├── 5d0c8e9ebb80bb67adf84f21ce26922f5b91f942.nq.gz
│   ├── 5e192d7d3bd361f6154dc3805f90ab320934b581.nq.gz
│   ├── 601106a30c39a163b518bcb7c004b2fa7cc712b5.nq.gz
│   ├── 61a94a731348b5a7a4d9a626dbff189ada6aa7fa.nq.gz
│   ├── 61fff76ed564c1a707d5068e8711d47db5af9841.nq.gz
│   ├── 64ce881fb38735c45079201d12643437cbba5e79.nq.gz
│   ├── 66f8610061a1ef4082fee164683a438934dfc4a5.nq.gz
│   ├── 6a5b9c7fe24c820c0bd940c8c3f64f914fa926a8.nq.gz
│   ├── 6b8d445096d102c9d74ab835e95e0e30c1d5a2c7.nq.gz
│   ├── 6ca7ab95633371ab1b5d4b6afe91ee97dad430fb.nq.gz
│   ├── 6f8d5afcc0054c99189cfa8de19745fde0a836c4.nq.gz
│   ├── 701a6b1e032826fd97aca5d72e23c4061200b262.nq.gz
│   ├── 72e7066943a1f80645de8c9a78874a0c32a973fc.nq.gz
│   ├── 7563c04e3814e078491bc00089ad1eab04e1be6c.nq.gz
│   ├── 75adeb5cbc7bbc6a2b4aa13731ece6facf787b89.nq.gz
│   ├── 76694bd6e3cd4b601e87e987b18934350f0ce67a.nq.gz
│   ├── 773733cfd645b226c5edbbae727e69f79d8bd5c7.nq.gz
│   ├── 78a93a94ffed3c8c41185b7d354b5e2eb60f351b.nq.gz
│   ├── 7b51cc7a1ad34c81935de8be67496b69b67a3f94.nq.gz
│   ├── 8c5e06fe1485d92bbb56d08c1709e3ae46d9c763.nq.gz
│   ├── 8fe7d7453fda953689e1441b6a5127fd8808a279.nq.gz
│   ├── 9132b7c8143e060a2d49a0d834a6b75b2496e3e5.nq.gz
│   ├── 92f7abaf81d5c49cc575446b4f420835e7b98608.nq.gz
│   ├── 93503c2c90ef847bd0362ef831a0e02876d5f8aa.nq.gz
│   ├── 965fa951d32652611f0c1f49069a74b03f88c785.nq.gz
│   ├── 999cc3cf259e3f51bedccea64d98acdbeb2c423f.nq.gz
│   ├── 99a93bebbabf4ec5a7a197a295bc7efcadfc99fe.nq.gz
│   ├── 99f120df571aff3159614fe8c1f70d3b3364b58c.nq.gz
│   ├── 9b37f3f2cfb35c5c452955696a2f28b931ce4354.nq.gz
│   ├── 9e59798f4d959b43509858fa69873e7a38267113.nq.gz
│   ├── 9fdcfdc83e7807ad6e17e67ec86ee1a44633a839.nq.gz
│   ├── a076c3351a449532ef4a4fcd44784bfd6ce47995.nq.gz
│   ├── a292f311d3779081102627704fa3ee9bcdf52537.nq.gz
│   ├── a33ce1eba50bb19b6d5976dda12f63702c4d706f.nq.gz
│   ├── a3d53cdb1cb70d3b2055ef570f34aa7e90d44fea.nq.gz
│   ├── a6717b8ebe0e0732a94cc356b0dfc0fe15eeb1d7.nq.gz
│   ├── a929508774c5d2ac60c766ce7b2ff85e9066ac05.nq.gz
│   ├── aa003ac87dfdc274470906ca5de179296cc83eb1.nq.gz
│   ├── ab65f717ae5721c0e5233c33a46e42e3565eb716.nq.gz
│   ├── add9321c491090abed8f2b0a940f85e0400e2f47.nq.gz
│   ├── ae266300876444c8aa51bc44e87372ebf7b2c2b3.nq.gz
│   ├── af045818860adb9e25ef14de1378f8b15967f012.nq.gz
│   ├── b29cea236b43d3300027072c12109d1926030693.nq.gz
│   ├── b764e2c75aec04c8e51bf5d030701bafbaeb580c.nq.gz
│   ├── c0a0e82313eb1e24493becf5bf0f001000d31328.nq.gz
│   ├── c256f7d0d09fb28b067cbaf06f4545f73de0331e.nq.gz
│   ├── c4214030ac123e28b7efb16177433cfdfd0937a8.nq.gz
│   ├── c43d6f7097c4cab4bacf8e2ae63924a661cfcda4.nq.gz
│   ├── c60cd4198ec4546b9a671a7883cf8a1bb077dc66.nq.gz
│   ├── cb0f66f98d65aeefea3416d08bf82afbd87b91f2.nq.gz
│   ├── cd14661e7b7f2377336082b07cbba5009715988a.nq.gz
│   ├── ce44d6ec446dd4b36495fcbdbbdce30ba2485698.nq.gz
│   ├── cf6000aa7d6f5fa101eab62680b9babd75eba7f2.nq.gz
│   ├── cfb6eaaa9a8a7f1fb88f9cce7ebc6f26bb6e8d72.nq.gz
│   ├── cfd6373dae714b4e43d5fad18d539d9befcd7ce9.nq.gz
│   ├── d0781094ea8be55a6b0ea968c5ef75d4c1998140.nq.gz
│   ├── d48808bdd919b0d5f9c56c34c018a1c2382c016c.nq.gz
│   ├── d4bbb7bba5fe0bfdfe7655f6e28f2fbed14ef898.nq.gz
│   ├── d4cfdcd6e0af87bed067098701e6210be10348a7.nq.gz
│   ├── d4d5821e572c554e170bb8a1cd51e616e2c731e9.nq.gz
│   ├── d63fbacc3580b813c7b37226ef9db4e28dbdf896.nq.gz
│   ├── d6a93f67955f3a8ee15a73fd00672ddf52d1ed6d.nq.gz
│   ├── d8109a7b290e76115414e547e49342b69512fd50.nq.gz
│   ├── d984b98d75c1958fb33f31dd64d930b96471c7aa.nq.gz
│   ├── dae3849405463c374737789bb35fcdab1e3dde3c.nq.gz
│   ├── dca364584dce9849b28001f2bd17879bf7b35bff.nq.gz
│   ├── dd546fea1b652db80f5bcf423cb1226dadfa14fe.nq.gz
│   ├── e0ebacbc13e30d86772bacddc48183870474636e.nq.gz
│   ├── e27eefa9b1ae0c11107e3bd82f255db6a94ff9f2.nq.gz
│   ├── e2eb7535cf8f2369a5f1b17e27fc7b6150e68ed4.nq.gz
│   ├── e3476257d6552b55d6588494f31968019ae52730.nq.gz
│   ├── e4f956b9758bb37b3f2f0aef4914935f13f42dd4.nq.gz
│   ├── e569631be5e8b0512ed2d8dc9c2cc2bf5be26f04.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8a7cc6dbe3b11e24da065793d9eb2eeacd5769c.nq.gz
│   ├── ec7865a0a321abb2a4783a365205165face00d28.nq.gz
│   ├── ed61f9f1779d7b10862a374e7c04ce6d049ec771.nq.gz
│   ├── f1459b1be3ada7bb0e6f653948cb991bc7a8254b.nq.gz
│   ├── f325d1e40f4d1c0502b0bc9f9428fb6f115dd9ba.nq.gz
│   ├── f7645e95332d353f3d6b8955c72927bfe7500399.nq.gz
│   ├── f7f762a365ccaf1e254982cb24ffeb96db2bb8ae.nq.gz
│   ├── f904c1eaf1384b56d10779873c039e5723763d8b.nq.gz
│   ├── f9aa5e4e7b5cfcf968af9c2c3bc1ed30ecaceff8.nq.gz
│   ├── fa564df5f2f55108b1b64b5e19a2e3915585784a.nq.gz
│   ├── fce98a8f5a644282db3241efb3a2fbfbae9f0f9d.nq.gz
│   ├── fdd35bcf36440a483f165863a38b4926918f9981.nq.gz
│   ├── ff16537b3d30437ce6c66a25a6a0e8b3e19f2db5.nq.gz
│   ├── ffa57ec4f0314a182d161d7422eb76c4e3157609.nq.gz
│   └── fff06f6faa15148ed087572af7427e9b9dc2eafb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0d27158f98aa939493009e6844576d81ec7d8254.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 142 files
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

[vmagamedov/grpclib](https://github.com/vmagamedov/grpclib)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
