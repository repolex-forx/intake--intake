# Repolex Knowledge Graph of intake/intake

RDF knowledge graph data for [intake/intake](https://github.com/intake/intake), parsed by [repolex](https://repolex.ai).

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
rlex download intake/intake
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 61369fee4dfc5f1706438f0cd9c9eded6639b050
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 61369fee4dfc5f1706438f0cd9c9eded6639b050
│           └── chunk-001.nq.gz
└── blob
    ├── 000f640cfb25d40fd4439be82643b4118346953a.nq.gz
    ├── 00d27ba3a7524c8f999f0f230aaf52fb85ed25ee.nq.gz
    ├── 011d650c3d9ea1342fbc2a25893509908860a68e.nq.gz
    ├── 016ba5b98edcef05e1fc8a2aa613d379c69123f9.nq.gz
    ├── 07058d61ced8a268c7665b0480de2cff8d56cdf3.nq.gz
    ├── 0790ba5d20a2f579754777096330dbbc10da5dfc.nq.gz
    ├── 08536c5fb27f27f78c829eda1dd2b4df0be2c912.nq.gz
    ├── 087d371677a3a06885ac6cc035d2c82da2cf1520.nq.gz
    ├── 0880138bcb94f677d30fb60b9223354d75c25516.nq.gz
    ├── 0948f33024fe81abe2f8702a1406f61cf6d6c51f.nq.gz
    ├── 09817f02a7ac486804d433ad57cc770ea2025dd4.nq.gz
    ├── 0a685d96498b26c202e7d33591510af2e7e6a252.nq.gz
    ├── 0a737dfe65c1b26118dead6eb892d6f1fac6d88e.nq.gz
    ├── 0aa13ef882ec49194d2de726c652e8d42289d452.nq.gz
    ├── 0bca1718821afc08cd0c4ea803c8cad9de31a614.nq.gz
    ├── 0be93ef7e2ad7de6ef28eb82bbccdc097b4ed30e.nq.gz
    ├── 0c5dfd62c2e89864078cb26cb73f776f9fb267ac.nq.gz
    ├── 0c8547fb860e5578e177661e17f4e90c26f861e6.nq.gz
    ├── 100b2b69d8d1536a4135bf58226be5ca27dac37b.nq.gz
    ├── 1070a857b197299c15913a61dbcfb6d822906ba3.nq.gz
    ├── 126c06962a9ad9de81ed6044e404470f56ca3916.nq.gz
    ├── 1436c1f235adb04b90494ecba87a247e47998a54.nq.gz
    ├── 1443fb4b26d86462560aa41dfcc2e67cece13605.nq.gz
    ├── 1467422fe1c4056cfa27e5c64b00b0774ea0f264.nq.gz
    ├── 17c18250e5a3d728d0f5cf8b9539878e792f9957.nq.gz
    ├── 18ba690343f024b5bbe8741fe9c8e941f053c686.nq.gz
    ├── 1a6c1c78aefe71d19a316bb2891fcd07121326ae.nq.gz
    ├── 1aff5729b1ec57d94be51108fd8546a7db9ea376.nq.gz
    ├── 1d252b1188c71c7f9a062ebf76d6f224582b9a8a.nq.gz
    ├── 1f118fc369731a2f906488ab18fb1491d769f97d.nq.gz
    ├── 1f95db8e4968a59e197b0da07b83d477e4df89a0.nq.gz
    ├── 1fa49f2d4db0a5dc91ae2b2f3c840e56a897f07f.nq.gz
    ├── 1ff99a0783f9cdc524b15fdb9c19bc988f53b00c.nq.gz
    ├── 213c8f550b35997e6589ec76ac5d6e7a2f367e9a.nq.gz
    ├── 230b1a7606b2cfacfeadd471a7ce6f5d0f5d3816.nq.gz
    ├── 24fba3f4ee1078dac389fec819886b0ae5fb483d.nq.gz
    ├── 25e46123c3abb24df1564d1d723cce85d1ca5e48.nq.gz
    ├── 285473a30b1d77eb70515dfc6b7ebbaaa817a51f.nq.gz
    ├── 2a7705ccacd9a2cbc9fa3ae966dc726e2140697a.nq.gz
    ├── 2d9998be338edd8600b996c856f0556b8f289cbc.nq.gz
    ├── 31d94a25e262007405b2edca3d8b0e4b60ab8aa2.nq.gz
    ├── 32045fdfca40d266f876be05c2cb859bca807a42.nq.gz
    ├── 32ad056f32e7a5dc53fde65001ae9e5d033c7ad8.nq.gz
    ├── 32d35fe83f737d6c4b8b79d41066306d000ffbd8.nq.gz
    ├── 338c46ce5727033aa9a1ba760250dd9061df6864.nq.gz
    ├── 358cc979697d70e4aa2637a46bff2f68afe6cd12.nq.gz
    ├── 358e6e0e406b714dffcdca0969f6f368a103d5f4.nq.gz
    ├── 3602107d4096f84c0f39c200f9484862bbe1afef.nq.gz
    ├── 362973e5b9f6042aab1863ea6b909a424be5a359.nq.gz
    ├── 37417a456ae3175e5f2518e94183aada3450a3e1.nq.gz
    ├── 38b609a53081fb401bd76d5abb1313bd5ffb93cf.nq.gz
    ├── 3a38126be4e6850bb1142b2a5f0971edf11d120a.nq.gz
    ├── 3c267114753f1ac80a62f34a48cd04764e198d3b.nq.gz
    ├── 3d9f11fdbed97ef35f74963d8b1621d4ba067d5d.nq.gz
    ├── 3ea9e16938b7fc55ea4e2fec6a9ed4ecd05b193a.nq.gz
    ├── 3f439bac4988d55ef188d53fefa17f964e30d153.nq.gz
    ├── 3fa5a9b0dbb77973ae8bbd310a6bff37e99b29b5.nq.gz
    ├── 4103792610ba80474310d82aeed9c299ffbe7c89.nq.gz
    ├── 41f3cba84ea32efa3b2480904c7da27ce3f5cd3e.nq.gz
    ├── 41fff0557b74ebbb61cc20e267fd5f0ff6d89d14.nq.gz
    ├── 43fd21f11e2f04e59161e5b4d67551cb10d0f7fe.nq.gz
    ├── 44301b358749069cade26b6093872480d340570b.nq.gz
    ├── 44f76635ef17419dc2c6e16de348761b8c354c3a.nq.gz
    ├── 450a91d65fe0c3ae5be56702e0d534251e0dc283.nq.gz
    ├── 4624b093cdfaf53795ab1437d0f2ccf735d8fbbe.nq.gz
    ├── 4636e0b5b493ba6b053be2179e8a34d6913b5307.nq.gz
    ├── 48adf3e4e2531a51be194b56e58311e51f4d805c.nq.gz
    ├── 49b83e6d8fa98e816458054cf20aba059955d70d.nq.gz
    ├── 4a04631bad94205ac2535fc5b1fe99e7ebe67272.nq.gz
    ├── 4c39460429b75dd1d46a65b4fdf4aaf98c26c3fd.nq.gz
    ├── 4ce0ecb99cd05f348e4508820c376300803f9581.nq.gz
    ├── 4da9a6b6da6fe20c9289f6b1de95bf20c1e634d0.nq.gz
    ├── 4e12b82c3f8af27bf42dd3a41c6f318d2a0c951a.nq.gz
    ├── 4e43338caddba229c070901fe40d325ed3e97fcc.nq.gz
    ├── 51d8336b406e3b00dbd7910569b7a39c23363416.nq.gz
    ├── 5343c690f8a166d00e168ca90d854b86a195698a.nq.gz
    ├── 5385585d4ae367c108b234c46270bfceb15268c4.nq.gz
    ├── 53d8a9a84160006fdfb8baa10d274512d4234d44.nq.gz
    ├── 5417b310280c69c997951138f92411d5e057c230.nq.gz
    ├── 58ac65fc45e4057cea10f792c7432126e6ab8a5b.nq.gz
    ├── 5abf1304960e7e57819f0e5fcea14325b5c9c081.nq.gz
    ├── 5c7908b8a3000f45bdf3e201fe0220eda7e07516.nq.gz
    ├── 5e44b81acf4d51aaf3d9874f2e514c3e6539ed12.nq.gz
    ├── 5ff7c9af90cf9ddb6eca30c036b227967191912a.nq.gz
    ├── 610666224495f11dee3bcb58138c8dca2d6b0aab.nq.gz
    ├── 6365be67271b61e44833fdf08bb41be40fadccbe.nq.gz
    ├── 63b9260cd05c09de3ae72411b9a1ada8ba7e5a6e.nq.gz
    ├── 64ab2305988b7ba338d72b3a7bf891740b9d3723.nq.gz
    ├── 6530de2923f2a2d169dde8f50bfe0bf684b3f5d3.nq.gz
    ├── 65f50216f9dcf35616afef723c1a330f3cdd4b5c.nq.gz
    ├── 666c2b7865be788c4afe985778a836cb02fd0eb9.nq.gz
    ├── 6913e418be3358c6ccee027edb7621a1cce00427.nq.gz
    ├── 6a494c5a14a03dbccb84411c9e94f80dc91d76ac.nq.gz
    ├── 6acddf529248e050035179ea4e389cf1a72d6f51.nq.gz
    ├── 6b8915fe684cd551b3f25932f84e6498ba34bf7e.nq.gz
    ├── 6db614ffc9133ad05be1c47961af73a09fbf46f0.nq.gz
    ├── 6e1d09aeb2a4298bd84651dc40defddc5581921a.nq.gz
    ├── 6e6e9c01fe66c05225bbb477a9f8be1240f4871a.nq.gz
    ├── 6ea0f7bd9558987e888fa4e1bd0ad030387119ca.nq.gz
    ├── 6f43b3c4d57dd30ab166d1c3e24692414d22ce8d.nq.gz
    ├── 6f4e493245205b2ed19575368ae8b06c1a646def.nq.gz
    ├── 6f9f8a158a40804ef8af8355026d5936f7977acf.nq.gz
    ├── 7062e4c11db5d1402999b47c47e1c2b3bb23b75d.nq.gz
    ├── 70f0ab23b5c28dbb51bfeacf4624cf4f0975f73f.nq.gz
    ├── 72802ca910a3bc1c1163346da558c0d3d94c6749.nq.gz
    ├── 7315107adaab564341aaa3dfbe3395167a8ddaa3.nq.gz
    ├── 739168064744cc2711872ae6cc8d0a9ef80294fa.nq.gz
    ├── 7517fe60c1283d97b22098a3d6425fb51a0c708c.nq.gz
    ├── 76228f6f4e272ae8a7e838aad15f388d284be48e.nq.gz
    ├── 769141505d3e37f82eb0632211977683f3d95ac4.nq.gz
    ├── 76d538738d7357cbace5e48721fc8efdfcdf2770.nq.gz
    ├── 773ed8f3436319cadeafe40be971afe71c0970fe.nq.gz
    ├── 77958ee2e59910d7c9a4481628f8cc38c40f84a9.nq.gz
    ├── 77a9e993a9720a76c88e194c583f128c0208a994.nq.gz
    ├── 77bd6da3177825210591aa9fd0b337d72c5c399e.nq.gz
    ├── 7853ea106689c80fb680b7875e1cb80b57791c54.nq.gz
    ├── 78e19c5dbf2af383b9d8b7fe8b38881dcbff7a09.nq.gz
    ├── 790c3e0d422e2bffa12e6c083f96ede2ce1af022.nq.gz
    ├── 7996554e7f346adbb4e8277e3a55250d7c7385be.nq.gz
    ├── 799c5934010654e5990192ad13479f822b9d083b.nq.gz
    ├── 7abb6d605e2cff69fd3750eb8d5ad8b6b74ec4d1.nq.gz
    ├── 7aec066cb50ac55bb73112f96f6173b8bdcb9597.nq.gz
    ├── 80e778494c31464dd1e19d78deaabe3b3d9f0af4.nq.gz
    ├── 82ed41b3e6fe8137e934416bdca743b7d4a669c5.nq.gz
    ├── 850fe689e4d52da35b8fc06203f1c2d1a5a33766.nq.gz
    ├── 86e75e09489fa8b53b625145af15109b19bcfbe1.nq.gz
    ├── 881363e6fb9e5bd7b9d695a04830015a8948044a.nq.gz
    ├── 889e30d9e713a30dc9fe501fc46449fcb760286c.nq.gz
    ├── 88d98d3d9f6d97b6b3c5997b200f5f18afd6690f.nq.gz
    ├── 891cdaec93c9195322aed3e3130ae9317f69e4f0.nq.gz
    ├── 8d70f32354b25f664fa11f9b0f4745bb654ce45e.nq.gz
    ├── 8e0caa3ffba4b069865b87250a532c3b25686ce4.nq.gz
    ├── 8f28b4ade62a66959412f08710dcb4740409fd77.nq.gz
    ├── 92a6d9b53c95daa83d7da4f96a126a14e6b26490.nq.gz
    ├── 92b9ea9bafdaa14899df7181ff7d23651c4802a0.nq.gz
    ├── 933fad81784ae596156a742eab841f2e4dcbcbc4.nq.gz
    ├── 957c711f14dc7c7892456f6df65935d873614507.nq.gz
    ├── 96bbd39996bc83fb7a1f5da2c528443d4d7ca7ed.nq.gz
    ├── 974f9e27aa47cbb904f4b2f8100cbe31bc6eedc9.nq.gz
    ├── 976ee61a34cc7ee1a40d8bc01e3e5c247b662d21.nq.gz
    ├── 97d506fd118d42f208de9bd2c36223ceb8e6f3ca.nq.gz
    ├── 99a7bd46752f4f1fad3471d85764f8899e8dbe0a.nq.gz
    ├── 9a0cdfea55221764113574895865d00a8a7276bf.nq.gz
    ├── 9b84f4498490facf5cd71f117fa85b80deac5745.nq.gz
    ├── 9c13cb9718e89ea28aae76e0f182bf5a5e5f393f.nq.gz
    ├── 9fcb9457ab24fb72a143a98b286c6ed9b5edafc6.nq.gz
    ├── a07f66f398dcaa2838caf4244ba6e9a542adeff6.nq.gz
    ├── a0cd6f382730449e3995d23e1a892c67e97abebc.nq.gz
    ├── a0fbe00e686f2a32accaa38b56555768f143e7b3.nq.gz
    ├── a102e82afd69f1d1bcb36ad7ac22c93640024142.nq.gz
    ├── a1b7b923f14cb3aafd7b579e333579ae4a49d245.nq.gz
    ├── a1ea9d90b90bc099b266eebc04ae3764addbd81b.nq.gz
    ├── a3c6c69ed99eeaed8397e5fd810605492f9fa0d0.nq.gz
    ├── a3f99ca869cf1766c4676fded10f911cdefcbed8.nq.gz
    ├── a628fe15ebce876d4b497e115a2b15428ecbf242.nq.gz
    ├── a700f9da4e905c103dfd833b97c8f476b350e5cf.nq.gz
    ├── a7389ef0fbdd287a021972561549c6bfb27d0c0e.nq.gz
    ├── a8fdfce8e1d2184f08f37289eda7cf56e40ec18d.nq.gz
    ├── a97f05b6229966b4a2310b8eab478f28f73a9538.nq.gz
    ├── aa33845cd82178671d794040851f826e8ad8252c.nq.gz
    ├── ac653cb80d3cf3db006038654b095a967e83c7e5.nq.gz
    ├── aee6b44dedcc04ae81ccae8becbb735196104847.nq.gz
    ├── af7607c8c1e26fd73e76ebaa5806229fee20cf72.nq.gz
    ├── afa3272ca65ed714fc4be75b8cf77c92ba3a6b09.nq.gz
    ├── b0573372a31bf0245574cf42e2762813cff66854.nq.gz
    ├── b2f1e32d3ea31fbe24abd5eaaebc95b789107d8d.nq.gz
    ├── b62fe20923eee910a32042b9dba7d20654087088.nq.gz
    ├── b648a8423d0047dc7227106f8f6f5500fae44c45.nq.gz
    ├── b69079e138e97649f4f1314d1d950ba8051ad316.nq.gz
    ├── b6aa1ee20932c5a5a873a1bfb43070b5439a5729.nq.gz
    ├── b8add1fd4c3c05158f590c6a474d75e061447340.nq.gz
    ├── baa6f560161aaac1df087ead6b7950957c1f097a.nq.gz
    ├── bac48f858093504b0fb33bc2b171dfae1626bfe2.nq.gz
    ├── bb3db63c016eb2b4c1281d10410518c3935d7e96.nq.gz
    ├── bca6d7c225706970ee20d60e4f94fbb26a27026d.nq.gz
    ├── bd2fa9094b0fceb5ec78a08db3c4815cc90fa54d.nq.gz
    ├── bd9bbf55eef55c4f3a2f324bd6939103cb185afa.nq.gz
    ├── bdd08823682b1f6f5685fcb4c23764bf646b6625.nq.gz
    ├── bdd644b1163ca64e6455dd3610692c10f57a31dc.nq.gz
    ├── c12350e8665e24eb6ec296771060cbc4cd675329.nq.gz
    ├── c206c636fed188e06e92586afb719ffb872c13fc.nq.gz
    ├── c30950c960eb0b2216d959b2160b5534fa6aa698.nq.gz
    ├── c3a0b47509e0090c9a15ac87681ec0f43370d3b7.nq.gz
    ├── c520762454ab6b877a3ea021b013067805acf595.nq.gz
    ├── c59ceb9b8602608d0fe7c93c648d55281bba15f8.nq.gz
    ├── c5e4a2c0b2bee3f6f8cfc91bfd00d28ff114a186.nq.gz
    ├── c6978559fb5364e19e1bd7315ccfbe37d9628ca3.nq.gz
    ├── c79b95acb6f54eea6dba67ee66923fb8b286f2a9.nq.gz
    ├── c9a869dc7097eddf33fdb3b0800b8c4b15c31316.nq.gz
    ├── cb7f8f3e5a5c6357fa4fbd435e2e0b18aafd5e7b.nq.gz
    ├── cb8ec4b146c4ba529035bc40a7033f0b2663c145.nq.gz
    ├── cdbf438377e57ab72263bea081c50c7df646d9ff.nq.gz
    ├── cfb1dbc3722e6812ddcbfb36e4a69e01b09bf7d4.nq.gz
    ├── d06101a3f7716c6f2a7f686b4fbc5744513bb739.nq.gz
    ├── d1129f9b39287923ca2c88dbc1cbaa94b7212fed.nq.gz
    ├── d248f2c999783a7426ba5286d44c0ffa9e5f173e.nq.gz
    ├── d34372c4d1ad4a47ed10956b05f27daa1835efaf.nq.gz
    └── d3c4da21fe462bee3b8a1dd225076c8228159651.nq.gz

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

[intake/intake](https://github.com/intake/intake)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
