---
layout: post
title: 快速跑起一个Springboot工程
---

### 版本选择
- 详细可以查看[Spring-boot官方文档](https://docs.spring.io/spring-boot/docs/)
- 查看下目前最新版本的系统要求：[getting-started-system-requirements](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#getting-started-system-requirements)

```
Spring Boot 2.1.5.RELEASE requires Java 8 and is compatible up to Java 11 (included). Spring Framework 5.1.7.RELEASE or above is also required.

Explicit build support is provided for the following build tools:
```

| Build Tool | Version |
| :----------: | :------------: |
| Maven | 3.3+ | 
| Gradle | 4.4+ | 

版本demo选择了JavaSDK8，Spring2.1.5。自己可以根据工作环境选择，但要考虑兼容。

### 环境准备
以下的安装，如有不清楚的可自行网上搜索，相关的文章非常多。
- [Java SDK8](https://www.oracle.com/technetwork/java/javase/downloads/index.html)下载安装。
- [Apache Maven](http://maven.apache.org/download.cgi)下载安装。
- [IDEA](https://www.jetbrains.com/idea/download/#section=windows)下载安装。
- [IDEA插件](https://juejin.im/post/5b21e48e6fb9a01e573c4be4)可以选择安装。有些插件的安装，有利于开发效率。可自行选择。

### 创建Maven工程
- 可以通过[Spring Initializr](https://start.spring.io/)网站生成。进入网站，选择我们要的配置项，然后点击Generate，便会下载一个根据我们的自定义选择配置生成的zip包，解压后便是一个完整maven工程。
- 也可以通过IDEA生成。[file]->[New]->[Project...]-->[Spring Initializr]。

### 导入Maven工程
- 打开IDEA，[file]->[New]->[Project from Existing Sources...],选择到工程目录,之后选择Maven项，再选择配置路径等参数，默认直接Next到最后便可以正确打开工程。

-----
工程代码：请看github：xxx