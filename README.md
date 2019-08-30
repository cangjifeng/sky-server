# sky-server

## 服务注册中心
​    sky-server 工程是一个服务注册中心，springBoot web工程，jdk 要求1.8 。

​    采用 eureka 服务发现组件实现，生成者和消费者都需要把各自的服务注册到 eureka 上 。   

​    eureka 服务之间也需要相互注册，搭建集群注册中心。