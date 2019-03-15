**架构原理**    
1、[InnoDB，5项最佳实践，知其所以然？](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651961428&idx=1&sn=31a9eb967941d888fbd4bb2112e9602b&chksm=bd2d0d888a5a849e7ebaa7756a8bc1b3d4e2f493f3a76383fc80f7e9ce7657e4ed2f6c01777d&scene=0#rd)  
MySQL两个最常用的存储引擎，MyISAM和InnoDB，先了解MyISAM和InnoDB的特点，然后再看InnoDB的实践。  
2、[InnoDB并发如此高，原因竟然在这？](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651961444&idx=1&sn=830a93eb74ca484cbcedb06e485f611e&chksm=bd2d0db88a5a84ae5865cd05f8c7899153d16ec7e7976f06033f4fbfbecc2fdee6e8b89bb17b&scene=0#rd)
表锁和行锁、MVCC、快照读、事务回滚机制。其中，MVCC在分布式一致性中也有应用。
  
**架构设计**   
1、[一文详解：如何设计出高可用的分布式架构？](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655817551&idx=1&sn=0cfae5563d30c9fdc311abec8ea7d73a&chksm=bd74c2988a034b8e3a0061da7b27af4974c85805e3370c4acddf0a3445622f2a0eb43c10eebb&scene=0#rd)  
介绍了SOA、微服务和Service Mesh的演进，以及分布式系统的基本原理和概念，内容较基础。  
2、[权衡取舍：企业落地微服务避坑指南](https://mp.weixin.qq.com/s?__biz=MjM5MDE0Mjc4MA==&mid=2651008743&idx=2&sn=85e41382c56d65169079e45bacef56f8&chksm=bdbed6b48ac95fa2ad63ce8fe3069bee3157f02faaa91776a374f0c04da72ff840a44fb9a381&scene=0#rd)  
什么叫微服务？要不要微服务？怎么做微服务？微服务最难的是落地，最关键的是配套的基础设施支持。  

**架构实践 - 性能优化专题**  
1、[美团外卖系统架构演进与稳定性的探索](https://mp.weixin.qq.com/s?__biz=MzI4OTU3ODk3NQ==&mid=2247485032&idx=1&sn=891af24fc16cd0d43567397d2e3b2a3e&chksm=ec2c4cd8db5bc5ce689e363c2167f9f038a19fab62e6c22d674e949cbe296c2aa3905c98c631&scene=0#rd)  
美团外卖在ArchSummit上做的演讲，介绍了美团外卖的架构演化思路和稳定性实践。  
2、[阿里超大规模秒级监控平台的“打怪升级”之路](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655817983&idx=1&sn=12648ac44e18e52c0a0b955819999bb6&chksm=bd74dd288a03543e24e801d7c5077d87e93fc6e66785321b1e8849f066c17f89bff0b4f12b16&scene=0#rd)  
阿里巴巴的监控平台经历了多次迭代与更替，在曲折发展中慢慢从简单的自动化转换为颇具智能化的系统运维。  
3、[500万日订单下的高可用拼购系统，到底暗藏了什么“独门秘籍”?](https://mp.weixin.qq.com/s?__biz=MjM5ODI5Njc2MA==&mid=2655818275&idx=1&sn=5e22bf8a323e2f6d947a89c4eb247ba0&chksm=bd74dff48a0356e26bad4cabd4f0ac97937997d39fc0f25581a79f169f48f0ec3d1e58d9b222&scene=0#rd)  
零点提交订单峰值破 1 万 TPS，单日总订单量超 500 万，活跃用户数 200 万，苏宁 88 拼购日活动取得了丰硕的成果。  
4、[实战回顾：苏宁金融营销系统的重构之路](https://mp.weixin.qq.com/s?__biz=MzI4MTY5NTk4Ng==&mid=2247488975&amp;idx=1&amp;sn=f0557fd6aa7154f2ce6b28bca4a397a6&source=41#wechat_redirect)  
本文所阐述的是从 2015 年至今，苏宁金融营销系统的发展历程。苏宁金融营销系统不仅支撑了苏宁金融营销业务，也支撑了苏宁易购，苏宁体育，苏宁门店等部分营销业务。  
