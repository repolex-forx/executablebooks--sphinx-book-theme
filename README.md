# Repolex Knowledge Graph of executablebooks/sphinx-book-theme

RDF knowledge graph data for [executablebooks/sphinx-book-theme](https://github.com/executablebooks/sphinx-book-theme), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/sphinx-book-theme
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3512c865a60f9975e38077cc6e15f30c049cf6ee
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3512c865a60f9975e38077cc6e15f30c049cf6ee
│           └── chunk-001.nq.gz
├── blob
│   ├── 0116b47c2c857036441077c61d8f672da06d3e8b.nq.gz
│   ├── 0173ae184287daf7caa31b50554ec161ba749506.nq.gz
│   ├── 03bbec8572b654ba2832269fba680e19bd5fa1f9.nq.gz
│   ├── 0593031a745e92e5bb3efec4b42bca75e7603a6e.nq.gz
│   ├── 0757b1c9a8f3e81c556b7ef19846e86a3f12fc24.nq.gz
│   ├── 089acbc2ac107de6b84003500b739c1f4b227f71.nq.gz
│   ├── 08edaeabbdf26650e7f96a6295026e6a99ce3f5a.nq.gz
│   ├── 09e821f6608940d9729857e544fad8f296f6b57f.nq.gz
│   ├── 0a393c97e2b88f4e5705bdd9d9fee147ccf5185f.nq.gz
│   ├── 0aac91e46c7df5c49bc662302cc900bed74c89e5.nq.gz
│   ├── 0d7f3752fbc7b04a6c15a9683d8c5b425244af51.nq.gz
│   ├── 11fa96e2e4f893d5eb5c3cc9d3cb8611cd4a7329.nq.gz
│   ├── 12c8c19be9a3c9c88eaec64bb2bad496455840ba.nq.gz
│   ├── 130959db83a34ef09f5ad144edb03ce9695ca515.nq.gz
│   ├── 1428a8286afe5abb1a9a4fa8544dc552da981736.nq.gz
│   ├── 152a86ef370108e3566da85313a78adcf9763bdd.nq.gz
│   ├── 1583f56c9c46b009bd66de71eaf49504b4c1a14d.nq.gz
│   ├── 163f953e0bde86b642994faac9ca569f25de009b.nq.gz
│   ├── 1647b2d63b97c639650a4e85bdea03c25dd11f00.nq.gz
│   ├── 17fef0631e479395b948a153e5fd9d31728aff41.nq.gz
│   ├── 18814ce574db455b830c35a2afaf624260411e1e.nq.gz
│   ├── 191a9ee82d9a19e1759648e9fb301f9a18f29658.nq.gz
│   ├── 19d24364268701a31bc1cdbe80f7dd661a82b40e.nq.gz
│   ├── 1d46757fb42f99ad11ca34a5e56d271e6a1b26b8.nq.gz
│   ├── 1e4a119b19d3ff933e10fe410a491191ac2bcc03.nq.gz
│   ├── 1e90cdf65f51f9cf4e41c7c944a93ae98ead927d.nq.gz
│   ├── 1ed2e888dc95b4df6412d84bfbf25cd0d93ea85a.nq.gz
│   ├── 1f3b4078c5d84bd24608e969cd873e25462366be.nq.gz
│   ├── 1fed6364aba5b4c8dd8fea60856c6889faf1e325.nq.gz
│   ├── 220d48a4a965a17789532f48cf91386870a61fd7.nq.gz
│   ├── 251fcddbf304b694a01cbca1c0f23fbcaf4a2c71.nq.gz
│   ├── 256f2a71e185cd03f1456b72c8cf14f6630fe406.nq.gz
│   ├── 27839f641d6c9e649c0bfcb07be958eb244841bf.nq.gz
│   ├── 27b7e13e386b090b6c318d47c133ce8bd3c603ee.nq.gz
│   ├── 286492af5317ce6c0b8cb8a027a4dc9059dc79b0.nq.gz
│   ├── 2a05f7ae194e4ddf5533458192c808d03b510c0d.nq.gz
│   ├── 2cc6ef83e67cc75adec03bce5d8dfea3eb53ff19.nq.gz
│   ├── 2d6c0f6317ae9e8cd60caf4eced47d9275c10a5b.nq.gz
│   ├── 36222d8b93c9d6f08e87e4710c19f0399b8224cd.nq.gz
│   ├── 36337b058d0434f094799a98de99a975d8cf57f8.nq.gz
│   ├── 37654b85514bbae343c3d627a90749f1eaea3289.nq.gz
│   ├── 39cad918e94ef5a982b2a233b4632d3d18052199.nq.gz
│   ├── 3a47807a9c0a00e6cf940d7660a15245a384fca1.nq.gz
│   ├── 3d07eed5be4b4df8536d9dca4a49faa628d93b18.nq.gz
│   ├── 3f3468eb0122898c0d86d0015ecc7a0a5cf8f303.nq.gz
│   ├── 40f521c838674d16194a454425e7b850451bcbc3.nq.gz
│   ├── 41ed332875d4acc9a1d1058307f500ba47e3aaf9.nq.gz
│   ├── 4335c4d8d3acbbf21430981c2a2a79305a154a07.nq.gz
│   ├── 45fecf75114bea0e1f22ce6f412d6729d894f893.nq.gz
│   ├── 462817b594e00311002805290c7baf78ba894a70.nq.gz
│   ├── 46a25c07f54bc1ea0c22e71ccd0b96b031591e55.nq.gz
│   ├── 46eb4d9b69ee97cb213f51df8fa2f3ed35bbc60b.nq.gz
│   ├── 495af2b913cc75abeee9aef3cf12847841a072fe.nq.gz
│   ├── 4a353189dcbaa413af15ecb542b47c1743f10281.nq.gz
│   ├── 4ad772c4688d0bb17300c1b12d36dbe2dd93f7a6.nq.gz
│   ├── 4cfd6c190b44bb6d9671fce210c1d4a971379b7e.nq.gz
│   ├── 4df632307800ae47e4d0f34c2eb62e43a03a7a84.nq.gz
│   ├── 4e2940cce90aba12ad1b287b03228618d336fbfc.nq.gz
│   ├── 4ef45490eb6083a98932cd57003fe4ec69ae53d5.nq.gz
│   ├── 50583a1efca7dcd3848a7c306179e68624b9e2b6.nq.gz
│   ├── 52f5daa6120496e3c15720cfd2415de46f996023.nq.gz
│   ├── 541d505d5d71119135b3f7ff28b2e0c7549df338.nq.gz
│   ├── 5557aa3052d0fdcef0dc57bf2af9271381886a8d.nq.gz
│   ├── 55f0716fb634fb671ee8a1d62083f4b4d6662b31.nq.gz
│   ├── 5765ac1a01e53ab2f916e2f4d67b6f700e5b55d6.nq.gz
│   ├── 5a83568fffc67fe6ed040062606c83ced8e21760.nq.gz
│   ├── 5c7cafc74b1fc5ffc86a1dfd0172e90d0e9227bf.nq.gz
│   ├── 5ca75abd87e39e165cbf3eb58d02509e6f0d2131.nq.gz
│   ├── 5d03e8c716d2abcb164ee0c8bc415c8c23ff91ab.nq.gz
│   ├── 5daa8ffeaf1103fe03abc29a29b43168aaa2fb8b.nq.gz
│   ├── 5e68689384d91bb28fba56f032b5131dd062d874.nq.gz
│   ├── 5ef0f0f1b6d1637b589510128c22b061b38081d4.nq.gz
│   ├── 5f188f6b68610cede80ddee7ddbf358ff8f32b9c.nq.gz
│   ├── 5fb1c9f0ff613546457552dae3e0eecc5aa165b1.nq.gz
│   ├── 5ff068f918fac10dcfc948539ca8f4af74348dbd.nq.gz
│   ├── 5ff45a7cd0f3d814a5e01d7ccc3c6588c39807b8.nq.gz
│   ├── 605d024662041adbf069cbd00d246b876b05e3b9.nq.gz
│   ├── 60cfe9f222e5617f1a4bc0de005685f7d8ce35af.nq.gz
│   ├── 6399c6462710f0b28c71e87b03e6e8b20a426bff.nq.gz
│   ├── 63f37fe83abbcc643c4b19b386a0829da01e4d51.nq.gz
│   ├── 649d6ff15e12018b0b6f4444e3db87f563b6f1df.nq.gz
│   ├── 66efc0fecd1554e6e4681fcb149692591f388bf2.nq.gz
│   ├── 6792e53dbbf7cde9690fb4422132db8125dbbef0.nq.gz
│   ├── 684343fe6849a75e84d61036f44585384eaa7ff0.nq.gz
│   ├── 6b39022a249ea099bd2eb3531eb2d70f48cf5a2e.nq.gz
│   ├── 7090243c7e5b61ed3e6d94dafb35ee31aa18dbb0.nq.gz
│   ├── 71cf2e1047109ae7eb54679da4e786b068d4e25c.nq.gz
│   ├── 74008bdbd32f59c7a765455eabd48412c7833af0.nq.gz
│   ├── 753676f081f399630b5c12426f361f327c6d1d47.nq.gz
│   ├── 75af2aa6c86e90f8bb842d15ec14a3ca1915f9b0.nq.gz
│   ├── 764cdb06e5de0f913afc00206568488c5ca1258d.nq.gz
│   ├── 77291a54a1d627045f4d408f1c51b8b3cef01811.nq.gz
│   ├── 7735652c649ca36d3e564501faf915b858933d44.nq.gz
│   ├── 7ac6fb85799117794b44844c7853140e4f777a1e.nq.gz
│   ├── 7b4a42e9ab50b4e72d811a40ef72b429775aba34.nq.gz
│   ├── 7bdb00733a2b197d328a4080570b29658c576443.nq.gz
│   ├── 7e2267d290154b68098f6cb62a688939d6ddfab8.nq.gz
│   ├── 7e66b559c8d39b0fb0009dae3d6c2b9128991f4e.nq.gz
│   ├── 80e67924418b0280dbb5d7a8ab4f764e1a1c9829.nq.gz
│   ├── 82679935b6470f08814ab1f50aa12922162be972.nq.gz
│   ├── 840515b12ba60320645f939e7969f1a4342cee8e.nq.gz
│   ├── 84cebb3fd13e08ea0332491b818a113ad4efe960.nq.gz
│   ├── 86386e16a419bc43f010fee04754bf28800ee209.nq.gz
│   ├── 8789c0d810b71fab4c9e5567ad3dfe63043a2a0a.nq.gz
│   ├── 87aae581d93c72d533245e8ea293050f0f47994e.nq.gz
│   ├── 87d368ca59f58d650279d44e3f1a20e65ba785c9.nq.gz
│   ├── 88ca0d5af969235b547374118e45cae3b31bd213.nq.gz
│   ├── 89d9ee428d747d715ffaa3a1b00859e6136e5035.nq.gz
│   ├── 8bd977c5b88e7c35087636a343088ee0a4e31e18.nq.gz
│   ├── 918543165437467da2f7ef3cb02a20a8b4df3b48.nq.gz
│   ├── 92369df83e1705360a8d5be3332804bda06c65e9.nq.gz
│   ├── 92b1a3331a6b2b48ed920b1017d7d1c9a8ecb871.nq.gz
│   ├── 9384340226b0e3c76aa145691aae283cf6b92fd7.nq.gz
│   ├── 96349c8cbb390b2c01b69ed428421fa769b07376.nq.gz
│   ├── 970578a0eabbd358d9a6fe8b9da82daa94c43070.nq.gz
│   ├── 9933978ca06e112282f5da83a36321800c3c590e.nq.gz
│   ├── 99685497fb900b091acd383fd459276db2e2b39b.nq.gz
│   ├── 99b4912a5208da1addee1a253d455ae31854d6db.nq.gz
│   ├── 9db579b0631c700fc3facb5057f988eea6bdc21b.nq.gz
│   ├── 9f67cab2b16324cfe77328c437ce18888d046ffc.nq.gz
│   ├── a3415b7938297acb72053a6c4969b575276f8755.nq.gz
│   ├── a367ead9283185ee2802dfc59c36cbf2a99a8380.nq.gz
│   ├── a458812c5252e50b8a88b17d4543eb8daca5b16c.nq.gz
│   ├── a488aa48059fdb2de7353e01283f1793cec7c930.nq.gz
│   ├── a78ac73fbcdf6b431b5124e421289876b72b348b.nq.gz
│   ├── a7daa4d406476d18450f67e8cf3a6145d319917d.nq.gz
│   ├── a8128758c9e8f7fb3e43ad848b7212bea40ba7df.nq.gz
│   ├── ac3195ee84a904c2d4c6b7d40c1eb2b631812f23.nq.gz
│   ├── ac4ff6e72f6da5cf7789ee51d26332f68371a694.nq.gz
│   ├── adaa004f6c44f4c315ff90e42aa8a98407f94848.nq.gz
│   ├── ae9492c2d11e4ea0945fe08e9601dd669e164492.nq.gz
│   ├── af48628e87fbc0be18953f6805d69df8ae8156b2.nq.gz
│   ├── af94df918ef7bf1ed7f2d06e26378a765e3e1943.nq.gz
│   ├── afa18b90d513f6712423b3436e5aadc28fbb6577.nq.gz
│   ├── b00257f90c589c5f3aaf0a1a6f339092f9bd5d22.nq.gz
│   ├── b0877ca81a84627efffbbf6afcd719e73369ddac.nq.gz
│   ├── b09f8fd6b3fa2464bef28d9f8aca4ece9340c028.nq.gz
│   ├── b539f0e63bef98271557cd3d43c316d71bc2d4d5.nq.gz
│   ├── b734c6387627cec5c1a641d3a3ecf4afd7101164.nq.gz
│   ├── b7560ec216b2d1b6f77855525fe966c741833428.nq.gz
│   ├── b8d00be4792b9e0ac9446a1106dadaff8ee7a1dd.nq.gz
│   ├── ba026a3ce07978c62f317afc859f086c7fb5b968.nq.gz
│   ├── bb6245b364e6b431942510270bc9e1a4c2057b4d.nq.gz
│   ├── c214ae50d977626389a6b5a3ee8020d005152785.nq.gz
│   ├── c3a9605762dbd3c4fa8cdf92d8c906af158e1a7b.nq.gz
│   ├── c52f46e77687f994547798d2e4d76acff0e7239e.nq.gz
│   ├── c8300257c190aca0d03cedb4ab65322f63023b76.nq.gz
│   ├── cf7fca71374ea9ed0c0dca523142fe01662593ad.nq.gz
│   ├── d0cb19f480aa94747913f5176af62bbcb1fc88dd.nq.gz
│   ├── d112824d2df991c465558ee301706c085aadf3db.nq.gz
│   ├── d1e7404e1a70171a971790db71212000459558ad.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d7d1fb2b78d808cfa6b8a9b096ab958ba7e17709.nq.gz
│   ├── d91dd4a88f7d8221306f3faabe4fed1455cb84ac.nq.gz
│   ├── d938d12285daaf3236e96ebf1b354ad2d06d048e.nq.gz
│   ├── da2b7923dfbbbcc03ddfb767d6c77f4d813af29a.nq.gz
│   ├── db3875dd4123861a315d5f7db69fac50fcbbc4b7.nq.gz
│   ├── dc51ce9f2e86d7b81006d52595139a987ef2828c.nq.gz
│   ├── dda9865ad01e8f6ecebfc69f0889c81050a594f0.nq.gz
│   ├── e2a8221a97d1c12d3252e6db7852c50b991a65b2.nq.gz
│   ├── e461959e6f824b193e115242b322d59f8e647254.nq.gz
│   ├── e6d02b57a954219435707d83c5a13897881025c9.nq.gz
│   ├── e979100d9f040ef1b68dd7625e07f415dc6304a2.nq.gz
│   ├── ec9d17ce61b33a6e9ff42a1ee8cfd3157f17e8e6.nq.gz
│   ├── ed14f712ccc7f69e63e0e5d51a93b59fb26efea7.nq.gz
│   ├── ee764281b80da8bdf7ab30a0a69d2b4f6b6f1206.nq.gz
│   ├── f04834001a14618a3928da376a688687ca9d0630.nq.gz
│   ├── f203aed585df96a858647d7959e77ba97f862626.nq.gz
│   ├── f412658a043e3326d1cc2e4d011831985386ba06.nq.gz
│   ├── f54b30eb95c3b57e93b320ed6d71e103c22d400d.nq.gz
│   ├── f6bcd0c6b5c6f5586ddc31fd86a48d0efac23029.nq.gz
│   ├── f6ecf7ddd6c0cb819f5d69106be548e367fe5df9.nq.gz
│   ├── f7f62954a985181f4c0b9e5aa723c8b42cbbb44f.nq.gz
│   ├── f958e61af30d37231f382dbc783cfe4aebac329a.nq.gz
│   ├── fa77ebfc258ac10ebdaa17a3dde4dfc75b8e8b2b.nq.gz
│   ├── faa68c92819d76e76d8ed5d4c037ea5c4de753cb.nq.gz
│   ├── fba522f4e5a51749a7b0d5c7dce5ab30ccd576c0.nq.gz
│   ├── fe7d6f4093965bc8e0b52ca5e3e33746c80e0940.nq.gz
│   └── ffa2a2aefd0bb6e4b040a1d6daf2def92e0299b6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3512c865a60f9975e38077cc6e15f30c049cf6ee.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 187 files
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

[executablebooks/sphinx-book-theme](https://github.com/executablebooks/sphinx-book-theme)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
