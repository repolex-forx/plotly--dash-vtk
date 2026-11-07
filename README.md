# Repolex Knowledge Graph of plotly/dash-vtk

RDF knowledge graph data for [plotly/dash-vtk](https://github.com/plotly/dash-vtk), parsed by [repolex](https://repolex.ai).

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
rlex download plotly/dash-vtk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 32195915653a7fd9930faec6a029fe6636cc64c2
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 32195915653a7fd9930faec6a029fe6636cc64c2
│           └── chunk-001.nq.gz
└── blob
    ├── 007f2d776727e2b3d12d8f33a99fb03d5aad35ef.nq.gz
    ├── 030cfeaf2c0e8738ae37a9f4817bc284ce9087fc.nq.gz
    ├── 0320f44a101a62c6f0716b553961eed3a85bfd5f.nq.gz
    ├── 03d4eba26ae0f96b18b29a06d01f36078bdfe2fb.nq.gz
    ├── 0520e5e4ce5dd18a48d41b633ee8fa2967e35e67.nq.gz
    ├── 06a8ae6b8c743382261cdc7133799063e5bc3bff.nq.gz
    ├── 06e1679e4a894e93dcc9c67b0a061f48fff6e06d.nq.gz
    ├── 0892b09d273ad9681387492535b37586b38cee25.nq.gz
    ├── 08e20d5deaf2012323b51c5275463be829a07afe.nq.gz
    ├── 08fcaf3916bf1990c3d65c17bc2c269740a2bf4d.nq.gz
    ├── 098568685e16a8eefc453d29aaa2a116d7105c67.nq.gz
    ├── 09a1a7ae34e950c8d5c491c5709040b5386704ed.nq.gz
    ├── 09c93336d22b54c1691a299ec09484e556368634.nq.gz
    ├── 0a5db83336bcf75dc63322ac34af7f2ad03c0ade.nq.gz
    ├── 0b77c078bcf69d9de56838fb01a71e2d01d80983.nq.gz
    ├── 0bb1753afa634b98fe05d36c31fdc3425a5e3ff5.nq.gz
    ├── 0c36a89826415bb87ee94c0901bbe6e143580ac6.nq.gz
    ├── 0cac3cb3ced45e0b7e22c6f73437dbd0f2d9adcb.nq.gz
    ├── 0d30e52dc49ed2036780f23346097579fd9a42c8.nq.gz
    ├── 0eb548bd7dff672e4ac97da530aceacbbd5ccb2c.nq.gz
    ├── 110cc99c05d965c74b559b083635b244a6f8c29b.nq.gz
    ├── 1158ca1fd6f6aabbda96f853e31f0d0adbbe0892.nq.gz
    ├── 14597d808b916a54088c8a3a8eae0e4cdb142d3e.nq.gz
    ├── 1468d0e3ff974309b385aa73c4b520693f92c3cb.nq.gz
    ├── 15e91b139009971bb28383c916ee5aebe8904f6c.nq.gz
    ├── 1611d86d33667381bfbfeaabd52da337c10cd2ea.nq.gz
    ├── 16ea16465210730550fad915a377ad516d49bd77.nq.gz
    ├── 17257e63144f366852e558cc9b34c7d8f3b5445a.nq.gz
    ├── 17387be770137fd327020ddc241133f5a5c52547.nq.gz
    ├── 19f3bfa8048283a7694cc57ef7bf5a60fede34e4.nq.gz
    ├── 1a1fe2421ffef8fb9cc8f3706ff182999d1a0da0.nq.gz
    ├── 1a3e4fe54b365c210fdb6759545eef06cc2ec265.nq.gz
    ├── 1a5ee9269e7fba1b006b54081cc281be08abbf32.nq.gz
    ├── 1addcd4306f6d7b085fa4dc8f63cacec890cc986.nq.gz
    ├── 1b5d706901aafb6058c269b8dab6ee435b5cb5a6.nq.gz
    ├── 1bface244fe3c3411f1e109b9ff92c2c075cb766.nq.gz
    ├── 1c668142790efdc2faaafde78abc5013c5de8690.nq.gz
    ├── 1d3270a56327231065cad61fc743a01d99de0a77.nq.gz
    ├── 1d7e9a503c69ca7ba81589b022f35d6d7e07580d.nq.gz
    ├── 1db4f709c61fd2a35b5f09a20c59fb9020770f4f.nq.gz
    ├── 1e9ef0e8879fa62b58590b68851a9d7a338d21e0.nq.gz
    ├── 1eb072db4cf63989c7033f5523509861c05a6fbb.nq.gz
    ├── 208c8d7151ddf6e6f43493498c7d9e4caa64d671.nq.gz
    ├── 217cf7d45eccc6d4f10356fbf25a150fd51bac98.nq.gz
    ├── 22e8495f82dee24f38768379f06cda0fe0e4810b.nq.gz
    ├── 23972f8883539076be2ba77ea1b0b2159cbb57cb.nq.gz
    ├── 257b314f5fd25cbeb7257e1e2028d95ebd5f5b47.nq.gz
    ├── 2630e2dc0b246e73b66cb5b662de38f308c1c74a.nq.gz
    ├── 264e1ca2afadc34fde983886ee5e450f00083875.nq.gz
    ├── 264f5719b5995664e0feccd42969cbba313e6f41.nq.gz
    ├── 26ad7dd25c4aa1ad08b61fae5d38e7f258b4aaea.nq.gz
    ├── 26ae9bd3fd822f6b1f8a178eb20a7119465ffc35.nq.gz
    ├── 26b06ce542aaa3925eaa72ba0ab657dbd2a643b2.nq.gz
    ├── 26fbb7aeaeb53d3d76233416966bf8a2be3c5dc0.nq.gz
    ├── 285cab6cf6c97cc471f431701668ab8d5f5bd896.nq.gz
    ├── 28a55ebd0dc746529a1de819808aa37d1308fa81.nq.gz
    ├── 29ada3aa17a6fd84fe85e97594e93312ae890d87.nq.gz
    ├── 2c41fa3dd633680e11a5a4b505ddbb99e9ae3bbf.nq.gz
    ├── 2d2570259d1daaf881491f8c40206b74e006efe2.nq.gz
    ├── 2d727aaa9cd29283be34e707a091e7e53afb8a5b.nq.gz
    ├── 2f6b5c1a49876f9d584bf5fccd5494eda84092e2.nq.gz
    ├── 2f6c17dbcd0c891f26439a2c7c62106216b085e7.nq.gz
    ├── 2f6c7817b5a47875d875b17e989eb6e9124d0ab0.nq.gz
    ├── 2f6d17ff939bd6d14250c67cc4a98501576a6119.nq.gz
    ├── 3073ebd2e66121f2e5c238968096e403f5c9aa84.nq.gz
    ├── 31f5629260d996d86b1b8ee38cdb8630b906e3d3.nq.gz
    ├── 325e347a443ef2a47521522bc06e2a43b0c93621.nq.gz
    ├── 32a2d507c7a7258a03bb60297f765b451c44385d.nq.gz
    ├── 3459a77788bc18e5caa23f8ac6c4b6ba65bad4dd.nq.gz
    ├── 36324de33e50ef0f2d858ae8590dffbeecf29170.nq.gz
    ├── 36679044f38b83e7b627b68ad8bc0a134974610d.nq.gz
    ├── 3814d490e2ce16fdd51c5da5ca88aa7b00057a45.nq.gz
    ├── 3823e0247f91d56daf7c96cf2505dc75a1abd6d3.nq.gz
    ├── 38b630e820fd0cb7768cca6768a4b45c039c45b6.nq.gz
    ├── 3a0ddd47263f281f1e969a55c8c06e9f42a792e3.nq.gz
    ├── 3b2015514cca56225dc9ba2c1b0a6d2e4805a4eb.nq.gz
    ├── 3b3d1eb9f64dd889ce76057ae3efb13952835779.nq.gz
    ├── 3b97933cc673267c26a464974cadbf039e590a7c.nq.gz
    ├── 3cbc1ad55be65db51c7368004c75e15c20b68248.nq.gz
    ├── 3cd2f11b743e87f81080138ad7ff204d38e7cfdc.nq.gz
    ├── 3cfe8bed8d82db06df366f68ed71f1280ad2f082.nq.gz
    ├── 3d2ca9ea1a701bf974307811b19bb316613dd84d.nq.gz
    ├── 3e23dafb3c9ec9ae21c220f81a19cda242e5223b.nq.gz
    ├── 3e6611129f9bfd27c3f4a74473642e4d03ca66e3.nq.gz
    ├── 3ec4a1f210134aafb4572faa3b9278732b551aff.nq.gz
    ├── 4031650d2610a6d4c6dc6d6690e91fb1cf168dce.nq.gz
    ├── 415706b8cecc09da798e5fcad3099700e2f964b0.nq.gz
    ├── 4187667ce0c53211ca898df0aee1e1a28980a885.nq.gz
    ├── 4282f6af0b2b51ef86ab513f24fab56a024433cb.nq.gz
    ├── 42bcdbe5606cfc75ccbee1cf13c0fc46b469a422.nq.gz
    ├── 4766e03c8ced322580c2b46291e23c1b3360ca82.nq.gz
    ├── 477336802a47666e6b2585a1b2cd9440df02b101.nq.gz
    ├── 48fbd442daa1fe3574b6ff76b727f522e115b504.nq.gz
    ├── 48fc6389d7d4420b92724037bd1ab8ec03b1aee5.nq.gz
    ├── 4901c7af0b816f942419bfce1f757b8dfdc29545.nq.gz
    ├── 4a8b0edf106be3083227916b26cf0a4ae24adbed.nq.gz
    ├── 4ab810d624a7a8630ac3a93d4768839e9e6997ef.nq.gz
    ├── 4ac5696737c8156ba90735ae968315970f25bdea.nq.gz
    ├── 4ad44f0b33b3526223546ae256605eba2bddfabc.nq.gz
    ├── 4b1e6a7c7e688603bef634099ac8da9d199f2065.nq.gz
    ├── 4cba17814d5af1929a4f8284f9ace5d3fc31b0c3.nq.gz
    ├── 4cbdcd3f10a82be9c7b0e6fd7bdc25fc090f8159.nq.gz
    ├── 4cea3a1e57621dd3ab11eb5ec9ff77d2847accc4.nq.gz
    ├── 4ff943bf9fbfc86df668222a73116668ff634cf0.nq.gz
    ├── 50a19023637e3124161bcd370f9d0bf1bb8244fd.nq.gz
    ├── 5172f56f9fbfeb707a85bf5f2b73a0da4ab37d26.nq.gz
    ├── 524e16c6c9bb84c29ef15e2c53f0c880c000d184.nq.gz
    ├── 527cdc60dbedd39535d24005a31485a7d88f5ef1.nq.gz
    ├── 5346d589193f01533f81adb948a7727cab7eb4e9.nq.gz
    ├── 562dd6a70fdc85b4afd508268f1e7ebfa71dd104.nq.gz
    ├── 56b30626cc08fd3979cf09b398bf9a99c2bce64d.nq.gz
    ├── 57274124dd5526731f010b187f885d21f81a6569.nq.gz
    ├── 57ede6876e0f6c16db72780c0a486ef7f8458757.nq.gz
    ├── 586dcecc67a05f9442c67b45834ba92c5eae0a91.nq.gz
    ├── 5a3d2dae43c00b3b2ed9a9f565d2de6a0d8b1d8e.nq.gz
    ├── 5a6c012ec03c29e08ec56c350ad2368024d54261.nq.gz
    ├── 5b053d24812295ce5d5b08e0ebd31e57c373c53d.nq.gz
    ├── 5c08a6b2a6294278f3869c7f8a9592d46669f8d2.nq.gz
    ├── 5c748287340f82cdccc5519dc7afaf1af4f32690.nq.gz
    ├── 5cffc5cdbfbf8d4daeb8c99a348c156b9b71f78f.nq.gz
    ├── 5d1e8882a89fd8d8b5f97f867c70c3157e9cc551.nq.gz
    ├── 5dce9058cbfa8a6f73a70e0e047df375ef67fbeb.nq.gz
    ├── 5e23892c2df99aa15c4f756f817a666e9e381162.nq.gz
    ├── 5fe4603349756db3a9eccc3fd68359c9a4c66cd6.nq.gz
    ├── 609f74024e085ae5554baa93684e15dab126160e.nq.gz
    ├── 6192664c293bfd384a31a9651042bc96e9c8a8ab.nq.gz
    ├── 62294eb0c39d7d347678e1977a417fd4ed06783d.nq.gz
    ├── 6271b0fd410b6b248c58fbf4ce6c381664d51e73.nq.gz
    ├── 63838a189f81fd97f710e542b4c2f2b958bb8f67.nq.gz
    ├── 63f73dde8947948f6b0cf0bede6f6b9f7a1008e8.nq.gz
    ├── 6411bdae6340aa077eaa703996015703e7db6934.nq.gz
    ├── 647e346a59dec1f3b885bde604453f6a212b11b1.nq.gz
    ├── 64c700bd2d583f7771f70f6bdae6ea8787701415.nq.gz
    ├── 653483739976886b56b418f30f23c17361733ac6.nq.gz
    ├── 65e56ada6ce1d2408f01b1ea79305100539ca0c0.nq.gz
    ├── 66d8eadf421ef6aadc2174be8feb508dc28e060a.nq.gz
    ├── 68c322bc51cfd21fce8e8857b558430ce70d36a6.nq.gz
    ├── 6b85234978e76d5e9fc441e9f1f7fabd006558a7.nq.gz
    ├── 6b9150e96209fcf4511c67e08be89980cfe81241.nq.gz
    ├── 6c2d63ef4386d88b59797595fbeec2c5bb69dd41.nq.gz
    ├── 6c711fc238869466dd7352f32d5e276f6991c06b.nq.gz
    ├── 6e4aaee23a63a6ddd587c53a7291e826606bbf9f.nq.gz
    ├── 6e975bd60900d5dc7e25d2360e87e4173f21c8f8.nq.gz
    ├── 6ebedd83faeaf82b1658bc44c8775332f6c6f7d2.nq.gz
    ├── 6f077b675ae3f37a7877817be169c03dcf87a623.nq.gz
    ├── 70dad2eda2bd0431871f323ba68353a1aa4d4894.nq.gz
    ├── 7540ce0b51729ea327aa649e09b7ea32496e5e61.nq.gz
    ├── 7644339c2e9c961cc6763d774d14ae6d956b9140.nq.gz
    ├── 780c9332398cc83f7a0d55e039ac08472a0ec72d.nq.gz
    ├── 783516b4e11c94ac27cd66587a3721303e44c71e.nq.gz
    ├── 78e59351ff45aa36b5036d0ce8408d724280ec42.nq.gz
    ├── 792172fd912e052464ab1b022846815a9a4f1c2d.nq.gz
    ├── 7b7bc3ec4fb3dbdcf28fe3301054fb1aedc0c02e.nq.gz
    ├── 7cac331ca3b52671f09e5726af6202e070df767c.nq.gz
    ├── 7cebd06545917ea99e2ca76f6038d47f70fa4606.nq.gz
    ├── 7da6737f43035bbe499d717851c2877f764a470d.nq.gz
    ├── 7ddbffd70ea9e2f20e023b74159e4bcd606db154.nq.gz
    ├── 7e0aaa912f3f1958ec990066700d1b2b0532cfb4.nq.gz
    ├── 7f9321af36e7a0d980b66f8f7008fc35407ef825.nq.gz
    ├── 7fc23b131b2fcebc495714c2d2b2f57f889e96f1.nq.gz
    ├── 80216994d58538ff051dd65a5d6a1c75de4557a9.nq.gz
    ├── 817d35a20856b28892faca1697215156b289b3aa.nq.gz
    ├── 81cacce16f310bbef77e5c92afe3d09d285098cd.nq.gz
    ├── 83055e596ba965c962236c40fa8c19fdf9f36334.nq.gz
    ├── 852fad4a5ec72920d1753f2c0416e8a3062e8576.nq.gz
    ├── 85e1d0bb8179d0c8273467af8ceb8b14d7ceb0d8.nq.gz
    ├── 87123bf84a52d5bd7a7e6342836e9768563cab7b.nq.gz
    ├── 8745b045064a1f624a72a024a3d0ed8db6b4a3f9.nq.gz
    ├── 88f94abec341b16921bb415ce0f3d8d1f4f5df8c.nq.gz
    ├── 891cf853ac18ae685f435e89e098474d4826ebe7.nq.gz
    ├── 8ab91ef180806dd82ac92326c28bad5d7c87351d.nq.gz
    ├── 8bc2c17ff6cae3ed65641c9f85d6d6dfd490fc6b.nq.gz
    ├── 8d83a7768c9ceb4ee4fac1fcde09bff92a9d069d.nq.gz
    ├── 8f161aa3ece5a306be420c023498ef0f33b34713.nq.gz
    ├── 8f709436399ad31f0409d7d131dd736b6ca9c291.nq.gz
    ├── 90746d1267ec803f632775667e540106d83773e8.nq.gz
    ├── 926f18fb24d247c6a57cae019c5048c91fa55bc4.nq.gz
    ├── 9405ea3666248ab72143255b443d2ea08c389d02.nq.gz
    ├── 94b24d72e348f1a8348cad79e6efdbc80f53da98.nq.gz
    ├── 985d3b910da6ceab077dc42e47c37c9e316404cb.nq.gz
    ├── 9880ac534a2c999a5eb7361454c7026fa789c2c3.nq.gz
    ├── 99904c6171bdb37c09a5adbe705f605d3b8f75d7.nq.gz
    ├── 99b46a9e307db93cb25e2ebcb41df04a016ff64f.nq.gz
    ├── 99e92825dcb55b6344bdd57ae9d04cff849837fa.nq.gz
    ├── 9a8efc0c0001ed946f8417c6e448fe2825ed4261.nq.gz
    ├── 9b638f4ce288110ebd7599fb9811a7770dd419d8.nq.gz
    ├── 9c1e357af76b6951b28e149b3e3945d54925c915.nq.gz
    ├── 9c3fd078d7933c1e1a9ec77bb674fbdf751184d1.nq.gz
    ├── 9c60c746f1877b0ebb365678ae93142f1bd3174d.nq.gz
    ├── 9e2cf4e18717d7d7cb47d0d70b0532dc025217af.nq.gz
    ├── 9f6a35aa89b90b5060c7b3826c40b55bd87ed633.nq.gz
    ├── a0f60bff5b73b169f7ab25d8a9a4bdc4f71fb180.nq.gz
    ├── a1d24b464fc30a41a135b6fb9a02433f2a780533.nq.gz
    ├── a4ad7056c13527fa11c66daeada13bfd8984dc41.nq.gz
    ├── a72653f27d31c9fa7348000a02269f3a266e6ae6.nq.gz
    ├── a81622a463c87636cd672e2facc90c49a2bb17d4.nq.gz
    └── a8255197d5c91cf8b2c2850f2bf69c8a339b42fe.nq.gz

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

[plotly/dash-vtk](https://github.com/plotly/dash-vtk)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
