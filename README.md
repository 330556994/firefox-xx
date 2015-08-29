
Chrome+XX-Net
========
* 项目状态：chrome_44.0.2403.157集成xx-net_2.12, 新用户启动后，需要等待一段时间（30分钟到1小时），扫描到足够ip之后会比较流畅   


下载链接：
==========
* 本地：https://github.com/yeahwu/wu/releases/download/chrome/GoogleChrome212.zip
* 腾讯微云：（有效期一个星期）http://share.weiyun.com/be93a551e9442f8149fc73a57cb0eafa
   

问题
========
* xp系统问题:
   - 需要 tcpip.sys 补丁, 比如用 tcp-z
* 文件解压错误问题: 
   - 请用7-zip解压
* 遇到“您的连接不是私密连接”问题: 
   - 点击chrome菜单 - 设置 - 证书管理 - 导入 - 下一步 - 找到Data\gae_proxy 目录下的 "CA.crt" 证书- 安装证书 - 下一步 - 选择 “将所有的证书放入下列存储” - 浏览 - 选择 “受信任的根证书发布机构” - 下一步 - 完成。重新启动浏览器。


主要特性
========
* 点击chrome.vbs启动，启动前会检测进程，所以不管怎么打开关闭，系统里只保留一个进程。
* 隐藏goagent窗口，隐藏xx-net窗口，去掉弹窗。
* 自动导入证书，减少大量手动工作。
* 内置了50个私人appid, 方便新手。（老手请换上自己的APPID）下面是申请appid的详细教程，做完一、二步即可。然后把申请到的id填入xx-net主页，配置项，完成。  https://github.com/phuslu/goproxy/blob/wiki/InstallGuide.md


平台支持情况
================
* Windows XP （需要 tcpip.sys 补丁, 比如用 tcp-z）
* Win7/8/10




使用方法：
========
* Windows下, 双击 chrome.vbs，不用任何配置。
  - 托盘图标：点击可弹出Web管理界面, 右键可显示常用功能菜单。
  - Win7/8/10：提示请求管理员权限, 安装CA证书。请点击同意。


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

![chrome_status](http://a.hiphotos.baidu.com/image/pic/item/cdbf6c81800a19d88406df6235fa828ba61e464b.jpg)

GAEProxy状态页面

![goagent_status](https://cloud.githubusercontent.com/assets/10395528/5849287/f71c62fc-a1b9-11e4-9ae0-b33fc78ed5fd.png)

