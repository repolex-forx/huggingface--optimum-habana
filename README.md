# Repolex Knowledge Graph of huggingface/optimum-habana

RDF knowledge graph data for [huggingface/optimum-habana](https://github.com/huggingface/optimum-habana), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/optimum-habana
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 65a8255bfcdf8f216e00f68bda3353af78e8e1c5
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 65a8255bfcdf8f216e00f68bda3353af78e8e1c5
│           └── chunk-001.nq.gz
└── blob
    ├── 005f50f0325d0a7cc4594d8ff7910bb3e78755c1.nq.gz
    ├── 00a0832fc83fbc239919e43499f511a9ae258c3c.nq.gz
    ├── 0148bb7921b9120b5d04eba26b06eb5f389b3495.nq.gz
    ├── 01b5684d689c86f262bc922dd0664024471be078.nq.gz
    ├── 028219d3db0430bd2d14eb5d897f6adc4d040289.nq.gz
    ├── 03163d519e715e9829053287797e5016741dc9b2.nq.gz
    ├── 033c506668df175a27daa00f2fc75731443cf461.nq.gz
    ├── 034c6a537610d9792441dfeead9adabf03887217.nq.gz
    ├── 041f3132667ea8985231202b4f23baaec99e0f8a.nq.gz
    ├── 0482e80a23b2eb6793bbf40ef5b2c61e00a888fa.nq.gz
    ├── 04f96ab70ee967970f48929b34870e34030a6b16.nq.gz
    ├── 053e516e8542f5a85a6ce2c4efb5e565901c95b4.nq.gz
    ├── 05788b3cd461b45ae7ef88ca38ecc0023aaee9cf.nq.gz
    ├── 0610822d8134d528460a9f3fa7d78b72fe41300a.nq.gz
    ├── 06e88925a31c34762ef25a2dd3849f43e060886c.nq.gz
    ├── 07cc0fe74c16e1931812215a099cb79b687b8863.nq.gz
    ├── 08106f7abd03ffee8c5f02351cb1dad399a231c4.nq.gz
    ├── 0854e731eec44e227870a59a0a8eb5d0076a27ce.nq.gz
    ├── 08b5c0baa741ec2c99f1ae5c1812c4e2f41a2f6c.nq.gz
    ├── 08ccaf3725aafe71b973067f7e3bd546ac2b26e5.nq.gz
    ├── 090f589ccc0c3ee0552dcd243afca8c615cf5b34.nq.gz
    ├── 09ccd1db5b5543de38b0582db8b692c8408f5b45.nq.gz
    ├── 09d6a5fd7701dac8343517dfc505c5a59e4b786e.nq.gz
    ├── 09e8aac5e89b62af9752c06d9593ad57bbd10287.nq.gz
    ├── 09f85a5451c741985f7f2e2af60444d75e97cbf1.nq.gz
    ├── 0aa16c83e008b2751838cc34547a22d08851b05b.nq.gz
    ├── 0b15ff561726b1c554b05d7ef3174e8a3926c156.nq.gz
    ├── 0b1e3e2a735095ebc779b5662a2fcde98e0d43d2.nq.gz
    ├── 0b5c3faef6c9ae215a08efd6180b76ade9b0d8a3.nq.gz
    ├── 0bf9ccf43caf7575c976d2b7ffcb351085796ce5.nq.gz
    ├── 0c24d1a0e174ad6a737ef9a551a17dc20d051444.nq.gz
    ├── 0d22cd33cf360f6d6bc8ffb6f9d6bd9100768b68.nq.gz
    ├── 0d3835de543075ea918540765abcdd71c2a99173.nq.gz
    ├── 0d7c22374687353326130b78b6e56d256832a113.nq.gz
    ├── 0d872fc75fc880f564cb6137f9565406cfd07a41.nq.gz
    ├── 0e2453ed1c439c7dde742ed31289b9bd753002bf.nq.gz
    ├── 0e46bd9dfd9c1e7ff061f94df8d9c6dcf37fb4cc.nq.gz
    ├── 0e5fbb4a2759f1c08ecffb80d186c616a12de168.nq.gz
    ├── 0e679a5348d071c96922352974a36f46e32ee874.nq.gz
    ├── 0e8dd2d6c1048db26463e2b22f044ba5fb655d51.nq.gz
    ├── 0ec4dbaa1c8becab64bfad80b1eb73a9f74ec2c1.nq.gz
    ├── 0fa8686f688bc0fe9cd23ca8f1f60af3e7446ff9.nq.gz
    ├── 1065dc8938616b790ec43f304956913737baf111.nq.gz
    ├── 10f01e7745347a65aaa5dce0aa91f7e609c77ff7.nq.gz
    ├── 11586d477b3e48e406bcbd54c349807758faeffb.nq.gz
    ├── 116df15e87a41ab060f803f9ca5d8788dc9bf6ce.nq.gz
    ├── 1172ae83022986492292b4bc5b35bb4ddfd7ae53.nq.gz
    ├── 119ba8a6325d80d9f84a0b5ce62211825ca1d3b1.nq.gz
    ├── 1218c0fc658652171ca3671fa7c2f49364ca1c4e.nq.gz
    ├── 122f7820c7aeeb582ca6269a9a0123aadb33e7a8.nq.gz
    ├── 123ec4b7d417f04383827bd612ab146947f62c55.nq.gz
    ├── 128b5cd1334d1cb07981b6edf11ab6d100b439e5.nq.gz
    ├── 12aee59d1c4a7802397986c3422d809b25327de0.nq.gz
    ├── 131c78e566d554c5c6a80b274c24fe2d1e057c15.nq.gz
    ├── 133f87623d47c96973c6d4ed3d5cb01a99c0a365.nq.gz
    ├── 13ed59664b3aaa6223a53f71a8fb9bd69f029b4a.nq.gz
    ├── 14842d24caf773181583433dc3cc2ca4ebbc80d2.nq.gz
    ├── 14e5db6dfd8f2018e69d43a8c7dc875e601f0620.nq.gz
    ├── 14e8efeb0ea0d4071240b6a8dafa29eb2785fad5.nq.gz
    ├── 155abcc892a13e85aa5640d9a6ded2411b153a03.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 160f88e7be8a2e1d318976003718de7b5f7f0721.nq.gz
    ├── 166e6b6f14e1c49b14c6328ffa97943ace94fed6.nq.gz
    ├── 17f1dac0d9a684d2b34530c4401213c6c941218f.nq.gz
    ├── 18b9f36fc346a7e21be5226e39ecc44dbd45e9bc.nq.gz
    ├── 1af2571297f23698a2e662e7996d3adf9de0ce8c.nq.gz
    ├── 1b53b542b167ad0c77d3cd265c426d5e019507ca.nq.gz
    ├── 1bd714db013a20ff058374fe0118c918df9760cb.nq.gz
    ├── 1cbde0fb18c6178c63c9ba74775d17b806322184.nq.gz
    ├── 1d7c1c1410533d1f5e7ab425e784b11e621bd53f.nq.gz
    ├── 1ddefdf0e9f3e99ccd4fff2310c86b1e2a0ac73c.nq.gz
    ├── 1e05eeec04fcaa525f93fa2bb9a488e11e85a613.nq.gz
    ├── 1f0588c9993a49c8c902e503a6812bb0e8658580.nq.gz
    ├── 1f6896d0156ff80107876b893a73e818bd0efaa1.nq.gz
    ├── 1f7438a8f01200e692f2e1aea78ae2fa0475dea1.nq.gz
    ├── 21395bf7dfefde7aa88f77d362f705aa1d69cad9.nq.gz
    ├── 222198b85416eb44925a0c6afe3549932f2248e3.nq.gz
    ├── 23e184744cb88ee31e8364cb3993d7e8db158e79.nq.gz
    ├── 25313a8f1b2f46fd14266ab8aca9502fec4c02ff.nq.gz
    ├── 258f1a0f670a333d02ca2d482620af8904023efd.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2649fd2ab175b7d1099cc3805b6280c271518dcd.nq.gz
    ├── 26a8b93c389641a0325589fdc38fb7b2e1b0431a.nq.gz
    ├── 26cc31320f0d7fbf999f8fc997afde06bd1c4871.nq.gz
    ├── 2788aaf910fd2885df60e755d5e819ef083a43e2.nq.gz
    ├── 28622de390aff2e1bcf269508f5095bf47da5d43.nq.gz
    ├── 2949423b7561dfb0be3ab996e88f2b93c3207115.nq.gz
    ├── 2a169573f7b37b0e5df66285a68b24afe1dabbd8.nq.gz
    ├── 2a2ccd57f9e3c5c9a5326883401fe1f78d4a0d13.nq.gz
    ├── 2df2d8951c2d23837861e5028e1054f07b390e2f.nq.gz
    ├── 2e2a95f885dae1c400b86cb8d869dfc444ec5317.nq.gz
    ├── 2e3c280fbdd621a8f2dd65f2c47991364c6c6cd5.nq.gz
    ├── 2e6ad5c1968290f8a28d99c9d33aa52e4bcc3111.nq.gz
    ├── 2e84780213a6d6617bb0a24212748db9b2fa97f6.nq.gz
    ├── 2f0ac74e53cd18c9670640165982c1892baeae3e.nq.gz
    ├── 2fcf6bec0a70a41e1b871d3eb5e11d3118dd3f10.nq.gz
    ├── 305afca08129dda4aa0b9f00f8c14b7fe5291ee8.nq.gz
    ├── 308106f0c9142ae48ac55cdf3bf085aac57b9371.nq.gz
    ├── 30a6c5f7f7c916cf1e97181b72cf9a20f1ffcd8a.nq.gz
    ├── 317417d52f41c7c97eef0bb098029f474aef339c.nq.gz
    ├── 31a8216be5876093d3767f783d67b35b03bedd27.nq.gz
    ├── 328d8df8759ea26a7627c7134e85a03759d6555f.nq.gz
    ├── 32cb0daf7bea54ab63844467b8f59a3a52c4b61c.nq.gz
    ├── 33500fc8e6b2c18935a9bf34b917af0cb0309ae3.nq.gz
    ├── 33b72d15a70d88fe2181ca8414d6e59dea4f9f47.nq.gz
    ├── 33bfeebb30ffdf71be9cd1035c3ff59f15e6f71e.nq.gz
    ├── 344bbc54f8183787b53812ae4e7fdc2eeb0fbb17.nq.gz
    ├── 3500a43f26d4b207313436361b0a9fdb7a16dd8d.nq.gz
    ├── 351152c026cc796585a9d9586505369838daa360.nq.gz
    ├── 353e829b0ad2f7e227621d8e0a9854ccf15f172b.nq.gz
    ├── 35bbdad6f8e2eb4d39e0a3de77b79787c5f3bdaf.nq.gz
    ├── 36b9c6e72362d5a0292b1fb6cf7737e5299ed986.nq.gz
    ├── 372e29bd5f02fbaec8bd62554dfa019c3405c8fb.nq.gz
    ├── 38728d337fa0fec41b82338b22e8e7bfb33f3bc9.nq.gz
    ├── 387b07c069dd2769f5b5e690dda2f539ab620f10.nq.gz
    ├── 38a672a41ec90f11bae4f91398d9bece6c5c9da3.nq.gz
    ├── 38f09b736a398ef97015118bbea59c70bf9c7ff5.nq.gz
    ├── 3936c43ac781d5369bce13657fad9963c3cfc4a6.nq.gz
    ├── 399ec9a3c98ce0b69011e4e5ea773e98aea028a9.nq.gz
    ├── 3b2d4d5d83809875f35a47a9d60d5612769d4e5a.nq.gz
    ├── 3ba99eba269b6e933cf1e97bbceb1e0fd3b4c876.nq.gz
    ├── 3c95a67d0d3fff19dc9b390ffc9b355c1ba4ef28.nq.gz
    ├── 3f037985802f529173cd42350d25b9372638bd75.nq.gz
    ├── 3f3311b40373a6a9a0127d51f6925110fea1e552.nq.gz
    ├── 3f3a6f441be630aac32a77d4490713ef53324438.nq.gz
    ├── 3f3bd150563317b16d164091aaa29dfc0f98dc64.nq.gz
    ├── 4056faa37b3cb3e69f9c38b1c2b118f72dcb3e88.nq.gz
    ├── 4172bd0c666275c7cf470cd5d9370033252dc627.nq.gz
    ├── 4204df892f99abbaed0265f094267308a0158d52.nq.gz
    ├── 42b4cecac56cff58101b5a62fde0bca1f49ceb50.nq.gz
    ├── 4349c7075ce86541fc51272807535bd36bdff5d4.nq.gz
    ├── 43b2b2c71471c842ebb6edd3b9ead76b092deec7.nq.gz
    ├── 43d90b57e8a941ca3a6b2a8bbe8c1650a3bfaa49.nq.gz
    ├── 4494523446ce7d6d2488ecd8ce79c096ad6ccbcb.nq.gz
    ├── 44957c5efb862c518fca435bca2f5e616e37e104.nq.gz
    ├── 44fc349075d5c135c6c03b9a6d93f973aba3b3d3.nq.gz
    ├── 45a6624b5bb09bd4352bc2b6320f8eb7defe69a0.nq.gz
    ├── 463b277999557ce43104f4445da587b83901a59d.nq.gz
    ├── 463fcadc91ae7f1b03f4cfd184f7763f9911e85f.nq.gz
    ├── 46f23d260ee06faf3a9475a1402b44aacba4b092.nq.gz
    ├── 482b1af44a925a06cbda5de2fbf29d1f0b9f7be4.nq.gz
    ├── 48bf0bd8e9fb0bbda685a7b0461aec9ac9832132.nq.gz
    ├── 48efc0ef0c07c74e9d58e5dad0b6902f0be8e782.nq.gz
    ├── 4a83c6bfac9c87a0e5c73da72c4e9cff00a3e147.nq.gz
    ├── 4ad5abdd0c8c931be5429188631927f3fedccb66.nq.gz
    ├── 4aec1a5e0729f88f64e7b7e810dfe0783daec802.nq.gz
    ├── 4d037fc272bb6a498aac047eef7685787f9c69d2.nq.gz
    ├── 4d0997861d50f99c28ec2af2a894fbb0a3917695.nq.gz
    ├── 4fb4ebcdba0c459b3e3011db7666d0f3a0cf6d22.nq.gz
    ├── 50bff7328fdbae86afc5f291f4eb00d5bddf701f.nq.gz
    ├── 50da15d2ecefd1558110a0bb7a4fc039c945a262.nq.gz
    ├── 50e4da4fbe2f0ec938305fe6265c66869763dd6d.nq.gz
    ├── 5114d138a024e71a5d0e0d8206ac33c5e33a7c79.nq.gz
    ├── 51e823e1ae2e97d4828c0a6020bc26e8ff6c0ad5.nq.gz
    ├── 524dbb2af8d73a7f2d619944702aa79a097c7dca.nq.gz
    ├── 533c2858144a1875768327904f4395d0995fae42.nq.gz
    ├── 549d55352c830a1edde2e40dec81b3b7407472c6.nq.gz
    ├── 54f4c1de8daf080887c75f19e524c31d22a220d4.nq.gz
    ├── 55f448091f339948ff832d4195c95f1235e0f960.nq.gz
    ├── 571a187ba4d9167a6f5448861a87697ba5bc7fa0.nq.gz
    ├── 575a334a6ab78f7d082f5d56aee56bb6177efead.nq.gz
    ├── 57bd56072b719d813f71130a56c883a99591224d.nq.gz
    ├── 585ce75573a465245ac7aa4d06b5924f22a2396c.nq.gz
    ├── 5868bea3e88daaf9f3fb052690a7afd25cbc3609.nq.gz
    ├── 5883bd59ae0b958e97258c1fed094b6d28c0ee4f.nq.gz
    ├── 589a36ff1f16af7f61e40bcbef8dcb5ccd87e9ef.nq.gz
    ├── 589abec3e10c6d09514e58546a22f3651e7c75ce.nq.gz
    ├── 596d3f84630b7039158d2c06d70aaca16e9d9284.nq.gz
    ├── 5a47d7bfe67ad4a5ad61c86e7ca947254042e389.nq.gz
    ├── 5a9234c77468c82d5291c9d2fb8cade293a7999b.nq.gz
    ├── 5ab70dd1b86fcddf83a87c5fbce59ef9380bd3cb.nq.gz
    ├── 5ac39d272e214f8822330c376ebff9897162329e.nq.gz
    ├── 5b471a98fddf982a037b7defbc260bc4cbfa4bf4.nq.gz
    ├── 5b9f2f97d3cedae830b993fdee5a01785c314118.nq.gz
    ├── 5ba56e82d063cdb926ebb1b88e96317ed839acc0.nq.gz
    ├── 5c5fb458a0214ee15d9d931e7a0474f1ccad3403.nq.gz
    ├── 5d4daa4a6639b52b98628a7c086b2359c71e6614.nq.gz
    ├── 5d7100c1e30338744ddfb33b4f6cf19c3b5dd6af.nq.gz
    ├── 5df883121ddbe636554e581af8383fdeb6136fca.nq.gz
    ├── 5e58205d091edb3a63e973ba6f8192cb7131f691.nq.gz
    ├── 5f45e4908f734f1865cb921c118a248477da1b41.nq.gz
    ├── 5f47c5c6be699ace4cee6e1e582a8f69c307f9aa.nq.gz
    ├── 5fb93f71eb0448771d3c625a13b41c438a0fcac7.nq.gz
    ├── 61990281fa6f0f495808e68bee31f204979d110f.nq.gz
    ├── 61ccc184f5519ea956ba4b957ddb21e3ad8fbc5d.nq.gz
    ├── 627931535a217185048cfdaf253924e765712cbd.nq.gz
    ├── 62df6c2e07c55b610b47ed9f99842295fcafb3f4.nq.gz
    ├── 639bfa8035166934fe9272c4756f57a416e7a9ba.nq.gz
    ├── 63b155f7a0e3640d8022da94805744345c38468b.nq.gz
    ├── 63f5d3e2464a79249099f1bcc6897053b1f675a5.nq.gz
    ├── 6533ce19fd13479ffb8acaa447ae72b02b0ead16.nq.gz
    ├── 65f7dcb894fd69e7d59bd02b93120ca45accbdbe.nq.gz
    ├── 66897f73ecd45a605b059fa970a7723d01e3ae0e.nq.gz
    ├── 66b7087da2463b7a074e8d7b9d905c492c7af8f6.nq.gz
    ├── 66c2c292ef1d8765e7e811a4711e1f0e9bd321ce.nq.gz
    ├── 66d10d0f727b36161d8da12ec84ca96d05174785.nq.gz
    └── 676486fc517132d5ceb6eb69fb15fac2de2a03c8.nq.gz

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

[huggingface/optimum-habana](https://github.com/huggingface/optimum-habana)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
