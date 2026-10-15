# Repolex Knowledge Graph of twisted/mantissa

RDF knowledge graph data for [twisted/mantissa](https://github.com/twisted/mantissa), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/mantissa
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 53e5502aba23ce99be78b27f923a276593033fe8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 53e5502aba23ce99be78b27f923a276593033fe8
│           └── chunk-001.nq.gz
└── blob
    ├── 00626384463469626301def26485669f97d8db6f.nq.gz
    ├── 007c90e2dd96a9ceb6af765608288c5d374897ac.nq.gz
    ├── 03161e10d3d974bfa2d6db87f4024e151c71efd9.nq.gz
    ├── 0390f328cec197fb3cacd7ec5efb4aad2ee69fb7.nq.gz
    ├── 0495e1efd512a32380f658d979a5d96d469a60e3.nq.gz
    ├── 05c6338247c93d2aefffad6fa23d8db20171b95a.nq.gz
    ├── 065a57b1ab2b78ed13b45a55f5e27dceaeedfe0d.nq.gz
    ├── 06650edf10a5831c7f8a612b402791ad67e12b43.nq.gz
    ├── 069dadec6a16c01c4f1437ad8e427373bab2a858.nq.gz
    ├── 072768f2898940a3eb0f750a35e492ae03a61def.nq.gz
    ├── 074bf0108e1b1390bcb4a2efd4040aab43bbf7cc.nq.gz
    ├── 0788129b63b16505e644b052b5d5ec57b11e8e03.nq.gz
    ├── 078f3c0018a307366274ee4d1d2710419e2af7f1.nq.gz
    ├── 0aedb0ea79f50e076131f73032c5f86367e1c0ae.nq.gz
    ├── 0c0487f806efdf363fbbdd2c8ebd07ccb13612cb.nq.gz
    ├── 0c1a488c42b95cd847b9a8ef0ba997bc8b6c340a.nq.gz
    ├── 0c4ccbe8dc11958b67f924ac71841a5d430aa79f.nq.gz
    ├── 0c5e01ff227dc33b1f849965533d40ef0a683281.nq.gz
    ├── 0dde3b1ef87b4fec9c26fcea1ee66ed20cf1e5ee.nq.gz
    ├── 0e145e790268f6e5a1e976f5b17f817cd5ef1567.nq.gz
    ├── 0e1f626fec0411920fec4c047ae666a024b744e4.nq.gz
    ├── 10a6228f83222cbf8a02d5a6f66d4df3811dd947.nq.gz
    ├── 12364bcca578a3721119568bbd62c5e95643d5ce.nq.gz
    ├── 128885d56db3c42297efbd532a8a5db4174000fa.nq.gz
    ├── 1319922efe6744c55a322e3ba68cbc6ccf103b9c.nq.gz
    ├── 132e890f389e51b4c444294d5db8e0930b688234.nq.gz
    ├── 14678e4e7434ce7a27dd7b428f7af83a6e98a30b.nq.gz
    ├── 14ee8e79a0befc8f9e58a78511fa9b0c982f79fc.nq.gz
    ├── 15417cdb9876c6b4943a3ad3f481dcb63a4d1f74.nq.gz
    ├── 15619b7d4c2c480eeacfa569ab750aa031febe10.nq.gz
    ├── 16e4f99267a1c546d62aac85ea28add355390009.nq.gz
    ├── 1823855f168f88cd06a231a62df8c9e358ec0bac.nq.gz
    ├── 1860e79b3722024a52c43093541276efa132026d.nq.gz
    ├── 1868fce67c6ab6e507ab139038e2932a4a4a26c6.nq.gz
    ├── 186b1ca6c69558f21ead4ad3e466208752baf13b.nq.gz
    ├── 18eb81daba92e0b501deb31b3d8683d1d978177f.nq.gz
    ├── 18f635b374374c38a4c8b48c95188536d98e9fc3.nq.gz
    ├── 194f5ce0da8cc785e9a79e8103e1f6921bd663f1.nq.gz
    ├── 1a79eeac88453654638db9192535898ef31080d0.nq.gz
    ├── 1abc68ac43302be9c44add350bfe38fd58071df0.nq.gz
    ├── 1ae4862d8e6ec4c383625366b4f9fb02ac658c8a.nq.gz
    ├── 1b72f7e85fcb54679a4eb81db3e28b4baa3f02b1.nq.gz
    ├── 1c7000d4474d8b1bc029f68354bb8825382722c9.nq.gz
    ├── 1dadbb39b3596c6091c0c11c3a1d192e0a4be68d.nq.gz
    ├── 1de78fb2c93b6d4d15f3db8228738a0b46a38997.nq.gz
    ├── 1eeceda46ad79f81aab369290945786749ca821b.nq.gz
    ├── 1ef3ba05103d887b98b74efc9e2aa3a30fdd8819.nq.gz
    ├── 2026f58d458b612648ccd8ffaedf366a1c550e29.nq.gz
    ├── 21114f1e6b6304faa21263f692f6575ee6432941.nq.gz
    ├── 22977b043b2522fca1fe4a950ba6c4813ea117bb.nq.gz
    ├── 229dd6337ac0d51e45450de05ec7f5955c294b9d.nq.gz
    ├── 233f13b034b28ee0c846c11767ce6177b9e1cc51.nq.gz
    ├── 238b073080690ca2f36aa1215373f657aa92502d.nq.gz
    ├── 26b55fe2951000eae1c5857b517e9b9e72674135.nq.gz
    ├── 26e1d172c0300b40567c75f4dd1cab7d72965384.nq.gz
    ├── 27fad372e4de5a27dda2d90830545f2ee013cfcb.nq.gz
    ├── 2852e662eba8908841503edda479785416c937bd.nq.gz
    ├── 28f8b9311d8b6e2f505434e9d805edc3a33e8eb2.nq.gz
    ├── 2905ae736463ab23fc845edbdb895eac6cecaa1a.nq.gz
    ├── 2951eed9265bf0e05c3510490f252a1c1d1986e3.nq.gz
    ├── 295f7fcd00ce4aa9d2e0af79b97a26308c75985d.nq.gz
    ├── 29e6052471727857f859922a15368c76f73c498a.nq.gz
    ├── 29ead04c17971cf325511e84b392aec557a3f8b4.nq.gz
    ├── 2abde16466fd23e446b3366fb3133d5b8bcbae22.nq.gz
    ├── 2b069ce445bfdb33f836ba55365b717bfa502f54.nq.gz
    ├── 2b84cec68932baf92d57c8ef202205d802ad8c20.nq.gz
    ├── 2c45ab958c7b139720b2902be2210015acee5c18.nq.gz
    ├── 2dd6a089378a5a6b277f3a4cad646a31830139b1.nq.gz
    ├── 2e60344a8a7c447a506b6841b271349e8efbf7a4.nq.gz
    ├── 2f51a107585e382808f10104e23ebf35f7f6037e.nq.gz
    ├── 311e9a013f6cad5ba2c85151702179c7cba1a2b8.nq.gz
    ├── 31d71f9722b270cc657f50fd2122cbcbdffc6703.nq.gz
    ├── 327afd161fa1b8d9d05ff7e1750632d0aee9d2a2.nq.gz
    ├── 3379cbfc8785769860cc2a63deb72512b6778dad.nq.gz
    ├── 34f049a8159e4953b3e1216ff7b87200977aa969.nq.gz
    ├── 358ef4c2a805b5de184070236f9b1b3904f101be.nq.gz
    ├── 363ce41f78fcc14939122ae1a6dfc45c685b3962.nq.gz
    ├── 3711ad99e3c5f7ea2904005221c9cef6a552f769.nq.gz
    ├── 3778f85a64f4e2a4793f22659932d06a2dabde0f.nq.gz
    ├── 37f5d68922f064e06044d1f7d02207585defba34.nq.gz
    ├── 389b41d5065064b10e07db14150b14944fa0878c.nq.gz
    ├── 397cd73a137fc86334b01e81f52dc47e1b8c6bab.nq.gz
    ├── 3adf9d45626c64ab0ba9e2308ffbdf5be1ea39f7.nq.gz
    ├── 3b0a2f1e8e6120481215d820337ac69ee7cd0ed3.nq.gz
    ├── 3b1bc16abf9e2023299efeea3357d471c1184341.nq.gz
    ├── 3b5699726180b9673b2e3771d6083f5ea843518f.nq.gz
    ├── 3b81a27c3b4345e5456a1d56a1960a7a83e42af8.nq.gz
    ├── 3bc755869e5befd896de717ba06fe5b7f1a58c69.nq.gz
    ├── 3bda85913b3e1ce5307d081e99676ec8089b9d56.nq.gz
    ├── 3c5961e7e3f912be39c211740f1ff71b126e9a16.nq.gz
    ├── 3d5ed6a1f337a656a2fb391620b66671e48f2106.nq.gz
    ├── 3d94d87c2e4dc84126fee4d52d8895cfd454bd13.nq.gz
    ├── 3dc8b17b4d514da2c606f0e085a2c60311ef8185.nq.gz
    ├── 3e926ce95437ee24177ce8280fde1a9017701d1b.nq.gz
    ├── 410c445b37b886197f86af529aec49aa6523f830.nq.gz
    ├── 41bae588b46ddbd85960a13d30dd6690133f3f51.nq.gz
    ├── 41f8379e607d23bb61566e3db4efeb16dbdf58ed.nq.gz
    ├── 4215d782a97f7e4ea53f606a5cb28129675e92a8.nq.gz
    ├── 433474eed80679b43617fe5b254b8ee929f3149e.nq.gz
    ├── 433bdbf4907b14b59695cf2bca5129b51f080170.nq.gz
    ├── 433f789566ae979ef7311a214287d641b5242b66.nq.gz
    ├── 4448bca56ec8330ccc5f75b70a85e9b9cbf971ee.nq.gz
    ├── 44a658319c78cf842c774240ea63b1d7edce060f.nq.gz
    ├── 4676425f06fd5090be93682f011d4c8ab8c05205.nq.gz
    ├── 46dfadd86eb63404ef339d1f569efa1dfa5ae8bc.nq.gz
    ├── 4701e2467720e721a5925f9aa21131b4141a92ce.nq.gz
    ├── 470f796720169bc46f40c8d4d2c6b9062d68fe74.nq.gz
    ├── 475bf9520f32565fe2e3b6fdd5756c83e49a3bf6.nq.gz
    ├── 47d450b75dcc338b94771b337cd698c7cd62f7d2.nq.gz
    ├── 480364ebd003ff2e45066d2ab1fcb63072e8dbf1.nq.gz
    ├── 481f28cd88a03933db97d876d4d4106b743803b0.nq.gz
    ├── 484484c8f518c4849b17d4d9e63d812f45791f94.nq.gz
    ├── 486489ca3b22103f2429a17c7e322b5b5301df49.nq.gz
    ├── 48da70554e61bb90ba3e489e904b0088ab024843.nq.gz
    ├── 4905b981b6f86ba5b1a1bcf715434352ac046f2e.nq.gz
    ├── 495a3d3f40369039b9b26c12b028455f5b054f96.nq.gz
    ├── 49b8f8483ef9e949cc9f36ca281c6f4b6530c1b2.nq.gz
    ├── 49fb8e883b9d36f816c1d0ec0b18141a5e3a55ec.nq.gz
    ├── 4d392df473ae6b6b058b40247ea4128bb6730e5e.nq.gz
    ├── 4e64155ddb9944c5f4ecd444c6703fb67a174ea4.nq.gz
    ├── 4e876b4dc6051f963e494076df89ab1e145cbfc4.nq.gz
    ├── 4efdd786d8f1d1f43a389d79fb3b7b477484a294.nq.gz
    ├── 4fc2ed41f1dbe315a514c98c454a512f3bc21f61.nq.gz
    ├── 50002add3877bb8fd28db97fdc6e99463b156787.nq.gz
    ├── 50618e0a07aa94335162ed82d8cf8afe0ea3d152.nq.gz
    ├── 536ac381851a46fa0c96fcb47e9c23ec3744a290.nq.gz
    ├── 539f5c5fd2ecf7a4f57a1d45cd5e7a8bdeacfdef.nq.gz
    ├── 53dfb0787b27b121375dd0b252a94c9727b3e2a3.nq.gz
    ├── 540017b9666133ad8f320967f8cedc767014a4ef.nq.gz
    ├── 548b59b8f9827525050b8943c3cdf3c819171e1d.nq.gz
    ├── 55c907dc1a599fd5158a2f5317a0ed9a15e7d948.nq.gz
    ├── 56253978228ca85a1932460e0f52ebe2cca2192f.nq.gz
    ├── 56647ce7e1667749c7482488d629952c0185994a.nq.gz
    ├── 566b2a0187bac6167aaad119b8a2aab0c5ef87ec.nq.gz
    ├── 567b97d273cf618f299248edf97fed75b759bd51.nq.gz
    ├── 56e120eedb46d77f03952ad18d33d93874f5fabb.nq.gz
    ├── 5704d2270330dabd3b0ecc6c636ac1791ff8a919.nq.gz
    ├── 57a63ec116cb7c5951b3d8afd7b43bd3794d8703.nq.gz
    ├── 57c90c61aa07b0f7e1dfc6ada91bfcac78b77fda.nq.gz
    ├── 584a0fc0c4dd0242702a99699ce9a48973af1f9d.nq.gz
    ├── 5892ee873199e300410511a7c12df870ac861c59.nq.gz
    ├── 597df4b82d70b92be167f4eb5f3d3857a608a3d4.nq.gz
    ├── 5a2450a2d6f749b547c4407704a3fc064fcf3774.nq.gz
    ├── 5a381e7756451d181c0c5b7aa754f66463e5d4bb.nq.gz
    ├── 5adc31e1b70cca727cd105bd37414f83971f3ac1.nq.gz
    ├── 5b730df0455628b86a4dfbf9d7bdb4592b5b0d4b.nq.gz
    ├── 5f45d26d2221cbe5c6c6f98c1e2e168812d03883.nq.gz
    ├── 5f6627fb0a09d4be03829ac76af042f4c95022c3.nq.gz
    ├── 6064b38fbb8056fe25860e8b011a9f2b8a5423dc.nq.gz
    ├── 60d6a92bcec890cfbf4fab426b428bff541f62ef.nq.gz
    ├── 610f99e40c95faebac6af66027964e798b0fed76.nq.gz
    ├── 6111a6d381946acaba25a810176c81337af31ed1.nq.gz
    ├── 618707c317d86e4f541576851ac5aa5da763a2f3.nq.gz
    ├── 61df60c1088f0da4b67e8eec342889d47ddde6c6.nq.gz
    ├── 62a7b6a78ddbcec385155661c14ca1be50186d89.nq.gz
    ├── 63d1ff8468b8bef65f8691047ecd13d0a6c186b2.nq.gz
    ├── 6498a734b53c1cc49d2d6c60bf4cb06b1c3f16f2.nq.gz
    ├── 6575e5f6031fd94eb075bb92cf5e3d2e691f2395.nq.gz
    ├── 6593815fae5e11b3b9d24a1cf9644d31c895eaf4.nq.gz
    ├── 66a7e03f5369edce00b082244fc63a2de8990016.nq.gz
    ├── 66df9bb9cf4b411b540fcc2a24a020864aba0a97.nq.gz
    ├── 66f14085e555fb06235670e88f9aef4c8c15c86b.nq.gz
    ├── 6828c6a6f8648d9bccb85ab5f686ad9f73f0a164.nq.gz
    ├── 6a086f19829f3eb72534ef4daa099dad59096bcf.nq.gz
    ├── 6a7ae6986b6c95a2179af9a1ecfe34fda46bd2c0.nq.gz
    ├── 6a82bd4ea692bfb80eec0a05bb54ac11bf556a7e.nq.gz
    ├── 6ba4170274b636959e3d33eec70f918c1a5ddb10.nq.gz
    ├── 6c1a5f3cd767720bf962d8b5e8aacf7fbc6be475.nq.gz
    ├── 6c35660c33b8e0245cf83daac5d7ec7781cf62cf.nq.gz
    ├── 6d281a0b983f7ec462a6d4f8eb5c5b2017929d1f.nq.gz
    ├── 6d7625689fd3a34e39585b6c646652e455fd9b83.nq.gz
    ├── 6dcd662346077d9581ece48ed06aa87f53e0b956.nq.gz
    ├── 6ebe4412684ab4552c4a1d1004898fc03423ff48.nq.gz
    ├── 6f0f958d0f7bb6ba47e7daf10be03025c94c2e4a.nq.gz
    ├── 6f43b27fa47e8db3c88d4307411ff6966f297cad.nq.gz
    ├── 6f99dc1df1b5d3ae52634e574a9e30c36ae7e57f.nq.gz
    ├── 6fdde15b5c1308c13a8520921a7db36b78f00874.nq.gz
    ├── 6fec4d242a5922b313ba13aa6afb5ec24b1740a1.nq.gz
    ├── 718f581d8b6fd74d2cff6e21f918a32ac27ba7c9.nq.gz
    ├── 71ec1e46e8e0082c79312307187a8c2f7edc4074.nq.gz
    ├── 724219a31954dc5ac3fc650791b20f00d2fd5510.nq.gz
    ├── 72d9632119180de4e379e7f522893792428bc859.nq.gz
    ├── 75b327d16b6fa9a1c8f8117226606f9fec74388f.nq.gz
    ├── 75e055294d859bd43c0d63d07aa576fd7b836fdf.nq.gz
    ├── 76b30e0d4c6a801b72c233a43854ee84df3220fa.nq.gz
    ├── 7745dbde42ee2ec5bea726344e7b3205f95701d4.nq.gz
    ├── 77f6d950d3db7ffad0f70f51b635d08ecffc05fc.nq.gz
    ├── 780e69c57bea7b94ab9615f56ebed90b03079c6e.nq.gz
    ├── 782f92d5f5ee3641fbc9ea9b6a3cbd7699ba5a43.nq.gz
    ├── 790a636642b90802ff3afe4d29661ae23d6f172c.nq.gz
    ├── 7a4014821107836d4a587c186f771029d6e7a0e7.nq.gz
    ├── 7a5328c8422086033732b291c59a5ca2f8b50982.nq.gz
    ├── 7a549c41558fe669f92233574fe36d545a0ede5b.nq.gz
    ├── 7aadde0bf628343c75085836c0c80e3cdf1f1a44.nq.gz
    ├── 7baf6befe77351553026d1b45705019984b832cb.nq.gz
    ├── 7c24b17c96e0aa068faf271c989bc2ab2c4af531.nq.gz
    ├── 7d22fc8cbfe21b33a77f0db1be5256d9b24ec85f.nq.gz
    └── 7d921954dda9b3cb94c0bf5670677afe816463a2.nq.gz

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

[twisted/mantissa](https://github.com/twisted/mantissa)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
