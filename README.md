# spring-boot-test-mockbean-aop 

The project demonstrates the compatibility issue between **spring-aop** and **spring-boot-test** in Spring Boot 1.4.1.RELEASE
The bean annotated with `@MockBeam` annotation stops been extended and monitored by AOP context initialization routines. 

# How to build

`$mvn clean install`
