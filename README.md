# 基于angular+php+MySQL实现执子之手官网
- 经过一个多月总算完成第一个版本
## 前端架构
- 页面结构(H5,CSS3,原生JS)
- 框架(基于Vue脚手架:vue-cli)进行搭建
- 数据请求处理框架(Axios)
- Vue-Router进行路由处理
- Vue-LazyLoad进行图片赖加载

## 服务端架构
- 选用NodeJs进行后台开发
- Express中间件进行服务的配置，路由、请求的处理
	- 官网 [http://www.expressjs.com.cn/](http://www.expressjs.com.cn/ "express官网")
- Mysql中间件处理与数据库的"通信"
- Body-Parser中间件进行前端请求参数的获取
- Cookie-Parser、Cookie-Session进行cookie与session的处理


## 数据库选取
- 采用MySQL进行相关数据库的设计与实现

## 目前项目已实现功能
1. 首页数据的展示
2. 分类页数据的展示
3. 购物车
4. 我的
5. 注册
6. 登录
7. 商品详情页
8. 商品搜索


## 安装

已安装MySQL数据库，然后导入migou.sql文件

然后通过`npm`安装本地服务第三方依赖模块(需要已安装[Node.js](https://nodejs.org/))

```
cd vue-jd
```

```
npm install 或 cnpm install(个人比较喜欢使用后者，下载依赖模块速度较快)
```

```
npm run dev
```

最后开启后台服务

```
node server.js
```

## 目录结构
<pre>
.
├── README.md           
├── libs               		// 后台常用工具模块的封装，比如格式化事件、MD5加密等
├── route              		// 后台接口的编写目录
├── server.js          		// 后台服务的配置文件
├── webpack.config.js  		// webpack配置文件
├── index.html         		// 项目入口文件
├── package.json       		// 项目配置文件
├── src                		// 生产目录
│   ├── assets         		// css js 和图片资源
│   ├── components     		// 各种Vue组件
│   ├── store          		// vuex状态管理器
│   ├── App.vue        		// 项目中全局Vue
│   ├── main.js        		// Webpack 预编译入口
│   └── router.config.js    // vue路由配置文件
</pre>

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












# zhizizhishou
“执子之手”，一个销售钻石的企业网站，使用angular+Bootstrap+php等技术，使用百度地图API还有腾讯QQ的API，用来展示位置，以及启动QQ进行对话 ；风格展示页面，可以筛选产品的类别，系列，以及排序方式；数据的获取使用瀑布流，当页面滚动到数据的末尾时，自动添加下一页数据；面对管理员，即登录了帐号，风格展示页面，页面的产品是可以拖动的，当拖动的距离达到2个当前产品的宽度时，会提示是否删除当前产品；风格展示页面以及新闻页面，当拖进文本文档，不限文件格式，内容为json数据时，可以向数据库插入数据；联系我们页面，信息以卡片的形式显示，管理员可以查看用户的留言以及对留言进行删除
# [![zhizizhishou](https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(1).png)](https://github.com/13025214712/zhizizhishou)

https://rawgit.com/13025214712/zhizizhishou/master/screenshots/%E7%94%B5%E8%84%91%20(1).png
