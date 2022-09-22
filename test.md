# 1.文档编写目的

Cloudera与Hortonworks合并以后，开始打造基于CDH和HDP的合集新产品CDP7，CDP7是基于Hadoop3同时包含大量其他组件的大版本更新的发布版本，Cloudera于2019年11月23日正式发布Cloudera Data Center7.0.3，并于2020年5月底发布CDP7.1.1，截至2020年12月9日，最新版本为CDP7.1.5。考虑到C5会于2020年12月31日停止更新，C6也只能再支持到2021年的3月，许多用户最近会开始考虑从CDH5升级至CDP7。本文主要描述如何从CDH5.16.2原地升级至CDP7.1.4。

- 测试环境
  1. CDH5.16.2
  2. Redhat7.6
  3. Kerberos+Sentry已开启
