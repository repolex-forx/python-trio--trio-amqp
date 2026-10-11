# Repolex Knowledge Graph of python-trio/trio-amqp

RDF knowledge graph data for [python-trio/trio-amqp](https://github.com/python-trio/trio-amqp), parsed by [repolex](https://repolex.ai).

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
rlex download python-trio/trio-amqp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9a572309e00db917590a579aacde8aea5d2e55b6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9a572309e00db917590a579aacde8aea5d2e55b6
│           └── chunk-001.nq.gz
├── blob
│   ├── 04e55ca700f7b989313834e330b2954c96054f49.nq.gz
│   ├── 08edf82c691a0bbbbfa9613a950da0b8ee7abad5.nq.gz
│   ├── 0d0a1d14d8227adc635e40ee6f972547dddfbdb2.nq.gz
│   ├── 10fd9c84f8f064668dfee7f286809d6adb5f0f77.nq.gz
│   ├── 15d5d41160248ed14275345d06b08e7addb56f66.nq.gz
│   ├── 163aaf8d82b6c54f23c45f32895dbdfdcc27b047.nq.gz
│   ├── 1a6add5d07b225dbd3fa24b5c11daa792ecb35b3.nq.gz
│   ├── 1cf884cb9bccb31be19d64a22444549826e2d69a.nq.gz
│   ├── 1ea92f1f5a4f80178dbf25586a57b61ee5dd0eb7.nq.gz
│   ├── 3309f5b1a11a9d38a9377e8bb8f0dddac5531b39.nq.gz
│   ├── 335519737fd0c79a5cd57ad86a7e369ab64413a4.nq.gz
│   ├── 38fa03d55ba474294b604dc6e7a989f7c18ff4e6.nq.gz
│   ├── 3c04e80456209899da29d2784b5030c9bda89828.nq.gz
│   ├── 4108bc0dd30b50db0134328068944542753504a6.nq.gz
│   ├── 46a45b6e6a2aa596a3a4def3c1414deeda4234a8.nq.gz
│   ├── 4c2f326ef08d92de666f30d1138785b6259ae676.nq.gz
│   ├── 4ce2fbde939c70d15f08d3e76e0bd8751087b274.nq.gz
│   ├── 50f8618288f1d5f9403711fa9eaca35c3591101a.nq.gz
│   ├── 520ce31558c606bfe963b8d50c951f7e9cf278f5.nq.gz
│   ├── 541a2296bd7b2be6e6226140559811443fdc0bcb.nq.gz
│   ├── 54b906fefe8d0eace8a438c7f96c5401e259534f.nq.gz
│   ├── 55ef31374488b3dbe7e8cdc495528e2bc451ed2a.nq.gz
│   ├── 5866bd6df77f5e28cc0da71ff54b8c6811cb2207.nq.gz
│   ├── 5a26a46ccbe428c6cfedebbf8b19aa6ec2aabc45.nq.gz
│   ├── 5c4a0610a24cf329aa5584e8c497d0111ddd3e22.nq.gz
│   ├── 5d5f15f703337cee1dc79d543d0e284016587f1a.nq.gz
│   ├── 5e19019f06b2c2272287f09878ad2e6dc2094ecc.nq.gz
│   ├── 5edfb0cba0494691f2089ea9ca7c8ff7cf7da8ec.nq.gz
│   ├── 653b1e24cbec62bf1a4bb5ab4d6d78321427e424.nq.gz
│   ├── 687e5f2fcaac03cdc55e99022b295a7c99bf56f1.nq.gz
│   ├── 6a4b30af6af97fe4bd83bfe8cbcb24d45e0df961.nq.gz
│   ├── 6cc7bb6f1b1386662d74ab5ee26528cd9dbb45bf.nq.gz
│   ├── 6ea8085e7dcee8929852e6c47d887cf2783b97eb.nq.gz
│   ├── 6edebd8a22e124ca92ddea9894aec3dbcaa3b549.nq.gz
│   ├── 71a187da626d42c561c362bbe8c0961917c2f25c.nq.gz
│   ├── 71c6d98f72e17622d0ac0c90c52f917f8d2a898f.nq.gz
│   ├── 72616d1682b83049265689b1bd4eb4a04560f426.nq.gz
│   ├── 7623f372ed37fcd4efe4d2ad96424bdfd73bd863.nq.gz
│   ├── 769af76680fffede90ef3377d117ad45a3e78519.nq.gz
│   ├── 7c3746215454e85593cc99ec12817a8124a4d4cc.nq.gz
│   ├── 7c6d5dae1ebc219675dc83bfa8ef188b2e782bbf.nq.gz
│   ├── 7f3d4a075ab44d6edde60f7d9e49b3ed3e47d3e1.nq.gz
│   ├── 82694a19421bbb607d00c1f1fdfcf06c40461894.nq.gz
│   ├── 8393578a2743af40585cd233f6d7935769036373.nq.gz
│   ├── 83b63da05e717372150d4109500c8e98cde93a4b.nq.gz
│   ├── 83f69e8b1580cd728eff454d30088bf9d4d28059.nq.gz
│   ├── 842ec8eee331b822b3f95b5752da187b1f7a52e5.nq.gz
│   ├── 858c39532ad2c917c98d8d12e19074ab1cd4ff35.nq.gz
│   ├── 8a9efc47377e916d7182f93ca430561122ee6339.nq.gz
│   ├── 8fc2731acb89f05041969fb4f7cc4e71f70eaaaa.nq.gz
│   ├── a295963440f3ad6b601a57ad43ca8271848d0c3a.nq.gz
│   ├── a8d0bcd68369d21149fe0f5ff99324c3bb8384a7.nq.gz
│   ├── ac61c0a1327faec3d4ae0f9342b4b6c31f2c3ab2.nq.gz
│   ├── ae990217732d35c043e4f23bd816bf7113b935fa.nq.gz
│   ├── af9541db15e8eff41e2c52ac46d5142e38bd69ce.nq.gz
│   ├── b1bd38b62a0800a4f6a80c34e21c5acffae52c7e.nq.gz
│   ├── b48b0fd5af96ac3828a7434e7b983398a37abfeb.nq.gz
│   ├── b73da50924072de020d7041a7a2f1ab828efc04c.nq.gz
│   ├── bb13b79512b89b46f1cb46be46a7900452650154.nq.gz
│   ├── bd45722f19b2fe5ae43a3df4aa62ca1b789ac49c.nq.gz
│   ├── c1a054c83a113a568df1915a5404e84cb01b91bb.nq.gz
│   ├── ca1856124437074372bb6af1c58a54ea8cbd0987.nq.gz
│   ├── cb9a201f96fba06da96a8ac28ded1e0f1d972027.nq.gz
│   ├── cbc8a0dc6e665ec758187fb6d14c7169cd6db389.nq.gz
│   ├── cbcc58d92660a0dcf9fcdb1db8429f6259858a88.nq.gz
│   ├── ce2f282f8187f669ce1c04d1c7da5ca3ee713821.nq.gz
│   ├── d2f16120d623df3fb18a1f6fd0414bff09d752e2.nq.gz
│   ├── da6abdf2ce977fc22ed876f6b16a95a7fa4341da.nq.gz
│   ├── dc8f417578eff6205692b6f8346ac07fd47ca0f6.nq.gz
│   ├── e2ab889c18de23ace5da7b53e5b4dffd8ddb7862.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8394f960a104d539b59ea29e54e118b8ba43951.nq.gz
│   ├── ecb590a69275d287c4c28926a97058f1cdd3e46e.nq.gz
│   ├── f17b3bb03f0bcb96c253b5418958bf12eeec159d.nq.gz
│   ├── f3849fbc511afafc08b67fb4b2f4fbcadf21bce1.nq.gz
│   ├── f6d6501bfe72d37f9c78acef47db859c73f3b12b.nq.gz
│   ├── f7077763507c3d1da336e6d1c79f0eb5512cb965.nq.gz
│   ├── f968bde9e6643dc2d190f2baac174eea76ec85ad.nq.gz
│   ├── f9d4994d271d511008899b9340835eb26d9d08b2.nq.gz
│   └── fabf35235890f4a269c1db9ab467328644e12a94.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9a572309e00db917590a579aacde8aea5d2e55b6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 88 files
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

[python-trio/trio-amqp](https://github.com/python-trio/trio-amqp)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
