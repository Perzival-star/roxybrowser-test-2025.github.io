# 名词解释
## User Agent
用户代理（user agent）在计算机科学中指的是代表用户行为的程序（软件代理程序）。例如，网页浏览器就是一个“帮助用户获取、渲染网页内容并与之交互”的用户代理；电子邮件阅读器也可以称作邮件代理。而在会话发起协议（SIP）中，用户代理指代的是一个通信会话的所有两个终端。 

在很多场合，用户代理作为一个主从式架构的分布式计算系统中的通信所用网络传输协议的客户端而行为。特别是在超文本传输协议中指定要求发起请求的客户端软件要使用一个“User-Agent”请求表头，即使在客户端不由用户操纵的时候。SIP协议（基于HTTP）沿用了这一用法。  

与许多其它HTTP请求标头一样，在User-Agent字符串内的信息构成了客户端发送给服务器的信息的一部分，由于该字符串可以因用户不同而有很大程度的差异。  

例如，Windows电脑上，Chrome浏览器的User Agent：  
* Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.7039.0 Safari/537.36  

字符串|说明
-|-
Mozilla/5.0|Mozilla/5.0 是一个通用标记符号，用来表示与 Mozilla 兼容，这几乎是现代网页浏览器的标配。
(Windows NT 10.0)|Windows NT是Windows的核心技术名称，10.0是Windows 10的内部版本号，Windows 10 和 11 共享相同的主要内核版本号（NT 10.0）
AppleWebKit/537.36|浏览器所使用的平台（平台为Webkit浏览器引擎），AppleWebKit是开源的网页渲染引擎，537.36是WebKit的版本号
(KHTML, like Gecko)|浏览器平台的细节（使用 KHTML渲染引擎，一种类似Gecko的渲染引擎）这部分主要是为了网站兼容性而存在
Chrome/135.0.7039.0|这部分代表用户使用Chrome浏览器及其版本号135.0.7039.0
Safari/537.36|表示与Safari浏览器兼容
Mobile(如果存在)|表示用户正在使用移动设备
## Cookies  
HTTP cookie，简称cookie，又称数码存根，是浏览网站时由网络服务器创建并由网页浏览器存放在用户计算机或其他设备的小文本文件。Cookie使Web服务器能在用户的设备存储状态信息（如添加到在线商店购物车中的商品）或跟踪用户的浏览活动（如点击特定按钮、登录或记录历史）。  
虽然最初引入cookie是为了让用户在浏览网站时记录要购买的物品。但现在用户购物车的内容通常存储在服务器的数据库中，而不再是客户端的cookie中。
当前会话cookie的常见用途是登录。当用户访问网站的登录页面时，Web服务器通常会向客户端发送一个包含唯一会话标识符的cookie。当用户成功登录时，服务器会记住该特定会话标识符已经过身份验证，并授予用户访问其服务的权限。  

<font color=gray>资料来源：维基百科</font>  
