# 个人简历

# [<img src="https://img.shields.io/badge/CSDN%E6%8A%80%E6%9C%AF%E5%8D%9A%E5%AE%A2-%E8%A2%AB%E8%AE%BF%E9%97%AE%E9%87%8F318%2C733-informational">](https://blog.csdn.net/qq_41666142)[<img src="https://img.shields.io/github/stars/731016?style=social">](https://github.com/731016)[<img src="https://img.shields.io/badge/Gitee-%E9%A1%B9%E7%9B%AE%E5%9C%B0%E5%9D%80-red">](https://gitee.com/LovelyHzz)

## 基本信息

<table align="center" border="0">
<tr>
	<td>姓名：</td>
    <td>涂鏊飞</td>
	<td>性别：</td>
    <td>男 🚹</td>
	<td rowspan="5"><img style="zoom: 25%;" src="https://img-blog.csdnimg.cn/12c2e81228e14a5e993a5968f8bfc522.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA5oqY6IW-55qE5bCP6aOe,size_9,color_FFFFFF,t_70,g_se,x_16"></td>
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

到岗时间：    一周以内

## 专业技能

+ 熟练JavaSE基础知识，如数据类型、包装类型、字符串、字符串常量池。
+ 熟悉Java异常处理、常用集合。
+ 良好的面向对象编程思想，并且熟悉常用的Java设计模式（如单例、工厂）
+ 熟悉泛型、多线程的使用方式。
+ 掌握Java反射机制。

+ 熟悉Java Web技术，包括JSP、Servlet、Filter、Cookie、Session、Request、Response、EL表达式、JSTL标签语言。
+ 掌握JDBC编程，并且能够熟练使用DBUtil开发工具包、druid数据库连接池

+ 掌握HTML+CSS+JS及AJAX等前台技术，能够熟练Ajax进行同步或异步数据交互。
+ 能够熟练使用jQuery、Bootstrap插件。

+ 熟练掌握Spring框架，包括IOC和DI、AOP编程、声明式事务处理及SSM的整合等技术。
+ 熟悉SpringMVC、MyBatis、MyBatisPlus等开源框架、深刻理解SpringMVC核心流程。
+ 掌握Hibernate、Spring Data JPA等开源框架。
+ 掌握Redis缓存，掌握jedis连接池的基本使用。

+ 熟悉Git、SVN版本控制工具。

## 项目经验

#### 项目名称：天天生鲜交易平台

**团队人数**：5人

**开发环境**：IDEA + Tomcat9.0 + Mysql5.7 + Redis5.0.14 + SVN + Git + Maven

**软件架构**：SpringMVC + Mybatis-Plus + MYSQL5.7 + Redis + JQuery

**项目描述**：该系统为用户提供生鲜、蔬菜、水果等农产品的交易。

**功能模块**:
1. 用户管理：用户注册、登录、收货地址管理、个人信息展示、浏览记录展示。
2. 商品信息：首页分类展示，详细分类展示。
3. 交易信息：加入购物车，生成订单。

**责任描述**：

1. 负责ER图和用例图设计，参与数据库设计。
2. 负责小组任务分配，协调进度。
3. 负责用户管理模块。

**技术描述**：

1. 使用拦截器拦截指定请求，采用自定义生成Token的工具类设置md5加密的字符串，发送回前端隐藏域，防止用户多次点击表单提交按钮。
1. 用户注册使用Ajax异步请求，判断用户名是否已被注册；密码使用Apache Commons Codec工具类加密，更安全。
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
3. 负责首页设计。
4. 参与service层功能编码。

**技术描述**：

1. 使用过滤器拦截请求和页面跳转（包含已登录用户或者防止直接输入url地址跳转），判断用户登录session是否存在并设置编码格式，防止乱码。
2. 使用Druid数据库连接池维护数据库连接，使用Properties加载数据库配置文件。
3. 使用QueryRunner和prepareStatement来防止SQl注入攻击。
4. 使用工厂模式和反射实例化service层对象；使用工厂+ 单例模式创建Dao层对象。

#### 项目名称：员工信息管理系统

**团队人数**：1人

**开发环境**：IDEA + Tomcat9.0 + Mysql5.7

**软件架构**：传统三层架构（dao+service+web（servlet）） + MYSQL5.7 + Druid + JQuery + Jsp + EL表达式

**项目描述**：该系统为员工管理，包括员工信息的增删改查，包括员工头像。

**功能模块**:

 1. 员工注册
 2. 员工列表展示-可筛选部门
 3. 删除单个员工，批量删除员工
 4. 修改员工信息
 5. 双击头像，可提交员工头像

**责任描述**：

1. 负责数据库设计，项目搭建。
2. 负责员工信息和部门信息管理。

**技术描述**：

1. 使用Druid数据库连接池维护数据库连接，使用Properties加载数据库配置文件，使用QueryRunner封装返回数据，使运行更高效。
2. 采用自定分页工具类，对员工信息进行分页查询，并对工资使用el表达式判断，展示不同的效果。
3. 使用SmartUpload工具类上传员工头像，简化上传操作。
4. 将文件名根据时间戳+随机数重命名后，另存为后删除源文件；当要修改头像时，获取数据库保存的文件名对其保存在数据库的文件进行删除后，重新上传。
5. dao层和service层部分采用单例模式（懒汉式-不支持多线程）；service层部门采用工厂模式

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
