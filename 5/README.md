**架构原理**    
1、[大数据凉了？No，流式计算浪潮才刚刚开始！](https://mp.weixin.qq.com/s?__biz=MzU1NDA4NjU2MA==&mid=2247493243&idx=1&sn=db32057f4b6450a66844ca4e3aaa46da&scene=21)  
文章梳理了当前大数据技术中使用的主流框架、核心组件的来世今生。  
2、[后端缓存的23个关键关注点](https://mp.weixin.qq.com/s?__biz=MzIxMzEzMjM5NQ==&mid=2651030776&idx=1&sn=87e55b76d625a0e52b4d9f327fedbaf1&scene=21&ascene=7&devicetype=android-28&version=260703f2&nettype=WIFI&abtest_cookie=BQABAAgACgALABMAFAAFAJ6GHgAmlx4AV5keAJuZHgCcmR4AAAA%3D&lang=zh_CN&pass_ticket=RxN%2BPFQtZe0J1FSI1ViPH8jXfi4HEniKKorZWPjKOmwoG3swNzDdgm5eNP4PsNzh&wx_header=1)  
后端缓存的设计与使用常常伴随着很多的坑，文章总结使用经验总结了一系列关键关注点值得我们参考。  
3、[一文读懂熔断器和重试机制](https://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=2653550148&idx=1&sn=d5ee9ea75e86782d1acc9cb5c62f163e&chksm=813a67dcb64deeca29363a66b0b00be10117476c7e25f9f840f15591b4704252740d9fa09c9b&scene=0#rd)  
在高可用系统中的两个核心概念就是降级和重试机制，降级和熔断又密不可分，文章介绍了熔断器的设计思路和重试机制。  
  
**架构设计**   
1、[一文打尽分布式系统的数据分片难题](https://mp.weixin.qq.com/s?__biz=MzI4NTA1MDEwNg==&mid=2650770727&idx=1&sn=3240671a9c11b6b0cd70537ab098bb06&scene=21#wechat_redirect)  
从分布式系统数据分片方式、特征值选取和元数据管理等方面解释了分布式系统数据分片设计的核心。  
2、[万亿级数据洪峰下的分布式消息引擎](https://mp.weixin.qq.com/s?__biz=MzIxMzEzMjM5NQ==&mid=2651030885&idx=1&sn=028f6d5f496f312d8088fc7e26230332&scene=21&ascene=7&devicetype=android-28&version=260703f2&nettype=WIFI&abtest_cookie=BgABAAgACgALABIAEwAUAAYAnoYeACaXHgBXmR4Am5keAJyZHgCmmR4AAAA%3D&lang=zh_CN&pass_ticket=7ISPDY0sPLJ6HStx4%2FpzYC4I0s%2F98Ueh7SyNqwfmyY50QEOE66ErZr%2BCLWn8Ehcf&wx_header=1)   
阿里团队总结经典应用场景中说面临的问题 - 响应慢，雪崩，用户体验差，继而交易下跌，从而推出的一种低延迟高可用分布式消息引擎解决方案。    

**架构实践**  
1、[秒杀系统架构分析与实战](https://www.jianshu.com/p/df4fbecb1a4b)  
比较全面的介绍了秒杀系统架构的业务特点和架构设计思路。    
2、[用最少的机器支撑万亿级访问，微博6年Redis优化历程](https://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=2653547263&idx=1&sn=fe484b24660b7e1dc4beabca71fe1cb1&scene=21#wechat_redirect)  
[Redis实战：如何构建类微博的亿级社交平台](https://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=2653547053&idx=1&sn=833fddbc83379d9cac8d7f757343412e&scene=21#wechat_redirect)  
两篇有关Redis在新浪微博中的应用，阐述了微博对Redis架构优化历程和架构设计思路。  
