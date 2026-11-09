# Repolex Knowledge Graph of cucumber/cucumber-ruby

RDF knowledge graph data for [cucumber/cucumber-ruby](https://github.com/cucumber/cucumber-ruby), parsed by [repolex](https://repolex.ai).

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
rlex download cucumber/cucumber-ruby
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0a5512bd64f5619c54beb15dcfaf8040157b1f81
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0a5512bd64f5619c54beb15dcfaf8040157b1f81
│           └── chunk-001.nq.gz
└── blob
    ├── 008b6ddb32076196fb230216f20467e1a1dac0c8.nq.gz
    ├── 010233371e6e134bb83419f748e4dc057bd4e4a9.nq.gz
    ├── 011d217d7272aa590e7535f400a16793ba1861ec.nq.gz
    ├── 01af528cde12e8fdb2daeadc2dcebd5e42e3e5c8.nq.gz
    ├── 021dbadbd17f31dac4b6538da30ee68cab6540b1.nq.gz
    ├── 025f1f616ae68e25bdd7b9e70fb437f4140746b7.nq.gz
    ├── 04235ce5c650192f804f1e93c192c033c30825e1.nq.gz
    ├── 050ba25a971f7786e01af7dd44837f20ec0bdb47.nq.gz
    ├── 0549414a99d8f146be9e9f8720179e59992d5e8a.nq.gz
    ├── 058d5f43897021e02f413346d7d6ff46cdc03680.nq.gz
    ├── 05f1d42209f233cd1c72f03d4a149ff65b44abf5.nq.gz
    ├── 060c75cc8798c99f8a6944d530cc9b55e719e02d.nq.gz
    ├── 06d219a2ab3a6af498f1ca1a6d389d4ca5018cc8.nq.gz
    ├── 072e0a4679324e0adcd1b6deadadd967e854064b.nq.gz
    ├── 0789ef185797bd379b07537a56cc907e715ac3ee.nq.gz
    ├── 07b9836609dfc9b2aef327460d4ea54a9740c024.nq.gz
    ├── 07d785e5e2f327b769ae4be89aa7fca03a6f77c1.nq.gz
    ├── 09503be79abb351db5a64497c647e4fe317184b8.nq.gz
    ├── 09d31625785bd5260da341573d6f5c59c644eaa8.nq.gz
    ├── 0abd63db0a47976d18b919de456ab1cf49f3455d.nq.gz
    ├── 0b2d49e6fb5ff98a9a0b12040cac0524020db88d.nq.gz
    ├── 0b8225a4abeae49c34f0eb071acc060e2b5c7f24.nq.gz
    ├── 0bcff4ab934bd514b27b95290ad9a546bea3c244.nq.gz
    ├── 0bf81b6f3a4a0f8fcc7f8ca13aded7259d6a4865.nq.gz
    ├── 0d9ed943a8ab940acf0bea7321a094969384fcb4.nq.gz
    ├── 0dc39f841e44ecd325bd0c06637e10ff1368f853.nq.gz
    ├── 0e1cc5c5cfca9b6bf4ce00e1041e5e84be723788.nq.gz
    ├── 0e6316fb1e0408a1d22893678d924519f86d24c7.nq.gz
    ├── 0e90950c59bcb425c57511c87ff44a05c5d7b317.nq.gz
    ├── 0f8279862a21807a806f48f89982c40498802d30.nq.gz
    ├── 0f9790b66bc6e5a94817321dd6d2f851974681ad.nq.gz
    ├── 10f36a2520e124a549cac97956c7d001f8fbcabd.nq.gz
    ├── 1110cb44554b5e1730a8d66fe7f6012a5dc81ef1.nq.gz
    ├── 1171124d58de6d491fd6cb5873d55d91ee24b4e0.nq.gz
    ├── 12872103b9b3e75517cf990a848ceb39133db136.nq.gz
    ├── 12f930130280c9dfff58a95dfd7af956936667ed.nq.gz
    ├── 1406c236079f1b846668b033eef7f10070cfa003.nq.gz
    ├── 1424bb07280c98e279c0d5a3db7e54b43095a961.nq.gz
    ├── 146892077dff1ee718f32f6ac0feda57d596a9e3.nq.gz
    ├── 147bfe4c2dfb9c756bb5114efcfbfc42a0d6c3dd.nq.gz
    ├── 15d0c30236aed464ce5440d818efff6355d6c439.nq.gz
    ├── 16308966cfd8154755df5385fa28b2d6a269a422.nq.gz
    ├── 16827ec062f3efcbe0211f1f151c403f38f4a47e.nq.gz
    ├── 17365ae7362a00d90a395a2e8a4d67a29abac15b.nq.gz
    ├── 181ff7274ec9123c5c01812f857a9d2ff7a4b990.nq.gz
    ├── 187272a3afae0dc5c0eb44a9665c9fb1160b172c.nq.gz
    ├── 187996c9da741d5d26ff051969db046fcda98173.nq.gz
    ├── 1880bf6502e7d30840fb82b611409840f921c576.nq.gz
    ├── 190d00144e283d47fb9eac4c77f4e1413dc3842f.nq.gz
    ├── 1974dae66a9395f29710e6f39e0f9d52c24c1b84.nq.gz
    ├── 19c17dd4dbe49c5e67c4de346234ce28305030db.nq.gz
    ├── 1aaa5c9803951e13019b0757bac778fa6a8f6df6.nq.gz
    ├── 1ab38b9567ce936967b335978c2352099360e153.nq.gz
    ├── 1b2572b645c7170210b0246707d0f2b1c7de34c4.nq.gz
    ├── 1b2ed8f73eb4be7ae91e554179b5fda299b28a99.nq.gz
    ├── 1befc3846328bafaef339cabcf73d145a214a4b6.nq.gz
    ├── 1c4e12744606217efcf8687d2eaca45e9c305dc9.nq.gz
    ├── 1d35f08b560f42903e50c8af0d5959a8b0894a07.nq.gz
    ├── 1f378d33649bf5793373b8721f49a03d872eaf21.nq.gz
    ├── 1ff569dc56b7463379a4cf2f287dc27df99993b0.nq.gz
    ├── 2017284de5a291491d2fb3ec801f6e04b19b019f.nq.gz
    ├── 208c7c96a1cbe2bcf1b19a251d98fd54765b3e68.nq.gz
    ├── 21754e5d0576949ab57dcc8e5ec35b7c68696d6a.nq.gz
    ├── 237710b74d4abddaaaddef7282440fad2705f024.nq.gz
    ├── 23ebe13cf358f92be55c7991f6579254807080f7.nq.gz
    ├── 23f25d55fd34179ea5643675bb2f6aa0359b145b.nq.gz
    ├── 240c6a502e0bf0ead5bc18184fcc3e211c80ac24.nq.gz
    ├── 24c466bfb90a57ecb1fd4884513417b04ffbf17b.nq.gz
    ├── 24db2564da3e6d1c77b84af816818ba47b49a4cd.nq.gz
    ├── 24e40558fb0131ede086ce3a1d8d3359440c8968.nq.gz
    ├── 2512e482cec3446b98fe8d93a5690cf35b350ff7.nq.gz
    ├── 25286b62bef2565e657cb8d03d66256275360745.nq.gz
    ├── 255f604e34e0b274fc416ea37f05b2f5abff0565.nq.gz
    ├── 256587d9629d67c0aeb9ab5e3199849f8d2bfa01.nq.gz
    ├── 25a767757dbc0d9ac34f226dcdd826b9d23fe17e.nq.gz
    ├── 271e3831735ef298c94aaf60be778bb711ffc961.nq.gz
    ├── 274397a0139d942f3ff4e3a35e595d7888ae6578.nq.gz
    ├── 28ea3808735f94371e3f8eb060752cdd1533ff87.nq.gz
    ├── 2a09da6ad5cdf3ab7dab88eedeed07c86b964484.nq.gz
    ├── 2a2321aede9c59e12a9620ebf5d5cfe53efc9aae.nq.gz
    ├── 2a31173771531f353557a626a3d17df49185cfc4.nq.gz
    ├── 2aab1a5b4faba77ff48c100c91511f9133e52670.nq.gz
    ├── 2ab440a65c30af34cd543706a4a07c9270279c9c.nq.gz
    ├── 2b14732a2275ae34f5e6078d6c8fbe268984bfad.nq.gz
    ├── 2b78ce3200ae1dc714183fdb0f2eb0da0f8fc9ec.nq.gz
    ├── 2b890b4f242cf90d170b38fd7a787a939e0dc208.nq.gz
    ├── 2c91ce883ede4fca75af274b3c6e1f7d558204d5.nq.gz
    ├── 2cd5305be4ec909feba95247d7e901cfdd76fcf5.nq.gz
    ├── 2dfcd689c2c36885595f7edf135f79571420b3b3.nq.gz
    ├── 2e37207d29b0a9f5a67b7ab947cbd3ab1010f36c.nq.gz
    ├── 2e678db59bca1012e493b431488aa729d47a53a3.nq.gz
    ├── 2ed12dadbba730260e566a8c1ba9fa6b84c6b9ee.nq.gz
    ├── 2f6501908353d3df3fb74a4a47157e77f7114794.nq.gz
    ├── 301f46f8b1c2a86ef16b39f88f88fba54dc2b461.nq.gz
    ├── 30d44ee1bdfdf0fd9d8bed19967c6aff9e2d6a01.nq.gz
    ├── 30da3f87001896e1f3a795c0cf0e26bd0c86598c.nq.gz
    ├── 312d8e91ecb435c1d2b9f9e39a5e36c659e06ea2.nq.gz
    ├── 318942341f67f9a7922ffa65614f378b4e1fd1a2.nq.gz
    ├── 3194b9a759a3ee155eb7b318d160548d6ead440f.nq.gz
    ├── 329c2c429f3197439de3e7f858bcc37b3d7eaf04.nq.gz
    ├── 330cb962938189fbf460e437bf2c6815d873d4a9.nq.gz
    ├── 33b5c401e70387d66ea8b71c7fdad58391e8381b.nq.gz
    ├── 33d0e385c170f32c036f6d7aec59c52621885f15.nq.gz
    ├── 340e9cbd34698f433b62f373ce9c60be420e2751.nq.gz
    ├── 34a35fe2cf61cb0cf36716a802c242fe406e587e.nq.gz
    ├── 35653335c3688b778008bd33df1419a3314e4a2b.nq.gz
    ├── 3687797e56f4efaf16e3194edaa28d2a10210410.nq.gz
    ├── 37781d85085a1cc380885133d447076ff1223648.nq.gz
    ├── 378a83e5da5b4a021e3e9065ada85781e7b2d78f.nq.gz
    ├── 37d984306257356d13170498ca993dc02250224f.nq.gz
    ├── 391b9853b8f18fa9854967168f1a495d39e095c2.nq.gz
    ├── 39fbf46d169f5373b5eb72ddf827e182925a6b09.nq.gz
    ├── 39fcb59e3fbaaf2dad9130f52caff83bee05ed4a.nq.gz
    ├── 3a5431d6ec36336adba74bc3950cf9b66459879e.nq.gz
    ├── 3aa0e1b0ea77e8ee8096e0d0c1b77a8e40818d9c.nq.gz
    ├── 3b5187169308939408a2bc45b4c01fd55b933705.nq.gz
    ├── 3b72a1afc9bb0421489188419c91e65a82099f6a.nq.gz
    ├── 3e0cda6fd56d8ee0d26539dfbe311c8c52b61377.nq.gz
    ├── 3fc37720bdd8de2bf7d9068b1fa95bb56789618a.nq.gz
    ├── 3ff5e024465e2af7387bc2c8d2f06f8b01216fd8.nq.gz
    ├── 4061742f18e6b9292a52bc2b40404e611444332b.nq.gz
    ├── 40926cb993a4180ec87149e0b7245e2c3c4a3762.nq.gz
    ├── 40ebe3ffd1f1c93005dedaf895477b82603321eb.nq.gz
    ├── 419a054a12003bc456525161afe1900134b29751.nq.gz
    ├── 430091d81f39bd9eca425200907f205a4a249060.nq.gz
    ├── 4379fac275e3216e61ad79a8a790ea2ac500b772.nq.gz
    ├── 43a5ed6c38b1253ef7c38400b59c0804c5c80251.nq.gz
    ├── 43f3226c2980cbf341676dd40ddb3b02f3aac8ec.nq.gz
    ├── 441f91bd5a4707e4778ad94248741e878962be59.nq.gz
    ├── 457d2faf2671f9b1d94d59cf8b922bc5fcd7712c.nq.gz
    ├── 45aee13f0c7f40948b9f418b3b02f548820f163d.nq.gz
    ├── 45b7b21aa148bdc54b6d6d0efd61af50da0be7e4.nq.gz
    ├── 468f42dfe53bff308bed4a0ac4816fe8847d6727.nq.gz
    ├── 47a103d3a5747cb403e888f4503dcb20469e323e.nq.gz
    ├── 4805c14a75e532bc98e5c79d82a02d8d1bf9df86.nq.gz
    ├── 485738c5fd2605c968763386d1f66c6e355482b9.nq.gz
    ├── 4888906ea8cbb13a31a2f7c1b0f774ca5d5bad7f.nq.gz
    ├── 4942dbc89bd1352a5e1aa3794f8afc0d6627804b.nq.gz
    ├── 4961e5bd75165e691fb01853d88353cfab7f0367.nq.gz
    ├── 49871fd0b95faa257019c4a467dd459de37a88e6.nq.gz
    ├── 4afb3e372133a32a1e7edb9e43ce38a737b2dc8b.nq.gz
    ├── 4b4994e1f98d457373b83f9569484c88faf6fdea.nq.gz
    ├── 4b52e3ff82b2eb56961799dad96adc14ca163986.nq.gz
    ├── 4b637e9419bd3df9b5c23a0c3310c0fb7bfdc54a.nq.gz
    ├── 4c10bdfd4045bb7e3a375172ce05cde59f2ba590.nq.gz
    ├── 4c7de26af65fbbdf71633614e141614d3b6ecdd7.nq.gz
    ├── 4d0dbf00367a615ea5f563829c216a4aca634c05.nq.gz
    ├── 4d4e82966e38ce1f7854772fc5be6738e4c0e40a.nq.gz
    ├── 4d6aa0b2c538fa04b7f6aed8798a141b4ee16295.nq.gz
    ├── 4f6225577c40400816196263479387511660b872.nq.gz
    ├── 5020a79819d4817727ad0ac78bd8c79fe534e17c.nq.gz
    ├── 5039b605618231ab877e4b7a725b3dd6add9c5e7.nq.gz
    ├── 518f47b96662875d22eb48ddd1ab9788fc7c76de.nq.gz
    ├── 51c9e839ea5a3cc98620cdcf9723a7e6df30a76d.nq.gz
    ├── 51d4cc036d08f98776948189de8dd98a4b6b6eeb.nq.gz
    ├── 52310a44a8b3d35cc60ffdcc3b415bba1be6ddd8.nq.gz
    ├── 523bacbac236ad347cd09a153c6c79148e274490.nq.gz
    ├── 534ae9d4d5e54b8679719d6100c23fa52ac94d2f.nq.gz
    ├── 543cc8a354ea8104f902af571ea1c2ea3c6de4cb.nq.gz
    ├── 5474b1be1268465b817b7d9113a49449f8ce0bf1.nq.gz
    ├── 55891742245b84e0a0ef5fea27ac3d012bc181fa.nq.gz
    ├── 55e2b2bf50569d01f3d189df11673701049d69d9.nq.gz
    ├── 55e3e52b47ff990148737f24d62a4a6e7baa77a6.nq.gz
    ├── 569403cd274cac6ead8ff6487a01f252c33a1560.nq.gz
    ├── 574144f677e6d9065e9e4925aabc6ef1259feaab.nq.gz
    ├── 5751fccd71ca335cf7f75935017679d547de3792.nq.gz
    ├── 5839517d2948f5c9878a340637f56a6362e487f3.nq.gz
    ├── 58d0d028f59b2fe6cd25f439e59712e0c6df3646.nq.gz
    ├── 59842ba818c24b6b687ef14c98a8457604eb9601.nq.gz
    ├── 5990e9d8f5a6bade48b39f6a14e87b731498bc50.nq.gz
    ├── 59e06d72c4d6589d3ef69014965cd9c0a30b320a.nq.gz
    ├── 59ed755765c3b02f89e1aee17cb2e0629f364077.nq.gz
    ├── 5abf963c2d8808a970076778ae0626e567e7ef58.nq.gz
    ├── 5b23d05909b86a036e04229addbce38e7bc399a4.nq.gz
    ├── 5b7e65487b316822c3d61687023ab7f1e5ea3535.nq.gz
    ├── 5bde28c91897917749a82672d461a66f9a80bcd3.nq.gz
    ├── 5d9c3999a7f5e78796b4e8b8b5721568a40689ae.nq.gz
    ├── 5de350dbcd14a7b2cce3ccb79fa03f848af68795.nq.gz
    ├── 5df76f0adeaf0e57caa8fde1c8c90f464cba8ed3.nq.gz
    ├── 5e0187f46898b0e3d9b9f78bc49122302963896f.nq.gz
    ├── 5e0824f5c53d40f75f69ddd3f59f93b197a5689c.nq.gz
    ├── 5f1bc0c69f9c453087f52f6bf9cbc7d3403ce6f9.nq.gz
    ├── 5f5de2adf184326e6de28feadea407aafbbdfcc1.nq.gz
    ├── 5f98bce5e664d6721a4dc92dde653bf3935ef3ae.nq.gz
    ├── 606ce16b4d0c7a0cd6c83917f8f6bc5ad6410785.nq.gz
    ├── 60dd71cd55ac02667242befba1b9888a79c4a6da.nq.gz
    ├── 60e31cdc0eeee2b90bad7fddd72b847b87e5a131.nq.gz
    ├── 61259124a8c1bb87ceb9b5180bea92d33d3571f6.nq.gz
    ├── 612fddddb026e1b74d118c32652b6f6ca9c6ef49.nq.gz
    ├── 6139d972bdf465339f4d870927ce1d03de0f5451.nq.gz
    ├── 620e8f25e35fb99ebbc81035e75523498f28406f.nq.gz
    ├── 63da210c5855d28a0fde1877d278391bdbe2be56.nq.gz
    ├── 64300f01efc9d0dcaa86fd5b224e4e8b6e75d205.nq.gz
    ├── 6487ecb024396601318ca0e8b2c7595ae7aeb788.nq.gz
    ├── 651426bfa32888f2c9aa07b690369dc84b2bdd4d.nq.gz
    ├── 65811bfeba419cc14c56f65386cb124d399595cb.nq.gz
    ├── 6598796007c172218ca55dbcbcd90d08e520e890.nq.gz
    └── 65d5052d2778f0055f2ce3b259166049634f190a.nq.gz

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

[cucumber/cucumber-ruby](https://github.com/cucumber/cucumber-ruby)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
