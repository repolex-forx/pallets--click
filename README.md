# Repolex Knowledge Graph of pallets/click

RDF knowledge graph data for [pallets/click](https://github.com/pallets/click), parsed by [repolex](https://repolex.ai).

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
lexq download pallets/click
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 1784558ed7c75c65764d2a434bd9cbb206ca939d.nq.gz
│   │   ├── 533cf7c209a0dba15b4ec784e8789d443754e64e.nq.gz
│   │   ├── 5db412ad777a40881c884dc0e17ade539dd58b67.nq.gz
│   │   ├── 934813e4d421071a1b3db3973c02fe2721359a6e.nq.gz
│   │   ├── bf1a6d4956cbbbfd0a6f4dd6310c8110cf89f7fe.nq.gz
│   │   ├── cdab890e57a30a9f437b88ce9652f7bfce980c1f.nq.gz
│   │   └── f7cdff5cfc614f34025d1fc238642be029dca1f3.nq.gz
│   ├── dataflow
│   │   ├── 1784558ed7c75c65764d2a434bd9cbb206ca939d.nq.gz
│   │   ├── 533cf7c209a0dba15b4ec784e8789d443754e64e.nq.gz
│   │   ├── 5db412ad777a40881c884dc0e17ade539dd58b67.nq.gz
│   │   ├── 934813e4d421071a1b3db3973c02fe2721359a6e.nq.gz
│   │   ├── bf1a6d4956cbbbfd0a6f4dd6310c8110cf89f7fe.nq.gz
│   │   ├── cdab890e57a30a9f437b88ce9652f7bfce980c1f.nq.gz
│   │   └── f7cdff5cfc614f34025d1fc238642be029dca1f3.nq.gz
│   ├── lsp
│   │   ├── 1784558ed7c75c65764d2a434bd9cbb206ca939d.nq.gz
│   │   ├── 533cf7c209a0dba15b4ec784e8789d443754e64e.nq.gz
│   │   ├── 5db412ad777a40881c884dc0e17ade539dd58b67.nq.gz
│   │   ├── 934813e4d421071a1b3db3973c02fe2721359a6e.nq.gz
│   │   ├── bf1a6d4956cbbbfd0a6f4dd6310c8110cf89f7fe.nq.gz
│   │   ├── cdab890e57a30a9f437b88ce9652f7bfce980c1f.nq.gz
│   │   └── f7cdff5cfc614f34025d1fc238642be029dca1f3.nq.gz
│   └── repolex
│       ├── 1784558ed7c75c65764d2a434bd9cbb206ca939d.nq.gz
│       ├── 533cf7c209a0dba15b4ec784e8789d443754e64e.nq.gz
│       ├── 5db412ad777a40881c884dc0e17ade539dd58b67.nq.gz
│       ├── 934813e4d421071a1b3db3973c02fe2721359a6e.nq.gz
│       ├── bf1a6d4956cbbbfd0a6f4dd6310c8110cf89f7fe.nq.gz
│       └── f7cdff5cfc614f34025d1fc238642be029dca1f3.nq.gz
└── blob
    ├── 012538d5fdda114b109b03f672104d53d169907f.nq.gz
    ├── 01da3f9df29e3dc1028460b24b8923a7c1e45ea8.nq.gz
    ├── 027538579199e3a0986ce3398e4608bcf998891c.nq.gz
    ├── 02755caef267c2730c04d6aa5b4f3c474e01108e.nq.gz
    ├── 02ef9e9f045cd437ce043a72e29cbc1de732e962.nq.gz
    ├── 0434e07215afa9c3dee74eb8bb437b0a2332eafc.nq.gz
    ├── 04d263eeac9f0e38ec1c3922e88b15b38ced58c4.nq.gz
    ├── 0502dbce18e838b1675343d200e3f2176b6af40b.nq.gz
    ├── 0579a37318584eb843e4509d109cdd67bfc8305e.nq.gz
    ├── 0580cba7a026c83b738f473b19aebd03a1563ca3.nq.gz
    ├── 06ede94bce3f42135bfcdf220144a1342506ada3.nq.gz
    ├── 07b5257ccc0c9b1f81df7815c1e6b62e8264f167.nq.gz
    ├── 07d0f09bac38f7deca2514e7e33c177577e8102f.nq.gz
    ├── 08266b160ae64963bc91d0f66f98c2c8819e1778.nq.gz
    ├── 08c31b113ebd1ddc052f9d2f8ecf72b83c5f4962.nq.gz
    ├── 09535a68570b08d9a5dfef2d5a5397d9a299bf62.nq.gz
    ├── 09efd033cbcdce184d3c7ecfec9a097e9f44f7bf.nq.gz
    ├── 09fb00855e68840d18187f3de3a604e7defc37e8.nq.gz
    ├── 0a33948664037abacf790ffae42da48bb2ba6475.nq.gz
    ├── 0a61966857f0101b0ab31d4f96f45c33be5fcbd5.nq.gz
    ├── 0a74d4144abfd4ecfe747bd1ea0780c4979fd07f.nq.gz
    ├── 0b510c00b8aeed45f6af134b17148f08ce44916b.nq.gz
    ├── 0b64f831b5578e7262302ec9218fa498a2336794.nq.gz
    ├── 0b8315166ea2594f89b18e8d6dbdff2929b3ae18.nq.gz
    ├── 0d227f2a0a6b679085f05ec0e519aa5380321270.nq.gz
    ├── 0e2e424cb2a18694aed3f71126d2dec2b9618f66.nq.gz
    ├── 0e438eb89122cc49b5c1c34490ff818d47fc34f5.nq.gz
    ├── 0f3e90c1797d20354d582e900d7387654302b0a5.nq.gz
    ├── 11716969a2e58c5717bde62bb73706ac57bfdf22.nq.gz
    ├── 11d796a65a3f5e1b0fe89124b22fdcee7225c885.nq.gz
    ├── 11fe29dc5d9bd1213b4dff98565ea495e8317e6f.nq.gz
    ├── 120c6e76ad8fb07f1fa65a11da488ffeb811efd1.nq.gz
    ├── 125fac3c4429cb14887de3db62abacd7ce2fce1c.nq.gz
    ├── 144178ee908a7a97d57163c63b94f1b7def8f30a.nq.gz
    ├── 147946324c884168fd847cc1e83837a60808d748.nq.gz
    ├── 1649f9a0bfbe60ba6c386d18634cdd77eb8df600.nq.gz
    ├── 1704daa2c04139c5b2d1ac0bd4e1f21dab6d6b34.nq.gz
    ├── 181c5b3b705a0ec26e6d4c925db0268d3ff7d297.nq.gz
    ├── 1915de4af86afed493fac007ec5b1a4f4a55035e.nq.gz
    ├── 191e712dbddc442d18c8addbaf6fff74ad9055e7.nq.gz
    ├── 1928e17b3ce0ce568e75c7913690ddf112643059.nq.gz
    ├── 195379472621c85e7424f06b8f5b91284245cfe0.nq.gz
    ├── 199b85bbe7081767cff4af3ec2af564082a2168a.nq.gz
    ├── 1aa055dc046b665e3a962a576c5dc4d598ceadb2.nq.gz
    ├── 1aa547c57af68954b3bcd6012873881030e53d91.nq.gz
    ├── 1ad3bdcbf150c794d219c72d73674cddb901b6d9.nq.gz
    ├── 1b1575657c7d5a74d7ab0fd55088f7ee4ddfae23.nq.gz
    ├── 1b41414a1e582cea87f9324ded5d33f2b7d11169.nq.gz
    ├── 1d94417039d870174e3a11774f9f037dae18e66a.nq.gz
    ├── 1d99218cdc6b2287a8633fe809d4b7e41f65434d.nq.gz
    ├── 1e941d8ca3dfaa2522e04702ac10f2dd8c9cd9f7.nq.gz
    ├── 1e9df6f9402973be8ab0877b93da6b3e4b073d9c.nq.gz
    ├── 1ea1f7166e4b9eac5bcb632ecd86fe0331829141.nq.gz
    ├── 200f5b5e2350c6c131bb3699348c638f6578aa19.nq.gz
    ├── 208b193f1ac5067d5ee449eaa0f80bd5703dfee8.nq.gz
    ├── 20cbe734280e51ab5d64284ae0b909b4ebdfa89a.nq.gz
    ├── 20cff238f7c72d4999b20205c1fa0244f9934d70.nq.gz
    ├── 20fe68cc139d2cbff3928659bfc3999f37d35c3f.nq.gz
    ├── 21f4c342245fa93a7946b17d7661e0d2fa6a0c29.nq.gz
    ├── 22228a1cd2fd561782e0fc49bbbe17d61007f4d8.nq.gz
    ├── 22a285d906b3bec64441427ca7e0f6f566eafac9.nq.gz
    ├── 22dd39f4cdd533b9e88f045ff14a8552644cc2f3.nq.gz
    ├── 23520a0f20c6dbc1248b1398d743cc190b075247.nq.gz
    ├── 248f1acbb6140f817983cb11c90c228f9711a36d.nq.gz
    ├── 250c646d4d565e29da96e0b276685d87be4e9b85.nq.gz
    ├── 2610d0e1422dd5021a7d5ff2e78992dece7cdc8f.nq.gz
    ├── 273c00f9e44ae8569b6cc936c7b2b7cddf49ba1f.nq.gz
    ├── 29f3d6c143a17005309052a98d139c61685dfa4b.nq.gz
    ├── 29fd35f8557158826f728f846f4c631a18469400.nq.gz
    ├── 2a445f9c62843f5205e3e4a920fd49c1808a399e.nq.gz
    ├── 2a565c102975b968624f6cb1eb7f145f42cdb0cf.nq.gz
    ├── 2a8da70125c840b610f7d60b712920204d47d27f.nq.gz
    ├── 2b223ab42264487f3f490e10f5039cfb4b373a80.nq.gz
    ├── 2b6008f2dd4176d819f06e0d7e92e43b142d30b0.nq.gz
    ├── 2b7a6729692c96ce8aa0804e1c78fa42fff8753e.nq.gz
    ├── 2c9d9dd045e9aad50efcdd8f0999fadc5812dbbf.nq.gz
    ├── 2d5a2ed7ba744f0eb6cd561d98c667b09cff4cc0.nq.gz
    ├── 2e98a0771ca410a7a2ed83199cf401e75cc6d41f.nq.gz
    ├── 2ecf518af5d66bcf6f615928bf2f38e52414c812.nq.gz
    ├── 2f6ca903b1af7b31ec31e0420284af4df776850d.nq.gz
    ├── 2ff985a67af35fdfd1076354b771c425867cdab4.nq.gz
    ├── 30059aa42dc72c321575b5814e73ae9a61ce2b3c.nq.gz
    ├── 3028020d8257ed4a94b8581714d6f19a5b6f9bea.nq.gz
    ├── 30a4d9317af24c0dd8eee4b278f5639a10291c8a.nq.gz
    ├── 310e2b251ca94d051b242058ecc42903bd8f4f81.nq.gz
    ├── 314842bdace76c0c0a17ff34553a3d66bcfa3856.nq.gz
    ├── 319c7f6163e266de1abe6f96bd4290193184ec6c.nq.gz
    ├── 31eee844b933a2532195e5f43babc1018ae65f24.nq.gz
    ├── 31fc546e24c366078ccef7bf3b5c6426aaf2ab0b.nq.gz
    ├── 32df098e9bb08f9bbc36b77abe62f06a032db1b6.nq.gz
    ├── 33a73a89f7c9ea550a727d18c847500d700cf6e8.nq.gz
    ├── 34336dc39193b7b54a5ed7018c0cd8a8bdf5f394.nq.gz
    ├── 346900b20057ec00e57daea6fe05344254f1c168.nq.gz
    ├── 35176c73e39cf8f79339bde23d3f5b5f9034eec9.nq.gz
    ├── 358f5245f29d52e25a2d39814176b6da69c0ef13.nq.gz
    ├── 3644509e043832c8867c7e110ce2b75bf46df020.nq.gz
    ├── 372b1d4cacd0f6ad649f282b7eb98137c0f77d18.nq.gz
    ├── 378eac25d311703f3f2cd456d8036da525cd0366.nq.gz
    ├── 37a426dd48065f221f1789983e66b5f053007cc9.nq.gz
    ├── 37b39f5d249ca4fa71a619e9f30619e39a3d4e82.nq.gz
    ├── 384846683a9ab348c5946cf3f2037cf9427028f7.nq.gz
    ├── 3932f5e1d02bd33fb005cd6ab040807ef645f4cf.nq.gz
    ├── 3bb77f68483eb9937e75a309f6c530f251bcd996.nq.gz
    ├── 3d3fdad141ca0bff287a037040bb96abb4ee291b.nq.gz
    ├── 3d6cbc9759cdefa88fcde22571f75dac55a17bbe.nq.gz
    ├── 3dce4a42e9516af7a2f734470b5d361c7100e1a5.nq.gz
    ├── 3df492a778a0d979fd028a69e492d53b7e83f480.nq.gz
    ├── 3e1a59492615436151aa96d7845ef38749587b0d.nq.gz
    ├── 3e4f6c980851be9f71d80797c19a51ce16d34a4f.nq.gz
    ├── 3e7a2bd7fd1da8094046a131f07f53ed5939d6a0.nq.gz
    ├── 3ee050af0e04a01c5906abd816205005e610f133.nq.gz
    ├── 3f293e881626a1c578eb2071cff929124394bfd1.nq.gz
    ├── 3f7352879fb5be878ea161a892537e973dff3f9f.nq.gz
    ├── 3f78df0e7f6d0c119aa37ad4e48409145bdde4ed.nq.gz
    ├── 404870bbe5a826194aee107976788c74cc0c4d88.nq.gz
    ├── 41bde2641eb46650f5113702d33e48f7a9c57ced.nq.gz
    ├── 42c79028d267ecd0dfc946c1f270fc0e54fc6d0b.nq.gz
    ├── 42e26acc34906ff08d267269aedaa49782f4c6bc.nq.gz
    ├── 43afe5788e15287d36a98616b5047bd0a01c16f5.nq.gz
    ├── 442b638f465ed78915e507eb1bbfbb549b9437ee.nq.gz
    ├── 45e36ef753d4f52c2e7e3bc5fafba04780955ba7.nq.gz
    ├── 46dccd47e248063e981bb40cfef5bf4d1e193afa.nq.gz
    ├── 47f7e5f57bcce943ded68e2f000c6861e5938faf.nq.gz
    ├── 480058f10dd6a8205d1bff0b94de7ae347a7629a.nq.gz
    ├── 48670bae6090f02b79d2ab43f17ad7fec0993b6e.nq.gz
    ├── 48c35c801efcf7c3d070a17e3018b58276a21ca3.nq.gz
    ├── 4b022cb26ffe1ce0457c8a367ae1f29915d0adef.nq.gz
    ├── 4b5b44f6968375c3feac5a76218836361b63aeb7.nq.gz
    ├── 4b979bcc1edcb33feb9b385156492221d92253dc.nq.gz
    ├── 4baa37451ff3c94884a2d56b63166a0d91939f76.nq.gz
    ├── 4c2bc07a8dfbb1ff2ac81b1b3447249539713a3c.nq.gz
    ├── 4cb53b91a5c20f2df891175478032d2aab6288a3.nq.gz
    ├── 4cbbc0e7922fd2176abaca8f155c4b458e33b0fe.nq.gz
    ├── 4d782ee361442e4aafeac7e371ab12789c8a3751.nq.gz
    ├── 4f1d54cd6b28d5daefe24e86891cc4cf81a3f893.nq.gz
    ├── 4fabbb20f20b24d456ba11a8ad247d9d43920d4f.nq.gz
    ├── 502e654a3774a159ddf20596d0036d65dd633110.nq.gz
    ├── 505c39f850922af375a12b130754e9ad6fb7fd02.nq.gz
    ├── 5133085a4356fff920d6052053d8d4ac8cc21b91.nq.gz
    ├── 515a7a5e44c763c6b14fd788ea15f5116514a31d.nq.gz
    ├── 519b1a682c512ad5ec40f5be1850669a7fc785ba.nq.gz
    ├── 523a8072d5bb69fbcae3fbc246277171180d5f9e.nq.gz
    ├── 52a888dd713ba5fe1ea2818b9c5356fd31eeb3ec.nq.gz
    ├── 52d1fa7d0be96447f5ee4074625eac1d3efee6b3.nq.gz
    ├── 5322e8f836ba73eb693723e7695272c3d521b5f8.nq.gz
    ├── 53a1c3a462c1b52423a00e7dbfb2838c78a7515c.nq.gz
    ├── 53db0f9be0f7f1871873e1bd1cd9d79a29373ab0.nq.gz
    ├── 546f4cf87becff3a119f6b19cb118126dcf6504c.nq.gz
    ├── 550c6ff6734cc0ab0af62ca70e4b6b58c174ab84.nq.gz
    ├── 566153fc9cb296fc7b07e3729569c8d4a7a8766d.nq.gz
    ├── 5727f2ff8b425c900a433bf37e496cde001a46b3.nq.gz
    ├── 57369e5216333c5f732f6abd56791cbadee1588f.nq.gz
    ├── 579132facc51c0d0a9c64597204b83149ff34132.nq.gz
    ├── 579fe9c023d3110799d9b04d5ebc56c9a5bde0f3.nq.gz
    ├── 583cc895d9345c93bd0be6ea5fb6a6d43d0d4dc7.nq.gz
    ├── 58afb9c945f30fe6e47fd75a17e9b6e6fc8633a2.nq.gz
    ├── 592ee38f0dec509dceadded39aa7f1684d853ff4.nq.gz
    ├── 5a4a0665663b93c02d5ce2e739f413b6b151a973.nq.gz
    ├── 5a9186236dc8dcd3dbbd29203f0d81d33a83f323.nq.gz
    ├── 5b4219eb2088dfe7fee8ffdb6a88f956cec950a2.nq.gz
    ├── 5b795d66890ad8406fff9fe73800be5f198b50d3.nq.gz
    ├── 5bb721439f1dde9c4c6bfb667a0c9869c4cce041.nq.gz
    ├── 5bd268c0a60be62ed5b8d667d61ac35bc4c2a6b8.nq.gz
    ├── 5bd618bd4590a0bc4b500ce5937a788135e02189.nq.gz
    ├── 5c23badba4e62837d0b6a3890180320dff4cac34.nq.gz
    ├── 5c5e168ab6bb1ee247ceaad422b289acd70808b1.nq.gz
    ├── 5d00dba5087372d7f207400653086eec63a7b838.nq.gz
    ├── 5d8b9fb8034e24286929e8e0910c6879a8300b45.nq.gz
    ├── 5e819df4f4263932c922a4e7631b0a26ce6f0a8f.nq.gz
    ├── 5ecb483506e0e8ae9452a3db0c462e513fb1d8b4.nq.gz
    ├── 5f1046c3e410a5c0e1f989f2fb6d2a3fab3466fe.nq.gz
    ├── 5fd6ead88a5b55b586e73d7885bfc2c44bcb0d48.nq.gz
    └── 5ff140bbb47f2ac68c86c0c3ea33ba79f17d7230.nq.gz

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

## Source repository

[pallets/click](https://github.com/pallets/click)

---
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*
