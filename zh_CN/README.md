
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


### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces*


## Configuration

*Libraries for configuration parsing*


## Continuous Integration

*Tools for help with continuous integration*


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


## OpenGL

*Libraries for using OpenGL in Go.*



## ORM

*实现对象-关系映射或其它数据映射技术的库。*

- [xorm](https://github.com/go-xorm/xorm)：一个简单且强大的ORM库，支持MySQL、Postgres、TiDB、SQLite 3、MSSQL、Oracle等。

## Package Management

*Libraries for package and dependency management.*



## Resource Embedding



## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*



## Security

*用于安全防护的库、框架或服务器。*

- [gocaptcha](https://github.com/hanguofeng/gocaptcha)：goCaptcha是支持中文和干扰线的验证码服务器。


## Serialization

*Libraries and tools for binary serialization*

  

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

*Libraries for accessing third party APIs.*


## Utilities

*有用的工具。*

- [bat](https://github.com/astaxie/bat)：bat是类似curl的对人类友好的命令行程序，可以用来调试HTTP服务。


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

### Middlewares

#### Actual middlewares


#### Libraries for creating HTTP middlewares


# Tools

Go software and plugins.


## Code Analysis



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


## E-Books



## Twitter



## Websites



## Windows



### Tutorials

