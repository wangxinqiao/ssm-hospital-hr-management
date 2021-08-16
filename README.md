# ssm医院人事管理系统

## 项目介绍
````
本项目旨在为医疗机构实现便捷化人事管理。
人事管理系统，实现的模块有：个人信息管理模块、员工管理模块、考勤管理模块、请假管理模块、部门管理模块。
数据库：使用mysql，Druid数据库连接池，监控数据库访问性能，统计SQL的执行性能。
持久层：mybatis持久化，使用MyBatis-Plus优化，减少sql开发量。
使用spring作为控制层，spring mvc为前端控制器，界面使用bootstrap。
````
演示视频：[ **点此查看** ](https://www.bilibili.com/video/BV1SA411g7BS/)
源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=138)
## 环境需要
````
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；
````
## 技术栈
````
1. 后端：Spring SpringMVC MyBatis
2. 前端：JSP+bootstrap+jQuery
````

## 使用说明
````
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中jdbc.properties配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入localhost:8080/xxx 登录
````

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/163550_184bb2ca_9582667.jpeg "WechatIMG334.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/163603_d3c4404c_9582667.jpeg "WechatIMG335.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/163611_e491c049_9582667.jpeg "WechatIMG336.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/163619_ef97f979_9582667.jpeg "WechatIMG337.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/163629_7dd0189f_9582667.jpeg "WechatIMG338.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/163641_187ef01a_9582667.jpeg "WechatIMG339.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/163702_9cf07c3d_9582667.jpeg "WechatIMG340.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/163710_da919012_9582667.jpeg "WechatIMG341.jpeg")





