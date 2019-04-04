**架构原理**    
1、概述搜索引擎架构原理基础知识，可以作为概览简单了解  
[深入浅出搜索架构引擎、方案与细节（上）—— 搜索引擎基础](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651959895&idx=1&sn=de25ce2544c088ff9be0b93fd3ea4d15&chksm=bd2d078b8a5a8e9d5ae4339a683d3f980ff2994f3c10c4081c7bab7f0d77f37521de95e974bf&mpshare=1&scene=1&srcid=0404qI5fj0PsiAAYsU9lMQzr&key=0373dd6dcb08f5af2b9755ab1e407a68267af5d6078907612ec67940da15b5d096659a6800dc071288e94de981a119a5b68f27ba253bea6c6c3648b858349161a271a8716421206379e657b24ad29988&ascene=1&uin=MzQ3NDgzMDc1&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=WX%2FjvKfwZFrho%2FCcN6UUWZv2PXSVEif00Tv07da7kKid%2FDONfyV%2FctgZslTYn9eS)  
[深入浅出搜索架构引擎、方案与细节（中）—— 就是这么迅猛的实现搜索需求](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651959917&idx=1&sn=8faeae7419a756b0c355af2b30c255df&chksm=bd2d07b18a5a8ea75f16f7e98ea897c7e7f47a0441c64bdaef8445a2100e0bdd2a7de99786c0&mpshare=1&scene=1&srcid=0404UjhPBPmWHuyphaMCSh7w&key=e0570729d1f68810da4432ebca6c3b4342462a2ab247aad4fbd599e9c15ebc5b2096acd778d447dda648381249e334aeb513f4797593ccbe5173cdab48b4d1723dc3688fde9dcdf0de07f0a7c7eecac2&ascene=1&uin=MzQ3NDgzMDc1&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=WX%2FjvKfwZFrho%2FCcN6UUWZv2PXSVEif00Tv07da7kKid%2FDONfyV%2FctgZslTYn9eS)   
[深入浅出搜索架构引擎、方案与细节（中）—— 百度如何能实时检索到15分钟前新生成的网页？](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651959949&idx=1&sn=83f78cf6293714bd1fd97a11ff7c2c35&chksm=bd2d07518a5a8e47e6fce9fc03cddec1d8a43f2b4ac67cfbbf73a55143593da8a132da7a0815&mpshare=1&scene=1&srcid=0404QRrq72PUHXwVTB8R7HoD&key=f860b9b8147abbb927909382612ad95ce146ef683a17c4d862d4ce00063292dd2ac5f307fd80d01cfe1b105fc136d04450e560af634f67591a647baaa29a72e3f4c37f8971e1672c075970f16c803ced&ascene=1&uin=MzQ3NDgzMDc1&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=WX%2FjvKfwZFrho%2FCcN6UUWZv2PXSVEif00Tv07da7kKid%2FDONfyV%2FctgZslTYn9eS)  
[百度咋做长文本去重](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=403419223&idx=1&sn=7f45d6bf8af2e2e87349570ab93af441&mpshare=1&scene=1&srcid=04049Azep686vjJqimDuC1jF&key=480a3550c10d3149be69cd8268620ee197a3f4f4e9f99897e76744876f767e5aa13d6ece926b181fbdb2c4f3f045e4f43fcf1735feba643b7d9e2b6842532b431480ef2ab458e9a9f89a66248a552db1&ascene=1&uin=MzQ3NDgzMDc1&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=WX%2FjvKfwZFrho%2FCcN6UUWZv2PXSVEif00Tv07da7kKid%2FDONfyV%2FctgZslTYn9eS)
[如何快速实现高并发短文检索](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651959451&idx=1&sn=991d9c3737d7db50a8351d50cdf6419d&mpshare=1&scene=1&srcid=0404hhiJ2952d5A4LegfMfNK&key=0373dd6dcb08f5aff48bf98a5539e25e53f1ed0f55d0b0260e21f5840df93e902d5bef52846129ab7938ec7d3d3fe587e2b08b3df81bc2b051423af44a9fa32ef9c7b47b65516f38220427f1133d0f2e&ascene=1&uin=MzQ3NDgzMDc1&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=WX%2FjvKfwZFrho%2FCcN6UUWZv2PXSVEif00Tv07da7kKid%2FDONfyV%2FctgZslTYn9eS)  
2、[分布式事务](https://mp.weixin.qq.com/s/ahGUAyynbPyid6HYFn6M-g)  
简单介绍保证分布式系统事务处理的主流实现方式  

**架构设计 - 区块链**   
1、[区块链技术架构分析（数据层）](https://mp.weixin.qq.com/s?__biz=MzA5NDAxNzIzNg==&mid=2450006039&idx=1&sn=b76fa4e2a7ed42c05cf62a2ed0da2ccb&scene=21#wechat_redirect)    
介绍区块链内部数据结构。  
2、[区块链技术指南之分布式系统核心问题](https://mp.weixin.qq.com/s/gQxc-eetS2-P9M1BNjvi6Q)  
从区块链的设计上来看分布式系统一致性问题的解决方案。  
3、[Redis架构之防雪崩设计：网站不宕机背后的兵法](https://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=2653548432&idx=1&sn=ac120e1ffca7c2007c0bc5df51e03d7b&chksm=813a7e08b64df71ec7b8b6afc2a36a8ff1d780db54a395b58a9f18f084080c09de514e999834&scene=21#wechat_redirect)  
互联网系统中不可避免要大量用到缓存，在缓存的使用过程中的核心问题：穿透、雪崩、热点。  
4、[Codis作者黄东旭细说分布式Redis架构设计和踩过的那些坑们](https://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=208733458&idx=1&sn=691bfde670fb2dd649685723f7358fea&scene=21#wechat_redirect)  
Redis集群的主流组件Codis、RedisCluster的选型，以及对一致性和分布式系统的讨论。    

**架构实践**  
1、[阿里巴巴的全链路压测](https://mp.weixin.qq.com/s?__biz=MzIyNjE4NjI2Nw==&mid=2652561115&idx=1&sn=ba9b1b1dfa738a455c3640f79c16b8e0&scene=21&ascene=0&devicetype=android-28&version=2700033c&nettype=WIFI&abtest_cookie=BQABAAgACgALABIAEwAGAJ6GHgAjlx4AVpkeAMaZHgDZmR4A3JkeAAAA&lang=zh_CN&pass_ticket=vYsQrWZQaJpy946fySNtJgFXN1CO6F3GMPUzI7mo41Ni7G%2FVgx972i0W19meLCnD&wx_header=1)  
开发运维一家亲 (类比文体不分家、文体两开花~)。  
2、[知乎基于Kubernetes的kafka平台的设计和实现](https://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=2653550746&idx=1&sn=41871413a14082b5940d072efa64c482&chksm=813a6902b64de0148414b05de2904a4195ae24bb8f2322fc7d6f76afd2391a086039bb33c681&mpshare=1&scene=1&srcid=&from=singlemessage&ascene=1&devicetype=android-28&version=2700033a&nettype=WIFI&abtest_cookie=BAABAAgACgALABMABACehh4AI5ceAFaZHgDGmR4AAAA%3D&lang=zh_CN&pass_ticket=9jTQre38gjyldjwfX5lguohZV13GA6uLwTHEOAJIlac%2FnQdlB3iD4yEVxsQi9%2BJE&wx_header=1)  
Kafka 和 k8s 在知乎的应用，最近会发个副刊专门分享几篇流式计算架构文章。
