---
layout: post
title: "Activiti快速入门项目-kft-activiti-demo"
category: activiti
tags: 
 - activiti
 - 入门
 - demo
 - springside4
---

## 1.项目简介

### 1.1 项目信息

本项目旨在让Activiti初学者可以快速入门，使用工作流里面的**请假**流程作为Activiti企业实战的Hello World。

简单通过这个实例说明如何结合流程与业务，表单、业务、流程之前如何衔接……

发起这个项目也是目前没有太完整、接近企业真实项目的例子，本项目作为一个补充希望能帮助更多人。

### 1.2 DEMO截图

![kft-activiti-demo截图](/files/2012/05/kft-activiti-demo.png)

### 1.3 流程图

![请假流程](/files/2012/05/leave-process-definition.png)

### 1.3 项目结构

本项目使用[Maven](http://maven.apache.org/)作为构建工具，使用[Springside4](https://github.com/springside/springside4)作为基础架构。

### 1.4 如何下载实例程序

本项目托管在著名的**Github**，地址：[https://github.com/henryyan/kft-activiti-demo](https://github.com/henryyan/kft-activiti-demo)。

具体操作请参考本项目的WIKI文档：[https://github.com/henryyan/kft-activiti-demo/wiki/配置说明](https://github.com/henryyan/kft-activiti-demo/wiki/%E9%85%8D%E7%BD%AE%E8%AF%B4%E6%98%8E)

## 2.功能说明

请参考WIKI：[https://github.com/henryyan/kft-activiti-demo/wiki/功能演示](https://github.com/henryyan/kft-activiti-demo/wiki/%E5%8A%9F%E8%83%BD%E6%BC%94%E7%A4%BA)


## 3.意见

本项目使用的是接近企业的环境作为开发的基础，可能对于有些没有接触Maven、SpringMVC的初学者有些不太容易理解。

我曾经考虑过降低门槛，但是我没有这么做；因为Activiti官方的实例以及源代码都是在Maven下面构建，所以你有必要去学习一下如何使用Maven。

因为是演示项目，目的就是让大家理解流程与业务的结合，特定功能使用哪个接口完成，项目里面的Web层使用SpringMVC，有Struts2经验的人来说SpringMVC也不难。

## 4.更新记录

1.<font color='red'>2012-05-27</font>：为了让更多人能快速入门，我做了妥协。创建了**no-maven**分支，以便让不懂maven的也可以快速运行项目。[https://github.com/henryyan/kft-activiti-demo/tree/no-maven](https://github.com/henryyan/kft-activiti-demo/tree/no-maven)