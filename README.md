# linfeng-community

#### 1.介绍

社交论坛uniapp小程序/H5/App版本基于SpringBoot2+MybatisPlus+Shiro+jwt+Redis+Vue+Uniapp的前后端分离的社交论坛问答发帖/BBS项目 项目分为Uniapp用户端（兼容H5、微信小程序以及App）和Vue后台管理端（包括完整的权限处理）， 基于以下技术栈开发：SpringBoot2、MybatisPlus、Shiro、jwt、Redis、Vue、Uniapp、MySQL5.7。

功能：图文帖，短视频，圈子，私聊，微信支付（小程序/H5/app），付费贴，积分签到，钱包充值，积分余额兑换，话题标签,抽奖大转盘，手机号邮箱登录，人机发帖等完整功能，直接看演示更直观↓↓↓↓↓↓

***后台前端的代码在 src\main\resources\static\linfeng-community-vue目录下！***

***用户端的前端代码在 src\main\resources\static\linfeng-community-uniapp-ky 目录下！***

代码三端开源，包括用户端也发布了**开源版**（**SQL文件在qq群文件中**，点个star加群获取即可）

#### 2.软件演示

官网：https://net.linfeng.tech

##### 2.1移动端H5演示版本（手机扫码浏览/输入手机号登录）https://www.linfeng.tech

