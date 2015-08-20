
Chrome+XX-Net
========
项目状态：chrome44.0.2403.155集成xx-net2.07,新用户启动后，需要等待一段时间（十分钟到1小时），扫描到足够ip之后会比较流畅   


下载链接：
==========
https://github.com/yeahwu/wu/releases/download/chrome/CN.GoogleChrome.zip
   
  
  主要特性
========
* 点击chrome.vbs启动，启动前会检测进程，所以不管怎么打开关闭，系统里只保留一个进程。
* 隐藏goagent窗口，隐藏xx-net窗口，去掉弹窗。
* 内置了25个私人appid, 方便新手。
* 自动导入证书，减少大量手动工作。


平台支持情况
================
* Windows XP （需要 tcpip.sys 补丁, 比如用 tcp-z）
* Win7/8/10


证书问题
=========
如果遇到“您的连接不是私密连接”
解决方法：
找到Data\gae_proxy 目录下的 "CA.crt" 证书，双击打开 - 安装证书 - 下一步 - 选择 “将所有的证书放入下列存储” - 浏览 - 选择 “受信任的根证书发布机构” - 下一步 - 完成。重新启动浏览器。


使用方法：
========
* Windows下, 双击 chrome.vbs
  - 托盘图标：点击可弹出Web管理界面, 右键可显示常用功能菜单。
  - Win7/8/10：提示请求管理员权限, 安装CA证书。请点击同意。

感谢
=========
* GoAgent
* GoGoTest
* goagentfindip
* checkgoogleip



附图
======

GAEProxy状态页面

![goagent_status](https://cloud.githubusercontent.com/assets/10395528/5849287/f71c62fc-a1b9-11e4-9ae0-b33fc78ed5fd.png)

GAEProxy 配置页面

![goagent_config](https://cloud.githubusercontent.com/assets/10395528/5849285/f68ac84c-a1b9-11e4-808a-5ec78f2fd3af.png)

GAEProxy 部署服务端页面

![goagent_deploy](https://cloud.githubusercontent.com/assets/10395528/5849286/f6e81dda-a1b9-11e4-94f8-2b9d2492bd39.png)

GAEProxy 查看日志页面

![goagent_log](https://cloud.githubusercontent.com/assets/10395528/5849288/f72138cc-a1b9-11e4-94df-d0b7ab160f0c.png)
