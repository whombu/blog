---
title: 抢答助手使用说明-交部门
tags: 微信小程序
abbrlink: ab566f93
date: 2018-09-28 23:21:46
---
## 概述
`抢答助手`是一款微信小程序，其采用wss技术，支持一个`裁判`和多个`参赛队员`同时在线进行抢答比赛。由`裁判`发起一场抢答比赛，并通过微信邀请其他`参赛队员`进入抢答房间开始抢答比赛。
## 技术路线
`抢答助手`服务端由抢答业务服务、会话服务、信道服务组成。其中`抢答业务服务`负责完成抢答业务功能，由`java`实现；`会话服务`负责为每个微信客户端使用抢答业务服务提供会话支撑，由PHP实现；`信道服务`为抢答业务服务提供客户端`WebSocket`长连接服务，由`java`实现。

`抢答助手`客户端由微信小程序实现，主要负责完成视图展现等功能。
## 操作流程
1. 可通过打开`微信`-`发现`-`微信小程序`，搜索`抢答助手`；也可通过扫描小程序二维码进入`抢答助手`。
2. 进入小程序后，程序会自动提示您进行`获取头像等信息`的授权；
3. 点击最下面的`发起新的抢答比赛`按钮，进入填写基本信息页面；
4. 填写抢答比赛名称，并点击`发起新的抢答比赛`按钮，进入详情页面；
5. 点击`发出比赛邀请`按钮，将比赛分享给好友；
6. 好友通过点击`分享链接`即可作为`队员`进入比赛，参与抢答；
7. 发起人作为`裁判`可在详情页面点击比赛名称面板进入抢答比赛。

## 费用
`抢答助手`小程序服务端采用腾讯云配置为1GB内存、50GB机械硬盘、1CPU、1Mb带宽的云服务器，费用为`￥600元/3年`，续费为`￥700元/年`；注册域名费用为`￥12元/年`；开发调试用的手机和电脑均为组内人员提供。
## 附图
- 二维码
![rcode](https://whombu-blog-1253987194.cos.ap-beijing.myqcloud.com/weapp-qiangdaqi-readme/rcode.jpg)
- 进入小程序
![index](https://whombu-blog-1253987194.cos.ap-beijing.myqcloud.com/weapp-qiangdaqi-readme/index.png)
- 发起一场抢答比赛
![inputname](https://whombu-blog-1253987194.cos.ap-beijing.myqcloud.com/weapp-qiangdaqi-readme/inputname.png)
- 进入分享页面
![share](https://whombu-blog-1253987194.cos.ap-beijing.myqcloud.com/weapp-qiangdaqi-readme/share.png)
- 转发连接
![sharelink](https://whombu-blog-1253987194.cos.ap-beijing.myqcloud.com/weapp-qiangdaqi-readme/sharelink.png)
- 裁判进入
![caipanjinru](https://whombu-blog-1253987194.cos.ap-beijing.myqcloud.com/weapp-qiangdaqi-readme/caipanjinru.png)
- 队员进入
![others](https://whombu-blog-1253987194.cos.ap-beijing.myqcloud.com/weapp-qiangdaqi-readme/others.png)
- 开始抢答比赛
![startgame](https://whombu-blog-1253987194.cos.ap-beijing.myqcloud.com/weapp-qiangdaqi-readme/startgame.png)
![begin](https://whombu-blog-1253987194.cos.ap-beijing.myqcloud.com/weapp-qiangdaqi-readme/begin.png)
![pause](https://whombu-blog-1253987194.cos.ap-beijing.myqcloud.com/weapp-qiangdaqi-readme/pause.png)

