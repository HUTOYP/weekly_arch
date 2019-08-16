**架构原理**      
1、[分布式事务处理方式总结](https://mp.weixin.qq.com/s/tQ1nXjrPgHmXOUzfA2rGAg)  
前两周都分享了分布式事务原理和技术，解决分布式事务最优的策略就是避免分布式事务的发生。除此之外，灵活使用事务补偿、异步消息通知和改进的两阶段提交可以应对大部分场景。  
2、[Kafka史上最详细原理总结](https://mp.weixin.qq.com/s/decNVmiGH5BbNGl0wHwEMA)  
文章很全面的总结了Kafka的架构原理，文字较多，需要花些时间阅读。  

**架构设计**   
1、[我使用了6年的分布式锁](https://mp.weixin.qq.com/s/vAk-W8kbC4zUhe1ELs5npA)  
之前分享过使用Redis和zookeeper实现分布式锁的原理和基本实现，本文作者分享了基于Redis实现分布式锁的实践和对存在问题的思考。  
2、[爬虫平台的架构实现和框架的选型](https://mp.weixin.qq.com/s/hRKHpZFZWwPW8bN5VMWGkw)  
本文介绍爬虫平台的架构设计和选型。  

**架构实践**    
1、[京东电商推荐系统实践](https://mp.weixin.qq.com/s/vpANPrl86Ou2fBVHgLXtBQ)  
文章分享京东电商推荐系统实践方面的经验，包括召回、预估和rank工作。  
2、[贝壳：流式数据的平台化实践与挑战](https://mp.weixin.qq.com/s/yuAdxM3hpgd4STOm9dtcQA)  
文章分享贝壳找房流式数据的平台化实践与挑战，具体介绍如何建设流式数据平台来满足业务方的需求。  
3、[微博广告Hubble系统：秒级大规模分布式智能监控平台架构实践](https://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=2653548805&idx=1&sn=6a5f3c6d82e4c074e37def632816a4b5&chksm=813a609db64de98b7c54c666efe5202c62d5bc3a286408acc36963a9b281dc2a8f41fd203b74&scene=0&key=50814c5812fb30a20a0488411eda6eb950afa6a43c3b37c508cfa03330aa218ab91b69cfd10e7c347e7461750c501325676cf8cc6a35d62e1e514ffedf8464f790b7e9816827f274dc754a53a7b9da77&ascene=0&uin=Mjk1ODMyNTYyMg%3D%3D&devicetype=iMac+MacBookPro11%2C4+OSX+OSX+10.12.5+build(16F73)&version=12020810&nettype=WIFI&fontScale=100&pass_ticket=uEdvR1r78ft%2FMFzhT6k8FRq5%2BlrGHWy%2BikGY5oJfoYtwYeil4sWX5RBnZfiv2Q%2F%2B)  
广告pv常常比核心业务pv还要高，比如搜索广告对比搜索，微博广告对比微博，文章介绍了微博商业广告 Hubble 系统的设计原理及在智能全景监控实践中的一些思考。  

**技术管理**  
1、[在阿里做了五年技术主管，我有话想说](https://mp.weixin.qq.com/s?__biz=MzIxMzEzMjM5NQ==&mid=2651032703&idx=1&sn=8eb391e81d24a718d94edfa53002a5f5&chksm=8c4c597bbb3bd06dbbb50e88bb9ea5c67a393fd6018b90e005e7a6c448bfbcfda412cc2a45a6&scene=21#wechat_redirect)  
从管理的角度分享技术TL的核心职责，主要包括团队建设、团队管理、团队文化、沟通与辅导、招聘与解雇等。
