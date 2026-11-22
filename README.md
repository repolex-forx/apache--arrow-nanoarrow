# Repolex Knowledge Graph of apache/arrow-nanoarrow

RDF knowledge graph data for [apache/arrow-nanoarrow](https://github.com/apache/arrow-nanoarrow), parsed by [repolex](https://repolex.ai).

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
rlex download apache/arrow-nanoarrow
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 209b293d190912a8a6b1e8f682dbc6d6a534a2a2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 209b293d190912a8a6b1e8f682dbc6d6a534a2a2.nq.gz
│   └── repolex
│       └── 209b293d190912a8a6b1e8f682dbc6d6a534a2a2
│           └── chunk-001.nq.gz
└── blob
    ├── 009d6a7557142c0675a9495473508aabc3103a5f.nq.gz
    ├── 00fd3097c6512afc90ea3709d16952d2d74b1007.nq.gz
    ├── 0136422e4da95059102df2a5405c05439c902b17.nq.gz
    ├── 014f5bc8c9442276393849104398ea35e297c524.nq.gz
    ├── 018421ea3d042964916ef29cb99c19c5fca89118.nq.gz
    ├── 0227a97a45266e400a7cb6ca500d4094def02efe.nq.gz
    ├── 02437fb7de8d8cfb4c5332cda13a66671421302e.nq.gz
    ├── 031a0e0c0a2373e190258eecf9ec7a81d59143bc.nq.gz
    ├── 032f7e87f8786d5b60280f0333ec9ca3a7731a1b.nq.gz
    ├── 03c55bc6b2664fada4c43089a0b1046840855af7.nq.gz
    ├── 041a4b407e344864355ab1b4545c07711136ca42.nq.gz
    ├── 0427b34cfb39ca36c2243fe2bbdd6092a5b99c27.nq.gz
    ├── 0470d08a6c28e2d3f5505c75c9ef94568c441a63.nq.gz
    ├── 059099c449f130a033b3c79945eeceec3756e7dd.nq.gz
    ├── 0592f313238095ebb6aad9fe6811d972c6740fca.nq.gz
    ├── 0626f4dd7ad3770304914478b5bec59d73dfb630.nq.gz
    ├── 062d94f5d35dc95b9226933a426ac04aa0a7dd77.nq.gz
    ├── 068e3958d7255e70dc5ce2220c6a7e8ee6ac9f50.nq.gz
    ├── 06b265ffc37bfa2b145ee85f004142013b564c36.nq.gz
    ├── 0735af58427140abcdfefd150bbf302bb7ef8829.nq.gz
    ├── 094673629c382d8a39ceb939e36b99de6f5cd363.nq.gz
    ├── 0a3b8ee192fe0006b02071fcd1fd2f045f0a0e6e.nq.gz
    ├── 0d70bf1ed4136e9b223ff3a982ca495288f1f2e0.nq.gz
    ├── 0d7e3e8794b9aef87c88d9cb282351dc1661b3e5.nq.gz
    ├── 0e30fe0d46dd1df1032e45ae2138f78627698471.nq.gz
    ├── 0e38b35362f6a893e46bdd0598e1898b6899929f.nq.gz
    ├── 0f8b0218e9f72ebff816254215cf0a26f7c02c2a.nq.gz
    ├── 105bb7f4ba1e4c1a9b614d724e1ef8073f7f09e1.nq.gz
    ├── 106c080a0bd6995c21b3690e64fd3fc55ecd00d7.nq.gz
    ├── 110029b8c76c8c9f7e9175a23dbf01178fe01dd7.nq.gz
    ├── 1164b2f1484ec37f8c96fe6854040bf209cf4774.nq.gz
    ├── 116bac10468f7a202058d494739960e6741d5684.nq.gz
    ├── 1196540f15cafdf77931c0c5f273d280dc68eddc.nq.gz
    ├── 122ba8e245c027e8bfc4b8ea504895ac6f0ed48f.nq.gz
    ├── 12816155726669370fea492ec418775c18097c4d.nq.gz
    ├── 1392248b87d28b071dc35a6a971ce1f8a46b14d7.nq.gz
    ├── 13a83393a9124bf6ec36540556b4808abd47e206.nq.gz
    ├── 14ad124c55ca165ff620afc36e0a89d5d7be2aec.nq.gz
    ├── 14cecfd570115461b90b98ea30dbbb9d94018735.nq.gz
    ├── 15209371d8788e332cbaaefa8e132bc1940e1f3c.nq.gz
    ├── 15f029210ab693cd852ca8aa5afd411211665be9.nq.gz
    ├── 163644d9e1c51bba0bb7044d728a105f46d6eb09.nq.gz
    ├── 16ab032efa8cdd89902a45563615a0580fdf34ec.nq.gz
    ├── 16daa8969a901c5557ad8b81aacc96f94d441384.nq.gz
    ├── 16f9b2c9bd7b4b44a6eaa008a2d481494c24286e.nq.gz
    ├── 1737ca01e81455831f3489122f7650f794055f32.nq.gz
    ├── 17c879122f0d9c6972a15b8bd058e4d50e523cf1.nq.gz
    ├── 18614cf9df2f3ee7f2691769abdd5f6823ebd23c.nq.gz
    ├── 1976e19dc13d985f5964a83d0d25d555734c398a.nq.gz
    ├── 19d8da0fa22db7965081a0e2727aa21c7643cf99.nq.gz
    ├── 19df21ed31e31e26d8f804e642793cfe42d42513.nq.gz
    ├── 19e5bedf068ead27c520ab65127566338df7b49d.nq.gz
    ├── 1a6afc1c4ade717a6d4580adcd0df4605c305a33.nq.gz
    ├── 1a8ad98cc88f84f612aec6ed7b3d0c78d8b9a4c8.nq.gz
    ├── 1ada24fdb0cf120edc039036dbe4829bd45ebacf.nq.gz
    ├── 1af151b1c7f08da732901c2527569b663b107fb1.nq.gz
    ├── 1b6d1493688ec84039f1bd147e8c371d27329851.nq.gz
    ├── 1bbcbe5e879047c5153dc0738d02c23a22721b84.nq.gz
    ├── 1dd62c046fa87716869a65fdbd96440e06ec6fa9.nq.gz
    ├── 1eae9dc8b5aa0e1c29d4dd7b4d7933054150467c.nq.gz
    ├── 1eb71f5971da901eb3a55ab6279c2f2f4bbefba8.nq.gz
    ├── 1f100865b5894a1e23b2411be4970f380ed1b522.nq.gz
    ├── 1f4d7ecde65cb1c179395b5eaf14879abf35bc73.nq.gz
    ├── 1f7bc18dda2c7563bc5f2feec1c8df9404fd203f.nq.gz
    ├── 1fb6a24ea18ebc00405a0b2908915b4334c890a7.nq.gz
    ├── 202715e80e34116b44033d5c8f2d435c19d006c1.nq.gz
    ├── 209f698313e35342147fa671d3913283f9855c1a.nq.gz
    ├── 20d1aa9db75c63bfa9a951ee6d892161626292e9.nq.gz
    ├── 20fd207bad0983d900be886df482bd7fece1f871.nq.gz
    ├── 218fb783aa6f32257f6ac0a53727c604130cc05d.nq.gz
    ├── 230596537d21a63168b1ea394039bfc580c420d8.nq.gz
    ├── 23a9f2ed502a8f8ec38fa2bdcd4e49c026f00bdd.nq.gz
    ├── 23b854bf020ada9f6e0b1597a5bd1c4e61456bf2.nq.gz
    ├── 24b080038b493c37c816f048714849e87cb3ce76.nq.gz
    ├── 24d5634e615be7f06f4b917c4557e64a4070f833.nq.gz
    ├── 25870b416f1b9360633679af580978132fdd6aef.nq.gz
    ├── 2587f60655af63d9bdb30d32571528d379897463.nq.gz
    ├── 2596a284c8785c4cc46378dbaebeb062a28087ba.nq.gz
    ├── 25ac73a47c8463cebdee6b74db3fb151ea5b6b49.nq.gz
    ├── 25fc2eb04641866ebeec5b4aeb557117237b68cc.nq.gz
    ├── 26c529e0e94f779a705a5062ed015dff67d75749.nq.gz
    ├── 271fbd16311f41466d05ef2b4714792dbf8d49fc.nq.gz
    ├── 27c359c675cf2a509a3de296bc5ac9cd48507e2a.nq.gz
    ├── 282b21e14c107ce8c9857d47bc4a6efd4d3c6fa2.nq.gz
    ├── 28d4cbf539815685e133b3b377ecb602a6814c3a.nq.gz
    ├── 29e8f1509e38fb6f096ef1ac5ca9e04adb73ca6c.nq.gz
    ├── 2a17b2ada693d1108942b8ae21d31275d9a9659a.nq.gz
    ├── 2aabaf097d5397effb55b1f448f15514775a0d07.nq.gz
    ├── 2bb85fc7f95c9e89e97790f0e918ce9f88b7b803.nq.gz
    ├── 2c0fd8e82b4cfde80ae59d2630027f79f2ebf2ae.nq.gz
    ├── 2d010c729e6adfa640768dd02ca3db2d1111dac3.nq.gz
    ├── 2dcc49eb8758a807586ddcd531ca5bb6d8125671.nq.gz
    ├── 2e11e22c040719c50f6b00261963662fa35a96a1.nq.gz
    ├── 2e3778d45cf5e82698bce04c6ac51bc0225985ce.nq.gz
    ├── 2e3dc6d43f90a22fa631300ad7a75a9c7b5ca7bc.nq.gz
    ├── 2e4bcca9e4422d1a429794272cf444000c60ffe4.nq.gz
    ├── 2e84d297963233bce5dfc06ef43e13ce9af567ba.nq.gz
    ├── 2ef383fc11deaf940824bc9f6e8b0a2da900bfcc.nq.gz
    ├── 2f0f824cf82c4370f910190fb6aab9a41e9ddd20.nq.gz
    ├── 301bb4d1e3580319e13aa7711c88385149b6e08b.nq.gz
    ├── 3041e32e8c99177757a3e16da3acb2f118d92cde.nq.gz
    ├── 30bb9a531f0c6a2b5804898442f50b4a5dd7078d.nq.gz
    ├── 3146ecbfdaf5b09d17f7d5001b7bab2b2475e55e.nq.gz
    ├── 31ed17cf8cbed9f4527076b292fd011f0fe2e0d4.nq.gz
    ├── 32b80daa3dfd741e75300b7768cb2f5f9187d525.nq.gz
    ├── 330530c36405aea0b4dca443f10430a8a470560c.nq.gz
    ├── 3581eb0f2ce0bdda3d6118574e073c033a6826eb.nq.gz
    ├── 35a9378715753f8d529b6bc7fdcc8012cbcc82b3.nq.gz
    ├── 36095770a00bc5d4ac67baaeaa158327d3dd5302.nq.gz
    ├── 3610116fbda000f0a56551747c46f033b681bd00.nq.gz
    ├── 36482dc49c4be23bc78bbc31dce2948a2f5f8121.nq.gz
    ├── 36859c05a3db0cfe8baa591052fde94d4cf4f64f.nq.gz
    ├── 378522fe05b3156dfdb1ddc93c1c132a35db673c.nq.gz
    ├── 380579abb313fe230a3b1b2103d1234e80dc7e4a.nq.gz
    ├── 388afede7d3d7da02627a032e0dc51f2850689b9.nq.gz
    ├── 39273b64ace944efb2b2dcefc7ddec4a60322d7e.nq.gz
    ├── 392c3241f93944551b2be03f319ab8928792493f.nq.gz
    ├── 396a25fc2d69b0c15b60c3b2b28e066662403c4a.nq.gz
    ├── 39e66a8d0f865cacfb4826a2b9ab75f0369e3083.nq.gz
    ├── 3a74ed6040dbc5b4c806a12c50d9519f50e72b75.nq.gz
    ├── 3b6704639e7a8dba51d371eb36322b92fad2bbea.nq.gz
    ├── 3c0faf6d08112688c0d0a2e5d38b6f24de59428f.nq.gz
    ├── 3ca7140d407b12b89a9215ab3e49de09e99fec04.nq.gz
    ├── 3dc727c4734d2f046056ba60cc5726b4164e1740.nq.gz
    ├── 3e0826da7fe5b996cbbb28d94a283ca47e245b4d.nq.gz
    ├── 3e31a23e22253a2c3bbd0713244d4a2ca36c9a68.nq.gz
    ├── 3e77733f4d1ee342d7d9aae4366fab75d5014a0b.nq.gz
    ├── 3ecb2fbfa18e548c1d7294bbf67497011e4a5f87.nq.gz
    ├── 3f704d320a8bdb850c2e218b5517107d0ff819a0.nq.gz
    ├── 3fe5595b05f4b151852358daab45d92eb8a5f9c4.nq.gz
    ├── 40e622ccba630bf4465786eaf32a18ab6528dd1d.nq.gz
    ├── 415d56a0854dfcd3867eb2a78e57111ed3706f36.nq.gz
    ├── 419b6107122450983ee306a69f5282aa82c68c31.nq.gz
    ├── 41db69b8f3f219e5f811f1132abe2aa2f8e109e7.nq.gz
    ├── 41f2e1bd9f5ad4c34358cdb878d034b962c8107c.nq.gz
    ├── 44efd8d476d05071188ef67dcdd16cb952873305.nq.gz
    ├── 451a66880c089fc5c05946e805ae8d64c0fea031.nq.gz
    ├── 455522ad9a02a9d92558ae4b61a9cab44d135473.nq.gz
    ├── 4628a20d95e8ab03024834c5c236651bcdba4b50.nq.gz
    ├── 46b47802666a6c64a8ecf0328ccf77712c7cde24.nq.gz
    ├── 47af7d334299ffe10e0e3a1bc4270152ba461a16.nq.gz
    ├── 47ec93927468e7251b7a4dc2045908c38a828d7f.nq.gz
    ├── 47f8fc7d8810dac12e85dd421852cf7374e3d8d0.nq.gz
    ├── 48a0e082a0cf2bbd281b2487187c6d597f4904e2.nq.gz
    ├── 491869f311cd47ab6af6d3520307b15b08d473d2.nq.gz
    ├── 4a2478fee91e011718eb97e56f9cbed14b9016df.nq.gz
    ├── 4baae94e0d242cafe91b293b95c68d89446a797a.nq.gz
    ├── 4bc9875bc4becdf2e4392f2db9b865040e6dd262.nq.gz
    ├── 4d1c443b6272c843233c8e84402602ca395b6fb6.nq.gz
    ├── 4d2c20794c98e48999776b032148b030e82f8975.nq.gz
    ├── 4e96a1e4093c4dc1705f02324a58b32dc5357cf8.nq.gz
    ├── 4eda3d33feaac9dda736de6ef223998b4257f0e5.nq.gz
    ├── 4f427e4eb8985bb06d7013cb501da820ebef60df.nq.gz
    ├── 4faa3f540d21a6311d17baf767cc938ca21d7a19.nq.gz
    ├── 5093a88f8ef776d699510d84f72d71f3a1749f29.nq.gz
    ├── 5114649f61157fa44dda39c3a02559c9b79b63c5.nq.gz
    ├── 51f6e346ce692866da85f4f1ab6bc16f9e6eab88.nq.gz
    ├── 520636b84ca88bba47b99783edd8e6ac62d0f432.nq.gz
    ├── 52e8d4421eed8f2c9d177d318102e9bb58acd99f.nq.gz
    ├── 533dd703d7abfe5ae0b1a625e6a4f5796dceadbc.nq.gz
    ├── 53937b8028fa6b1a28d29e7113820d089fbba5a6.nq.gz
    ├── 53a11f206c7bb7eb564361ffd384b8c43ca31ac2.nq.gz
    ├── 547dbb7a0c1a203ba600406e8db633150677a444.nq.gz
    ├── 5570bf971b257eee411ee14d1b85787d35f25759.nq.gz
    ├── 56cc5428578925f7199b97c3a3f40aa9c49a3b82.nq.gz
    ├── 56d9d05a7282a4084fcdb2b21859df921815e520.nq.gz
    ├── 5737996772e35e4e9864c50f14b36d4d597338bc.nq.gz
    ├── 5769855e80f394393b7ce9bf006b50c2e84cedb2.nq.gz
    ├── 581184a37a2c3de03e0dbe1a2a0c9d303d7278d8.nq.gz
    ├── 5881481b0789acbc8b0153ddc2a6c2bfc889ce58.nq.gz
    ├── 597f42ef6a4d67ba61b5a61122fcb44dbbd2869a.nq.gz
    ├── 5a7471d0c38aa46bd78a0de149ea289be05d6577.nq.gz
    ├── 5b5116a12366520896fe771584ad9936de40e3fb.nq.gz
    ├── 5cb042ea748273c3eef634fa767cb8b60ebf4db9.nq.gz
    ├── 5e1788271956f0a0dbae0f026fcbf4583e4fc007.nq.gz
    ├── 5ea0c609eb68c27118632201a0f4d2b5d2c6250e.nq.gz
    ├── 5f369789513e25a8f2e27df429a22fe5f01c0ff9.nq.gz
    ├── 603645d2f282e8d92dc1a906aa5516959ba6f90a.nq.gz
    ├── 604736d9852e8e6772541ac44abef5bf88735768.nq.gz
    ├── 6140071ac43b0cd0bd94956f89ba47549a507d61.nq.gz
    ├── 614bf9928aa58c8b4c1f7a94e495fa245c5bdf47.nq.gz
    ├── 6157bf551bc6e6d447c31f2e99cfa5fc04ed65da.nq.gz
    ├── 620dcba4a8a42089867e338f77ce190e8b207c73.nq.gz
    ├── 623576937c842c7c841e75bfce39cf02d00ccea1.nq.gz
    ├── 62a9d77a96145ab3f244fd81dbfd1a6e7ad8c60c.nq.gz
    ├── 631396b11e1486fae9521ecec5cd372f339b04ca.nq.gz
    ├── 63943b46d2c9144c3178152de9bd76383e642820.nq.gz
    ├── 63c2af7a0340412c2fd205e56a0fd3c9c32700c0.nq.gz
    ├── 63cd967b5f481ef4b38fd2df513795c10c327ddb.nq.gz
    ├── 66586d721b0f35ff5ed222905b7a48410c8046b3.nq.gz
    ├── 681f6b236546159ebe1cb9e01cb708e5c098a3f7.nq.gz
    ├── 68a1bd65f2813c265cbc63ecf962bb3cb9a2ec11.nq.gz
    ├── 69160e7216ca8ddaf32b0cc0ff15bfcf44e7d938.nq.gz
    ├── 695a986c294a76228862efcd959f5dfcc59f80aa.nq.gz
    ├── 69605d2d63c44271012d687baa7af8fe5ea076ae.nq.gz
    ├── 69becb169015ebacf17e8b52d617338c9d9b3d15.nq.gz
    └── 6a0fdfbab14431d97c731984ea74fd20cc807439.nq.gz

8 directories, 200 files
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

[apache/arrow-nanoarrow](https://github.com/apache/arrow-nanoarrow)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
