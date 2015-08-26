## dubbo-transaction 

```

dubbo服务间的分布式事物

```


### 业务场景

```

dubbo customer调用多个 dubbo provider 时具有事务性。整个调用过程中，任意一个 provider 出现事物异常，整个调用链中所有 provider 都回滚。

```

### 技术方案

[分布式事物](longtime.md)

[伪分布式事物](transition.md)

[轻事物](quick.md)

