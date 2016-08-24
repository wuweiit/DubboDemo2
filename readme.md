### DubboDemo

基于zookeper单机配置2181端口配置中心的dubbo案例。


### zookepper部署

使用默认配置zoo_sample.cfg 复制为zoo.cfg无需任何修改。

bin/zkServer 启动则行



1.启动tomcat运行项目，此时会想zookeper注册一个provider服务提供者IService接口。

2.执行单元测试DubboConsumerTest，会注册一个消费者，并调用sayhello方法，返回数据并打印。
