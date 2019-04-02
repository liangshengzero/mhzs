# 麻花助手（Xposed Plugin）

麻花助手，这是一款Xposed插件，旨在净化麻花影视手机版/贝贝影视手机版。当前是功能还不是很完善，使用软件时注意**助手所支持的麻花影视
 版本**，现已**支持 EdXposed 框架**，**支持太极(TaiChi)框架**。
 目前插件在逍遥安卓模拟器4.4/5.1/7.1下，均测试成功。
 
收到很多热心的用户赞助，我在这里感谢大家对我的支持和信任。
与此同时，我也收到了很多用户对插件兼容性较差的反馈和增加功能的反馈，当然由于Android设备的开源和国产的ROM太多，有些兼容性问题可能会永远无法解决，但是我会尽力而为。
收到最多反馈的就是太极框架(Tai-Chi)了，这也是我最头痛的问题，这可能是由于太极框架兼容性的原因。

**目前收到最多反馈的是，部分设备安装助手后任务消失，该问题的解决办法是，先在助手中关闭插件，然后正常启动“麻花影视”，打开任务页面正常显示后，再重新开启助手即可。**

## 功能特性

麻花助手目前拥有以下功能 [目前支持最新2.7.0版本]

1. 支持 EdXposed 框架，太极(TaiChi)框架  
2. 去除启动页广告  
3. 去除启动页5s倒计时  
4. 去除启动页历史广告显示  
5. 去除“推荐”、“电影”、“电视剧”页面中存在的广告  
6. 去除视频播放页面的广告  
7. 自定义主界面底部选项卡  
8. 去除主界面升级提示  
9. 获取视频播放地址（测试）  
10. ~~去除底部滚动广告（测试）~~  
11. 免特权投屏（测试）  
12. 强制微信分享成功（测试）  
13. 自动签到（测试）  
14. 观看视频时长30分钟+（测试）
15. 假装分享（测试）

## 功能截图

* 假装分享

<figure class="half">
    <img src="https://github.com/1595901624/mhzs/blob/master/img/share.gif?raw=true">
</figure>

## 版本对应

* 麻花影视 2.6.1——麻花影视助手 0.1 - 0.6.12
* 麻花影视 2.7.0/贝贝影视2.7.0——麻花影视助手 0.7.0
   
## 使用帮助
   
   **麻花助手**首次运行时，在 Android6.0 + 的设备上需要申请读写SD卡权限，请给予其权限。
   目前**麻花助手**还处于测试期间，功能还不是很完善，在部分设备上运行可能会出现问题。
   首次运行**麻花助手**模块，请重新启动手机(Xposed模块需要)。当然软件已经开源，
   如果您是开发者，您可以定制您需要的功能。部分功能介绍如下：
     
   1. “**全局设置**”——您可以选择是否启用插件，如果此选项为“否”，那么所有的功能都将会禁用  
   2. “**详细设置**”——目前包含“**广告净化**”，“**底部栏设置**”，“**去除5s启动**”三个设置  
   3. “**广告净化**”——可以自定义广告净化 
   4. “**底部栏设置**”——可以自定义首页底部五个选项卡的显示与隐藏  
   5. “**去除5s启动**”——开启后，可自动进入首页; 
   6. “**实验性功能**”——在此选项内的所有功能都是测试功能，在某些设备上可能会无效，希望大家多多反馈此选项下的功能   
   7. “**获取视频地址**”——该功能尚处于测试阶段。开启后，将会在视频播放页面添加四个按钮，分别是360P,480P,720P,1080P，点击即可自动复制到剪切板。
   如果没有蓝光特权，则将无法获取到1080P地址。获取到的视频地址是**.m3u8格式**,播放链接的时效性仅有几小时且直接复制到浏览器无法播放，
   请使用视频播放器或者是m3u8视频解析链接播放。**如果播放时一直是0KB/s，请复制该链接至站外或者电脑上播放**
   8. “**强制微信分享成功**”——**该功能将会“假装分享”取代**。被该功能是有部分用户反馈在太极(Tai-Chi)下无法分享成功而开发的。该模块启用后，通过微信分享到群或者朋友圈，
   无论分享成功与失败，都会返回成功状态。**提示：可在模拟器下使用(下载微信后无须登录微信)，分享后立即返回即可**
   9. “**免特权投屏**”——该功能是测试功能，可能会无效，如果无效希望大家反馈问题。
   10. “**自动签到**”——该功能可以说是半自动签到，只有当用户登录后，点击到任务页面，才会自动签到。
   11. “**观看视频30分钟+**”——开启该功能后，播放任意视频即可完成观影30分钟的任务。
   12. “**假装分享**”——此功能开启后，由于优先级较高，将会覆盖“强制微信分享成功”，如果您的设备测试此功能没有问题，则请您关闭“强制微信分享成功”功能。支持微信朋友圈、微信、QQ、QQ空间、微博分享，点击分享不会跳转APP，也不会提示分享成功，但是状态时成功的。本功能可以用来获取热门视频播放和完成分享任务。
   
   注：目前助手没有检查更新功能，大家可以从Github或者蓝奏云下载最新版本(地址在下方)。
   
## 问题反馈
* 应用内反馈
* 提交 issue
* 发邮件至 haoyu3@163.com ，邮件主题注明“**麻花助手+版本号+框架名称**”

## Wiki

* [码云](https://gitee.com/haoyu3/mhzs)
* [开发进度](https://github.com/1595901624/mhzs/wiki/开发进度)
* [扩展插件](https://github.com/1595901624/mhzs/wiki/扩展插件)
* [更新日志](https://github.com/1595901624/mhzs/wiki/更新日志)
* [Github下载地址](https://github.com/1595901624/mhzs/releases)
* [蓝奏云下载地址](https://www.lanzous.com/b614986/)   密码:4uk6


## 捐赠与致谢

##### 捐赠名单

<!--**`*建鑫`**、**`*思源`**、**`*堃`**、**`*成`**、**`*凯`**、**`*炳亮`**、**`*佳旺`**-->
**`*建鑫` ￥20.00**  
**`*思源` ￥04.00**  
**`*堃` ￥02.00**  
**`*羽` ￥00.38**  
**`*成` ￥00.10**  
**`*凯` ￥00.10**  
**`*学` ￥00.10**  
**`*源` ￥00.02**  
**`*炳亮` ￥00.01**  
**`*佳旺` ￥00.01**

非常感谢你们的捐助！

##### 致谢名单

**[`a2212997715`](https://github.com/a2212997715)**、**`晓星`**、**[`Czy492`](https://github.com/Czy492)**、**[`AceMONKEY519`](https://github.com/AceMONKEY519)**  

##### 捐赠二维码

**推荐通过扫码领红包的方式捐赠哟**

<figure class="half">
    <img src="https://github.com/1595901624/mhzs/blob/master/lucky.jpg?raw=true">
    &nbsp;
    <img src="https://github.com/1595901624/mhzs/blob/master/alipayc.jpg?raw=true">
    <!--&nbsp;-->
    <!--<img src="https://github.com/1595901624/mhzs/blob/master/wechatc.jpg?raw=true">-->
</figure>


<!--![支付宝捐赠](https://github.com/1595901624/mhzs/blob/master/alipayc.jpg?raw=true)-->

<!--![微信捐赠](https://github.com/1595901624/mhzs/blob/master/wechatc.jpg?raw=true)-->

   
