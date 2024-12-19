# 涂鏊飞的个人简历

# [![Static Badge](https://img.shields.io/badge/1,017,004-%E6%80%BB%E8%AE%BF%E9%97%AE%E9%87%8F-blue?logo=csdn)](https://blog.csdn.net/qq_41666142) [<img src="https://img.shields.io/github/stars/731016?style=social">](https://github.com/731016) [<img src="https://img.shields.io/badge/个人网站-笔记-red">](http://xiaofei.site/)

## 个人信息

<table align="center" border="0">
<tr>
	<td>姓名：</td>
    <td>涂鏊飞</td>
	<td>性别：</td>
    <td>男 🚹</td>
	<td rowspan="5"><img style="zoom: 25%;" src="https://note-1259190304.cos.ap-chengdu.myqcloud.com/note/tuaofei_image.png"></td>
</tr>
<tr>
	<td>出生年月：</td>
    <td>2000.1.11</td>
	<td>现居地：</td>
	<td>湖北-武汉</td>
</tr>
<tr>
	<td>电话📞：</td>
    <td>17683866724</td>
	<td>邮箱📫：</td>
    <td>tu_aofei@163.com</td>
</tr>
<tr>
    <td>意向：</td>
	<td style='font-weight:800;color:rgb(196, 61, 56)'>离职-随时入职</td>
	<td></td>
    <td></td>
</tr>
</table>

## 教育经历

**湖北工程学院** 计算机科学与技术 本科

全日制 计算机学院 孝感

## 专业技能

- 熟悉 Java 基础知识，如基本数据类型、异常处理、集合、多线程等，能使用 Java8 的 Stream API、Lambda表达式操作集合类。
 专业技能

- 熟悉 Java 基础知识，如基本数据类型、异常处理、集合、多线程等，能使用 Java8 的 Stream API、Lambda表达式操作集合类。
- 熟悉 常用并实践过多种 Java 设计模式（如单例、工厂、生成器、门面、注册器、适配器）。
- 熟悉 HTML、JavaScript、jQuery、Vue、ajax 等前台技术，Ajax、axios 进行同步或异步数据交互，掌握前端开发框架，如 Vant，element-ui 的使用。
- 熟悉 SSM、Spring Boot、MyBatis-Plus 等主流后端开发框架，熟悉 AOP、IOC 编程、pagehelper 分页插件，能独立开发项目。
- 熟悉 Hibernate、Spring Data JPA 开源框架。
- 熟悉 springboot 轻量级框架，FreeMarker 模板引擎，根据模板导出 word，excel；Quartz 定时任务，实现对服务方法的定时配置，不用在代码单独配置。
- 熟悉 Mysql，Oracle 数据库及库表设计，能够通过创建索引、Explain 分析、SQL语句优化等方式优化性能。
- 熟悉 常见业务开发场景：比如nginx正向/反向代理、全局跨域解决、多环境问题解决，api签名认证，springboot starter SDK等。
- 掌握 Git、SVN 版本控制工具，如上传、拉取代码和版本控制。
- 掌握 常用消息队列的基本使用（Kafka）。
- 熟悉 Linux 运维基本命令使用，如 find、tar、ps、netstat、top 等命令，有排查 cpu 占用过高、磁盘空间不足导致应用无法正常访问的经验。
- 了解 Redis ，掌握 jedisPool，Redis 分布式锁，Redission分布式 session 的使用。
- 了解 SpringCloud 分布式框架，掌握 SpringCloud 各大组件的使用，如 Nacos 注册中心、GateWay 网关等组件。
- 了解 elasticsearch 搜索引擎，能用elasticsearch实现分词搜索，使用Logstash、定时任务实现elasticsearch和数据库进行数据同步。

## 工作经历

#### 上海威士顿信息科技股份有限公司武汉分公司

2022.7.1 - 2024.12.20

智能制造事业部 Java/.net 开发工程师 武汉



负责制造执行系统（MES）的开发与维护，专注于生产消耗、库存和质量管控等关键业务流程。

负责统计过程控制（SPC）的开发与维护，监控生产过程中的质量参数，实现实时质量控制。

负责厂区智能安防项目的开发与维护，主要对接海康威视平台，实现门禁控制、防区报警和入侵检测等功能。

根据需求文档进行分析设计，完成业务功能开发、单元测试、缺陷修复和维护工作。

## 项目经历

#### 武汉卷烟厂 MES 系统

**软件架构**
spring + Hibernate + oracle + redis + Kafka + Quartz + Stimulsoft报表

**项目描述**
用于在制造过程中监控和控制车间的生产流程的制造执行管理系统，以提高生产效率和产品质量。MES系统通过集成生产设备、收集生产数据、监控生产过程，实现了生产流程的自动化和智能化。

**责任描述**

主要参与生产消耗、库存和质量管控等关键业务流程的开发和运维。

参与项目的需求分析和功能设计，确保系统功能满足生产需求。
与客户保持沟通，收集反馈并持续优化系统功能。

**技术描述**

