# eval-shiro
权限控制+数据过滤框架<br>
附简单demo

介绍
====

模仿shiro的思想实现，功能上更加简洁，而且增加了数据过滤功能。

特点
====
* 1.源代码和思想简单易懂
* 2.实际项目中（springcloud+前后端分离项目+sso单点登录项目）真实应用
* 3.自己可以动手扩展相关功能
* 4.多种数据过滤配置

项目背景
----
* 项目中需要做权限控制，到接口级别
* 更加喜欢注解方式的控制，简单直观
* 集成shiro不成功，项目环境复杂（springcloud+前后端分离项目+sso单点登录项目）
* shiro和spring-security框架，中功能点比较多，而项目中只需要用到接口权限控制一个功能
* 项目中还需要增加权限过滤功能，及不同权限的用户看到同一接口返回的数据都不一样(不想通过sql实现)

项目目录
----
* eval-common -----相关实现核心代码
* eval-demo   -----springboot简易demo，权限验证和过滤

环境
----
jdk8 <br>
springboot2.0 <br>
redis

使用方式
----
[CSDN博客](https://blog.csdn.net/xiewenfeng520/article/details/90270607)

项目截图
----
![首页](https://github.com/huajiexiewenfeng/eval-shiro/blob/master/img/index.png)
