## 编译

```shell
mvn -Prelease-all -DskipTests clean install -U
```

## 启动nameserver

```properties
# 设置环境变量
ROCKETMQ_HOME=/Users/0xffff0/coding/java/read/read-rocketmq/distribution/target/rocketmq-4.9.2/rocketmq-4.9.2
```

## 启动broker

```properties
# 设置环境变量
ROCKETMQ_HOME=/Users/0xffff0/coding/java/read/read-rocketmq/distribution/target/rocketmq-4.9.2/rocketmq-4.9.2
# 设置程序参数
-n 127.0.0.1:9876
```

