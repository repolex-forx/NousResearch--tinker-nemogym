# Repolex Knowledge Graph of NousResearch/tinker-nemogym

RDF knowledge graph data for [NousResearch/tinker-nemogym](https://github.com/NousResearch/tinker-nemogym), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/tinker-nemogym
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ebd1c3ce642500b0d505978924ae37ac95960e38
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ebd1c3ce642500b0d505978924ae37ac95960e38.nq.gz
│   └── repolex
│       └── ebd1c3ce642500b0d505978924ae37ac95960e38
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ed83213ebed1708cd6025b54367cf45a09b0c9.nq.gz
│   ├── 039603a69f1d6b938e343dfe76eee80a7a71c85e.nq.gz
│   ├── 03f476016e9f8d17c0f3e2d3b681aa68bcbab8d2.nq.gz
│   ├── 03fa14a3d5d608e87367fadb35b05994b00ec918.nq.gz
│   ├── 07353c20f8c720022e68e7215b51f8796038e5e1.nq.gz
│   ├── 097e425d6251f1e417ce404c29e7b6c14d7c6a6b.nq.gz
│   ├── 118fb373bdd081c8111e91db825215adf6e491cb.nq.gz
│   ├── 11cc264c8bf8370a192c32af558104ea6074bdb4.nq.gz
│   ├── 14518a0ce257a8533aed6589dfc4f7212cdb941c.nq.gz
│   ├── 16221f3359fef6ade1fee28f269826611b544768.nq.gz
│   ├── 1949048ae0c0d23d12438c47845cea6c6f3f38d8.nq.gz
│   ├── 1a03a07f19db32e9b62b214a1e79fe28033a96d7.nq.gz
│   ├── 1b78b78c27a7dda119dcc175c9ebf5e6ce735ebd.nq.gz
│   ├── 1c22ac28851206529d3a2ca168ad74715aa7e3a3.nq.gz
│   ├── 1f1b5e4037528a157a3676212f89eca72dc685be.nq.gz
│   ├── 2236b6ee87c7f11320dec18f80baed2066b7abf3.nq.gz
│   ├── 290671452ef51002d5cd246afa2e69b3cadc92ed.nq.gz
│   ├── 29cf4d7db60f609cbe20bb5a06d2baf13ed3268b.nq.gz
│   ├── 2c8d9c75059678c0d323554ce906f97e43c211a9.nq.gz
│   ├── 2f3ac8d24565486ad7be3da84bab08e7ae67f3ad.nq.gz
│   ├── 32206346c9c9713025cba07dbde7e6d09625999b.nq.gz
│   ├── 34097cbe4f70e5b4622e5f168de6a786b17ce244.nq.gz
│   ├── 366a0cd8998caef72025cdccaac432f559da4241.nq.gz
│   ├── 36f23a29846d1f7487eb547c5ec4bd2442a312f5.nq.gz
│   ├── 383ed0500fdebe64e785d5f74ad1caa935257dbd.nq.gz
│   ├── 3b487bd02d45ef1d087bcaf6b598ada3aca5fc49.nq.gz
│   ├── 3ce1f2a55b1ab5f3199ea514694c3fa4e90d89ed.nq.gz
│   ├── 3d02fd6497a8b87d63fc6da80edaa9844570bee6.nq.gz
│   ├── 3dfdce5022b95fcea392bd629fc9d89305813215.nq.gz
│   ├── 3fba075cd642aea937ed6daadda4328ef4c204d0.nq.gz
│   ├── 42840c78ee8076cbd4b5211365151f406967a72e.nq.gz
│   ├── 42f57778b96f17c10a420e678ef352c067b133ea.nq.gz
│   ├── 473cbb005755a6e4f05ed5f6c1b86fe76bbfa378.nq.gz
│   ├── 474feb2447b67c3e824b2764d9dbf2a018a23dcd.nq.gz
│   ├── 47c5b3109913df1c8f7d5c3816d47da2f25b5bbe.nq.gz
│   ├── 48b9b8cf1fa1bd0c6191544b270e4427583b297a.nq.gz
│   ├── 48dba33a0fed0d1fd1a0095353f80456950ce608.nq.gz
│   ├── 4b818a904fb510fc9124e13f8d329066111de50a.nq.gz
│   ├── 52047f452fccab1e05eb53cf21ffd9b4cfca887c.nq.gz
│   ├── 528e5044694fa26da28da4ea61f74a8e0f428717.nq.gz
│   ├── 56b863f4ec63d21a9befa4b0b39d64ba3a164dfd.nq.gz
│   ├── 5700b997827973cb0eb6d84a2782bb08a5872434.nq.gz
│   ├── 58ccb158cdb2bfec9e7a2d550b4dd57bb10dd1a4.nq.gz
│   ├── 597c63dc5339ca9c6c13d6e760e87681a4f0b61f.nq.gz
│   ├── 5e9299794f1672271343fcef99dfa1c009b4c92d.nq.gz
│   ├── 61774b280079f7156a945a7e7f0c8d4de0f86ac7.nq.gz
│   ├── 63e0f6d780f5fd85ea459297941e76b86cfa8ddc.nq.gz
│   ├── 640a84abba13c62489132a658864eb1fbdd0cbf7.nq.gz
│   ├── 65bf5fadac168f37ed2e771db472a6cc638c714b.nq.gz
│   ├── 695da7b367887bf1029ea6d099e1b774e9426513.nq.gz
│   ├── 6b60b34083fc39f47cc51617ca98ab5ada2bcc35.nq.gz
│   ├── 6d6f666087c80164fb8b431cf0fdfbf1066c0ed1.nq.gz
│   ├── 6d829c6539f890d19675c4a0cf4a02668a3c7e31.nq.gz
│   ├── 708040a8c802701c3d269dadaba91cbba8f007ff.nq.gz
│   ├── 749713e880160b74cc237850fe48580fb822d0e2.nq.gz
│   ├── 78f30bbb67f4a4e5948dbd3cf0d5e8d0742f9532.nq.gz
│   ├── 79eff1ca1af25ca04a32fb8c4129b7f095b7661e.nq.gz
│   ├── 7a2254993b6fe373c449d0342f537dc0dd83ca69.nq.gz
│   ├── 7e692d7d5864e38e2c85cad00cef64a83306a708.nq.gz
│   ├── 8220590d1314f282143edef6ef6384837620899f.nq.gz
│   ├── 824179e092268667abce33817bdd069b9703d8c2.nq.gz
│   ├── 82dec332f457d7be4d85061c7528baed8dc4f97b.nq.gz
│   ├── 8b3c6e5374daebfcb99aeb1231c052ef365764c2.nq.gz
│   ├── 8e6571ba7e431d3fbac6cc4eadd0b67dae4b64d6.nq.gz
│   ├── 955d399c6a00c5cf12ac93ce4d6d9a75694b568b.nq.gz
│   ├── 971595eb3b6d882f727ee2c0b2baa5c9c2697c15.nq.gz
│   ├── 9ad274aa42d331946f91b9d5ca1d0b64a61b7a3f.nq.gz
│   ├── 9c157334010e4c48e5f7a6aec4f2ca56f7caff2e.nq.gz
│   ├── 9c54b853f1c5d062124ead06896bd2a82d222f74.nq.gz
│   ├── 9c8ea7fad523dc8be8afaf4c2b344045ac1ea4ea.nq.gz
│   ├── a1418108c9df07b3c4d08baa66026acef5307d27.nq.gz
│   ├── a2654a3766cf2a574ce1f6636554b0903d7ae8ce.nq.gz
│   ├── a4c7f9125723009bfab80b345c8f661f7b875280.nq.gz
│   ├── a9bca4a3e4955f49e11a8af50371889f93842869.nq.gz
│   ├── aaf837f5ddd601bff9ece7d2e59546311674761e.nq.gz
│   ├── ab1033bd37224ee84b5862fb25f094db73809b74.nq.gz
│   ├── ab909c148f3728b937ab35ef604222d0ea694435.nq.gz
│   ├── aec923fe874d18296d08576650d276a62f320e88.nq.gz
│   ├── aed8f78d55565f8514e180d2219d0f5b36ab68d4.nq.gz
│   ├── b0f65da69acbd995317496954fe8a9351388bc83.nq.gz
│   ├── b9fd1e911d57cd80e62dbc573ac1db1a0765ed87.nq.gz
│   ├── bb70bf7617a14551239ff4f3075b8f7d71457788.nq.gz
│   ├── bf30189bf16418108ee30ab93cfd04d0381a677d.nq.gz
│   ├── c07212527cd988481a751084397ef473f3e42411.nq.gz
│   ├── c0c428b9c868612e78a9bb57d483172b85d4b232.nq.gz
│   ├── c3df51940245f6eff703bf43ad99704f60217f32.nq.gz
│   ├── c58d547f922682a8814d5dacd0ae844940697524.nq.gz
│   ├── c87f0f4b529232d7221c6d7110a60dfd000aa120.nq.gz
│   ├── c88c0b9b787da90e65515286451e7436be093f80.nq.gz
│   ├── c8b82cbed8b50228f1b4222b0a07a9757b63aa76.nq.gz
│   ├── c8f9bb74c1f4ad61c401f4454f911019df12658b.nq.gz
│   ├── c9856fd79674c7aa6b28affc6d4da872d5264fcb.nq.gz
│   ├── cbb90dda98c3a628f07b88420f86e142d7ce8462.nq.gz
│   ├── cbbe8a143daf100cecdc75cf2159559465f215c0.nq.gz
│   ├── cd196de498fe5651e18f1a77ae344ff4a51b15b6.nq.gz
│   ├── cfb607518798e495d92ed9e4486e0fee94ec4229.nq.gz
│   ├── d1bd8ce2754e811ac2ec86c6d077c3fb3a5d2ca0.nq.gz
│   ├── d79f80a449d4231d26f17734b0e29878d28e6010.nq.gz
│   ├── d8305c68b03c1b35149b35f6f1fe2fcffa1af041.nq.gz
│   ├── daf3d55c03ef1dbb59eb11bd7b139a04d0ca7b2f.nq.gz
│   ├── e0618482327ec4ea821f2649bf5f964240e0a17f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a21499e34dcbbc7de2b68550c7400c5dd3c7a7.nq.gz
│   ├── e82b64451595c737029e3e7c8eef1e9dae8589bf.nq.gz
│   ├── e98642aea68ad04fac5cc7d8f23467e81def8e64.nq.gz
│   ├── eac52e0f7ec478d4dcd7aa672dc04b8abfbaca2c.nq.gz
│   ├── ee635cb13357ac8a1eec61891a397a5b1234883b.nq.gz
│   ├── f5d80e1cc599e78c24ed0811730a78ae00de716e.nq.gz
│   ├── f8e76ff71a096a1ac5cad1bfc0ada564ae68c1d6.nq.gz
│   ├── fc78d34ad7464b3b7fce7b05b3061260b1065ad7.nq.gz
│   ├── fcb5e19091673268bbb77f44b6dbfb90fdc45d36.nq.gz
│   └── fe9eaa9fa3a2d8531f884a54a9ca51e822dee7cb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── ebd1c3ce642500b0d505978924ae37ac95960e38.nq.gz
├── filetree
│   └── ebd1c3ce642500b0d505978924ae37ac95960e38.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 121 files
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

[NousResearch/tinker-nemogym](https://github.com/NousResearch/tinker-nemogym)

---
*Parsed on 2026-10-08 by [repolex](https://repolex.ai)*
