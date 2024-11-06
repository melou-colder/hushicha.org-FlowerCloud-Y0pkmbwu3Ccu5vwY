## 思维导航

* [前言](https://github.com)
* [Garnet](https://github.com)
* [LiteDB](https://github.com)
* [优秀项目和框架精选](https://github.com)

## 前言


今天大姚给大家分享2款使用.NET开发且开源的数据库系统。


## Garnet


Garnet是一款由微软研究院基于.NET开源的高性能、跨平台的分布式缓存存储数据库，该项目提供强大的性能（吞吐量和延迟）、可扩展性、存储、恢复、集群分片、密钥迁移和复制功能。并且无需做任何修改可以与现有的 Redis 客户端配合使用。


* 开源地址：[https://github.com/microsoft/garnet](https://github.com):[蓝猫机场](https://fenfang.org)
* 详细介绍：[https://mp.weixin.qq.com/s/C58UE7\_\_M2lJGeYVRmlidw](https://github.com)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241105193713461-1151547707.png)


### 项目特性


* 协议兼容性： Garnet 采用流行的 RESP 线路协议作为起点，这使得可以从当今大多数编程语言（例如C\#中的 StackExchange.Redis）中可用的未经修改的 Redis 客户端使用 Garnet。
* 性能优势： 相比同类开源缓存存储，Garnet在处理多客户端连接和小批量请求时表现更优，提供更好的吞吐量和可扩展性，从而节省成本。
* 低延迟： 在Azure VM上展示了极低的客户端延迟，通常低于300微秒，对于实际场景至关重要。
* 技术特点： 基于最新的.NET技术，具有跨平台、可扩展和现代化的特点，易于开发和维护，并在Linux和Windows上实现了最先进的性能。


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241105193730339-123286732.png)


## LiteDB


LiteDB 是一个小巧、快速和轻量级的 .NET 开源且免费（MIT License）的 NoSQL 嵌入式数据库。


* 开源地址：[https://github.com/mbdavid/LiteDB](https://github.com)
* 详细介绍：[https://mp.weixin.qq.com/s/Rq8z17ZmP\_Cx\_yGfcgeN\_A](https://github.com)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241105193749921-1655578600.png)


### 项目特性


* 无服务器的 NoSQL 文档存储。
* 简单的 API，类似于 MongoDB。
* 100% 的 C\# 代码支持 .NET 4\.5 / NETStandard 1\.3/2\.0，以单个 DLL（不到 450KB）形式提供。
* 单一数据文件存储（类似于 SQLite）。
* 对文档字段建立索引以实现快速搜索。
* 提供类似于 SQL 的命令来访问/转换数据。
* LiteDB Studio \- 数据访问的精美用户界面。
* 开源且免费供所有人使用，包括商业用途。


## 优秀项目和框架精选


本文项目都已收录到C\#/.NET/.NET Core优秀项目和框架精选中，关注优秀项目和框架精选能让你及时了解C\#、.NET和.NET Core领域的最新动态和最佳实践，提高开发工作效率和质量。坑已挖，欢迎大家踊跃提交PR推荐或自荐（让优秀的项目和框架不被埋没🤞）。


* GitHub开源地址：[https://github.com/YSGStudyHards/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md](https://github.com)
* Gitee开源地址：[https://gitee.com/ysgdaydayup/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md](https://github.com)


