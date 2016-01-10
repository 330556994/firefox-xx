Chrome+XX-Net
-------------
* 项目状态：Chome_47.0.2526.80集成XX-Net_2.8.9, 懒人翻墙包。点击 Chrome-XX.vbs启动 ，初次运行请等待10分钟左右，扫到足够ip后会更流畅。

下载链接：
--------
* Chrome47集成XX-Net_2.8.9  正式版 [本地下载](https://github.com/yeahwu/chrome-xx/archive/master.zip)

* Chrome47集成XX-Net_2.7.3  稳定版 [本地下载](https://github.com/yeahwu/chrome-xx/archive/Chome_47.0.2526.80%E9%9B%86%E6%88%90XX-Net_2.7.3.zip)
   
* [历史版本](https://github.com/yeahwu/chrome/releases)

使用方法：
----------
* Windows下, 点击 Chrome-XX.vbs启动，不用任何配置。
  - SwitchyOmega插件：弹出“你的互联网连接受到控制”，请点击保留更改。
  - Win7/8/10：提示请求管理员权限, 安装CA证书。请点击同意。
  - 托盘图标：点击可弹出Web管理界面, 右键可显示常用功能菜单。

问题
-----
* xp系统问题:
   - 需要 tcpip.sys 补丁, 比如用 tcp-z ，下面是补丁下载地址，将数量调节到2014。    https://github.com/yeahwu/wu/raw/master/WindowsXP-TCPIP-concurrency-count-patch.rar
* 遇到“password is wrong”问题: 
   - 主要是公共appid设置了rc4密码导致的,新版已修复。另外由于appid不够用也会出现这种问题，下午4点以后id重置后就可以连接了。
* 遇到代理插件损坏问题:
   - 这是由于github自动压缩导致的，重新下载，或者点击dropbox下载，即可解决。
* 遇到“您的连接不是私密连接”问题: 
   - 点击chrome菜单 - 设置 - 证书管理 - 导入 - 下一步 - 找到Data\gae_proxy 目录下的 "CA.crt" 证书- 安装证书 - 下一步 - 选择 “将所有的证书放入下列存储” - 浏览 - 选择 “受信任的根证书发布机构” - 下一步 - 完成。重新启动浏览器。

主要特性
--------
* 点击Chrome-XX.vbs启动，启动前会检测进程，所以不管怎么打开关闭，系统里只保留一个进程。
* 隐藏goagent窗口，禁止启动弹窗，禁止创建桌面xx-net快捷方式。
* 自动导入证书，减少大量手动工作。
* 内置了150个私人appid, 方便新手。

创建个人APPID
-----------
* 详细图文教程：https://github.com/XX-net/XX-Net/wiki/how-to-create-my-appids

平台支持情况
------------
* Windows XP （需要 tcpip.sys 补丁, 比如用 tcp-z）
* Win7/8/10

联系
-------
* [Google+](https://plus.google.com/communities/101215702940766881013)
* [Twitter](https://twitter.com/yeahwu404)

感谢
-------
* XX-Net
* GoAgent
* GoGoTest
* goagentfindip
* checkgoogleip
* PortableApps
* 无私奉献APPID的网友

附图
--------

chrome状态页

![chrome_status](https://github.com/yeahwu/wu/blob/master/chrome1.JPG?raw=true)

GAEProxy状态页面

![goagent_status](https://github.com/yeahwu/wu/blob/master/chrome2.JPG?raw=true)

