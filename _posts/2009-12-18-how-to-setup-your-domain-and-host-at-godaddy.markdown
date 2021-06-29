---
author: billrain
comments: true
date: 2009-12-18 10:13:22+00:00
layout: post
link: http://www.billrain.com/2009/12/how-to-setup-your-domain-and-host-at-godaddy/
slug: how-to-setup-your-domain-and-host-at-godaddy
title: 如何在Godaddy上管理你的域名和主机？- How to setup your domain and host at Godaddy?
wordpress_id: 1918
categories:
- 信息技术|IT
tags:
- godaddy
- HowTo
- WEB
---

最近关于godaddy的利好消息不断，先是即将支持支付宝交易，然后又推出了1美元的点com域名优惠，其实这么多年来11一直在使用godaddy的服务，虽然登录其设在外国的网站进行设置需要些耐心，但是其配置和使用还是很简单的，关键价格很公道，当然前提是你能看懂英文，下面11就为大家介绍一下如何配置域名和主机之间的关联，至于如何购买这种简单的问题，就不要问我了哈。




1. 首先登录到godaddy的账户内，左边会有下面的导航栏，假设你的域名和主机都是在这买的，那么接下来选Hosting先




[![1](http://www.billrain.com/wp-content/uploads/2009/12/1_thumb.png)](http://www.billrain.com/wp-content/uploads/2009/12/1.png)




<!-- more -->2. 会显示你当前购买的主机类型，点击Manage Account




[![2](http://www.billrain.com/wp-content/uploads/2009/12/2_thumb.png)](http://www.billrain.com/wp-content/uploads/2009/12/2.png)




3. 进入管理页面，打开Settings页面，选Domain Management来添加域名




[![5](http://www.billrain.com/wp-content/uploads/2009/12/5_thumb.png)](http://www.billrain.com/wp-content/uploads/2009/12/5.png)




4. 然后会打开你所有绑定在这个主机上的域名列表，新建的话点击右边的Add Domain按钮




[![10](http://www.billrain.com/wp-content/uploads/2009/12/10_thumb.png)](http://www.billrain.com/wp-content/uploads/2009/12/10.png)




5. 会跳出下面的画面，输入你购买的域名的Domain地址，并指定它在当前主机上分配的目录Folder位置，一般来说一个网站对应一个目录，这个路径在这是可以新建的，当然通过FTP登录也可以新建




[![8](http://www.billrain.com/wp-content/uploads/2009/12/8_thumb.png)](http://www.billrain.com/wp-content/uploads/2009/12/8.png)




6. 返回到3的画面，选Manage FTP Users来添加FTP的用户，点击下面的Add FTP User会出现输入框，我们可以看到一共可以添加50个用户，在User Name下面输入一个用户名，在Password下面设定密码，在Path下面指定这个用户所能访问的路径，如果是/根目录的话，则能访问所有路径，权限最大，填写好后点Save保存。这样你就可以通过FTP客户端软件向你的主机上上传文件了，如果忘记密码的话也是在这里进行修改




[![9](http://www.billrain.com/wp-content/uploads/2009/12/9_thumb.png)](http://www.billrain.com/wp-content/uploads/2009/12/9.png)




7. 现在你的主机方面就配置好了，下面开始域名的绑定工作。返回到1画面，选进Domain Manage进行下画面，会看到你账户内所有的域名信息，选中其中一个[![3](http://www.billrain.com/wp-content/uploads/2009/12/3_thumb.png)](http://www.billrain.com/wp-content/uploads/2009/12/3.png)




8. 选中的这个域名的具体信息就显示出来了，点击最下面的Total DNS Control来把域名指向到你的主机地址上




[![4](http://www.billrain.com/wp-content/uploads/2009/12/4_thumb.png)](http://www.billrain.com/wp-content/uploads/2009/12/4.png)




9. 出现下画面后，点击右边的Add New A Record按钮




[![6](http://www.billrain.com/wp-content/uploads/2009/12/6_thumb.png)](http://www.billrain.com/wp-content/uploads/2009/12/6.png)




10. 在第二行，Points To Ip Address里面填写你的主机的IP地址，在你购买主机的时候就会发给你了，不知道可别问我啊




[![7](http://www.billrain.com/wp-content/uploads/2009/12/7_thumb.png)](http://www.billrain.com/wp-content/uploads/2009/12/7.png)































11. 点击OK，这样就基本配置完成了，由于网络和其他原因，每个页面打开时候都有点延迟，需要耐心等待，另外每次做新的变更后，状态可能显示为Pending，就是处理中的意思，可能不会立刻有实际的反应，一般半个小时你做的改动就会反应到网站上了，也不要着急。关于新建SQL数据库的步骤其实也类似，这里就先不介绍了。
