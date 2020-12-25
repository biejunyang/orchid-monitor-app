微服务监控应用：
1、service-admin:微服务状态、服务器信息监控
pring Boot Admin 是一个管理和监控你的 Spring Boot 应用程序的应用程序。 这些应用程序通过 Spring Boot Admin Client（通过 HTTP）注册或者使用 Spring Cloud（例如 Eureka）发现。 UI只是 Spring Boot Actuator 端点上的一个 AngularJs 应用程序。 

https://blog.csdn.net/u010739551/article/details/81539370


2、hystrix-dashboard:断路器状态监控、时观察各个服务的运行健康、效率和请求量等服务调用监控
    监控Hystrix的各项指标信息。
    
  
    
   
   

3、链路追踪
https://blog.csdn.net/pengjunlee/article/details/87797969
https://blog.csdn.net/zhangcongyi420/article/details/99698834
https://ld246.com/article/1571898375961

4、Turbine
https://intomylife.blog.csdn.net/article/details/90732956?utm_medium=distribute.pc_relevant.none-task-blog-OPENSEARCH-6.control&depth_1-utm_source=distribute.pc_relevant.none-task-blog-OPENSEARCH-6.control
使用 SpringCloud 的 Hystrix Dashboard 组件可以监控单个应用服务的调用情况，但如果是集群环境，可能就

  不能满足需求了，这时就用到了 SpringCloud 另一个组件：Turbine。

  Turbine 将每个应用服务的调用情况聚合在一起展示出来。

  如果了解过 Hystrix Dashboard，那么可以简单认为 Turbine 就相当于另起了一个工程，把其他工程的监控情况

  全部显示到了 Turbine 工程中。