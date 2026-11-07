# Repolex Knowledge Graph of ansible-collections/community.aws

RDF knowledge graph data for [ansible-collections/community.aws](https://github.com/ansible-collections/community.aws), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.aws
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0b09b16b651bb4fd639cbe0e77461551e0a523a6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0b09b16b651bb4fd639cbe0e77461551e0a523a6
│           └── chunk-001.nq.gz
└── blob
    ├── 0177f8eacc2165e25c2daa8aacff7e56adf57621.nq.gz
    ├── 03dafce6b73e25b8a23765ee6777847db8193790.nq.gz
    ├── 0457142a60d68036fb40f1e1c48e4a57e3a0b6f1.nq.gz
    ├── 04fd465e2f1f1a2d38d1a1dc97ece22c6e63249c.nq.gz
    ├── 05a73845d025dc0bde571f57cb13152048c5582e.nq.gz
    ├── 061acb2c36907fcdecd67a9cd90e38e294833017.nq.gz
    ├── 07008c1fb5dfde8c2de2a00742b2873de186d755.nq.gz
    ├── 07104daa7129174fac4aa77fd40951f7c2e564ed.nq.gz
    ├── 0816527fb4feeed3ebce9e7fe4ab24547cfc49a8.nq.gz
    ├── 081fb9e9338860a2cc0e6aa00c0a27e51483dda8.nq.gz
    ├── 08e04e03c014eb03d403a47e84b1648c1d6b9578.nq.gz
    ├── 08f3e88e3d4ce47853b259d8ae76e402f30c0678.nq.gz
    ├── 0aecb0d50456caa0e3200dcb4eb4e218dafc9d57.nq.gz
    ├── 0b4f7037a71c93bb3a4cb4d39bf01e48b709fafd.nq.gz
    ├── 0b62cbbd9386dbc5f0df4f6280c2657ed7d79a2e.nq.gz
    ├── 0b691ad0a10382b89d4532e06c7eb352b1b3cb4e.nq.gz
    ├── 0c185596789ae7d7791a7d94bf884c72a07945bf.nq.gz
    ├── 0c8f094ab387735dfca28014ea15ab660e750fd0.nq.gz
    ├── 0c947b17bac26a3f67e2f0d9c3301844878d1b06.nq.gz
    ├── 0ccb37907dabfcbcba0c285f3b815aa6a968cee0.nq.gz
    ├── 0cd5b0a771e7b94cd0dc9d8dbd2e464cbf43c55a.nq.gz
    ├── 0e134527a96712eca89a0313027ce8f6ab0f0fe5.nq.gz
    ├── 0e79ebb61bf668d6b5f3da437e6c35c6646577b9.nq.gz
    ├── 0ed690ec5f73ec397acd9a1623cd1edf7a275783.nq.gz
    ├── 0f37a021936fa2f9cfbd480620fb9bf6c4782faa.nq.gz
    ├── 0fdc98e46c6b5607b1ef400991b8e4e002a47dd1.nq.gz
    ├── 0fe7fbe3390baf4c04e8a76bc68854139906feef.nq.gz
    ├── 1045164dce3b4b80c7cd937a616440394239d36b.nq.gz
    ├── 10926e87f113fb026c366866d6fa466061562870.nq.gz
    ├── 10ad102e34065bf3c8b505279c7ad68e55cb92d6.nq.gz
    ├── 11f2faed964830b5c06c67d3258eedad73afc854.nq.gz
    ├── 131f0651bd32f4be9af665f954a4ac11a5609aea.nq.gz
    ├── 1342a8d5887c2fb7d289ab10ee9aae083e99700f.nq.gz
    ├── 136c05e0d0290e2dc7eb89bceaa27b5f011e780a.nq.gz
    ├── 1395b93fd10c0705b3f9ecd4dc4bd5f97447b1b0.nq.gz
    ├── 13bc6ffa8544799504ec66e0cb816c6ca03c64df.nq.gz
    ├── 13d971105d155a8915990f9865dedf81df0ef13d.nq.gz
    ├── 13e88808fa1d0515f8add3fcf3f4ceb2678faa6a.nq.gz
    ├── 14b08bd88a9d42059880d879599750ce6235367e.nq.gz
    ├── 14c3d1182037ca8e7f5947839cbb524959d259ff.nq.gz
    ├── 15297c5dda48f68dbbd007a08f860b9632b7cc03.nq.gz
    ├── 17108e5b3673eed44132debb0b7c45a03367b160.nq.gz
    ├── 177499f353926d33029a7d008dfa8f5acecec835.nq.gz
    ├── 17bc8ac53074a517d96b423e9fb01b100b1e238e.nq.gz
    ├── 17f1dde88e2f01deff847cc8937833baa8770d76.nq.gz
    ├── 17f3126a02570199c13bf8b9af0209b42625573c.nq.gz
    ├── 18c1a366a0d325455341e856ef4ce14ac143d534.nq.gz
    ├── 19612b90c61cac55b8083876fe6ea87799862b1b.nq.gz
    ├── 19870bcc46516f71d806abfa6fbfad7cd4c2f4f4.nq.gz
    ├── 198acfc3acd1932450020dd569f7394172115969.nq.gz
    ├── 19c44066b205c5b44f806d17ecf29e386376b6fd.nq.gz
    ├── 1d38e98d746122e6358e27fae584224476f4ee0a.nq.gz
    ├── 1d9bbe21375933400c07c4c3abd39831001b91c6.nq.gz
    ├── 1dda65457f6f4c4949fdff31480e44a5badcea45.nq.gz
    ├── 1e99fd5ea03040d2ebbd443404dbf9408aecd199.nq.gz
    ├── 1edc34701406a94c0709457e53d6e3826b085152.nq.gz
    ├── 1f136642a70c15a19ecf2591170ca98b7978332c.nq.gz
    ├── 20063b40b98f8486c915770c5a827b61d1493f05.nq.gz
    ├── 2081f49e60f1715119d31e0f3cfa18150230e93a.nq.gz
    ├── 213f2d681a74c4657c7a7621f47fde1e7f2695b3.nq.gz
    ├── 218afac1c3061d7c6c500f855d7a184e119aa4ac.nq.gz
    ├── 21fa9fd98294a93e005a7cf0c4f3fcea9519e035.nq.gz
    ├── 22e419328d97613c78e702b957317ff85bf4311e.nq.gz
    ├── 23555a9458664059cd7441692ed865a61ce408bf.nq.gz
    ├── 23d65c7ef4514be9029e7c1d73b885867d81c383.nq.gz
    ├── 2446c01e3dda16c6f676ee9fe969253520be9e32.nq.gz
    ├── 2469f95984b1beeb17096bfcc9dc89dd8e797855.nq.gz
    ├── 248b5540c675668a43be07f0a006bbf6c1cd24e2.nq.gz
    ├── 25fa80918d17aa78227dbca9ffc5d90cdcbd0b70.nq.gz
    ├── 260adc8391b6585cb377f1c5c3bb73399b97556a.nq.gz
    ├── 262a31067b867a1e9fb884a08c7dde401db28503.nq.gz
    ├── 262bc99b2f01d71d81b069abed1225b53fa91bcb.nq.gz
    ├── 26819cbd1e96242668308240cd6db4de046c6fa0.nq.gz
    ├── 271aff17dffff26287c679667e5b351e4096eb38.nq.gz
    ├── 27355069438aeef670f0947c7a7896e7c5d21a2d.nq.gz
    ├── 295e5e469041f99b7c646dd1a8ffcc400ee5d17e.nq.gz
    ├── 29c581415ba1bce5c5a89c2d685dceb969774d21.nq.gz
    ├── 2ae3a24059e8bfb69a18d41519847d0ccc87dc7f.nq.gz
    ├── 2b82edf6c9d005462fc69d6ea773dae4183717fb.nq.gz
    ├── 2be4bca533ab7ac0b18e27f5aa4a4f0e99deaf8b.nq.gz
    ├── 2c1f53061598e963211075288de5655e384674d5.nq.gz
    ├── 2c5614eb8bc570650974361b3fdf92d80a722655.nq.gz
    ├── 2c9cf19d1809d9cd363c0162b002756f7ff50124.nq.gz
    ├── 2cb4779f4400421bf94270371133c91e44354366.nq.gz
    ├── 2db7f76ab152903cfa2d05c12883defea69ad3a8.nq.gz
    ├── 2e00128cdb6f627110f7a38ff052e54ab2600acb.nq.gz
    ├── 2e31df2d87cd79d7f47606ad6eed823f2e89f5c6.nq.gz
    ├── 2e61d2a8ccda788463330bdc72faf471ee254e7a.nq.gz
    ├── 2e8c38f8847cf774e8f4fa2655ee445ea598331f.nq.gz
    ├── 2f368b9e8e8584ca495acdc30cb545892b13f38b.nq.gz
    ├── 2ff719104cf63ef8111bf092701377a43787cf1d.nq.gz
    ├── 3015292c6cbc7f4f811ec8091f3081fcc4e821b8.nq.gz
    ├── 301d22c06e8ce63c3fa88f976e87383ed251b7b7.nq.gz
    ├── 30f178c06eac2fca87b590ea40940dcb5ce59486.nq.gz
    ├── 31a6674ca3a373bfd1e86eb17f7c3ccdd06354f4.nq.gz
    ├── 31c370e0976b38a8d9a5b713b59c7d9049fe1ff5.nq.gz
    ├── 33241890b569adb14392fd0aec40c5cb191bd370.nq.gz
    ├── 3369b815ffaf72b120c62c1e9959e02436abd899.nq.gz
    ├── 342057cf6e2f21f9860cdb248a282206915bb2c5.nq.gz
    ├── 34c7cfef498b2267c1a1c086777621eb408959dd.nq.gz
    ├── 35d82e289c2718944a8624007c6f280780ea8869.nq.gz
    ├── 35ecb23e3a94f3c9805acacfa9b94024d6a66478.nq.gz
    ├── 3629378c015360f79cb04bcffba8ff76d5b872cd.nq.gz
    ├── 36809ed2f7572cecc67c34bdf6432bf0e5d5c004.nq.gz
    ├── 36969897cd82dd0c2e6d553a2823eee385606cdd.nq.gz
    ├── 386233f3b84a853c0d6d95e62d8c4f2d715469ae.nq.gz
    ├── 38a0b2a20ce48012fa68f9a568dab565531a7b84.nq.gz
    ├── 38d2f40a147dd66b044159304750ff163adc5a7e.nq.gz
    ├── 39f13a71f385bc0f155046af385eda0b1a8d14d6.nq.gz
    ├── 3a010d0edd3313930dbb700d3419c41d0f1da9e0.nq.gz
    ├── 3a2d882eae4de71eaadeca964bdb170743cca672.nq.gz
    ├── 3ab103da780d28c0f24d5aa33e6d0134b985b1be.nq.gz
    ├── 3ab9be64d27e3f324581afe625ca071c33163324.nq.gz
    ├── 3b0ca2f858896b4bfcb5e1ab61cf9badc0b15808.nq.gz
    ├── 3bb921745132f518a39ebdeafde4f54c2c6a5ba3.nq.gz
    ├── 3beeca841b61c5fc6922e171a554e225b35ada33.nq.gz
    ├── 3c4e2a436bea3cb0175557a75b04f98af1efaed4.nq.gz
    ├── 3c80a3fd1bc918cce4d9bc95243aa7d592094b1d.nq.gz
    ├── 3cf2196b959c9a01194151d0f1532d8bd5f3ea2c.nq.gz
    ├── 3d2106fb1acc15ac508e2fd2c04529610d9a82e7.nq.gz
    ├── 3d73d9ca8c2cd93c47f44887699ff6df93e487eb.nq.gz
    ├── 3df85be4f794ee80b29f39fbe6c3a9941fecef6a.nq.gz
    ├── 3e5634a1a29457fc55925b29b654d3b5e3d6ccf0.nq.gz
    ├── 3ed19959ee6d96dd143f2d4c4360669a9961d7a3.nq.gz
    ├── 3f38e1a85af45c114e722f8a329aea1ee9a974f6.nq.gz
    ├── 4029505d03f1bfc80190e59eefbbb71cd23cb56e.nq.gz
    ├── 406fa5a1587a7e96f85c4bf04e85f973d0f347aa.nq.gz
    ├── 40d10a86bb10603aa57784e4a57f3a310958c6c4.nq.gz
    ├── 40e9bc913226925124d7e04fc39018722e70c07a.nq.gz
    ├── 41b5c870f22fe404e3aa42f20b9242dacd1e4367.nq.gz
    ├── 427e272b666c14e330033952c1c283846c6ebdf5.nq.gz
    ├── 429c25ba383de4db3165fd6ee8ab7d7aec217ed8.nq.gz
    ├── 4412f3258ae9a447e756151f1e830b4e25a30ca1.nq.gz
    ├── 4463722e59eee5c50bea5d87eae32778bcb64204.nq.gz
    ├── 4524a3c9cd3bfce375c3b55b4d3e05c2ded823f0.nq.gz
    ├── 45382fc18c090f8bdd55f76de10b95d7db7c6335.nq.gz
    ├── 455a9886b8c3f7178632967154fa09b3cbee0560.nq.gz
    ├── 4606e000e014321a650311b733f160e98feed630.nq.gz
    ├── 4650d75e4f64426eea061fdeb4af56df41933934.nq.gz
    ├── 46823c3c88474826a07085566958455bbcd14179.nq.gz
    ├── 46f5b34e01b5c94014584a811dbcc1f3ff180f30.nq.gz
    ├── 470706f15f2f99f88c038090a3a437154c24c241.nq.gz
    ├── 480b38f7a1b4e1168e4fb3a4bd8f97652d6c4977.nq.gz
    ├── 4873adc929155062267bb53c7bc6b3add22bbf5e.nq.gz
    ├── 48771080b4584168d1448347f65a191790c0441c.nq.gz
    ├── 488fe377f4e06871f328980175645a4d65572ede.nq.gz
    ├── 49ace153f4a3b1c909dd1f859dc7a4d4a7b5f734.nq.gz
    ├── 49d9b9201d32faeeb80b72b5d3f862b42b1f4c00.nq.gz
    ├── 49f8ae5a1469c2dc1e079273d78c6489282bdf92.nq.gz
    ├── 4a9127942f9b9b7b5dee3d9da4db78e9ef6f132b.nq.gz
    ├── 4aad92bd23e641cf282a3a1abf0a4e5ee2648f44.nq.gz
    ├── 4be42cbc56b6e27e10e474063d2bb80c9e9023a2.nq.gz
    ├── 4c01380f9b450cf13cfd543f413b503061f497a9.nq.gz
    ├── 4c45db05e6d7bbe59a9938eb90e69271239a2a1c.nq.gz
    ├── 4c7d2ba25e008b7bfe13a3ec5fa933a4a64b80ce.nq.gz
    ├── 4d005b90a5ba10bbf78799a1e598021a26e11011.nq.gz
    ├── 4d2e7c547e013958142aaaad7e24fdc3da49d492.nq.gz
    ├── 4d56c0d8f4a91afbe36319ed05dd358965664094.nq.gz
    ├── 4e3c62c7913bb3cd2f8abade77044a7bd2c97a5a.nq.gz
    ├── 4e62b7bf8e4a376e66af8d954e744936b49e7ad5.nq.gz
    ├── 4edd7475e983655e56e0b0b195f060106acf1170.nq.gz
    ├── 4ef4b2067d02bc467864b47795b10b7b8672c60e.nq.gz
    ├── 4f295646300c28aa0a04424bc130a3910d0e20bd.nq.gz
    ├── 4fa38187a049bdfa3e3b0392df044405ce30a466.nq.gz
    ├── 4ffd136da3167d2ade48f285b04d1aa263aee763.nq.gz
    ├── 50a8cb5ff0df2d8fc53a634f6d722150d8b0c6e7.nq.gz
    ├── 5140582e26784e838062cf24a83eb2129db8e978.nq.gz
    ├── 515306abfa13ccda73168c05b7dfdcc0c6c11a09.nq.gz
    ├── 518a11a3bb4598fded2962d6024bf96d9e8a3685.nq.gz
    ├── 51f64f08d19269af96695bccad22f7d02dd34b0e.nq.gz
    ├── 52f3aa8aaa4dda0ef8a0e29955f2801d63cc4830.nq.gz
    ├── 5309330008d158933f32bf61d6811ba28b6365be.nq.gz
    ├── 53ded1719700d68f7891bcd6ea098e1afe5dd930.nq.gz
    ├── 53fbc388b209541ce2efeb6dd6e1396e48bf6288.nq.gz
    ├── 540370803989a19ab781afd1198adec747a0da34.nq.gz
    ├── 5492bb922ee813cb4dfc98712a1b722d30ab188d.nq.gz
    ├── 5504cb746fd2960530a135777aad1fcad7aa1ab4.nq.gz
    ├── 57353ed8a58987d80be2ff8487b486fece788108.nq.gz
    ├── 5866de4ecaaab906f24126450b3cf08b6b11896f.nq.gz
    ├── 58857cb4c1743e3c03865dfc8fa363a4dc10f6ba.nq.gz
    ├── 5a60654d89c5f06331d62e1321838a52919fe888.nq.gz
    ├── 5b3592f308109a2a56cba55a15458aafe1d85bc4.nq.gz
    ├── 5bab44f9fb90d01b1a44311207b104d3dce1f8e2.nq.gz
    ├── 5c5f55293039d2c536e84c1bd3d914ccf626be59.nq.gz
    ├── 5cc6d31a096433619c5af19345320a6d8fca53d4.nq.gz
    ├── 5cd0fdbc78db88976903e868ae24b80d9eae3b52.nq.gz
    ├── 5d3648f8e60f454787109c400a5a81d9e67f8be6.nq.gz
    ├── 5d92219df8b0747405a24260f58baaf6f8a7d999.nq.gz
    ├── 5e235096d960d662131f303db35fb0cbd053e4dc.nq.gz
    ├── 5ec53e713643a5a2e878423257f8d78aade48aaf.nq.gz
    ├── 5f7f6c782040d432339318cbbf2ef0203ce4c4b0.nq.gz
    ├── 5f87e5afef55469eb8e37669be7c6d2458b8bf32.nq.gz
    ├── 600490706a4a2c760e5b7a036fa9a658c9ed63bc.nq.gz
    ├── 600d8eb59bd5a3a7cac3bc2e9552c374c91b3168.nq.gz
    ├── 6056bf212d8eca360bef5b5e160bbc1f59183635.nq.gz
    ├── 608246217e7b52ccab574e823742010d9f2bf541.nq.gz
    ├── 60c85b8eb34f662fc7bfca9b08201bc38f0f5c8d.nq.gz
    └── 60f6d3a56700df38532af59bf9519ebd3ff9132a.nq.gz

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

[ansible-collections/community.aws](https://github.com/ansible-collections/community.aws)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
