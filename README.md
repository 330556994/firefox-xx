Chrome+XX-Net
========
* 项目状态：Chome_47.0.2526.73集成XX-Net_2.7.3, 新用户启动后，需要等待一段时间（20分钟到1小时），扫描到足够ip之后会比较流畅  

* 点击Chrome.vbs启动。如果SwitchyOmega插件弹出“你的互联网连接受到控制”，请点击保留更改。

下载链接：
==========
* [Chrome47集成XX-Net_2.7.3  抢先版](https://github.com/yeahwu/chrome-xx/archive/master.zip)

* [Chrome46集成XX-Net_2.6.2  稳定版](https://github.com/yeahwu/chrome-xx/archive/Chrome_46.0.2490.80%E9%9B%86%E6%88%90XX-Net_2.6.2.zip)
   
* [历史版本](https://github.com/yeahwu/chrome/releases)

问题
========
* xp系统问题:
   - 需要 tcpip.sys 补丁, 比如用 tcp-z ，下面是补丁下载地址，将数量调节到2014。    https://github.com/yeahwu/wu/raw/master/WindowsXP-TCPIP-concurrency-count-patch.rar
* 文件解压错误问题: 
   - 请用7-zip解压
* 遇到“您的连接不是私密连接”问题: 
   - 点击chrome菜单 - 设置 - 证书管理 - 导入 - 下一步 - 找到Data\gae_proxy 目录下的 "CA.crt" 证书- 安装证书 - 下一步 - 选择 “将所有的证书放入下列存储” - 浏览 - 选择 “受信任的根证书发布机构” - 下一步 - 完成。重新启动浏览器。

主要特性
========
* 点击Chrome.vbs启动，启动前会检测进程，所以不管怎么打开关闭，系统里只保留一个进程。
* 隐藏goagent窗口，隐藏xx-net窗口，去掉弹窗。
* 自动导入证书，减少大量手动工作。
* 内置了80个私人appid, 方便新手。（老手请换上自己的APPID）下面是申请、使用appid的详细教程：https://github.com/XX-net/XX-Net/wiki/how-to-create-my-appids

平台支持情况
================
* Windows XP （需要 tcpip.sys 补丁, 比如用 tcp-z）
* Win7/8/10

使用方法：
========
* Windows下, 双击 Chrome.vbs，不用任何配置。
  - 托盘图标：点击可弹出Web管理界面, 右键可显示常用功能菜单。
  - Win7/8/10：提示请求管理员权限, 安装CA证书。请点击同意。

联系
======
* [Google](https://plus.google.com/communities/101215702940766881013)
* [Twitter](https://twitter.com/yeahwu404)

感谢
=======
* XX-Net
* GoAgent
* GoGoTest
* goagentfindip
* checkgoogleip
* PortableApps

附图
======

chrome状态页

![chrome_status](https://github.com/yeahwu/wu/blob/master/chrome1.JPG?raw=true)

GAEProxy状态页面

![goagent_status](https://github.com/yeahwu/wu/blob/master/chrome2.JPG?raw=true)

