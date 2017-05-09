### 第2课 - SpringCloud 101

#### Eureka-server

Eureka是Netflix OSS的组件之一，提供了服务的注册与发现机制。

执行如下命令启动Eureka的一个实例:

```start.sh``` 

执行如下命令启动Eureka的集群实例:

```start_cluster.sh``` 


#### Event-Service

执行如下命令启动一个EventService实例，并注册到Eureka上

```start.sh``` 

执行如下命令启动多个EventService实例，注册到Eurkea上

```start_cluster.sh``` 



#### 其他

本代码来源于《微服务架构与实践》视频课，更多内容请访问[详情](http://www.stuq.org/course/1149)

* 1.Spring Cloud是什么

	* Spring家族对于分布式开发提供的全家桶
	* 提供了多个支持分布式软件开发的组件
	* 包括Netflix OSS、Message Broker、Security等
	

* 2.Spring Cloud能做什么

	* 集成Netflix OSS的组件(Eureka/Hystrix/Zuul等)，提供微服务系统需要的支撑组件。
	* 提供集中化的服务配置信息，动态更新实例的配置信息。提供服务实例间配置信息的变更。
	* 使用分布式消息机制，提供不同服务实例之间的协作。简化服务间的异步通信机制。
	* 提供服务安全相关的实现机制(OAuth2)。提供服务间授权与认证。

![微服务架构与实践](/images/2nd-introduction.png)
![微服务架构与实践](/images/content.png)
![微服务架构与实践](/images/index.png)
