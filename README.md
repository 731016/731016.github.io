# 涂鏊飞的个人简历

# [<img alt="csdn" src="https://img.shields.io/badge/csdn-845%2C893%20%E8%A2%AB%E8%AE%BF%E9%97%AE-lightgrey">](https://blog.csdn.net/qq_41666142)[<img src="https://img.shields.io/github/stars/731016?style=social">](https://github.com/731016)[<img src="https://img.shields.io/badge/Gitee-%E9%A1%B9%E7%9B%AE%E5%9C%B0%E5%9D%80-red">](https://gitee.com/LovelyHzz)

## 基本信息

<table align="center" border="0">
<tr>
	<td>姓名：</td>
    <td>涂鏊飞</td>
	<td>性别：</td>
    <td>男 🚹</td>
	<td rowspan="5"><!--<img style="zoom: 25%;" src="https://img-blog.csdnimg.cn/12c2e81228e14a5e993a5968f8bfc522.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5oqY6IW-55qE5bCP6aOe,size_9,color_FFFFFF,t_70,g_se,x_16">--></td>
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
	<td></td>
	<td></td>
</tr>
</table>

## 求职意向

方向：   	Java开发工程师

到岗时间：    两周以内

## 专业技能

+ Java基础知识（数据类型、包装类型、字符串、字符串常量池、数据类型常量池）：掌握
+ Java异常处理、常用list、set、map集合：掌握
+ 常用的Java设计模式（如单例、工厂）：掌握
+ 泛型、初始化多线程方法（synchronized、ReentrantLock）：掌握
+ Java反射机制：掌握
+ JSP、Servlet、Filter、Cookie、Session、Request、Response、EL表达式、JSTL标签语言：掌握
+ JDBC编程相关技术，JDBCUtils工具类、QueryRunner、Druid数据库连接池：掌握
+ HTML + CSS + JS、jQuery、Bootstrap、及AJAX等前台技术，Ajax、axios进行同步或异步数据交互：掌握
+ vue前端框架：了解
+ SpringMVC、MyBatis、MyBatis-Plus等开源框架：掌握
+ SpringMVC核心流程：了解
+ Spring框架，包括IOC和DI、AOP编程、声明式事务处理、pagehelper分页插件等 SSM 的整合等技术：掌握
+ Hibernate、Spring Data JPA开源框架：了解
+ springboot轻量级框架（Thymeleaf，Quartz）：了解
+ springclond分布式框架（Eureka，Ribbon，hystrix，fegin，gateway）：了解 
+ Redis常用数据类型和jedisPool的基本使用：了解
+ Git、SVN版本控制工具：掌握

#### 项目名称：天天生鲜交易平台

**团队人数**：5人

**开发环境**：IDEA + Tomcat9.0 + Mysql5.7 + Redis5.0.14 + SVN + Maven

**软件架构**：SpringMVC + Mybatis-Plus + MYSQL5.7 + Redis + JQuery

**项目描述**：该系统为用户提供生鲜、蔬菜、水果等农产品的交易。

**功能模块**:
1. 用户管理：用户注册、登录、收货地址管理、个人信息展示、浏览记录展示。
2. 商品信息：首页分类展示，详细分类展示。
3. 交易信息：加入购物车，生成订单。

**责任描述**：

1. 负责ER图和用例图设计，参与数据库设计。
2. 负责小组任务分配，协调进度。
3. 负责用户管理模块，包括注册、登录、用户信息修改、商品浏览记录。

**技术描述**：

1. 使用拦截器拦截指定请求，采用自定义生成Token的工具类，采用代理模式。设置md5加密的字符串，发送回前端隐藏域，防止用户多次点击表单提交按钮。
1. 用户注册使用Ajax异步请求，判断用户名是否已被注册；同步方式使用传统拼接和restFul风格方式；密码使用Apache Commons Codec工具类加密，更安全。
1. 下订单和减库存采用同步方法加锁 + 事务处理，防止出现数据不一致。
1. 商品分类id采用redis缓存。
1. 商品浏览记录使用 PageHelper 插件进行分页查询，处理数据使用 stream 流批量处理。
1. 使用枚举类和自定义结果类设置返回状态和信息。
1. 采用canvas动态生成验证码和正则表达式，对注册表单进行验证。

#### 项目名称：出租屋信息管理系统

**团队人数**：6人

**开发环境**：IDEA + Tomcat9.0 + Mysql5.7 + SVN + Maven

**软件架构**：传统的三层架构(dao+service+web（servlet）+filter)+ Druid + MYSQL5.7 + JQuery + Layui + Bootstrap

**项目描述**：该系统为租客和房东提供一个房源信息的共享平台，方便房源交易。

**功能模块**:

 1. 用户管理：个人信息修改（包括头像，密码）、用户登录、注册。
 2. 浏览记录管理：看房记录
 3. 房源信息：租房信息多条件查询
 4. 管理员管理用户：用户禁用/启用，房屋管理

**责任描述**：

1. 负责ER图和用例图设计。
2. 负责用户注册、登录模块。
3. 负责首页和房源详情展示页面设计和js请求和响应信息展示。
4. 参与service层功能编码，调用dao层对象的crud方法。

**技术描述**：

1. 使用过滤器拦截请求和页面跳转（包含已登录用户或者防止直接输入url地址跳转），判断用户登录session是否存在并设置编码格式，防止乱码。
2. 使用Druid数据库连接池维护数据库连接，使用Properties加载数据库配置文件。
3. 使用QueryRunner和prepareStatement来防止SQl注入攻击。
4. 使用工厂模式和反射实例化service层对象；使用工厂+ 单例模式创建Dao层对象。

## 教育背景

2020 - 2022    湖北工程学院     计算机科学与技术 本科

2017 - 2020	湖北大学知行学院  计算机应用技术   专科



**主修课程**：Java程序设计、计算机组成原理、数据结构与算法、计算机网络、操作系统原理、JavaScript高级开发、Java EE程序设计、高级Web项目开发



在校期间获得校级二等奖学金，计算机二级证书

## 自我评价

- 注重代码可读性
- 喜欢写技术博客，介绍自己在日常编写代码时遇到的问题，善于帮助他人
- 良好的学习能力，在校期间获得学校奖学金，对学习有一份执着与恒心，敢于尝试新鲜事物，并从中提升自己。
- 具有较强的团队精神，有强烈的集体荣誉感。
- 喜欢钻研新技术，敢于面对和克服困难。
