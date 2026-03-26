# Repolex Knowledge Graph of matrixorigin/memoria

RDF knowledge graph data for [matrixorigin/memoria](https://github.com/matrixorigin/memoria), parsed by [repolex](https://repolex.ai).

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
lexq download matrixorigin/memoria
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
└── blob
    ├── 0157034825ac20c8bc853e318a40389b79ca2a13.nq.gz
    ├── 0222ee89a1d808404929057b99109bd0b8f8880b.nq.gz
    ├── 0412785ea25dc2e2829f92289715bed254e0f049.nq.gz
    ├── 0424a458eae28938af1c80a7cb68f29045450578.nq.gz
    ├── 0539f3415fcb6d61c364d6a35eb0fffc8cea0247.nq.gz
    ├── 0557d2a6887fe25daae6cc6f0ca7f1dc50f57ee3.nq.gz
    ├── 085d24f434eb4915606939863ec695d7ee447cba.nq.gz
    ├── 0876e7344163c3ce3aa3f12f9d4262e2eb70c3a2.nq.gz
    ├── 0a2f5fb839ba9f0a1ecbad93f5f0c5d82f13d56e.nq.gz
    ├── 0a3d2f3d28cad4d51cf8cf7287f2833fadfbe112.nq.gz
    ├── 0ae87f2d94748ed9a100b828470426c57e932024.nq.gz
    ├── 0aeaa8470c384f3e5f6501c8a637f568e5a9ce8d.nq.gz
    ├── 0bc2197b5684b8d4e9711baec7a9ac3e355ccf5f.nq.gz
    ├── 0ca3f45b7369679515ab3fa9161aca3d82780683.nq.gz
    ├── 0cc88c0eb5698d6583c8a31a9dad577027f765ab.nq.gz
    ├── 0d202079e1157adca984849b6567a857b972e126.nq.gz
    ├── 0d602d3e158d2dee3ab8be81d78c444219501624.nq.gz
    ├── 0e5b16225888201ef843eebb3641b6377e542d14.nq.gz
    ├── 107ca989e14611124f26c46c7a902e3d3e5c0eae.nq.gz
    ├── 109aff337985259de83103682d218577bc7b7fd0.nq.gz
    ├── 10fa51693dce63aa7ac71f249700d7de436c8bac.nq.gz
    ├── 116a49ccad514e98b1133829a19174dab2db13ab.nq.gz
    ├── 117c009bcae41a4a8898713801c54f547fc15644.nq.gz
    ├── 11bca0480606ddae041abd50c57650bdace005dc.nq.gz
    ├── 1238a3e86f15169d0e6de2bb6c4b0a76c3f9d58c.nq.gz
    ├── 14ee0caeb48f4b8ea9780938a023199a8756d577.nq.gz
    ├── 150534d02f33131b49dea217b5a758d0f56a243b.nq.gz
    ├── 158bfcb40c00619cd1e8ea81a444f5e5248248dc.nq.gz
    ├── 18f543b3327f562f5e8e058533f589328ef745b2.nq.gz
    ├── 19b3a6f27c09798cbf466189ee0dec8cd4f69cae.nq.gz
    ├── 19e59028e1424c26a2baf8a239a91db2d2e8d029.nq.gz
    ├── 1bb841b9a130ab8ab2df7ad54a9c1c81cfe8b62d.nq.gz
    ├── 1c5069c88c3b5e5f8923880051aaad090eefe7e4.nq.gz
    ├── 1df4b22c847c93995d583027f7b70f04ae614c41.nq.gz
    ├── 1e1f97ebeee7d6fa4a5859a1411f0ebecdd14545.nq.gz
    ├── 1f93ed11a5bd7e51c88dfa5a3cd476ce919f2bb4.nq.gz
    ├── 1faa4c1721b42c65ccb1010835c00b943a5fda5f.nq.gz
    ├── 2286ee89030c0bbacea773a60d260e9785705459.nq.gz
    ├── 235fc0700046d4c64c0b659118ff76618a4805a0.nq.gz
    ├── 24ad30b830ec0735593d1067f20ef0fa1aeadb9f.nq.gz
    ├── 269485b044f77aeea3af3050353a93f7b249dfa6.nq.gz
    ├── 285f6f5a88fee6c43130df2f9e36d77f0389a617.nq.gz
    ├── 299438ae189bc71f195eff456e0d01e8f1678a95.nq.gz
    ├── 2b6d46718c997671ebafafb7220b566891b068fc.nq.gz
    ├── 2d03cc9b8cac32e78a9b36d71b7c34dc89529597.nq.gz
    ├── 2e6fec1c0dbc9da8c9f8142e37d5fd97e4ff8a41.nq.gz
    ├── 3007884c72523cfa69d43c250c829057896752c5.nq.gz
    ├── 327ca216ddf6421c603d6578e3de39c68c5e586a.nq.gz
    ├── 32cb6b34969ae4df4cadb6a6beb77aace7da7496.nq.gz
    ├── 33032ec2cedd4f25a5937f60d29f3cc61fa5ca89.nq.gz
    ├── 334e20d813d8e18fa8b26a5e3f1c671acab056da.nq.gz
    ├── 3487c010ca29b0dd7feeddbc38402f9eca51cb0d.nq.gz
    ├── 34d03023b9ad991960b37f912318e922a3d5500c.nq.gz
    ├── 34fb6cabed8b35c7f3e50672f1610c56d9204750.nq.gz
    ├── 36967449d35bda9ea6f83634daa7c9cb466b823f.nq.gz
    ├── 38b33470d2920dbebf3ecf94237914eb965e27d7.nq.gz
    ├── 391ee16b2bfd2205945a0d4e07ddffa34a90fcd2.nq.gz
    ├── 3960da3a56c448c1ed03ae2566425bc45858c1f4.nq.gz
    ├── 3971c2ff87b4ff58f5eacc4630afda245b538e64.nq.gz
    ├── 39e215bec5386e3c2838bdeec362fdc4e7eca42c.nq.gz
    ├── 3afecba5ac11d13af1c2f8e54a4e6b4498957aed.nq.gz
    ├── 3b745c6c80240db9dd339002dd32a2de2cbd18e6.nq.gz
    ├── 3b861c55d6a636ddd48d93fdb415fff92f8776a3.nq.gz
    ├── 3bcb60fc63721cb297f24a86a88bec7d7ed4cb8c.nq.gz
    ├── 3d9e4ebc125f0f52637dab8010d1d262f21a1acf.nq.gz
    ├── 3e306f3796f6cbfc707c5b305e97259aeafa3cb3.nq.gz
    ├── 3f3ce5833eaf1bf5b58d4074168f46685ebe2c43.nq.gz
    ├── 3f56de0007a6368021ea24931ebccb96cedb236f.nq.gz
    ├── 3fef5216520b13ca105803154dac3113702adb62.nq.gz
    ├── 40771ce475296e962e2b9a02f787372c6798a140.nq.gz
    ├── 40ff7ef02339b9c42f555274d3efbaafd251b6fe.nq.gz
    ├── 4246d39973f9e54e6d9f5421dce19771ee713e16.nq.gz
    ├── 42ee44063eb44b51183cb723658271d3eb9fc791.nq.gz
    ├── 4313d4461f3e132e8aae6328643ddbb53fb2a803.nq.gz
    ├── 44acb31b3ae1626f23c7b13ae4d3d932961523d4.nq.gz
    ├── 456cc90f0179021818d21bfb6f650bf9faf2f24e.nq.gz
    ├── 46149a6e45592c08068d425f073af441751671b8.nq.gz
    ├── 464529cba242d6bfc5a9e77c9afb46984668349d.nq.gz
    ├── 46a3a3f90c4030a027d209add4dc09f4627c1032.nq.gz
    ├── 4a2baaa4b9f18967efffac78d3e2c79b6d43005a.nq.gz
    ├── 4a8bb0375a256c17c87550a4d34e05726a4c5840.nq.gz
    ├── 4ab50874215b46e0a9f370d8493e89cd077367c2.nq.gz
    ├── 4b066f5dbb35916d794dff4c3d344e8529fe23cf.nq.gz
    ├── 4b3ddbeb67beb22b63e3d65527c7ed74bb508a53.nq.gz
    ├── 4e709e7676e222b484a64fe66aad5dfccfbd13cd.nq.gz
    ├── 4eb8ab2eb4cc120c4cb6b08efa97a90524a0766f.nq.gz
    ├── 4f5af4bf6dec22db6a8e953e92e2e779bd5d61b4.nq.gz
    ├── 4f5cee0bd07f732005227a7c861a1c1af341169a.nq.gz
    ├── 4f7fb8f9c31c48ed8644a1a2eaaf20e4bb500d79.nq.gz
    ├── 515468853902fd7719f8f7b7940444545aee5091.nq.gz
    ├── 545cb5f4f2e79ae721b4d8b670fb2c2c1bde4d4e.nq.gz
    ├── 5567f98812bdcf6b96237f8f2caabdaa15651dfd.nq.gz
    ├── 5602c1a256816b640ebfdfccd4f48e689998306c.nq.gz
    ├── 56923a66e521ebdfd2d215d0ef326a280fd56212.nq.gz
    ├── 581397d56b46c8c3fb414a669f04d0caed5c3400.nq.gz
    ├── 5f8b795830acbab5961c1a28c76a7916c9631493.nq.gz
    ├── 5fd71f38f0e784337e8bb6edf9bd28c007b1cbda.nq.gz
    ├── 5ff6ef07789aa62c78754d0b88f50b5b95d1f32c.nq.gz
    ├── 6012b11939d47bcc4a5238fb07943edafa880c7e.nq.gz
    ├── 613f8e702f5e47bfdc3126381b70c4603210dcbf.nq.gz
    ├── 61ecec95d4704bf31b99abf4de5b393192d7daa5.nq.gz
    ├── 620654dd915763fbda1e377794e7cfe46ba52a80.nq.gz
    ├── 63c7b0686d0352ac3b2ec5f92de36842b44cab02.nq.gz
    ├── 64eb98dc30a6f8b8eec79b05f6fc93c8cee3b75a.nq.gz
    ├── 64f2b82e112ac7d20d2db61c4e21b726e7a0bd54.nq.gz
    ├── 6624c3cbd4b3789377d7ff9645d45f7963fc4d79.nq.gz
    ├── 668b984875b42772f2e919b4fd5bd71d7fac7e4b.nq.gz
    ├── 67420c18de858dc5126b7c74a706e4d977cd363e.nq.gz
    ├── 6779ed8c01d21486519a2ec1581f320a938746ff.nq.gz
    ├── 682e4eacd784c01161065ee42b4052af313a212b.nq.gz
    ├── 685d5bfda71e4aed6b4203e928b810e678b6cbcb.nq.gz
    ├── 6a544625886f23bc6883dac80c1ad6a092aaaa01.nq.gz
    ├── 6bccdb3ca1ff674d904558df3525c2e06f4a25d2.nq.gz
    ├── 6e51e7b564d24f7e5c8256c377810170ab3e167b.nq.gz
    ├── 6e78243c7afd64d4870678cdc9c69ac3de45bfd2.nq.gz
    ├── 7103c946cee3839f4c835eeea0410c97b015d318.nq.gz
    ├── 7111bd03961864d0231e43fdcf160fd45ea15c48.nq.gz
    ├── 72ac854b20c5521b13c0325e6473e143c0540140.nq.gz
    ├── 72fcb0609f4232f5a12a0a2a4a0ad1a4752b2491.nq.gz
    ├── 732af8b6a51b3d232c40ada3a9c09480198f8c95.nq.gz
    ├── 76bda6d2bf764b8036d47f0d81a66692380b9384.nq.gz
    ├── 77d9d4e50c30109a0af7ce9b7c51b56baf4ed924.nq.gz
    ├── 783e5fa23624c2a69eda489261e6d49ea51058a1.nq.gz
    ├── 79090d382a797d04ae0571a65e59f231243cb61c.nq.gz
    ├── 792446e9f305c8d39b4091eebd31abf02a277b3f.nq.gz
    ├── 79767dc6027f84f621b0f3e1168c27242215b260.nq.gz
    ├── 79b55ace3cefc3ff3614c5e094e073afec44e605.nq.gz
    ├── 7a649cba4291f739992e7ecb336d31c36cf3820c.nq.gz
    ├── 7a69d230fc37b82ace2a55c2b14c90997333c349.nq.gz
    ├── 7aa14256f3f3d4282f7cb382f401138852fd8b46.nq.gz
    ├── 7d8c243d3604ec662752277f680d299feee41867.nq.gz
    ├── 7e073b20325e80dfaec4dab05278e65ff93b1f1c.nq.gz
    ├── 7f0fdaa0d80ebc90d47961d10d4e860761e1e900.nq.gz
    ├── 7f115fa73a247b64728a7ec161b6dfbddd059e76.nq.gz
    ├── 7f169d43809e2c2a0ef1086fac96a4a65d9d2d76.nq.gz
    ├── 7ff8294486277ea35442702420557451b3110b12.nq.gz
    ├── 8233e90893ca28b2a2a42520440bcb971647cf47.nq.gz
    ├── 84ffef2f15afb4d9f1daf7a20ddb5821b5a53573.nq.gz
    ├── 8562160a2a37d0586e036718cd9b976deb91c7c2.nq.gz
    ├── 85a9d84f961dd8b6d8e6da72af7620f973af752b.nq.gz
    ├── 861bf60855b35fa5a4815321c63b6c44fa469320.nq.gz
    ├── 87732cb40cfea72d38d069d7bab03bdc00295fc9.nq.gz
    ├── 87d867e010de1290ce211f103ee6000082b61ce2.nq.gz
    ├── 885c7ab9e9bda87ec2c5e0c71529075d91d37ce2.nq.gz
    ├── 8904cb580a29cc7770c87fce0b644150fc9382d3.nq.gz
    ├── 89de9a32cef498988c732c38bd5ea15e79af22ae.nq.gz
    ├── 8aec119deba8e5f465fb52aca495654d84d7c789.nq.gz
    ├── 8bd4d37f48af9dc6ff562efc87563650bb4f1582.nq.gz
    ├── 8cc949881fb0a605b69f51f264c6972755d98b8a.nq.gz
    ├── 8d24987a53e4392eecaa542b895b88150772d3e0.nq.gz
    ├── 8d36e231063336c4af2fa22d200044dee7ce973b.nq.gz
    ├── 8de8bdda08f0e2d4e95b4cc524e6848578f6efcb.nq.gz
    ├── 8f54cf10fe2e1a56bde3d0a71cd1ccf1c3662935.nq.gz
    ├── 90ccf65b436244499c01809f34c6678eb8d3262a.nq.gz
    ├── 91c1e51fa3fb45f64a128d603c3630eb17fe99ac.nq.gz
    ├── 91f0f87008e832fb0d8fd51901be6e6edda213f2.nq.gz
    ├── 926be77849cfdf0524139c51cde58b911e7d4afc.nq.gz
    ├── 9527413932b88e8e845514c107bc8a91fd1660bd.nq.gz
    ├── 9873b2094f3f3fa2ebf7042b30dd3eb0f98513a4.nq.gz
    ├── 99abae8062115b16c6db9068ba56c7dab76b6869.nq.gz
    ├── 99c0651fa8ccc38d375b930cf7b7b3a7d5867cda.nq.gz
    ├── 9ae6b3c9097fecf255d2e0e8d631e17d0eddd62c.nq.gz
    ├── 9bee2dacc7ddfd33944dc19be9e5056aca9ccfb6.nq.gz
    ├── 9d59be7fd94842387e9522c585b0da675c67defb.nq.gz
    ├── 9f4a2eafc58d5f48de55dac396214b10dd60b87e.nq.gz
    ├── a0d16ad9617bb690bf347a85ad846897be6c7b77.nq.gz
    ├── a0d62c37c284bae52e50f925fadf2fbae797f4c9.nq.gz
    ├── a15645e4c0084d23d573e13f4e3d7fa6bcf3c2b9.nq.gz
    ├── a25ee1d2f1ed5629187dabb2eeec00131978ea45.nq.gz
    ├── a32dd4aa456840e55c21f00a4084bd2bd9169eba.nq.gz
    ├── a41095606a913115ec155e85b134e7919eab6cf4.nq.gz
    ├── a5bc5065f71b1c08bde495d8c3386e91ed9cceb6.nq.gz
    ├── a72453a0688f70d690e412cebfc3f09dca390d2f.nq.gz
    ├── a7adb6f85d513662898c24d86b16e871ddbdc317.nq.gz
    ├── a80b233fc960dcc444938da5c8ee9c92233ab2dd.nq.gz
    ├── a90dc2b2e6737f506da1859dedcbbb4d1a06d769.nq.gz
    ├── a92f03108e95968d7168e4d3525c74ad081a1c35.nq.gz
    ├── a9979940956c6af8a5a091052f4fc4a27b50fd3b.nq.gz
    ├── a9c5cc581b2531921c7d31fae3712c45b3d7ea17.nq.gz
    ├── aba0b3f59e19180012f9b69f74954357157115f4.nq.gz
    ├── abd8894df595d4a8328423639474945b5f585311.nq.gz
    ├── ac6a9ee32043623370f47d9259818744e28ac3af.nq.gz
    ├── aca36af867709eceb5f4e3a21fb6cc42a65e3eec.nq.gz
    ├── ad61c1bee8768e2c02eee27647907b78a970a195.nq.gz
    ├── ad8646d4b86fcbd31a3ff0100b503e9388515472.nq.gz
    ├── ade079ad4e90b085f06f6671198bea25a9e64faa.nq.gz
    ├── aed01663aba3ffc26eb9a9e32ccd269360045bdd.nq.gz
    ├── aed3d50c8dcbc953b662bc11462bf1f8eeb0a86d.nq.gz
    ├── aeebf25a736ba3bbea5878d4e330e4c5f9ac2bf1.nq.gz
    ├── b1438af69db5be6d69387b0cf5ba17ef728b89a7.nq.gz
    ├── b1bae1950fbee36646e27c534bf1d5a318bf6758.nq.gz
    ├── b1caec37af5a3cead095e104a77fb3a4fc2285c5.nq.gz
    ├── b3533adb4261a6f04f9c50b3f6a6b9b88cb1d7a1.nq.gz
    ├── b47baa3554b02454c216f791f466e3b9f77e314a.nq.gz
    ├── b483ac2c86ae81e12570c2fbc8a77d879b231e70.nq.gz
    ├── b53dd1c6c1e51b93da5045886173ef8f2e80fd58.nq.gz
    ├── b549af5765a04f3431309fbbf4d5367cbd6379dd.nq.gz
    ├── b707e3fa59a48fdf756b9856ff9d6ef5328ddf36.nq.gz
    ├── b88f5c434a1d5f17b33aef294ca744f05773d15d.nq.gz
    └── b8ded66193bbaf0131393274c81e1a72559a364b.nq.gz

2 directories, 200 files
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

[matrixorigin/memoria](https://github.com/matrixorigin/memoria)

---
*Parsed on 2026-03-26 by [repolex](https://repolex.ai)*
