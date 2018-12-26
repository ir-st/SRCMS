# 欢迎使用SRCMS V2.3.1社区开发版 ![codebeat badge](https://codebeat.co/badges/67e58b6d-bc89-4f22-ba8f-7668a9c15c5a)

**SRCMS** 是一款安全应急响应与缺陷管理软件，致力于为大、中、小企业和组织提供“最敏捷、安全和美观的安全应急响应中心的建站解决方案，帮助企业建立属于自己的安全应急响应中心和体系”。有了SRCMS，您就可以像使用Discuz!搭建论坛一样容易，为您的企业建立安全应急响应中心平台。

> * **项目开发/维护**： Martin Zhou
> * **官网**：https://www.plusecurity.cn/srcms.html
> * **最后更新日期**：2017-09-09
> * **QQ交流群**：132108046
> * **安全应急响应**：https://www.plusecurity.cn/tracker


## 授权说明
1. 任何人在未取得SRCMS开发者正式书面授权的情况下，不得将SRCMS项目源代码或二次开发过的源代码用作**商业**出售**用途**，否则将保留追究其法律责任的权利。 
2. 使用SRCMS搭建站点或二次开发时，请您在网页底部加注Powered By SRCMS的相关字样。如有特殊需求，请您及时与我们联系获取授权。


## 免责说明
SRCMS仅为建站软件，任何使用本建站程序搭建的网站其运营的内容所产生的法律纠纷与本项目以及本人无关。


## 运行配置说明
* 第一步：在本页面下载SRCMS源代码
* 第二步：将SRCMS释放至网站根目录，并在\Application\Common\Conf\db.php中编辑与数据库相关的配置
* 第三步：进入\Application\User\Controller\PostController.class.php，第63行修改报告提交提示邮箱信息。
* 至此所有初始配置已经全部完成，后台默认登陆账户/密码为: Admin / Admin，请您登陆后及时修改。


## 版本更新日志

##### 2017-09-09（建议等级：重要）
* **修复** 后台审核用户礼品兑换订单时出错的问题（由藏形匿影反馈）
* **修复** 前台用户兑换礼品无法自定义数量的问题（由藏形匿影反馈）
* **修复** 第三方组件引起的SSRF漏洞

##### 2017-07-02（建议等级：严重）
* **新增** 审核后台单个漏洞报告导出
* **新增** 审核后台全部漏洞报告导出为报表
* **修复** Ueditor上传路径错误导致的文件上传失败问题
* **修复** 用户个人中心礼品无法兑换的问题
* **修复** 前台安全应急响应中心名称动态不显示的问题
* **修复** 跳转页面LOGO不显示的问题

##### 2017-05-31（建议等级：重要）
* **修复** 荣誉榜排行顺序问题
* **修复** 站点名称和简介无法配置的问题
* **修复** 荣誉榜团队无法编辑的问题
* **删除** Ueditor存在漏洞的截屏插件

##### 2017-02-03（建议等级：推荐）
* **新增** SRCMS V2开发版

## 常见问题
SRCMS项目目前已经在Github仓库中开设了专门用于解答常见问题的Wiki页面，详情请查看：
https://github.com/martinzhou2015/SRCMS/wiki/%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98
问题反馈可以通过Github的Issue功能，或是加入反馈QQ群进行咨询讨论

## BUG提交说明
如果您在使用本框架或是二次开发中发现任何SRCMS的问题，欢迎迎通过Github的issue功能将问题反馈，Issue功能能够很好的帮助我们定位和跟踪问题的修复情况。 

## 致谢
在开发过程中，SRCMS得益于广大开源项目和开发者们的帮助和支持,在此向下面的开发者们致谢：
* [ThinkPHP](http://www.thinkphp.cn/)
* mramydnei
* Del技术菜鸟
* Blast
* Ivan
* 藏形匿影(挖财网)

## 公众号
![欢迎关注我的微信公众号](https://s1.ax1x.com/2018/12/26/F2p2yF.jpg)
