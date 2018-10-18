Config service: 8088

Discovery Service (Eureka server): 8061

Employee Service: 8090

Organization Service: 8092

Department Service: 8091

Gateway Service: 8060

How to run a second instance of employee service:
mvn spring-boot:run -Dspring-boot.run.profiles=instance2