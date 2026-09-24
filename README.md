# Repolex Knowledge Graph of pydantic/pydantic

RDF knowledge graph data for [pydantic/pydantic](https://github.com/pydantic/pydantic), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/pydantic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 4cd172ca710a2617280563292f55b1a18f743b26
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── bd2d0dd0137dfa1a8fdff2529b9dfb1547980150
│   │   │   └── chunk-001.nq.gz
│   │   ├── cf67d4b3193c3fe43ede18612ed62785eee11382
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── ee8a3131a4676504040664d9bb39e2fb3e8fe8ae
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   └── f29bd714a4cb863d6da5101daa01250278405ee2
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   ├── 4cd172ca710a2617280563292f55b1a18f743b26.nq.gz
│   │   ├── bd2d0dd0137dfa1a8fdff2529b9dfb1547980150.nq.gz
│   │   ├── cf67d4b3193c3fe43ede18612ed62785eee11382.nq.gz
│   │   ├── ee8a3131a4676504040664d9bb39e2fb3e8fe8ae.nq.gz
│   │   └── f29bd714a4cb863d6da5101daa01250278405ee2.nq.gz
│   └── repolex
│       ├── 4cd172ca710a2617280563292f55b1a18f743b26
│       │   └── chunk-001.nq.gz
│       ├── bd2d0dd0137dfa1a8fdff2529b9dfb1547980150
│       │   └── chunk-001.nq.gz
│       ├── ee8a3131a4676504040664d9bb39e2fb3e8fe8ae
│       │   └── chunk-001.nq.gz
│       └── f29bd714a4cb863d6da5101daa01250278405ee2
│           └── chunk-001.nq.gz
└── blob
    ├── 002b60cde1bf28bbbf20af824638503d598fbc60.nq.gz
    ├── 00490ff64d22246271629f52c3d5bbcb30e02fe3.nq.gz
    ├── 00574c42448bd0fb29114419e1cc6308139f61cd.nq.gz
    ├── 00603c464703706fb900f0d02d780906e3e38eac.nq.gz
    ├── 00b8dfc6128e75df31f4694d653c71d0ff1e1eed.nq.gz
    ├── 00c68cd4248e120c56c47084aa092704747cd971.nq.gz
    ├── 00d024b0af3f739e54441a442d6c58d3e22648a4.nq.gz
    ├── 01212849e733d8f07df79b27f328a294c54d7fe3.nq.gz
    ├── 01375425661a0c4611a879d1a2e4cf07e672cdb9.nq.gz
    ├── 014af35c07fc2b3e723a27c31c57a1c903a65bbe.nq.gz
    ├── 0170dc08bc13d29ef4b23476877fc22dc81bdfff.nq.gz
    ├── 01bc28fe829e90e0e9986d1ff8b84c359827079b.nq.gz
    ├── 01cf5bbb3b6f8b411a4c001a4985245587d7d486.nq.gz
    ├── 01ea993559b227251e77be08b2ed2542817ba0fe.nq.gz
    ├── 02323b8da5924aa3285dd557b2a33533053534bd.nq.gz
    ├── 02543fd1370844a58f51c9be0341310a515a8ef6.nq.gz
    ├── 02930286df3065dac48a38fc4f47ba4bc9279b65.nq.gz
    ├── 0321ea63d3c471049ffebd8cb4ccb45a1aca5cbd.nq.gz
    ├── 03327ebdbe9370cec6987265150c54f33dc72bbe.nq.gz
    ├── 03ef0dcbada93a8d8d2fd69fcd8243fc5aea2aa3.nq.gz
    ├── 0424d27cc2ecf397e27c15b626f409f8f56c195c.nq.gz
    ├── 042b1c52e5c60170fa22a3d9ba5c25b7b4fb9fdc.nq.gz
    ├── 048a613114842710fd18b34fceaf29dafc8cd9a3.nq.gz
    ├── 04900b1439cf93f597358a7030117d0322562b8b.nq.gz
    ├── 04a7cac6b57e8401d2b12e0095838527f490a6fa.nq.gz
    ├── 0506957eca678e0394cc99fcbe3a7252bc30cc28.nq.gz
    ├── 053f3a01abbc5967004b251e1ab7d6e53faf00c6.nq.gz
    ├── 0583121bbc691b0a86edf23ba9516a8582d79648.nq.gz
    ├── 05f51d0b5fcbfc3e174caa583c50c3a5be0ff0fe.nq.gz
    ├── 0696157482a07fc519c721b2c5be444b5b97f158.nq.gz
    ├── 069ed0ba9b4c1f00a36b2fac679ddb995f03f3a1.nq.gz
    ├── 06cfa17ca5cd7eb81eab8e2e7af611b94d1f4c26.nq.gz
    ├── 0716871caabdbbb3e77a0371d49936cef1923ea1.nq.gz
    ├── 07b602e4d363f102f07edafe0ea005a54aefae35.nq.gz
    ├── 0832934485ec9c5e23d799c085422f9b08513a64.nq.gz
    ├── 08506559086d6e41172a7779a36013b3ff154e70.nq.gz
    ├── 085b2b94b807c415b2d40ea7435b9ff34d96897d.nq.gz
    ├── 0863c68ca0c3bed4e5b58118d4fc448f12fc3b48.nq.gz
    ├── 08c0e9425ebef74e9458ad187b15081d1193c27e.nq.gz
    ├── 091f2ae6d6ecf9ec966f547af5815a7077335ad6.nq.gz
    ├── 0920a54af6bcc231635d385c379c7dcea2e9216c.nq.gz
    ├── 093885caf85ba0e1ae2bef7fa4741c556d7fa9c5.nq.gz
    ├── 093e6688313022bd83f8d824c355c9992d186169.nq.gz
    ├── 0a77569218ce6f832e7221b1f557d811318402e7.nq.gz
    ├── 0b0cb935b6364b0ab0c24728ccf43158dbac8d97.nq.gz
    ├── 0b270ac976b87bc4ddb4da94bd1fef6d83b69257.nq.gz
    ├── 0b27a496626e9a4dbeafd4ac155620a837422d7d.nq.gz
    ├── 0b7653f5825979edcd446d698d320bdb980b8e9e.nq.gz
    ├── 0b92f2a1e4191d6fb756e2fe24e18a0544a7871f.nq.gz
    ├── 0bda22d02ffc59f306ded475805343aef2855f49.nq.gz
    ├── 0c1522f1bba25bc66aaa3c02a6785203ada8552f.nq.gz
    ├── 0c3f438a59a5217d6f20db6bee19849508b40369.nq.gz
    ├── 0c45ae3676398882094720d70fcbbb8f27cbeac0.nq.gz
    ├── 0c75c29f47e55ab18c88a37a8705a9c377040305.nq.gz
    ├── 0d2819ac2d680f5abaa43726e45f1288b4986340.nq.gz
    ├── 0d36a2f8662ad4cac4ce556d5d867af285449962.nq.gz
    ├── 0d97560c1b791956726b04fd66740a947647aabe.nq.gz
    ├── 0ddaf5991ffb9dacfc0f3904105f93094f59a818.nq.gz
    ├── 0e505676b92dd7c5c30fb29a175d7b43d5fcd1ff.nq.gz
    ├── 0e7a2ec381792824e0c97b9b2786254a87459abb.nq.gz
    ├── 0f27803bbb2151c9f7768b4ebccf9a6e93b5313d.nq.gz
    ├── 0f2ee07402252972d8c6f3d8ab090b3dfcc9c9f8.nq.gz
    ├── 0f365c353fb7fce14cb37e4742aef40258aac459.nq.gz
    ├── 0f7f8d3c071a88a8be10554951503bf55b4ab82a.nq.gz
    ├── 0f8cf08ade425149028d9ef0c55843e8ea6c84c7.nq.gz
    ├── 0fa00f15a573de60598ae40225385fca17a93bc9.nq.gz
    ├── 1006689fd348366d0f3a0ca76778f578374a6226.nq.gz
    ├── 100b126dff8651ae2271f4b348bc283bc15a5421.nq.gz
    ├── 10a4e52052d00a79f0ff304165f2f12660cff5cc.nq.gz
    ├── 1149472b58ce61caf27af27c25cf6124b361c419.nq.gz
    ├── 115749ebd88053d1f12981870f08112bc30bb6e2.nq.gz
    ├── 116100a5a1685fa53e9505d0fa09329ceefd219d.nq.gz
    ├── 11c403c6d7cf03ed85cb63f7a8e3a16d2ab877c5.nq.gz
    ├── 11cc01f403415fdef64ae26fdaf754f760a43789.nq.gz
    ├── 11da3670aab2e2c130235dd2c76054af6d4c5260.nq.gz
    ├── 11ed54c63614aee49e23eb1355010ac15a78a2c8.nq.gz
    ├── 122c86faae3998f4e594c791ae1afab8f332850f.nq.gz
    ├── 124f7062f835f62306e615d86e07c3b98ab9ee39.nq.gz
    ├── 1286da4902e91e8eac58486cf0e086b2fd5754c2.nq.gz
    ├── 12bdcb446290ac4aa547ceb8e5225af89704f486.nq.gz
    ├── 1307b359505e8cad12a042e8bee30a8228b07a2b.nq.gz
    ├── 13224e75e20571e5f76b9feb79611727aaf9d1fd.nq.gz
    ├── 13915de31a65ce927a67bd430a4dc483ff9c9ae2.nq.gz
    ├── 13cdd5ff5077bb0052d1a59b5b84c78853a82061.nq.gz
    ├── 14429a0d504644946f81e10cec5a4672d09947a7.nq.gz
    ├── 14d4c31a4bfbc6b59ecf0a2b353e26942702e541.nq.gz
    ├── 14f28b32502acf7263270855142f5996f3919a5c.nq.gz
    ├── 150effb96c60a336b611364793f71b95a9f9bf7e.nq.gz
    ├── 15de91204ff058ae1a821c6e1192c089e7419f97.nq.gz
    ├── 167f87774fb2ca50a1c5b7ad30eaf29862fef532.nq.gz
    ├── 16879938647133095106b82a5b8df5bea1f72715.nq.gz
    ├── 169d4d373f41f73c3965b9418d5f849832bc78cc.nq.gz
    ├── 169f611c1641dd708e722190530257a64fc0ae5e.nq.gz
    ├── 171cad83daec49d4478ed3f0e62316694f049d34.nq.gz
    ├── 17d41c972f0b1d24186222a1b2e44509423b8d55.nq.gz
    ├── 17ec3401e1298c820a6d94683770a1ea0be757b0.nq.gz
    ├── 18184629a104086e063b0851516849b67b3d1299.nq.gz
    ├── 18c6da6469b7c9a2dbf0fdf25ef13eeb86068adb.nq.gz
    ├── 18f7c999bee0fab95293b2434047fd20532a6446.nq.gz
    ├── 193c56ac67b5cd41f570ea01faa1c6c606fd305d.nq.gz
    ├── 1988d36deba8c244670aefd58c4919a88d01b9a2.nq.gz
    ├── 19b6debe2fa141ca581f97874134c87cd8587a51.nq.gz
    ├── 1a1b490fdf3b806f0eda8d2b7f5b362934f3aba1.nq.gz
    ├── 1ad3a490859b83edb37495d6baf95a86c9f7e572.nq.gz
    ├── 1afc3d172e1c7be962989fe5318d62567baff793.nq.gz
    ├── 1bde0cdcc8bdf6a2ed82be35de8b53cc78e8d437.nq.gz
    ├── 1be1662324162741203aea7f9bf45a317b84e573.nq.gz
    ├── 1c2c9fb94d707632c7b309300df22f46ec5ae0f4.nq.gz
    ├── 1c6d7c06a3562d2a98db06c824e86c13c130fb4c.nq.gz
    ├── 1d3bef0c83783633c6b6f146a7552232215c51a2.nq.gz
    ├── 1d8e78ae2701ce3f44e0a6bf9dd0e4ae308406c0.nq.gz
    ├── 1d9b8756e4f3e9864e2a6d88667390dddcfd2fcb.nq.gz
    ├── 1dd4844538c33c8b6cc6493a7615d32865ed3075.nq.gz
    ├── 1e216a765d15d5dd9e379f9de4f8f91ab8063877.nq.gz
    ├── 1e4dfa6bc845f991c3746b36ac7147c4008c9de1.nq.gz
    ├── 1e932d7ce69b799e1f370a72c1e587118550b073.nq.gz
    ├── 1e9927eb9d6fa570aa35ea38ae0f97d1e0e6dbaf.nq.gz
    ├── 1eef441cebb485f8adc08c7c33b2e3031961f3fd.nq.gz
    ├── 1f18015410fe5ca7d9a0c3494d483c9168cbd400.nq.gz
    ├── 1f99a762f9b6157c63d0846472e9c78ce0128d71.nq.gz
    ├── 1fb5dccb8cf2de7753cdcd0417b5e2a67ea2259c.nq.gz
    ├── 2039c488c863d13bd9ec6406860610bcc039dce7.nq.gz
    ├── 208cafbd9277f63221bb186a263ede3f88792d72.nq.gz
    ├── 2094e84fad951d6620635cf86f7f5fb647c5c20b.nq.gz
    ├── 20b25020f69c8efa7434548d8b28235c5dcf4916.nq.gz
    ├── 20f6ab456b44ea37c028f7a46cbefa1fad5ecfb0.nq.gz
    ├── 211631fc45c08d12346fdb5b146a247014cad42a.nq.gz
    ├── 212a6bb11aaa2fd65acd84655db8631ecbf8b138.nq.gz
    ├── 219930c5045797aba7a3c1f3b48b67881b94cba8.nq.gz
    ├── 21ab373425f620584e366a84b90e42aa69c6e23a.nq.gz
    ├── 21bbe59eaeb1e02b817b13b01c5b4b18993d5249.nq.gz
    ├── 21ec09939953ba4fb4bc77352c829147882eba1b.nq.gz
    ├── 21faeab633979263792c2c53839f3abbdcce806b.nq.gz
    ├── 21fd24f0b9946d5c72d769693f5c783613d38777.nq.gz
    ├── 220a72433f2014cd41cf2917ec20e5518834d1a6.nq.gz
    ├── 22611bb89b4e72278797d2f601d4f6828fea5df2.nq.gz
    ├── 22847bacea472e9e647f0bb199f23e1fd5314c2e.nq.gz
    ├── 231f81d11b87ef05d4765cd61d88d7348eb9e401.nq.gz
    ├── 2357e4750c0ac4c79378b0fefa643523a32e8374.nq.gz
    ├── 23a01568c28467239198e51bb91eab902c9f265d.nq.gz
    ├── 23c8dcb242dfbce20a90578960b241f117da652d.nq.gz
    ├── 23e484789dc6e9db177251f325136d8af6b5c521.nq.gz
    ├── 240a6c3d029cdcf3b352cea9bd48f2749fc7ed8d.nq.gz
    ├── 243fbfb9551f2ec8b39d911e9e1c9dab7e1bf3a6.nq.gz
    ├── 2464a526245477d81650641ff0f26682a255cd03.nq.gz
    ├── 24e40acd485a735df8f9c2be68f926b977ce2c82.nq.gz
    ├── 24e82be3288f86860ae53273aafdd57ac3dee152.nq.gz
    ├── 25f0e57d1acc4635805f6df439e17a91783713db.nq.gz
    ├── 2645c99efac307064ca2d7c7809560667a7c6641.nq.gz
    ├── 26609578ca229ee46864a1de7b4708b9c2041b36.nq.gz
    ├── 2684443ea93b63cb9925ebd5c04564cde3d8a5a6.nq.gz
    ├── 2687423362395eaec26d4a57406e43eaeab0ad7b.nq.gz
    ├── 26a60bb77bd46abfa3169b5e7c31df53c2ccb883.nq.gz
    ├── 2735dbf7cd8992989e80397b2e75ef2940041929.nq.gz
    ├── 275afaeecdcbb382fe3b1b35bfe47ce8232efc7e.nq.gz
    ├── 27a061e4e975659563282b96cd648377a64bd3bc.nq.gz
    ├── 27cd6d2b5cd8a6bf6d021dc1ab9dcf07055210f7.nq.gz
    ├── 2816098b66ef60024d60c6d125b5dd891f76b2e3.nq.gz
    ├── 285ade7df2154e512d85ad4d0d75fd175998ba5b.nq.gz
    ├── 286b327d7685b92ab201a73d630019315f953dad.nq.gz
    ├── 289574c73158ec5d151467539979f06ba42f5cd7.nq.gz
    ├── 28a649ef69a445468ac61d32c86ef22dedee91dc.nq.gz
    ├── 2918305630853d6c02bc179d799d69a27de32dfc.nq.gz
    ├── 2919e8b080acc3dfef859093b2628c751e16670e.nq.gz
    ├── 29772757208407925ed2e4ba3a6a3e914e804162.nq.gz
    ├── 297a2518b38d81c1854b1f45ea7c57e1a91e4d65.nq.gz
    ├── 2985419abf23f5e529af43883f1d365452e4190a.nq.gz
    ├── 29fd3e33f907e2d6eb434a0ef6e60481da88fb2a.nq.gz
    ├── 2a43bbb63da592437bfc78068b53c779ce3fb956.nq.gz
    ├── 2a8db87535375f8a50243e95f9c1df032677fba6.nq.gz
    ├── 2a92e62b7b2e8dab77cbe0c2dbb79c810af7f452.nq.gz
    ├── 2b2a647605c62d0e7603db8fd76d51267e8c59cb.nq.gz
    ├── 2b3148eda1d687ebbd6636a6ce427a23a9ab19bb.nq.gz
    ├── 2ba38ee239316c5c74040e2e4f1fe87a1acea5e5.nq.gz
    ├── 2bfa0a1cb6666c06f4a72b5c5908517ee87286c5.nq.gz
    ├── 2c4d8c6af3ad9074863dbb177530a21b501d6ed4.nq.gz
    ├── 2c7c2c2ffdb45ca50cd2b7e57bde1fc711adb851.nq.gz
    ├── 2c7fab66dc26d33cbfc256e44c9e15379463535a.nq.gz
    ├── 2c9499fbe2490b95e6582ad5f7d25080bc319069.nq.gz
    ├── 2d793c0309edeb7a4bfc2384a7b634f6bbdd6d0b.nq.gz
    ├── 2e1360971f8e778804469fabc5598815dd2ec11b.nq.gz
    └── 2e2dd83c13e00e95196734a07eda2c3f8d408654.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[pydantic/pydantic](https://github.com/pydantic/pydantic)

---
*Parsed on 2026-09-24 by [repolex](https://repolex.ai)*