![移动端H5二维码](https://github.com/virus010101/linfeng-community/blob/main/images/er.png)

后台管理系统演示地址：https://dev.linfeng.tech

账号 ： test         密码：  123456

小程序端和App安卓端体验版二维码请查看本链接：

https://www.linfeng.tech/#/pages/post/detail?id=140



**注意:演示版为标准商业版**

开源版具体的功能清单请查看：https://net.linfeng.tech/version/version.html

##### 2.2移动端效果截图

<img src="https://github.com/virus010101/linfeng-community/blob/main/images/showPic11.png"/>

![](https://github.com/virus010101/linfeng-community/blob/main/images/showPic12.png)

![](https://github.com/virus010101/linfeng-community/blob/main/images/showPic13.png)

![](https://github.com/virus010101/linfeng-community/blob/main/images/showPic14.png)

![](https://github.com/virus010101/linfeng-community/blob/main/images/showPic04.png)

##### 2.3后台管理端效果截图

![](https://github.com/virus010101/linfeng-community/blob/main/images/showPic05.png)

![](https://github.com/virus010101/linfeng-community/blob/main/images/showPic06.png)

![](https://github.com/virus010101/linfeng-community/blob/main/images/showPic07.png)

![](https://github.com/virus010101/linfeng-community/blob/main/images/showPic08.png)

![](https://github.com/virus010101/linfeng-community/blob/main/images/showPic09.png)

![](https://github.com/virus010101/linfeng-community/blob/main/images/showPic10.png)

#### 3.安装教程 

1.  配置数据库和redis。先启动redis，再启动后端api服务
2.  数据库请使用MySQL5.7，其他版本可能会有问题
3.  配置后台前端  先npm install 下载依赖后，再npm run dev即可。移动端同样，先npm install，再启动。
4.  github下载速度慢可以访问国内码云gitee链接（优先更新gitee）：https://gitee.com/virus010101/linfeng-community

#### 4.必看说明

1.**后台前端的代码**在**\src\main\resources\static\linfeng-community-vue**目录下！

2.**后台管理系统和后台管理系统后端API已经全部开源**。

**用户端代码已开源**，在**\src\main\resources\static\linfeng-community-uniapp-ky**目录下！

**需要商业版（即为上图演示站点项目）源码联系客服**。

<img src="https://github.com/virus010101/linfeng-community/blob/main/images/mine.jpg" style="zoom: 25%;" />



3. SQL文件开源的，在QQ群，开源不易，**请左上角点个star后备注gitee的用户名加QQ群（640700429）获取**

<img src="https://github.com/virus010101/linfeng-community/blob/main/images/qrcode.jpg" style="zoom:25%;" />

4.**商业版和开源版的区别**

https://net.linfeng.tech/version/version.html

详情查看官网：https://net.linfeng.tech

#### 5.开源须知

- 开源版仅允许用于个人学习研究使用!

- 禁止将本开源的代码和资源进行任何形式任何名义的改造或出售!

- 限制商用，如果需要商业使用请联系我们或查看官网了解商用详情。qq:3582996245。


#### 6.版本更新记录



***当前版本V1.5.0***



2022.10.8

###### **V1.5.0发布**

【新增】1.新增会员模块

【新增】2.接入广告模块

【新增】3.新增用户改名限制

【新增】4.新增发帖奖励

【新增】5.新增数字格式化 过滤器

【新增】6.会员积分奖励翻倍

【新增】7.新增系统消息长按删除

【新增】8.增加管理端消息模块 帐单模块条件查询

【新增】9.创建圈子数量限制

【优化】10.处理app端视频播放

【优化】11.删除帖子的数据清理优化

【优化】12.禁用账号禁止私聊

【优化】13.用户端圈子信息修改可能越权的问题

【优化】14.帖子详情查询优化

【优化】15.敏感词库管理优化调整



######  V1.4.2发布

2022.9.6

【新增】1.新增举报模块 [重磅]

【新增】2.重构升级用户主页和个人页UI [重磅]

【新增】3.APP端适配  [重磅]

【新增】4.帖子列表操作栏动态处理 

【优化】5.帖子列表查询优化及移动端结构调整

【优化】6.增加个人页背景图公共配置项

######  V1.4.1发布

2022.8.16

【新增】1.新增积分抽奖大转盘 [重磅]

【新增】2.新增圈子内帖子置顶功能 与平台置顶区分 [重磅]

【新增】3.新增客服页面 [重磅]

【新增】4.新增邮箱验证码登录 可配置开关 [重磅]

【新增】5.H5端新增注册页面 区分登录和注册 [重磅]

【优化】6.圈子管理员h5端删帖优化

【优化】7.h5端设置管理员页面样式兼容和用户列表图标

【优化】8.帖子详情查询优化

【优化】9.投票贴空选项优化

【优化】10.fastjson升级

【优化】11.后端swagger文档全注释

【优化】12.用户缓存信息

【优化】13.手机验证码登录

###### **V1.4.0发布**

2022.7.24

【新增】1.虚拟用户自动注册发帖 *【重磅】*

【新增】2.后台统一管理可配置项设置 *【重磅】*

【新增】3.后台管理系统首页增加echarts图和快捷入口 *【重磅】*

【新增】4.个人中心菜单在管理端可配置化 *【重磅】*

【新增】5.轮播图新增跳转链接包括外链和页面链接

【新增】6.新增帖子上下架系统消息通知的处理

【新增】7.新增圈子页公告栏通知

【优化】8.后台管理系统添加敏感操作日志记录

【优化】9.h5端登录页面重构升级 *【重磅】*

【修复】10.修复帖子列表由于置顶帖导致分页查询不全的问题

【修复】11.修复圈子解散和删除存在的bug



2022.7.1

###### **V1.3.2发布**

1.新增投票贴

2.私聊模块前端样式重构升级

3.系统通知消息统一管理

4.修复苹果机型无法格式化时间的问题

5.修复瀑布流模式下h5可能存在的不兼容

###### **V1.3.1发布**

<u>2022.6.8</u>

1.修复移动端分页功能存在的底部提示bug

2.修复圈子管理员修改圈子背景图无效的bug

3.修复圈子人数展示不统一的问题

4.修复一键已读为空时的异常报错

5.优化圈子查询代码

6.优化帖子分页查询组装代码

7.新增子评论回复时间展示

8.新增帖子列表组件置顶图标展示属性

9.新增发帖时选择话题

10.发帖时间改为新格式

11.新增帖子瀑布流展示风格组件

<u>2022.5.14</u>

###### **V1.3.0发布**

1.优化私聊功能及时性

2.优化阿里云短信验证码和测试阶段的处理

3.优化话题标签删除导致的问题

4.新增用户端圈子管理员圈内删贴功能

5.新增微信小程序端支付

6.新增私信列表历史消息

7.新增付费贴

8.新增积分签到

9.新增余额钱包体系&用户积分体系

10.新增可配置消息清理定时任务

11.新增用户端父子评论长按删除

12.新增管理端模糊查询

13.新增后台管理端用户余额充值

14.修复私信排序问题和查询可能存在的问题

15.修复quartz定时任务暂停和恢复的bug

16.新增h5微信支付

17.新增视频模块和充值模块显示配置

18.新增积分兑换余额模块

<u>2022.5.1</u>

###### **V1.2.3发布**

1.优化私聊功能及时性

2.优化阿里云短信验证码和测试阶段的处理

3.优化话题标签删除导致的问题

4.新增用户端圈子管理员圈内删贴功能

5.新增微信小程序端支付

6.新增私信列表历史消息

7.新增付费贴

<u>2022.4.24</u>

###### **V1.2.2发布**

1.修复H5端回复评论bug； 

2.修复H5端分享图标布局； 

3.修复H5登录同步圈子人数；

4.优化H5端圈子页布局； 

5.优化无效token处理； 

6.新增H5端删除个人帖子选项；

<u>2022.04.17</u>

###### **V1.2.1发布**

1.新增防止重复提交注解

2.扩大匿名访问权限

3.优化小程序登录

4.新增后台前端面板统计数据

5.移动端用户手机号脱敏处理

6.新增帖子上下架处理



<u>2022.04.04</u>

###### **V1.2发布**

 1.优化私聊模块

 2.新增置顶功能

 3.优化UI 

4.优化消息已读未读的处理 

5.其他bug修复



<u>2022.03.05</u>

###### **V1.1发布**

移动端适配H5

移动端分享功能优化

移动端其他bug修复



<u>2022.01.29</u>

###### **V1.0发布**

