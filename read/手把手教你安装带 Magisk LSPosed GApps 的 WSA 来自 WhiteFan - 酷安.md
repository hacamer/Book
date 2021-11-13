> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [www.coolapk.com](https://www.coolapk.com/feed/31018494?shareKey=YmEyMmNhNmZjYzA5NjE3YWFjMDM~&shareUid=11455514&shareFrom=com.coolapk.market_11.4.4)

> # 前言 #Windows11# 第一个有谷歌服务的 WSA Github 地址：查看链接

# 前言 [#Windows11#](https://www.coolapk.com/t/Windows11?type=12)  
![](http://static.coolapk.com/emoticons/v9/coolapk_emotion_1011_hengji.png)第一个有谷歌服务的 WSA  
Github 地址：[查看链接](https://github.com/LSPosed/MagiskOnWSA "https://github.com/LSPosed/MagiskOnWSA")

此项目集成了 Magisk、LSPosed、OpenGApps 等多个项目文件，可自行前往编译

，或在此处下载编译好的文件

其实如何编译如何安装在 GitHub 项目的 Readme 文件里已经写的很详细了，建议有一定基础的快速划一遍就去 github 上看吧![](http://static.coolapk.com/emoticons/v9/coolapk_emotion_1011_hengji.png)教程还算比较详细的啦

# 安装教程

1. 卸载 WSA  
①如果安装过的话，直接卸载就行了  
②如果没有安装过的，先做一下图里的操作勾选一下

![](http://image.coolapk.com/feed/2021/1030/00/2616217_79779399_5180_1823@1499x962.png.m.jpg)

转自酷友 @的图（）

2. 下载 [#WSA#](https://www.coolapk.com/t/WSA?type=12) 安装文件  
这里是我在 github 上下载的编译好的，也有我自己在 github 上编译的，都可以使用。  
下载地址：[查看链接](https://cloud.189.cn/t/BZrqimyMv6jy "https://cloud.189.cn/t/BZrqimyMv6jy")  
挂载盘总是炸，先用天翼的链接吧

文件名最后的几个字母表示 GApps 的完整度，文件越大集成的 APP 越多，运行起来可能也会越卡，推荐下载 Pico 版本的

3. 解压 WSA  
解压的位置就是你的 wsa 要安装的位置哦

4. 开启 Windows 开发者模式

![](http://image.coolapk.com/feed/2021/1028/16/2616217_28649868_9210_9954@870x796.jpeg.m.jpg)

5. 以管理员模式运行 Powershell

![](http://image.coolapk.com/feed/2021/1028/16/2616217_5fef8e9f_9210_9956@779x768.jpeg.m.jpg)

在刚刚解压的 WSA 文件夹下运行命令

Add-AppxPackage -Register .\AppxManifest.xml

![](http://image.coolapk.com/feed/2021/1028/16/2616217_dfe0762b_9210_9958@859x191.jpeg.m.jpg)

6. 等待安装完成后，启动 WSA、开启开发者模式、打开开发者管理，刷新 IP

![](http://image.coolapk.com/feed/2021/1028/16/2616217_50196847_9210_9959@1920x1006.jpeg.m.jpg)

7. 安装 Magisk app

上面的链接里有 apk 文件了，下载下来，安装 apk 推荐使用 “秋之盒” 或者“WsaToolbox”

![](http://image.coolapk.com/feed/2021/1028/16/2616217_89ed1fe8_9210_9961@1036x643.jpeg.m.jpg)

8. 启动 Magisk

自动修复环境并重启，这就 OK 了

![](http://image.coolapk.com/feed/2021/1028/16/2616217_4de8fed7_9210_9963@772x463.jpeg.m.jpg)

9. 安装 riru... 装模块吧  
模块都是 zip 格式的文件，不需要解压，点击下面的【从本地安装】就可以了

![](http://image.coolapk.com/feed/2021/1028/16/2616217_b22ca635_9210_9964@865x679.jpeg.m.jpg)

10. 安装 LSPosed  
推荐安装酷安、微软桌面、搞机助手、MT 管理器，root 权限在 magisk 里授权

打开 mt 管理器，侧栏点击终端模拟器等待加载完成（加载搞机助手运行环境）  
打开搞机助手（上面的链接里有我用的 apk 安装包）

，在 magisk 模块里依次安装 riru、riru-lsposed，在 xposed 模块里安装 lsposed 管理器，重启，就有 lsoposed 了

找不到模块下载的话，可以去搞机助手、爱玩机工具箱... 这些软件里下载，哦对，酷安的 [#那些好用的 magisk 模块#](https://www.coolapk.com/t/%E9%82%A3%E4%BA%9B%E5%A5%BD%E7%94%A8%E7%9A%84magisk%E6%A8%A1%E5%9D%97?type=12) 话题里也有很多模块