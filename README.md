# idea

## 通知Hub

* Notification Hub
* 主要解决问题：对接各个系统的软件，比如Slack等，需要一个IM软件，有的团队不一定需要切换IM，但需要一个集中的通知中心。
* 这里是专做一个通知Hub，集成各个第三方系统，用户可以新增通知，在通知集成列表里订阅。
* 优点：
  * 简单：浏览器通知，无需安装软件，在网页订阅后，只需要开着浏览器（可能不需要开启），即可收到订阅
  * 通知订阅中心：可创建通知集成、订阅通知
* 集成参考：https://bearychat.com/integrations
* 集成参考：https://slack.com/intl/zh-hk/integrations
* 主要形式：浏览器通知、浏览器通知网页（通知消息、通知集成列表、订阅）
* 次要：机器人，发送消息，DevOps。主要解决单项的消息传递问题，使消息双向，或对其他用户广播。

## 内容分享系统

* [Mozilla的Readability](https://github.com/mozilla/readability)
* [Mercury Parser](https://github.com/postlight/mercury-parser)
* [Mercury Parser的在线Converter](https://mercury.postlight.com/amp-converter/)
* 简悦
* Mercury看起来比简悦简洁，且开源，可以做参考
* 简单内容分享站点
* post列表：单篇、系列
* post：url、选择系列、转发人、时间、标签
* 技术类似于Pocket，但面向的场景不太相同，着重于分享：团队、公司、群

## 游戏场景生成图

很多互联网产品在首页呈现用户场景时用了类似下图，每个图都需要前端来实现，即使很多素材可复用，但依旧会花费很多工时。

创建一个游戏，包含很多风格上类似下图的素材，可以自己搭建场景，并让其中的人物可以活动。用户构造好场景后，可以捕捉当前画面，直接作为UI图。

![](images/index_14.png)

## weblin

大学时期玩过的浏览器插件，停留在相同网页的用户可以以人物动画的形式展现在浏览器上，并互相交互。

现在居然还存在，还能服务！！！起码12年了，看起来并没有什么人在用。

* 大规模互联网上，由于人们集中于一些网站，不可能全部展现出来，需要分组，分组策略是个问题。【可行性问题】
* 缺少个性化，动画太古老了，还有点卡。
* 动画其实属于次要，太像玩具。主要还是在环境感受、交互。
* 有一些站点有聊天室的概念，但效果一般，感觉还是人多、分组问题。
  * 比如youtube等视频直播，会有聊天窗口
  * bbs有聊天功能，bbs信息延迟比较高，聊天可以解决。但脱离了bbs的初衷，即用户生产内容。对于专业小群体bbs可能比较合适，不在乎沟通内容，而在乎沟通内容产生的结果、结论。

[CN1662871A - 使访问相同网页的用户能够彼此通信 - Google Patent](https://patents.google.com/patent/CN1662871A/zh)

[weblin](https://www.weblin.io/)
