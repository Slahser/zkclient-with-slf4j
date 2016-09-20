# 介绍

本项目是高锦科技目前使用的dubbox以来的zkclient

版本0.9a

主要工作是替换了默认写死的log4j实现,替换为slf4j协议.

以及默认loggerFactory选择替换为直接选择slf4j协议,自动托管到classpath下实现日志框架.

## 更改源代码

如何提交

```
本地安装
mvn clena install -Dmaven.test.skip=true

提交到高锦nexus
mvn deploy -Dmaven.test.skip=true

查看解决jar包依赖问题
mvn dependency:tree

```