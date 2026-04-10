# Repolex Knowledge Graph of rollup/plugins

RDF knowledge graph data for [rollup/plugins](https://github.com/rollup/plugins), parsed by [repolex](https://repolex.ai).

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
lexq download rollup/plugins
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 02f6cc8d4d83aabc7dad0a1bb09490b253a169d0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0bef93f5f4826a0580d4483a9e583abbfb5002ab
│   │   │   └── chunk-001.nq.gz
│   │   ├── 22da0a5cc9725a0032c87a79ff9e035d88a63c2d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 251a455cbbc7a4df84a1cc740b480b7367a7e6e3
│   │   │   └── chunk-001.nq.gz
│   │   ├── ca65cc4cdbfbf8e7f869706e099a84ab734b1bc0
│   │   │   └── chunk-001.nq.gz
│   │   ├── cdf9113a14c116520ef9f937a1151797666bbfa2
│   │   │   └── chunk-001.nq.gz
│   │   ├── ee8c8bc30eca77bc5141302a4634ee7f6e4c048f
│   │   │   └── chunk-001.nq.gz
│   │   └── f8be8347be6e988975ce2e816ea61e441b7a3d6c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ee8c8bc30eca77bc5141302a4634ee7f6e4c048f.nq.gz
│   └── repolex
│       └── ee8c8bc30eca77bc5141302a4634ee7f6e4c048f
│           └── chunk-001.nq.gz
└── blob
    ├── 004f7d9b605541587207ccbd7203f3b504e1f8c5.nq.gz
    ├── 00544732cb2f5378d33b60f3931a8f8d55472059.nq.gz
    ├── 0066d0550013f85565e635953f0709e0007c7d30.nq.gz
    ├── 00a71a7914fb2d876d4ff4440290084a5b7bea41.nq.gz
    ├── 00b083b311bc05e3c2ff54b32d673477739b9ffb.nq.gz
    ├── 00b85058e06bc5452d169f80aaab30eb16520feb.nq.gz
    ├── 00d2b9db748146a54ba4456d46883eb9b01f8132.nq.gz
    ├── 00eec291f261da3f14df90b6a8533ffd48e93bf8.nq.gz
    ├── 00f4bc74325f1a2ba305822f525b74b40e2d71c5.nq.gz
    ├── 0102b96b7df0b0ba2d657917111c3ac587f161a2.nq.gz
    ├── 0115a9bacbadece10025eb6b191457af4ec6cfc5.nq.gz
    ├── 012c12c621cbf2d8e665c70096fda426f5ec520c.nq.gz
    ├── 0132294796c07b77fcb98cd8d6303d0b0ae3d92b.nq.gz
    ├── 0135f2c421dee9ce39394639310975fe447f0991.nq.gz
    ├── 013c94484844b696dce875c7233d85901dcea4c0.nq.gz
    ├── 0147eafa05475553541a66cccf31817098339031.nq.gz
    ├── 016cc5b8bf8426ed6b3a876b57c80aa0e7b255df.nq.gz
    ├── 01b304c14f4747f4cc369d85ba4cfb95d6b44e1c.nq.gz
    ├── 01c83e8a1d655d1aeb149e962566d00da798c59b.nq.gz
    ├── 01e4c73f3ed892a34a2d7960e3f5b42d70466f93.nq.gz
    ├── 01fc809d6d3f0afb2484fef6aa1e4b16594a9e72.nq.gz
    ├── 0245d6e0a5a765364b91ea19ade9512f0da2e85c.nq.gz
    ├── 025ab006a065bfdfae1138b7a89c303ae1985e9b.nq.gz
    ├── 02616e955c28013f0a1c1333b016a808e8e54327.nq.gz
    ├── 026a3feec592cb622445de5985c5059f608da8c0.nq.gz
    ├── 027ecef087b8f16ba33e34b04fa1c25e14b05a64.nq.gz
    ├── 028c5281ce716816194d4800d4ddad7269c421a7.nq.gz
    ├── 0294c2fe902ce58583c371a19e56ac9e9a2e5826.nq.gz
    ├── 02993729874ae6ca03538bddc45e79f77684a1d1.nq.gz
    ├── 029c53b0130d4ae4d0eb38d979b6660891aebbd6.nq.gz
    ├── 02a69157e1922627552806560db9f3ba83976074.nq.gz
    ├── 02a902fb01ea8b9a3fc28025cf195060dd37111a.nq.gz
    ├── 02cfa79c6c5c9f8a2e939ced85a9984663a05e34.nq.gz
    ├── 02fff0325833b331e5ed097eac3e0916801f608f.nq.gz
    ├── 030310948eb229546b0c61a20f045da64637f732.nq.gz
    ├── 031a354b3f110fa50eecbc819330a39b458fa217.nq.gz
    ├── 031a6268cdd19f7aa962e662370c3ae8be45bccb.nq.gz
    ├── 03227a7fca75c53d6c48f37e8ff3141777526064.nq.gz
    ├── 033c7379f5ac5e1ab850f10c98f41097e6e65f69.nq.gz
    ├── 03677c018ab1683c1a626571e7320ece847761c5.nq.gz
    ├── 037256b610cb63cf82194e05df7c75855dedb8f8.nq.gz
    ├── 0383c2a2efacabd045aeb8f3a0f1186cb12e0f04.nq.gz
    ├── 038764f9f655f6ca7b93db0db0006a9b47e31bad.nq.gz
    ├── 039ae356b764fd7097a5f561e018434670284ac5.nq.gz
    ├── 03d934380b046e622ba96435a9a7fc1176413b82.nq.gz
    ├── 03e15e77e231b3b3412275c7ed897fa1804df573.nq.gz
    ├── 042ef8f2e9bc8c4dfbef768522b85b7930694f01.nq.gz
    ├── 0430a519f8c962b5a78226d522118c06a9ac7926.nq.gz
    ├── 0438e8c927a006d3c581c3270238382e5d0afd6e.nq.gz
    ├── 043d164a775c1f3d7f9033843e8849bf4e630ddc.nq.gz
    ├── 045d7044c92e62ca39f6349ae7ff2d4ee342261e.nq.gz
    ├── 04773a728b88ecbc4a9aa147813aa3ca075b672d.nq.gz
    ├── 04b381c33ec2e357c695fbf03c5ebb0dec5d355f.nq.gz
    ├── 04bbb79d4c2f1012288d921683185a90d16fc6c6.nq.gz
    ├── 04c8860c3ac429dd7917090bd80889fb1cb0f29c.nq.gz
    ├── 04d5b812849cb68c68756c86ec5010be38e58b8d.nq.gz
    ├── 04efeeef1d39ef120e7c7d1f2df106932055885f.nq.gz
    ├── 04f3a8a8b57a10779a438cdc06b1df3d276d8030.nq.gz
    ├── 04fb98b92afeb18389fb03dafd952371aef3f1b4.nq.gz
    ├── 050048ba9d15853f1f35154dc26a04c089ffd9bc.nq.gz
    ├── 050826daae485371bc3938baaff64c36bcfad148.nq.gz
    ├── 0515c698de9dfb0710eaa358cac4fa880d0f2ab5.nq.gz
    ├── 051cca3984bd72c9bee54ec4e3a299dfcf59c756.nq.gz
    ├── 053023496f53866ad8ce22e625a275703dc134ad.nq.gz
    ├── 053509583f18f7efa5b91f202f93f35ee0b54a6a.nq.gz
    ├── 05e65967ba114f9ddc96f703af2fa10c73cf9f17.nq.gz
    ├── 060233d714317d14999ebf7436909120c708e563.nq.gz
    ├── 0602f6ea274fa9d3ef97bb0aa53970b6dd958eb6.nq.gz
    ├── 062230db54b3ddc395c4eec74f86b8d350988d33.nq.gz
    ├── 0639cde3f6287ad91c6ee19a0e6fa4b9bfa1ba6c.nq.gz
    ├── 06410052328d5c2f3671399809f9190a17e48a04.nq.gz
    ├── 0663c383c053636632ffa45924be04a4b4595636.nq.gz
    ├── 0693ea19d9bf338edf2fc38b6dda04a37689822d.nq.gz
    ├── 0697a9677321b7054e099f2f98f60a987e39f093.nq.gz
    ├── 06aab08cc8bc7c04fc84b474d4e92d842624fd97.nq.gz
    ├── 06b315a7fae203aef7a02a3a086758dbac41b4e3.nq.gz
    ├── 06b76067dc70874f2aa3fa088d2b609cb13fb2be.nq.gz
    ├── 06c18b41ab2161c80423de91fb82b27039f2e3d0.nq.gz
    ├── 06c9914c5b8c671084e631423088a19955d2a1af.nq.gz
    ├── 06d5f590c32e1b3dc62395641666271cc8461f38.nq.gz
    ├── 06f082aa643e2f07903137cc306b5279726d0ea8.nq.gz
    ├── 070b383edbfb2bb44256ea5335ba5752e7d67c95.nq.gz
    ├── 0711bc012fd15c39b688e0c29a571a598155d6f5.nq.gz
    ├── 0713326f6c93f697067f559a83fe4cb18acaf601.nq.gz
    ├── 071b4ff0b1db22d8d9f8a755b31808e99322be4a.nq.gz
    ├── 073278ee0a1a599889601a1418e591de135f0e31.nq.gz
    ├── 07341c3d6b2318a802517f1330d24629ae341599.nq.gz
    ├── 07396e09d9a26f7a43e3fcb3f6c9e36cf6bcd2d5.nq.gz
    ├── 075084c8866c014ca5b1998d4f5d710de1b4d16b.nq.gz
    ├── 0759a74915e389db5f3e4ddbdb1189b9fa561186.nq.gz
    ├── 079a5f3e0b1e3b83631bfbb539d01da014f40640.nq.gz
    ├── 079d273dfecc63fc6d174b8eff58bf337a363814.nq.gz
    ├── 07a418f6eb92b62a140047e5a0abe6c681915a65.nq.gz
    ├── 07a8f2e9a0deb48312042a8e849086efc2c0d2a0.nq.gz
    ├── 07a956b9851512ce03b4e736dbb6ba7f9dc40baf.nq.gz
    ├── 07bf25d18f2f079b8b585204c4888a634daf535a.nq.gz
    ├── 07c03e975d527d52b2d3b93ce7a72742811d38aa.nq.gz
    ├── 07e41281bf5d2a887736c663d5631a0e7662acab.nq.gz
    ├── 07e622c02ca1bac59bbbd3abb3f75dc27a8b059c.nq.gz
    ├── 07f08d262c10f14bb90171d891fe85e1d652eb7d.nq.gz
    ├── 0803628632cace62047de6c52cdb1e33dd97d5c5.nq.gz
    ├── 0815f4d71678d4f089a5485c4c1708badaa8eea0.nq.gz
    ├── 081b3039da1f7b5218af396929fa47ba92e5af8b.nq.gz
    ├── 08647fc36fa5057b848dcca3daa40543e72597d9.nq.gz
    ├── 0866af55f0d981e69c9c2bd9f0d69835e19e744a.nq.gz
    ├── 087482ddfa7fd7db3e972c7760d8a437f8438374.nq.gz
    ├── 08762918628bd657745b458c7f499066679fa06b.nq.gz
    ├── 08941b81fb32c0f3e456185a15f1d64ab3848e04.nq.gz
    ├── 08a9071bf3a10f4cca30fc1a228b8702aa131157.nq.gz
    ├── 08d6a58531054e33301bd7daf0241bd471d9e23d.nq.gz
    ├── 09023e2380f07386fd12f73cc71b119e2323cd32.nq.gz
    ├── 090906eb58a93e10f00cb12cd8c0876ede9aa34b.nq.gz
    ├── 092d75926cffdce2f24666d92e42c11c9cbc9462.nq.gz
    ├── 095dc66b6ee68dedddea5f5b45d399f377026489.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 0972a6d71395657f2ec53695742d23a0ca9e7963.nq.gz
    ├── 097c93f68730565ea30e5311012d1fb8a577aa8d.nq.gz
    ├── 09925de34ab432ad98e08ce0e304c93bbd8489ac.nq.gz
    ├── 0996c4937dd74c5f7410daf9fbacfd66baf7f724.nq.gz
    ├── 09a8422ef3e3d5712a6ef607b6032054cc4a3699.nq.gz
    ├── 09aeced27f6530ee8a0e2141d4c7d949337b3863.nq.gz
    ├── 09ce84cd8d3bd2edd76dd6bc51ef1cfd3462b141.nq.gz
    ├── 09d1d0261307d3155b1b871d30f523c5d8bc07e4.nq.gz
    ├── 09efec448383360dc56a8573663e5fe09500e9cf.nq.gz
    ├── 0a06f3e79e733d45deeec2d5124f69a77921396c.nq.gz
    ├── 0a32e68ca360cac7884bdfc964b8e4b3cc089f9a.nq.gz
    ├── 0a37054eb21e59d10a1b1ac8cbd0f38816248cc6.nq.gz
    ├── 0a4fb26a40774ee299c9e5a27880a473057fc723.nq.gz
    ├── 0a6e8769b81570d29d1ee06a6b878b639570e63a.nq.gz
    ├── 0a84c733325e138c022d1ba27b8df9fc7be8a7e5.nq.gz
    ├── 0a89b5bf6ae65aac3437a1facd1ff9c59fff05b9.nq.gz
    ├── 0adcbab3df760bcb92997f7cc93fc2e5e02ece8d.nq.gz
    ├── 0b0b7f6a7344513767eb2aad8b7eb557f94e0622.nq.gz
    ├── 0b1ca5133ba8e6729ec7908c198ea67038223824.nq.gz
    ├── 0b6c9844b03dd80aacd20e7830cd98be9573deca.nq.gz
    ├── 0b7a530267a9f21e87525137d3fc8c92aba72bd2.nq.gz
    ├── 0b86623b6ae56467e17b0312c6ce480e4d70af6f.nq.gz
    ├── 0baff428911e244f634b930b0d6ee481069cd551.nq.gz
    ├── 0bf020d0b3f08f325cae0981bb0a876a85adeb1b.nq.gz
    ├── 0c08d4db50cf120e649ca9da9bb66ef28e6cc120.nq.gz
    ├── 0c0d1749c99d7252ba9aa5bc3dd2fc2929aeb511.nq.gz
    ├── 0c19432d2d58a7657261eddaa978c6746dbeec77.nq.gz
    ├── 0c233f00b19032c9c34ade86ae29839beb90b456.nq.gz
    ├── 0c6347fb207c0249a43a02591303b7ad466f5dfc.nq.gz
    ├── 0c8fc86e86420722987a4ebddce1f4b2694a73a3.nq.gz
    ├── 0ce2e655c62f75be2757c22bbee2c517611d2751.nq.gz
    ├── 0ceefb13b66f9f6cd2ae91db988a440de731e6a2.nq.gz
    ├── 0cf01bec8dab706ab0bdf21120b2117225e2028f.nq.gz
    ├── 0d16393eda7724fe0160c2c1169a37fb42967478.nq.gz
    ├── 0d245b3629b0755d2d9a3942f73d83490a32da03.nq.gz
    ├── 0d3a40b78829059d09d79e2788765d303e161de7.nq.gz
    ├── 0d57a21e7012eb476aa0b86548c39e91f54a8a9b.nq.gz
    ├── 0d619194d0a3e09ba8d479584e866d758ce72909.nq.gz
    ├── 0da47ff7e0f098482a8945c26c3e381802327dbe.nq.gz
    ├── 0dadfb2c494b33fa6232daaa5e1ab7094cb55d6e.nq.gz
    ├── 0dc0ce037c9eac2eb89b8071b3f3f92788e37be6.nq.gz
    ├── 0dcfb5e5e5e16a0c731fb192abc5d76532869fae.nq.gz
    ├── 0dd4449b67240542b2c9c7abcc932856b6039670.nq.gz
    ├── 0ded9cf2bbfa1f9fd4b4386d62602558fb265889.nq.gz
    ├── 0dfe37a480a51a7cc3d7e115ef5d612834666e0b.nq.gz
    ├── 0e285da3630461d94b67accaec36654d424910cc.nq.gz
    ├── 0e54e95358d5aec433e3525cbf6291e12c6c08ba.nq.gz
    ├── 0e6f93f42cfb9326df081408e7071109e411c762.nq.gz
    ├── 0e83462883323bcffb277e9fb986ccfe0ff770ee.nq.gz
    ├── 0e8d018334fcca1fae265bf756177d8b3a95490b.nq.gz
    ├── 0e9886246ae442a9ca9e195c77f3ddea7a0fe413.nq.gz
    ├── 0eaba6b0550b2e75c35ecd5e16428b6683e8aff5.nq.gz
    ├── 0eaea1db575a04c8258a3eebab4e0b6399ecb97a.nq.gz
    ├── 0eb27bfff59a7816916f6f83a7fe07997d663d1c.nq.gz
    ├── 0ecf6e33d959702fa71cbbe0c44b5864cf70c9c8.nq.gz
    ├── 0ede632147dff9ecb99ac6eaba2c5f90eae9c491.nq.gz
    ├── 0f0514a0cc2c88931c3e36e4a747ea454b8d032e.nq.gz
    ├── 0f2bae2c6ae267b6d79d7af7e14c538f1fe0baac.nq.gz
    ├── 0f412eb44793910129f41b304a7429d09780b84b.nq.gz
    ├── 0f551534536570641ae0863e295839c77889dd0c.nq.gz
    ├── 0f5dc63f604044a8b868168b924f4bf8bc21e443.nq.gz
    ├── 0f8303736105af8683e185cf360a725d06fa7c02.nq.gz
    ├── 0f8ba3a3cc2b0dfb498ded307636d81087c85212.nq.gz
    ├── 0f8bbc208e00d91306ce497bc660944e4dc515ff.nq.gz
    ├── 0f93c1fb99f2f2c89de09184c40c9bf346dcd5af.nq.gz
    ├── 0fa1fcaa8b044511ec292266f1227b31c22c1cdd.nq.gz
    ├── 0fde251addf4e7e91f8521fa7c05bbbd0452c2bf.nq.gz
    ├── 0fe500a8296fdc8b30c684c18c214804cf8c720c.nq.gz
    ├── 0ff50380c672947784c1f969c863228d5897d06a.nq.gz
    ├── 103cbeb6d3e1e58d939d169a210aa7623b7a87fd.nq.gz
    ├── 1053b7f0216bb0e560f0eff254057bcfe975c5aa.nq.gz
    ├── 10830e07b718df0bf11b885b0deef6269029cb1f.nq.gz
    ├── 10abdcfdef658ab18602210078cf3484c7827b8e.nq.gz
    ├── 10d14768980df0936bbc988198953f4e25332bdf.nq.gz
    └── 1107da3b1966fe32bff52e36cc853715c388a7b2.nq.gz

15 directories, 200 files
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

[rollup/plugins](https://github.com/rollup/plugins)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
