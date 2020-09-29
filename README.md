# spring-boot-experiment

Run using `./mvnw spring-boot:run`. 

`curl localhost:8080/actuator/health` checkes the health.   

`curl localhost:8080/hello?Jenny` should give you a greeting.   

`curl localhost:8080/` should give you a greeting.   


Download the Spring CLI and then run   
`spring run src/main/groovy/app.groovy  `should run the groovy app and `curl localhost:8080` should give you a greeting.


Build a JAR file using:   
``./mvnw clean package``   

and run it using    
```java -jar target/spring-boot-experiment-0.0.1-SNAPSHOT.jar```   


