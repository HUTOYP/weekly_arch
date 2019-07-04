**架构原理**    
1、[系统调优，你所不知道的TIME_WAIT和CLOSE_WAIT](https://mp.weixin.qq.com/s?__biz=MzA3MzYwNjQ3NA==&mid=403319808&idx=1&sn=ddae082f5b844d040b9ab23c9c0eb778&scene=23&srcid=0311hhv2oaIbIdkiBjAsYXML#rd)      
2、[我就是认真，为了一个net.ipv4.tcp_tw_recycle参数](https://mp.weixin.qq.com/s?__biz=MzA3MzYwNjQ3NA==&mid=403232978&idx=1&sn=4ed396ac1999add1c866419bd62b0e75&scene=21#wechat_redirect)  
之前使用libcurl进行短连接 Restful API 调用时，出现系统大量 TIME_WAIT 的问题，以上两篇文章深入分析了 TCP TIME_WAIT 机制和应对方案。  

**架构设计**   
1、[Feed流系统设计-总纲](https://mp.weixin.qq.com/s/ccxM2thPbzg5vDWgGVJ5vQ)  
比较完整的介绍了Feed流系统的特点、应用场景、架构设计和选型。   

**架构实践**    
1、[每秒千万级的实时数据处理是怎么实现的？](https://mp.weixin.qq.com/s/Us3Eg-CbAMPHQXxyqh9rVQ)  
咸鱼（淘宝）在处理大规模流量实时数据处理的解决方案，主要是在开源方案上的定制化，从而优化性能。  


