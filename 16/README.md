**架构原理**    
1、[系统调优，你所不知道的TIME_WAIT和CLOSE_WAIT](https://mp.weixin.qq.com/s?__biz=MzA3MzYwNjQ3NA==&mid=403319808&idx=1&sn=ddae082f5b844d040b9ab23c9c0eb778&scene=23&srcid=0311hhv2oaIbIdkiBjAsYXML#rd)      
2、[我就是认真，为了一个net.ipv4.tcp_tw_recycle参数](https://mp.weixin.qq.com/s?__biz=MzA3MzYwNjQ3NA==&mid=403232978&idx=1&sn=4ed396ac1999add1c866419bd62b0e75&scene=21#wechat_redirect)  
之前使用libcurl进行短连接 Restful API 调用时，出现系统大量 TIME_WAIT 的问题，以上两篇文章深入分析了 TCP TIME_WAIT 机制和应对方案。  

**架构设计**   
1、[谈企业级互联网架构的演进之路](https://mp.weixin.qq.com/s/YIdJVN6zXEtCBSorc2Docw)  
围绕阿里技术架构演进及过程中遇到的问题与企业级信息系统架构的演进展开。    
2、[一份详尽的支付平台高可用架构设计实践](https://mp.weixin.qq.com/s/kuJRRUoiZYfWCT5KqZlrVA)  
应用组件模式、Builder模式、策略模式重构优化支付平台高可用能力。  
3、[亿级流量系统架构之如何支撑百亿级数据的存储与计算](https://mp.weixin.qq.com/s/eqtR9QAMIm3F4QnGut1vrA)
海量数据计算无非就是分离离线和近线，从而满足不同实时性要求的数据计算和分析。离线一般就是基于HDFS的mapreduce和spark，实时则使用Storm或者现在比较火的Flink.分库分表、读写分离则只能是备选方案。

**架构实践**    
1、[Kubernetes监控在小米的落地](https://mp.weixin.qq.com/s/ewwD6A3-ClbotdfFmYY3KA)  
小米在监控系统中引入K8s和Prometheus的应用实践。  
2、[蚂蚁金服轻量级监控分析系统解析](https://mp.weixin.qq.com/s/m4WyeU3KbjyJn6ZFC7go-g)  
蚂蚁金服轻量级监控分析系统 SOFALookout 原理讲解和功能演示，对时序数据库特点进行了简单归纳。