+ 防止多个用户操作同一数据造成数据不一致的问题，使用 dataVersion 实现乐观锁机制，更新数据库时对比版本，保证数据一致性。
+ 多数据源实现，通过配置文件定义的不同的数据库连接信息，构建数据源DruidDataSource，得到对应的SqlSessionTemplate去操作对应的数据库，不同业务模块使用独立数据源，降低系统耦合度。
+ xml和restful接口日志，统一接收接口路径前缀，使用设计模式设计抽象类接收器，抽取公共方法，不同类型的接口具体实现不同的处理器，提升了接口的可维护性和扩展性，防止接口失败可以重放请求，重新发送或接收。
+ 通过扩展 service 方法，实现可配置的 callback 机制，支持在方法执行前后动态配置和调用业务逻辑（如发送接口、消息提醒等），并可灵活设置 callback 的执行方式（同步/异步）和异常处理策略，降低系统耦合度，提升了程序可扩展性。
+ 定时任务配置,项目启动时，获取定时任务配置信息（包含执行方法，上下文信息...），构建Quartz JobDetail,添加到scheduler任务调度器，执行定时任务,并通过分布式锁保证多机部署时定时任务不会重复执行。
+ 系统中用到的魔法值，可维护code和name的对应关系，不用在代码里写死；自定义注解，在po实体转dto时，通过反射自动填充编码对应的名称，集中管理，提高程序的可维护性和扩展性，提高了接近1倍的开发效率。
+ 结合Stimulsoft报表工具，使用生成器模式构建复杂的报表对象，使用线程池ThreadPoolExecutor并行查询数据，优化生成速度，生成速度提升了30%以上。
+ 为实现可搜索上传文件内容，使用elasticsearch替代数据库的模糊搜索，使用动静分离策略创建文章索引，只在es中存储要搜索的字段、修改不频繁的字段（如文件名，文件内容、文件实体id），其它信息可关联数据库查询；
  并使用ik分词器实现更灵活的分词查询，减少es数据更新同步的成本、保证数据一致性，相比于传统模糊搜索搜索效率提升70%以上。

#### 武汉卷烟厂 SPC 系统

**软件架构**
spring + oracle + redis + Kafka + Wonderware时序数据库 + websocket

**项目描述**
利用统计分析方法监控生产过程，确保产品质量的过程质量控制系统。用于实时监控生产过程中的各类与质量管控相关的数据，并在线进行统计、分析和展示，及时准确发现生产过程的异常波动，并指导生产及时采取纠正和调整措施，保障生产过程稳态。

**责任描述**
根据需求文档，对系统进行优化和开发
对系统进行运维，保证系统的正常运行

**技术描述**

+ plc采集的数据通过OPC服务器读取到Wonderware时序数据库，支持高频采集和大规模数据存储，保证数据完整性和可追溯性。
+ 通过配置需要采集的数据信息，根据工单或批次来通过查询实时数据库来获取数据采集信息并实时计算控制图，后端通过kafka获取数据进行消费处理，解决大规模实时数据的计算和处理问题，通过消息队列实现了数据处理的解耦和削峰，缓解了高并发情况下的系统资源短缺问题。
+ 实时监控页面通过websocket和后端建立长链接，后台处理完成的业务数据实时推送给web端，解决了生产数据实时展示的及时性问题，提供了更好的用户体验和实时交互能力。
+ 自定义线程+处理队列实现单个数据采集点位的数据处理，可通过线程标识控制线程启停和监控，解决了数据处理的并发控制，实现了采集任务的管理和监控，支持动态调整和异常处理，实现对单个数采点的管控。



#### API接口开放平台

**软件架构**
spring boot + Dubbo + Spring Cloud Gateway

**项目描述**

基于 Vue + Spring Boot + Dubbo + Gateway 的 API 接口开放调用平台。管理员可以接入并发布接口，可视化各接口调用情况；用户可以开通接口调用权限、浏览接口及在线调试，并通过客户端 SDK 轻松调用接口。

**技术描述**

+ 基于 MyBatis Plus 框架的 QueryWrapper 实现对 MySQL 数据库的灵活查询，并配合 MyBatis X 插件自动生成后端 CRUD 基础代码，减少重复工作。

+ 为防止接口被恶意调用，设计API签名认证算法，为用户分配唯一AK/SK用于鉴权，保障接口调用的安全性。
+ 前后端使用 Swagger + Knife4j 自动生成 OpenAPI 规范的接口文档，前端在此基础上使用插件自动生成接口请求代码，降低前后端协作成本。
+ 为解决开发者调用成本过高的问题，基于 Spring Boot Starter 开发了客户端 SDK， 一行代码 即可调用接口，提高开发体验。
+ 选用 Spring Cloud Gateway 作为 API 网关，实现了路由转发、访问控制、流量染色，并集中处理签名校验、请求参数校验、接口调用统计等业务逻辑，提高安全性的同时、便于系统开发维护。


## 自我评价

- 注重代码可读性，可维护性。
- 喜欢写技术博客，介绍自己在日常编写代码时遇到的问题，善于帮助他人。
- 良好的学习能力，对学习有一份执着与恒心，敢于尝试新鲜事物，并从中提升自己。
- 有较强的问的解决的能力，能够利用GitHub Issues区、AI工具、搜索引擎、StackOverflow等自主解决问题。
- 具有较强的团队精神，有强烈的集体荣誉感。
- 喜欢钻研新技术，敢于面对和克服困难。