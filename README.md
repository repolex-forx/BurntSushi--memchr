# Repolex Knowledge Graph of BurntSushi/memchr

RDF knowledge graph data for [BurntSushi/memchr](https://github.com/BurntSushi/memchr), parsed by [repolex](https://repolex.ai).

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
lexq download BurntSushi/memchr
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 886ca4ca4820297191c6e9f7b023dc356f31a4d1
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 886ca4ca4820297191c6e9f7b023dc356f31a4d1.nq.gz
│   └── repolex
│       └── 886ca4ca4820297191c6e9f7b023dc356f31a4d1
│           └── chunk-001.nq.gz
├── blob
│   ├── 00038a7cdc1c9988407d5b8ec12103c8055c1503.nq.gz
│   ├── 000676d7e6f32eb3ce6d6131ee8b88779285c5b3.nq.gz
│   ├── 01da2e45ed0094b73c811beca569cd20bd37bdeb.nq.gz
│   ├── 0355fc8d07886252e0f83c55cedda17005a17f2d.nq.gz
│   ├── 03e2d9c9765b36d00ccc995e3e761188a45b0185.nq.gz
│   ├── 04c12958ec2db19157e43020cb64f643cda614eb.nq.gz
│   ├── 0564ad4fbb8a19fd269b1aa658a6e93c6b9c633b.nq.gz
│   ├── 064f8b21039a2e5086bf410258476887478c1a59.nq.gz
│   ├── 07da6ae4e76a60141b79907de5ead33dcd859111.nq.gz
│   ├── 0c6e1b146d3b97cb284e5a813dd541aaeebe2ba3.nq.gz
│   ├── 0c7901909b63cdd04e95a3fcb3c560e7b2a5ad86.nq.gz
│   ├── 0df3b4a86e950c8e97e51a29da088ca26b5ca31d.nq.gz
│   ├── 10332b64cd52908335a994f77ff1385d17eab6bf.nq.gz
│   ├── 107b0d2c71a4f21e7daa7c22ae3425ded981204c.nq.gz
│   ├── 11a5abd0956d941f111ebc66048af0a362db6e66.nq.gz
│   ├── 132ae617c3233a08ae9b1dc9c9b05248f7a00b85.nq.gz
│   ├── 138c28d0f6a6b1c51fc2ab3986f65387063d8129.nq.gz
│   ├── 145f8077b5aeefefe48e4f5aefcce56f6a3c9e84.nq.gz
│   ├── 148a985521d817c99708f91c6fb82a9f874fe8da.nq.gz
│   ├── 1a2dc594f9c37448141e36aea547b985b88d9b29.nq.gz
│   ├── 1bc6009849f12d3ce1b696ebcb9ddcbcb171b239.nq.gz
│   ├── 1fc3a57c63a3faf4434c665ba7cf854b58510364.nq.gz
│   ├── 204635b83ea9c1485c19a361352ace0480b676c4.nq.gz
│   ├── 209f876cb58376aaa7c077498050d8d6ea429c5c.nq.gz
│   ├── 259b67827a142276efce7954eda07acb8b03b6ef.nq.gz
│   ├── 25b72cc647a1d69bf036c423265d78ef02103cee.nq.gz
│   ├── 26ef2c5778b2c61ede8aa62e292301e9279b9e74.nq.gz
│   ├── 2869fec98f72fbe4b7ea36d5128ee1650cb34370.nq.gz
│   ├── 2a533e02fcf6d834ee7a6adb169e01cb28b518c2.nq.gz
│   ├── 305061fc6714d03d8b8419c489bd39cecae71529.nq.gz
│   ├── 308e359e0ff0a4b01064bcabcd94a2c424b544b6.nq.gz
│   ├── 31b4ca3816ace287913339ed02eb65ca41b1aa85.nq.gz
│   ├── 335f4f58e833ff51761ed5d32804d5ea2a49b6a4.nq.gz
│   ├── 3483c04dc39640e2c30f16d4ddaeb589be8c2157.nq.gz
│   ├── 355cbc7e2908c5f7757edc11344862204089a365.nq.gz
│   ├── 369ee05f4926f03a6ff70c0ea94878f1fdae247b.nq.gz
│   ├── 36e57de0298cdb9b7f354a8fd65975dfaeabf562.nq.gz
│   ├── 37eeca7b7d56710c2a1769752e2401fd770db706.nq.gz
│   ├── 38f35ced55fc24407b8dfce25b953ba6db7dfd38.nq.gz
│   ├── 3b0a5dc09c1e16357459ddc9182a50f360f3cdba.nq.gz
│   ├── 47ec4742e04a7478a88952af6cf22e5770852dd4.nq.gz
│   ├── 495a0179ffbac8dd882b64d77a3f86e46214957f.nq.gz
│   ├── 497ff86064c216502d477fcc4869bbd052b2dd00.nq.gz
│   ├── 49a5769d36da3995f0fce8ead554742befef8307.nq.gz
│   ├── 4ae25a1fe64d114e819a2fd6df8a485c9107e6fb.nq.gz
│   ├── 4b96df7fae8ee03cde9e44b0730067803b965b73.nq.gz
│   ├── 51e917ad2b1a43acc56da215ed094b206f2a7202.nq.gz
│   ├── 5306f9760f9a013f6bbc29832947e71330f280b5.nq.gz
│   ├── 54bef6bd40d57d44d3e3bbb16ed4e0927b25b24c.nq.gz
│   ├── 559cb75104d03a1d5f88b26f8bc3ce1e90dec766.nq.gz
│   ├── 55c1c1bb472f10571b5944b91233eb14a5cd20b3.nq.gz
│   ├── 583a0824c0b53f27829088a84bb9e251a9490544.nq.gz
│   ├── 58a510f08cebf4718be4a6a47f57892f11e9d8db.nq.gz
│   ├── 59f8c7f7382028b9cb155e4034b490a732c71f11.nq.gz
│   ├── 5b86454ae76350fee500e634ead255eba6cec305.nq.gz
│   ├── 5cc2a029697b886a29a742ad9258cd1dfba74e7d.nq.gz
│   ├── 5dad7218216b79a31e3d877e9c7f6669ec8a0338.nq.gz
│   ├── 5fcc76237bad136747ea34fcfef41f2048f97085.nq.gz
│   ├── 62804bd37287f9fb424d79665c2a62fa5e450c61.nq.gz
│   ├── 63ee3f0b34ed96a7c935fdaf5730c9a04aeaee8b.nq.gz
│   ├── 644543629ccb4ef379d97206f9124a3e3378a8b4.nq.gz
│   ├── 68a49daad8ff7e35068f2b7a97d643aab440eaec.nq.gz
│   ├── 69f2af01b46a44f7c0d3099fdb4e2b017f1193b6.nq.gz
│   ├── 6aa3895e61ef77b287047058349f2fd88d4233e0.nq.gz
│   ├── 6dccb35757f8f74510b840fd9197cdfc617c5f7d.nq.gz
│   ├── 6ebcdaea72a7fd3c965a63e62809a8dcac3c94d2.nq.gz
│   ├── 74749534c17830971bf12f60a8466011477efc94.nq.gz
│   ├── 77b7adcf56c7963d4d8074bce7806847d894aa85.nq.gz
│   ├── 79572b82b1c618598d0183e346c1e4db0439f55d.nq.gz
│   ├── 7a4c0346e3d734ed74d59362d100c76663f641d8.nq.gz
│   ├── 7b3291257b9360521d888332b085b57669d72e83.nq.gz
│   ├── 7c9f052e9a9db1242b00c4dd17174bef61a96a20.nq.gz
│   ├── 7eb85bb02ffbacace9c263d9c3e727cb8e319e86.nq.gz
│   ├── 7f0daf33a5dce5f68e22ff6f460ad7731f74cacb.nq.gz
│   ├── 7f327f86f45732e00f170bba0e8122ec64723b0b.nq.gz
│   ├── 802697ab34cc0c5b701b9396d9083d6613f4d24a.nq.gz
│   ├── 803850395a6dde0306061c9fc2098c8baf722803.nq.gz
│   ├── 84a53d7530ad4a758e6da383a52cff836881d34a.nq.gz
│   ├── 8628b898bab10062ecc03b789889020483fae129.nq.gz
│   ├── 87946a6a5a42d76a5ed33ac858fe862c23fcc1c5.nq.gz
│   ├── 896f9306139b638565e8e0e274a9b76b504609b7.nq.gz
│   ├── 89e83b4c895dec7aa4324bfd5b42994c1a3b8274.nq.gz
│   ├── 8d97cf28fad117c1f468e6feab7717209ac6ca61.nq.gz
│   ├── 92358a8d8c9662525db8a03fd5293fb44b921607.nq.gz
│   ├── 92a18bd5fa9c352319497e813e4376c5077821e9.nq.gz
│   ├── 949ef1f15abc566d9222aaee88c79fcc09c481fd.nq.gz
│   ├── 962bebb6bafd324396bd6f2370acd02f13b8f4ea.nq.gz
│   ├── 9674a6ccd58d9bf8fc8c85e33fc96836d58d764d.nq.gz
│   ├── 9b933d4ef54347c75f65324e117225b5173e1508.nq.gz
│   ├── 9d72ef2987dc67a3f1d2b74cd6c93c2651c64f36.nq.gz
│   ├── a076946e79d5db63717650276f2dac14d31814d3.nq.gz
│   ├── a7020efaac7bbf42c3d586f530a70498dbbb6451.nq.gz
│   ├── a818ab29daaa6f7dc9704ff92f2d831ec85dd3f3.nq.gz
│   ├── a8352ec74c5acc1402bd0c185ff9482716a77d74.nq.gz
│   ├── aa37a218b97e5f6ad37a74a62b50727279a5e460.nq.gz
│   ├── aa6d8be66401cc2b74bf869a98ec49a46d4d0f42.nq.gz
│   ├── ae546b563adea7b92c22a33fd8fbf8dc27a308ac.nq.gz
│   ├── b0547fcedc184e4b400b8a8d184ddb7ce1de6623.nq.gz
│   ├── b3105169cc1dd8fb433b1699b723347e9670a8e5.nq.gz
│   ├── b48cbccce23d604fd9ec2c144ea3f4057522acf3.nq.gz
│   ├── b4c978532b2d091aafec088042cf7bf01d8842bd.nq.gz
│   ├── b55d1f07b074060395815e4d8865d84006b8c7f5.nq.gz
│   ├── b690564a642e9d4275a474426951c0385f39905b.nq.gz
│   ├── b743cbb0b7b9232bc2fb7ab34ad36ca9fe2b8735.nq.gz
│   ├── b7fa0a7f34fd66bc4bdc100432d406016904c156.nq.gz
│   ├── bafd891ec25ff2637e10a112f4f436c1c743174f.nq.gz
│   ├── bb9c20a094e41b7632d63bcff20c0b4b95e80777.nq.gz
│   ├── bc1b14b292f4506d69cc123d0ddde42f0e3422d2.nq.gz
│   ├── bcb830790fbbaaebef528806a2bd00bf8987f6fe.nq.gz
│   ├── bfe58edc7185b0ebb27070aa0eecc9e6f3d4b206.nq.gz
│   ├── c304b4c26ee3bc1348e519d0550495be3445a0c3.nq.gz
│   ├── c4c3130503be874ea869ec4b2478071c15072a07.nq.gz
│   ├── c535f7b5ef82aad0127f06f236a46b29aeeb035c.nq.gz
│   ├── c8b5b9999b63cddf6f4aa66599b4b5eadff647f1.nq.gz
│   ├── cb19de1be78ebb80da7d31828f951a51080b1ca3.nq.gz
│   ├── cbb64c094dfe41c0c870b3a494f23f4df120e70f.nq.gz
│   ├── ccf9cf81f4bf47fb9271075d3ddaf2149fe325fc.nq.gz
│   ├── ce6eed2f5d84a89cd65393a716d61ecfb0c61731.nq.gz
│   ├── d1b8f14d9432e981ed6cf54ed1d94b7939451ffb.nq.gz
│   ├── d1dd208080dc33ba5376df1b81de8df707c1f31c.nq.gz
│   ├── d6658bf09545b1980e00bbe1edc411a3d834ca0b.nq.gz
│   ├── d6d084250700acd568177c87c4bf10eba3d05647.nq.gz
│   ├── d73ae77e1860fe1355632355cf1cb17f3b504035.nq.gz
│   ├── d806cc6cd04a5b7df24d8a4626ad07b4df9edf1e.nq.gz
│   ├── db00ebbc9356485fe1b2aa471513338259981b49.nq.gz
│   ├── dd10cbdd4b32c54f5ce91120b07a4eb7d2579249.nq.gz
│   ├── dd5dfa8cd0a0f747632d7d18f1c47003f7b95d72.nq.gz
│   ├── de61fd81d8b24e40d92168df92e3a57cffe313ab.nq.gz
│   ├── df5631c57e2b69d581c785d0337ab9fcb277b885.nq.gz
│   ├── e0053b2a2205b7e2627f4b84a765a53cc49b81ed.nq.gz
│   ├── e0b1b782a1ab492c80463790d5fbf94709d4ccd4.nq.gz
│   ├── e0bafbac9829509e7ad2786abe981fb5fec254bb.nq.gz
│   ├── e429753e881516ba239dd89480e3804d48b3d8a2.nq.gz
│   ├── e7e0d09a7013aa1f4518f95e90d539732dfb25a1.nq.gz
│   ├── e84d8f34b7855734752c305cc07a3593641cf98c.nq.gz
│   ├── e89248a28c7b418cf26401e308fd7e2e74dae9e9.nq.gz
│   ├── e8cf745a8feb77e27993b23ce0d7c4d98c30156c.nq.gz
│   ├── ea8c4bf7f35f6f77f75d92ad8ce8349f6e81ddba.nq.gz
│   ├── eafedc7225960229ced7c2bdbc30796c4ca81e6b.nq.gz
│   ├── edb6d431d973042a41787da705264ad51ccea0ff.nq.gz
│   ├── ee4097d6f4c34d0939f7f06195e1619aaed6e7f4.nq.gz
│   ├── eecc4ddb958e6d8f5a152683c88ab9cac26e97f5.nq.gz
│   ├── ef8788de79313746df262a59bd5408ae592f3bdf.nq.gz
│   ├── efae7b66c72c5b9f0a6115595fbd4ad2bac2bdd8.nq.gz
│   ├── efae927f64fe7275cf151c3a05aae86446fc28ba.nq.gz
│   ├── f4abd19bd5017133973c2faee3dd0d96b531ec14.nq.gz
│   ├── fa314c9d18aa6ff8991fc82b22292378eb2e4853.nq.gz
│   ├── fb9ecaf5d98d35ccbb3109fc31ef740e30fa0d51.nq.gz
│   └── fe67d5b1fa06cc9bd517497cad4ee4c3bd7e738b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 886ca4ca4820297191c6e9f7b023dc356f31a4d1.nq.gz
├── filetree
│   └── 886ca4ca4820297191c6e9f7b023dc356f31a4d1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 159 files
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

[BurntSushi/memchr](https://github.com/BurntSushi/memchr)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*
