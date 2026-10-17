# Repolex Knowledge Graph of Lightning-AI/pytorch-lightning

RDF knowledge graph data for [Lightning-AI/pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning), parsed by [repolex](https://repolex.ai).

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
rlex download Lightning-AI/pytorch-lightning
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 84df182f50ab34301aabb3c0eb4031815bfb413d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 84df182f50ab34301aabb3c0eb4031815bfb413d
│           └── chunk-001.nq.gz
└── blob
    ├── 00244e53c09ebd2449d3d22f10cae41bcf358dc6.nq.gz
    ├── 00484009481e9fbadb801ab49f7df7e6395eb57e.nq.gz
    ├── 008d47fe256cadcd6fa32758db077ad02780347a.nq.gz
    ├── 042532f968e7d2796295feced41bc3d05c012d43.nq.gz
    ├── 04b95443ce6028801009b4b601a2aa5525d442e1.nq.gz
    ├── 04f6fc23aa8dfd3e457665825ec0db68e64a6be3.nq.gz
    ├── 06425047bffba2f8de45221be8ddfb146aaddcd6.nq.gz
    ├── 0718dab78d75f04441a9249b3e1e65d177b36840.nq.gz
    ├── 078f089b97305ac40d41a3847d0a504acca61695.nq.gz
    ├── 079ec5f27a6c29decc25fde204e63c9a0e153c99.nq.gz
    ├── 081b1875361507385a662ada4c56e49aed295d09.nq.gz
    ├── 082f8e2c52163730de2b32a56c530be25a84691b.nq.gz
    ├── 08a0230f759cf7eeb37e434edde7a884ef2dcd19.nq.gz
    ├── 08a9b20b357f6ef686a64c271ae4bc8def8624f2.nq.gz
    ├── 08bd1707b5cfdfef0cb0a71bf5617c1c49e86025.nq.gz
    ├── 08d9f9ac8f1ca1e02dda83c11fad2a7a084200d0.nq.gz
    ├── 093346f96882274c046052c20d676983716272aa.nq.gz
    ├── 09879ccc593210956941216387467fbf7ac644b1.nq.gz
    ├── 0a977db8111f648da65e87ea0a1e401e1373ec16.nq.gz
    ├── 0c5a3edc6faee3cece2783451118e9958ac7bfa7.nq.gz
    ├── 0cc56b59bae19851c25291b0380e0078e70548ad.nq.gz
    ├── 0d5410d71e8b897a81d8c0e7a80a4b7797cf9f0c.nq.gz
    ├── 0d5aefefc816cb240f02d5a2070084dde42717ea.nq.gz
    ├── 0e010ca53ddcbadd6e3e5ea80c7ebb3a5169196c.nq.gz
    ├── 0e4590cc76f0112bcc356f6541ec7c06fb4eb9c2.nq.gz
    ├── 0e4e5210db60cab90126bf470fc997ecce43925e.nq.gz
    ├── 0e8010a78c0ef5e4314f14f4fcc408ef4fc33025.nq.gz
    ├── 0ef19335709e9b98d9822ad5df5937a600e00110.nq.gz
    ├── 0f19349f7a0fc9fe6eda895cef1d0a4c63cb3e53.nq.gz
    ├── 0f41c5948fb463c87b4666d982a70dc6884f6afa.nq.gz
    ├── 0f66f215f686456858c335c4fe48c2dbdfe0bb45.nq.gz
    ├── 0ff82c88a19bb6e0394b9f9d1d1b897dffed963d.nq.gz
    ├── 124a9120a9197fb836ee54c03fd6728474516308.nq.gz
    ├── 138830e4e3b1b304cb5f371c99836aba7cb69542.nq.gz
    ├── 13a15e1c95ef569ee0f11b60b376df4e3675d1cf.nq.gz
    ├── 13d61d121ca8f9af6fdb3694c495aa18f6ca2448.nq.gz
    ├── 13d90708cf3d1f75534f51e9c8931ca4780ffbb1.nq.gz
    ├── 146fa2f33b5108a535879ea049ce9ee2b63d8519.nq.gz
    ├── 171656d072076ff72c07216454a4c5527d5daef6.nq.gz
    ├── 17cbef6a76faa4d99979f11f37c6d2a47bf65774.nq.gz
    ├── 193e6495a418247aa4590d1ffc39f6ab6b1548d5.nq.gz
    ├── 195a9df478f26f4ce4b5741ee4f1611da8968924.nq.gz
    ├── 1992d8a2d3d09dcc1594f50171c1a9b54ca236cd.nq.gz
    ├── 1a23efd9191719e04b731673341680fd228fd611.nq.gz
    ├── 1aa6419969b5cfae546ee5f82dbdaafd2b584c65.nq.gz
    ├── 1b054ed6715f7107e740a233d9a215dbdd718354.nq.gz
    ├── 1b1768ae1872b7292d2dd6832a7a6109b0c5fff5.nq.gz
    ├── 1b56453220edd15e5212c9866cb3b2fbfd4ad0fa.nq.gz
    ├── 1b842ca610077b092b1a256d77227f6262314216.nq.gz
    ├── 1b893005a91f10149c67a315bbe3a0f21d76786e.nq.gz
    ├── 1c9b646936a15d65969549fd8401371398fbc0a3.nq.gz
    ├── 1d07f3e99d412e9859c96d0eeb9732fe0da2d2fd.nq.gz
    ├── 1d30130aa6da3191242f3528f8737be7d03b53f0.nq.gz
    ├── 1dfab2a7bc649b6206a2100fd51bfde1baac2ad1.nq.gz
    ├── 1e01297248ffa1945012b4951cb5fd0291f46485.nq.gz
    ├── 1e03e2fdfde9598328da71f3ed76ab4b104a1277.nq.gz
    ├── 1f4320be1c30c62e73f9204409dc2bbbd9fa7b58.nq.gz
    ├── 1fb4760ae8b371f077c0f7d4080f0ba691c731e7.nq.gz
    ├── 1fce7b06887cdc56d0705bfd3be2362596d67ae3.nq.gz
    ├── 20679c52394c09f0a43ea1bc5aa605faac9d4d51.nq.gz
    ├── 208244dc38cd3fee57ba8d765c503b4ab620f99c.nq.gz
    ├── 20b418437c6819888018bfd40053f3f069d3df56.nq.gz
    ├── 2121ce915c9ea42548393f863fa7b23d37f57439.nq.gz
    ├── 217b76106aea99f55f31db5ab6ade617d896dfcb.nq.gz
    ├── 21cb198b031dd95b5c877ac8e1c9fbf3b75aa179.nq.gz
    ├── 2205317d232dd07f16292cb44f420b429b542d40.nq.gz
    ├── 226e3fcf77afea52487bd66b5ee09f36d8fa1678.nq.gz
    ├── 227727d954fcb4f9b24d00ad18735c388cbc56a4.nq.gz
    ├── 235d3a6794527b84b72c41d6ee9b8369b75c446b.nq.gz
    ├── 23b972418deae8ac8569933315452faadbc193f0.nq.gz
    ├── 23f9258b0d56bb4937093b9884ae88822027570c.nq.gz
    ├── 240dae6296c1f5ebb7b46f043a2cf2ad146cc691.nq.gz
    ├── 241d624483b1e9b6804c93ce31a6b4ab592240a1.nq.gz
    ├── 2543702cc3450950fb52e14d3cc0beec6c5f934c.nq.gz
    ├── 25602cc3a95e433b15663e8965dccb5cae15c473.nq.gz
    ├── 25cf5f9dbf52c6a41ea46d01fa63eee08111f3f1.nq.gz
    ├── 260e5adda00bf56597850737896c5f1621958c8b.nq.gz
    ├── 260e7934a28a64b29c106df201f7c02dd5eb676d.nq.gz
    ├── 26e8ca54e30791c332e97dbf3ce2a18edbe340e0.nq.gz
    ├── 27184d7b17afb91ac13425aedae6c72980df766d.nq.gz
    ├── 276af8b8eab72ed2025d5699b06434665cd6b780.nq.gz
    ├── 277971d64b180d9bd15cd3a9f0b239d3c44335a8.nq.gz
    ├── 27c1dfbe9c105d89a16f914be202fc0c1c0e8a13.nq.gz
    ├── 29763fc40240730c4101881569279f2d6c1adece.nq.gz
    ├── 2a11b7c66c7729537aa442ceb20a3e10a4bad008.nq.gz
    ├── 2a5e2f3a85b96b31951db97b675e0bffe3ccb5e3.nq.gz
    ├── 2b2aa302024bf9a6398668b8af4d5f85f8dd901a.nq.gz
    ├── 2c25289ea1ddeed46038fb7e7c1731c86056dca6.nq.gz
    ├── 2d21e9fe9d11332aca402b3f17846fab34c2e62f.nq.gz
    ├── 2df53b216a65490a258ca850452079078b8b3080.nq.gz
    ├── 2e70c4b5c00c95b021d2534def621cc78a72b7e6.nq.gz
    ├── 2e8c5899020d999bdca6f066cd10ef2262f22f2c.nq.gz
    ├── 2f6a2573335059e1fc6ab56fb496865f0945b000.nq.gz
    ├── 2f99f69fb30f5d91fd54062b6acd7807bee9bafe.nq.gz
    ├── 301721e4b28f5a24aa52c5beb0e68cf4f6940e79.nq.gz
    ├── 3042c318cb4aab9f37e15619941198669040138f.nq.gz
    ├── 315ca5aabee2a494582d0ff8a4b14bbc888ec627.nq.gz
    ├── 31cc5976cfe096287f0e500d89e6ff32da075e5c.nq.gz
    ├── 31d6f0399efa9cae0218c0799c814d17ddd9e34e.nq.gz
    ├── 3272f7f87d0fcb4951becb013d2747b2c238086f.nq.gz
    ├── 3315c328b62495b81a5fc2f6043711a08230e3c8.nq.gz
    ├── 332c9a811e3e43542f0f0bc9d72940e2496990ab.nq.gz
    ├── 333779df71a38ca6acd5696a63c31590e576d528.nq.gz
    ├── 336a9fafa324391bdba528e98d81fd573bf8a672.nq.gz
    ├── 3426c3e51f41dbc3e06820fea6cb4bfb6ee251d5.nq.gz
    ├── 34e7b83f69600cb213e8a674a407b98638916646.nq.gz
    ├── 34faa141cd09f17ad6f62795bc3762b0a3744f78.nq.gz
    ├── 35a9dacae766dc1d99c49080c1501311027bb3fa.nq.gz
    ├── 366aaecefe7e49e2e3b6158e99d58f1bd3ae6aef.nq.gz
    ├── 36b1c4099b17cba4afce574b8e59e710eb8a554c.nq.gz
    ├── 3789cb079915fcb015beab0c2516f7d9554d3096.nq.gz
    ├── 37ccbea5e6c950f6d3e85ccbcfaeb7c5d6650497.nq.gz
    ├── 380f8a0cf1d96ba073bdaafde197b0fb1ba11097.nq.gz
    ├── 39a9fa06a08d02a745718fb5cf2340759b990d26.nq.gz
    ├── 3a275add9a7317e864a2a39d4d28d508326f8fcc.nq.gz
    ├── 3b2ab99d015c16334f776c8a327504403e578c35.nq.gz
    ├── 3c10da7de40de44cf17a09edfef83d25d1a32d28.nq.gz
    ├── 3c18f80b89aca33c90eb699165ff44b4e3ccb8cd.nq.gz
    ├── 3d4b43f75c762678badebf077fd96be26f92fb29.nq.gz
    ├── 3df0000cf2766debeea7a99b1a5021438898e2ba.nq.gz
    ├── 3ea1f621c7ac3bb575a3df08fc35ec00ccd6e313.nq.gz
    ├── 3f8726b7a7fed95c2c33400c6dc718d2060d1756.nq.gz
    ├── 3fde2600c948325c9a89c0b620fc459f2bb3db15.nq.gz
    ├── 4003dd30dec09a7bed9a3adda3b6b583dc93bc05.nq.gz
    ├── 40494226f3a344dea5339841f9f3cbe8c79c406e.nq.gz
    ├── 404b0043dd0c9ea73f7d4b220059dba0bc464b6e.nq.gz
    ├── 40918ec0011d9f8f1240a10d5bf1fc2a47dacba5.nq.gz
    ├── 40ff5914301bef23d36d7307c38572f8e5110398.nq.gz
    ├── 41036e3270c7b26b59c052ddefe61ca0a0af0c85.nq.gz
    ├── 4137d1ae95e1e1c78c952741bc1dbdc1028e1ae4.nq.gz
    ├── 420f711678808aae41ba05c7507c1df3e15e264c.nq.gz
    ├── 429d3e8257d94ff8b24fc451da6bcecd67361021.nq.gz
    ├── 4396aa26e908a8d54a18dc5bc233f29c13222f33.nq.gz
    ├── 449484da970a862a76a75c510189f44de31c3d14.nq.gz
    ├── 44a0c85184d9eebe62dfe14556569997ee2dbf63.nq.gz
    ├── 44d55c8da1cc948ff12e4bcb06767b3b4fc06ad4.nq.gz
    ├── 45f6705f3cc9b6fd04d4a75d1729e3c943356c3c.nq.gz
    ├── 4613b46a436340dd2192738aa718e894e5982181.nq.gz
    ├── 482db1324de2e712976b641e5f979403becacbac.nq.gz
    ├── 491acd4398b30267e2a672317ea2ffa19535bcfa.nq.gz
    ├── 4950bed292dc15a0f48e3930fa71085c5726c4db.nq.gz
    ├── 4a77e4717da2dfed983045dd433431261b29b2a6.nq.gz
    ├── 4bad7885028eb1a92f20f022ccf624c0fa64d248.nq.gz
    ├── 4c5b3bb6b471277ce0d8bfaa014bc7e5cb5eea5f.nq.gz
    ├── 4cb0671e357b42cefd95a852707756cb94bf05d4.nq.gz
    ├── 4cb55c4cb68d8e33880486ee2f86744ecd766923.nq.gz
    ├── 4d683c0c0b0d85b093f6b122f34f4b5b8b4bf53e.nq.gz
    ├── 4d98b7ed6a8ebd4edf433d1b0dab915bdd2c85cf.nq.gz
    ├── 4e803b4f7d940770cbfa37ad618dd0f4adf75143.nq.gz
    ├── 4ecbc64d7be0c2f14fb51c505d9bedca8279af0f.nq.gz
    ├── 4fd22e39babc5c28536bbdb63691d539a8c860b1.nq.gz
    ├── 50ddc10f0f6611a45c7c5df70f03e2155f7d2416.nq.gz
    ├── 5135ec214b1de721f607f59f8471bf9ac6865aab.nq.gz
    ├── 51b7bbeedf90bdf49f8bbb3af89a55f3e3176e2d.nq.gz
    ├── 53229f1eaf94680cc11a29b264930b4da64d33ee.nq.gz
    ├── 532f0f9b8ca94a29c3784ad46d9fdb9501bdac2b.nq.gz
    ├── 539b7aa8a01dcae23b1387fa7fd2e5b3511159b1.nq.gz
    ├── 53c14cf5afd24b397e78ce1b1c95a0a3302c0715.nq.gz
    ├── 54518491a3446d94611851320fd71a5b45692186.nq.gz
    ├── 548bc1fb15cacd84f2aec036138e9b2cda529f29.nq.gz
    ├── 54a3a68285c22703af8890414ac0f64e042bcdab.nq.gz
    ├── 54c0de7297ac54dbfe7429bbea3b1f051ce72779.nq.gz
    ├── 550a0a0fb26aeb970213f0a7e6711762cd124bad.nq.gz
    ├── 551ea2172175417a610a4035e9812984982d2270.nq.gz
    ├── 5560388d6e61201a279ec8cf3bc128292ef1d858.nq.gz
    ├── 55eb7a4dd8871312938c9b962d43894b583cbd1e.nq.gz
    ├── 563c2b1e043b2a0df924e45252ddd755ffc308e3.nq.gz
    ├── 56e3b19b3757756866eaea97ff88532139903cab.nq.gz
    ├── 580d1db6769decfdad064a7a63faba6e5b36f535.nq.gz
    ├── 5ad7353310af402169240bd07c0ca6824beb93df.nq.gz
    ├── 5b24a63e7ec23d55ea165afd31b6f5d7033fb513.nq.gz
    ├── 5b408f3971df73fe57fdc996b328a5b0c0a4a3a7.nq.gz
    ├── 5b72d60491df7745a4ad4035982a899c9b898d85.nq.gz
    ├── 5b7f8798f47a1ef1317496e67aee0695699fc661.nq.gz
    ├── 5c536cc739da062587d0acae6c74f08e4db83d66.nq.gz
    ├── 5c750e263d761848429ece57269ffc9885241cf1.nq.gz
    ├── 5d10b62e633acf5be304fdde2db6740827c50369.nq.gz
    ├── 5db942b29183f5f8429b21a225674815f866a904.nq.gz
    ├── 5eeb2c68f9e683c649325b0daac9d6b66fe6ee50.nq.gz
    ├── 5fe29464caed8a8a6d84ae70a496c22889a8ffa6.nq.gz
    ├── 61034b7c243019c15d317d83eca7ab785c1ae347.nq.gz
    ├── 612bd8f74a6406bf78a22c7654b18a64d42065ce.nq.gz
    ├── 61ede2786ddde04d365cf5dc58fe2f63d3a07301.nq.gz
    ├── 62025cece6c8388d042012dbb372546e94b48496.nq.gz
    ├── 620e8f88eb1190e9771d38c822644ecbfc2e9488.nq.gz
    ├── 6212bfe264e6ef59cbe57edf9d71cd606b877644.nq.gz
    ├── 6293d2cd6484efc3a0add60d254afb6693e7768e.nq.gz
    ├── 6322698ef3b734dafa8c434c372d1a3e2d729710.nq.gz
    ├── 63657ad677e1c92ffc6da55daf383e875ce00fb7.nq.gz
    ├── 6373985687ad306f5250faba2b32f0cf6ade2edb.nq.gz
    ├── 63b05a0a131f2b316ed2f339ea0aeda1fb5af26e.nq.gz
    ├── 63e42fd23b6d034ecaaef5856b2bc8df377fa812.nq.gz
    ├── 6402021c79eebc87115812695bfc55ef77a71c63.nq.gz
    ├── 6444a6bbdd17a57d6fa0deaebfc57c58302ae242.nq.gz
    ├── 6447bec303c91fcf2c9b1b50f607b4b45bd71a81.nq.gz
    ├── 661f9159adbb7f9139737a36d2d13efcb1c18769.nq.gz
    ├── 6621f57e3ffec5d8f68430089faea6b1de2fb698.nq.gz
    └── 668fe39cb67d2d13af8eeab2d2e16cc5a8706e9f.nq.gz

7 directories, 200 files
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

[Lightning-AI/pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
