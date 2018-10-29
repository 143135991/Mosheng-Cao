#Native App、Web App与Hybrid App简介#
><font color=green size=3>手机，是现代人日常生活中不可或缺的。在手机与生活的联系愈发密切的今天，手机本身已经不仅仅是生活的一种工具，而已经逐渐成为人们生活的一部分。人与手机最重要的交互途径便是应用，简称app。App是手机这种微端的灵魂，也是其最为精彩与缤纷的部分。

<img src="G:\GitHub\pics\apps.jpg" width = 40% height = 40% div align=center />

><font color=brown size=3>当前手机上常见的app从载体的层面上大致可以分为三类：native app(原生app)、web app(网络app)和hybrid app(混合app)。顾名思义，native app的载体是本地操作系统。而web app的载体则以网络为基础。而hybrid app则是前两种app的混合，同时使用两者的载体。


><font color=black size=2>接下来将分别对三种app进行简要的介绍与对比。

###Native App###
######Native app是基于智能手机本地操作系统如iOS、Android、WP并使用原生程式编写运行的第三方应用程序，一般开发的语言为Java、C++等。手机上下载后在桌面出现图标，点击可以打开的大多便是native app。Native app并非不能连接网络，但它并非存在于网络之上，而是存储在本地机中。######
><font color=blue size=3>Native app的优点
>><font color=grey size=2>*可以调用移动硬件设备，比如摄像头、麦克风等

>><font color=grey size=2>*可以访问本地资源

>><font color=grey size=2>*提供最佳用户体验，最优质的用户界面，流畅的交互

>><font color=grey size=2>*能够为不同的平台提供不同的功能

>><font color=grey size=2>*能够有效提升营销的效果与效率

><font color=blue size=3>Native app的缺点
>><font color=grey size=2>*每种移动操作系统都需要独立的开发项目，开发成本高

>><font color=grey size=2>*发布新版本慢

>><font color=grey size=2>*应用商店发布审核周期长(安卓平台要约1~3天，而iOS平台需要的时间更长)

>><font color=grey size=2>*是否下载更新由用户决定，因此需要维护之前的多个版本

>><font color=grey size=2>*盈利需要与第三方分成，盈利空间小

###<font color=black>Web App###
######Web app是基于web的系统和应用，运行于网络和浏览器之上的应用程序，目前多采用h5标准开发。进入手机浏览器后，会有一些应用的图标。点击这些图标，浏览器会打开一款应用程序。这样的应用程序便是web app。
><font color=blue size=3>Web app的优点
>><font color=grey size=2>*不需要安装包，节约手机空间

>><font color=grey size=2>*整体量级轻，开发成本低

>><font color=grey size=2>*不需要用户进行手动更新，由应用开发者直接在后台更新，推送到用户面前的都是全新版本，更便于业务的开展

>><font color=grey size=2>*基于浏览器，可以跨平台使用

>><font color=grey size=2>*可以与其他网站互连，可以被搜索引擎检索

><font color=blue size=3>Web app的缺点
>><font color=grey size=2>*操作流畅性远差于native app

>><font color=grey size=2>*业界公司的移动端开发重点，几乎都是native app，对于web app的支持较少

>><font color=grey size=2>*页面跳转费力，不稳定感更强

>><font color=grey size=2>*在网速受到限制时，很多时候出现卡顿或者卡死现象，交互效果受到限制

>><font color=grey size=2>*安全性相对较低，数据容易泄露或者被劫持

>><font color=grey size=2>*大多数用户都更倾向于native app而不是web app

###<font color=black>Hybrid App###
######Hybrid app是Native app与Web app的混合体。一般通过原生app打开程序主要部分，在native app里内置浏览器，合适的功能页面采用网页的形式呈现
><font color=blue size=3>Web app的优点集合了上面两种app各自的优势
>><font color=grey size=2>*在实现更多功能的前提下，使得app安装包不至于过大

>><font color=grey size=2>*在应用内部打开web网页，省去了跳转浏览器的不便

>><font color=grey size=2>*主要功能区相对稳定下，增加的功能区采用web 形式，使得迭代更加方便

>><font color=grey size=2>*Web页面在用户设置不同的网络制式时会以不同的形式呈现(以微信朋友圈为例，在数据流量下，设置APNS为WAP时，微信订阅号内容将屏蔽图片和视频。这样就能为用户省去一部分流量)

<img src="G:\GitHub\pics\compare.jpg" width = 40% height = 40% div align=center />

----------

####<font color=black>那么我们在具体开发过程中应该如何选择呢？####
>*如果app对有无网络、网络优劣敏感，那么应选择native app。Web app在网络较差时的稳定性不如native app

>*如果app要频繁地调用硬件设备，选择native app较好。由于载体的限制，Web app调用硬件的性能远差于native app

>*如果app反应速度要求较高，则应选择native app。Web app刷新时，基本要加载整个页面，就像一个浏览器打开一个新的网页一样，所需时间较长。而原生系统只需要加载变化的部分

>*如果app中出现了大段文字，并且格式变化比较丰富，那么web app更为合适。Web app对于字符串的处理功能要优于native app

>*如果app的主要部分更新频繁，那么最好选择web app。Web app相较于native app更易于更新与维护，并且不需要维护之前的版本

>*如果app应用于短期活动，可以选择Hybrid app。使用native app制作基本的框架，而内部页面采用web app制作，成本较低，同时便于修改与管理

>*如果app应用于长期运营业务，应选择native app。Native app的用户体验更好，并且更加稳定，也更便于拓展其他功能

-----------

####参考网站####

[https://www.jianshu.com/p/24bf070a4dcb](https://www.jianshu.com/p/24bf070a4dcb)

[https://www.cnblogs.com/wxcbg/p/6405822.html](https://www.cnblogs.com/wxcbg/p/6405822.html)

[http://www.kubikeji.com/gljs/faq/201601204942.html](http://www.kubikeji.com/gljs/faq/201601204942.html)
