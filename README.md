# Repolex Knowledge Graph of hamcrest/JavaHamcrest

RDF knowledge graph data for [hamcrest/JavaHamcrest](https://github.com/hamcrest/JavaHamcrest), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download hamcrest/JavaHamcrest
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 60454d3c3e2eac8f3049dfbef2900a989a8b8624
│   │   │   └── chunk-001.nq.gz
│   │   ├── 68984b85e869df6a888fffcad87e4b676a8fc0ac
│   │   │   └── chunk-001.nq.gz
│   │   └── 750dc3627d322eed26ecee54c04412ad4da9ccbf
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 60454d3c3e2eac8f3049dfbef2900a989a8b8624.nq.gz
│   └── repolex
│       └── 60454d3c3e2eac8f3049dfbef2900a989a8b8624
│           └── chunk-001.nq.gz
└── blob
    ├── 009fdefff132235a768dfb7a5aee622e5866b92b.nq.gz
    ├── 00b89ea7f1051ecf856eb2d92e036def4d9f4e7e.nq.gz
    ├── 00eef9935682d6f392b8cfb4e6ca7b52155035ca.nq.gz
    ├── 01d9e3dee2c4230a6da8a2e58f32ab962aae018a.nq.gz
    ├── 02148b8192560862ad410ffb2228903c51f2a7ca.nq.gz
    ├── 022e519cf3abdb343067a2a1b6315f87f7964c7f.nq.gz
    ├── 02b5e426a0ad2e345a254a5199c85516c4568b73.nq.gz
    ├── 02ce09e6857d7687da0a97a655fe7b5d46efdeb3.nq.gz
    ├── 036a764027b78fc6ecd4fe49ec4beb405a8b536c.nq.gz
    ├── 038467d255f1ef10ea572c1d1ecf3076e4d814f3.nq.gz
    ├── 0387207ccaa4b48185f10ad88d4907840183c082.nq.gz
    ├── 03e4c43e348461f5d16ad94f593b341e85278144.nq.gz
    ├── 03efa9dbe32a1374d225a98e02131cfc1835a493.nq.gz
    ├── 047e670ce8e2c4ab2ff175125439a4e910bc9c13.nq.gz
    ├── 049d2e8471977ff65d9dc1d12b5145c532443d62.nq.gz
    ├── 050fd1591868dff003dd6fc35d42c5cf9f2d75c3.nq.gz
    ├── 051021a9b7f57ceb452572061565730d6a4c8b6c.nq.gz
    ├── 06577685095d63755867fadaa52cabc3dc66b5d1.nq.gz
    ├── 06b361d285456f733522aaaf177cf8e946161a4b.nq.gz
    ├── 08649f7a3022fbdccef408c15584105d907a77ee.nq.gz
    ├── 087570cd495f471903e388ffa281903f7e088b14.nq.gz
    ├── 08dfce8ba270c0cf0d9ea3c6a4878aec00202761.nq.gz
    ├── 091c34755689da5e1205df5afabf149a22a986d5.nq.gz
    ├── 09523c0e5490700d1a647ecf95309b5f7f9a8199.nq.gz
    ├── 09ab0f7dc20e5f580a854fb2899a3bde2fcc6c76.nq.gz
    ├── 0a1535fe94b9c0379bd910035b0f7adbcced4406.nq.gz
    ├── 0a984087f2530a4ba5daaa77db8a8a129f6c87c5.nq.gz
    ├── 0a9d7432e805db59fa28cc2e016db0041e3a4e8f.nq.gz
    ├── 0b00139129f2ec8f81e33fe8da1b1b223295393f.nq.gz
    ├── 0c71224c38fd59eea839fa05fca81ba449f5f723.nq.gz
    ├── 0d6a3eed9985984483d8f2c6976c85f42f2a2e18.nq.gz
    ├── 0e63a1863d49cef41b999fd68018478cc1c12e25.nq.gz
    ├── 0f14598405c68477cad0a525eee3f1c74ec37386.nq.gz
    ├── 10e6731ad27a79ac9ae6b11eaee552e648e2de9f.nq.gz
    ├── 118131067c773b8cc4d7175a8174f18ccb224cf4.nq.gz
    ├── 12049a611e0832d3167766e11d5ef8998c66d397.nq.gz
    ├── 122e19b5b49fc4901a30b3b65c891aba98334427.nq.gz
    ├── 136fe9a176a530eb33b4ed895e830321d7efd18b.nq.gz
    ├── 13f067c8725cd516977fa3f39966e89c81c371d0.nq.gz
    ├── 1581d59a3f85495666cc284ce5184b2a9f1b05e5.nq.gz
    ├── 15bdf94f864f59d7b35757f9e0926b6b6e7490cd.nq.gz
    ├── 181bcbebb1ea46ca6ccb7814504f978b8242df4b.nq.gz
    ├── 18230743427b1798e5bd7aa4de25d543d50cca37.nq.gz
    ├── 18f607ec652316758932fcf663500098225aedc4.nq.gz
    ├── 19482c3d74f7bf807ced20ac196169d159d879f6.nq.gz
    ├── 1af974b46be282ef4ab4d0c80f46a9881da0b382.nq.gz
    ├── 1b86902759a2ecbc1b7afe8e7a21fcad66f27389.nq.gz
    ├── 1c1c3759bc7528db16a76a0044f5777ea50f58ea.nq.gz
    ├── 1d4d83ee03f58d6c6a5f708799c5fe09f2b47334.nq.gz
    ├── 1e5db96e2b23e4c642c94df26a22adc98bf3733e.nq.gz
    ├── 1ecba2579616dcbf651390d2b34a7f9ad741b020.nq.gz
    ├── 1fc269efa8f124670d911a5d3eccd88057d1f446.nq.gz
    ├── 218c86e31790ecd097275101f47a66afea7b7f88.nq.gz
    ├── 23876095a4bae73e8dc6893be747f56cb67d4899.nq.gz
    ├── 25e6da2cceb4898582634418be83d6c6d50794d2.nq.gz
    ├── 291ed1db5c4e269d0b901c5a364a453dcf234403.nq.gz
    ├── 29953ea141f55e3b8fc691d31b5ca8816d89fa87.nq.gz
    ├── 29b299b885181c6e7082c2f44fd90c8f459f3908.nq.gz
    ├── 2b2991bfbbb26f92cb8f6be765de9ffb5b560fe7.nq.gz
    ├── 2b3ebefe29a7593e652a4f71cc539684a3266689.nq.gz
    ├── 2bc53d4cf8f66a71201117dee5f4e3b33dfc6ada.nq.gz
    ├── 2c3521197d7c4586c843d1d3e9090525f1898cde.nq.gz
    ├── 2c867126c067a3fa15730439d4bf8114a7dbc2bc.nq.gz
    ├── 2cf7c2a8d081299d3438befdb9e65e715bf9ca65.nq.gz
    ├── 2d0479cdb52767aa4f172138cf451d5662d75584.nq.gz
    ├── 2dab9de4c3bfbcbe641b9251fe457c91d901c8cd.nq.gz
    ├── 2f09c136b3e626330b29250bc6fdd02391e5a134.nq.gz
    ├── 30064b12d7a72bdf6ed2ee557d03a256e0dcf042.nq.gz
    ├── 30b33af5881ff388d9f5ebf2746d604e831f3ef3.nq.gz
    ├── 30ed081a79e2c3e567ea1dde3de02d8fa6ebf854.nq.gz
    ├── 320a49ef681c4384efa9fad95db1abcb3a5bd885.nq.gz
    ├── 33169e343f7f156cc7f38fbb5d731757cdf7a96b.nq.gz
    ├── 34477c7e2f8c8575ca1424980b831e5701f52556.nq.gz
    ├── 35b8bad306ae0851ddc9aa33b0f067d16f3c7048.nq.gz
    ├── 37027c502d1f16aa5c87a1b6a6b272772d6643b3.nq.gz
    ├── 37d7af53657a3a1235d70b66f8e56f3a612ae075.nq.gz
    ├── 385cf99955b370694c6c27139816867fe77836a9.nq.gz
    ├── 38907b1bd921761ec4f0d18ae06c90944ce105ca.nq.gz
    ├── 38ce1b1d9b7be350d485a4cd15de2697afe1dceb.nq.gz
    ├── 38f5d915d4860fafba7fcf3d9602d3779e9417fe.nq.gz
    ├── 3928647b66fb2f3fffb367f32ee5dc7799f21306.nq.gz
    ├── 394ab82183e42cb1c161f5d5b6beb747dda8e9c7.nq.gz
    ├── 39e50666cd22307c5d90b7190590259718762cf4.nq.gz
    ├── 3b5006e7762a9187355219773bbc08392a1e67d3.nq.gz
    ├── 3b6967dced902b4f4e7319a0ad5aeca94d0789a9.nq.gz
    ├── 3becc146e22e77d883d97ae114fc5686ecdc1174.nq.gz
    ├── 3c3cb9cf85ecc1acbaee2cc80e77d007529fc641.nq.gz
    ├── 3e2ce384c55921064b9b1c1d04b749f4c4b89156.nq.gz
    ├── 3e2d9114ebfd1a59f2249c54d13aac7d3162fa85.nq.gz
    ├── 3eed346309ae8df38b78398509e7d22e8c95406c.nq.gz
    ├── 3f5e945f7afbd63d68cfbbe2b55e12bbaa740d0a.nq.gz
    ├── 3f71115a596b72fd5f1629e0cc4a8c3279999959.nq.gz
    ├── 4012027aa4eb34cbb93ee1fd9bd6950ce715acf8.nq.gz
    ├── 41044b224f8d632637288f5e67e9c4cac03c3b5f.nq.gz
    ├── 4135d9f5fadff3ac07aa4985e219de967ef5f28d.nq.gz
    ├── 415a9a2b7a28e9663365247a1452a93c8a2990a6.nq.gz
    ├── 42270cc74d6629bdbe5838adc072613623461dac.nq.gz
    ├── 42ce320a568c86b0698757bc8fd88772a257288a.nq.gz
    ├── 43b64d4645457c82f7fada9e17dd60ae38de437c.nq.gz
    ├── 43cf58b0a713b0e259550452d2d7fdf66186e4c3.nq.gz
    ├── 4422a2ab09cdd69735cff001a65a630b67bf28c2.nq.gz
    ├── 44aa76192dbaeea2eb8b3fc79414862d1f4ffd93.nq.gz
    ├── 4773dc65eb749ee8041fe25bffa03a684fb154ad.nq.gz
    ├── 4799aeaafb699988f0ab84564f09b3a0caaba0bc.nq.gz
    ├── 481b08c3b26dc075b448fa27adeaa5187c54de04.nq.gz
    ├── 48ffd923cfcd7e64090ceba8957f4f60c112e611.nq.gz
    ├── 496d3fec53c012229322f3b4f7ed5cea7e6ae9b4.nq.gz
    ├── 49f5f274e7be6ab0935cb651485fedc590be3dde.nq.gz
    ├── 4ae7235e7920bbc4316f1cd6d3d2635c70075f61.nq.gz
    ├── 4c860f0c105753fea88479dccece76c3c5f3957b.nq.gz
    ├── 4ed45392fa2642f73c71bc0811af580733353c04.nq.gz
    ├── 4f3515560cfd5d64e6809c3217aba54a6c72b711.nq.gz
    ├── 515f9e9ea1bc5d37a7c6912f5ca4ad195253938b.nq.gz
    ├── 52390a828baa123f534538b0b924a00931b43bc1.nq.gz
    ├── 5264e89d9ea542293dec16767d71e8a9daa0e2fb.nq.gz
    ├── 52a134afffcf8d2bf92ac9583d5fbae48cf17ca0.nq.gz
    ├── 538d56ad69a6ac4c0c069d448529964c8fe01801.nq.gz
    ├── 544c203b0e2823e46572e2d324f295d07e356069.nq.gz
    ├── 549f1681738ba8675e19cb4d4376ec7cd3f0c582.nq.gz
    ├── 54e9bf146aed240a33d3b4e58df390ea8b0fcd1d.nq.gz
    ├── 5563fabc4d08fac490d14aa20b1062835fe62af6.nq.gz
    ├── 556e06bd4776d48a854569b6e5d8666c5f8a711e.nq.gz
    ├── 572bf63d5b9b5c4f1bc861707943d2a9a55f9e20.nq.gz
    ├── 57fbe8c1d4164135cdaaf03b01bf8af0719b0a98.nq.gz
    ├── 582c630f680527857bf99dc8503ca8cd51fa107d.nq.gz
    ├── 586dfcef657e8f836c2687a01e165ca3f1bfc8bd.nq.gz
    ├── 5953bd0bf19817ce61f495ecabb97c228da2300e.nq.gz
    ├── 5a508c9b58d63633d230cf5c1962356f6e792722.nq.gz
    ├── 5a57af22a4513197e3a87ee4fa25d7633ac8d835.nq.gz
    ├── 5a7ed7b925111a70ce7d1a0a2cb7c74059a409c4.nq.gz
    ├── 5ab8b30632cfb17014da4d52ffd9c333d6c601de.nq.gz
    ├── 5c0513c1a42b26a40e5f0ce67ea095d31a4233eb.nq.gz
    ├── 5c7511cea084b77c015fed230af91895a9715649.nq.gz
    ├── 5c76af903418b2fc0e0a5a606aa30138d5de034a.nq.gz
    ├── 600b57603858b2e67fb8f265e119020edbeb9b53.nq.gz
    ├── 62a3637c8fd5e62d74942c9e3fd121064cd24e17.nq.gz
    ├── 62e30535bc8f0b4a4937b9584af70e1c9fc774ab.nq.gz
    ├── 64a54e64aa592a2436798076aac713438db71505.nq.gz
    ├── 6537018a64bf4aaf02917399109a83dddbbd2326.nq.gz
    ├── 6713e6879bb1add3c59c9215621742e5dc07a3bf.nq.gz
    ├── 67e776b0c721457b04c0f763da94f023eac3affe.nq.gz
    ├── 6977968ba78792882994bb819a1cbcc72fe62bb7.nq.gz
    ├── 6a5415cb696f39c8164e5015b6a966051df9859e.nq.gz
    ├── 6aac6f87ff6df1eb0fb97aaa45adeb78d221b474.nq.gz
    ├── 6aca721ecf9c86e8ee3c16fe23e18e8c88fa35ad.nq.gz
    ├── 6b220f4f4a773ba19effb300f3cefb988c82beb7.nq.gz
    ├── 6bd9da710940b6ae9f561fdb9ed51a5e3892e7df.nq.gz
    ├── 6cc97e81bb64f1ca91691bd14c46da8ee769e27b.nq.gz
    ├── 6df9a531983f07c5d9802dfaf78db22d47724817.nq.gz
    ├── 6e25fcda91e8f996f8a27b5a3d73a85e9561d223.nq.gz
    ├── 6ea9e5161615fcf6cdb0d194d913139c26fa417a.nq.gz
    ├── 70a3ff2cec353a12d37ec3bbbe14bf85938546fd.nq.gz
    ├── 715332154f6ea31eb3265ad51051076aeaaaf6a0.nq.gz
    ├── 725179b25cea948bd7773d0e41ebb9fd8da41af5.nq.gz
    ├── 73bfa3855af5f5a1d28bade637f834d4921fe435.nq.gz
    ├── 73edb83540a1fafda7834b9648285e6acdba2a58.nq.gz
    ├── 74261761edf264ba94ac66af6fb7efd41b27801c.nq.gz
    ├── 74b046b57e88a4f1d848b447b0593daa1c87e151.nq.gz
    ├── 75625958d55a683f25e974c8711903338cbebdf3.nq.gz
    ├── 7662946542831046cfb4ead62bde912411cea581.nq.gz
    ├── 76fd39f8c7fc72cdcc27a4b36f715aa89f927df0.nq.gz
    ├── 778259b28f746d9b42e6c0ac188d1c221d2d9f75.nq.gz
    ├── 77a26591cea9fe7703c7e85fb5e111e9ab363dbe.nq.gz
    ├── 77e09d5bb2dca799a81395490438ce288de93412.nq.gz
    ├── 784817a0b84e3b76d22b1893e92cdefe933fb8d0.nq.gz
    ├── 79a51298b8358891db61ee4e564a8fc23ca107b1.nq.gz
    ├── 79f4683784b9b7bd27f0ffcc59f63ea6cd869c29.nq.gz
    ├── 7a209b62463c0b61168d32c799b07f21b1887080.nq.gz
    ├── 7a22c22e2fd843ebae9e9ca09c028ce699394b4e.nq.gz
    ├── 7a2437cecae804b4cd816b6d3de581a517a29279.nq.gz
    ├── 7bd9ef89d5dcd5f79d791c442534a33e9dfc3172.nq.gz
    ├── 7c2e5cd0e78f4630e2e0f5f1294b710d7b8bf847.nq.gz
    ├── 7c3de8a887b1601f258c36f98429ce03183c2995.nq.gz
    ├── 7c5c46ce648332a42f7e99a9c656d7c6f0f023eb.nq.gz
    ├── 7cfd04a7d9483ec8a89fc980ce1dde8befaf2c9c.nq.gz
    ├── 7e23e68933415baf2d15a8a00621b653a65da708.nq.gz
    ├── 7e72a622abf2d3d038e4dd746649d549bb42f622.nq.gz
    ├── 8070f2fb632efd91531db084637599f7b73e68bd.nq.gz
    ├── 80a8444cc42b99a7e7d42681000be04f663ad3fb.nq.gz
    ├── 810e5b509578caf9f0d09bd510800968e43ef263.nq.gz
    ├── 813c1782a6fad5b52fbc6bac7bc41d11cefa8ea5.nq.gz
    ├── 816b7a3208166eb2d8c2635b07de2a0f4a1eaf64.nq.gz
    ├── 8192c8bf2aaa9570640487fc9c40b14b3743b15d.nq.gz
    ├── 81c5fc61d13826d301fe7751f0eabcb6d249511e.nq.gz
    ├── 8248c99712c35f1939813d792ce27c8a5d7e1946.nq.gz
    ├── 84098110f0385eba8c620bd61bb2b64c335bb5a0.nq.gz
    ├── 859f7b469945e6a97eb598e26a217dd71d1d84f5.nq.gz
    ├── 86805ae1f05c2e2ec3fcd38667f5fb45e93c887f.nq.gz
    ├── 87fccc0a418385714373633147f1ce005025969f.nq.gz
    ├── 88288b07a8076222c45d5a11560ab0004d7578a9.nq.gz
    ├── 892a94ef6ef919fb74503be6f6dd305325f4a3af.nq.gz
    ├── 8949e10285efacc458fced5233903c32405bbad8.nq.gz
    ├── 8a77713db17e69799a69f98e1abbdaaa0c04c3bf.nq.gz
    ├── 8b0e244b41d5160ece9fc0b690154b7c72387cf9.nq.gz
    └── 8bf65d14cc60d19e39aebd4e1b18488afe90f266.nq.gz

10 directories, 200 files
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

## Source repository

[hamcrest/JavaHamcrest](https://github.com/hamcrest/JavaHamcrest)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
