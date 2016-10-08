# 介绍

本项目替换默认zkclient内日志框架为slf4j规范,并且将项目迁移到maven上.

版本0.9a

默认loggerFactory选择替换为直接选择slf4j协议,自动托管到classpath下实现日志框架.

## 更改源代码

如何提交

```
本地安装
mvn clena install -Dmaven.test.skip=true

提交到nexus
mvn deploy -Dmaven.test.skip=true

查看解决jar包依赖问题
mvn dependency:tree

```
