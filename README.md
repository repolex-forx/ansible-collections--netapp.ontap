# Repolex Knowledge Graph of ansible-collections/netapp.ontap

RDF knowledge graph data for [ansible-collections/netapp.ontap](https://github.com/ansible-collections/netapp.ontap), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/netapp.ontap
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c64438a27ba7caa80b8309b65c0189e90dac9b68
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c64438a27ba7caa80b8309b65c0189e90dac9b68
│           └── chunk-001.nq.gz
└── blob
    ├── 00445a252f8e5541184cadca43dff0b9bbe8dea1.nq.gz
    ├── 01767c396b5cf0b93e8007b8351026d194a641a6.nq.gz
    ├── 025d95343d89115dad2aab5afdeaba973f5f81cd.nq.gz
    ├── 027c5319958690a39cd802f19f81c0f3bc0963d5.nq.gz
    ├── 02bcbd136b8c23aa42a737465d02a54f651d5ccb.nq.gz
    ├── 041b2d1002da68712bbc7f4a95f908a763aec282.nq.gz
    ├── 04930f26ac4f1b76e7d599774900be0654ce7f73.nq.gz
    ├── 04ebeae3b8ab2ab59e0abcac5a80f7acadb5ec53.nq.gz
    ├── 053c6f3483dcd305b4983773913f7aaa2dc909e7.nq.gz
    ├── 05559d5f8b68e5d153fe6ed42bd75074eab2e7a8.nq.gz
    ├── 0630bdff76a40d1cd9e62986b6b2b125b4a1cb3b.nq.gz
    ├── 066452600a37a4a3f4d34bdef79dbd4d99bb58c9.nq.gz
    ├── 06f54af7fb2746097a2f4a8dc3d9b070058b25e4.nq.gz
    ├── 070c08998507f15fcc91e7f1800f830439e8b158.nq.gz
    ├── 071cccc345382aadc1ad246c2f8ada34fa8142d1.nq.gz
    ├── 0784cbe9bc7bf2d72f2bfaea51f24421550b02d6.nq.gz
    ├── 080dbab613aa6143cec83f3b8099e168e1d26590.nq.gz
    ├── 08d39152ddc49ba30a45b9071868bb3ea8a6b8fe.nq.gz
    ├── 096314f004b8c9c57ac7f54fd60c369a3986413e.nq.gz
    ├── 09fda1ddb6c1ae742fe1bb0bdc2424f23f558dde.nq.gz
    ├── 0ac8dcdc15301707f01c8031fa5214dcf677198c.nq.gz
    ├── 0ae991ca57e23098c77df654c389b3026503d4a5.nq.gz
    ├── 0b39c551625374c1aa73a7a5a085245fd2954350.nq.gz
    ├── 0b8f44440405c547e095a1c0c0f40ba3f3eaa58e.nq.gz
    ├── 0bb42db769083888401ac6d6867597cdf7a634ef.nq.gz
    ├── 0bf7f7caa66c4a431b93501d20bfdbf0a0ce9ea8.nq.gz
    ├── 0c028bfcdbb78c3e4b8aa9412964f7ac60d9f9bb.nq.gz
    ├── 0c11019a29b662ca615db1932503867ce99b2431.nq.gz
    ├── 0c1a77e7f6e9d9539e7eb602e02f890f3e0c358a.nq.gz
    ├── 0c95a1cad627b79acecfe771909722156a0c322d.nq.gz
    ├── 0d3321af09140a6c04ba27a75b307b3b7da06324.nq.gz
    ├── 0d6434ee603da720e38894c3752d6a7966ae8ad2.nq.gz
    ├── 0daaf93bf4a6e03d100a94f7ab96b0c941ae4412.nq.gz
    ├── 0e1a68713bb040666ef6b3fb71156cd6375d9646.nq.gz
    ├── 0f092f5ce49f0726e36c87b650c3309d774927ee.nq.gz
    ├── 0f5c24e7de807f65b5b1bd508055e6e2cea23e5a.nq.gz
    ├── 0f7460f24adfb284612fee214ca3e3c39e67c7e8.nq.gz
    ├── 0fa7301d92cae8be8501dfac42ea0acbb3e89f77.nq.gz
    ├── 0fe4be71b5d90fa271fae532b61ce1864a0b5f32.nq.gz
    ├── 10e5e9d982d8044c700652ae639c99834b0fe438.nq.gz
    ├── 111aa9805375f4faa021880a22d8557ccb28da96.nq.gz
    ├── 1197300a180d642ebdba79d268ce1af6e3437cba.nq.gz
    ├── 12d109c2c89fe925e41b5ac762c0090c469e5eb7.nq.gz
    ├── 131195b57f630db2e769444cadb66cbab7806258.nq.gz
    ├── 134428c20e1f5cfdf393bf5d5b2b2669a0d853e2.nq.gz
    ├── 137b88d6d3dd82797ca8695cc6cdf2a03a177796.nq.gz
    ├── 13853a9266b62964ff08a6087175d4b3b8cb4ae0.nq.gz
    ├── 138f3409f9b97bf483fd8e294e9c5c64dcc4c8b6.nq.gz
    ├── 13a75f2291edf87dc76103f64493e4e37da3bca8.nq.gz
    ├── 1400ec8d0bfbe2ebc1aff288fd02713c9845844a.nq.gz
    ├── 140a8e0f18055ccec2bc6aec341e1ece8032bbde.nq.gz
    ├── 144ebac87dda4fcf090f92b308f7c00bb41c13f4.nq.gz
    ├── 1520c17711713d0672d80897bcc1870a648262af.nq.gz
    ├── 15a5fabb4f06fb0d6248695c43b3228b080d5b95.nq.gz
    ├── 16982036b19ae529c07ab9c54fccb09b2bfad8f0.nq.gz
    ├── 18064f1d571d3a26cb430e5f3ccf6da64ea3eedd.nq.gz
    ├── 183b20e0c2bc2b2a5d7ca9b7cea0b53887940fd1.nq.gz
    ├── 18c10fa180fbb585032c9a08f3ca014b3c441b59.nq.gz
    ├── 192ecdca8027fc9ed1ade7c30debe63200b8a01f.nq.gz
    ├── 194a334f791ae142cc0f0e1ae90d5026a5726f5e.nq.gz
    ├── 19e4840d07e3409e5189cbae26a4c26cf46a9a01.nq.gz
    ├── 19f3d6c67d44c0263f1930d53426e374236f054a.nq.gz
    ├── 1a8a90c419d05a8437e015f9e1f1b6ebf91d62a8.nq.gz
    ├── 1ad997f41cc461302e7828125ad9ce0ba793dc52.nq.gz
    ├── 1b271b79ee5ebf4a62181b17f650d294ed7030a0.nq.gz
    ├── 1b53688ad6afa04ba7042f969699220a5cb01e62.nq.gz
    ├── 1bc629077b44de677e09c45d95c6521ce967b9e0.nq.gz
    ├── 1d409bc8069ddf1651b073721bf20167d02b2cbf.nq.gz
    ├── 1ec6e3cf3a0660f76dd111bde3ab769c15b800f7.nq.gz
    ├── 1fdcde111d81d390bc74178fd8b458d5acb41556.nq.gz
    ├── 20300a9c86e633ff97d64bf146f62a2bcd1535ad.nq.gz
    ├── 2117518ada972ced3fae0c59929d8c989176560a.nq.gz
    ├── 2166f8b0c9d15be973b117a61270f33b9736219b.nq.gz
    ├── 21dffcd1c1548b71f4610ec8317671009c8e11cd.nq.gz
    ├── 2292235292f4624237c463944fb974b69a1e4984.nq.gz
    ├── 2332c4b13ff86ca5c1180bb8c0f25f79a94210d6.nq.gz
    ├── 234599fa8fdc81ff4d83fde95a8104ef16d2b08e.nq.gz
    ├── 2497f420bc1a4478cf4644717e855ebc4eef1e4b.nq.gz
    ├── 257bac252964a2a7fb4d82dd3544b91ce63a4e97.nq.gz
    ├── 25ea26dd0ad98a476d6389bac92bdd4ac0d8aaac.nq.gz
    ├── 2609d54e89bb4e30ea7188ec0889e39287ebd929.nq.gz
    ├── 2640402ada20fa248e40d02155cee2a9fbb25b56.nq.gz
    ├── 265c71d7675b5bd68125bbceb096425974582714.nq.gz
    ├── 26a6b1337d9dd27f83409938ff6492b7a2c39086.nq.gz
    ├── 26eba0a51cc81a0f87f2e61d0f85b9656847f2ce.nq.gz
    ├── 29e784a3f310c34999f976f28639874f2dd69b7a.nq.gz
    ├── 2a6c5ebc03f48ec7b76735fbfc9dd77f893b2856.nq.gz
    ├── 2a89f34ddc9f6a897ebe10a8669faa898649bab2.nq.gz
    ├── 2b39ba2b755b54c833181d134a3d8db1dfb02777.nq.gz
    ├── 2b807e23cd71864a6358945595a17c72d5a5aa8d.nq.gz
    ├── 2be9f48c3c09961bed5afd33d1b6ac127487d792.nq.gz
    ├── 2bf0ad3c492a0ecf6fcc5b3cd67b286d66ae3ff3.nq.gz
    ├── 2bfafc3ce17e0f73b1f7d2126bed2c402fc9654a.nq.gz
    ├── 2c2659c10a2e5670da60240856d1f3e49a882e78.nq.gz
    ├── 2cdc97a59e1dc20b4a00fef5b6a8171000a9f3db.nq.gz
    ├── 2e08a1ca6b4c034564c04c0ed2ee9879a9ded674.nq.gz
    ├── 2e890604838ee000136aa43779062fb191f82797.nq.gz
    ├── 2e9b0068f9287fa790b68137b5c6fcf590d34bc8.nq.gz
    ├── 2f1694cd536ff284c913601a5a406b643d913cc1.nq.gz
    ├── 2ffb45bbbbc29c55b1bed7430f8ec13727d0352d.nq.gz
    ├── 3054047ca80f877dfc4b625afdf1f47b0ff86279.nq.gz
    ├── 30df815925c773387d899fa26b3aa0f36e419e08.nq.gz
    ├── 31174bb7d0d17972b0c9675e98949bcb198be87a.nq.gz
    ├── 315145bb4d376908e5ac62e866f1820baa2a09fb.nq.gz
    ├── 31d17f23686d4449f84860881ab96a8b37847a1c.nq.gz
    ├── 32fb0f8e5c6398126b4961481031be3f4ab5224e.nq.gz
    ├── 332fedcc92b30e9c61374805309e3180371e6b01.nq.gz
    ├── 3497206be4afbd9c510384776cd0dc0e066f8fb6.nq.gz
    ├── 356346b613d679d4409d5fbda8783d401ff8ae6b.nq.gz
    ├── 3599cd0123b03ae46d77f6bf98d73232cf27d1e5.nq.gz
    ├── 359a82ead80852af7d52db9d7ee099476383a9b5.nq.gz
    ├── 36a83a33eeda70550492ba7ccb6375652ea8f0c5.nq.gz
    ├── 371a387e3cd19b61f75bcadde68c57e1305f38f6.nq.gz
    ├── 37358f1f48f46c2a9993797bbf9755cccfdd8e98.nq.gz
    ├── 37e4e5a075a5316f43e82bc6a97e95e9e46ff770.nq.gz
    ├── 387813686ce18ceffcd379ad5803d8d1c8608f56.nq.gz
    ├── 38bc6ec96d3c1e6a3b78c8b04ddeabb32bdd202d.nq.gz
    ├── 38dd6ee16e2b9091945584e839cab286f7866258.nq.gz
    ├── 39d27ef1fb08624db7ac5be8c4fdadb0ed3a99cd.nq.gz
    ├── 3b40ed7dc6998d8298144b715f6da51639c73d62.nq.gz
    ├── 3c8533ff677bcfeae53be1b769760f3a2651f37d.nq.gz
    ├── 3c8fd16f420e6045c4d05815c41a9d9177ee9bbe.nq.gz
    ├── 3ced00bca44fde429977f522a235d1a14c013294.nq.gz
    ├── 3d25f8ba24b358288b39677f60000d676947c72c.nq.gz
    ├── 3d523d7ca9f81309414ecbd7422ecb84d352e940.nq.gz
    ├── 3d7270d769c0be5c2e4a0177b4a8f0205f35e28c.nq.gz
    ├── 3ddf4f341e50f5699f4b72e5fd1f0849520016fc.nq.gz
    ├── 3e721148c136f10dbecbb7982a6a6806735ffdc0.nq.gz
    ├── 3e7564507b69f7e4aa55f43193e89d13246c8a4d.nq.gz
    ├── 3ebd5b68ad21456c45180684bf9e2677b110e773.nq.gz
    ├── 3eeb6cac528a03608e02435bb0c18cea1fb325b5.nq.gz
    ├── 4048eb5c74844d8493b8bef85f51e235c69038e2.nq.gz
    ├── 40753c700d16159cea9d189db845f547268e83ef.nq.gz
    ├── 40c89c4185845fc4be0a1f729c45bcf802454834.nq.gz
    ├── 40dfa579858ac744f0e4544d8746d745d30be001.nq.gz
    ├── 41170240b74b8ba0cc3ec2d813bc283c334a92f2.nq.gz
    ├── 428b8d712f42454b6523b0811e5ad07edf75604d.nq.gz
    ├── 42d0a145c9dab2d19062cabbe0bc41ff8ae381b2.nq.gz
    ├── 43544606e8b86fb546052111b5cb2ced9a479840.nq.gz
    ├── 43bc92c5cc64b1078373a223e22525710ad1062e.nq.gz
    ├── 450127283ce6b92f71e3e97b04e3feebb69d5154.nq.gz
    ├── 4584c641125dbe61e489716c5f4069565d857f9b.nq.gz
    ├── 466fb8373afbaa5f0912540ad19836ed48666bf3.nq.gz
    ├── 487e2f486943061a7141f771390dce78c38be6bc.nq.gz
    ├── 494a548912a8a173df0800931e914498351b4616.nq.gz
    ├── 4a5a485e998d486b35c8bf0ee2529fcad50075a9.nq.gz
    ├── 4af90c520344b0d7730c3b850e6e9d44ce1c356a.nq.gz
    ├── 4b187496dba29aaf99e34e7c9c3499f53efa77aa.nq.gz
    ├── 4b68bf0c8e3e66ea649ed293ca3bcf5ee0242660.nq.gz
    ├── 4b86b3351c8326b91883b78e4443f4fa996cdfa4.nq.gz
    ├── 4c570f8d85f3d620f37ebe522c0513934ce5997d.nq.gz
    ├── 4c890155f7e1427d78dbd1092c334fc1166413a9.nq.gz
    ├── 4d51b8f146d32447fbd339eb3106caf6317fa26e.nq.gz
    ├── 4d929c975a1be17cbfada52b7bd6bcbd31e06186.nq.gz
    ├── 4e5d8fd491298117a59463febc5db846c1cfbe31.nq.gz
    ├── 4ff2b3dfe844810f6f0ed76848c276dc88031901.nq.gz
    ├── 5078b7d062a5462737dfa51df3ef2d920fc897d6.nq.gz
    ├── 508b46b1b2b6718b22b38b693f72c2149d5f9b45.nq.gz
    ├── 510084f20b503a89c8940b9ba00f48a2f8c9d309.nq.gz
    ├── 510f04a9e77512293bcf12578b888d54df8d26bf.nq.gz
    ├── 516c5378bbc924e94eea9a03f4143a3e63f88320.nq.gz
    ├── 51fbe972b2591bb82d05aa6a3d46d62f4a169744.nq.gz
    ├── 526d3f2f4781bea7e2c1b57347340d6d56af7793.nq.gz
    ├── 530dd36d879af95348fe306b461c50e1489966ca.nq.gz
    ├── 55653bd52922893a14b7d0fcf67c5f3592a30ac2.nq.gz
    ├── 55802f3712ff5c3b6ca98c8f0d3a7b12763ac679.nq.gz
    ├── 55a0c9029a8e01fa6293dc586366a158209ea483.nq.gz
    ├── 55b3f42df790e14f619f88187c055f2b69a9120e.nq.gz
    ├── 55d25d22dcf52381fb009eccebb53d5c9cdf309a.nq.gz
    ├── 5683b1aadaca608d2f1663f976b12822610c4975.nq.gz
    ├── 56ebfb2a371df56a7c0242f96b589c3214a4637c.nq.gz
    ├── 572117e20a2c096cb388db619095393c6882e384.nq.gz
    ├── 573c4a26415609f0399ffaa5652ca7b000a22f95.nq.gz
    ├── 578d46420922caa4f6e3f59281509ab41f5654f6.nq.gz
    ├── 585db823e98f86895e28b51710093c3be28d0847.nq.gz
    ├── 58bbcb115c6135f084a0c88c366f6d8df18fcc69.nq.gz
    ├── 58d8290f063b08af248c2efa9ad88889d6e3bba2.nq.gz
    ├── 59718edc48ae7dbe6935ff4ff9d588f0ba46d315.nq.gz
    ├── 59e04b3b3d3d1ae914574784b43fbf2acce3464a.nq.gz
    ├── 5a4950b6be8a7ed0edaaa2378fad0cc9014dd720.nq.gz
    ├── 5a5d61029ac886b2d11a35e97fee79e742f91442.nq.gz
    ├── 5aa40c50286ee2eb050d744f667a4f712ff176ba.nq.gz
    ├── 5aeb23518f0e6e054894476693940dabadd85b62.nq.gz
    ├── 5b6c3aec85c8dda651b8c6cb53c5b810c482060c.nq.gz
    ├── 5c9d1e4d47f11af65e152910bf71d05d2a063c78.nq.gz
    ├── 5cb2b05435bff64ecb146f7fe35f7fe1300d1c8f.nq.gz
    ├── 5d23ecc9aafecd9e46e53d0fe8ae6f0bc1915085.nq.gz
    ├── 5d381d8527aaf93ace89c11bdb43b3930bbc13d9.nq.gz
    ├── 5e5b45e039d51cdfa25758ad550c3331b40c905a.nq.gz
    ├── 5edb951a4a2077ea7efe57e171671708015a6cd9.nq.gz
    ├── 5ee561336b0919ac65dc10a57cd75609195e97d3.nq.gz
    ├── 5f62ec2e49c5db12a4bc37cb7a0e468608f679ed.nq.gz
    ├── 6015df039ea31ac39e7f90435a0da5a0a8f663bb.nq.gz
    ├── 6018ae2d7489d6480336571344516c29c0ffc02a.nq.gz
    ├── 614f8da769113be278df51589303ffd50b6099a9.nq.gz
    ├── 615bf35a7cea83172fda5c9c0840b63d7beb8773.nq.gz
    ├── 61bea7b1de2f45c34b116715d5e15106cc0c34e3.nq.gz
    └── 623613c8e5eb344df6ba7eecb20a78e382ae5a61.nq.gz

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

[ansible-collections/netapp.ontap](https://github.com/ansible-collections/netapp.ontap)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
