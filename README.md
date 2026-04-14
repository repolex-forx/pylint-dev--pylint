# Repolex Knowledge Graph of pylint-dev/pylint

RDF knowledge graph data for [pylint-dev/pylint](https://github.com/pylint-dev/pylint), parsed by [repolex](https://repolex.ai).

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
lexq download pylint-dev/pylint
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 053c2c3a25f97f043e10cdd41d2609e495a68f57
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0939ac584f16288138ee43002758d912de531be6
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0a805f88671eda9820be5b75590db5f4199fc6ba
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0eb8cb5a4c4704451eb217eb004b9a9c348244ee
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0eb92d25fd38ba5bad2f8d2ea7df63ad23e18ae3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1052bc8b2fed14105fa291dd3dff104aa2db4694
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1a5ffc1f447b77071ffe18a9c6836c09147ee2ed
│   │   │   └── chunk-001.nq.gz
│   │   ├── 31f348f162c8960867f340e5ce56358897ef9e57
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3259bc81ec3c92a1f00040f3e036f85d0ffc5da2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 425ad66da9467bac9074de3f2294f7851cb3320b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4a7ad5ea9f1c5a98ccf736578a00554be0da6dc7
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4cab7ca4eae88b75960fcf2479b8ddd377dd4ce2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6350dfa900b11de442bc562564884037ca8bc4f6
│   │   │   └── chunk-001.nq.gz
│   │   ├── 769ffd20bbf321a6cf23f5e7221a0b8221f51482
│   │   │   └── chunk-001.nq.gz
│   │   ├── 76bce72bc57cc8089e439cc9d22fed5806341ed4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7ac5a4d4f77576df3a00e63f86ca86e0e1780b47
│   │   │   └── chunk-001.nq.gz
│   │   ├── 811538121f07173bab6a8a1e0366ed56b020954c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 84b6552b86e210097ac29de7ef64b152efb4a454
│   │   │   └── chunk-001.nq.gz
│   │   ├── 918d2168e15662df90cfb993df100e566f69d418
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9223172074c4ca2bb5bff3b2c5a40190cc527fcf
│   │   │   └── chunk-001.nq.gz
│   │   ├── 94eed8181960ec1012eb4f4c314db3e226749f23
│   │   │   └── chunk-001.nq.gz
│   │   ├── 98942ba4126a6fe1657bad77027bcc11016d16da
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9a3035053154ba0c3ca3b300d6bc9fa72b95d552
│   │   │   └── chunk-001.nq.gz
│   │   ├── a5a1bc3a9602d08f15ac90ad12f5b25bde375613
│   │   │   └── chunk-001.nq.gz
│   │   ├── a98215b8c6a6203dd56366bcfe1cd946fb41282a
│   │   │   └── chunk-001.nq.gz
│   │   ├── aaab3ccb541532d2bcdf0410ab93ff4fafc266f5
│   │   │   └── chunk-001.nq.gz
│   │   ├── ae730ac7721d2cb206c153f680605b83d66fbc84
│   │   │   └── chunk-001.nq.gz
│   │   ├── b738d233e2df7651abae847e2331e2621482e5fb
│   │   │   └── chunk-001.nq.gz
│   │   ├── c28580be76fe1ec55a6cac41833c0bd68070d2f7
│   │   │   └── chunk-001.nq.gz
│   │   ├── c2b01c3d0b6410d4c93eb1f32fb28f2116b1e68f
│   │   │   └── chunk-001.nq.gz
│   │   ├── da1956664d6be3d008a90ad3f72bdd9d8a7ecfaa
│   │   │   └── chunk-001.nq.gz
│   │   ├── e16f942166511d6fb4427e503a734152fae0c4fe
│   │   │   └── chunk-001.nq.gz
│   │   ├── e808f895d9ac2bdc0de8a544784dba88c2dbf47d
│   │   │   └── chunk-001.nq.gz
│   │   ├── efee9618894795cc8847727108522aa79431ee25
│   │   │   └── chunk-001.nq.gz
│   │   ├── f2cded41f7f3d4b45236cbe107b366b6caf84bde
│   │   │   └── chunk-001.nq.gz
│   │   └── f798a4a3508bcbb8ad0773ae14bf32d28dcfdcbe
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e808f895d9ac2bdc0de8a544784dba88c2dbf47d.nq.gz
│   └── repolex
│       └── e808f895d9ac2bdc0de8a544784dba88c2dbf47d
│           └── chunk-001.nq.gz
└── blob
    ├── 000006ac82cd06ca0022be1a6567830dfc250522.nq.gz
    ├── 0007db21d5dc2a9651d9d785b457d802a27b1cc3.nq.gz
    ├── 002931de3d97332ec6e010e0c41e9370fcf43e4a.nq.gz
    ├── 002c7eb031fbbede1ba42e548f607c95d2a6201c.nq.gz
    ├── 002db0d762003a7cdc7505cdd83ff420a1f961c5.nq.gz
    ├── 002eca2cdb8bc8dc142d488ac48e1cab54a60ca2.nq.gz
    ├── 0044e1fcd2f26143fca28a6f138c4d5aaeb573a5.nq.gz
    ├── 0053b8dfe0c86442b31d5197dd97f6dc1bdfacc2.nq.gz
    ├── 006065705e96eb1b5bb3ec0438639b6f6cd708c0.nq.gz
    ├── 006a29bf91f0c7d7dc6b98dbb064aad1a023e023.nq.gz
    ├── 007371a5dba1934f93dbd36c55066f2e80054e5f.nq.gz
    ├── 007f59a27c0f68d476ba3ae3da4e4523725caf00.nq.gz
    ├── 008c9c5d0a85ed6db4746d150c4a0519ee13ae4f.nq.gz
    ├── 009ec21d35184de9f843eb66ebbc6bb23fb15bd4.nq.gz
    ├── 00b1ee70fcacd7b851f3c3f46fd3e5be076ca64f.nq.gz
    ├── 00b7e40ed7245e4da5aade890f6669be906d2e41.nq.gz
    ├── 00be9ad4607f3bd20df7b13661884369923c3333.nq.gz
    ├── 00bf5799fcbfbe73ce6f4e40d7a96828423136e8.nq.gz
    ├── 00c9130402d1a735299b12c656853379dcd78862.nq.gz
    ├── 00cb00780b6410a1c24df816f8b8b5a3147c615e.nq.gz
    ├── 00d539500c3610dfc5909bb6376a0b136d2ce77c.nq.gz
    ├── 00db8cdfe549f866864812123042499c7a52c236.nq.gz
    ├── 00e410b4691c3c37939603110e1653a3533b3c97.nq.gz
    ├── 00e43cbdc81770482c074b9adea7a72b2794c1cf.nq.gz
    ├── 00ee4993077cbc10480de310846216cdccf4f385.nq.gz
    ├── 00ee8aff796f68d784a0c4157660f8cbbb66e5f7.nq.gz
    ├── 00ef2204619c0eca16b091575e7dc3f63ec57cb0.nq.gz
    ├── 00f4caa8cff4e2131ba031e3f44bf8eace528c8d.nq.gz
    ├── 00f9963b72e90b0247ced72dad8385ce66e72bc6.nq.gz
    ├── 0108fb107c6e7b660cacc7d15b5a4b08752fbecb.nq.gz
    ├── 01120115fe1f2de645d5e7ffcfd15f0b7af0b3b0.nq.gz
    ├── 0116c9bb7a4133a8f2f95c512f9c584c83ceb227.nq.gz
    ├── 01175ec98e782fad1dd5de8a7e233d655e8151d7.nq.gz
    ├── 0119c9bcffcae9179f78f45dcb52748c78732a55.nq.gz
    ├── 011cff572ba874ca21037b25bfcb76a9af5c2de5.nq.gz
    ├── 011fb3235af54d7b9cdb5fd78dc8425bfcf4807d.nq.gz
    ├── 0124db53e611a131f1961cfa0f1f7ba5163e9e62.nq.gz
    ├── 012657516a8117cef13a04e16c17a8e692a23477.nq.gz
    ├── 012825db07e116764714ab8bd3f0b576695a4be3.nq.gz
    ├── 012ba136bac310f6478eae4860ec72dcecf7fc98.nq.gz
    ├── 012bc42f4635fca57b4f755fecb8e1bb892a1d3b.nq.gz
    ├── 0132f8b64f2dd102e4c95c2468a9f666f50bef56.nq.gz
    ├── 01457802c427e5992926eb0b37ff0dbeffcb6025.nq.gz
    ├── 014a76cb58001721d7aa167ab378b480bdc29494.nq.gz
    ├── 015401a0578697971d769959d3a36136710e365b.nq.gz
    ├── 0182ebd1a0968be20ef4689d1a7e063e296b9257.nq.gz
    ├── 0184f5db5cb73b3bd46080c37cfd5149914daa0f.nq.gz
    ├── 0193339de6df312ecf45a33f9e274712535a74cf.nq.gz
    ├── 0198ae7d1edee3a53bc3b0646eacdcdd499e8001.nq.gz
    ├── 01a7166b1ddc8ca4902a62c0c7795bfe6c1704bf.nq.gz
    ├── 01ac3e5351fa70b7004251c1ef9696987ef73a62.nq.gz
    ├── 01b411303c015ba81e280400616bfb936e1d37d1.nq.gz
    ├── 01b978e4bc647cb4ce8a48c2cd2a7c359b338865.nq.gz
    ├── 01c2bed368d33a7d9e8605d41b9b671fb33e4d86.nq.gz
    ├── 01c57af07839b27b6855bb0a1f1194cd4d3b5ff8.nq.gz
    ├── 01f17a7530e28b731a1bab511b576816f68b945d.nq.gz
    ├── 01f9a7851aad607b3fccc33d20229e9efac7b287.nq.gz
    ├── 02137f2879df7d5e7c007d10983d9e28a6116cc3.nq.gz
    ├── 021f3b4bfdda2e8e22eb46639eb869961c31351e.nq.gz
    ├── 0222308af63cfa420fffdf66e64e94d2eaeffffc.nq.gz
    ├── 0226f48239acf441a1acf2ce222bcbecfdf55296.nq.gz
    ├── 024b35a38ad25eddc0a40aafff083b06ce99e5c1.nq.gz
    ├── 024ec1695ca2364370b4167ddda2a6076c3626f2.nq.gz
    ├── 025a55a16d2e99517b0444216e36082c78fa88d5.nq.gz
    ├── 025cd2a0f52961d109d7c4793959fe9605e206ae.nq.gz
    ├── 025f28562269c225d16e13211df110f9daff9593.nq.gz
    ├── 0260798b468f4c9377a21d35023086a63f19e07a.nq.gz
    ├── 0269bafa1c0c705b565a2037462c76922ae60e94.nq.gz
    ├── 028191ddf850497642bfcb8ff8bca917bc283f04.nq.gz
    ├── 0289a13fb12e6b039c8ece60ae5311f60ed26f97.nq.gz
    ├── 028ab1809b234e725cdbb16b9cb00d9b345d4d82.nq.gz
    ├── 028dc13f384a22bd43b601957db5e3b4353d2f20.nq.gz
    ├── 0295c956d015289dd0e48abb78e8b5afddff5d6e.nq.gz
    ├── 02a76e93a1cee430f43687c4d4e5dbcb7ad45038.nq.gz
    ├── 02af32f45fa7a78e9d04ccebb1a364eca9bf02c7.nq.gz
    ├── 02b1d7653a0cf037c239874c09f5b0478b0ca879.nq.gz
    ├── 02b93948fb53e767da73069a8e3ddfd39336cb6e.nq.gz
    ├── 02cbcf081cdc703e942265aa6ef8355b9c687e58.nq.gz
    ├── 02d068916e72b8f231fcd88fb0a033ba0a679c1a.nq.gz
    ├── 02df36c4424ba4795f9b8b50d431c14140a2f0ab.nq.gz
    ├── 02f064b89ea4bf30d70c23b217622b041dbb4a1e.nq.gz
    ├── 030b519e220f9d76a15948eeab3157e6a4da9864.nq.gz
    ├── 031faa0f139732404b767801372ed938e4394383.nq.gz
    ├── 033bad0b0ffea087fee8d601ffbdcc56bef20e31.nq.gz
    ├── 033bd8974e22fb88dea3db740e673e2543731024.nq.gz
    ├── 0344e981cbc0647263c973658a9f185d1d4715bd.nq.gz
    ├── 03457972414a49e97af6daa5a6f1cd3b7b158a89.nq.gz
    ├── 035e951ab26e8533d6672071b6edb493f3cd7421.nq.gz
    ├── 03690cf36b6410f8df833a35e9eacee857c6db11.nq.gz
    ├── 037248a8721f1e6d934be81fe574b464b9acbf5d.nq.gz
    ├── 0374b87dd4287ef7650ee2dc099e8d3010942b18.nq.gz
    ├── 03753f607ebd159a7bef40b3776f6f635be77dbc.nq.gz
    ├── 03765fe0a086e6203388d81901c3ffd778705317.nq.gz
    ├── 0377e9284fa9bb5bc6295c9932003c9eb1ece3fe.nq.gz
    ├── 038a94c77414548f270b133c47844125b36bafd1.nq.gz
    ├── 038dc77ed3515d429bc73b7e67545dc2a9af46ba.nq.gz
    ├── 039d07b5225386964e1c60eb4add6031bd378db8.nq.gz
    ├── 03b07c4d6a6be74a47e716a6cbb9df0b181079fc.nq.gz
    ├── 03bd1523d9f798861b9e0a583b091f0c3247d6ce.nq.gz
    ├── 03bfd3b435b64c504fe40c964a1e95d9fbc5d778.nq.gz
    ├── 03c0ef1e4b99fd5153ae4f787f2f387e3214bf01.nq.gz
    ├── 03d1e82ac1151b68c64d480decad689e7205da1e.nq.gz
    ├── 03e0a5444aec37c15abb6665b2463c29129c6fbc.nq.gz
    ├── 03fa3de6d52a1532a7bf52c332eaab722bb26712.nq.gz
    ├── 040fce9a69d671cded003881e918d755a180026f.nq.gz
    ├── 0415bb3d4eb72afd866cd8db2a66d0c12cde7246.nq.gz
    ├── 0415e32ac7793c9ba11d5fe6c20c26ad37252081.nq.gz
    ├── 042d4d02d1bd8499c5b827c39c7c0afe135733da.nq.gz
    ├── 042f53a8392cef24eb5b3908a887d1005b5a8132.nq.gz
    ├── 042fe85c25730da4e0933db6cfccf8eb9c41a792.nq.gz
    ├── 043e2a3f3a14715e391dd87d3591bfb5c3e7a03a.nq.gz
    ├── 044174e0af4863e1a598199dd2e67a2d75114067.nq.gz
    ├── 04509727b8afa68044f2653af47dd0c7d9ee5ea5.nq.gz
    ├── 0451554e91032997b362b77bc1fb73714e3ad72c.nq.gz
    ├── 0460e4b7d84c9d4c95ec58b4121a1212304c7aac.nq.gz
    ├── 04620998867f0ff6f5870f547b818ffe91f42657.nq.gz
    ├── 046af6f7f6a6f4f0f83cebfeb8f1d1123f5a4637.nq.gz
    ├── 047175861910ee4eb9c7646aeb3493411a0ab6a6.nq.gz
    ├── 047df588953ff6371b66d9f7a37f983097fbe810.nq.gz
    ├── 048abd1d7e55ea366256650b1ee78222e846eb79.nq.gz
    ├── 0491b3b61e1890c7280373123a9ba34bf99e62ee.nq.gz
    ├── 049213dd4cb693794e734011e37bda62da35c948.nq.gz
    ├── 0492c3a8bcfa837317b1f988e96c50be44c85330.nq.gz
    ├── 049563fd3b767f6c7010c6b291f2676bd6c53d06.nq.gz
    ├── 04a186c72cb00971ae13aacc6d365efca7b09b3b.nq.gz
    ├── 04b357abd698ba13fb1b223129bd0d2c9e07452f.nq.gz
    ├── 04bdf3ffd1a72cfe9abfc7ec8528176f6d5f6b72.nq.gz
    ├── 04d8deb8cc73485a48d317ed684c850f7375107f.nq.gz
    ├── 04e084d9cb2a9a599822d1a64377f4f9b75be100.nq.gz
    ├── 04e70188433af4b1b48d010bb5b55d925427e7bf.nq.gz
    ├── 04ea2d1700a94ef88f99b7528f77bad031fd77ba.nq.gz
    ├── 04fa4db313c57b63f538a1c8091c06560e0e4bec.nq.gz
    ├── 05075f6e2e9cb121e8ce5d1aaf83f459b4d34124.nq.gz
    ├── 050b2066cc54202d380873118b16d25028efd7e2.nq.gz
    ├── 05199227013a70f1ca106d6e83bd53fcc2b19a82.nq.gz
    ├── 051bd11ba0bbe5c4347e251b2c6347a88eb652d4.nq.gz
    ├── 0534340b1e0ad46f1e0fa66a38a4912252dcbabd.nq.gz
    ├── 053552640a230ac47d9d3afcd0acccefc9caca14.nq.gz
    ├── 054687d0ab51bdfd4ea04e466ec6b9fd5e418a77.nq.gz
    ├── 0547c6e306e9c0a1c9209542a8365277a5cd0e5d.nq.gz
    ├── 054814d0513ded94c75898c8d2e4dbba35362c81.nq.gz
    ├── 055bd4aa56b88654fe0be9f5debad4a149afdddd.nq.gz
    ├── 05624a3a0b44d8cbd66798a6b397634903d1f76b.nq.gz
    ├── 05696381394efaec595ed22bb00599588bc77f30.nq.gz
    ├── 05753266da8dc46b397c7bf66f082bd1e549e852.nq.gz
    ├── 0581ca3356a219d5d14eca78ff0adc5771aa602c.nq.gz
    ├── 058787eb0e6b05e2f7361d86ec71334a4d082c24.nq.gz
    ├── 058dcbe4913f84859f27b797a6d77823ddcda078.nq.gz
    ├── 0595d895d8c811bad60679d4faa07966ab3db79c.nq.gz
    ├── 05978a355be6284386ca3e881d4c4c9941284f99.nq.gz
    ├── 05a2447d436777a8dc6620d51d4553ca18ad9af5.nq.gz
    ├── 05a33d48f86b0991beaf92000e01f6878ac8001b.nq.gz
    ├── 05a7271cdaf004906a0be7ed7841fe2fe5e3c16a.nq.gz
    ├── 05b57ae412d298cf0b97b0f87ac6fa830279275e.nq.gz
    ├── 05bfbd19da3ec0e1381f70a9ea2b2e34a7ccce67.nq.gz
    ├── 05c57ad843e2cd0de2fcc8d4e560541f23d8e30e.nq.gz
    ├── 05d5bbb05728e84d515b01e140f99d54c22a3d3c.nq.gz
    ├── 05db0cd500764c5ada69f278214c677f7d2f42e0.nq.gz
    ├── 05e4a31e18ead174fdd28ee70fad234f43bee1e7.nq.gz
    ├── 05e682811e0c6be3b3c89151a6147ee2b7821df7.nq.gz
    ├── 05ef610cd508025d8b4be356046045db1f5667e0.nq.gz
    └── 05f680377a1219c102c459b640c2371055dd3821.nq.gz

43 directories, 200 files
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

[pylint-dev/pylint](https://github.com/pylint-dev/pylint)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
