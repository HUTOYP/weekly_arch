**架构原理**      
1、[一文读懂高性能网络编程中的I/O模型](https://mp.weixin.qq.com/s?__biz=MzAxNzU3NjcxOA==&mid=2650718514&idx=1&sn=ea23aa6828cef53d231fbcca415d7eb7&chksm=83e90753b49e8e45cc74f68bc90f1521a03de46a99ac6be3967b20135ddb599b39e1576265aa&scene=21#wechat_redirect)  
Linux系统中五种IO模型的实现机制和对比，可以期待一下更加完善的AIO的实践应用。  
2、[分布式事务解决方案汇总：2PC、消息中间件、TCC、状态机+重试+幂等](https://mp.weixin.qq.com/s?__biz=MzIyNjE4NjI2Nw==&mid=2652561205&idx=1&sn=e7318dc36e8a6bf0201b02ceaf56104c)  
本文从实践角度总结了解决分布式事务问题，比较可靠的七种方法：两种最终一致性的方案，两种妥协办法，两种基于状态 + 重试 + 幂等的方法（TCC，状态机+重试+幂等），还有一种对账方法。  

**架构设计**   
1、[数据库软件架构，到底要设计些什么](https://mp.weixin.qq.com/s/yyh013dDNfaiT0wtBihCLQ)  
文章简单的讨论了在高可用数据库架构设计时的要点问题，比如可靠用（主从/双主）、一致性、读写扩展、与缓存的作用关系等。
2、[千万级并发！如何设计一个多级缓存系统？](https://mp.weixin.qq.com/s/h1GzL_-CiQBRC4qHetbRRg)  
在业务架构中应用多级缓存机制，实现系统对高并发场景的良好支持，文章对多级缓存存在的热点、一致性和更新问题进行了探讨。  
3、[海量结构化数据存储技术揭秘：Tablestore存储和索引引擎详解](https://mp.weixin.qq.com/s/Ef-JRY_Vmo7olWP-NXL1uw)  
之前分享“现代IM系统中的消息系统架构”系列文章中就是基于阿里Tablestore构建构建的，本文更加系统的说明了Tablestore引擎原理和架构，对比HBase通过二级索引和多元索引引擎加速数据查找。  

**架构实践**    
1、[蚂蚁金服 Service Mesh 落地实践与挑战](https://mp.weixin.qq.com/s/9ldxEr7LjO0TCjzXqeWr3w)  
蚂蚁金服在实施 Service Mesh 时的业务背景和挑战，方案设计和架构落地时的思考，可以借鉴其中Sidecar平滑升级和性能优化方面的经验。  
2、[Medium的微服务架构最佳实践](https://mp.weixin.qq.com/s/T3b_UKgjcXD4UfEhzcdQWw)  
Medium在实践微服务架构时避免“微服务综合症”的经验分享。  

**技术管理**  
1、[一文了解微服务的流程和组织](https://mp.weixin.qq.com/s/ymgkJfCVtIii_cXybNdG7w)
做微服务
