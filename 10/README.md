**架构原理**    
1、[为什么MySQL数据库要用B+树存储索引](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655823045&idx=1&sn=4b26147c86a456f3dc9e738cad9f5051)  
HashTable、跳表和平衡二叉搜索树（扩展到红黑树、B+树）是实现高效查找的重要方式，本文浅显易懂介绍为什么主流数据库都采用B+树存储索引。  
2、[关于零拷贝](https://mp.weixin.qq.com/s?__biz=MzI4OTU3ODk3NQ==&mid=2247486275&idx=1&sn=06e79f5f5c9a50db580b518607e7b9d6)  
在诸多的开源网络库和分布式消息系统中都能够看到“零拷贝”技术的实践，本文介绍Java实现零拷贝的几种方式。  

**架构设计**   
1、[可能是最易懂的Hbase架构原理解析](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655823985&idx=1&sn=93e3af75a64ced2a997535f9a78e2d74)  
基于BigTable思想实现的HBase是Google的三驾马车之一，也是分布式列存储的经典案例，在OLAP中有着广泛的应用。  
2、[数据库之架构：主备+分库？主从+读写分离？](https://mp.weixin.qq.com/s?__biz=MzIyNjE4NjI2Nw==&mid=2652561421&idx=1&sn=05a793ec6b6123ee418051e22d52b671)  
主备和主从都存在一些附加收益损失，比如可用性和性能问题、一致性问题等，如何结合分库、读写分离和缓存平衡数据读写效率，本文简单做一梳理。  
3、[数据库之分库分表 - 垂直？水平？](https://mp.weixin.qq.com/s?__biz=MzIyNjE4NjI2Nw==&mid=2652561425&idx=1&sn=2202df44937711d4c891719ac92c842d)  
分库分表应该是数据库设计架构领域的必学必会内容，同时，分库分表的核心不是技术实现，而是业务驱动。分表分库引申出“分布式id生成算法SnowFlake”。  

**架构实践**  
1、[Facebook F4架构解读：千亿级图片存储Haystack的演进](https://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=2653550888&idx=1&sn=191d4e67807c39a17b7c5abc4fa028d9)  
Facebook F4 系统用于存储介于冷热数据之间的温数据，目的是降低存储成本，在容忍磁盘，主机，机架等故障的同时，保证一定的可用性。  
2、[从观望到落地：新浪微博Service Mesh自研实践全过程](https://mp.weixin.qq.com/s/jpf4v8Wcytvt2kxTnrUrjg)  
Service Mesh 是一个专用的基础设施层，用于使服务到服务的通信安全、快速和可靠。这几年Service Mesh伴随着微服务的兴起也成为当下最火和面向未来的微服务架构思想。
