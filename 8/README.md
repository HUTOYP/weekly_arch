**分布式实时计算系统专题**  
**介绍** 
我们为算法团队建设了一套分布式实时计算系统，用于在线机器学习的应用。  
我们完全采用高可用分布式开源组件搭建分布式实时计算系统，其中：  
1、ZooKeeper 集群用于配置管理和服务协调；  
2、Flume 用于线上服务日志收集；  
3、Kafka 提供分布式日志/消息队列服务；  
4、Storm 用于实时数据计算服务；  
5、TensorFlow + TensorFlow-Serving 用于模型计算并提供线上服务功能。  

本周将这些常用的高可用分布式开源组件的文摘分享给大家。  
**ZooKeeper**  
[这可能是把ZooKeeper概念讲的最清楚的一篇文章](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655818907&idx=1&sn=990fb18f67f57672d5a5824455bc677b&chksm=bd74d94c8a03505af967fb8b2d59de9055b7b86ec7f5f114d2333f24a2642c014d0e4830cf43&scene=0#rd)  
**Flume**  
[Flume详解](https://mp.weixin.qq.com/s?__biz=MzU3MzYxNzIxOA==&mid=2247484119&idx=1&sn=6a828a63cb54a67203219796e8c8ba6c&chksm=fd3fa7faca482eec9ad78fa3fda4f74b29d5aad0c84a24d950cdde33f6fbcd8c0d1b42ce7490&mpshare=1&scene=1&srcid=0412ONpY8ZVXAigVqlPdDl3R&key=43dd34a134a69c19e40e9338fcf009e3dbea819e9ed695305b847675eb2e1ce23476c28a50135aa5471a829ee0bdd79f22f2b11d54b8bd81d8f385c4162357bb1ae47c83b3f1b84eee486539f2fe8726&ascene=1&uin=MzQ3NDgzMDc1&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=Uoa4uj4%2FUhFJg7fCld7dfnx8Cj2uoK3uCgHIvOoCS4K0pCptsq%2BywABB%2B6CQpJRa)  
**Kafka**  
[Kafka原理与技术](https://mp.weixin.qq.com/s?__biz=MzA5MTc0NTMwNQ==&mid=2650714484&idx=1&sn=3e0917f0b4b940868bed73208b6d8d3a&chksm=887dac02bf0a25147b0d865b49871835eca75cd586f2301fad5973e25cebb834462847339118&mpshare=1&scene=1&srcid=04121i1N0nHEeIar8ty2OrNj&key=797661f48a795748a9c29ab8e0bdb64978a345595f7bf7bcd2744e9218b2ff3d273208a085d4cf9d705fe764501ad1ffb902f3153c8a396aa79fd6b277ac23a543751a3590eb91f4867e933dff1417a1&ascene=1&uin=MzQ3NDgzMDc1&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=Uoa4uj4%2FUhFJg7fCld7dfnx8Cj2uoK3uCgHIvOoCS4K0pCptsq%2BywABB%2B6CQpJRa)  
[震惊了！原来这才是 Kafka！](https://mp.weixin.qq.com/s?__biz=MzUzMTA2NTU2Ng==&mid=2247486503&idx=1&sn=0064e987f8ee3fa76c7dca292c2271d1&chksm=fa497396cd3efa8046b1d3b639c09325fdfba39873b4431e7ad0af04db695d3e3b2140bd0548&mpshare=1&scene=1&srcid=04123j4P7IoxbqSVURqgHsxo&key=43dd34a134a69c19e6bbbc3ab4e5b3dc28ea555877e42bf7bb39f62961b5a044580a4654b0cc80ced598432bf34efdaca92e8675539958af8fc4793ea9e917d7ea0eddeb98d2978f08ae56897c1d6742&ascene=1&uin=MzQ3NDgzMDc1&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=Uoa4uj4%2FUhFJg7fCld7dfnx8Cj2uoK3uCgHIvOoCS4K0pCptsq%2BywABB%2B6CQpJRa)  
[Apache Kafka：优化部署的 10 种最佳实践](https://mp.weixin.qq.com/s?__biz=MzA5MTc0NTMwNQ==&mid=2650716178&idx=1&sn=9f537e9ee81a30e08c70a0314cd60e80&chksm=887da564bf0a2c721d240859a3cf7705bdaaf387d600c9e041f758f57d9da9c1a1f923360dab&mpshare=1&scene=1&srcid=0412QAVfmCmyG5R7yKCripq6&key=43dd34a134a69c19f7180705facb4af1e89ee59d6624a0de1072994c6356d6c5c47018517772f993d43ac160f973686e1cc2c866c19fb05683bff69abb519d1492a1cc1fd0d466574ecb158a1f487328&ascene=1&uin=MzQ3NDgzMDc1&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=Uoa4uj4%2FUhFJg7fCld7dfnx8Cj2uoK3uCgHIvOoCS4K0pCptsq%2BywABB%2B6CQpJRa)  
[为什么Kafka那么快](https://mp.weixin.qq.com/s?__biz=MzIxMjAzMDA1MQ==&mid=2648945468&idx=1&sn=b622788361b384e152080b60e5ea69a7&mpshare=1&scene=1&srcid=0412WdfuchhNPLHNFJy3DGjN&key=480a3550c10d3149eff9cb4222ab7d8e7080ae89dc20a6b6682fcd161142c142a7b1d382632683306647a7e98083723f626335118886f9e3b746a1b10fc13656a81701a0c6418c57da912d082ef81e31&ascene=1&uin=MzQ3NDgzMDc1&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=Uoa4uj4%2FUhFJg7fCld7dfnx8Cj2uoK3uCgHIvOoCS4K0pCptsq%2BywABB%2B6CQpJRa)  
**Storm**  
[Storm入门中文版](http://ifeve.com/getting-started-with-stom-index/)  
[Storm介绍(一)](https://www.cnblogs.com/Jack47/p/storm_intro-1.html)  
[Storm介绍(二)](https://www.cnblogs.com/Jack47/p/storm_intro-2.html)  
[Storm内部的消息传递机制](https://www.cnblogs.com/Jack47/p/understanding-storm-internal-message-passing.html)  
[Storm如何保证可靠的消息处理](https://www.cnblogs.com/Jack47/p/guaranteeing-message-processing-in-storm.html)  
[理解Storm并发](http://www.cnblogs.com/Jack47/p/understanding_the_parallelism_of_a_storm_topology.html)  
**TF-Serving**  
[基于TensorFlow Serving的深度学习在线预估](https://mp.weixin.qq.com/s?__biz=MjM5NjQ5MTI5OA==&mid=2651748960&idx=2&sn=4c637290b0bd35dc5b541d01d76ce574&chksm=bd12a32d8a652a3b24e159f352c835fd7ff4eedead31dd5b0d0ae2c21da4a0fc587f69a99aef&mpshare=1&scene=1&srcid=04123V12RIOKG61chhoxb3Oe&key=0373dd6dcb08f5af9bf2d7b387632f8a3da00f0e561fec6c69bd13870d39116933b1d1e01a65a7d1219953dc3b7d1839082284ad06793d63c7d21c983df0069dff76b4b7173fef7206b3cd0b041f7af0&ascene=1&uin=MzQ3NDgzMDc1&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=Uoa4uj4%2FUhFJg7fCld7dfnx8Cj2uoK3uCgHIvOoCS4K0pCptsq%2BywABB%2B6CQpJRa)  
[How we improved Tensorflow Serving performance by over 70%](https://mux.com/blog/tuning-performance-of-tensorflow-serving-pipeline/)  
