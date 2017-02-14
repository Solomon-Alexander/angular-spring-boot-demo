# angular-spring-boot-demo

Build and run the application

Prerequisites:

1. Install JDK 8.
2. Install Maven 3.3.9.


The angular-spring-boot-demo project can be build and run with the below steps:

1. Go to Project directory.
2. Run mvn clean install.
3. Run mvn spring-boot:run to run the Spring boot angular app demo using the Spring Boot Embedded Tomcat Container.
4. Application will be running and tested using http://localhost:8081/index.html#/

Note: Currently the tomcat will be running in port 8081, if there are conflicting ports, then
change the property "server.port" from the application.properties located in src/main/resources.

