> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [github.com](https://github.com/uniartisan/adblock_list)

> adblock_list 是一个致力于中文区广告过滤、隐私保护的快速迭代规则，以解决现有中文区拦截规则重复、维护缓慢等问题 - uniartisan/adblock_list: adblock_list......

**一个订阅，拦截所有**

[](#说明)说明
---------

这是针对中文区的广告过滤列表，实现了精准的广告屏蔽。

我们的原则是：**减少误杀**

### [](#订阅)订阅

<table><thead><tr><th>列表</th><th>raw</th><th>jsDelivr</th><th>Gitee</th></tr></thead><tbody><tr><td><code>adblock-basic</code></td><td><a href="https://raw.githubusercontent.com/uniartisan/adblock_list/master/adblock.txt" rel="nofollow">link</a></td><td><a href="https://cdn.jsdelivr.net/gh/uniartisan/adblock_list/adblock.txt" rel="nofollow">link</a></td><td><a href="https://gitee.com/uniartisan2018/adblock_list/raw/master/adblock.txt" rel="nofollow">link</a></td></tr><tr><td><code>adblock-lite</code></td><td><a href="https://raw.githubusercontent.com/uniartisan/adblock_list/master/adblock_lite.txt" rel="nofollow">link</a></td><td><a href="https://cdn.jsdelivr.net/gh/uniartisan/adblock_list/adblock_lite.txt" rel="nofollow">link</a></td><td><a href="https://gitee.com/uniartisan2018/adblock_list/raw/master/adblock_lite.txt" rel="nofollow">link</a></td></tr><tr><td><code>adblock-plus</code></td><td><a href="https://raw.githubusercontent.com/uniartisan/adblock_list/master/adblock_plus.txt" rel="nofollow">link</a></td><td><a href="https://cdn.jsdelivr.net/gh/uniartisan/adblock_list/adblock_plus.txt" rel="nofollow">link</a></td><td><a href="https://gitee.com/uniartisan2018/adblock_list/raw/master/adblock_plus.txt" rel="nofollow">link</a></td></tr><tr><td><code>adblock-privacy</code></td><td><a href="https://raw.githubusercontent.com/uniartisan/adblock_list/master/adblock_privacy.txt" rel="nofollow">link</a></td><td><a href="https://cdn.jsdelivr.net/gh/uniartisan/adblock_list/adblock_privacy.txt" rel="nofollow">link</a></td><td><a href="https://gitee.com/uniartisan2018/adblock_list/raw/master/adblock_privacy.txt" rel="nofollow">link</a></td></tr></tbody></table>

*   **Adblock-basic** - 快速、极致的去广告体验
    
*   **Adblock-lite** - 针对移动设备的专用规则
    
*   **Adblock-plus** - 广告，当然一个也不要放过
    
*   **Adblock-privacy** - 你的隐私，在你的手里
    

#### [](#说明-1)说明

*   adblock_basic 是主要面向于中文（尤其是指中国境内）网站而制作的过滤列表。
*   adblock_lite 是面向于中文网站（同上）且针对移动设备优化的过滤列表。
*   adblock_plus 是针对于中文及绝大部分常用网站的过滤列表，提供了高质量的去广告服务。
*   adblock_privacy 阻止互联网常见的隐私跟踪，日志搜集器。

_注意： 如果您使用的是 adblock_base 列表并发现有未过滤广告，您应该先尝试使用 adblock_plus 并复现结果。_

[](#规则来源)规则来源
-------------

**上游规则和自己的补充规则**

### [](#感谢)感谢

*   [Adblock Plus](https://adblockplus.org/) - 畅游清爽洁净的网络！
*   [Adguard](https://adguard.com/) - 世界上最高级的广告拦截程序！
*   [cjx82630/cjxlist](https://github.com/cjx82630/cjxlist) - Adblock Plus EasyList Lite 与 CJX's Annoyance List
*   [Gitee](https://gitee.com/) - 码云 (gitee.com) 是 OSCHINA.NET 推出的代码托管平台。
*   [jsDelivr](https://www.jsdelivr.com/) - A free, fast, and reliable CDN for open source

[](#参与贡献)参与贡献
-------------

本项目分为上游列表和补充列表，如果您想要参与我们，您可以 Fork、Pull request。

1.  **如何参与贡献？**

项目的 dev 文件夹中分别有黑名单和白名单，您可以修改他们并提交，提交要注明广告的复现流程。

2.  **上游列表有误**

反馈英文网站或 EasyList 或 EasyPrivacy 或 Fanboy's Social Blocking List 的问题：请将网址发到 easylist. [subscription@gmail.com](mailto:subscription@gmail.com) 并英文描述

反馈非中英文网站的问题：请查看对应的语言列表 [https://adblockplus.org/zh_CN/subscriptions](https://adblockplus.org/zh_CN/subscriptions)

3.  **如何提问？** [提问的艺术（中文版）](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/master/README-zh_CN.md)

**请注意，提供此翻译的个人及组织不对本项目负责**