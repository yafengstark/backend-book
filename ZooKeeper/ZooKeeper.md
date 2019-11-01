①Zookeeper 可以被用作注册中心。 ②Zookeeper 是 Hadoop 生态系统的一员；③构建 Zookeeper 集群的时候，使用的服务器最好是奇数台。

虎的开发人员就试图开发一个通用的无单点问题的分布式协调框架，以便让开发人员将精力集中在处理业务逻辑上


Apache ZooKeeper成为Hadoop，HBase和其他分布式框架使用的有组织服务的标准。 例如，Apache HBase使用ZooKeeper跟踪分布式数据的状态。ZooKeeper 的设计目标是将那些复杂且容易出错的分布式一致性服务封装起来，构成一个高效可靠的原语集，并以一系列简单易用的接口提供给用户使用。

Zookeeper 一个最常用的使用场景就是用于担任服务生产者和服务消费者的注册中心(提供发布订阅服务)。


ZooKeeper 作为 Dubbo 的注册中心(Dubbo 官方推荐使用 ZooKeeper注册中心)
