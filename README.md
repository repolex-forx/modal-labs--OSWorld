# Repolex Knowledge Graph of modal-labs/OSWorld

RDF knowledge graph data for [modal-labs/OSWorld](https://github.com/modal-labs/OSWorld), parsed by [repolex](https://repolex.ai).

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
rlex download modal-labs/OSWorld
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b138d348256078fa634fc3b73567a7337c793e6b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b138d348256078fa634fc3b73567a7337c793e6b
│           └── chunk-001.nq.gz
└── blob
    ├── 00791bc2242ddd2180c8a68b3118b7035856f39e.nq.gz
    ├── 0095949dc046be6b045cfdbcf8a59d64955aba6e.nq.gz
    ├── 01da5abded88389934f35fec99edc8871b098f82.nq.gz
    ├── 0214d69af05538b6143a4ef3f8c046a0e59b16e7.nq.gz
    ├── 026f146045204f17377ee5f9c04be0275e66be95.nq.gz
    ├── 04311e0ac2f7e696e0de6ee6ccadc1735a6c5084.nq.gz
    ├── 04980d086f111a7d45aa92481f82d625fe7333e5.nq.gz
    ├── 04e939373dde7f19d1a3af32def669f0a85a1eb5.nq.gz
    ├── 05e51ff64f9a78b58b2cd60da61c3cb7b5932d01.nq.gz
    ├── 06001ec2e363b2ec8082a45685a9d742c1587672.nq.gz
    ├── 06be07706b304c3f0ddc40f32d8380c8273c5f8e.nq.gz
    ├── 081136f9cd126454c376f50a5df33f9f5ac9927b.nq.gz
    ├── 0902abe6ddd446c1faa2484c61727935e89be474.nq.gz
    ├── 09bca41b7e420514620b0fd05511a0e82f280be8.nq.gz
    ├── 0a64b74d8312fb6bee896a35aa77e4b295bb33f5.nq.gz
    ├── 0aa73c132578223c8832474c417b96a604a7b1f8.nq.gz
    ├── 0b8ba172d0014651fc782779879eccfd22f764b0.nq.gz
    ├── 0b97b8cd7d44a48ac12086845b422fae4dae0541.nq.gz
    ├── 0c60d5276b80ece3442506784276a3bbfb70789d.nq.gz
    ├── 0d99f090ea28cf8fb4029f6487e022e19f9856d2.nq.gz
    ├── 0e1b5dd0901e7f8033b43605c6b870662842b229.nq.gz
    ├── 0fa54c826825bb9467cedf6fc33820ef54044ab0.nq.gz
    ├── 0fdc082d909e1ea4952a1ab9e2112c8ba60592a7.nq.gz
    ├── 102bdf5860060260148c85c0655a1e4c7bb0eca2.nq.gz
    ├── 1077f909842e8e5a14086e55fdc7c8818a7c8c05.nq.gz
    ├── 10a2cc16267f1b696f9845d69001c2fa50fa7d92.nq.gz
    ├── 11821670b5680edda20b77abc205f99993b5dad9.nq.gz
    ├── 11fedb76e7b60b066da66357de57ad5c6379b815.nq.gz
    ├── 12ab8d66bc7d2b135bb301bcb933e391de2abcaf.nq.gz
    ├── 133e4d6fb65f6a8597644e4b177c1cd2ab7eedfb.nq.gz
    ├── 1422cc5b2c61f44639e886ee958c869d6fd7b17e.nq.gz
    ├── 145c443e434d95559f0476e158045bc1f25f59f1.nq.gz
    ├── 1561d7fdc23fc11c9e667ec53e275196838b76a5.nq.gz
    ├── 15aa78407b998c88ce5dbc2d616501219b2214bc.nq.gz
    ├── 170034103af97567c5a6ee3d36b5e7e1dbb94255.nq.gz
    ├── 1724982187f67f34a45ccc697e505c2746a5b61f.nq.gz
    ├── 17647690ab6359a77243deeb539f7861af91a216.nq.gz
    ├── 178f0bccb8ea2f2b66840166566c5e923b79bc55.nq.gz
    ├── 17db707f22f6e44a5f09968f6522f98b8d954486.nq.gz
    ├── 18863fd6a545e0cfb65902f8d54c6236c201076d.nq.gz
    ├── 1892088d1c81df5540ef8acb570b04272e80370a.nq.gz
    ├── 19801d6f7f5b94e82e6091c561523f56632eb741.nq.gz
    ├── 199cef44e14ade0baf44eb1861198dadb3d8cc1b.nq.gz
    ├── 1a0a2cc50cb80511cd5e8473e081e45753ae9749.nq.gz
    ├── 1b4cd53b9d041a3594560f35377457a5f1ed56d3.nq.gz
    ├── 1bb6d78af28bba64706a2522f6d5dc6875e9fbb7.nq.gz
    ├── 1c296f5adfeff03d2328be419140faed3fe2d565.nq.gz
    ├── 1c4953c358c99a6e4825d01351097a9ca06ab240.nq.gz
    ├── 1cce1a249dc8c46cba423c55d296698339e156db.nq.gz
    ├── 1e4e750f9b2c1c892833adbbafaa076156dbb48d.nq.gz
    ├── 1ea43ea54b8310fe5de9c6a5d17ef52cc129133c.nq.gz
    ├── 1ef158a27ea81b483d88bbb626229204688e4e41.nq.gz
    ├── 1f50e09fbca5c233b668d260cc0a55d5c1d9e013.nq.gz
    ├── 1f50e94e4013bba0e065153b883770b3284175d0.nq.gz
    ├── 1fef8ed2cd7a3cc16646035b24088eb30846c1ae.nq.gz
    ├── 20c4d6e22542c5a4eca2d9885b626ae59fb3a190.nq.gz
    ├── 218b080e3aa3dab61cf5bf3f2e6028ce0e3d20e1.nq.gz
    ├── 22e2a14a93960f87c4850a4433a1e639b69493f7.nq.gz
    ├── 23ab197fb10131cccf773270799885e86b66f3ae.nq.gz
    ├── 23d7ac93f534b73b0cb6de6a5496dd6b3ee094d9.nq.gz
    ├── 23e90a630f651c510d1f76c25f9a0a768cdcc0e9.nq.gz
    ├── 24103297afbf6371496291739a48559d580a1f90.nq.gz
    ├── 24138ed65fe44ae10e16be29ceef771714636e26.nq.gz
    ├── 24a668623b4375c6545180a44342e9ffd2e9fdd0.nq.gz
    ├── 250a4085565a828d7a344ff167b39f64d0058dac.nq.gz
    ├── 2512f45865ba0530ce18f0c056e3dfa414d8afdd.nq.gz
    ├── 25c7cd8d91e7e71b4e2fb3f2668d737c2be37397.nq.gz
    ├── 2638102fc50d117f45f90cecc0660379eb18cd8f.nq.gz
    ├── 269f151e934e6cb649be40f6b61696ef7684129d.nq.gz
    ├── 2726f5fd2d4092c87a8dbba31e31a452c7448ba0.nq.gz
    ├── 27e1090d7401bc958e81667f7f1e22bee035fd3d.nq.gz
    ├── 28c00ea9631f1659c60383cc4242026b18254824.nq.gz
    ├── 28dc775a2b6a7e5c3d9a8e0470e87fc82c3d4dac.nq.gz
    ├── 294a980f278de8ff3bb2e8d8f27ce103d28213e1.nq.gz
    ├── 2aef6401febf8efa5da771656bf9bb1f151ddd3e.nq.gz
    ├── 2b98b53a1993ab86593d66e69ac2d649a5b2acf6.nq.gz
    ├── 2bc16b9cad3bf5540fe8f6d5ca425f02897857cb.nq.gz
    ├── 2c42d83c0e26bbbd4bf44e0e948a14fcc1a429d6.nq.gz
    ├── 2e1cf6ad3d1ea784f9472eca49bfebd5907ad7e8.nq.gz
    ├── 2f5ed32c145000c16ff4159937d9fa667abc0580.nq.gz
    ├── 2fd284532f17a5f2f2b0fdd4ee2242fa564c458c.nq.gz
    ├── 301944626a231c1d2e5b8864f17afa0dd842a46b.nq.gz
    ├── 3100ed27da15b48137cdff183260251b6ed7e162.nq.gz
    ├── 32884cddcc864bc8e0df955123e8bc780f3c5882.nq.gz
    ├── 32b4497f8969626fcb876b74a3f1eb8824c42ea0.nq.gz
    ├── 32d47e11ee0c94d9661f8b7a53b02f86cb976b3e.nq.gz
    ├── 33848ebf846109a483329189c4072120a418f30f.nq.gz
    ├── 34bdf0abc9fb867228711dcf085a02410b42177e.nq.gz
    ├── 35095c85a5c8798f9d6712b13fdd883bda9a9928.nq.gz
    ├── 353fb9f9dc1c42a2b0d1f95835389081a78831c2.nq.gz
    ├── 378f0ecfd2235b1089dc9adfd6764bed5e409971.nq.gz
    ├── 37fe6fd21f392ae8bf69e2d1a79abde3f280c8e0.nq.gz
    ├── 39f16d649dd75309fc4a4aafde40553eaa186085.nq.gz
    ├── 3a0c3a047b85fb67198050312777066537b981d6.nq.gz
    ├── 3a1f63174c0780d08ca029f9dd4a8fd7921a14c0.nq.gz
    ├── 3a36dd2aa270dd1ec25eda86e4b6672d04f2e7f8.nq.gz
    ├── 3a4abfd895e66d95fda3d16e2a5801e0f52cc605.nq.gz
    ├── 3aab182706aeca6e965f276a74e69ffffb5fefde.nq.gz
    ├── 3b09b5f2fba750c77c79ce735c069153170de8bc.nq.gz
    ├── 3ba079ccb1b4c8a52f689bf711cd3cb9e4689950.nq.gz
    ├── 3e9210e5570a6fca7824eb32655883f0caf7b8b9.nq.gz
    ├── 3e92b090993d4a60824fb7ebebf336842ce629fd.nq.gz
    ├── 3f725aa40fba7f1f3ce7bed2cc3d754815455265.nq.gz
    ├── 3f9914b828ad8b7d5120a68a11435a583642532a.nq.gz
    ├── 3fbc87146b8497976bd51cd2a3f42b06052221d7.nq.gz
    ├── 3fc13d41c30b87bdf8b879d52345c8a160f3aba5.nq.gz
    ├── 4147896287581448a279ed4537b26121e264b354.nq.gz
    ├── 4167df8f18d8a1523b6a1c344061fdd1f17745a3.nq.gz
    ├── 4176f49428971bbd03b88ad6c22853112943242b.nq.gz
    ├── 418563766406c2291f75b1c46ab551d99245cede.nq.gz
    ├── 4186ff072ca7417a0dd3d0bee75aee140b86204c.nq.gz
    ├── 41df020b39270d4a2f2246df3d38de0c977fac15.nq.gz
    ├── 425f672856e7a2bc413dbb7d276f9fc889ff282e.nq.gz
    ├── 434055baca18fb51e43c3d747a16bb51c2fd8641.nq.gz
    ├── 438195572f97c2442f153a3c868148146662960b.nq.gz
    ├── 438a192079633f662bd7b357131b1ad427aaf394.nq.gz
    ├── 438dcad8aa94b0ce4ef57757e29febdb4a888ed6.nq.gz
    ├── 43cbeb76bb0222bba8596184dc57c124f822a8a7.nq.gz
    ├── 4437fd66059d47f24d74a1ab21cf9c2a6d33f816.nq.gz
    ├── 44836df21629c7264283b00182d38e8b8a3ab0cf.nq.gz
    ├── 456ec35e3487e6195e82c83247d2935df9ec33b1.nq.gz
    ├── 45bc8bd8f19ef3005912ff5f7e2e001f3d3c7800.nq.gz
    ├── 464f5b56e7b67ed40fceed72f4c04437ba0bf4af.nq.gz
    ├── 467a825b71e9a0685df02da69bf085ca7fdda864.nq.gz
    ├── 476865703927c332400f523386c685b709f281d1.nq.gz
    ├── 4947748ef2dab1c5d8e3c5d7c39c3848aa751441.nq.gz
    ├── 496430b9290443831542c77a21e3b1841a9f2a7d.nq.gz
    ├── 4a11828f991df5dc716a78e1ba873b370d2b64f4.nq.gz
    ├── 4b7479b441d54078deb955697b03d40cc61499d4.nq.gz
    ├── 4b7603c7caf534983bba4928944b51ca1f9deb17.nq.gz
    ├── 4b95a59100bd3a307dc93fd599408cff26b43f46.nq.gz
    ├── 4baf19429310d2820c50f53e981dc6149ce0f266.nq.gz
    ├── 4cf120cca67af0581caa9cd341632a5a87a33808.nq.gz
    ├── 4d5453dab530be7ec235cd0929c887ab664838e2.nq.gz
    ├── 4d62f2ebcfa4ff688f82945ce6bb4e64a9a509ef.nq.gz
    ├── 4d6690ffca9737013df28185ee99a896039d5324.nq.gz
    ├── 4e06aafbf7ee695a1b3b63445d4a3af925c7ae9a.nq.gz
    ├── 4e3b4e4fe069134db0ceb642a358ee85504adabe.nq.gz
    ├── 50f9df1198f8c2c8b3de8f361c24a16c3a4a33b0.nq.gz
    ├── 5151695815ad57ac76c1c6d12489958d11100020.nq.gz
    ├── 51fed87b5aecd85183014f0499c0f4ea9253eb90.nq.gz
    ├── 5292cdfbc9eeb9153a4a0ed0171f65e677848d1e.nq.gz
    ├── 52d380a7f8473f9f330bdcecabdc5cbe8d6c010f.nq.gz
    ├── 53460ab2944ee95c609c99c122708ae62ec0b220.nq.gz
    ├── 540da7f99541add89741c505779e3105ecfdb410.nq.gz
    ├── 551beb9d64200981ec36239bab2af7d0465c57f7.nq.gz
    ├── 55ddb3e492d69a95b922036028b2d6091604595c.nq.gz
    ├── 55ede0fb4363a897789ac6fa473e6c233576291d.nq.gz
    ├── 56f369d970e5d8e73f9c142b72fd434af9579b5b.nq.gz
    ├── 571d18ab21885a4701196f96fddbd241014c9916.nq.gz
    ├── 57b9f81b052fc029c3afe7217e5d392675069c38.nq.gz
    ├── 58790f2c204a0eeea42b2353b89d0de7f7846549.nq.gz
    ├── 5883518827612afb32d42f1b8775b2fa59cbf508.nq.gz
    ├── 588d8a3b09f9f9babeb30c6691b0f56115d6779f.nq.gz
    ├── 58d7b005cdfb47323dc448f459f45c74427b2715.nq.gz
    ├── 58e4c531e18ff503d2ec99221f5d2e93e0704af2.nq.gz
    ├── 592537eab8266fc2ea0f4af4720cc19a7e0c319e.nq.gz
    ├── 592b6a0ec7ce6e17d97ffa3ef796f14e5ae67d72.nq.gz
    ├── 592e4c40d84c372bc734e0b84aca0187037548ae.nq.gz
    ├── 596d9f4b01d3901b0025c4acf142c554d6acdcaf.nq.gz
    ├── 59f8975eb6006b2be01cc5c058894d382ad78681.nq.gz
    ├── 5b311923d32f3e065e65e4da75fa7b4352bbe0e6.nq.gz
    ├── 5b3c91f44634b600f0e105e80c3a7a8ed580dc0c.nq.gz
    ├── 5b7aaa0771bb385f6bfe3e1e0917a8f36b25b360.nq.gz
    ├── 5b996f8a56b395167fa2537ebdaaa77af93c6337.nq.gz
    ├── 5ca08a3d9ec441d1fd64a0e6982cdcb4c245657f.nq.gz
    ├── 5e13a8a106c4fbbe2d0b510ba2d03004376b0c3a.nq.gz
    ├── 5e286c52bdfafdf5b19ccba02e96e4de0dee12e3.nq.gz
    ├── 5f8add3a16e53bed5e0d03b04d813e717e9b8b5c.nq.gz
    ├── 5fba71f48ad352bb4c91c5040699cf043ac7f33b.nq.gz
    ├── 60cefb2527629179fe099e319703612ff4926b38.nq.gz
    ├── 60d0edcb164e63027fda49865712d5bcde225195.nq.gz
    ├── 62026c3533c708e619e765df1bf61595af74b6e5.nq.gz
    ├── 6239cbf9c64b007bf361955a4d184a1f6384eab5.nq.gz
    ├── 6297c7034f21a72ce995ebd646e2ff851688f908.nq.gz
    ├── 62bd1443137d071a7b52068300b3486f094a6ebf.nq.gz
    ├── 62ed046739089f186c1558c0dbf044c1b9bab39f.nq.gz
    ├── 63232debe189d555625d9d2f0073bc04140306c4.nq.gz
    ├── 63ec7a1f89455d40fcff0dc38db3e9d3a2f50686.nq.gz
    ├── 63fc0a97522aa6fa361069200f6c3f70d97a28ac.nq.gz
    ├── 64881fdf15634d741634c3fce98be45e3f5a18b5.nq.gz
    ├── 64f12f076eda6587569a1cd45e73cdaa8f8d5fcc.nq.gz
    ├── 64f2052044a4347616c4195c02393cf5dd845074.nq.gz
    ├── 65cb330465451ac48747b5cf0a30f018aa498779.nq.gz
    ├── 6681e5e6e0877ac9594b40e3a3a902a08a724e0c.nq.gz
    ├── 66bf63ae326f2267a294aea094b3b3de7c1e2519.nq.gz
    ├── 66c6b4852e4e0bcad775ced7c468ed0ab36e1b87.nq.gz
    ├── 6797e34ca9dc1acddbd3a54e43f237bc6d0ca2ec.nq.gz
    ├── 68226a16e5323fec6ffe27276937986fe20d0ded.nq.gz
    ├── 68afa4c08ad2d4cc8ea9e1fb9cc14e613131e84d.nq.gz
    ├── 690f91099d55e477abe333fc1b51490d076fdd18.nq.gz
    ├── 69814b990206ca0547f919d3c1f296ac12b5a61f.nq.gz
    ├── 69b5e81e99e65ff91f671742ac7ab9cf40480836.nq.gz
    ├── 6a126f828cbf60d7601e7e6b564671d1a37a38b6.nq.gz
    ├── 6a164e665901e6291654f63ccda5fd287bd9113b.nq.gz
    ├── 6a5f0cd2eebe7fe6030226f900230d9d1b90cbf4.nq.gz
    ├── 6b1eefc26049b96c7a9ab0d0ee7c3d2667efda83.nq.gz
    └── 6bb38926213a4618983639914e311482bf311e9b.nq.gz

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

[modal-labs/OSWorld](https://github.com/modal-labs/OSWorld)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
