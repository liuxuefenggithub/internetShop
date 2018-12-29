1.IP代理池设计（redis+多线程）

抓取得网站：http://www.xicidaili.com/nn/1

主要代码以及思路

ThreadJob.java:主要过程

首先使用本机ip抓取第一页

之后使用代理ip抓取后面得页数

用到的知识点

要把数据存放到redis中，必须使java对象序列化(实现了serializable接口)

2.利用IP代理池抓取天猫图片(mysql+多线程)

3.网上商城（ssm）

