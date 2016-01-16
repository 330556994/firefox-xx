Firefox+XX-Net
-------------
* 项目状态：Firefox43.0.4集成XX-Net_2.8.9, 懒人翻墙包。点击 Firefox-XX.vbs启动 ，初次运行请等待10分钟左右，扫到足够ip后会更流畅。

下载链接：
--------
* Firefox43.0.4集成XX-Net_2.8.9  测试版   [本地下载](https://github.com/yeahwu/firefox-xx/archive/master.zip)

* Firefox43.0.4集成XX-Net_2.8.9  测试版   [Dropbox下载](https://www.dropbox.com/s/kxsxqx4xn15zf9n/Firefox-XX.7z?dl=0)

使用方法：
----------
* Windows下, 点击 Firefox-XX.vbs启动，不用任何配置。
  - Win7/8/10：提示请求管理员权限, 安装CA证书。请点击同意。
  - 托盘图标：点击可弹出Web管理界面, 右键可显示常用功能菜单。

问题
-----
* xp系统问题:
   - 需要 tcpip.sys 补丁, 比如用 tcp-z ，下面是补丁下载地址，将数量调节到2014。    https://github.com/yeahwu/wu/raw/master/WindowsXP-TCPIP-concurrency-count-patch.rar

* 遇到“您的连接不是私密连接”问题: 
   - 点击Firefox菜单 - 选项 - 高级 - 证书 - 查看证书 - 导入 - 找到Data\gae_proxy 目录下的 "CA.crt" 证书 - 弹出的“下载证书”窗口 - 选择"信任使用此CA标识的网站"，确定  - 确定。重新启动浏览器。

主要特性
--------
* 点击Firefox-XX.vbs启动，启动前会检测进程，所以不管怎么打开关闭，系统里只保留一个进程。
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

火狐状态页

![chrome_status](https://raw.githubusercontent.com/yeahwu/wu/master/firefox0.JPG)

GAEProxy状态页面

![goagent_status](https://raw.githubusercontent.com/yeahwu/wu/master/firefoxxx.JPG)

