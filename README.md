# Repolex Knowledge Graph of tinytag/tinytag

RDF knowledge graph data for [tinytag/tinytag](https://github.com/tinytag/tinytag), parsed by [repolex](https://repolex.ai).

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
rlex download tinytag/tinytag
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ea5be2b7cf9ba51452bf01e42c6dfae04357e94a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ea5be2b7cf9ba51452bf01e42c6dfae04357e94a
│           └── chunk-001.nq.gz
└── blob
    ├── 026ac5d10e204c8a691ad6b61846e49ecc94a9bc.nq.gz
    ├── 026de1d152a88dbae40396770f2e8dcc9ac5517b.nq.gz
    ├── 02b59ab65b04ea25f6dcf427c61c2eb227543fbb.nq.gz
    ├── 04f026883f263cd0eef832514d24762235a44ba3.nq.gz
    ├── 0595e47e7a6dc2fad3c09d280bcb1985cd619fdf.nq.gz
    ├── 05bad19c4ead9edd316541353ca3ffe4632d4a08.nq.gz
    ├── 05dfc6bb2a1b3c46455946081cda2a2691297119.nq.gz
    ├── 072b8cb00e57dc7f21783009b9c2e8f18dc9ab6f.nq.gz
    ├── 09477c32ddc96b0670b852b7703d4a8e5bd5ff41.nq.gz
    ├── 09a1cc16e19aff2d55416cf563b8af20f1666fc6.nq.gz
    ├── 0c2d62f280cd8867c230694682db5070eb358e00.nq.gz
    ├── 0c327c906b744dfe998ca3aa4c3fbdf4d007fbaf.nq.gz
    ├── 0d7bfdeb0ed0c3ffe6fb4c67bbc71dc76e0df20b.nq.gz
    ├── 0e259d42c996742e9e3cba14c677129b2c1b6311.nq.gz
    ├── 0e556757627dcbf79c10d4c3025e6d9596c21217.nq.gz
    ├── 0e8c4bdcad6fb763fd7c04c327b7d54b865b6520.nq.gz
    ├── 0fdbdcd511d1fda2caafd9ad3801362593c3ec41.nq.gz
    ├── 13b6f5d2a419c2cb47db582108ff01a014285913.nq.gz
    ├── 14d20e3cf73869cf4408ae9be0d7ac62afa5ea38.nq.gz
    ├── 153edfc926edacc03b3afcc54bc0a12449c5cc90.nq.gz
    ├── 16ba279f6421e3b48da709a41d796b3f75524f57.nq.gz
    ├── 16e85bf242ee15aae455f81b8610e263c761bad6.nq.gz
    ├── 17140daae36227a3105f83ea57389c3e82bba0df.nq.gz
    ├── 186689aef23227ff8f5cf5c3b67901dbde533f4f.nq.gz
    ├── 1a05c0de04edb9586c831b88da9c2666cd8b24c0.nq.gz
    ├── 1a5af0dd316000cc672e71b23e34bf073aef5d12.nq.gz
    ├── 1aa79bc36634eed333e2310c1bf941d565d3254f.nq.gz
    ├── 1b6f9be7ff9e8f663fa02d98e8b3d0f2816052c2.nq.gz
    ├── 1cdcbbe604969ec3799b249b2f247ee4b12c30b3.nq.gz
    ├── 1d170dc3395c4ebe8ee29b7c70c14330569c1dad.nq.gz
    ├── 1d7c383bca5bc9edcdd9df6e8c70f154a254f9a3.nq.gz
    ├── 1ed22955aef32bd2737bc7fe2ae881d5c3d17063.nq.gz
    ├── 2118a69b949362b95bf2db8c2371bc3da9b99067.nq.gz
    ├── 218ef46a1f71c15671407dcea5d64978274d0014.nq.gz
    ├── 2213b68d07917ef8afe3b106351c2929ecbc5c5e.nq.gz
    ├── 23c5dad36197793e21e0df10a6d8e3c8b3b9d8c0.nq.gz
    ├── 23e2defb92694883b084c7c756f8e589a3ebadf0.nq.gz
    ├── 24780dd0bdf18d79dcf2e7fc15cea4e3bcf59865.nq.gz
    ├── 26d726acb19010283cdd40355eff41d18989a9a2.nq.gz
    ├── 293a54bf24ab6d5ae5f3064c8bd3b305353e6228.nq.gz
    ├── 294d5f1771766acf088625cf72ec985e8dc27f1c.nq.gz
    ├── 2a2baa188998a41e97e3ef72bd107b4702816890.nq.gz
    ├── 2b9ca16ed6bc18f93f7fe14638d276ce199f545c.nq.gz
    ├── 2c2db9d812b09e19e64aa82cfb1b42ccc4966851.nq.gz
    ├── 2cb560eff147632ff3ad80565a20d0460da05473.nq.gz
    ├── 2e7955232707b384e4826514284bfc31a46b08ea.nq.gz
    ├── 2f4ea41b8e3ef200207ce7e3ba1440226e1e2f45.nq.gz
    ├── 2f72f317c2dfeec07954cc05df5d486386a3deba.nq.gz
    ├── 307563d7718a5b2a4f07690353c5ff68905fa304.nq.gz
    ├── 30f8d3ca0e3c68db1ed362ee84f5e6572683ac71.nq.gz
    ├── 31a87611d03d5f7db85b8cb35a6a76f05e6e1237.nq.gz
    ├── 31aeb4d8d435976a70b3a2821201ba722f786503.nq.gz
    ├── 3215d2ff3328c2e30af8eda9f0ab0a49a65c5ec3.nq.gz
    ├── 33b1559b4c66ec2dc452147f3df8f5733f712aaf.nq.gz
    ├── 33bffa0a1cc5a270356f1cfaf03d36ba6464b1f2.nq.gz
    ├── 3505c17eb4e32cd3fe3a5e6ab51fdb9271a8d90e.nq.gz
    ├── 37db568e0be8abde66315d882fcdd941b6f10e63.nq.gz
    ├── 3af58208a423be8a15537300e1bd31b2b73d0fb4.nq.gz
    ├── 3c6416a061448b7d87dcbee836d4f606c3f3e7bf.nq.gz
    ├── 3df77bffb30f50c0bf093be26f45a9b4ed99b2b0.nq.gz
    ├── 3dfea19e4d9b41e7b445674753cbac98954073f1.nq.gz
    ├── 3ed982521464dc6dc68fd2a942db251e4afa9901.nq.gz
    ├── 41714416760792085717cb85fa1542e5a7e28981.nq.gz
    ├── 42ccfdfa762b7ac1ae54c42b9f8cf788c934260a.nq.gz
    ├── 431ed9c9d2eb845d4b79d817d6773390c1130008.nq.gz
    ├── 4431706fd3230ac3bb765f454eede97bf69adb3d.nq.gz
    ├── 44a4b1588adef59a7702710ac27a13b78315bd3b.nq.gz
    ├── 44dc4e5ffb624273e839950c65361110e0a3e7b8.nq.gz
    ├── 453ece33c3c872d253665a5505e8b40e52f539e0.nq.gz
    ├── 4907e6391eef3a669e2b4b158b746d77e56fce89.nq.gz
    ├── 49a835c92bfaac646d20195fed3cf21658a86408.nq.gz
    ├── 49f368127a2552629a8f184eec4597b21a146b34.nq.gz
    ├── 4b7322de04f3273a1d099c9295cf8b093a465925.nq.gz
    ├── 4e2b326c29630d1a62ddad14bcc6f54abe1e9df6.nq.gz
    ├── 4f42283566597c76d2e1b95fc7cf915f874d536f.nq.gz
    ├── 4ff77a709f78b20a5367329e9433f373e55f3ae0.nq.gz
    ├── 50cb4f21e83f77c2d6c2f884fdd9de56faf95be9.nq.gz
    ├── 524f62ac02d0578a2ecc10df7fe17dcf939f3662.nq.gz
    ├── 55c919506eac42dc10c832e14da5df8f5e456f84.nq.gz
    ├── 569d806ab7dbb522b314d501bd8822ed930b6e88.nq.gz
    ├── 572747825e67532d813247f2981ee8769fc20198.nq.gz
    ├── 57835395b61f0c4757df6c8a2da16accfbe989b2.nq.gz
    ├── 57abf14afbc18221bba8cb296b52eb664ad834fc.nq.gz
    ├── 588b649d96c0443521c8669d46fce88cb7b091d7.nq.gz
    ├── 595680bb91ad1400e13e69fd23149de650dbb229.nq.gz
    ├── 5a64758973239ce836c0b252ea6425731aafc540.nq.gz
    ├── 5a808d2a96017e168f2cd04952c2824721591f6e.nq.gz
    ├── 5d9916254215a6936c1075e85da8f6f743f43c82.nq.gz
    ├── 5de4f3b2d879bae0a41710cea4d0b1aad9309124.nq.gz
    ├── 5e59008f261c0c03958101db3bf78981416a2188.nq.gz
    ├── 5f26b43eabbd2d7d8b1ac00e1ff9906970c458f0.nq.gz
    ├── 601cb0142fb6acdf11a5ae57c7ac6f5693039fc1.nq.gz
    ├── 60248668b88c5cc0f3f25b199eb1031f4c93444f.nq.gz
    ├── 614eb573719511350a076b5b9d40e4eb34757b5f.nq.gz
    ├── 61dd2408a9acac2f5c2685c1649e47a705681534.nq.gz
    ├── 624ef10a1f74562ca8a6ddc5aa42f928949d8b71.nq.gz
    ├── 6286259f3837c48789e4984cb7cc1ffa5fab5d4f.nq.gz
    ├── 62aa53b773c89d2f57c9d006c80050ad40c2ffa1.nq.gz
    ├── 6342e3d88023a47616bf6dfbf1a699f537821335.nq.gz
    ├── 6421ae085865436aee7fea71ff14916b09566a23.nq.gz
    ├── 644c0e0db672943a95c77e13bb948ef69da2e2e1.nq.gz
    ├── 65989abafdad04df82525dde5affed203ae22637.nq.gz
    ├── 6620e22918b7c0ba95a77c7ab3b583eb7bcb92ae.nq.gz
    ├── 66ee13f02e28303978cf6cc875f089abff332dbb.nq.gz
    ├── 67265613d49aad1ccd3e66b0184582f13ff5b9a4.nq.gz
    ├── 689bbc33eb74d2f8dd6b8bac2a8b9cf15e1ac0dd.nq.gz
    ├── 68ba7ca15ed3e5963dbe791e1efd26fb94dcf9d7.nq.gz
    ├── 6984412b47f27ff13204c7a3574aa4ab2971ca57.nq.gz
    ├── 6a40e026190fca3f08b759df185b5f10bb437ecc.nq.gz
    ├── 6cc4c88188d3ecb1bba3a979bcb6af9159008f69.nq.gz
    ├── 6d2e9930c8cba148b65907a2e73d8666241128fd.nq.gz
    ├── 6eae87e84fc94bd38cd1f6e3850f087a82d22523.nq.gz
    ├── 6f426d7689113cf31a1cefb74b8c383b33dd9db6.nq.gz
    ├── 6febe87eb7505ee537e3b59022daabdfb50912c1.nq.gz
    ├── 7141d718e0a88512ce9223cf308d91f2faea1fe0.nq.gz
    ├── 723253c4fa3b91fe72eae939297681d0cb5a9545.nq.gz
    ├── 7387f2e093a1acb0ba7ad8a75f2ef03c0d517d9b.nq.gz
    ├── 740dbcd22995d4eaa143fca9ce3799276f08f965.nq.gz
    ├── 77e6b1a87961bc7103daa0e0f952a4b8ea15e9db.nq.gz
    ├── 78793735b26891081721369e5aa0b17495ede9ea.nq.gz
    ├── 7ab9791e2015d3b3717c8769db529908ecd75810.nq.gz
    ├── 7c0646bfd53c1f0ed45ffd81563f30017717ca58.nq.gz
    ├── 7cc799936ee70e54a69698226e34717cbad77e30.nq.gz
    ├── 7d9c6872437a914bcca0f1a258e060523e214971.nq.gz
    ├── 7df777e0c4a1eac91bd5a5702c4d4f1979a29ec7.nq.gz
    ├── 8029ecd56e083676d12ac2a2efa7ddcda44fe4b7.nq.gz
    ├── 8156ba3a2fd675d2cc80170ebc4b4aa7c9f34707.nq.gz
    ├── 825d9d49bac19256c15b3be611cb41a0d2879874.nq.gz
    ├── 859dc0b4b77f73aaff8d16855a7854055368a84c.nq.gz
    ├── 893800c585533d9753fb2e40b46d569922598208.nq.gz
    ├── 89b983bd0f6f61c1211d8bbbeb03369c172759fa.nq.gz
    ├── 89f730ace5d84aab0b62f09fc4183f1bbbe5ffca.nq.gz
    ├── 8c1e15fdec55abd3ef3c09cf642310361ef47c2c.nq.gz
    ├── 8c42c911c2d57496cafb68c0cce8ad5ed599bb5c.nq.gz
    ├── 8c55ade51440ecc9df74863a405caf055bcf00cd.nq.gz
    ├── 8d36804e32c9193c8517b19414776a7914f27edc.nq.gz
    ├── 8e057fe0f600f47c5b81e169d787581c05295507.nq.gz
    ├── 8e8dd88757f1b7e54bc105eda3d768f135849d9f.nq.gz
    ├── 8f15b980266ed1d7bfdaf30b11d890f91035cf30.nq.gz
    ├── 9051b2565f3a474aac8bd356cc93abb3e0dedf5a.nq.gz
    ├── 908e5b6a9fdecd4f1cc3891e0b202056628bc18c.nq.gz
    ├── 90b6ee94f4c05cef10b678f3b43e271e583613ab.nq.gz
    ├── 921f6bd5e7c7da7a6e4e6bbfe1d4cf6aee15c00d.nq.gz
    ├── 92d115e329b804b527b32f6e083be34e14d4a597.nq.gz
    ├── 939031071359313d7d8bdbc8e792f048792ca784.nq.gz
    ├── 93b3fe0ba6af77d28e73c8d9272352b5871b8ece.nq.gz
    ├── 93bacea85d511a085c3de97d20a45cc11e8386ea.nq.gz
    ├── 9503aed9e801ac2ce0103492f2e134a0ffc35462.nq.gz
    ├── 96be6222eb87d226a7ced9c018400f7a56b2f69f.nq.gz
    ├── 9861d2c104aa24becade801c891014dccf7fd830.nq.gz
    ├── 987ee417c3eb84cf41fddf1ebadab523694d2e5f.nq.gz
    ├── 993634f57a6f86431966059aee726e23e6e7eec5.nq.gz
    ├── 9b438854e12067f14192fc319b0b21c1bb403a49.nq.gz
    ├── 9d360819eb7622a51fc5833094bd78b90c017da9.nq.gz
    ├── a3cdadc3c0cd065d232819917c12b8387574db43.nq.gz
    ├── a415ac0185af3b8c3d4dbe7a9fdee27179f069a7.nq.gz
    ├── a465a52200dbba11c130aa32334a65c6332ac332.nq.gz
    ├── a715c84776842af9b78c18d9454ac9c46686918d.nq.gz
    ├── a725b8876697b32eb614621ac8e1a4617eb11f13.nq.gz
    ├── a8455f6024d8e1910b14b43065d783b97a01e31d.nq.gz
    ├── a8c5edcedfa2b0deb565cd12e873b3d9bc2de9b2.nq.gz
    ├── a99f68b526b1be6e90ed52b406d6029226cd33af.nq.gz
    ├── aa533104d6fde177772775137cb7660a3be11418.nq.gz
    ├── ac0dbd86e5a92ed312217376dd7f2704fb50db7c.nq.gz
    ├── acf8dacccbfbc92559c751d341392afe77a3af27.nq.gz
    ├── ad4a6de33170ed3c854ff5074c278ef63e2e4a77.nq.gz
    ├── af3f62854f8e8aa0ca53affbe5214b802d8cbd9b.nq.gz
    ├── af9c67caf695db2ef6afdd715f3ea65bcf4d35a1.nq.gz
    ├── b1157cf63a1373a099e8ab0e2cd627387f563f02.nq.gz
    ├── b19a06efbeddce435871aa2338647631ae474f1e.nq.gz
    ├── b212c903bec18314e9d3161a56af85b8a0913bd7.nq.gz
    ├── b23c9fd0e4d0081c5fb1a3c10a9bf91ea590ea5e.nq.gz
    ├── b43ea2635da82eb0688cdc278178a28559068547.nq.gz
    ├── b66884077c32c01a51dc64b61783da04bbfa81ae.nq.gz
    ├── b7554f49265d5610c2248fa9c6a6052ec917e080.nq.gz
    ├── b7882f89f3402cc3b5722ac818478cffdc876057.nq.gz
    ├── b81b0c14fcc5544d10b39949743d263f048aecbf.nq.gz
    ├── b83632b48b26fa5dfd5fd94b564ab285cc287f7c.nq.gz
    ├── b8aaea00a2d98cffe2f5bc851dc56e7b3e12e5b4.nq.gz
    ├── ba37c1e3315db2bde061e9e33819c22f7bb6d696.nq.gz
    ├── bbc02502ffdad4f7b9d460385e1052daf77efde0.nq.gz
    ├── bbc9739be5481d8eda3aa5717be6cffb8abc408f.nq.gz
    ├── bbf89fb6d73cd4551f2bad3898525bea8bf64762.nq.gz
    ├── bc2194b023601b0535b50bbb6e25dd9cb7010e6d.nq.gz
    ├── be1432bedc2f90c09b154e3c98ac218d4daf0fc3.nq.gz
    ├── be40b11696091a8eae010d398793c95e1ff9f8fc.nq.gz
    ├── c048ce6f56fad0f38ed787bba04feade53ea74ef.nq.gz
    ├── c3153d4e664bd7a76c321ebb4b8afd6dc99463a9.nq.gz
    ├── c35476996b2463c235133da2f7fd6d8855a083f7.nq.gz
    ├── c4432b4e5173bd0f2df506f9cd112cbd43cf36ea.nq.gz
    ├── c472ccf03960b0876c1e6020ae8c762e46997897.nq.gz
    ├── c52254e2c86d724a73a3d55a0af5566882e25fea.nq.gz
    ├── c5d43cb8250073c29b44eb62a93943dc0bdff61b.nq.gz
    ├── c855b1141b06441f6260c1417dd3903a7a2e6025.nq.gz
    ├── cb4c187613f5f32c63f64ea325881a2cfb318928.nq.gz
    ├── cbb0e37e96691c4cebcde5173a6e956c4f5eb273.nq.gz
    ├── cca5aa351c22888a412c41cdd465875f650b959d.nq.gz
    └── cccc116c203660cd5531d4639556deabf6575335.nq.gz

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

[tinytag/tinytag](https://github.com/tinytag/tinytag)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
