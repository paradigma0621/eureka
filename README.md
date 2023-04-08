# Time Flow System 
Backend and Frontend implementation of software to measure time quality in work

## Eureka Server Microservice
This project is designed to run in *Java 17*.

Eureka microservice for Java 17

Access to see the monitor page:
http://localhost:8761/

## Configuration get from Config Microservice
It gets the properties (example: the port to run) from Connfig Server repository.
Port that Eureka runs = 8761

http://localhost:8888/eureka-java17/default      (Point accessed by Config Server Microservice)
(file: https://github.com/mselucas/configRepo/blob/master/eureka-java17.yml )

## TimeFlow Project
### List of microservices correlated for Java 17: 
https://github.com/paradigma0621/timeflowsystem-config-java17 <br>
https://github.com/paradigma0621/timeflowsystem-eureka-java17 <br>
https://github.com/paradigma0621/timeflowsystem-api-java17 <br>
https://github.com/paradigma0621/timeflowsystem-gateway-java17

### List of microservices correlated for Java 8
In https://github.com/paradigma0621 there is also all this microservices in Java 8 version.

