# Repolex Knowledge Graph of pydantic/pydantic

RDF knowledge graph data for [pydantic/pydantic](https://github.com/pydantic/pydantic), parsed by [repolex](https://repolex.ai).

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
lexq download pydantic/pydantic
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ee8a3131a4676504040664d9bb39e2fb3e8fe8ae
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── ee8a3131a4676504040664d9bb39e2fb3e8fe8ae.nq.gz
│   └── repolex
│       └── ee8a3131a4676504040664d9bb39e2fb3e8fe8ae
│           └── chunk-001.nq.gz
└── blob
    ├── 002b60cde1bf28bbbf20af824638503d598fbc60.nq.gz
    ├── 00490ff64d22246271629f52c3d5bbcb30e02fe3.nq.gz
    ├── 00574c42448bd0fb29114419e1cc6308139f61cd.nq.gz
    ├── 00603c464703706fb900f0d02d780906e3e38eac.nq.gz
    ├── 00b8dfc6128e75df31f4694d653c71d0ff1e1eed.nq.gz
    ├── 01212849e733d8f07df79b27f328a294c54d7fe3.nq.gz
    ├── 014af35c07fc2b3e723a27c31c57a1c903a65bbe.nq.gz
    ├── 0170dc08bc13d29ef4b23476877fc22dc81bdfff.nq.gz
    ├── 01bc28fe829e90e0e9986d1ff8b84c359827079b.nq.gz
    ├── 01cf5bbb3b6f8b411a4c001a4985245587d7d486.nq.gz
    ├── 01ea993559b227251e77be08b2ed2542817ba0fe.nq.gz
    ├── 02323b8da5924aa3285dd557b2a33533053534bd.nq.gz
    ├── 02930286df3065dac48a38fc4f47ba4bc9279b65.nq.gz
    ├── 0321ea63d3c471049ffebd8cb4ccb45a1aca5cbd.nq.gz
    ├── 03327ebdbe9370cec6987265150c54f33dc72bbe.nq.gz
    ├── 03ef0dcbada93a8d8d2fd69fcd8243fc5aea2aa3.nq.gz
    ├── 0424d27cc2ecf397e27c15b626f409f8f56c195c.nq.gz
    ├── 042b1c52e5c60170fa22a3d9ba5c25b7b4fb9fdc.nq.gz
    ├── 04900b1439cf93f597358a7030117d0322562b8b.nq.gz
    ├── 0506957eca678e0394cc99fcbe3a7252bc30cc28.nq.gz
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
    ├── 0b7653f5825979edcd446d698d320bdb980b8e9e.nq.gz
    ├── 0b92f2a1e4191d6fb756e2fe24e18a0544a7871f.nq.gz
    ├── 0bda22d02ffc59f306ded475805343aef2855f49.nq.gz
    ├── 0d2819ac2d680f5abaa43726e45f1288b4986340.nq.gz
    ├── 0d36a2f8662ad4cac4ce556d5d867af285449962.nq.gz
    ├── 0d97560c1b791956726b04fd66740a947647aabe.nq.gz
    ├── 0ddaf5991ffb9dacfc0f3904105f93094f59a818.nq.gz
    ├── 0e505676b92dd7c5c30fb29a175d7b43d5fcd1ff.nq.gz
    ├── 0e7a2ec381792824e0c97b9b2786254a87459abb.nq.gz
    ├── 0f27803bbb2151c9f7768b4ebccf9a6e93b5313d.nq.gz
    ├── 0f365c353fb7fce14cb37e4742aef40258aac459.nq.gz
    ├── 0f8cf08ade425149028d9ef0c55843e8ea6c84c7.nq.gz
    ├── 0fa00f15a573de60598ae40225385fca17a93bc9.nq.gz
    ├── 1006689fd348366d0f3a0ca76778f578374a6226.nq.gz
    ├── 100b126dff8651ae2271f4b348bc283bc15a5421.nq.gz
    ├── 10a4e52052d00a79f0ff304165f2f12660cff5cc.nq.gz
    ├── 1149472b58ce61caf27af27c25cf6124b361c419.nq.gz
    ├── 115749ebd88053d1f12981870f08112bc30bb6e2.nq.gz
    ├── 116100a5a1685fa53e9505d0fa09329ceefd219d.nq.gz
    ├── 11cc01f403415fdef64ae26fdaf754f760a43789.nq.gz
    ├── 11da3670aab2e2c130235dd2c76054af6d4c5260.nq.gz
    ├── 11ed54c63614aee49e23eb1355010ac15a78a2c8.nq.gz
    ├── 122c86faae3998f4e594c791ae1afab8f332850f.nq.gz
    ├── 124f7062f835f62306e615d86e07c3b98ab9ee39.nq.gz
    ├── 1286da4902e91e8eac58486cf0e086b2fd5754c2.nq.gz
    ├── 1307b359505e8cad12a042e8bee30a8228b07a2b.nq.gz
    ├── 13224e75e20571e5f76b9feb79611727aaf9d1fd.nq.gz
    ├── 13915de31a65ce927a67bd430a4dc483ff9c9ae2.nq.gz
    ├── 13cdd5ff5077bb0052d1a59b5b84c78853a82061.nq.gz
    ├── 14429a0d504644946f81e10cec5a4672d09947a7.nq.gz
    ├── 14d4c31a4bfbc6b59ecf0a2b353e26942702e541.nq.gz
    ├── 167f87774fb2ca50a1c5b7ad30eaf29862fef532.nq.gz
    ├── 16879938647133095106b82a5b8df5bea1f72715.nq.gz
    ├── 169d4d373f41f73c3965b9418d5f849832bc78cc.nq.gz
    ├── 17d41c972f0b1d24186222a1b2e44509423b8d55.nq.gz
    ├── 17ec3401e1298c820a6d94683770a1ea0be757b0.nq.gz
    ├── 18184629a104086e063b0851516849b67b3d1299.nq.gz
    ├── 18c6da6469b7c9a2dbf0fdf25ef13eeb86068adb.nq.gz
    ├── 18f7c999bee0fab95293b2434047fd20532a6446.nq.gz
    ├── 193c56ac67b5cd41f570ea01faa1c6c606fd305d.nq.gz
    ├── 1988d36deba8c244670aefd58c4919a88d01b9a2.nq.gz
    ├── 1a1b490fdf3b806f0eda8d2b7f5b362934f3aba1.nq.gz
    ├── 1afc3d172e1c7be962989fe5318d62567baff793.nq.gz
    ├── 1bde0cdcc8bdf6a2ed82be35de8b53cc78e8d437.nq.gz
    ├── 1be1662324162741203aea7f9bf45a317b84e573.nq.gz
    ├── 1c2c9fb94d707632c7b309300df22f46ec5ae0f4.nq.gz
    ├── 1c6d7c06a3562d2a98db06c824e86c13c130fb4c.nq.gz
    ├── 1d8e78ae2701ce3f44e0a6bf9dd0e4ae308406c0.nq.gz
    ├── 1d9b8756e4f3e9864e2a6d88667390dddcfd2fcb.nq.gz
    ├── 1dd4844538c33c8b6cc6493a7615d32865ed3075.nq.gz
    ├── 1e216a765d15d5dd9e379f9de4f8f91ab8063877.nq.gz
    ├── 1e932d7ce69b799e1f370a72c1e587118550b073.nq.gz
    ├── 1e9927eb9d6fa570aa35ea38ae0f97d1e0e6dbaf.nq.gz
    ├── 1eef441cebb485f8adc08c7c33b2e3031961f3fd.nq.gz
    ├── 1f99a762f9b6157c63d0846472e9c78ce0128d71.nq.gz
    ├── 208cafbd9277f63221bb186a263ede3f88792d72.nq.gz
    ├── 2094e84fad951d6620635cf86f7f5fb647c5c20b.nq.gz
    ├── 20b25020f69c8efa7434548d8b28235c5dcf4916.nq.gz
    ├── 20f6ab456b44ea37c028f7a46cbefa1fad5ecfb0.nq.gz
    ├── 211631fc45c08d12346fdb5b146a247014cad42a.nq.gz
    ├── 21ab373425f620584e366a84b90e42aa69c6e23a.nq.gz
    ├── 21bbe59eaeb1e02b817b13b01c5b4b18993d5249.nq.gz
    ├── 21ec09939953ba4fb4bc77352c829147882eba1b.nq.gz
    ├── 21faeab633979263792c2c53839f3abbdcce806b.nq.gz
    ├── 21fd24f0b9946d5c72d769693f5c783613d38777.nq.gz
    ├── 220a72433f2014cd41cf2917ec20e5518834d1a6.nq.gz
    ├── 22611bb89b4e72278797d2f601d4f6828fea5df2.nq.gz
    ├── 22847bacea472e9e647f0bb199f23e1fd5314c2e.nq.gz
    ├── 231f81d11b87ef05d4765cd61d88d7348eb9e401.nq.gz
    ├── 23a01568c28467239198e51bb91eab902c9f265d.nq.gz
    ├── 23e484789dc6e9db177251f325136d8af6b5c521.nq.gz
    ├── 243fbfb9551f2ec8b39d911e9e1c9dab7e1bf3a6.nq.gz
    ├── 2464a526245477d81650641ff0f26682a255cd03.nq.gz
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
    ├── 285ade7df2154e512d85ad4d0d75fd175998ba5b.nq.gz
    ├── 286b327d7685b92ab201a73d630019315f953dad.nq.gz
    ├── 289574c73158ec5d151467539979f06ba42f5cd7.nq.gz
    ├── 2918305630853d6c02bc179d799d69a27de32dfc.nq.gz
    ├── 29772757208407925ed2e4ba3a6a3e914e804162.nq.gz
    ├── 2985419abf23f5e529af43883f1d365452e4190a.nq.gz
    ├── 29fd3e33f907e2d6eb434a0ef6e60481da88fb2a.nq.gz
    ├── 2a92e62b7b2e8dab77cbe0c2dbb79c810af7f452.nq.gz
    ├── 2b2a647605c62d0e7603db8fd76d51267e8c59cb.nq.gz
    ├── 2ba38ee239316c5c74040e2e4f1fe87a1acea5e5.nq.gz
    ├── 2bfa0a1cb6666c06f4a72b5c5908517ee87286c5.nq.gz
    ├── 2c4d8c6af3ad9074863dbb177530a21b501d6ed4.nq.gz
    ├── 2c7c2c2ffdb45ca50cd2b7e57bde1fc711adb851.nq.gz
    ├── 2c9499fbe2490b95e6582ad5f7d25080bc319069.nq.gz
    ├── 2d793c0309edeb7a4bfc2384a7b634f6bbdd6d0b.nq.gz
    ├── 2ec39d466edeaf2f2622c56d8cc4f6b51679eff5.nq.gz
    ├── 2f68fc8600038d8de10017b0d02a3fde77a06ba6.nq.gz
    ├── 2f6b72527864c92062b99a2477fed47f3c2b069f.nq.gz
    ├── 2f71cbedfa1eeeadf651494d3c0337694c450399.nq.gz
    ├── 300c841fafc27740d0f1ae5f6a3896cbfae46ae7.nq.gz
    ├── 30716c0c599a87992a65f032239109bffbd2aa12.nq.gz
    ├── 30bcf8b86516c0d93f48514a3d99d27ed0f80763.nq.gz
    ├── 30f28276fb58fa05572cb2dc2be4a5ba5f486cd3.nq.gz
    ├── 30fb7a8ae5511464f61fee43c9d022fa078a536b.nq.gz
    ├── 31459a15ea844c7002c9bdd5cddb5c4d9cb05759.nq.gz
    ├── 31a0ef1f5e9834d5b6b7ed2d2be4d99b01874753.nq.gz
    ├── 31c802685e161d863e4ba34bac441a57bfc0dcad.nq.gz
    ├── 31fd6b49a0bacf587bba4ecbf9e2231526b7766f.nq.gz
    ├── 32122a675fdc7f9907acc5454bc00f4d804361f1.nq.gz
    ├── 3257bde68a36d765c729ccfca6171c1e13655068.nq.gz
    ├── 3261381281ae15f1965676fdc692b7980f061491.nq.gz
    ├── 3281e6e0dd6b796d56c19d0a3c8a2e172a9211cb.nq.gz
    ├── 32ab9e0456f32cb3a14e4b379b5f5a086dbb6fc0.nq.gz
    ├── 3303ce3976acfef16f6d3c54cfc5994cb817e9cc.nq.gz
    ├── 3315aa190476c68f03ed6f70546e3f20f798699e.nq.gz
    ├── 3370bdda29d43609b3256794daf5c0189d2b6287.nq.gz
    ├── 33851bded20b1125a3b55ecc03727692ed78e1db.nq.gz
    ├── 3385e9ee9aae98ef00de3ff8a9e43caba18ca303.nq.gz
    ├── 33e152cc8d178486ef016285855495a86d5991d8.nq.gz
    ├── 34273779d77666f5cd775f6a2684641092db67ee.nq.gz
    ├── 343a2ecc09f82c47f713085954a836819caadfbe.nq.gz
    ├── 34aabeea1d10f0ee794f0813208eafd9ead56f32.nq.gz
    ├── 352c20de42b6c4589b2ca11e39e1e09a01493c49.nq.gz
    ├── 360f73ac93ca2a708f054ed7259ae920543c122d.nq.gz
    ├── 36e1d91c8442f346acaa3ac8d83b008b5549e327.nq.gz
    ├── 36e9c44c98735ece2d784f5ad1d60b783e39ce59.nq.gz
    ├── 375668734948e503aa1fbac2b668bf9e2124c078.nq.gz
    ├── 37eb16d113b9defe944c187ffef4de2349b3fc5c.nq.gz
    ├── 3808e05cc280dd330f3f94d8474580a03ba61115.nq.gz
    ├── 3839b531302b58b6c6362a0f5a29c7b48a207722.nq.gz
    ├── 3925ae5230c28b8ea577f8bea5bdb21077be170c.nq.gz
    ├── 395cd8777e73d039209629290072ccb44c12dc9e.nq.gz
    ├── 3ad6c92790404b7b63cafed02e9dccb5c4fb7a3a.nq.gz
    ├── 3aec073a88ceb32c9b680f610a87b3808a27e104.nq.gz
    ├── 3b0c5ae8c40158a28a3b0cf21116c9695208076e.nq.gz
    ├── 3b4f3553fa14159b3382d24376a66aeee6171e6b.nq.gz
    ├── 3cc4ac111f19eee887d4d758e857c6985e9eeb85.nq.gz
    ├── 3d0af409a821187a346fcf38bd76ef2a16b95fb5.nq.gz
    ├── 3e376ae2f3e06ef58fedc231cda3913a4641391c.nq.gz
    ├── 3e65fa317fc804007c34249e1c697f72d9c94837.nq.gz
    ├── 3e7f820ceda3b8d984f01ad0aaa1e150f06beda3.nq.gz
    ├── 3edb81c06e1942726dc0164930c7a54beb871a69.nq.gz
    ├── 3ee0ac2f837aeea170d4f6259437f41567869ac3.nq.gz
    ├── 3f1070d08f3ac5bd554794401734eb349373ab8e.nq.gz
    ├── 3fcdf3ad66031e3b0e20fca5893101f956b72a66.nq.gz
    ├── 4015bad6b0db49006923bc1ba05fd0b8c06e072a.nq.gz
    ├── 40bada8a348be11b3ecabb7c3b33910614650c53.nq.gz
    ├── 40d0fa55c73ae4d4b137878aa3de668b5439573f.nq.gz
    ├── 40ffb1ddccd6d999b6b3b48a441d7b3cfac877c2.nq.gz
    ├── 411b2202e36c938d53e0313e9dafaf506a7d40c1.nq.gz
    ├── 4156bc04fdd5368e86723951ec97ab53cc75a51d.nq.gz
    ├── 4175cac8a7fc8b25793bb332288ca2b91bbf19f0.nq.gz
    └── 41a831eca2b458d6748ce66eea63598e28eb0a14.nq.gz

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

## Source repository

[pydantic/pydantic](https://github.com/pydantic/pydantic)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
