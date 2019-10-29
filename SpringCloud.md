# eureka
注册不成功，项目自动停止
---
报错信息：
```txt
INFO 17548 --- [      Thread-23] com.netflix.discovery.DiscoveryClient    : Shutting down DiscoveryClient ...
INFO 17548 --- [nfoReplicator-0] com.netflix.discovery.DiscoveryClient    : DiscoveryClient_EUREKA-CLIENT-DEMO/localhost:eureka-client-demo:8091 - registration status: 204
INFO 17548 --- [nfoReplicator-0] com.netflix.discovery.DiscoveryClient    : DiscoveryClient_EUREKA-CLIENT-DEMO/localhost:eureka-client-demo:8091: registering service...
INFO 17548 --- [nfoReplicator-0] com.netflix.discovery.DiscoveryClient    : DiscoveryClient_EUREKA-CLIENT-DEMO/localhost:eureka-client-demo:8091 - registration status: 204
```
可能原因：
```text
没有添加web启动依赖
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
</dependency>
```