# 涂鏊飞的个人简历

# [![Static Badge](https://img.shields.io/badge/1,000,863-%E6%80%BB%E8%AE%BF%E9%97%AE%E9%87%8F-blue?logo=csdn)](https://blog.csdn.net/qq_41666142) [<img src="https://img.shields.io/github/stars/731016?style=social">](https://github.com/731016) [<img src="https://img.shields.io/badge/个人网站-笔记-red">](http://xiaofei.site/)

## 基本信息

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
	<td>毕业院校：</td>
    <td>湖北工程学院</td>
</tr>
<tr>
	<td>现居地：</td>
	<td>湖北-武汉</td>
	<td>学历:</td>
	<td>本科</td>
</tr>
<tr>
	<td>电话📞：</td>
    <td>17683866724</td>
	<td>专业:</td>
    <td>计算机科学与技术</td>
</tr>
<tr>
	<td>邮箱📫： </td>
    <td>tu_aofei@163.com</td>
	<td>意向：</td>
	<td style='font-weight:800;color:rgb(196, 61, 56)'>在职-考虑机会</td>
</tr>
</table>


## 专业技能

- 熟悉 Java 基础知识，如基本数据类型、异常处理、集合、多线程等，能使用 Java8 的 Stream API、Lambda表达式操作集合类。
- 熟悉 常用的 Java 设计模式（如单例、工厂、生成器）。
- 熟悉 HTML、JavaScript、jQuery、Vue、ajax 等前台技术，Ajax、axios 进行同步或异步数据交互，掌握前端开发框架，如 Vant，element-ui 的使用。
- 熟悉 SSM、Spring Boot、MyBatis-Plus 等主流后端开发框架，熟悉 AOP、IOC 编程、pagehelper 分页插件，能独立开发项目。
- 熟悉 Hibernate、Spring Data JPA 开源框架。
- 熟悉 springboot 轻量级框架，FreeMarker 模板引擎，根据模板导出 word，excel；Quartz 定时任务，实现对服务方法的定时配置，不用在代码单独配置。
- 熟悉 Mysql，Oracle 数据库及库表设计，能够通过创建索引、Explain 分析、SQL语句优化等方式优化性能。
- 熟悉 常见业务开发场景：比如nginx正向/反向代理、全局跨域解决、多环境问题解决，api签名认证，springboot starter SDK等。
- 掌握 Git、SVN 版本控制工具，如上传、拉取代码和版本控制。
- 掌握 常用消息队列的基本使用（Kafka）。
- 了解 Redis ，掌握 jedisPool，Redis 分布式锁，Redission分布式 session 的使用。
- 了解 SpringCloud 分布式框架，掌握 SpringCloud 各大组件的使用，如 Nacos 注册中心、GateWay 网关等组件。
- 熟悉 Linux 运维基本命令使用，如 find、tar、ps、netstat、top 等命令，有排查 cpu 占用过高、磁盘空间不足导致应用无法正常访问的经验。
- 了解 elasticsearch 搜索引擎，有开发过对文档文件进行搜索的功能。
- 了解 docker 容器化部署。

## 工作经历

#### 上海威士顿信息科技股份有限公司武汉分公司

2022.7.1 - 至今

智能制造事业部 Java/.net 开发工程师 武汉

- 根据需求文档进行分析设计，完成业务功能开发、单元测试、缺陷修复和维护工作
- 熟练掌握 SQL 语句，并能应用 SQL 进行增删改查业务数据操作和统计工作。

## 项目经历

#### XXX卷烟厂 MES 系统

**软件架构**
spring + Hibernate + oracle + redis + Kafka + Quartz + Stimulsoft报表

**项目描述**
用于在制造过程中监控和控制车间的生产流程的制造执行管理系统，以提高生产效率和产品质量。MES系统通过集成生产设备、收集生产数据、监控生产过程，实现了生产流程的自动化和智能化。

