# Repolex Knowledge Graph of bytedance/gopkg

RDF knowledge graph data for [bytedance/gopkg](https://github.com/bytedance/gopkg), parsed by [repolex](https://repolex.ai).

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
lexq download bytedance/gopkg
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 165f9e47565258dbf687d8153427a5e1ed3e6b61
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 165f9e47565258dbf687d8153427a5e1ed3e6b61.nq.gz
│   └── repolex
│       └── 165f9e47565258dbf687d8153427a5e1ed3e6b61
│           └── chunk-001.nq.gz
├── blob
│   ├── 00cc58dd87a9f0edceb3ab995df14d3ff789f4f0.nq.gz
│   ├── 016d063946c7e5ededc32532d347175f56d90b78.nq.gz
│   ├── 021bee776feb0b27ac0f5eefeb804fc7fe3d5e7e.nq.gz
│   ├── 0310b329f317158b9b552d4410355ac4ed9de8ea.nq.gz
│   ├── 0577c36f72959a52b441e66ca1b2247e1d1e4a57.nq.gz
│   ├── 07cf9d2e40dc738fb4e84f3e6b0fac3fd54c91dd.nq.gz
│   ├── 09fc25ac58d191f70eb50223d50f057c8cb2253c.nq.gz
│   ├── 0a5bd767902f3c7edd43cc3d731316fcdffc95b9.nq.gz
│   ├── 0a8b46effa0599925d4d119ce651d7dea3cebf89.nq.gz
│   ├── 0c8ce00b12d1d74e1c4fefe671989daa6f6675c3.nq.gz
│   ├── 0fe4e6294475c29a9d1fef0d1345ccaab322ebe6.nq.gz
│   ├── 12a90f2d1d557cf53b65b0c7b4a706afa91917d5.nq.gz
│   ├── 14334eda36bd5086dfecca586ac9af8de7cbd757.nq.gz
│   ├── 169d65ea25dd506e27a3aed24061d22ea25e9f3d.nq.gz
│   ├── 1982d6c1b27d315accec933165d1f6eda84a2c9f.nq.gz
│   ├── 19eb67c16068bbb5e5335c19321b0333d55d851c.nq.gz
│   ├── 1aa9e5d139adfa7ae3c195e719f01a185da65f5c.nq.gz
│   ├── 1ac6ef186866a7620cee4f2fb0164058d38eb7de.nq.gz
│   ├── 1b32144455b404eeaa77400011bc4aa1a99c977c.nq.gz
│   ├── 1c0f26ce4b3f4ab16c6adfe68583ba2604168e07.nq.gz
│   ├── 1cae3358d48bfc122b331522ebd07bab0de036d1.nq.gz
│   ├── 1cfc9de4713299fc642546695c490ce69479dbf2.nq.gz
│   ├── 1e1b3f2d44b498a744565cf7e89e5243b97e491b.nq.gz
│   ├── 1f095c2a724ea657566cba26d02b920cb0ba89e3.nq.gz
│   ├── 20cd96833ba1db5de0c278b03b74df7c13a91932.nq.gz
│   ├── 216c810025fe3b3131ebcd7fc455f59d93700378.nq.gz
│   ├── 23711260b4e042a0c9d98d768208382f09d84e2b.nq.gz
│   ├── 244ff0d1d893a73a53c5cf498b1e9eb5f84180e6.nq.gz
│   ├── 2537fa5e8b9c9786640f5fa13d0da48014220488.nq.gz
│   ├── 25c4fab4e689c0b042ea16a59e1b39ef7917cb96.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 265fbd3ea57d05950f78f98e9758489ff0f8affd.nq.gz
│   ├── 26ee43e47c8cc6739cce4989e3259835347f3467.nq.gz
│   ├── 276cc3f5924142c26c01dcadda5cc7ae1722a7a4.nq.gz
│   ├── 29bfdc3c1072aa1911cd197f939f755cf0ee2498.nq.gz
│   ├── 2a5dc4ea5f8dbb978fac23ceaddf81ef48290dc7.nq.gz
│   ├── 2acb430dca2b918e37d5f5a695b28d5230441eb0.nq.gz
│   ├── 333540d4c2621f0bdbcc9c60e7b02135e99b7af6.nq.gz
│   ├── 368a5283ce86f35c848db22646c0b5ea883529e3.nq.gz
│   ├── 36c8e3a892d1f54903ad971fe8dee9895d18bbf8.nq.gz
│   ├── 38c2aa89ff63edf208de0fdcf7ad03e80cd7963c.nq.gz
│   ├── 3a211240fefe97365657003274f705998f012194.nq.gz
│   ├── 3b0bbd661b0a3fb7a176a0dc0d7c7771e826479e.nq.gz
│   ├── 3bef91b6aba67bd2639e20e4cb74b96798990016.nq.gz
│   ├── 3d17272fbef146c8f81f35bb84a707adb3778951.nq.gz
│   ├── 3d90240c70dcd0151113284bef057e4080824c78.nq.gz
│   ├── 4061e10f439467534dbcbd38eb67b526fd2c1ffd.nq.gz
│   ├── 40edb448dc36c317ad9430a4debd09513ea62a5a.nq.gz
│   ├── 41a4862f0166bd72d14f688e059378c91a835920.nq.gz
│   ├── 43b7b0be6ed7033ff920ec86ed5c643244b95b3f.nq.gz
│   ├── 446f7e007e332c476f0218ce17be72ec0258fbed.nq.gz
│   ├── 454d603b15dd5bbb15e8d9173c2544f964f3121c.nq.gz
│   ├── 4556af4cd17b87d6e9019739ddacdbe62c64fa68.nq.gz
│   ├── 45a9d6d141faf54f4cf07a9019571fff21e7966c.nq.gz
│   ├── 45b962429b00321ac523e764c02cf91818449c67.nq.gz
│   ├── 46bec2988a24c130ad72fa23e922260457c8bc34.nq.gz
│   ├── 478e825e656a79371ca2f31923763d7a4e6bc699.nq.gz
│   ├── 47eeebc0c749e5c66258bd6290a40ad15ec475ef.nq.gz
│   ├── 48dde0388ac2580afcaa01a09f019f851adf23cc.nq.gz
│   ├── 4a6f70679af0eddc1e16b46bca5272ecdb64dbd2.nq.gz
│   ├── 4cd035f1d85ae3e6d5229e24d910ccced27eb91c.nq.gz
│   ├── 4f0bb503b46af3f959fc18d4173754947e8fb524.nq.gz
│   ├── 4fa9d5b0f2865ecceb4844185da0bf5cecb7f068.nq.gz
│   ├── 504fe4dfb34b5a1e310f80152ea4f68ef8df9dd1.nq.gz
│   ├── 5118958b55ac628b34cddfedf17851087205d65e.nq.gz
│   ├── 527a8a3213ceccc5dd92019a2417f51666c270bc.nq.gz
│   ├── 54f5023d1ae1e2752d32bb2584fe54ddd8de3078.nq.gz
│   ├── 5853c7d0d4169fc33cadc72ebeabae3d6a5e8280.nq.gz
│   ├── 58753a61096ce0b28daecc796eb774525148ac38.nq.gz
│   ├── 5c9c4d5bdf94e3d1a608a2ff092abdf60926bd37.nq.gz
│   ├── 5d0b4dcec502d623193bb60a03e24dd3480eec7f.nq.gz
│   ├── 5dab0e52d6c71ea35de9d5e66429e17e8628cf35.nq.gz
│   ├── 5dbaebc2025c1d6baf027a38ce433287a9e6482d.nq.gz
│   ├── 60ca74fdc945930e0fda8b64041bc19782166540.nq.gz
│   ├── 616c6b8f3383033bc30130cf72f657cb818350ad.nq.gz
│   ├── 61d43751e2cad68c3da094a5cbfb83d77e5338cb.nq.gz
│   ├── 626af621ecd582e976795fc250a3f451eb54d52e.nq.gz
│   ├── 62d7b19b7cd517af55f52798144c40c32bcd6263.nq.gz
│   ├── 62e979bc2aa13c0a49a210fae88ec6ab0482e0b8.nq.gz
│   ├── 6383f0ebf3e8a7291fb84fb26396add2b5213234.nq.gz
│   ├── 665b984b7bd1f6d77103c288924ce3459934c3cd.nq.gz
│   ├── 6694c9003e99141879d50ceebac23591125e0ba0.nq.gz
│   ├── 66d000b81730b20684917963270e20a842602724.nq.gz
│   ├── 6b59d78461f61b1cf67ce12e0c9131880975a78f.nq.gz
│   ├── 6d81bec92695ea82321e21fd105f00c9f7cca496.nq.gz
│   ├── 6f391890f594a9c55baa5fe632a0be3e6af8f27e.nq.gz
│   ├── 6ff810de9e5f87bd90af5525c1880d44da05357e.nq.gz
│   ├── 75069a569fbe14128e3e42ad24696adb6f3d5b12.nq.gz
│   ├── 7624ca3810d2780ba1cdbbfc4080ee8408d84b58.nq.gz
│   ├── 775ceabbeeffbdf9228a75f50421460f86eeb619.nq.gz
│   ├── 7794f85db018a4bf36a6911a0fc87c71a65ae049.nq.gz
│   ├── 792a5eb4c1a6e9f50c3ba32067e6fbcba25e0897.nq.gz
│   ├── 79897ece17e860e2e25ecdf297f1bed21cf3e534.nq.gz
│   ├── 7acb70ec5d3aa41c7102376a02b4f81bd2facee8.nq.gz
│   ├── 8064459cb268553d4b892f2f57639e282d7cde0c.nq.gz
│   ├── 818b68de20475a34aff016325f7d5e31973781e3.nq.gz
│   ├── 8281cf873861b1c9cf886a1eed1ecf6a793bab90.nq.gz
│   ├── 85e048c1fad6712fb9fff2668a1beee7b7014179.nq.gz
│   ├── 8645df16194814ee436cdc368e10d1e790142bf0.nq.gz
│   ├── 87a21696c32490830202e583c1414bc18ab9e0e1.nq.gz
│   ├── 893b572e7e6b260e8e4604efd176c6c8836c435b.nq.gz
│   ├── 8a10e252c76b501147959096ae0070083b821f0e.nq.gz
│   ├── 8a455f69fa2568518250f2ba7765992f196d29d7.nq.gz
│   ├── 8a81df851701d797116008c10f6a7ed9c05c33e4.nq.gz
│   ├── 8dec340b7ca3b3713ad5551417b72da9abbce34c.nq.gz
│   ├── 8e99a4999ee1265ea0724567febbd7fcdf789e72.nq.gz
│   ├── 8eb7140f83028820d7ea76363ec28a6ae333018b.nq.gz
│   ├── 8fea275d537ec4731673bb3d59747dcaf1d011ea.nq.gz
│   ├── 901bf2436feec1513e4dff44dcb1da491350dc17.nq.gz
│   ├── 904d723fd53d4ce314c63344f899d2f9aef90008.nq.gz
│   ├── 95626fee64cea2bb31630bbbd5f6aa419be5aff9.nq.gz
│   ├── 971c0eadb260dc8544b9b9101c5ce757e9312504.nq.gz
│   ├── 9822c0589ad9352ecf256c6b9347e97082ce3b24.nq.gz
│   ├── 9935b230740ec067db25b28667b9aee537eae9db.nq.gz
│   ├── 9b3ad90234b7a92a80c31efb7d56378ed29d33ed.nq.gz
│   ├── 9b653780329d0f7276d77c64ee117c94521e3f37.nq.gz
│   ├── 9cc94c6c1678ec38d0df1032b1da77a4dd0892b7.nq.gz
│   ├── 9d218d4f1dc388c18a54090320573c9e2c331e92.nq.gz
│   ├── 9f30ccc77df1a9fdaa915cca6f5ee5449dd06c59.nq.gz
│   ├── a23f35a11a66d3058fc9eaba679d70a6a24941f7.nq.gz
│   ├── a30d7350686c0d826acd2262b2488e8dbfadb3e6.nq.gz
│   ├── a380c309c35c756b773060ad30480e495e695cc3.nq.gz
│   ├── a414104fd328e26f3d34221113e4427269a382af.nq.gz
│   ├── a4c2d9f53c77d86aa579c94e7c828b1b6559edd2.nq.gz
│   ├── a657841d36f36c8ef347705f51e50967e70089d1.nq.gz
│   ├── a69fcd99e5461d13e94df8239ae993a6c3d01d92.nq.gz
│   ├── aaddf1754739bac7d517fb55f755f4efa612fdf9.nq.gz
│   ├── aaec5873fd7591b912daeb4ce6c92763f9ef7460.nq.gz
│   ├── abd67fda24889767294cb21f70f0ab84a783b775.nq.gz
│   ├── ac1c026874415b294549820c70cb29416b8c5a53.nq.gz
│   ├── b0bd703abc6f6205f4b199a3c7df5452c47e820d.nq.gz
│   ├── b1fa2595cf620c089813d823e0587d0af3fc1d75.nq.gz
│   ├── b2e3932e841f4640e17c583abacbb2a15511c1d3.nq.gz
│   ├── b5627c54e0866adfcb5bb0970fd5055e46114774.nq.gz
│   ├── b6475908754d8cf4390d0d94e5ac80ab18b9b0e7.nq.gz
│   ├── b7b2b28632531f318e1190ee550d121619407009.nq.gz
│   ├── bab1fffb852464bf2dd8b67c9eff5dca22a33935.nq.gz
│   ├── bcc8c4dd629a697a57e5610ba92b7a1725e4e32d.nq.gz
│   ├── bd439f1d737e6d81e0c5f8961ba0753cb1da38b6.nq.gz
│   ├── bd595f17f3ba6cd52586c486a2650b0f0b77a3ab.nq.gz
│   ├── bd6c3f14b8d346d2d387fbd5609e3fd6b096e930.nq.gz
│   ├── be928655ca321d0c3014a3f08ba371b208a61354.nq.gz
│   ├── c0704eb610bcec92540ff6a7e07e594f8cbb132a.nq.gz
│   ├── c12c7926515b4f745e937cbe79163952955d7720.nq.gz
│   ├── c1ceb87782778ec0a82b1dc02fcfc6f4a2401914.nq.gz
│   ├── c31a03d8864dde8f50997ac96c51c250ab513d16.nq.gz
│   ├── c3fa96c2473234b13496d012a8dfd5de6635138e.nq.gz
│   ├── c46569b7f27de922fa14a8ba4eb5d92a0a13d9a4.nq.gz
│   ├── c6a01a11dee4847fd990384d465ea076d1abb82e.nq.gz
│   ├── c7b4f206afd8cf46c53b18dcc3c13ac63b5e77cc.nq.gz
│   ├── c7ccab233dc188af156b9fdb266748a9ba7b2606.nq.gz
│   ├── c7d267fd08079b2a85d97f7e7dfb19ea523ae71a.nq.gz
│   ├── c7fdf23f3a48116d7f718c2d04061429c938251f.nq.gz
│   ├── c924924502f9152a6a177ff90cabb080c2432ea4.nq.gz
│   ├── caf21212dd8b7e59137b1563f3e628ccb9bcb381.nq.gz
│   ├── cb95b2cbc5f1b03343881fbde2217cbf0784691c.nq.gz
│   ├── cbfffa7706cfd11efe1817738e4bea4f112047d3.nq.gz
│   ├── ce4cbc596fff0bebdb42ef1b43cb2d1452a39972.nq.gz
│   ├── ced55a12c16d673f9d7fe07677dc76ea1fcc8839.nq.gz
│   ├── d1890b4dbe7abc0fcf15873befcb3131b1aea65a.nq.gz
│   ├── d2743f41551772932912c2be201cc5cd0b70baff.nq.gz
│   ├── d3b95173ba68d47b08cfc3358e27c4518e8b63b4.nq.gz
│   ├── d4b769056f349592d9141d00d284f5c9b7ec5f6a.nq.gz
│   ├── d539b3b2f4b1faf6a4344e6826102a7e893e7e5d.nq.gz
│   ├── d572e090b274afcc6fb82875d546492728a2b91b.nq.gz
│   ├── d580c80156a0c5fd0ee0b3f1074b52f7a67a4a9f.nq.gz
│   ├── d9b32f71006a8590023b1f712bef67cb8d26f7f1.nq.gz
│   ├── da3b24e233ab9ab34adec7efa53a473c231a202a.nq.gz
│   ├── dd8698ae5b42f2bfc337c3a057d3f7fee9c9de16.nq.gz
│   ├── ddf03e6d5270c008bed189eb5eb006f18e9efa1d.nq.gz
│   ├── df0a2b06b70df324eb7cbc35bc1a33c84677a8d2.nq.gz
│   ├── df5815054428d73b401af20ced539ff4f30b71ab.nq.gz
│   ├── e0a7ce7d33cdfc7f5633628a53f184f946bed22e.nq.gz
│   ├── e23c684fc5e33834a279b92b70f09f36cdbbbee3.nq.gz
│   ├── e312c683f9cfe3b77c3ea7e270b41ef42420cffb.nq.gz
│   ├── e3d24e6882765606b2fd3b544e915aec3fff35e4.nq.gz
│   ├── e47eb9005c756e6cd5b8de5274e886c344168165.nq.gz
│   ├── e52fe796effb749d5dfc549cd03bd8e2ff7e8ceb.nq.gz
│   ├── e635d6ed18278cba17b47f4d412f3a66ff239b53.nq.gz
│   ├── eb6d1c32aac1f1c07ca0c09b851d8ae264dbcbd8.nq.gz
│   ├── ed9e29da3aa5c40ae7dc2cee55d0c0b4adaad592.nq.gz
│   ├── ee91c54e646dd243beb283bedd8941e8bcd11e7e.nq.gz
│   ├── ef98d70d02e09e32c0011c8201ff6af361513efc.nq.gz
│   ├── f54f99feb6018082fe3aa1ca64c9dfb51a0025fa.nq.gz
│   ├── f588f56aa5af047e779a7db9bc7aca4f279c61ee.nq.gz
│   ├── f6a0a890065d7cb829d5f40397d3d01f78584346.nq.gz
│   ├── f7e49dc469c0a2fe1061777a8fdcdb69c2bde7ff.nq.gz
│   └── ff80a876a84961df822902f3904da204b11c22d5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 165f9e47565258dbf687d8153427a5e1ed3e6b61.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 197 files
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

[bytedance/gopkg](https://github.com/bytedance/gopkg)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
