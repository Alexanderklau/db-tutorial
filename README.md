<p align="center">
    <a href="https://dunwu.github.io/db-tutorial/" target="_blank" rel="noopener noreferrer">
        <img src="https://raw.githubusercontent.com/dunwu/images/dev/common/dunwu-logo-200.png" alt="logo" width="150px"/>
    </a>
</p>

<p align="center">
    <img src="https://badgen.net/github/license/dunwu/db-tutorial" alt="license">
    <img src="https://travis-ci.com/dunwu/db-tutorial.svg?branch=master" alt="build">
</p>

<h1 align="center">DB-TUTORIAL</h1>

> 💾 **db-tutorial** 是一个数据库教程。
>
> - 🔁 项目同步维护：[Github](https://github.com/dunwu/db-tutorial/) | [Gitee](https://gitee.com/turnon/db-tutorial/)
> - 📖 电子书阅读：[Github Pages](https://dunwu.github.io/db-tutorial/) | [Gitee Pages](https://turnon.gitee.io/db-tutorial/)

## 📖 内容

### 关系型数据库

> [关系型数据库](docs/sql) 整理主流关系型数据库知识点。

#### [共性知识](docs/sql/common)

- [关系型数据库面试总结](docs/sql/common/sql-interview.md) 💯
- [SQL Cheat Sheet](docs/sql/common/sql-cheat-sheet.md) 是一个 SQL 入门教程。
- [分布式存储基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/theory/distributed-storage.md)
- [分布式事务基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/theory/distributed-transaction.md)

#### [Mysql](docs/sql/mysql) 📚

![img](https://raw.githubusercontent.com/dunwu/images/dev/snap/20200716103611.png)

- [Mysql 应用指南](docs/sql/mysql/mysql-quickstart.md) ⚡
- [Mysql 工作流](docs/sql/mysql/mysql-index.md) - 关键词：`连接`、`缓存`、`语法分析`、`优化`、`执行引擎`、`redo log`、`bin log`、`两阶段提交`
- [Mysql 索引](docs/sql/mysql/mysql-index.md) - 关键词：`Hash`、`B 树`、`聚簇索引`、`回表`
- [Mysql 锁](docs/sql/mysql/mysql-lock.md) - 关键词：`乐观锁`、`表级锁`、`行级锁`、`意向锁`、`MVCC`、`Next-key 锁`
- [Mysql 事务](docs/sql/mysql/mysql-transaction.md) - 关键词：`ACID`、`AUTOCOMMIT`、`事务隔离级别`、`死锁`、`分布式事务`
- [Mysql 性能优化](docs/sql/mysql/mysql-optimization.md)
- [Mysql 运维](docs/sql/mysql/mysql-ops.md) 🔨
- [Mysql 配置](docs/sql/mysql/mysql-config.md)
- [Mysql 问题](docs/sql/mysql/mysql-faq.md)

#### 其他关系型数据库

- [H2 应用指南](docs/sql/h2.md)
- [SqLite 应用指南](docs/sql/sqlite.md)
- [PostgreSQL 应用指南](docs/sql/postgresql.md)

### Nosql 数据库

> [Nosql 数据库](docs/nosql) 整理主流 Nosql 数据库知识点。

- [Nosql 技术选型](docs/nosql/nosql-selection.md)

#### [Redis](docs/nosql/redis) 📚

![img](https://raw.githubusercontent.com/dunwu/images/dev/snap/20200713105627.png)

- [Redis 面试总结](docs/nosql/redis/redis-interview.md) 💯
- [Redis 应用指南](docs/nosql/redis/redis-quickstart.md) ⚡ - 关键词：`内存淘汰`、`事件`、`事务`、`管道`、`发布与订阅`
- [Redis 数据类型和应用](docs/nosql/redis/redis-datatype.md) - 关键词：`STRING`、`HASH`、`LIST`、`SET`、`ZSET`、`BitMap`、`HyperLogLog`、`Geo`
- [Redis 持久化](docs/nosql/redis/redis-persistence.md) - 关键词：`RDB`、`AOF`、`SAVE`、`BGSAVE`、`appendfsync`
- [Redis 复制](docs/nosql/redis/redis-replication.md) - 关键词：`SLAVEOF`、`SYNC`、`PSYNC`、`REPLCONF ACK`
- [Redis 哨兵](docs/nosql/redis/redis-sentinel.md) - 关键词：`Sentinel`、`PING`、`INFO`、`Raft`
- [Redis 集群](docs/nosql/redis/redis-cluster.md) - 关键词：`CLUSTER MEET`、`Hash slot`、`MOVED`、`ASK`、`SLAVEOF no one`、`redis-trib`
- [Redis 实战](docs/nosql/redis/redis-action.md) - 关键词：`缓存`、`分布式锁`、`布隆过滤器`
- [Redis 运维](docs/nosql/redis/redis-ops.md) 🔨 - 关键词：`安装`、`命令`、`集群`、`客户端`

#### Elasticsearch

> [Elasticsearch](docs/nosql/elasticsearch) 📚

- [Elasticsearch 面试总结](docs/nosql/elasticsearch/elasticsearch-interview.md) 💯
- [ElasticSearch 应用指南](docs/nosql/elasticsearch/elasticsearch-quickstart.md)
- [ElasticSearch API](docs/nosql/elasticsearch/elasticsearch-api.md)
- [ElasticSearch 运维](docs/nosql/elasticsearch/elasticsearch-ops.md)

#### HBase

> [HBase](https://dunwu.github.io/bigdata-tutorial/hbase) 📚 因为常用于大数据项目，所以将其文档和源码整理在 [bigdata-tutorial](https://dunwu.github.io/bigdata-tutorial/) 项目中。

- [HBase 原理](https://github.com/dunwu/bigdata-tutorial/blob/master/docs/hbase/HBase原理.md) ⚡
- [HBase 命令](https://github.com/dunwu/bigdata-tutorial/blob/master/docs/hbase/HBase命令.md)
- [HBase 应用](https://github.com/dunwu/bigdata-tutorial/blob/master/docs/hbase/HBase应用.md)
- [HBase 运维](https://github.com/dunwu/bigdata-tutorial/blob/master/docs/hbase/HBase运维.md)

#### [MongoDB](docs/nosql/mongodb) 📚

> MongoDB 是一个基于文档的分布式数据库，由 C++ 语言编写。旨在为 WEB 应用提供可扩展的高性能数据存储解决方案。
>
> MongoDB 是一个介于关系型数据库和非关系型数据库之间的产品。它是非关系数据库当中功能最丰富，最像关系数据库的。它支持的数据结构非常松散，是类似 json 的 bson 格式，因此可以存储比较复杂的数据类型。
>
> MongoDB 最大的特点是它支持的查询语言非常强大，其语法有点类似于面向对象的查询语言，几乎可以实现类似关系数据库单表查询的绝大部分功能，而且还支持对数据建立索引。

- [MongoDB 应用指南](docs/nosql/mongodb/mongodb-quickstart.md)
- [MongoDB 聚合操作](docs/nosql/mongodb/mongodb-aggregation.md)
- [MongoDB 建模](docs/nosql/mongodb/mongodb-model.md)
- [MongoDB 建模示例](docs/nosql/mongodb/mongodb-model-example.md)
- [MongoDB 索引](docs/nosql/mongodb/mongodb-index.md)
- [MongoDB 复制](docs/nosql/mongodb/mongodb-replication.md)
- [MongoDB 分片](docs/nosql/mongodb/mongodb-sharding.md)
- [MongoDB 运维](docs/nosql/mongodb/mongodb-ops.md)

### 中间件

- [版本管理中间件 flyway](docs/middleware/flyway.md)
- [分库分表中间件 ShardingSphere](docs/middleware/shardingsphere.md)

## 📚 资料

### Mysql 资料

- **官方**
  - [Mysql 官网](https://www.mysql.com/)
  - [Mysql 官方文档](https://dev.mysql.com/doc/refman/8.0/en/)
  - [Mysql 官方文档之命令行客户端](https://dev.mysql.com/doc/refman/8.0/en/mysql.html)
- **书籍**
  - [《高性能 MySQL》](https://book.douban.com/subject/23008813/) - 经典，适合 DBA 或作为开发者的参考手册
  - [《MySQL 必知必会》](https://book.douban.com/subject/3354490/) - 适合入门者
- **教程**
  - [runoob.com MySQL 教程](http://www.runoob.com/mysql/mysql-tutorial.html) - 入门级 SQL 教程
  - [mysql-tutorial](https://github.com/jaywcjlove/mysql-tutorial)
- **更多资源**
  - [awesome-mysql](https://github.com/jobbole/awesome-mysql-cn)

### Redis 资料

- **官网**
  - [Redis 官网](https://redis.io/)
  - [Redis github](https://github.com/antirez/redis)
  - [Redis 官方文档中文版](http://redis.cn/)
  - [Redis 命令参考](http://redisdoc.com/)
- **书籍**
  - [《Redis 实战》](https://item.jd.com/11791607.html)
  - [《Redis 设计与实现》](https://item.jd.com/11486101.html)
- **源码**
  - [《Redis 实战》配套 Python 源码](https://github.com/josiahcarlson/redis-in-action)
- **资源汇总**
  - [awesome-redis](https://github.com/JamzyWang/awesome-redis)
- **Redis Client**
  - [spring-data-redis 官方文档](https://docs.spring.io/spring-data/redis/docs/1.8.13.RELEASE/reference/html/)
  - [redisson 官方文档(中文,略有滞后)](https://github.com/redisson/redisson/wiki/%E7%9B%AE%E5%BD%95)
  - [redisson 官方文档(英文)](https://github.com/redisson/redisson/wiki/Table-of-Content)
  - [CRUG | Redisson PRO vs. Jedis: Which Is Faster? 翻译](https://www.jianshu.com/p/82f0d5abb002)
  - [redis 分布锁 Redisson 性能测试](https://blog.csdn.net/everlasting_188/article/details/51073505)

### MongoDB 资料

- **官方**
  - [MongoDB 官网](https://www.mongodb.com/)
  - [MongoDB Github](https://github.com/mongodb/mongo)
  - [MongoDB 官方免费教程](https://university.mongodb.com/)
- **教程**
  - [MongoDB 教程](https://www.runoob.com/mongodb/mongodb-tutorial.html)
  - [MongoDB 高手课](https://time.geekbang.org/course/intro/100040001)
- **数据**
  - [mongodb-json-files](https://github.com/ozlerhakan/mongodb-json-files)
- **文章**
  - [Introduction to MongoDB](https://www.slideshare.net/mdirolf/introduction-to-mongodb)

## 🚪 传送

◾ 🏠 [DB-TUTORIAL 首页](https://github.com/dunwu/db-tutorial) ◾ 🎯 [我的博客](https://github.com/dunwu/blog) ◾
