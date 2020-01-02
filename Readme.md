Credits to @callicoder:

https://github.com/callicoder/spring-boot-actuator-demo

## Steps to Setup


**1. Build and run the app using maven**

```bash
mvn package
java -jar target/actuator-demo-0.0.1-SNAPSHOT.jar
```

Alternatively, you can run the app directly without packaging like this -

```bash
mvn spring-boot:run
```

The app will start running at <http://localhost:1010>

## Prometheus endpoint

All the actuator endpoints will be available at <http://localhost:1010/management/prometheus>
