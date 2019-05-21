# 项目愿景

## 一、项目概要

挣闲钱是一个大学生通过做任务挣钱的云平台，它属于以运营为中心的服务软件，也可以理解为面向大学生的专业“众包”系统。

## 二、项目背景

一方面，大学生有较多的零散空闲时间，而且，较多的大学生有着利用自己的零散空闲时间赚取零花钱的意向；在另一方面，有很多机构可能需要一些人群为他们完成一些零散的小任务，如收集消费者的爱好信息以更好地服务消费者等。在这种情况下，提供一个机构发布任务和大学生通过做任务挣钱的云平台，是真正满足了市场需求的产品和服务形式。

挣闲钱项目提供一个云服务中心，在这个服务中心，有一些机构，称为“奶牛”，他们提供任务给平台，奶牛发布任务要求与薪酬，系统推送到客户端；学生可以通过安装“挣闲钱”客户端，收到系统推送，并完成任务从而获得系统分发的奖励。在挣闲钱平台上，奶牛可以通过“闲钱币”发布任务或提现。另外。系统不支持零元交易。

## 三、项目介绍

### （1）项目概况

挣闲钱系统包括是学生管理系统、任务管理系统、交易管理系统、账户管理系统等，特别合适采用面向服务的架构实现。系统的难点在于运营，即任务（业务）的发现与投放。

* 账户管理系统：
  * 学生账户管理：所有学生通过邮箱/手机登陆；学生注册的学号、姓名、年龄、性别、年级、专业等信息是真实的。学生平时使用昵称、头像在社区中活动，可以自由组成兴趣组；
  * 机构账户管理：机构信息都是真实有效的，可以包括学校社团组织，协会，商家等

* 任务管理系统：
  * 机构作为“奶牛”，可以在平台发布任务（暂不考虑学生账户发布任务的情况）；机构发布任务需要提供任务需求和一定的薪酬，作为任务完成方的奖励，系统不支持零元交易；机构发布任务之后将由系统推送到客户端；
  * 学生通过在平台注册并安装客户端之后，可以收到系统的推送并自由选择是否接受推送的任务；在完成任务之后，学生将收到奖励；

* 交易管理系统：
  * 在挣闲钱平台上，使用平台发布的“闲钱币”作为交易的媒介，“闲钱币”可以用于发布任务和作为任务完成的奖励
  * “闲钱币”同时可以提现

### （2）业务场景故事

* 机构组织问卷调查。如学生会针对大二，女生就某个问题开展调查，共300份，符合条件学生完成调查就可得到一元闲钱；
* 协会招新通知。如某协会正对计算机大一新生征集简历，填写提交简历可得到0.01元闲钱；
* 取快递。如某学生出 0.5 元闲钱请同专业同年级取快递；

### （3）项目总体目标

本产品的用户群体是大学生，以及大学生周围的社团协会或者是商家。我们的目标是在学生与社团协会之类的组织之间搭建一个任务发布和接收的平台，同时为两种角色之间提供一个便捷的通道。

我们的项目的另一个重要目标是，在本学期践行面向对象的系统分析与设计方法，体验完整的软件开发流程。

### （4）项目可行性分析

1. 团队实力与技术分析：
   - 后台开发：java web或者go语言，有过使用经验；
   - 前端开发：React框架，较为成熟的技术，使用起来风险较低。

2. 市场推广可行性：

- 大部分大学生有着较多的零散空闲时间，也有着赚取零用钱的意向，该平台满足大学生群体的需求，因此很容易在大学生之间推广；
- 对于很多机构来说，有着一些零散的任务，如问卷信息收集等，该平台可以为这些零散简单的任务提供一个轻松发布的平台，因此便于在市场上的宣传和推广。

### （5）项目基本特征

* 提供一个机构与学生用户之间发布任务和接受任务的平台
* 使用“闲钱币”作为平台交易的货币
* 用户注册需提供真实有效的信息






