# Repolex Knowledge Graph of beeware/beeware-docs-tools

RDF knowledge graph data for [beeware/beeware-docs-tools](https://github.com/beeware/beeware-docs-tools), parsed by [repolex](https://repolex.ai).

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
rlex download beeware/beeware-docs-tools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 40147a4ba2d25de0b9dca008a42455ec5851576f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 40147a4ba2d25de0b9dca008a42455ec5851576f
│           └── chunk-001.nq.gz
├── blob
│   ├── 04a45720221866ee1bef7065d78853c802a0169f.nq.gz
│   ├── 05d6123c19121a1b0cff03b5fc8a3afaa5ad14e3.nq.gz
│   ├── 06269f07106707fbbe2142b4a75bda9480a532b0.nq.gz
│   ├── 074d21ba9654a345bbf7e25d0398728c87566f71.nq.gz
│   ├── 08221d8221286f6fce7ce83072823fdd6367103d.nq.gz
│   ├── 08e9e9528360006d5db93601ae3c426070710159.nq.gz
│   ├── 0cc2bcfb82521c2eca0cb383643efd97f0824f30.nq.gz
│   ├── 0f06e92a2d98fe30e1fa7a31f62fe727b61b96f0.nq.gz
│   ├── 0f28c5e5169a47569cb09b29ae2dd9d55371f9a1.nq.gz
│   ├── 1145c70cd727a3b980b17aa49cf46c711436f8e8.nq.gz
│   ├── 146b398ab7ab3a984a8bbaef614cf53abceaeb0e.nq.gz
│   ├── 1496d818ed005bdc4b6d7d2287a5a8b327e70fcb.nq.gz
│   ├── 14a86526dd4978321c30e6fff88b3975c292a246.nq.gz
│   ├── 1c04270773fd190157061a8245e28f3f6464d722.nq.gz
│   ├── 1d9f37b6ff8b8f826c7d8096481ec61bc878de67.nq.gz
│   ├── 1eea13cfaa629a530d5cdd938fc08df233599598.nq.gz
│   ├── 21e682d6bdfbb1ee2f8374028460a5889b68ac6b.nq.gz
│   ├── 21ed34eb49799859f73f164d6a5eefefac418a32.nq.gz
│   ├── 22718a3f36fe0cec5a84589cc434518ad0e4799b.nq.gz
│   ├── 23d0d5049bfa39303ae35a01940164cb7fbbf14f.nq.gz
│   ├── 25cfed253fb1b9a8a6f5bc5e2069006e3761df65.nq.gz
│   ├── 260ae8939294cf7b1d67248711ee1460f7910ece.nq.gz
│   ├── 2706a2db6720a9b98a8bd1d79588501630b12f6c.nq.gz
│   ├── 2b777b4462ef35678a5ddfec762be60bb64fd261.nq.gz
│   ├── 2db5cd49bb5e80bc14fd404e80e75b8001d42fdf.nq.gz
│   ├── 2dec4af8a6fe4f1f3a147f98ccc71ce469b36548.nq.gz
│   ├── 2f2e1067ddea64b29891f5dd4b1b6a6c1c1bc1be.nq.gz
│   ├── 30e8d2faf66511a389a0b8f84ad2503c989cb152.nq.gz
│   ├── 30f3f0c0ba447d071035ebac4492e5d586f1735b.nq.gz
│   ├── 31fa6bdbdce92bedd1fc2a42734955501b4f027e.nq.gz
│   ├── 3238192330c44f2d758b56a3486507d26c93cc71.nq.gz
│   ├── 35675f9e619970859999820c8fe0d1cd807f7c85.nq.gz
│   ├── 363d8359c9efed3b11f1aa3b964d0a45db7ce7eb.nq.gz
│   ├── 39184054eb47edaf5eee5584c5a7fa1e034550a3.nq.gz
│   ├── 3b4d057f84ab5f75040aaced8715c7a63bdf8902.nq.gz
│   ├── 3bcfa0725dbe71faaf3000463b4d0e2f609651a9.nq.gz
│   ├── 3be56fede1b1e58e79e0c89b7fe0000eef4d86c4.nq.gz
│   ├── 3cd1db686ec90aee4f3bf383d0cf336b0456c4e7.nq.gz
│   ├── 3e9364b251b9d710e35afab14bcc409d4246df4e.nq.gz
│   ├── 3f19aae3efb0675591fa49a2cb19abf636632b5d.nq.gz
│   ├── 4337efa023eb3044a45e1fcf7e6130c9bc6cbb75.nq.gz
│   ├── 43f8d1f70a796390a1e3d6c42010b4a2d84d3274.nq.gz
│   ├── 44a7772c7d582790ce580367a74b00454bd6a0f8.nq.gz
│   ├── 47bc4dd215c22faa47f744c362c08a9edc0bc401.nq.gz
│   ├── 48617dc969b02fe13424dacb167c25f20f6d90d4.nq.gz
│   ├── 4da8ef4e436408d44b08808c0f5957f81a70e8fc.nq.gz
│   ├── 4e384272ecbceaed2f616cc135a8c68cf2680069.nq.gz
│   ├── 4fa123056d2714e9de04bedcf30a3e4f8268091f.nq.gz
│   ├── 4fea1db59d3ec01e3491420df4b9ad376826ae1e.nq.gz
│   ├── 51083803caf1e4cec375e89bafb378698c6d8c10.nq.gz
│   ├── 5164a0a1d28d2ce47bd42185e6484361522e2b05.nq.gz
│   ├── 54401d4d65f62c8c5a4a27f50a26f6389843d4d4.nq.gz
│   ├── 55542319e4780ec2b7352eea9f2c9124f25ea1ff.nq.gz
│   ├── 586a4ce171f607fd47315f992a25e35c2fc9205e.nq.gz
│   ├── 5937a49d051639b7de6489697100a46fa4be5545.nq.gz
│   ├── 5940266004c926b975abc0f117c1ae32c457420b.nq.gz
│   ├── 5b5d2d0efe5e229ecb00e9c6c0c63f8747649ffe.nq.gz
│   ├── 5b73f5d79f4c200339b29de353e60caff62411be.nq.gz
│   ├── 6247ba4500ce561f11fb1845b142c748df53a40b.nq.gz
│   ├── 639b488f388ffdcae2f068ebd1fab1448288498d.nq.gz
│   ├── 65451b274976ad6ea79339f9ee9cf8749ae7e9fa.nq.gz
│   ├── 65cfdfc7e0ff8957244718df803d16f8822cff7b.nq.gz
│   ├── 6871709ba3573e2381b065f3e25d055627ed7667.nq.gz
│   ├── 6acb8bb52c75a0ea6f174d6ae9892fa7b4afdcae.nq.gz
│   ├── 6ae2f3b4ce329156216d44c4cd394c7eefa9f395.nq.gz
│   ├── 6d49e310f8ca6d5ff599456b76c090cf9cf5e8db.nq.gz
│   ├── 6d7952dd5ffe754931d15b8b75d795b4630ab6b3.nq.gz
│   ├── 6ec9fc692339f19943ee39b372c0fbf4a69c932e.nq.gz
│   ├── 70c1c0c48565a2e42c5ec85dabb4603d2ce3d0b7.nq.gz
│   ├── 72e3f4bebf56b3bebd2bbaa769825811edbed041.nq.gz
│   ├── 73c1caa173a7498ae8e2efe55cb823b7a47ce14f.nq.gz
│   ├── 74ada418b069ee6b9432dff6c238f0bedc3b7c56.nq.gz
│   ├── 7515710221e16d164eeebf64c5e32f40a77fe1e2.nq.gz
│   ├── 7755ef9798e18acb1d0287b106bfecd9e48937a2.nq.gz
│   ├── 7781a91eb394524d568d12b94ddf50191486276e.nq.gz
│   ├── 799f0fea7edf6eef52639896d8e7ef0eec7e5812.nq.gz
│   ├── 7ac9c7e76b4d6b3f798adc91921e5656eea42b8e.nq.gz
│   ├── 7d3f380d95507caccc4408078553ce4ce3d30bd5.nq.gz
│   ├── 7db47ed0ae488207c536709e7403201cd7e36867.nq.gz
│   ├── 82192dbe67d46ab8f87ed6cefc654b8586e855e1.nq.gz
│   ├── 83974c3111adf6c989ec2cef52c098eb801898ff.nq.gz
│   ├── 851aa2e6dc6e269ccc2baac8b8ccce8cbac31fc8.nq.gz
│   ├── 857f034f63e4205cbae41afdfaed39b04fd1f55f.nq.gz
│   ├── 85b9269631ae91558dedfb932f9cdf7702efa180.nq.gz
│   ├── 86dd6b3804a190bdc08fc5ad2c51adc0bee05cda.nq.gz
│   ├── 8795f3c90846e1bed31d9eab758f53bd9831d636.nq.gz
│   ├── 88d2da3ce8fc8e42e3a460408b89cf51b2f5ec39.nq.gz
│   ├── 8a51c3bca26c3750511ae5825823b6c75f1a320a.nq.gz
│   ├── 8aab5e10998d4fe1c2f135e9d324d06832efcdc1.nq.gz
│   ├── 8c4f3a76632d9af3b1b3cc89a950b77e39bdbbc6.nq.gz
│   ├── 8cdb8bf1de07a068cd8ac5efb45312ffea972324.nq.gz
│   ├── 8e03b2c963bda5ee9e1768c0a5371678debd2a75.nq.gz
│   ├── 8e3deafefd71928718c6810c3d56c87932e4dfd5.nq.gz
│   ├── 8eafdaf1acc3f80a5cf0d650c6fe2e4214cdbc93.nq.gz
│   ├── 9296776db29c8e93266d3ee5a72ed23a8e009d85.nq.gz
│   ├── 93bd9a2954f2acf13300c82ee0604e5473b39c80.nq.gz
│   ├── 9c4b9f800c1474ac38b054e1a1411dfdcba1a5e9.nq.gz
│   ├── 9cdac6e85474ad6878e469cd68ab67ce171560b8.nq.gz
│   ├── 9ef9b091e074001bc88e95f8a68be8ed45e80137.nq.gz
│   ├── a167a69c819828ce48ed7ebc0dca1d636db19d57.nq.gz
│   ├── a54bf74a5d140cdc3bb65def72bd1861945c9406.nq.gz
│   ├── a5e9a3658fc0c316ac4eb8f3a81214b3922c647b.nq.gz
│   ├── a99d4712379db178aca84297552a44af44b352a3.nq.gz
│   ├── ad2c1218979a40606c910feeb4dbf026448cb0e1.nq.gz
│   ├── ae525199e50b0de7e1d2f1d056594d12f95f9ecf.nq.gz
│   ├── aea812e3d40ce04b2d651b874e67cc2f76dbf4f4.nq.gz
│   ├── aefb69af95e2f4f6016afb6fd08255658cf88ddb.nq.gz
│   ├── b0d359665de05500513f156fdbadaa1aad82a5fe.nq.gz
│   ├── b21e1338c99b8362cc4af18d920ddfcb75607b69.nq.gz
│   ├── b26e07158c9aa265ab3d60ec5dfee25eaaaba22c.nq.gz
│   ├── b2f6c00202993a65595745775d060257df613b39.nq.gz
│   ├── b36d3c27acfc15e3f21d1026e9b6f030091a7bf1.nq.gz
│   ├── b370fdbfab6952d3f197f9efa68097277cc66353.nq.gz
│   ├── b4e27992e9e29401c339b67b0d92faffef181b85.nq.gz
│   ├── b834affdddcf5014398ca9c16aafe3ea7f2d0422.nq.gz
│   ├── b987a1ba99299d880b632a56f80623b0f3007d2b.nq.gz
│   ├── bcb4dd5301ac55d98d505b5ed8df353b58a7994e.nq.gz
│   ├── c015732f4d36e7e906202e76150b3a8374492cd5.nq.gz
│   ├── c1ecd287d16f581935ddc68d7c7da3a5ee1811a9.nq.gz
│   ├── c20328a4db3199c79172854a225f8b71ae78b2d3.nq.gz
│   ├── c2ff241e0217c06e9ad50597e30fbb10dbef1202.nq.gz
│   ├── c4d88e8173e484996f9c1fe716bd0fb7e4c8a73b.nq.gz
│   ├── c51e5aaec49808c1cdea41b361d1445a0a7652f4.nq.gz
│   ├── c59d448ff3813bda46c04ebe0f9dd3e2d1206bda.nq.gz
│   ├── c601b0bbc50eb1227e2bc8144c8d4d134fe563a6.nq.gz
│   ├── c7a6e5730b4d9bacf12158bc4e337a9b6f562e6a.nq.gz
│   ├── c815205597dae8a4c86419d2e39fc2e987c91410.nq.gz
│   ├── cc77532673be56f855e19675a72bc439bc45d3b1.nq.gz
│   ├── cd274895eeadd0e6d8eae878fdf11c90a837141c.nq.gz
│   ├── cd4838676d8ffe6b3fac624ba800479f38c3bd59.nq.gz
│   ├── ced4c1d560298b40b0ae7fa317b37491aa244ff2.nq.gz
│   ├── d117dae00fc4bf1db54547a57a29d43e5e9cae2d.nq.gz
│   ├── d3dee6463738f2f9b7744acceb9e3ed5e967ef53.nq.gz
│   ├── d54c4b5da3561e1e8d4c87ae3b3357583db6503d.nq.gz
│   ├── d5b630b8bc8bf5408ede38f24d5305ee032b6063.nq.gz
│   ├── d6df5d45a1083deb6c9d5eb810036b7ddb7edd4f.nq.gz
│   ├── d921347387608c7493c4fde765cbb2e1793dc409.nq.gz
│   ├── da085e5501cfc2de71e92f48c6d8491ed13a10e9.nq.gz
│   ├── da29b933fd0e423053d49639b74bc6d53aabebc9.nq.gz
│   ├── dd25c62e62be111bbeca96ea60121b8347fd8adc.nq.gz
│   ├── e143ead77c0c0f5a1b33103a6a638e3f097d8ff4.nq.gz
│   ├── e22c04e241c7dd4f2462b05b7d50e12b5155f5ba.nq.gz
│   ├── e35a875119e7e14fd2036cfdb344f0ad8bb7cb19.nq.gz
│   ├── e3e23aac43b57baf6685c87b7b5e38354ea630d3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6e89d6be991951fae576390671fb1fc26d547e5.nq.gz
│   ├── e765196c8b56e5e12d78bc9a30e9cc26990fe390.nq.gz
│   ├── e828b1f1a19365a2dfff348555c2c69fb5274476.nq.gz
│   ├── ead5509d0cd58c79c8a392365b9869161d088115.nq.gz
│   ├── ebf802d7be805a2310d5062078184ec0906487ae.nq.gz
│   ├── ef3b95ed46ac977a438e22264bb22e5896e5a927.nq.gz
│   ├── f162d5eb8edd77fd9974b284bd5f8141f540c5de.nq.gz
│   ├── f499d90d6478bc595774af954ea0ec5f8bf81449.nq.gz
│   ├── f56f750f4e0fa9de1bbe27a15a4f3d88a5a9378a.nq.gz
│   ├── f72cfd794134a6c44b93aea5af07b96a8b13f2a8.nq.gz
│   ├── f76775fb9d140693aeae12f00d57c59a3fd0dfe6.nq.gz
│   ├── f9be9f86c1e8ba694b7dd07fb5a05b16140239f9.nq.gz
│   └── fd2a82a2678a4cd18dcb7ce1b09a4093e13c60cf.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 40147a4ba2d25de0b9dca008a42455ec5851576f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 166 files
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

[beeware/beeware-docs-tools](https://github.com/beeware/beeware-docs-tools)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
