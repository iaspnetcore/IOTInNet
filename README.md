# SmartHome
# Smart Home开发者指南

## Contents

* [General](#general)
* [Home Assistant](#Home-Assistant)
  * [Title](#Title-SEO)
  * [Body](#body)
  * [Header](#header)
  * [Body body](#Body-body)
  * [Url](#url)
  * [Microdata](#Microdata)
  * [Build Automation](#build-automation)
  * [Bundling and Minification](#bundling-and-minification)
  * [Caching](#caching)
  * [CMS](#cms)
  * [Code Analysis and Metrics](#code-analysis-and-metrics)  
  * [Compression](#compression)
  * [Compilers, Transpilers and Languages](#compilers-transpilers-and-languages)
  * [Cryptography](#cryptography)
  * [Database](#database)
  * [Database Drivers](#database-drivers)
  * [Database Tools and Utilities](#database-tools-and-utilities)
  * [Date and Time](#date-and-time)
  * [Distributed Computing](#distributed-computing)
  * [E-Commerce and Payments](#e-commerce-and-payments)
  * [Exceptions](#exceptions)
  * [Functional Programming](#functional-programming)
  * [Graphics](#graphics)
  * [GUI](#gui)
  * [IDE](#ide)
  * [Internationalization](#internationalization)
  * [IOC](#ioc)
  * [Logging](#logging)
  * [Machine Learning and Data Science](#machine-learning-and-data-science)
  * [Mail](#mail)
  * [Mathematics](#mathematics)
  * [Media](#media)
  * [Networking](#networking)
  * [Misc](#misc)
  * [Office](#office)
  * [ORM](#orm)
  * [Profiling](#profiling)
  * [Queue and Messaging](#queue-and-messaging)
  * [Query Builders](#query-builders)
  * [Scheduler and Job](#scheduler-and-job)
  * [SDKs](#sdks)
  * [Security](#security)
  * [Searching](#searching)
  * [Serialization](#serialization)
  * [Template Engine](#template-engine)
  * [Testing](#testing)
  * [Tools](#tools)
  * [Web Framework](#web-framework)
  * [Web Socket](#web-socket)
  * [Windows Service](#windows-service)
  * [Workflow](#workflow)
* [Nopcommerce 4.3x Seo](#Nopcommerce)
* [Starter Kits](#starter-kits)
* [Sample Projects](#sample-projects)
* [Articles](#articles)
* [Books](#books)
* [Videos](#videos)
* [Podcasts](#podcasts)
* [SEO Site Checkup](#community)


## 资源

1. 先决条件

   - [C#](https://www.pluralsight.com/paths/csharp)
   - [Entity Framework](https://www.pluralsight.com/search?q=entity%20framework%20core)
   - [ASP.NET Core](https://www.pluralsight.com/search?q=asp.net%20core)
   - SQL基础知识

2. 通用开发技能

   - FRP+WoL实现远程开机+树莓派 + 远程桌面 https://www.cnblogs.com/thecatcher/p/13210748.html
   - 掌握HTTP(S)协议, 及其请求方法(GET, POST, PUT, PATCH, DELETE, OPTIONS)
   - 不要害怕使用 Google, [Google搜索技巧](http://www.powersearchingwithgoogle.com/)
   - 学习[dotnet CLI](https://docs.microsoft.com/zh-cn/dotnet/core/tools/?tabs=netcore2x)
   - 阅读一些关于算法和数据结构的书籍

3. IOT 平台

   1.  国内IOT平台
      - [阿里云 IOT](https://iot.aliyun.com/)
      - [华为物联网](https://developer.huawei.com/ict/cn/site-iot-next)
      - [腾讯云 物联网通讯](https://cloud.tencent.com/product/iothub)
      - [百度云 天工](https://cloud.baidu.com/solution/iot/index.html)
      - [中国移动 OneNET](https://open.iot.10086.cn)
   2. [针对特定产品的开发者平台]()
      - [小米 IOT]()
      - [QQ互联]()
   3. [国外IOT平台]()
      - [亚马逊云](https://www.amazonaws.cn/iot/)
      - [Azure 云](https://www.azure.cn/zh-cn/)

4. IOT 设备端

   1. 嵌入式开发板
      1. [树莓派]()
      2. [国产香橙派]()
      3. [MariaDB](https://mariadb.org/)
      4. [MySQL](https://www.mysql.com/)
   2. 云数据库
      - [CosmosDB](https://docs.microsoft.com/zh-cn/azure/cosmos-db)
      - [DynamoDB](https://aws.amazon.com/dynamodb/)
   3. 搜索引擎
      - [ElasticSearch](https://www.elastic.co/)
      - [Solr](http://lucene.apache.org/solr/)
      - [Sphinx](http://sphinxsearch.com/)
   4. NoSQL
      - [MongoDB](https://docs.microsoft.com/zh-cn/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-2.2&tabs=visual-studio)
      - [Redis](https://redis.io/)
      - [Apache Cassandra](http://cassandra.apache.org/)
      - [LiteDB](https://github.com/mbdavid/LiteDB)
      - [RavenDB](https://github.com/ravendb/ravendb)
      - [CouchDB](http://couchdb.apache.org/)

5. 生产环境第三方SDK的选择参考

   1. 天翼云电脑APP接入使用的第三方提供SDK
      1. [天翼云电脑APP接入使用以下由第三方提供的SDK（生产环境第三方SDK的选择参考）](https://www.iaspnetcore.com/Blog/BlogPost/616206fe8976be06f7c51cc6/cloud-desktop)
      2. [EntityFrameworkCore.Cacheable](https://github.com/SteffenMangold/EntityFrameworkCore.Cacheable)
   2. [分布式缓存](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/distributed?view=aspnetcore-2.2)
      1. [Redis](https://redis.io/)
      2. [Memcached](https://memcached.org/)
   3. [内存缓存](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/memory?view=aspnetcore-2.2)

6. Home Assistant  

   1. Beginner’s Guide
      - [Beginner’s Guide to Home Assistant Architecture](https://www.awesome-ha.com/)
      - [NLog](https://github.com/NLog/NLog)
      - [Elmah](https://elmah.github.io/)
   2. 日志管理系统
      - [Sentry.io](http://sentry.io)
      - [Loggly.com](https://loggly.com)
      - [Elmah.io](http://elmah.io)

7. 模板引擎

   1. [Razor](https://docs.microsoft.com/zh-cn/aspnet/core/mvc/views/razor?view=aspnetcore-2.2)
   2. [DotLiquid](https://github.com/dotliquid/dotliquid)
   3. [Scriban](https://github.com/lunet-io/scriban)
   4. [Fluid](https://github.com/sebastienros/fluid)

8. 实时通信

   1. [SignalR](https://docs.microsoft.com/en-us/aspnet/core/signalr)

9. 对象映射

   - [AutoMapper](https://github.com/AutoMapper/AutoMapper)
   - [Mapster](https://github.com/MapsterMapper/Mapster)
   - [AgileMapper](https://github.com/agileobjects/AgileMapper)
   - [ExpressMapper](http://expressmapper.org/)

10. API客户端

    1. REST
       - [OData](https://blogs.msdn.microsoft.com/odatateam/2018/07/03/asp-net-core-odata-now-available/)
       - [Sieve](https://github.com/Biarity/Sieve)
    2. GraphQL
       - [GraphQL-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)

11. 最好掌握

    - [MediatR](https://github.com/jbogard/MediatR)
    - [Fluent Validation](https://github.com/JeremySkinner/FluentValidation)
    - [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
    - [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)
    - [Polly](https://github.com/App-vNext/Polly)
    - [NodaTime](https://github.com/nodatime/nodatime)
    - [GenFu](https://github.com/MisterJames/GenFu)

12. 测试

    1. 单元测试
       1. 测试框架
          - [MSTest](https://docs.microsoft.com/zh-cn/dotnet/core/testing/unit-testing-with-mstest)
          - [NUnit](https://docs.microsoft.com/zh-cn/dotnet/core/testing/unit-testing-with-nunit)
          - [xUnit](https://docs.microsoft.com/zh-cn/dotnet/core/testing/unit-testing-with-dotnet-test)
       2. 模拟工具
          - [Moq](https://github.com/moq/moq4)
          - [NSubstitute](https://github.com/nsubstitute/NSubstitute)
          - [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)
       3. 断言工具
          - [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
          - [Shouldly](https://github.com/shouldly/shouldly)
    2. 行为测试
       - [BDDfy](https://github.com/TestStack/TestStack.BDDfy)
       - [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)
       - [LightBDD](https://github.com/LightBDD/LightBDD)
    3. 集成测试
       - [WebApplicationFactory](https://docs.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-2.2)
       - [TestServer](https://koukia.ca/integration-testing-in-asp-net-core-2-0-51d14ede3968)
    4. 端到端测试
       - [Selenium](https://www.automatetheplanet.com/webdriver-dotnetcore2/)
       - [Puppeteer-Sharp](https://github.com/kblok/puppeteer-sharp)

13. 任务调度

    - [HangFire](https://github.com/HangfireIO/Hangfire)
    - [Coravel](https://github.com/jamesmh/coravel)
    - [Fluent Scheduler](https://github.com/fluentscheduler/FluentScheduler)

14. 微服务

    1. 消息队列
       - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
       - [Apache Kafka](https://github.com/confluentinc/confluent-kafka-dotnet)
       - [ActiveMQ](https://github.com/apache/activemq)
       - [Azure Service Bus](https://docs.microsoft.com/zh-cn/azure/service-bus-messaging/service-bus-messaging-overview)
    2. 消息总线
       - [MassTransit](https://github.com/MassTransit/MassTransit)
       - [NServiceBus](https://github.com/Particular/NServiceBus)
       - [CAP](https://github.com/dotnetcore/CAP)

15. SOLID原则

    - [单一责任原则(SRP)](https://www.dotnetcurry.com/software-gardening/1148/solid-single-responsibility-principle)
    - [开放封闭原则(OCP)](https://www.dotnetcurry.com/software-gardening/1176/solid-open-closed-principle)
    - [里氏替换原则(LSP)](https://www.dotnetcurry.com/software-gardening/1235/liskov-substitution-principle-lsp-solid-patterns)
    - [依赖倒置原则(ISP)](https://www.dotnetcurry.com/software-gardening/1257/interface-segregation-principle-isp-solid-principle)
    - [接口分离原则(DIP)](https://www.dotnetcurry.com/software-gardening/1284/dependency-injection-solid-principles)

16. 设计模式

    - [CQRS](https://docs.microsoft.com/zh-cn/azure/architecture/patterns/cqrs)
	- [装饰模式](https://www.dofactory.com/net/decorator-design-pattern)
    - [策略模式](https://www.dofactory.com/net/strategy-design-pattern)
    - [观察者模式](https://www.dofactory.com/net/observer-design-pattern)
    - [建造者模式](https://www.dofactory.com/net/builder-design-pattern)
    - [单例模式](https://www.dofactory.com/net/singleton-design-pattern)
    - [外观模式](https://www.dofactory.com/net/facade-design-pattern)
    - [中介者模式](https://www.dofactory.com/net/mediator-design-pattern)

## 总结

如果你认为该指南可以改进，请提交包含任何更新的 PR 并提交任何问题。此外，我将继续改进这个仓库，因此你可以 star 这个仓库以便于重新访问。

灵感来源 : [React Developer RoadMap](https://github.com/adam-golab/react-developer-roadmap)

## 贡献

该指南是使用[Draw.io](https://www.draw.io/)构建的。中文版项目文件为`aspnetcore-developer-roadmap.zh-Hans.xml`。要修改它, 请打开 draw.io, 点击 **Open Existing Diagram** 并选择项目中的 `xml` 文件。它将为你渲染生成路线图，更新它，上传和更新自述文件中的图像并创建一个 PR（导出为400%的png图片，然后使用[Compressor.io](https://compressor.io/compress)压缩）。

- 改进后提交 PR
- 在Issues中讨论问题
- 推广项目

## 许可协议

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# 更多技术干货请微信关注公号「AspNetCore」，持续输出优质的技术文章~

