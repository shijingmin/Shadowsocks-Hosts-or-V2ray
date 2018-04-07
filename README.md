# Shadowsocks or Hosts
# ---- 影梭和Hosts的科学上网

## 免责声明

**本项目仅进行技术展示，对所爬到的帐号不负任何责任。**

**本项目仅面向海外华人用户，中华人民共和国境内居民禁止使用，并请立即关闭本网站！**

**本项目所提供的帐号均来自网络，仅供科研、学习之用。**

**请用本项目分享的帐号进行学习、科研，切勿用于其他用途。**

**请于24小时之内删掉与本项目相关的一切内容，否则出现一切问题本站作者概不负责。**

----------
![](https://i.imgur.com/upTVEr3.gif)
----------
## Hosts科学上网（Hosts Science Online）

----------

- ### IPv6
	*1. 如果网络支持IPv6，我们通常使用IPv6访问Google和YouTube。(If the network supports IPv6, we usually use IPv6 for access to Google and YouTube)*

	*2. 如果是Windows系统，可以在C:/windows/system32/drivers/etc修改DNS，并保存信息，之后可以直接地访问Google和YouTube。( If you are an Windows system, you can find host in C:/windows/system32/drivers/etc, modify DNS, and save information after modification, and finally you can directly access the Internet scientifically.)*

	*3. 该开源项目编写了一个hosts更改或恢复的[项目](https://github.com/lovelyyoshino/SS-or-ipv6_host/releases)，相关的代码和exe可以在这个项目中下载。（This developed project set a project to change or restore hosts，and this relevant code and exe can download in this project）*
	
	*4. 如果hosts失效可以将下载文档中的hosts删除并重新添加lennylxx利用Scprits生成的[hosts文件](https://github.com/lennylxx/ipv6-hosts/blob/master/hosts) （If hosts fails, the hosts which is in the download document can be deleted and added to the Scprits which hosts file generated by lennylxx.）*
- ### IPv4
	*1. IPv4和IPv6一样，均可以用该软件一键注册，直接访问 Google和Youtube ，但是普通家庭一般没有IPv6所以建议注册IPv4（IPv4 and IPv6 can use this software to register  and visit Google and Youtube directly, but normal families usually don't have IPv6, so it is recommended to register IPv4.）*

	*2. 如果是学校（教育）网络可以使用IPv6，因为这个更加全面。（If the network is school (education) network can use IPv6, because this is more comprehensive.）*

	*3. 如果hosts失效可以将下载文档中的hosts删除并重新添加googlehosts生成的[hosts文件](https://github.com/googlehosts/hosts/blob/master/hosts-files/hosts)（If hosts fails, the hosts which is in the download document can be deleted and added to the file which hosts file generated by googlehosts.）*

## Shadowsocks科学上网

----------

- ### 科学上网自建教程
	#### 1. 以下为自己搭建SS/SSR或v2ray服务器教程（以下两个Github项目操作均适合新手）：

	##### [自建ss/ssr服务器教程](https://github.com/ShadowsocksR-Live/shadowsocksr-native)

	##### [自建v2ray服务器教程](https://github.com/Alvin9999/new-pac/wiki/%E8%87%AA%E5%BB%BAv2ray%E6%9C%8D%E5%8A%A1%E5%99%A8%E6%95%99%E7%A8%8B) 

	#### 2. VPS推荐：

	##### [Vultr](https://www.vultr.com/) 	
	![](https://i.imgur.com/RLLJ9M0.jpg)
	*知名服务器供应商；全球15个服务器位置可选，KVM框架，最低2.5美元/月。支持支付宝和paypal付款。不怕被封ip，因为vultr是折算成小时计费，且可以随时删除和开通服务器，新服务器就是新的ip。*
	##### [Linode](https://www.linode.com/?r=898beb100d9309609e5ff5a004b3963b23cbaf34)
	![](https://i.imgur.com/srFGvmH.png)
	*inode是一家美国的VPS主机托管商，成立于2003年。最低配的方案为1G内存，20G SSD硬盘，价格为$5/月。实际上，它是按照小时收费的，每小时的价格为$0.075，如果你用满一整个月，那么最多只需要支付$5，但大部分的月份都低于$5。*
	##### [搬瓦工](https://www.thevultr.org/tag/ban_wa_gong/)
	![](https://i.imgur.com/pg6scjn.png)
	*搬瓦工vps（BandwagonHost）这款美国IT7公司旗下的一款便宜年付OVZ架构的VPS主机方案。因其价格便宜、且依托的商家比较靠谱。*
	##### [樱花VPS](https://vps.sakura.ad.jp/)
	![](https://i.imgur.com/fEt0pfL.png)
	*樱花VPS是日本著名的IDC，口碑极好，在日本的排名甚至超过了Linode，樱花家的VPS是KVM架构的，特点是大硬盘、大带宽、无限流量、稳定和低价。在石守、东京、大阪有数据中心*
	#### 3. SSR客户端下载：
	##### 第一次电脑系统使用SSR/SS客户端时，如果提示你需要安装NET Framework 4.0，有的电脑系统可能会自带NET Framework 4.0。如果不存在NET Framework 4.0环境，建议百度安装相关环境，或者通过[3DMGAME](http://dl.3dmgame.com/201211/28051.html)运行库合集安装包进行一键配置环境
	![](https://i.imgur.com/OFdtp1A.png)
	##### Windows SSR客户端 [下载地址](https://github.com/shadowsocksr-backup/shadowsocksr-csharp/releases)
	##### MAC SSR客户端 [下载地址](https://github.com/shadowsocksr-backup/ShadowsocksX-NG/releases)
	##### Linux客户端 [安装配置使用脚本(使用方法见注释)](https://github.com/the0demiurge/CharlesScripts/blob/master/charles/bin/ssr) 或者[图形界面的ssr客户端](https://github.com/erguotou520/electron-ssr/releases)
	##### 安卓SSR客户端 [下载地址](https://github.com/shadowsocksr-backup/shadowsocksr-android/releases/download/3.4.0.8/shadowsocksr-release.apk)
	##### 苹果手机SSR客户端：[Potatso Lite](https://bbs.feng.com/read-htm-tid-11369365.html)、[shadowrocket](https://www.hinwen.com/3662.html)都可以作为SSR客户端

- ### 公开Shadowsocks科学上网账号
	## Tip:
	我不生产 ss(r) 帐号，我只是帐号的搬运工。不保证可用，不保证速度，不保证安全，不保证隐私。再次声明，本项目仅面向海外华人用户，中华人民共和国境内居民禁止使用，并请立即关闭本项目！本项目所提供的帐号均来自网络，仅供科研、学习之用。

	#### 1. Github上面存在的Shadowsocks账号

	###### **[gfw-breaker账户新建的SS/SSR 账号](https://github.com/gfw-breaker/ssr-accounts/blob/master/README.md)，如果SS服务器遭到GFW封锁, 届时将重建服务器并更新账号信息**

	###### **[Alvin9999单个用户速度至140kb/s的影梭账户](https://github.com/Alvin9999/new-pac/wiki/ss%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7)，但禁止使用账号进行BT下载、发送垃圾邮件**

	###### **[BiulinkYoutube 1080p无压力版本](https://github.com/Biulink/ShadowsocksTutorials)，独享一台Shadowsocks服务器，不与其他用户共享资源，但是每日账户流量固定,[biulink](https://pro.biulink.xyz/home/index)注册，可以直接获取一周的免费Shadowsocks账号**

	###### **[VonSdite Bat文件快捷使用](https://github.com/VonSdite/Auto_Shadowsocks)，密码每6小时会更换(0点, 6点, 12点, 18点)并重启服务器,**

	#### 2. 其他网站上面存在的Shadowsocks账号

	###### **[ishadowx](https://get.ishadowx.net/)存活时间很久了，缺点在于时常变动账户密码，速度一般**

	###### **[逗比根据地](https://doub.io/sszhfx/)存活时间x相当长了，缺点在于时常变动账户密码，速度很快**

	###### **[google+：Shadowsocks免费帐号 ](https://plus.google.com/communities/104092405342699579599/stream/8a593591-2091-4096-bb00-7d9c5659db93)长时间有人活跃在当中提供优质的账户**

	###### **[google+：ShadowSocks公益信息交流 ](https://plus.google.com/communities/117702818760720009772/stream/47c69db4-9362-4d91-a017-97f3be948437)长时间有人活跃在当中提供优质的账户**

	###### **[google+：Shadowsocks俱乐部 ](https://plus.google.com/communities/107859708371989171939)长时间有人活跃在当中提供优质的账户**