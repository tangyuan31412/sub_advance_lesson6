# Substrate进阶课程第六课作业

-为 proof of existence (poe) 模块的可调用函数 create_claim, revoke_claim, transfer_claim 添加 benchmark 用例，并且将 benchmark 运行的结果应用在可调用函数上；

```
    ./benchmarks-poe/pallets/poe/src/benchmarking.rs
    ./benchmarks-poe/pallets/poe/src/lib.rs
```

-选择 node-template 或者其它节点程序，生成 Chain Spec 文件（两种格式都需要）；

```
  ./substrate-stencil/tangyuan-staging.json
  ./substrate-stencil/tangyuan-staging-raw.json
```

