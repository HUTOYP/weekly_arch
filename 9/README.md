**架构原理**    
1、[曾奇：谈谈我所认识的分布式锁](https://mp.weixin.qq.com/s/QWFNAWn2Gxn9FgYCowm7dQ)  
分布式环境中，数据一致性是我们一直关注的重点.文章系统介绍了分布式锁的原理概念和主流实现方式。 

**架构设计**   
1、[互联网架构三板斧之并发](https://mp.weixin.qq.com/s/87JWlUoc03UZy2ar3p4NlA)  
以类秒杀系统的业务特点为例，介绍高并发环境下并发设计要点。  
2、[微服务架构下静态数据通用缓存机制](https://mp.weixin.qq.com/s/QVILVNB9l7zKKkhPxo9CyA)  
静态数据是指不经常发生变化或发生变化频率极低的数据，除了在使用多级缓存外，微服务内部使用旁路缓存和消息队列方式实现缓存，使用一致性检查程序实现DB与缓存的一致性保证。  
3、[Kafka如何实现每秒上百万的超高并发写入？](https://mp.weixin.qq.com/s/g1TdX3Cce45MlBK384gAWA)  
Kafka的核心要点主要是高性能和高可用两个方面，本文主要介绍了Kafka高性能的实现方法：页缓存、顺序写、零拷贝。      

**架构实践**  
1、[详细解读 Github 上发布仅一个月就获得4k+ star 的分布式事务解决方案](https://mp.weixin.qq.com/s/6Tg0hUtrZLm3kXKyBsqNkg)  
文章介绍了阿里内部基于XA优化的分布式事务中间件 Fescar 的设计思路和解决方案。   
2、[微博短视频百万级高可用、高并发架构如何设计？](https://mp.weixin.qq.com/s/zQHlWSeMIEZ0-EL355raBw)  
文章介绍微博短视频产品在高并发（推拉模式选择、数据分片、分布式缓存等）和高可用（多机房互备、混合云动态扩容、熔断）方面的设计实践经验。  
3、[智能运维在百度日常业务监控中的探索](https://mp.weixin.qq.com/s/OkJlCr2hxB8ZGRwQOLzv5Q)  
文章介绍了百度大搜在业务监控运维中的探索实践，重点关注监控策略、实现方式和机器学习的应用。
