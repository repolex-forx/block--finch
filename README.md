# Repolex Knowledge Graph of block/finch

RDF knowledge graph data for [block/finch](https://github.com/block/finch), parsed by [repolex](https://repolex.ai).

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
rlex download block/finch
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3f4bb5c06f497ebf415ad41e80eb65f0202f6bfc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3f4bb5c06f497ebf415ad41e80eb65f0202f6bfc
│           └── chunk-001.nq.gz
└── blob
    ├── 00e77bd79be44872c0b29256b03799c2fb00c10d.nq.gz
    ├── 030904ec2404314b406db6a7b343cc27f85030f9.nq.gz
    ├── 041131aa2f2f27938f78e6ea49a559f2cb02fd07.nq.gz
    ├── 059b978665ac49759a581a6645b327d16a9cd187.nq.gz
    ├── 05f5bd236e9bf556f59c1f748bdaa26d054414ed.nq.gz
    ├── 063976bae8d61d08b30505246510ab32d8861158.nq.gz
    ├── 06ad888b4d8deb0ea9390e983f6fa54f269e2a0d.nq.gz
    ├── 081c4d61da27a1b3d2a3f09a5d42e2b1dc8e2411.nq.gz
    ├── 0acaaff03d4bb7606de02a827aeee338e5a86910.nq.gz
    ├── 0ae390d74c9f665cf8b1e5ea5483395da7513444.nq.gz
    ├── 0be298693615795556d9a28695128873ff72facf.nq.gz
    ├── 0c3ab4e4b8e6cf0a66587c95277465808a53a3fd.nq.gz
    ├── 0d70f57727bb56c64dfc63ba388b22b0ab7f8f60.nq.gz
    ├── 0d8b88da8283b0f29289da8b580933adf9e32ad8.nq.gz
    ├── 0df3de76b3e4a54c43c3683c757d1df2ce5722e7.nq.gz
    ├── 0e7da821eee0dd05a0a6f0b16c2c1345dc573a84.nq.gz
    ├── 0ec55f26700cbca22221371d54bd6d31301650bb.nq.gz
    ├── 0ed31968499070760570d02ab697cedea29b0ebc.nq.gz
    ├── 10c6696acb77f109c5980d387ecf6d28054ab005.nq.gz
    ├── 10c8ff15705a53529803bbe80583300653af34cf.nq.gz
    ├── 12bf8cfda478466137f367d0ad10df9b09dcb3d5.nq.gz
    ├── 132871c325f65773e848aaf295b340a83c608c42.nq.gz
    ├── 145ed9f7b5dd49124c0690788f8a32a5d8feb3b8.nq.gz
    ├── 15eb1a010f199228eaf11b730c3616b4d8ce1c58.nq.gz
    ├── 16a935e659301e3fde22fdb766ba260952f77573.nq.gz
    ├── 16f8295a1d6e22048e42d400199a0723655f4790.nq.gz
    ├── 17229744c77c302cc54d82b99da8a6225fef6e55.nq.gz
    ├── 17af8ca98d3c32107399fa33ae2934ee2846dc08.nq.gz
    ├── 1a14fb0a924ca67c35522277c2941aae037a15e8.nq.gz
    ├── 1ba81c131785d0a812e55b5c99ab7a13d07a4873.nq.gz
    ├── 1c041611b571fd2fa4e1c17a70bf5ff51850dd0f.nq.gz
    ├── 1c1c3ad9dba447a10f0274eb51b8c3093561ef0e.nq.gz
    ├── 1da6fbb5718e41ce71751befbe697f1d200849b1.nq.gz
    ├── 1df040799dc1e8751c02c774e01a7ef91fe67cae.nq.gz
    ├── 1e98ce6c203eb15015ef42df66fd2429f33e001b.nq.gz
    ├── 1ef86e2d3c2257811d2d07897c048950d2601708.nq.gz
    ├── 1f19a441fbb4eb6e4845a5faaab55e21a20d89bf.nq.gz
    ├── 205937f7fcc6a124f04d9b9ce521777adbbf1dd8.nq.gz
    ├── 2131341816861d6eb3a936bebdde36a2af5253d9.nq.gz
    ├── 215c143fd7805a5c2b222bd7892a1a2b09610020.nq.gz
    ├── 21f5812968c42392a3eaea9b0c6320870b6b8b38.nq.gz
    ├── 224cc74be1ad93a88852ebfd23400b5ccdea25ae.nq.gz
    ├── 24214da84719c76ac80b1f88772809d3af3dd903.nq.gz
    ├── 2432419f28936aff53ddfa2a732d027e6a6648fd.nq.gz
    ├── 249a28662218a7a17ad8bd1fe072169ecb666a49.nq.gz
    ├── 24cd0c5c83b1bf17d5c7f543c4ef0064c2bd66a8.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 264b82a80a4b931e8ad213f239e456f3d51c8b09.nq.gz
    ├── 273204c8f8d7251b5cde9e0bf8c690d13949b122.nq.gz
    ├── 2771ecebe31516e8fc59f6bdef7d6fa551c5a184.nq.gz
    ├── 29657023adc09956249f6295746c8ce4469b50d3.nq.gz
    ├── 2a304c56f1890f908ac98c460deb14df12057eb2.nq.gz
    ├── 2a3700f440c020e5e823754060e386f3422cec17.nq.gz
    ├── 2c1012fdeeb8109ac11c7b08beecd2fed01061c9.nq.gz
    ├── 2cd06d2a34b40892da77dc735f32ccd36f7d1c53.nq.gz
    ├── 2ce4ac827c6f644a93037887e877a6fc9ce169b9.nq.gz
    ├── 2d0f47285cdf3951c6cc6a867806d9661af4c517.nq.gz
    ├── 2f24a9c2b305bf858af36997732b6ff00d86b6d3.nq.gz
    ├── 31b84829b42edae20d0148eeec0d922dad2108c4.nq.gz
    ├── 32428980f98ac7b0874d9fc042bc319ae1ffb0c9.nq.gz
    ├── 328d3ba62cbe51a9816f11113d4b908edf55cc14.nq.gz
    ├── 32f164fcd4b1aea649fbd11b48b6ca6341e3fec8.nq.gz
    ├── 33104e13b5aa0e843ff40bfe9b4fc748dba730d9.nq.gz
    ├── 34396bd80f1fce29dd00afeecb56cc6c1e3393e3.nq.gz
    ├── 348b80b5a51f77a0c96502c5f6f551849ff18935.nq.gz
    ├── 349c06dc609f896392fd5bc8b364d3bc3efc9330.nq.gz
    ├── 34b122025042748343df082b7a5c809ee726b232.nq.gz
    ├── 35b03acdedde66717ede44855a9eaa440a5f2263.nq.gz
    ├── 371b55432dcef34a76fdfe02db5bcefe66841b96.nq.gz
    ├── 37ec55dc4fcff7bf1789bd1b14fc8908d4d2f327.nq.gz
    ├── 3812eb46b8fb206606e8a499a59c33d22267b986.nq.gz
    ├── 395f28beac23c7b0f7f3a1e714bd8dac253dd3bc.nq.gz
    ├── 3a56ad24da49f25ca86543e29cd70c6d2b3e2e24.nq.gz
    ├── 3c005fafff7e2e171205f5a09afbf377789efc5d.nq.gz
    ├── 3c0683c7f027f3ac23537318aed3ef70580be9c6.nq.gz
    ├── 3d5e5b0848c26dad28628c05a046d8a1b5c9ef20.nq.gz
    ├── 3e8ea3f9ebddc29cdc634c59151437962452c7c1.nq.gz
    ├── 3f4bb063748877e99d5c2c91c878a834ac9dab2f.nq.gz
    ├── 4126f8e5e84dc831114663dd39fe67405388d809.nq.gz
    ├── 4292c4cb1e16f4d682d4e0acedc3ae0ecca4f31a.nq.gz
    ├── 438c1e4b8e1cee7a35ecdd2b04fb94a002143aac.nq.gz
    ├── 44129599351a73d3a74069cccceab2aab544ad17.nq.gz
    ├── 44b06a7b25f39ad5dd85f05729b51f8d68f685a0.nq.gz
    ├── 45b431fcf8929084c409328139aae2f779332f8c.nq.gz
    ├── 45cace38397c97733e404f3b60d06282eb81d4da.nq.gz
    ├── 45d90014ec600fdcd1bdfea3b3373acb542dd625.nq.gz
    ├── 4635f91f4491b22086ef4fa66d2e6c5cecd8f8f5.nq.gz
    ├── 495716681eaa96154bfe31f6d66e65d65401daa7.nq.gz
    ├── 4969e47588edc178114f44339d790ed60bf06038.nq.gz
    ├── 4a15596826fd4d8e5e9f158f2ec5a9a57f618a78.nq.gz
    ├── 4c98e78f7cf7e5e755791e9207e8e98efc35000e.nq.gz
    ├── 4caf171b8317c42828dbc70c74443d1ad180c4a8.nq.gz
    ├── 4cde3a77f944b8099ffe4265d7c1b9febc06770b.nq.gz
    ├── 4d719ded55c6ba8b817c5d6b03d9b635f1dc7f10.nq.gz
    ├── 4dbde8ee5e4d18af9cd0a37da463626c3cf02cb1.nq.gz
    ├── 4f3cfd2917bb461b3fdb7f0f0d1d195d22268b64.nq.gz
    ├── 4f52f4c77ea28abce97e0f8337fea3f11555a1d5.nq.gz
    ├── 506e7b4e115c5de7355f3d5bb782786793cca638.nq.gz
    ├── 5161813c47f1658aa139076455984ad0779f53b9.nq.gz
    ├── 516d607c66ee6359c995580445ae2ca6861c2555.nq.gz
    ├── 53a473ac42c1065447b6207294e1e93a95c217f6.nq.gz
    ├── 546cc1ba7002cc3d3c0ac7db743ccaac72c96e39.nq.gz
    ├── 55c73d9bb3d9370c2ccdc6b7b996a78cf0a25cf4.nq.gz
    ├── 57045040b6a09332eee952649b089ec57494473f.nq.gz
    ├── 592f6ba9054890908b5ce015b12523c2fd2f33aa.nq.gz
    ├── 5931794de4a2a485fa70099bf2659b145976d043.nq.gz
    ├── 598e286a938e8aa365562f3406cd087608f8c536.nq.gz
    ├── 5b4a40a3c9362944f7f94afb1cac00aed501989f.nq.gz
    ├── 5cec1c6e598b9fd8d54d8c9ad0f5e11ab8d36daf.nq.gz
    ├── 5cfafd1cb6f96bbd4a1c150e957b3171ef520a74.nq.gz
    ├── 5cfe61edf52bf90ba9a920cbf56f52aeebb6f6c3.nq.gz
    ├── 5e78b52bcbbda6617c5955efc280e1bd40a0254e.nq.gz
    ├── 5f65cc45f3ba9abd58ce058ef87dabf8e249fc9e.nq.gz
    ├── 5fe5bc9e708ffb7320804193d1693b7a4d899d65.nq.gz
    ├── 60bd355e49ac8b5383d57763e5931ccfcd1cf517.nq.gz
    ├── 62e7b0bc1f21e168766b79090030e3abd0fe3f89.nq.gz
    ├── 635078d0633b682e3ff87f9d8581d883f1f6a16e.nq.gz
    ├── 64aebb70cc60b73f1b8ed3951989ced388c1cb8a.nq.gz
    ├── 6504d6e8b8a02b23b63cc6ba6bbefc635d8e9889.nq.gz
    ├── 6578f7b11917be265230165de8ea47b389327f28.nq.gz
    ├── 66f9b6f76a2b04b56351d380ba781c8323ba7e4a.nq.gz
    ├── 67591f9836f30762503b94ad778036e8754c0c8c.nq.gz
    ├── 67691287645713f9b26b46168cf5248cfc4287d3.nq.gz
    ├── 67807b0bd4f867853271f5917fb3adf377f93f53.nq.gz
    ├── 680c13085076a2f6c5a7e695935ec3f21cddb65f.nq.gz
    ├── 69fe82cea4fb5202aa73fe33c4f6520912c4e37f.nq.gz
    ├── 6a0135d17f9ddf292644d407ff07a92bd15914d9.nq.gz
    ├── 6b1342c2f125825ee1967d00c5e863ba5e4597e4.nq.gz
    ├── 6ca4335ab5d6f367d98af289a4796c79c23328c8.nq.gz
    ├── 6d9cde5a67b7a1cb556dac61ea4c079ee5484d63.nq.gz
    ├── 6f43b594b6c1d863a0e3f93b001f8dd503316464.nq.gz
    ├── 70b1beca8fc01e7fbc4109e07e2a637b5bbfdb4a.nq.gz
    ├── 71dd8ed3051f7f9fcd94a4282f26de22beb00e66.nq.gz
    ├── 735f6948d63c8cc7f8233735bb9c8d843c83d804.nq.gz
    ├── 74238f70101b7d322a19d57040390b6aca97dc5c.nq.gz
    ├── 75344a1f98e37e2c631e178065854c3a81fb842f.nq.gz
    ├── 758baa9087d75e726d871445a923a3d4ba665ff5.nq.gz
    ├── 75cc260a53fafeb8e8c3e08b570c579f6b29e80e.nq.gz
    ├── 76975f2e97fce83617642351759891f6597a5bd0.nq.gz
    ├── 771f1af705f5cef5f578b3a1e7d8eff66f9b76b0.nq.gz
    ├── 78962467e4e1359258fa8402ce039818bf9489f2.nq.gz
    ├── 796cb17b55771e8282b4554a86f145a6193f39a5.nq.gz
    ├── 79b9c8502addd0a0f1feb5788780b46eb61c3499.nq.gz
    ├── 7a6aa9c68f902c22c5682f9b9ae4cd0741ea942c.nq.gz
    ├── 7c46406f7c3c7b2cd3efa37fc14d4f65443fcc9c.nq.gz
    ├── 7cb4034853ab035c4d3ec058da0def415dfe815c.nq.gz
    ├── 7d6474eb7a818f65e90d279931482368c75783e7.nq.gz
    ├── 7e02df963621a5e26d53d510f0b4992eebde1c60.nq.gz
    ├── 7f292d91184f257054ef77cc1cd3443db757c9cc.nq.gz
    ├── 82300e507a660a95f55038063729108e94a04059.nq.gz
    ├── 8268304030f98df902b70c9dbc63f312a76b80ab.nq.gz
    ├── 82702fcdcd9d210c6f2e52ec146fb9a936980aed.nq.gz
    ├── 82aeceac0e72aceb4d64d05aae5ff46873e2b603.nq.gz
    ├── 82ff5bf5df039b36919e059a281156ab89469add.nq.gz
    ├── 8396ff4ef9b97320108f238686185abd1c72793f.nq.gz
    ├── 83fb3d2f3ea00adb2a096dbecc7b3db752bae852.nq.gz
    ├── 85e240f63ab557e7c666e6155524c3d8602385ec.nq.gz
    ├── 8626d5564b9f688c9021ea7362bee9d51118a093.nq.gz
    ├── 8674420d7fe7b99e7bc76605cfec503b7ab9bbb5.nq.gz
    ├── 86f6521c04884f81c9a48e50e3ae383b3aaa3ddf.nq.gz
    ├── 88c7473ba3ac0211440427f20c2b4fac16f20175.nq.gz
    ├── 8a253d585bc26515346accbc87003f2c22a4b1bb.nq.gz
    ├── 8a67e6f7d38ba7a513472399cfe75350ba3dec0d.nq.gz
    ├── 8ab84a8b001e7cb485e2a9479ae1f31ce35385fa.nq.gz
    ├── 8b6d961f430605629ac9dfd9d2c657e6d6a7dc5d.nq.gz
    ├── 8c89d15c1bebc3086161105f0251fcd415930dc0.nq.gz
    ├── 8cdf64125cc5f711b487f01301a9dedf67673227.nq.gz
    ├── 8d47c02d9408d34b2a9d566c0fe0d42bf82fb735.nq.gz
    ├── 8d9d18ed7adcee7f73a5d99d8c6ce343f09d30d9.nq.gz
    ├── 8dec03c6b551e16e8d18690b67717da6068ce5e6.nq.gz
    ├── 8e24d62a48801854b5852282fe2035b3dad13172.nq.gz
    ├── 8f8415de4e460fb69cb4df81a831d18bb3adef3f.nq.gz
    ├── 912769dbb52637e86315c2642df0b9abc019ec31.nq.gz
    ├── 914800034b3d06c1030cd88dafe647b72f02cf46.nq.gz
    ├── 914a6f472d0a428ea8bb179551595f98981f538f.nq.gz
    ├── 9417bbb3bded1472fd84991b42a7237c4e8752c7.nq.gz
    ├── 94482a655f7ace3716ec4ace04ae0b261b5467e1.nq.gz
    ├── 9759710d1d3e16eb10012d56babb73f2479ba9f0.nq.gz
    ├── 978678f909a5f0d4b45d725c86db807ec7804ad8.nq.gz
    ├── 98077fc09b0628dc61b7226b7275c4adaba4ce18.nq.gz
    ├── 98577abb3768e8f20cc0ea95cfd9f19bc9e087c0.nq.gz
    ├── 98a9b318c0f26611cc54bdc1d847fc4122fe68ad.nq.gz
    ├── 99a6a6a3f2ac196590b7ee26fca38b7fb777f8cc.nq.gz
    ├── 99d56de3d53fd5d5a5039e65ee79164ab1e59f2d.nq.gz
    ├── 9b400a393edcf0e3dc4cbc9602df9b759264c4a7.nq.gz
    ├── 9bdd534fd2beb9b878f0219da9d63ffba56677e2.nq.gz
    ├── 9d974c1866ca63321a1cb8fd88e13583c86dcbc8.nq.gz
    ├── 9fcfc7ee7b0051f60fdc69a08d8c629cb32e4b2e.nq.gz
    ├── a0e581cb32ea4e565ca5b5095a90120df4dc1a5f.nq.gz
    ├── a45ea26e771a071640c63d43a1d5a3809b4cc294.nq.gz
    ├── a4732d1c725eaf8bd442571c7b4470800c084130.nq.gz
    ├── a58daed496d3c32735dc826c6138dc2bf6c37d34.nq.gz
    ├── a5d67bc96f19e26aade2d6651c700f3d53f4fbc2.nq.gz
    ├── a6769d3fb4d04c1006784e73a80b216040cdf63d.nq.gz
    ├── a90eea85f6f7bded69ff5d40114447a6d8b48cfe.nq.gz
    ├── a9690dcf97c65f4f0885e6c8d5ec412973f1ebf7.nq.gz
    ├── a9fe8e7e21c2d623b572e5e69b164756b3182b5d.nq.gz
    └── aa0d88f7b930331871c04ffe334a417435db8c13.nq.gz

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

[block/finch](https://github.com/block/finch)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
