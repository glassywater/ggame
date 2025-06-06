---
title: "clientHold"
description:
published: true
date: "2025-05-25T21:51:45"
特殊标签标记: #无标签
editor: markdown
dateCreated: "2024-07-16T15:09:20"
---

## 简介

「域名注册局」需要与「域名注册商」之间通信，时刻处理注册或续订的域名交易，所以出现了
<ruby>Extensible Provisioning Protocol<rt>可扩展供应协议</rt></ruby>（EPP）来作为通信协议。

`clientHold` 是客户端，即「域名注册商」设置的 EPP 对象状态代码。通常用于所有权争议、付款争议，或者诈骗、骚扰。
此时域名解析会被暂停，网站无法访问，除非 DNS 服务器的缓存过旧。

附言：「域名注册局」是负责创建、管理和维护域名注册信息的机构。而「域名注册商」是面向个人销售域名的机构。

## 牛博网

[牛博网](/website/牛博网.md) 是罗永浩建立并运营的博客提供商。

2009年1月9日，牛博网无法访问。罗永浩透露：收到服务商万网的通知，称该博客存在有害信息，被要求整改，
因此万网需要停止该 `.cn` 域名的访问权限，随即网站被 `clientHold`。[^1654]

[^1654]: 月光, 《[警告——不要在国内注册和使用CN域名](https://web.archive.org/web/20240717052859/https://www.williamlong.info/archives/1654.html)》, 月光博客, 2009-01-12. (参照 2024-07-17).

2012年7月14日，罗永浩在新浪微博称，发现牛博网的域名 `bullog.cn` 已易主，变成了「天猫网」。
所以质疑万网在没有提醒续费的通知的情况下，偷走了自己的域名。[^34453]

[^34453]: 上方文Q, 《[罗永浩牛博网“复活” 却成购物导航网站](https://web.archive.org/web/20120718191052/http://news.mydrivers.com/1/234/234453.htm)》, 驱动之家, 2012-07-16. (参照 2024-07-22).

2012年7月16日，罗永浩在新浪微博道歉：「向万网正式公开道歉！谢罪！对不起！」。其实是有提醒续费的邮件，
只是管理域名的李笑来，没有登录万网官网，所以没有看到续费通知。[^34591]

[^34591]: 上方文Q, 《[罗永浩向万网公开致歉](https://web.archive.org/web/20120720011152/http://news.mydrivers.com/1/234/234591.htm)》, 驱动之家, 2012-07-17. (参照 2024-07-22).

## 电玩巴士

电玩巴士是中文单机、主机游戏社区网站，是含有游戏新闻、资源以及论坛的综合性网站。

2009年2月20日，[^82886] 电玩巴士无法访问，域名状态为 `clientHold`。[^1710][^9686] 电玩巴士宣称是「内部维护工作」。[^68399]

[^1710]: 月光, 《[域名还放在国内的，立刻转出去吧](https://web.archive.org/web/20240328212656/https://www.williamlong.info/archives/1710.html)》, 月光博客, 2009-02-26. (参照 2024-07-17).

[^9686]: 《[电玩巴士域名被暂停解析](https://web.archive.org/web/20240717054554/https://www.youming.net/news/9686.html)》, 有名科技资讯, 2009-02-25. (参照 2024-07-17).

[^82886]: 匿名人士, 《[电玩巴士原域名恢复访问](https://web.archive.org/web/20090625100111/http://www.cnbeta.com/articles/82886.htm)》, cnBeta.COM, 2009-04-28. (参照 2024-07-17).

[^68399]: 杨虞波罗, 《[电玩巴士域名解析被停　万网作出声明](https://web.archive.org/web/20090228140327/http://game.people.com.cn/GB/48644/48662/8868399.html)》, 人民网／游戏频道, 2009-02-25. (参照 2024-07-17).

2009年2月25日，万网市场部助理副总裁陶丽正式回应了该事件，表示 20 日接到了工信部的通知，
需要对部分域名执行停止解析的操作。因此导致电玩巴士域名被设置为 `clientHold`，不过陶丽认为是保密文件，
所以没有提供被设置为 `clientHold` 的万网域名清单。

2009年2月26日，电玩巴士启用了临时域名：`5068.com`。[^82886]

2009年4月27日，电玩巴士的域名 `tgbus.com` 恢复访问，不过电玩巴士始终没有对此事评论。同日，临时域名被关闭。[^82886]

## 多玩游戏网

多玩游戏网（`duowan.com`）属于游戏门户网站，类似于电玩巴士，旗下还有代理网页游戏、YY 语音以及多玩英雄联盟盒子等产品。

2009年2月26日，多玩游戏网的域名，被观察到处于 `clientHold` 状态，注册商是「35互联」。好在同样是游戏门户网站的游久网，
在首页贴出了多玩网的备用域名（`duowan.cn`），帮助同类网站。[^9695][^68024][^7481]

[^9695]: 《[多玩网遭遇电玩巴士事件](https://web.archive.org/web/20240717143710/https://www.youming.net/index.php/news/9695.html)》, 有名网资讯平台, 2009-02-26. (参照 2024-07-17).

[^68024]: 《[多玩游戏网主域名遭停止解析 游久网关键时刻伸出橄榄枝](https://web.archive.org/web/20201123202153/https://www.chinaz.com/news/2009/0226/68024.shtml)》, 站长之家, 2009-02-26. (参照 2024-07-17).

[^7481]: have, 《[多玩网遭遇电玩巴士事件](https://web.archive.org/web/20240717135922/https://www.free8.net/thread-7481-1-1.html)》, 免费吧论坛／资源交流, 2009-02-28. (参照 2024-07-17).

不过值得注意的是，原域名 `duowan.com` 有进行信产部的备案，而 `duowan.cn` 反而没有备案。[^9695]
然后多玩域名的恢复时间，大约是在 2009年2月28日，因为 Internet Archive 此时留有记录。[^20090]

[^20090]: [http://www.duowan.com/](https://web.archive.org/web/20090000000000*/http://www.duowan.com/), Wayback Machine, 2009-. (参照 2024-07-18).

## 2010年1月

2010年1月5日，注册商「新网」对多个域名设置为了 `clientHold` 状态，被注意到的有社交网站「51网」，[^54720][^92567][^915BF]
IT 资讯网站「IT168」，[^43227] 以及博客托管网站「博客大巴」。[^24556][^29530][^2045]

[^54720]: 《[关于51.com](https://web.archive.org/web/20121204054720/http://www.51.com/company/)》, 51.COM, 2012-12-04. (参照 2024-07-18).

[^92567]: DONEWS, 《[新网证实停止51.com域名解析 但拒绝透露原因](https://web.archive.org/web/20120730230457/http://it.sohu.com/20100105/n269392567.shtml)》, 搜狐IT, 2010-01-05. (参照 2024-07-18).

[^915BF]: 网易科技报道, 《[新网暂停解析51.com及IT168等网站域名](https://web.archive.org/web/20100519205425/http://tech.163.com/10/0105/17/5S9GP09A000915BF.html)》, 网易科技, 2010-01-05. (参照 2024-07-19).

[^43227]: 《[IT168 - IT主流资讯平台](https://web.archive.org/web/20091128143227/http://www.it168.com/)》, 2009-11-28. (参照 2024-07-18).

[^24556]: 《[博客大巴 - 免费申请博客网志注册你自己的个人Blog网站空间](https://web.archive.org/web/20091128224556/http://www.blogbus.com/)》, 2009-11-28. (参照 2024-07-18).

[^29530]: 京华时报／彭科峰, 《[网站域名被屏蔽 百万用户上不了"博客大巴"](https://web.archive.org/web/20110808001713/http://it.people.com.cn/GB/42891/42894/10729530.html)》, 人民网, 2010-01-08. (参照 2024-07-19).

[^2045]: 月光, 《[新网停止多个知名网站域名解析](https://web.archive.org/web/20240328212656/https://www.williamlong.info/archives/2045.html)》, 月光博客, 2010-01-05. (参照 2024-07-18).

2010年1月6日，51 网恢复了解析。而更早之前，IT168 以及博客大巴也恢复了正常运营，
但站方并未公开取消解析的原因。[^16858][^915BF]

[^16858]: 王华东, 《[51.com恢复正常访问 解决域名解析问题](https://web.archive.org/web/20120731025035/http://it.sohu.com/20100106/n269416858.shtml)》, 搜狐IT, 2010-01-06. (参照 2024-07-18).

2010年1月21日，TechWeb 的域名被停止解析。分别是 2010年1月21日 的 `techweb.com.cn`，[^53011] 22 日的 `techweb.com`，
以及 25 日的 `techweb.cn`。[^54946] 8 天的奔波后，才解决了域名的问题。执行董事后来在《创业家》杂志提到了细节：
「大概是因为回帖里有一条垃圾广告帖，卖治疗阳痿、早泄的医疗器械，里面提到了生殖器的名称。我猜是这条信息。其实，
到现在也没人正式告诉我，到底是哪条违了规……我不明白，我们解决30多人的就业，我们给政府纳税，我们做错了什么？
凭什么工信部的一道行政命令就让我的公司险些面临清盘？」

[^53011]: 陈中, 《[TechWeb.com.cn域名停止解析](https://web.archive.org/web/20110909064806/http://it.sohu.com/20100121/n269753011.shtml)》, 搜狐IT, 2010-01-21. (参照 2024-07-18).

[^54946]: 《[篱笆网被封前其他网站的遭遇](https://web.archive.org/web/20231210054946/https://www.aladown.com/2010/01/篱笆网被封前其他网站的遭遇/)》, ALADOWN-阿拉下载, 2010-01-27. (参照 2024-07-18).

2010年1月25日，篱笆网的域名 `liba.com`，被发现处于 `clientHold` 状态。[^8530s][^60932] 新网上的 whois 查询中，
能看到暂停原因是：「接到上级主管部门通知，域名对应的网站涉嫌传播淫秽色情、贩卖枪支等违法信息，
已停止域名的解析服务。」[^915BF][^58012]然后篱笆网启用了备用域名 `libalife.com` 和 `libaclub.com`，
但是篱笆网副总裁否认了新网的说法，只表示新网的域名解析服务器出现了系统故障。[^58012]
篱笆网的公司高层，也在 27 日飞赴北京，与域名服务商新网沟通。[^50352]〔后续情况暂无资料〕

[^8530s]: 深圳特区报, 《[舜网因涉黄被关闭４２小时](https://web.archive.org/web/20100206034025/http://news.sina.com.cn/c/2010-01-30/085717018530s.shtml)》, 新浪新闻, 2010-01-30. (参照 2024-07-18).

[^60932]: 《[域名被服务商clientHold 域名被Hold怎么办？](https://web.archive.org/web/20120906043157/http://www.51jiji.com/Service/FAQ/Domain/1560932.html)》, 北京做网站首选积极工作室. (参照 2024-07-18).

[^915BF]: 网易科技报道, 《[篱笆网遭新网停止域名解析服务](https://web.archive.org/web/20110904001253/http://tech.163.com/10/0126/10/5TUR6JP8000915BF.html)》, 网易科技, 2010-01-26. (参照 2024-07-18).

[^58012]: 周凯, 彭晓玲和康菲辰, 《[篱笆网被指“涉黄”，两天没法上](https://web.archive.org/web/20100412053205/http://www.jfdaily.com/a/858012.htm)》, 解放牛网, 2010-01-27. (参照 2024-07-18).

[^50352]: 《[篱笆网无法登录，多位高层昨赴京沟通](https://web.archive.org/web/20240305050352/https://www.aladown.com/2010/01/篱笆网无法登录-多位高层昨赴京沟通/)》, ALADOWN-阿拉下载, 2010-01-28. (参照 2024-07-18).

2010年1月27日，济南日报报业集团主办的「舜网」`e23.cn`，域名被万网暂停解析。[^60932]
在站方向 CNNIC 提交申诉后，域名在 1月29日 恢复解析。[^04184]

[^04184]: 《[舜网就无法访问发声明:万网称接通知即锁定域名](https://web.archive.org/web/20100924195502/http://china.huanqiu.com/roll/2010-01/704184.html)》, 环球网, 2010-01-29. (参照 2024-07-19).

## 保证书的世界

该部分内容较多，现已成为独立条目：〈[保证书的世界](/meme/保证书的世界.md)〉。

## 玩聚SR

2010年3月25日，类 Techmeme 和 Digg 网站「玩聚SR」（玩聚网），由于网站整改与内容精确性的矛盾，站长不再前往管理部门，
接受电话通知的谈话。不过第二天网站域名，就被以 `clientHold` 状态停止解析了。[^80233] 此后网站更换了备用域名，
但仍被停止解析。2010年10月，机房的主机也被没收，玩聚 SR 也就这么死去了。[^01120]

[^80233]: 《[玩聚网Beta | 聚了就灵](https://web.archive.org/web/20100902080233/http://www.ju690.cn/)》, 2010-09-02. (参照 2024-07-18).

[^01120]: 曹国星, 《[玩聚网的消失：言论监管下中国网站的生存状态](https://web.archive.org/web/20200214053454/http://www.rfi.fr/cn/中国/20101120-玩聚网的消失：言论监管下中国网站的生存状态)》, RFI - 法国国际广播电台, 2010-11-20. (参照 2024-07-18).

## 时光网

2010年10月14日，影迷社区「时光网」的域名被发现处于 `clientHold` 状态。[^22048] 而稍早前，
网页上还有「系统维护中」的提示。《沈阳晚报》提到多数网友认为问题出在国产电影评分上，
因为时光网用户对国产电影态度「不够宽容」，导致保护国产电影的相关部门难以接受。[^9305] 譬如时光网友，
对《建国大业》和《山楂树之恋》的打分太低了。[^24300]

[^22048]: TanCee, 《[时光网域名被clientHold无法访问解决方法](https://web.archive.org/web/20231211222048/https://www.chinagfw.org/2010/10/clienthold.html)》, 功夫网与翻墙, 2010-10-16. (参照 2024-07-18).

[^9305]: 关力制, 《[沈阳晚报：时光网被关闭的背后](https://web.archive.org/web/20101209081246/http://www.govecn.org/2010/11/blog-post_9305.html)》, 政府丑闻, 2010-11-01. (参照 2024-07-18).

## 慧聪网

慧聪网是 B2B 店商平台网站，曾经与阿里巴巴互相竞争，但在 2022 年关闭。

2011年4月21日，阿里巴巴旗下的域名注册服务商「万网」，也是当时的慧聪网域名的「域名注册商」。
因为接到美国科勒公司提供的侵权投诉，而直接将慧聪网域名设置为了 `clientHold`，导致网站下线一段时间。[^78122][^2649]

[^78122]: 孟先亮, 《[慧聪网称域名遭万网封停4小时 疑为阿里巴巴有关](https://web.archive.org/web/20110427072106/http://business.sohu.com/20110422/n280378122.shtml)》, 搜狐网, 2011-04-22. (参照 2024-07-17).

[^2649]: 月光, 《[从“断网门”看域名管理乱象](https://web.archive.org/web/20231208065411/https://www.williamlong.info/archives/2649.html)》, 月光博客, 2011-05-06. (参照 2024-07-17).

由于慧聪网与阿里巴巴是竞争关系，所以慧聪网认为阿里巴巴旗下的万网，触及行业和道德底线，涉嫌恶意竞争。[^78122]

## .cn 域名开放个人注册

2012年5月29日，CNNIC 运营的 .cn 域名开始开放个人注册资格，每个域名只需要 10 元／年。关于开放个人注册的原因，
博主付小贝认为有三种可能，分别是顺应民意、赚钱与方便管辖域名，而前面两种可能性太低。[^15139]

[^15139]: 付小贝, 《[别闹了，.cn域名](https://web.archive.org/web/20170926215139/http://www.diannao.it/keep-silent-cn-domains/)》, 互联网战, 2017-09-26. (参照 2025-05-17).

## 面包多

面包多是一个数字内容平台，创作者可以在上面托管自己的商品，而访客可以在这里众多的内容中寻找感兴趣的内容。
（类似于 Patreon，是供内容创作者进行群众募资的平台。）

2022年10月22日，面包多的域名大面积无法访问，原因是 DNS 被暂停解析了。
随后网站拥有者接到了 [有关部门](/censorship/有关部门.md) 的电话，被告知上面存在一个有害内容，需要删除，
但处理了之后依然没有解封，所以面包多将使用新的域名 `mbd.pub`，而旧域名 `mianbaoduo.com` 彻底失效了。[^SuMUA]

[^SuMUA]: DK本人, 《[关于最近情况的说明](https://web.archive.org/web/20221027145736/https://mp.weixin.qq.com/s/CZt2-UYSQ18NYPy5zSuMUA)》, 微信公众号/ 面包多, 2022-10-27. (参照 2022-10-28).

此外为了防止类似的情况发生，面包多决定极大的限制甚至在某些时候关闭新创作者的注册，并进行更严格的审查，
所有内容都遵循先审后发的规则。

## Linux 中国

2024年2月1日，「Linux 中国」的微信公众号发文宣布，从即日起该社区包括主站 `linux.cn`、公众号、视频号，
以及下属的《硬核观察》栏目，将无限期停止更新和运营。不过内容不会清空，依然供读者浏览。[^77277]

[^77277]: News Bot, 《[“Linux 中国” 开源社区宣布停止运营](https://www.oschina.net/news/277277)》, OSCHINA - 中文开源技术交流社区, 2024-02-01. ([Internet Archive](https://web.archive.org/web/20240301143840/https://www.oschina.net/news/277277), 参照 2025-04-14).

然而在 2025年3月20日，Linux 中国的域名 `Linux.cn` 因不可抗力，而被域名注册商永久冻结（clientHold）。[^dLIKg]

[^dLIKg]: Linux开源社区, 《[Linux中国开源社区官网正式宣布关闭](https://mp.weixin.qq.com/s/vQwAA2cY7MjQ4qw-WdLIKg)》, 微信公众号, 2025-04-14. ([Internet Archive](https://web.archive.org/web/20250414095027/https://mp.weixin.qq.com/s/vQwAA2cY7MjQ4qw-WdLIKg), 参照 2025-04-14).

> [!quote]+ Linux中国开源社区官网正式宣布关闭[^dLIKg]
>
> 由于来自我所能想象的最高层面的不可抗力，2025年3月20日，Linux中国开源社区的官网“`Linux.cn`”被永久冻结（clienthold）。
>
> 这距离我们宣布停运后也不过刚刚过去一年，我不禁有些喟叹，看来想留下最后一个纪念和存留的地方也终不可得。
>
> 我们尝试解封的过程我也不想说了，其实到现在，我们甚至连具体的原因也不知道。
>
> 目前，我们提供了备份域名 <https://Linux.net.cn> 以供访问，但是不知道将来会不会因为同样的某种原因而被冻结。
>
> 此外，大家还是可以访问我们的镜像站，以及公众号“Linux开源社区”来访问那些文章。
>
> 再见，该落幕的就落幕吧。

> [!quote]+ 「Linux开源社区」在关闭公告里的评论
>
> 嗯，还是说明白一些，省的大家瞎猜：域名是被域名注册商冻结的，他们是接受福建通管局指令进行，
> 而通管局是接到中央网信办指令的。但是没有任何申诉和改正的渠道，努力联系上一位领导同志，但是他也不知道具体是那里管辖的。

## 爱发电

2024年7月15日，爱发电域名 `afdian.net` 大范围无法访问，备案号在次日发现消失（琼 ICP 备18001024 号-1）。
域名的 whois 信息，也被发现处于 clientHold 状态。（该状态在 16 日凌晨被短暂解除）[^04953][^93766]

[^04953]: 山外的鸭子哥, 《[[更新] 创作者与粉丝订阅互动平台爱发电无法打开 备案被注销及域名被冻结](https://www.landiannews.com/archives/104953.html)》, 蓝点网, 2024-07-16. ([Internet Archive](https://web.archive.org/web/20241202085052/https://www.landiannews.com/archives/104953.html), 参照 2025-05-25).

[^93766]: 飞小RAN, 《[7·15爱发电afdian.net被锁事件](https://www.bilibili.com/opus/954474769819893766)》, 哔哩哔哩, 2024-08-14. ([Internet Archive](https://web.archive.org/web/20250327135610/https://www.bilibili.com/opus/954474769819893766), 参照 2025-05-25).

2024年7月16日，爱发电发布了公告，表示网站无法连接，是因为备案被注销了，正在准备预案。

> [!quote]+ 【爱发电公告】[^25109]
>
> 说明一下目前的情况，周一早上，我们发现有少部分用户主域名无法打开，核实发现原因是域名备案被注销了
> （国内不允许没有域名备案的网站运营）。此时大部分用户能够继续使用，我们也立刻开始准备预案，包括重新申请备案，
> 准备临时站点等等。
>
> 大家最关心的问题：
>
> 能否继续使用：预案，无论是重新申请备案还是临时站点，都在紧急准备中，很快会有通知，请不能使用的用户稍微等待一下；
>
> 提现方面：没有任何问题，现在的域名在正常提现中。之后的方案，也都能让大家正常提现，请不用担心；
>
> 域名备案注销的具体原因确实不明，没有事先的通知或公示，注销后也没有任何人联系过我们。（网上有一些推测、截图，
> 还请大家不信谣不传谣）
>
> 影响了大家的访问确实非常非常抱歉。我们先集中精力解决当前的问题，尽快恢复服务，感谢大家的支持和理解了！

[^25109]: 爱发电, 《[【爱发电公告】](https://weibo.com/6512497131/5056757671925109)》, 新浪微博, 2024-07-16. (参照 2025-05-25).

2024年7月18日，爱发电宣布更换为 `afdian.com` 域名，但并未给出更多细节解释。

> [!quote]+ 【爱发电公告 —— 临时域名】[^24343]
>
> 【爱发电公告 —— 临时域名】<br>
> [网页链接](https://afdian.com)<br>
> 欢迎使用！
>
> 【App】
> 安卓请更新 App 后使用，应用商店更新或 [网页链接](https://afdian.com/app) 这里直接更新！<br>
> IOS 手机请打开 Safari 浏览器，访问爱发电官网 [网页链接](https://afdian.com)<br>
> 点击底部中间的按钮，再点击 [添加到屏幕]
>
> 一些FAQ：
>
> 1.  是否是长期域名？
>     这是临时域名，可能后续还会提供正式域名，未来临时域名也能用
> 2.  我的账号是否和原来一样？
>     所有东西都一样
> 3.  原来的域名还能用吗？
>     暂时只有少部分用户可以使用
>
> 感谢大家这两天的耐心等待，临时域名还是会有一些小问题，如果遇到了，欢迎站内反馈给我们，再次感谢以及抱歉。

[^24343]: 爱发电, 《[【爱发电公告 —— 临时域名】](https://m.weibo.cn/status/5057558634824343)》, 新浪微博, 2024-07-18. ([Internet Archive](https://web.archive.org/web/20250217133723/https://m.weibo.cn/status/5057558634824343), 参照 2025-05-25).
