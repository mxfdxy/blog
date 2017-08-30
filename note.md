---
layout: default
---

# MySQL

## 存储引擎

### MyISAM
- 无事务特性
- 在大量数据中筛选迅速，适合选择密集的表
- 并发插入特性允许同时插入和删除，适合插入密集的表
- 根据表结构选择最佳格式类型
  - 静态
  - 动态
    - 尽量使用静态数据类型
    - 经常使用 OPTIMIZE TABLE 语句，整理表碎片，恢复由于表更新和删除而导致的空间丢失。
  - 压缩
    - 创建临时表，转换为压缩表。

### InnoDB
- 具有事务特性
- 更新密集的表
- 自动灾难恢复

### FAQ
- 在同一数据库中针对不同表的作用和行为选择适合的存储引擎，长远来看对应用程序来说是有益。

## 数据类型和属性

### 数据类型
- 日期和时间
  - date
  - datetime
  - time
  - timestamp
- 数值
  - bool 和 boolean 1字节
  - bigint 8字节
  - int 4字节
  - smallint 2字节
  - tinyint 1字节
  - mediumint 3字节
  - decimal
  - double 8字节
  - float 4字节
- 字符串
  - char
  - varchar
  - longblob
  - longtext
  - mediumblob
  - mediumtext
  - text
  - tinyblob
  - tinytext
  - enum
  - set

### 数据类型属性



## 事务特性

##


## 命令
- show engines;
