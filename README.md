# Repolex Knowledge Graph of allenai/molmo-motion

RDF knowledge graph data for [allenai/molmo-motion](https://github.com/allenai/molmo-motion), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/molmo-motion
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ab7c5f4e7c49359e4275e9a9b21a59659be17386
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ab7c5f4e7c49359e4275e9a9b21a59659be17386
│           └── chunk-001.nq.gz
├── blob
│   ├── 04511a81cc6118eb3668ae9c2d41c2948d4fea18.nq.gz
│   ├── 061a8eede1da5c4b78a0035e93280c90aed76960.nq.gz
│   ├── 07d2dea9aa947ed9ef5e6c6dc8ebc40157a1d5aa.nq.gz
│   ├── 0869c5f23d9b5ae9bd59e9a1f84430a9360fb528.nq.gz
│   ├── 086d2468dcd2954a60d74c3ad0c7bd318d53bbc2.nq.gz
│   ├── 09bd747ddbbe03199b6faddc72c1c527c0a32da9.nq.gz
│   ├── 0a5d88a956ee53b252b0469f572e09ebd9a2141e.nq.gz
│   ├── 0b4eefa29cd659b9e8d709661ed888e62b51a385.nq.gz
│   ├── 0e39ac407f35b695055fe72d3a5300f9de6eb878.nq.gz
│   ├── 105af2cb05b294cfd2b8d23d4b351dccc9a70f8a.nq.gz
│   ├── 1134690fb27cf5e64a8b91718d896dfdf421ae1a.nq.gz
│   ├── 11a91b7e1a86a01e446f9c004e6ced02e056c8fe.nq.gz
│   ├── 13229522821906225686ea7d9b5d12a00d3cbbc1.nq.gz
│   ├── 14840a30fbd9e5b8a2a5d86b45dac37f08bb926d.nq.gz
│   ├── 155063d15c40ef1d7c5f9382fe25ac42fd1cc20c.nq.gz
│   ├── 15b35a30a42e9ba0eac3a2bd9b7215173ee0bbfb.nq.gz
│   ├── 17d4b2399097c7ae0da26fed5efdbebf1732ac7e.nq.gz
│   ├── 1a183eb28c22391f8fc23e654e85ae82370c51c9.nq.gz
│   ├── 1a254d2fef1892dfc1085a64834a70f9af1e33dd.nq.gz
│   ├── 1a611dd794740d16f435e70d6460545c79bdcda5.nq.gz
│   ├── 1aa0fa46347e30121c877f28550b3a9cd949097e.nq.gz
│   ├── 1d10c7d453c1a03dcbf090da790f58443e3aa9fa.nq.gz
│   ├── 1e1a7dbbd050bf751a785f78631019b6b81ddfb8.nq.gz
│   ├── 215edb721c8f5f023d494d40f05c9071cba6623c.nq.gz
│   ├── 22eac237b9d6eb175cb6b8b5eff93a2fec88cc54.nq.gz
│   ├── 2529ba0bf2df0c3dcf295f315c30c8055bf2f226.nq.gz
│   ├── 26393edcf5e02762c22a9b26c9b4404799c44320.nq.gz
│   ├── 2640b95038f9ba7f920eff9bac6e3286e0255513.nq.gz
│   ├── 26a54542ea6642e499f11e212d8b5e11d353bbbf.nq.gz
│   ├── 27c6275330a17d159d2827ebe55ae3b5d0c09d82.nq.gz
│   ├── 28976cbcf10dbdba8ac80d6111a1e8831ec3078e.nq.gz
│   ├── 2eae98aed9307873780395a5c47cd6ffeee4622b.nq.gz
│   ├── 2f01ed1cdd8268ad2038a2449a03267f6ea46405.nq.gz
│   ├── 33685d8f99d74afe4be7d369a3cb35cf20c7afe1.nq.gz
│   ├── 347cc3e1ea6b0736753ebd434580d59bb040856a.nq.gz
│   ├── 356be8ff8b3f78f91cc4d29694afba169430a938.nq.gz
│   ├── 359ae7df24355d362a48977f5ff4ced99fb56820.nq.gz
│   ├── 3a922d6b1795436ee80f55dbd7d3990adede05d6.nq.gz
│   ├── 3c00b208193c164d1d1af81f06d2a069c1a118dc.nq.gz
│   ├── 3dc1f76bc69e3f559bee6253b24fc93acee9e1f9.nq.gz
│   ├── 3f26930298c0238912116d9c079c8f442cb6bfd7.nq.gz
│   ├── 4051a3c0ff52022cdeb575e8bbc453e41a2a3e66.nq.gz
│   ├── 41a53b4721bec2994592f170bc579a37a4ebbf28.nq.gz
│   ├── 42c0a7baab0fc946b52d532a2e778d9100a93dfa.nq.gz
│   ├── 42c89e452e897bb5c47e40648ffd07ccc1ecba24.nq.gz
│   ├── 44086ec078c615d795246c73e444cf64aa05d5cf.nq.gz
│   ├── 448c18d3588bc130e3faa7af5c07b28fde0cc809.nq.gz
│   ├── 45344637bfe738c86bc42bfd2fac2d2998e69041.nq.gz
│   ├── 453800e2d271e932a97981d223ad7682fa17b480.nq.gz
│   ├── 46a01e81a3ebf212afe8698f84eeaff86585ac39.nq.gz
│   ├── 48fc69c0b3c883d0e48aa96773c4b9950ce3e76b.nq.gz
│   ├── 499a663a983568c74d31f3d6aee9a24002e05997.nq.gz
│   ├── 49a7e0e9f5311ac96a4de8d09a59d50ef3fefa13.nq.gz
│   ├── 4c63de390b8f611d27d09e87e89b4d995ea70d7d.nq.gz
│   ├── 4d6bce565068ce778cc36dea94f3bea64cd04e05.nq.gz
│   ├── 4e0e0af7362c56bc3fa9171fbcc1c4734abb2d6c.nq.gz
│   ├── 50ea01904dde24f1ccef2764d600580e60dff6ef.nq.gz
│   ├── 5104f00838113262c1fa423dbd4f8118625f0d92.nq.gz
│   ├── 53ae327e1cbe514140123cc611309a1c176f1fab.nq.gz
│   ├── 558ec5b8929cbc51353214677b3863d1250822af.nq.gz
│   ├── 55e49e609cbd9e22cb5c444a28243522d98c4014.nq.gz
│   ├── 577f6b32122f96428bd635daddab6ed0dfbc48ac.nq.gz
│   ├── 58910f06a504bf912426354692be08cf64a0fa09.nq.gz
│   ├── 591e1ff65346661cc8830989390dea2016eb39d4.nq.gz
│   ├── 59435c58a61217a9c41febfd7d406ce6bcf7ddf7.nq.gz
│   ├── 59a28243db7f80536aa29ef07e582b61e63223e0.nq.gz
│   ├── 5c685178cabd183f1e155361a50694e9b7faaae1.nq.gz
│   ├── 5e29031b8141a470b40e3c3f3f55dbe4db02800e.nq.gz
│   ├── 5f1292eceb507dc3234b4f77b2ff0492181013f1.nq.gz
│   ├── 60576773742c19adc68f9726e59da441d9732516.nq.gz
│   ├── 60576d9424af8e04c3d1e5cc6193bf7e633c1a6e.nq.gz
│   ├── 614ab699bdab8289e87894697c780f49369cc9c3.nq.gz
│   ├── 616b91b6cd3f70e99f8655a61416860511d15daf.nq.gz
│   ├── 622e635651ebd9786eb21a9c64c77a46eda3624a.nq.gz
│   ├── 637c9c0574c4b83878960cc42473a9d3edffc13e.nq.gz
│   ├── 64473d5374738f6542c3b85e203085bf096704c3.nq.gz
│   ├── 661f2e56e4ff88e38d1f82a8a796a5eade82de20.nq.gz
│   ├── 67b64bc453f0502a658e5366f629ec268a1ef40f.nq.gz
│   ├── 67eb20ee81e6fae25c771ecefd0a3d12ec1fa971.nq.gz
│   ├── 69522ca624ae6b9dd70871913913dc6438474e55.nq.gz
│   ├── 6aaa3e4f33132e589cf7072d2e09f3429f3d4279.nq.gz
│   ├── 6aea1ab95b46bbeeb2eb1a6938d9d2bd501313be.nq.gz
│   ├── 6d188584a5082c47e4077c8b95cf1e84559d840c.nq.gz
│   ├── 6ea49577408ad5666447d000e42acfe6d92c7384.nq.gz
│   ├── 6f685df0476f7a7da51f9f46fdca442efa9149a4.nq.gz
│   ├── 6fcd143acdbc5c57712ad98657bd36cf03ec9a32.nq.gz
│   ├── 6fed6ad3f785d0237cfcf856b53355de918ca58f.nq.gz
│   ├── 73af41747c7e793b81ed8769cf73e7b9de0f3fb8.nq.gz
│   ├── 74c6ce546d4f63e337c68c01d89ad56ca5fa59f6.nq.gz
│   ├── 76f2cdaea6e3cfddf52d7f82a69398a0c1cc861f.nq.gz
│   ├── 789989dcc1d1dc8c5bcc9721c1893e8d893f3e1d.nq.gz
│   ├── 7a5df4fd288574e62480cdbdaefe5e1b6a0edc4a.nq.gz
│   ├── 7afdfbfe5973875a94c3e34a486d342bb2ff02cd.nq.gz
│   ├── 7b09f886f7cb95e61197120164658a86639ca51d.nq.gz
│   ├── 7b0a1289d916b2a0463b740c73fea63c34e784c3.nq.gz
│   ├── 7beb1e0460b1432cf5f717f2f7662812c0d1022a.nq.gz
│   ├── 7d0180ea1e992e4b0b6281f13bbd093bc54f7ed7.nq.gz
│   ├── 7e1978a07ce2b0be69dfea0ed176f1e82ee5a79d.nq.gz
│   ├── 7ffe077b417b0550f4c52c30205220ae91d7dff2.nq.gz
│   ├── 8563827a5a77e6fed72247ece2a6b062f64d22a3.nq.gz
│   ├── 8814bb5544e05210b1af6888b8053b186bde07fd.nq.gz
│   ├── 8860f5d2afd1ba0aa376f0684aff8fa5f04b88a5.nq.gz
│   ├── 890a19579c0dcedf5b1d6ba501c67f8de22eb43a.nq.gz
│   ├── 8a7311d8818664f448c9b76b3df1f40bdd8abe71.nq.gz
│   ├── 8af33721a5846307bc2172c08504304d4501a329.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8c38e220da59346fda5f4d3e00082800905f277d.nq.gz
│   ├── 8d88e990e9593768dbe09ca2bcaf17ae3da2013f.nq.gz
│   ├── 8ef829f3ce3d5aa12183c9177290379b9deb1856.nq.gz
│   ├── 91d7a9d672cb4e38a92574c20033997969f3ced0.nq.gz
│   ├── 92032da740e3420a4f697dbbef063c0e4e2a29ac.nq.gz
│   ├── 931162429a4c1af4eb5c572f674b851dd0046b97.nq.gz
│   ├── 93d9ca0332736c32fe9f20d4c3f110ed78ab8ba5.nq.gz
│   ├── 950b9630561f082472fda0a3d93c0286e7d74790.nq.gz
│   ├── 9593950d08fd506b6705e58ff09c98abd0c9b20d.nq.gz
│   ├── 965c3ebb0d2fb8e7b3fe2fdef40b4a2740ac96e7.nq.gz
│   ├── 968a1f661c64ea178b9fea35356aadddc33deda6.nq.gz
│   ├── 9b2871077d3de0f789aa3e99e4903a2716b25515.nq.gz
│   ├── 9c65e49ee8cdb59141f3470446882eef1e9d7fb4.nq.gz
│   ├── 9e55f54eef8a7e976980825fee990b6c5483a448.nq.gz
│   ├── 9ee19037077d2e65a0e847a057a0bca747feaad2.nq.gz
│   ├── 9fe4e90c606d92bb5b23db1025dfdf4df95891e2.nq.gz
│   ├── 9feaee1d99cd0a42b0b5a3ffe436e61ac36c7143.nq.gz
│   ├── a1600b4a134bc21e39d58158855d51a6bccd67ef.nq.gz
│   ├── a1700ef4ac41fc068bf8c99f075108f31e418a26.nq.gz
│   ├── a1e4b1c865a21d1cdbc4c350fe53be11bf4a6511.nq.gz
│   ├── a56e1fad22c85476cdbf4e9964ee325911dcd083.nq.gz
│   ├── a5e19b50b1c64ed24306a7ca3f20fff7d3d90c33.nq.gz
│   ├── ab0c2b79ed357690062c943b15fb563e7aa70a75.nq.gz
│   ├── abbd960adfad1bb46c89eaba4b2e9f43f3b84f01.nq.gz
│   ├── acaec8f6add94e17482e8362b7afa82126f445d5.nq.gz
│   ├── afeeef70fa1efee7576fe907e1352c51f7292d7a.nq.gz
│   ├── b05da68f78e331f926a48291dbf4b5b936452c20.nq.gz
│   ├── b0ae1d7f2961ca97591c29458100c143b4026a78.nq.gz
│   ├── b29ac4a58e8321259f0263dd69fa45276c00c6ab.nq.gz
│   ├── b3a8b8b0687d625cb78d668774c3ab6c7a6790be.nq.gz
│   ├── b4ec716d5a0dd680aebbfe38b35b9916279dd447.nq.gz
│   ├── b7ad706444dce795af2981773f06e33478faa1b8.nq.gz
│   ├── bb3dabf6a437371e13e17ce4f90d49268abce223.nq.gz
│   ├── bbfe8a98fff1aa22bdadff26c1a3bf06993719f1.nq.gz
│   ├── beaaa91e4ee6758d1f9eb466840b304133abe3ed.nq.gz
│   ├── bf74ee61db60534591d5c7ca4c546fdd1b74b52f.nq.gz
│   ├── c157d609b2ee73beb7aec18d489041932094fc32.nq.gz
│   ├── c2312ac6410afc3cf1d6eeb68cad6a50afd9de45.nq.gz
│   ├── c425a276fb5b5492b1cf818874ce6292645a1474.nq.gz
│   ├── c5e73262e19057a942eb93639a4a56f950327c64.nq.gz
│   ├── c7975f9b9cbf61cb522b195e2e524b214f9349ec.nq.gz
│   ├── c7dd5f5f553eec824beb3872a8840950dbecbbfb.nq.gz
│   ├── c80b682ae7cb8458559f42c99c349f5f64aaacc8.nq.gz
│   ├── c9ab9f69cb861fe440a9e48378dc83429131be6c.nq.gz
│   ├── caf39a00b3ebc67deeee1e8a0fab834bc757a1c3.nq.gz
│   ├── cca4b390d78e5ce733114c4765415626b88dbfad.nq.gz
│   ├── d1aaa0ed629a1ab62efe228f9f1425d6212ef5d3.nq.gz
│   ├── d5548b8f42997a1d5e82745b570dfc9e70d0b266.nq.gz
│   ├── d60ac385f54003f69552d35ad7fe209e1a8e9efc.nq.gz
│   ├── d9b24d7fb38f09f3a3f9cf36c3ace7e440a7173f.nq.gz
│   ├── db333e2ff6bbeff279eb732febb7330424a89911.nq.gz
│   ├── db9cba2a39be065446ee1773e96745834c7419e0.nq.gz
│   ├── de369dae008a5f17d23a6758f8f6f7da8f3c51bc.nq.gz
│   ├── df951ce4b53bac083068a306164a3843844d5458.nq.gz
│   ├── dfcce2468800ea2ddba6f3b5cc1efb4426d9745f.nq.gz
│   ├── e06e31dfc9cb2567be8de434616b89ecd3d0ca08.nq.gz
│   ├── e3df8fb45e9863fd1f120352ac4754756449902a.nq.gz
│   ├── e52a35e01ad64376c54c6ed78d315984a9f4817a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e865d37be4cdd9ce60e0a3810ec1c3a653e72c90.nq.gz
│   ├── e8a4b530d5a7dea68e40c948420d8bba85336332.nq.gz
│   ├── eb626996eb487e7ea4b5eeca2caf78b07dfb4ab7.nq.gz
│   ├── ed45dcd83cd0dba505fdd05280bac6c7179bf5c9.nq.gz
│   ├── ee86b6d9e1e7618ba21bd2c32ec7e9616a37b5eb.nq.gz
│   ├── f22e657e5fbbe4b1c6774ab77cfad6cb20d5ae1a.nq.gz
│   ├── f2bd015cb6d5c109043d4a2c0d235e46f6684c59.nq.gz
│   ├── f373ccd61de6be1082927721e1c9ce82763a4dd0.nq.gz
│   ├── f3ce7fd4d1eef48d679e65833a698fcaf21b5dc3.nq.gz
│   ├── f4a14332a13b00e7105cc7291891ae0ff71d4192.nq.gz
│   ├── f7570de6eaeca4a7f777b0108aacbffa9081ef8d.nq.gz
│   ├── f96ef1a2622860d3f2231ca9129f4f4775a35443.nq.gz
│   ├── fa904b6bea09e5724ffc5a6407dcec7f3d867360.nq.gz
│   ├── fb59bddb93dacb4a531d8915d22d3248507c33d6.nq.gz
│   ├── fd0181c83a8f9d1ce313e1984b062089e2e460cd.nq.gz
│   └── fd18b9cfa919f19a61f08ae313c61671f98774f5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ab7c5f4e7c49359e4275e9a9b21a59659be17386.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 189 files
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

[allenai/molmo-motion](https://github.com/allenai/molmo-motion)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
