
**本列表旨在聚合和推广华人创作的优秀Go语言项目。欢迎也希望大家积极提交PR。让我们共同打造它！**

暂定的优秀Go语言项目标准：

+ 可以是库项目或可运行项目。
+ 适应范围够广，通用的框架项目和服务软件优先。
+ 口碑够好，项目的 Star 数必须超过100。
+ 易上手。文档清晰、代码质量高、测试完整的项目更易上手。

_可以看到，以上标准均不是绝对条件。我们会进行权衡，并尽量提升本列表的质量。_

**由于目录的跳转问题，目录和标题需用英文。而项目的介绍会采用中文。**

### 目录（Contents）

- [Awesome Go](#awesome-go-China)
    - [Audio & Music](#audiomusic)
    - [Authentication & OAuth](#authentication--oauth)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date & Time](#date--time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Game Development](#game-development)
    - [Generation & Generics](#generation--generics)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Pool](#pool)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
    - [Windows](#windows)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)


## Audio/Music

*Libraries for manipulating audio.*


## Authentication & OAuth

*Libraries for implementing authentications schemes.*


## Command Line


### Standard CLI

*Libraries for building standard or basic Command Line applications*

- [readline](https://github.com/chzyer/readline)：纯Go实现的GNU Readline的CLI库，提供类似zsh的交互体验。

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces*


## Configuration

*配置文件解析库*

- [go-ini](https://github.com/go-ini/ini)：全能 INI 解析生成库


## Continuous Integration

*Tools for help with continuous integration*

- [Cyclone](https://github.com/caicloud/cyclone)：一个打造容器工作流的持续集成和持续发布系统，使用 Go 语言实现，有详尽的中文文档，由 [@caicloud](https://github.com/caicloud) 实现。

## CSS Preprocessors

*Libraries for preprocessing CSS files*


## Data Structures

*Generic datastructures and algorithms in Go.*


## Database

*用Go语言实现的数据库。*

- [LedisDB](http://ledisdb.com)：一个高性能的分布式数据库，类似于并兼容Redis。
- [TiDB](https://github.com/pingcap/tidb)：TiDB 是一个支持SQL的分布式数据库，其参考了Google F1的设计，兼具NoSQL和传统关系型数据库的优点。

*Database tools.*


*SQL query builder, libraries for building and using SQL.*



## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases

* NoSQL Databases

* Search and Analytic Databases

## Date & Time

*Libraries for working with dates and times.*



## Distributed Systems

*用于构建分布式系统的库，或可运行的分布式系统。*

- [glow](https://github.com/chrislusf/glow)：一个易于使用的分布式系统，可作为Hadoop、Spark、Flint、Samza的替代品。
- [hprose-golang](https://github.com/hprose/hprose-golang)：一个支持 20 多种语言的功能强大，简单易用的高性能动态 RPC，该版本是它的 go 语言实现。
- [kafka-pusher(taiji)](https://github.com/crask/kafka-pusher)：Kafka-pusher(又名太极)是kafka服务的消费者实现，它可以拉取(pull)消费kafka中的消息，并通过HTTP方式推送(push)给任何接口。
- [mqproxy](https://github.com/crask/mqproxy)：mqproxy是kafka的http代理服务。

## Email

*Libraries that implement email creation and sending*




## Embeddable Scripting Languages

*Embedding other languages inside your go code*



## Financial

*Packages for accounting and finance*



## Forms

*Libraries for working with forms.*



## Game Development

*游戏开发库。*

- [Leaf](https://github.com/name5566/leaf)：一个高效的游戏服务器开发框架，适用于各类游戏服务器的开发。
- [mqant](https://github.com/liangdas/mqant)：高性能分布式游戏服务器开发框架，可用于游戏后端服务器以及物联网后端服务器开发。


## Generation & Generics

*Tools to enhance the language with features like generics via code generation*


## GUI

*Libraries for building GUI Applications*



## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*


## Images

*Libraries for manipulating images.*


## Logging

*Libraries for generating and working with log files.*


## Machine Learning

*Libraries for Machine Learning.*



## Messaging
*用于实现消息系统的库，或可运行的消息系统。*

- [KiteQ](https://github.com/blackbeans/kiteq)：支持多种持久化方案的消息队列框架。
- [goim](https://github.com/Terry-Mao/goim)：一个轻量级、高性能的即时通讯服务器。
- [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster)：一个易集群化的的Comet服务器，支持Web Socket和TCP协议。


## Miscellaneous

*These libraries were placed here because none of the other categories seemed to fit*


## Natural Language Processing

*Libraries for working with human languages.*


## Networking

*Libraries for working with various layers of the network*

- [link](https://github.com/funny/link)：灵活的网络层脚手架，可用来快速搭建各种项目所需的网络层。
- [Pholcus](https://github.com/henrylee2cn/pholcus)：Pholcus（幽灵蛛）是一款纯Go语言编写的支持分布式的高并发、重量级爬虫软件，定位于互联网数据采集，为具备一定Go或JS编程基础的人提供一个只需关注规则定制的功能强大的爬虫工具。
- [Teleport](https://github.com/henrylee2cn/teleport)：Teleport是一个通用、高效、灵活的TCP Socket框架。可用于Peer-Peer对等通信、RPC、长连接网关、微服务、推送服务，游戏服务等领域。
- [Surfer](https://github.com/henrylee2cn/surfer)：Surfer 是一款Go语言编写的高并发 web 客户端，拥有surf与phantom两种下载内核，高度模拟浏览器行为，可实现模拟登录等功能。

## OpenGL

*Libraries for using OpenGL in Go.*



## ORM

*实现对象-关系映射或其它数据映射技术的库。*

- [xorm](https://github.com/go-xorm/xorm)：一个简单且强大的ORM库，支持MySQL、Postgres、TiDB、SQLite 3、MSSQL、Oracle等。
- [GORM](https://github.com/jinzhu/gorm): 程序员友好的全功能ORM，API 简洁，支持Model之间一对一、一对多、多对多关联，还可通过插件扩展功能等。

## Package Management

*实现代码包或/和依赖管理的库。*

- [gopm](http://gopm.io)：一个代码包和依赖管理工具。它无需Git、Hg等版本管理工具，就可以下载指定版本的Go代码包。

## Pool

*具有通用功能的对象池。*

- [go-commons-pool](https://github.com/jolestar/go-commons-pool)：通用的Golang对象池，改写自Java版本的 [Apache Commons Pool](https://commons.apache.org/proper/commons-pool/)，具有丰富的配置选项以及超时机制。
- [slab](https://github.com/funny/slab)：基于slab算法的内存池，提供无锁内存池和基于`sync.Pool`的内存池两种实现。

## Resource Embedding



## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*



## Security

*用于安全防护的库、框架或服务器。*

- [gocaptcha](https://github.com/hanguofeng/gocaptcha)：goCaptcha是支持中文和干扰线的验证码服务器。


## Serialization

*Libraries and tools for binary serialization*

- [fastbin](https://github.com/funny/fastbin)：一个零配置的通讯协议代码生成工具，从Go结构体反向生成通讯协议代码，适用于各类游戏服务端开发。
- [hprose](https://github.com/hprose/hprose-golang)：一个支持 20 多种语言的序列化库，该版本是它的 go 语言实现。


## Server Applications

*通用的独立服务器软件。*

- [Ran](https://github.com/m3ng9i/ran)：一款支持 Digest 认证、gzip 压缩、TLS 加密等功能的静态 web 服务器。


## Template Engines

*Libraries and tools for templating and lexing.*



## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks

* Mock

* Fuzzing and delta-debugging/reducing/shrinking

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
                                                                                    * Utility

## Text Search

*全文搜索引擎或服务器。*

- [wukong](https://github.com/huichen/wukong)：高效、高可定制的全文搜索引擎。

## Third-party APIs

*提供针对第三方平台的访问和操作功能的库。*

[wechat](https://github.com/chanxuehong/wechat)：提供针对微信公众平台、微信企业号、微信商户平台和微信支付的相关功能的Go语言库。

## Utilities

*有用的工具。*

- [bat](https://github.com/astaxie/bat)：bat是类似curl的对人类友好的命令行程序，可以用来调试HTTP服务。
- [tsdump](https://github.com/voidint/tsdump)：数据库表结构导出工具。


## Validation

*Libraries for validation.*



## Version Control

*用于进行版本控制的库或服务器。*

- [Gogs](https://github.com/gogits/gogs)：Gogs是一款可轻易搭建的自助Git服务。

## Video

*Libraries for manipulating video.*



## Web Frameworks

*Web开发框架。*

- [Beego](http://beego.me)：Beego是一个快速开发 Go 应用的 HTTP 框架，他可以用来快速开发 API、Web 及后端服务等各种应用，框架具有简单化、智能化、模块化、高性能等特性。
- [Macaron](http://go-macaron.com)：高生产力和模块化设计的 Go Web 框架。
- [Faygo](https://github.com/henrylee2cn/faygo)：Faygo 是一款快速、简洁的Go Web框架，可用极少的代码开发出高性能的Web应用程序（尤其是API接口）。只需定义 struct Handler，Faygo 就能自动绑定、验证请求参数并生成在线API文档。

### Middlewares

#### Actual middlewares


#### Libraries for creating HTTP middlewares


# Tools

Go software and plugins.


## Code Analysis
* [go-checkstyle](https://github.com/qiniu/checkstyle) 根据go语言规范，参考 java 
checkstyle 实现的代码风格检查工具


## Editor Plugins


## Go Tools


## Software Packages

Software written in Go.


### DevOps Tools


### Other Software







# Resources

Where to discover new Go libraries.


## Benchmarks



## Conferences

- [GopherChina](http://gopherchina.org)：Go语言官方认可的中国用户社区会议。
- [GopherBeijing](http://www.meetup.com/golang-beijing)：Go语言北京用户组主办的定期活动和会议。


## E-Books

- [Go命令教程](https://github.com/hyper-carrot/go_command_tutorial)：讲述Go语言标准工具的使用方法，展现Go语言给力的工程理念。
- [Go名库讲解](https://github.com/Unknwon/go-rock-libraries-showcases)：一套针对Go语言的第三方库进行评测讲解的集博客、示例与语音视频为一体的综合教程。
- [Go Web编程](https://github.com/astaxie/build-web-application-with-golang)：讲述使用Go语言进行Web编程的方方面面。
- [Go学习笔记](https://github.com/qyuhen/book)：雨痕的个人学习笔记。


## Online Tutorials

- [Go语言第一课](http://www.imooc.com/view/345)：Go语言入门的必备知识扩散。
- [Go 编程基础](https://github.com/Unknwon/go-fundamental-programming)：新手入门必备教程

## Websites

- [Go友团](http://golanghome.com)
- [Go Walker](https://gowalker.org)
- [Go语言中文网](http://studygolang.com)
- [Golang中国](http://www.golangtc.com)

## Windows



### Tutorials

