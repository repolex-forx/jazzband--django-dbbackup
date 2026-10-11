# Repolex Knowledge Graph of jazzband/django-dbbackup

RDF knowledge graph data for [jazzband/django-dbbackup](https://github.com/jazzband/django-dbbackup), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-dbbackup
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6714cd0122483cd2ba79722764a51bedad6a9caa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6714cd0122483cd2ba79722764a51bedad6a9caa
│           └── chunk-001.nq.gz
├── blob
│   ├── 10ffec88f989e8b43b52f380b918733d789fea8f.nq.gz
│   ├── 14eb2777815f8b058321a71ec6a1746886b145f6.nq.gz
│   ├── 152ce15d96c3bd0f8c426d848c1e5c73a60374ac.nq.gz
│   ├── 16e5a05e0d68d8137efa15264ac5743093bf68e0.nq.gz
│   ├── 186ba710c50c0cba4ce59075e98eaea7c2fad490.nq.gz
│   ├── 1b1e16ba759d9c34ed630cdc5a51254d0119d6ef.nq.gz
│   ├── 1d7e7b2d39f847947bb4e550420b9d8fa9b19819.nq.gz
│   ├── 1f86459c723553ea007bc4e9851d0a0d4acf766c.nq.gz
│   ├── 1febcd9cfc207ebdcf1f8f9f5ba9c760b7c64846.nq.gz
│   ├── 25c7cc3120fe8d735a915f7a6f9da4d4b9a21872.nq.gz
│   ├── 29d75e0ed5cbe22c1cf38451dae92055e3139d96.nq.gz
│   ├── 2d1abc1e5828e7fd7f4d6aaa3eb7c719d6ad1b3f.nq.gz
│   ├── 31481e889dc679e4a814850573fc8940789d06fe.nq.gz
│   ├── 33dc7cf1985f4d043f26f5fdc74532366fcad312.nq.gz
│   ├── 367ca7c65b69f7cdd5d5d07d097b4eb0dea41572.nq.gz
│   ├── 3b05fe682f59d78e7a45bb7e6895cc54f726108c.nq.gz
│   ├── 3d6b58d87cf552184c2da2e78c27a974725a875f.nq.gz
│   ├── 3fe5060af7fdc235ae84d06dcfef413ecdde9ad5.nq.gz
│   ├── 404e5826bf72cc21eafdecd46d9932d816f8f84b.nq.gz
│   ├── 4174dde2a41da988de6cdaf2c3515faa90208634.nq.gz
│   ├── 443eebbc6ef02cdf1be4798172480b118741eedc.nq.gz
│   ├── 48dff4c86beed05e521a55091af32e851034888c.nq.gz
│   ├── 49f5e27bdc710f890cd36a7d288447d86ca9877d.nq.gz
│   ├── 4f9288ac25ba46d0eca6b43961582a4322c5969c.nq.gz
│   ├── 51cdea8a298c07ca367e36a77f67b02290884194.nq.gz
│   ├── 5430fd31001eb525848756bdaccbd18efcaea2a9.nq.gz
│   ├── 5714f77b72cedebe23fff85ec72871b01842e42d.nq.gz
│   ├── 5eab151764ef871da341d0e5b155998882979a77.nq.gz
│   ├── 60f00ef0ef347811e7b0c0921b7fda097acd9fcc.nq.gz
│   ├── 61a9a82b2fa620db59a23830f78a9472366e5b88.nq.gz
│   ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
│   ├── 675687bd78ca855830cd20dfad7e4848aa458bcb.nq.gz
│   ├── 6baeb259c9d10e1f870c4e598ee8eafb105b6f36.nq.gz
│   ├── 7332ae1e3be1e5d33b846ce7c10f7c3e2330b049.nq.gz
│   ├── 744d18addcc2fe33b78f55797626456565870b24.nq.gz
│   ├── 74f8772d80e9f4f21890ab86cd31539cb3be5926.nq.gz
│   ├── 74f9dada031acdf63f0ff65d05f9f02b6d6bf16d.nq.gz
│   ├── 75ffd8ddf4a5081a031309a3bca280ed40f953a8.nq.gz
│   ├── 76e0e454aebeb23f8819798ea6a2575525327093.nq.gz
│   ├── 775dedb0998b81e8e366ebda8fde89495a7dc0f8.nq.gz
│   ├── 85210a1cd165554b206951ddb24363a7f89f88a4.nq.gz
│   ├── 867df47c271f6f2599cf3e37849a0f0375949e9f.nq.gz
│   ├── 889af87e98d54726bec7c73051cae8ce2f6379ef.nq.gz
│   ├── 89c27298c076b6bea9d727f658d963b7da7460e6.nq.gz
│   ├── 8c84d4ea1d549554c11a5a2f5b96381ce62bb2c1.nq.gz
│   ├── 8e2de19f568619aa51168b4c12f4cea455aa1d76.nq.gz
│   ├── 935d30e5319a36be51a4a6876ee8a80c480b2328.nq.gz
│   ├── 946c66ee727b5a16a744292740ab2d2a95144bdc.nq.gz
│   ├── 9a143b4fb30f6be500ad08ea31e8d7c74b3010da.nq.gz
│   ├── 9acbc7b2decc7d28887d4dfe2742f59e8d3bbff1.nq.gz
│   ├── a0a6bb3871612e43ff274d180d83395295a34ac7.nq.gz
│   ├── a3b0017a15bc11ea88e529bb78127cdc71e6b67c.nq.gz
│   ├── a3ed707123d0a423bed1707d6977cb6e39845d38.nq.gz
│   ├── a55532008919c6bc7d0ffce98546761c7ad1f1be.nq.gz
│   ├── b0dd9a12e19c878ae177a350c3b4ca6e350f89b4.nq.gz
│   ├── b2b2df3fb55464431bd0c67a49252894d3f3bcf0.nq.gz
│   ├── b4c7d507ecb053c678956662269ea940fca7743a.nq.gz
│   ├── b5d13a2353edb74884e62022afe50490feaa9926.nq.gz
│   ├── b5d74b6a2aa288cf897b00560ebb5a66a1e1a30a.nq.gz
│   ├── b6739db30e30360c80281d023f2418e308b809b8.nq.gz
│   ├── bb2987e696bee65a737d538a5852642e214b2dfd.nq.gz
│   ├── bb5a22a3f5a2d4a3fe3926500d50e2907494115a.nq.gz
│   ├── c2859cdaf8e57f6cf9b782812197649ab3e097e9.nq.gz
│   ├── c3052e674e481be567d6f8d25ed0d8b9a96362f5.nq.gz
│   ├── c68f101f3c64d516b0881fee421e09fc1265a64c.nq.gz
│   ├── c7fd29eb102c622f457c48dd6c247af7f5c68d59.nq.gz
│   ├── c97f3f10fff84d296aa578814b84ba2feda65e09.nq.gz
│   ├── cafac717582f352cc6187c1b5509807cae649449.nq.gz
│   ├── cb1ad4ff672f68757d730b880b55c469274af874.nq.gz
│   ├── d06448eaa8e3bc71148521398cbdf65c9f207a57.nq.gz
│   ├── d0f105f64cf506f12580eaab01a9374ceb35fb77.nq.gz
│   ├── d3caf0eea400f7555d866106647e87d7f4b455ae.nq.gz
│   ├── d710e28c45b674056bd7d62ca7e7d745a19c9d55.nq.gz
│   ├── da51fe17906ebe0e0436d2149f1d4e660aae6a62.nq.gz
│   ├── dede78ecf419e82df5f5acd1190e921fb7a7d4fd.nq.gz
│   ├── e0361bd2e14bf194fa00bedf246c538606804621.nq.gz
│   ├── e191fd7ab1b92bc1ee98f6d40017b19084d9087f.nq.gz
│   ├── e4cde87829df8a8bc929c94872fc0ba50eb09d84.nq.gz
│   ├── e67280dada8d8f7d3541d4be586cc350a16dc7d0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6f49d96e5ffb2d42ac269bdf77a20b9b97bfe55.nq.gz
│   ├── eae698a762c08c57b1b7599fa1bbb6e7c3094313.nq.gz
│   ├── ec5603048345614c84ed5a55681b764acde2a9e6.nq.gz
│   ├── ecc159c2281732dd9d627a26fc97fd28a97b7f40.nq.gz
│   ├── ecf68260e8b511809dba4fb47df768fd70b137db.nq.gz
│   ├── ed81fb8a38e93b4e2294c0c9a8294e541e119030.nq.gz
│   ├── edac41a7840d1f67a462ffed5cb75bc709dd129a.nq.gz
│   ├── edcf6f2781d57c748e87e58e401c0a2d2ee998e8.nq.gz
│   ├── f0f0503afafe9769313a6244025213839d277c81.nq.gz
│   ├── f16c4dc42cc0e54424686ccd16863d46f17c04f5.nq.gz
│   ├── f26e3b73e581f84a7cb58635c5b6b2534a255bac.nq.gz
│   ├── f737ca16e86cf18a407c905f1fe7a62c018ce2a4.nq.gz
│   └── f8ae8e565c6806815097e01fb0f7fbd4bb2881c3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6714cd0122483cd2ba79722764a51bedad6a9caa.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 101 files
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

[jazzband/django-dbbackup](https://github.com/jazzband/django-dbbackup)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
