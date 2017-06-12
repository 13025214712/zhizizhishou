# 基于angula+Bootstrapr+php+MySQL实现执子之手官网
- 
   执子之手是一个销售钻石的企业网站，整个网站使用了bootstrap框架，使用了响应式技术，对多种类型屏幕进行了大量优化，致使手机，PC，平板等都能很好的支持。网站具有八大模块，布局合理，功能齐全，网站首页有企业的简介、产品的展示等功能，让用户能够在首页能够基本了解企业概况；关于我们板块是企业的介绍，让客户了解企业的宗旨；风格展示板块，展示商品的分类和排序以及最新发布的商品；私人定制板块，供客户预约到店定制商品；品牌故事板块展示企业的文化以及发展历程；新闻动态板块展示企业动态和行业新闻；团队介绍板块向用户展示顶尖的设计师以及强大的团队；联系我们板块使用户能实施通过网站与企业进行业务咨询。整个网站界面美观，富有情调。


## 前端架构
- 页面结构(H5,CSS3,原生JS,bootstrap)

## 服务端架构
- 选用php进行后台开发

## 数据库选取
- 采用MySQL进行相关数据库的设计与实现

## 目前项目已实现功能
1. 使用百度地图API还有腾讯QQ的API，用来展示位置，以及启动QQ进行对话 
2. 风格展示页面，可以筛选产品的类别，系列，以及排序方式
3. 数据的获取使用瀑布流，当页面滚动到数据的末尾时，自动添加下一页数据
4. 面对管理员，即登录了帐号，风格展示页面，页面的产品是可以拖动的，当拖动的距离达到2个当前产品的宽度时，会提示是否删除当前产品
5. 风格展示页面以及新闻页面，当拖进文本文档，不限文件格式，内容为json数据时，可以向数据库插入数据
6. 联系我们页面，信息以卡片的形式显示，管理员可以查看用户的留言以及对留言进行删除
7. 八大模块：风格展示板块、新闻中心板块、私人定制板块、品牌故事板块、品牌故事板块、关于我们板块、联系我们板块、管理员权限
 

## 安装

根目录的index.html是启动文件，需要先用wampserver搭配好环境
数据库文件夹里面的几个txt文件的文件内容是数据库语句，需要先从建库表.txt 执行 MySql语句
举例product.txt、举例news.txt 用于登陆后，实现文件拖拽进浏览器数据库插入的示范，分别在产品页面和新闻页面实现
 
## 其它说明 
管理员帐号密码 '执子之手'， '123456'


## 项目效果图


![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(1).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(2).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(3).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(4).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(5).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(6).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(7).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(8).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(9).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(10).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(11).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(12).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E6%89%8B%E6%9C%BA%20(1).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E6%89%8B%E6%9C%BA%20(2).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E6%89%8B%E6%9C%BA%20(3).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E6%89%8B%E6%9C%BA%20(4).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E6%89%8B%E6%9C%BA%20(5).png))

![](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E6%89%8B%E6%9C%BA%20(6).png))









