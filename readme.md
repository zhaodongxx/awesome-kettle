# Awesome Kettle [![Kettle](https://img.shields.io/badge/kettle-v7.1-orange.svg)](https://help.pentaho.com/Documentation/7.1) 

## 索引
<!-- TOC -->
- [案例](#案例)
- [文章](#文章)
- [资源](#资源)
- [FAQ](#FAQ)
  - [连接MySQL数据库失败](#连接MySQL数据库失败)
<!-- /TOC -->

## 案例
- [使用Kettle实现数据实时增量同步](./案例/01_使用Kettle实现数据实时增量同步)

## 文章
- [kettle下转移mongo中数据到mysql中](https://segmentfault.com/a/1190000008762560)

## 资源
- [Pentaho Kettle解决方案：使用PDI构建开源ETL解决方案.pdf](https://pan.baidu.com/s/1tuT7HzwSXo6Dmte6R03ngg)

## FAQ

### 连接MySQL数据库失败
> 下载jar包`mysql-connector-java-5.1.15-bin.jar`,放在Kettle安装目录`./lib/`,重启Spoon.sh就可以连接MySQL数据库。