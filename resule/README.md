﻿<h2 align = "center">韩迎龙个人履历</h2>
###1.个人信息
* 姓名：韩迎龙(`Kencery`)、性别：男、现居住地：*北京*
* 毕业院校：长春工程学院
* 联系电话：**18658152123**、E-Mail：**hyl934532778@live.cn**
* 工作年限：2012年2月份->至今
* 求职意向：ASP.NET、Java软件工程师(有发展空间)

###2.开源博客
| 标题        | 超链接           | 说明           |
| ------------- |:-------------:|:-------------:|
| 开源项目源代码     | [开源项目源代码](https://github.com/kencery "开源项目源代码") | 在GitHub下开源的几个项目，也是自己使用过程中学习及整理的源码 |
| cnblogs(博客)      | [cnblogs(博客)](http://www.cnblogs.com/hanyinglong "cnblogs(博客)")      |  个人博客地址，详细记录了自己从开始学习到现在的学习以及经验等 |
| 开源权限系列博客 |  [开源权限系列博客](http://www.cnblogs.com/hanyinglong/archive/2013/03/22/2976478.html "开源权限系列博客")   | 开源的一个权限(用户-角色-权限-按钮)系统，从无到有的开发讲解  |
| 全文检索系列博客 |  [全文检索系列博客](http://www.cnblogs.com/hanyinglong/p/5464604.html,"全文检索系列博客")   | 学习基于Lucene的Elasticsearch全文检索(安装-集群-Java,.NET客户端) |

###3.个人技能
##### (1) Java
* 熟练掌握Java语法糖、Spring MVC、Shiro、MyBatis、JDBC、Spring、Hibernate
* 熟练使用Maven开发项目并且发布部署
* 熟练使用Myeclipse、IDEA等开发工具
* 熟练使用JSON、XML编写ajax异步应用
* 可以搭建基于Spring MVC、Memcached、Redis、Mysql等技术的网站框架

##### (2) .NET
* 熟练掌握.NET语法糖、ASP.NET MVC/WebForm、ADO.NET、Dapper、Linq、Entity Framework、Nhibernate、Spring.NET
* 熟练使用Visual Studio 2008、Sql Server2005以上开发工具
* 熟练使用JSON、XML编写ajax异步应用
* 可以基于.NET的任何平台/技术搭建架构,对设计模式也有一定的了解。

##### (3) 其它
* 熟练使用Git、SVN、TFS等版本控制软件
* 熟练使用Linux系统常用操作命令以及在Linux配置Nginx等
* 熟练掌握Sql Server、Mysql数据库,对数据库的优化有一定的了解
* 熟练使用Memcached、Redis、Nginx、Elasticsearch、Email、Task服务等开源组件的使用
* 熟练掌握页面架构和布局,使用JavaScript和Jquery及第三方插件(EasyUI，Bootstrap...),了解DIV+CSS布局

###4.工作历程
| 工作时间          | 公司名称  | 在职职位      | 完成项目       |
| ----------------- |:-------------:|:-------------:|:-------------:|
| 2015/03-至今      | 北京某O2O公司 | .NET/Java软件工程师 | boss收银系统、微信外卖网、日志监控系统、H5/WeChat外卖网 |
| 2013/02-2015/03   | 北京某教育集团 | .NET软件工程师/项目负责人 | 时代先锋网、教材信息系统V1.0、文档库管理系统 |
| 2012/02-2012/12   | 长春东高集团 | .NET软件工程师 | MVC权限管理信息系统(KJ240)、人员定位管理系统(KJ241) |

###5.项目简述
##### (1) Boss收银系统(http://boss.etao.cn/)
* 项目介绍:该系统提供公司各个终端、销售人员、开发人员、财务等使用的基础系统，各个终端订单的管理，销售人员对各个终端的销售，开发人员对终端产品的推送以及财务的对账等功能(管理后台)
* 项目职责
	* 主要使用Shiro+MyBatis+Redis开发用户权限模块，使系统能够对按钮进行权限管理
	* 门店、订单管理,营收统计,佣金配置等功能调用API的实现
* 使用技术:Spring MVC、Mysql、Shiro、Ehcache、MyBatis、Spring(redis、rest、task)开源组件、Swagger、Log4j2、Email

##### (2) 日志监控系统(http://bms.etaoshi.com/、http://mms.etaoshi.com/))
* 项目介绍:该系统提供给公司内部使用，主要是监控公司所有网站的请求(占用网络带宽/Http状态/响应最慢的URL/访问最多的IP/每个城市的访问量)、订单号剩余量、订单数量、RabbitMQ、短信发送等信息。
* 项目职责
	* 负责开发前后端信息，后端各项参数的设置等对数据库的操作
	* 前端使用Echarts来展现各种统计的图标信息
* 使用技术:ASP.NET MVC、Mysql、Dapper、Echarts、Redis、Elasticsearch.NET、NEST、win服务

##### (3) 时代先锋网(http://mooc.zjsdxf.cn/)
* 项目介绍:该系统提供了公务员学习的平台,在此平台上可以学习课程(视频/文档/作业/考试/问卷调差),教师可以对学生的学习情况及作业、考试进行打分，管理员可以对教师及课程进行整体的管理和审核
* 项目职责
	* 系统分为三个级别(管理员/教师/学生),每个模块独立,我负责管理员模块的开发，实现了创建课程(设置课程/上传视频/课程共享)，分地管理以及问卷调差，对区域内教师的管理和课程学习的统计
	* 负责后期的Bug统计和修改以及和第三方公司的登录对接
	* 编写文档管理员的操作说明和整个系统的测试用例
* 使用技术:ASP.NET MVC、ADO.NET、Jquery插件、Win服务。

##### (4) 教材信息管理系统(进销存)(http://jc1.zjtvu.edu.cn:8091/)
* 项目介绍:改系统提供了省电大对其分校教材的管理，整个系统分为6大部分(基础数据/权限设计/分校-省校征订/省校采购/供应商到货/省校发行/省校结算)，实现了分校征订教材省校发行教材的整个流程
* 项目职责
	* 担任项目负责人，团队人员：5人
	* 设计数据库，配置权限以及使用MVC、EF、EasyUI搭建整个框架，书写代码规范，测试规范，需求文档等。
	* 参与开发的模块有（权限，征订，到货，发行）,整个系统的实现和经销存思想基本一致，更具有个性化。
* 使用技术:ASP.NET MVC、Entity Framework、Linq To SQL、EasyUI、Jquery

##### (5) 文档库管理系统
* 项目介绍:该系统提供给医院销售人员在平板上销售药品的后台文档库信息的管理，可以管理所有药品的文档信息和文档配置以及视频信息。
* 项目职责
	* 负责文档库信息节点的上传配置，完全使用JS搭建前台显示页面。
	* 使用ASP.NET MVC和Entity FrameWork搭建项目，封装操作数据库的方法，封装常用的类。
	* 使用HTML5的上传属性(FormData)实现了上传文档,视频等JS的封装。
* 使用技术:ASP.NET MVC、Entity Framework、Linq To SQL、JS插件

##### (6) MVC权限管理系统(KJ240) (开源)
* 项目介绍:该系统是为公司开发的通用权限系统，可以在每个项目的权限中直接使用,关于这个项目在开源博客中已分享
* 项目职责
	* 该系统是为了在以后的过程中不需要开发重复性的工作而使用MVC和EF开发的权限系统，可以在ASP.NET MVC和WebForm中使用。
	* 数据库设计和项目框架搭建，代码实现等全部由自己实现，参考博客园内容。
	* 完成为用户设置角色和权限，给权限设置角色，给用户设置用户组，最后使用MVC的OnActionExting方法来判断用户必须满足上述条件才能进行权限设置并且登录系统。
* 使用技术:ASP.NET MVC、EasyUI、Entity Framework、log4Net

##### (7) 人员定位管理系统(KJ241)
* 项目介绍:该系统是对煤矿人员的一个总体管理(上井，下井，部门等),根据权限将系统分为好几个版本。
* 项目职责
	* 项目基于ASP.NET MVC2.0+Nhibernate+Spring.NET+EasyUI架构实现，B/S端仿照windows桌面的开发，可以给桌面设置不同颜色的桌面主题
	* 实现了可以上传多张图片的功能。实现了对煤矿人员的管理。
	* 使用NPOI实现将数据导出Excel的功能。
* 使用技术:ASP.NET MVC、Nhibernate、Spring.Net、EasyUI、Jquery、Log4Net、NPOI、SQL Server

###6.探究中
* Linux下搭建Raneto Docs(已搭建,细节为研究)
* Elasticsearch持续学习中ing
* mongodb学习
* Nginx简单研究学习中
* 思维导图学习画流程图