# Repolex Knowledge Graph of zenml-io/kitaru

RDF knowledge graph data for [zenml-io/kitaru](https://github.com/zenml-io/kitaru), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/kitaru
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9b33e7576c36b57f22db26e619bbeab58df72426
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9b33e7576c36b57f22db26e619bbeab58df72426
│           └── chunk-001.nq.gz
└── blob
    ├── 00c367c65ea3b018d1723140cc67ccad6b9ce1a3.nq.gz
    ├── 022cfdbba42aded797876af66a55b6f33fe243bf.nq.gz
    ├── 025834737c47dc68814165d6d8793bf286883227.nq.gz
    ├── 0295a87b19378225930995e56340c7377a68d92e.nq.gz
    ├── 0344bae9ae155bc28cd3df694cb92274f685fea9.nq.gz
    ├── 03d93d230265b5e8a9dd70d767d99fae0a593688.nq.gz
    ├── 03f2a441723b6c66b9f2b0e20b8c27b99628105a.nq.gz
    ├── 04dc891b3fd5c0f427c6766bede53899bc067cfa.nq.gz
    ├── 04e79892eaab8d756c4b1df3fcfe398fbcdcee9e.nq.gz
    ├── 04e7f9f7aa6d92533efaaba6b0cd893de634a8ef.nq.gz
    ├── 05f09b389d8a66fd1b8810e1b10c1c489ac63cc5.nq.gz
    ├── 0645191200da5316364e819453070996790fb521.nq.gz
    ├── 06a821d5b901c69644c0c43a2b79fced321191f5.nq.gz
    ├── 070fd4a7303f226242460f3b57cd6c20470e217d.nq.gz
    ├── 0808484b9263378c6a7bfb61ff2d23e81ece8fe7.nq.gz
    ├── 0808e39c6bda06c482ab5a8e995bba61629501eb.nq.gz
    ├── 080a50f721f0ee3b5fccc93ae8552d34f049d335.nq.gz
    ├── 08244e5c7d3484467519c96a7e7de688c3556613.nq.gz
    ├── 0860ce1ec0e793f72ab9f2b4301cfb591245dc90.nq.gz
    ├── 0a1300c34a4752a3e40b536c7c1a6d695be59f68.nq.gz
    ├── 0aa3cc1926dfe2914e109d150dc4ce690982fe11.nq.gz
    ├── 0aba3fce02175374561ccb34a95de7c5beb77891.nq.gz
    ├── 0bed1ebcc051f7c7a9b06f87be78bba53edfc905.nq.gz
    ├── 0c99ac6153ae9464458247b20a889a11931cd976.nq.gz
    ├── 0d4f423450e263b7d3afd6f2af07b40ffbcfa5cf.nq.gz
    ├── 0e8458ad73071c886e08ac3b1a60f658e042ea0d.nq.gz
    ├── 0e8a0eb36f4ca2c939201c0d54b5d82a1ea34778.nq.gz
    ├── 0f6f0c6a07645a60bbb75e108b7b9748a0b92d1a.nq.gz
    ├── 0febec636de087b2fd867be6ec35537822189d5e.nq.gz
    ├── 0ffec14c3e978080fc5fee89b5abded5974597bb.nq.gz
    ├── 107a7a689a10b089828f46314ac55ff2aca92cfc.nq.gz
    ├── 10c1043ec51bceb49eaafc3cde254469ac2ed75f.nq.gz
    ├── 10fb9faba7dbd73145feeba18b5cb8c79fd3bc71.nq.gz
    ├── 117b55c9db697ebf4b8eda2909f7c063768283ad.nq.gz
    ├── 125eeb09a51452f4041a4349d95e66bf791db58b.nq.gz
    ├── 12d97df0cb48b47d6b565cf9ec75c2e30e69dbf0.nq.gz
    ├── 131be7d92a2a35f7826780d7ad279ee6a0755312.nq.gz
    ├── 13c9f840145af417f92ed3a1bb2b658d85fd58d8.nq.gz
    ├── 1401589855070a35880c9a598b6e27d0723ead4c.nq.gz
    ├── 1406cd5cdc45ddae5535b66f20491b252a6ee77f.nq.gz
    ├── 141fedd6d13a7de1d363e74f048f54ea14924816.nq.gz
    ├── 14552ff129c63a5e9c0c530a6dda0e90e8e694ff.nq.gz
    ├── 14579ce2833b9f6b9634760b16dbdbb600d15848.nq.gz
    ├── 14971039794b2872ab40f6d5943406097c0c01b8.nq.gz
    ├── 14b6362ab8f3b7c92151c670609a51e39ffed255.nq.gz
    ├── 14f54f2b5fd9c939304f54d89458ba63b60eb4af.nq.gz
    ├── 15335beff4ea527882747ee8dc53cd727c606bb8.nq.gz
    ├── 15344a464d936f6d3e0d83172475a6c636332beb.nq.gz
    ├── 156b2f66756d7e3360d29d7876ed0b43dc567286.nq.gz
    ├── 158967d341e496e0eca74751ef9244e490586096.nq.gz
    ├── 158c04c846ec74d9289a323040dc0cf9e1c32685.nq.gz
    ├── 15c5dab3cc04e0778ebbaf3c62b7cdb15f769cf8.nq.gz
    ├── 16b9ec55fdf1efd4d078ba79941229652bc1d71e.nq.gz
    ├── 16f6b3d68800cb4c92013c11c2c67b7addaaac99.nq.gz
    ├── 17981ac046ae9d272cd20b02d0e99ad65136ca90.nq.gz
    ├── 1888b71cbb288dac4a76cff445f62034fe4a3b9b.nq.gz
    ├── 18994f91c8bca491310a9e4039f77ba7120a774f.nq.gz
    ├── 18bd77dcc6ee318c2dacd676f196046b14d992f0.nq.gz
    ├── 19874eda97c07921afc20eacce9ca38b8073a380.nq.gz
    ├── 1a8ddffaaf958b94318a3cc833c41307b8851e99.nq.gz
    ├── 1aa80a57e1c962ea5938f14e972f45371d42b05b.nq.gz
    ├── 1b3ec3828bbd3191b9d186a4caf060a09f21a807.nq.gz
    ├── 1b57c06bc8b59f5b006770c4fc4dee8d0df22404.nq.gz
    ├── 1bd3ecb875bdb2ad10c29970507ea61dac5193a1.nq.gz
    ├── 1c028a6a9e036e6792e12e0b702e9f6680379845.nq.gz
    ├── 1c249ac263b9bc522ce4c34480ae320b7e76ed79.nq.gz
    ├── 1c5908edba7c145fafc839b39d7f45c5eb21f57d.nq.gz
    ├── 1cd599b5db10495c7c1ba9ecc6aee1c78c15c466.nq.gz
    ├── 1dc37f581631dafd5d428643cc410336873e0784.nq.gz
    ├── 1f147d280f75fc5fbc7ffc5eccfdf18eb972ae98.nq.gz
    ├── 1fba1e39031f65cc1a6e03a541f57fe1d1a15d85.nq.gz
    ├── 20ae9544da38d747382cc15f54e98ee76ecc78ba.nq.gz
    ├── 20cd4b7dff25e4c0ddd2e336d81f0bb23bd7f307.nq.gz
    ├── 216ce1af5760fb98237e7ef0c5fb1724e79a3fea.nq.gz
    ├── 217e05422b87455f651fd21727ce44d266ddb1f8.nq.gz
    ├── 2248060e2747e47c3e4be785b245ac5ba0dc48da.nq.gz
    ├── 241bf8e555cfc1c063107a818524003adbaca773.nq.gz
    ├── 246d0b96d43b0c39523d06abc6c1db450c29f9a3.nq.gz
    ├── 25865adc635bdb82ca0995660fbf5348f4e79f49.nq.gz
    ├── 25a55bd8d6da0e4da6edbfb5cdbbdb1ab3bddf3f.nq.gz
    ├── 25ed1e00e4d495c227ad10156eb57d288ac6bea3.nq.gz
    ├── 26a1d963e0cadeccce1a38aadca16736b699acd3.nq.gz
    ├── 270a887fd47fde351089948a8eed9d1a47e89089.nq.gz
    ├── 28a736129ba5013a1765690e1fefe8cf74beeb86.nq.gz
    ├── 298f869a86ebce1c96683a5dc249ca2fc9212172.nq.gz
    ├── 299b5f81e53d6128c40dfa5b929fcee29e3fa400.nq.gz
    ├── 2a07f58ade3bfc5f172483d959aa8c3928662d92.nq.gz
    ├── 2a9bc3501f54ff7abd28520e6b579e4acc8be88d.nq.gz
    ├── 2ac7205c196a4e1b93fe2000983dd5747f738aa2.nq.gz
    ├── 2ad028f992d71ba9b10c1529167f380824ffc416.nq.gz
    ├── 2c2605cfc849f1b406ff7793ff948e92f29627f0.nq.gz
    ├── 2c8d07d02a7a6e43fa825f2da939e7ad699fa672.nq.gz
    ├── 2cdeb7f90401ed3f534603da8df0db5f21321214.nq.gz
    ├── 2e2ee995c31e9774d31a03535d2b773dd4d4cacf.nq.gz
    ├── 2eb2ec25439fdde0ae78db2f99c213b27cdd5684.nq.gz
    ├── 2ed30bfb8029fad3a648757efcea7fccc2d4ce48.nq.gz
    ├── 2f5953a6ff83d79a7f911ce4777c969d916e1735.nq.gz
    ├── 2ffe8bfa4a35d20e7c84a4d850db5582fc379427.nq.gz
    ├── 3023281d3c739a3182f399a263a3e0c465a933d2.nq.gz
    ├── 30cff7403da04711c46979a06f6bf8eb10ee088a.nq.gz
    ├── 31bf06686f08b64f8abf836a1eb8924a15df9d60.nq.gz
    ├── 31d0607d524f9f342e4a0e836faaf22be619cb88.nq.gz
    ├── 320aa275bc85c38d4cd530fd34fd170856e18938.nq.gz
    ├── 322c54de91be594055c41359af06fe5830f7f19a.nq.gz
    ├── 329d1ed0a88aafd8e403f152c66f81f260423ba0.nq.gz
    ├── 32df28fffcdbc800d708cfd32288d426c149f20e.nq.gz
    ├── 32fc94e627cda49acaa87a823172bd677f116306.nq.gz
    ├── 3311a522e46fe7c5fa6158ee58df0ef4198767b2.nq.gz
    ├── 3355b09414538b08fe7c223d8d7dd5fcde3c3564.nq.gz
    ├── 338a7cd9c3e0b5926edeb675d2faa90ea2dd3bda.nq.gz
    ├── 33903f319eb6687266f8451305f5afd146a57559.nq.gz
    ├── 34b27bcc472844ef0b900d642280a98fd54cad00.nq.gz
    ├── 356114a245f57455430b3caff98a56655ebdfd8c.nq.gz
    ├── 3593f017ef9b004c2c514359ef57cb398176f1dd.nq.gz
    ├── 35bb7653edd000924a5620731cf6ee6b8a8f1ff8.nq.gz
    ├── 35d69e9bb2ea9bd0579898173b3eae1fb49766ab.nq.gz
    ├── 36a9175cb5cc067c3988b8552d32a6272f0af5bf.nq.gz
    ├── 371e5f485fbb7b019c4f63b9af46d255128bbd74.nq.gz
    ├── 378d46de66928bfe26a78fb3abb6238f26286b0d.nq.gz
    ├── 3794b7a02478f03cd0ca42c667cc13ba52e740de.nq.gz
    ├── 3813f88680df245fbafd1cba2299f193b49473fd.nq.gz
    ├── 38447ad750ba95de5ba011fd3224062e3306bf75.nq.gz
    ├── 38e2397cc947d8bb069679c51c6e54c0d6e9fa4b.nq.gz
    ├── 39e398fa3eb8b2c51c211280e4700a1911249bd1.nq.gz
    ├── 3a60e7617e67ab85d36e80dc3dd0ac22b633c78a.nq.gz
    ├── 3b0a85eaa484d8a2dfd7b4983f2ac1eeddfda3c7.nq.gz
    ├── 3b537d6bfa828176169037c5d1615d1847315c87.nq.gz
    ├── 3b5e4892330245f3100f8dd984e534f8ad292ffe.nq.gz
    ├── 3c038b6b75d90770c524f21a05ee4ea9b017872f.nq.gz
    ├── 3c672e453e6e0f7bc6021cfd175b3fb38506bbc6.nq.gz
    ├── 3ccc24a3b07291039d64ff12fb12314c2538aece.nq.gz
    ├── 3d3598ab2d5d510479552a95dfbe86797864dab5.nq.gz
    ├── 3d3d684867b547355e4a7f28248aa16c874211c5.nq.gz
    ├── 3d5c2dd9bfde1e813460b9a1f7a3060daa129e9d.nq.gz
    ├── 3db021311dae4ddceb5d38ee36eefb9d18d03247.nq.gz
    ├── 3edeb610336ed51adacf042a25b7e3fd870fe9a7.nq.gz
    ├── 3f91f09ad25c5df7edf0bbc338c1454e9685fc5f.nq.gz
    ├── 3fa0f67390af1577cc14d5a6d60b0aab450bff95.nq.gz
    ├── 3fd4307cf58f37b95f1d706e051f37772b70e00d.nq.gz
    ├── 41c3ff5f9505b82d42202ef1ba30b5a643d57f9d.nq.gz
    ├── 4257b481ec9fd49332391d01e9a25c0f6e7039bd.nq.gz
    ├── 42b337b09a63460e2d685afdd477dac9de98cd4c.nq.gz
    ├── 43ec1f601f4c3a9dae126fafa0587e0cb8e4add1.nq.gz
    ├── 44ad69b5349e5b888ac8ed688f696feafc8cd23e.nq.gz
    ├── 44d456e003c82395a375cffdddb9445a42b309cc.nq.gz
    ├── 45269929e5ecdd7801def559c24e6aabcd8581a0.nq.gz
    ├── 45701a89539d3c391d967f11fe03c54719e9269f.nq.gz
    ├── 46ea1288a8949323695af4d93a14d9cf21e91314.nq.gz
    ├── 47fc5a506130b411524820cad7b2e624d750592e.nq.gz
    ├── 483277ee9637a85bda68e1855635ff210cccbe8d.nq.gz
    ├── 49b75f6cc81b45f1ba1cded054b6d9dbdf16611d.nq.gz
    ├── 49daf8fa3aa9f95292ff4422ff5ff355a984045f.nq.gz
    ├── 4a411d6de7c727a718e714deb843b1db92d6000c.nq.gz
    ├── 4aa4cbfcc6c55c83ab95db8e10ad78a4987f12f6.nq.gz
    ├── 4b0ffd1909bb87406c61a62843daf4bb7f58c474.nq.gz
    ├── 4bb26872e4dacbdd2cbd8a30dde875c37c9ac3f4.nq.gz
    ├── 4c4c5352838c9bee89d2cd59813194eb9c0a951b.nq.gz
    ├── 4d94da0a26172b9b36a0b6be5ffc32bfc339def4.nq.gz
    ├── 4db2a5a70ed7ba75e849bf6b710d74363c1f0fed.nq.gz
    ├── 4e95e984c84680f963df7ef0a6a5cf9c01dcb424.nq.gz
    ├── 4eb0e6c8ed9e41c08c07a9983647f24cdb2d0481.nq.gz
    ├── 4edbc7120b6491b6c00b1ca64123c80e8a98af58.nq.gz
    ├── 4f311e27a0dc1f048e0eff51e6f159a64d221548.nq.gz
    ├── 501fea457aa631a43ea2867d2a2ff62aecda23c7.nq.gz
    ├── 50ba661e173fb08570431eb903cd10117fb805a9.nq.gz
    ├── 5162e458c61e28a146839d53ae27fed689f17bed.nq.gz
    ├── 51a986c565c1a3a76c92aeb334573236689022d2.nq.gz
    ├── 51fd7198d01cebc93536446597a71c503d5ad2dd.nq.gz
    ├── 5203f6eb01a4bf26b5a57a5a6d8b03680e7d9ea5.nq.gz
    ├── 52cb1992db66bd1c31fe1380d5479e90e4081878.nq.gz
    ├── 52f99228704af22a64c05612df7f8321ff697d51.nq.gz
    ├── 534349afcd482eb6d9245cd409a5a630dcfb80ec.nq.gz
    ├── 536f127821ac9c55e265b1864784e8f331965522.nq.gz
    ├── 5384299ffa956499d84f03b3ed665c62b6f602de.nq.gz
    ├── 53a732834a780cf6d8d75a37f6061a8fd8185279.nq.gz
    ├── 53b8a03a87bd0c56ba816dc2f1c369e27f953046.nq.gz
    ├── 53da7467ad1cc5476d5efc210331f426b485495d.nq.gz
    ├── 5430088c9190d637a5f3394158e483acb4eb6c4e.nq.gz
    ├── 546c22bdb69288dba82442a37ff134f8ff2146f3.nq.gz
    ├── 547563c25f7c4eaa895193ca001e617381488fca.nq.gz
    ├── 54a92421b49c5d514439c2a8268d7f4d5022c99b.nq.gz
    ├── 55079b0bdfbc78a8ddaea18fcab606a9dc436973.nq.gz
    ├── 5575b196fc0329b2ba25ad5f559d948fb63f44fe.nq.gz
    ├── 56db818bd6b8d6988f1ff19682a5b683008df75b.nq.gz
    ├── 57ebcf88570be82d49976cec52c76cf4e07f2f31.nq.gz
    ├── 57ffee3a95be40dad945d2dc8a758524de22142f.nq.gz
    ├── 583651e6a04eb4e0f34fd37c0b80c99bbf113094.nq.gz
    ├── 5875a9a88e4941f7b579208276fd4ed2b2cc03e9.nq.gz
    ├── 589a3b61e93c9acccf242a720add79b19846e61c.nq.gz
    ├── 59436727f10aa2640c9ca7863d570652a64e4e54.nq.gz
    ├── 597c6705022258c80448125343276962d3f96598.nq.gz
    ├── 5a31417cf1d446cf2d68a18cd8cf8294cf5ab3e7.nq.gz
    ├── 5a7092012863238d24af1a06312299ca0d1f46ca.nq.gz
    ├── 5b9d27182bd9ab8bda43e1eb40b01962ee1618bb.nq.gz
    ├── 5bdc0ff4825a6f2f5d3d79a1a71ba85cbbc09036.nq.gz
    ├── 5c2ea55fdba16812d85efa29cb6eb3c9911673d0.nq.gz
    ├── 5c4782ffb4eddfde059b9d24244bad46e982f0c1.nq.gz
    └── 5c866559b60ea2100595eaac92f607de9f5478ef.nq.gz

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

[zenml-io/kitaru](https://github.com/zenml-io/kitaru)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
