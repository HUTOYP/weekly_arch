**架构原理**    
1、[TCP协议疑难杂症全景解析](https://mp.weixin.qq.com/s?__biz=MzI4OTU3ODk3NQ==&mid=2247485188&idx=1&sn=c2e8c0f8ab27c798954d417ca550c449&chksm=ec2c4db4db5bc4a24028715c8bdfe4564cdebca2ea4fa9eaa4b86634073f7f48e274fffd7180&scene=0#rd)  
文章简单介绍了TCP协议的基本原理，提出23个“疑难杂症”并做一一解答，对进一步深入理解TCP协议有些帮助。
1、[如何理解高性能网络模型？这篇文章说透了](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655818750&idx=1&sn=85f61fa4add73eddba9973c85f8be131&chksm=bd74de298a03573f9d42b5e6769e7ad7ed24a1d3204ac7ec188579dbb180b988d3db7b362639&scene=0#rd)  
本文旨在为大家提供有用的概览以及网络服务模型的比较，以揭开设计和实现高性能网络架构的神秘面纱。（核心是IO模型和线程模型（事件分派模型））

**架构设计 - Redis高可用性**   
1、[Redis为什么这么快？一文深入了解Redis内存模型！](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655816024&idx=1&sn=f4ee4afce1055d9f34c61a8a9d95918a&chksm=bd74c48f8a034d99ffb4291e78a6b0c6654a8ab74d83bbf6739bc4ec20ce7ae1165d19e79d44&scene=21#wechat_redirect)  
从内存管理和数据存储结构的角度来阐述Redis高并发能力的实现原理。  
2、[3分钟深入学习Redis的高可用特性“持久化”](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655817009&idx=1&sn=1b28414b42179d506d4216112dfc36c7&chksm=bd74c0e68a0349f0506ea75dccad96e4c302764b45e2b5c6869d5d1e5d1fd3bb5c4931caf2a6&scene=21#wechat_redirect)  
作为缓存使用的Redis一般不需要考虑持久化特性，但是作为存储使用时，持久化是重要的高可用保证方式，在不影响Redis存取性能的同时提供持久化特性是Redis运维的重点。  
3、[深入学习Redis高可用的基石：主从复制](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655817476&idx=1&sn=0a50d49549e3efbeb7a7cf4903e410f3&chksm=bd74c2d38a034bc53b808d9dcba840f958c2c856a256cb21702a2945b7e02f86b9e2702eb671&scene=21#wechat_redirect)  
Redis高可用保证——主从复制。
4、[深入学习Redis高可用架构：哨兵原理及实践](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655818849&idx=1&sn=1e1409612bfcb57bd4ab20a0d7fc43ad&chksm=bd74d9b68a0350a02093cd6b6b2925769ef2f364a411822fc3070ba0ebde6d24377190d5c886&scene=0#rd)
Redis高可用保证——哨兵，对其他高可用系统也有借鉴意义。Redis Sentinel配合Redis集群管理组件（Codis、Cluster等）可以实现对Redis集群的高可用管理。  

**架构实践**  
1、[4000+系统，10w+服务的立体式监控是如何炼成的?](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655818782&idx=1&sn=c9b21cad29923aad15b7a905d3886915&chksm=bd74d9c98a0350dfcac8527ee418186523db9a42bd41d9475840442856b61fa9ae906d062166&scene=0#rd)  
苏宁监控一体化解决方案旨在为用户提供从系统监控、问题定位、实时告警到决策分析、故障自愈的一站式解决方案。