**责任描述**
参与项目的需求分析和功能设计，确保系统功能满足生产需求。
与客户保持沟通，收集反馈并持续优化系统功能。

**技术描述**

+ 多个用户操作同一数据，使用 dataVersion 实现乐观锁机制，保证数据一致性。
+ 多数据源实现，通过配置文件定义的不同的数据库连接信息，构建数据源DruidDataSource，得到对应的SqlSessionTemplate去操作对应的数据库。
+ 为防止接口被恶意调用，设计API签名认证算法，为用户分配唯一AK/SK用于鉴权，保障接口调用的安全性。
+ xml和restful接口日志，使用LinkedBlockingQueue + AtomicInteger 实现一个任务调度器处理接口数据，使用抽象类+线程池+接口实现接收接口的处理，并记录接口日志。
+ 实现到service实现类方法的callback调用，配置需要执行的callback信息（包括忽略异常，是否异步执行），
  同步调用：通过具体的实现类的invoke执行各自具体逻辑；
  异步调用：通过线程池单独执行，忽略异常通过try catch处理，如果不忽略直接throw抛出。
+ 定时任务配置,项目启动时，获取定时任务配置信息（包含执行方法，上下文信息...），构建Quartz JobDetail,添加到scheduler任务调度器，执行定时任务,并通过分布式锁保证多机部署时定时任务不会重复执行。
+ 系统中用到的魔法值，可先定义好code，name和对应的属性标识，不用在代码里写死，po转dto定义注解，通过反射自动填充code对应的name
+ 结合Stimulsoft报表工具，使用生成器模式构建复杂的报表对象，使用线程池ThreadPoolExecutor并行查询数据，优化生成速度。

#### XXX卷烟厂 SPC 系统

**软件架构**
spring + oracle + redis + Kafka + Wonderware时序数据库 + websocket

**项目描述**
利用统计分析方法监控生产过程，确保产品质量的过程质量控制系统。用于实时监控生产过程中的各类与质量管控相关的数据，并在线进行统计、分析和展示，及时准确发现生产过程的异常波动，并指导生产及时采取纠正和调整措施，保障生产过程稳态。

**责任描述**
根据需求文档，对系统进行优化和开发
对系统进行运维，保证系统的正常运行

**技术描述**

+ plc采集的数据通过OPC服务器读取到Wonderware时序数据库。
+ 通过配置需要采集的数据信息，根据工单或批次来通过查询实时数据库来获取数据采集信息并实时计算控制图，后端通过kafka获取数据进行消费处理。
+ 实时监控页面通过websocket和后端建立长链接，后台处理完成的业务数据实时推送给web端。
+ 自定义线程+处理队列实现单个数据采集点位的数据处理，可通过线程标识控制线程启停和监控。



#### 基于poi-tl的word文档模板导出

**软件架构**
spring boot + Apache poi + poi-tl

**项目描述**

基于标签`{{}}`的无逻辑的模板引擎，通过接口使用JSON形式传递需要生成的数据信息（如解析的对象类型、需要生成的数据、Word模板），然后根据这些信息，通过对应的解析策略生成相应的Word文档。

**技术描述**

+ 通过接口传递需要生成的模板信息，文档以base64形式传递，生成word的参数通过json解析为实际需要的类型

+ 根据每个参数对应的参数类型（如字符串，表格，列表，图表）通过匹配对应的解析策略

+ 文档生成，将生成的Word文档输出，可以是直接通过application/x-download以Stream文件流形式下载


## 自我评价

- 注重代码可读性，可维护性。
- 喜欢写技术博客，介绍自己在日常编写代码时遇到的问题，善于帮助他人。
- 良好的学习能力，对学习有一份执着与恒心，敢于尝试新鲜事物，并从中提升自己。
- 有较强的问的解决的能力，能够利用GitHub Issues区、AI工具、搜索引擎、StackOverflow等自主解决问题。
- 具有较强的团队精神，有强烈的集体荣誉感。
- 喜欢钻研新技术，敢于面对和克服困难。