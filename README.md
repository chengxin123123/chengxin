# 橙心代理帮助手册

使用橙心代理首先要安装 shadowsocks 软件。

## 1. 如何安装？

### 1.1 windows 安装

下载 [shadowsocks](https://github.com/shadowsocks/shadowsocks-windows/releases/download/4.0.7/Shadowsocks-4.0.6.zip)

[备用下载地址](http://www.dahouduan.com/wp-content/uploads/2018/01/Shadowsocks-4.0.6.zip)

如果你的 windows 系统版本在 windows 10 以下，需要安装
[.NET Framework 4.6.2](https://www.microsoft.com/zh-CN/download/details.aspx?id=53344)

在桌面（或者其他位置也可以）创建一个名为 “shadowsocks” 目录，
解压 Shadowsocks-4.0.6.zip 到 “shadowsocks” 目录，运行 shadowsocks.exe


### 2.1 Mac 安装


### 2.2 

## 2. 配置及使用

### Windows

在任务栏找到 shadowsocks 图标，
点击图标弹出菜单栏，选择 “ 服务器 -> 编辑服务器”， 弹窗窗口如下图：


![](http://img.blog.csdn.net/20170318225018697?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzM2MDg1MA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

**在服务器地址、服务器端口、密码处分别填入管理员分配给你的帐号信息。**

点“确定”保存。

然后

- 勾选“启用系统代理”，
- 勾选“服务器->ip：端口”，
- 勾选“系统代理模式->pac 模式”
![](http://img.blog.csdn.net/20170318225041970?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvdTAxMzM2MDg1MA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)


打开你的浏览器，地址栏输入"http://www.google.com" 看看是不是可以打开了。

## 说明

- Pac 模式会判断你要访问的地址，如果是需要翻墙的地址就会走翻墙线路，不需要的就走正常线路，比如你访问baidu就走正常路线，访问google 就走翻墙线路，如果你勾选了“系统代理模式->全局模式”，这时不论访问任何地址都会走翻墙路线。


## 故障排查

1. 如果发现google打不开，先检查你的浏览器是否已经安装了其他的翻墙插件，请先禁用这些插件。
2. 检查你是否启动了其他翻墙软件，请关闭这些软件。
3. 按照教程重新操作一遍，如果还不能解决问题，请联系管理员。
