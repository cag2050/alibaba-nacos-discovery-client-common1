### Nacos 服务消费者

### 注意：
1.本项目版本：

Spring Cloud Version| Spring Cloud Alibaba Version | Spring Boot Version
--- | --- | ---
Spring Cloud Greenwich | 2.1.1.RELEASE | 2.1.X.RELEASE
2.服务消费者在主类上不用添加注解：@EnableDiscoveryClient，但需要在文件 application.properties 中配置属性：spring.cloud.nacos.discovery.server-addr

### 参考资料

参考资料 | 网址
--- | ---
Spring Cloud Alibaba基础教程：使用Nacos实现服务注册与发现 | http://blog.didispace.com/spring-cloud-alibaba-1/
使用 Nacos 的 Docker 镜像，启动 Nacos 服务 | https://www.cnblogs.com/cag2050/p/11918293.html
组件版本关系 | https://github.com/alibaba/spring-cloud-alibaba/wiki/%E7%89%88%E6%9C%AC%E8%AF%B4%E6%98%8E