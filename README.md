# Spring Cloud Config Server

- Implementation of Spring Cloud Config Server

# Dependencies

- java: 1.8
- spring-boot: 1.5.2.RELEASE
- spring-boot-actuator
- spring-cloud: Camden.SR5
- spring-cloud-eureka-client

# Default parameters 

- server.port: 8888
- spring.application.name: configserver

# Enviroment parameters

* Eureka config
- eureka.client.serviceUrl.defaultZone: http://localhost:8761/eureka/
- eureka.instance.preferIpAddress: true

* Git config
- spring.cloud.config.server.git.uri: https://github.com/rodrigovelaz/spring-cloud-config.git
- spring.cloud.config.server.git.username: username
- spring.cloud.config.server.git.password: password