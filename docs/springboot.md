# Spring Boot

This project uses Spring Boot with Apache Camel.

If you want to learn more about Spring Boot, please visit its website: <https://spring.io/projects/spring-boot>.

## Running the application in dev mode

You can run your application in dev mode using:

```shell script
./mvnw spring-boot:run
```

## Packaging and running the application

The application can be packaged using:

```shell script
./mvnw package
```

It produces the `workshop-springboot-using_camel-1.0.0-SNAPSHOT.jar` file in the `target/` directory.

The application is now runnable using:

```shell script
java -jar target/workshop-springboot-using_camel-1.0.0-SNAPSHOT.jar
```

## Related Guides

- Camel Spring Boot ([guide](https://camel.apache.org/camel-spring-boot/latest/)): Run Camel routes on Spring Boot
- Camel XJ ([guide](https://camel.apache.org/components/latest/xj-component.html)): Transform JSON and XML using XSLT
- Camel Kafka ([guide](https://camel.apache.org/components/latest/kafka-component.html)): Send and receive messages to/from an Apache Kafka broker
- Camel MinIO ([guide](https://camel.apache.org/components/latest/minio-component.html)): Store and retrieve objects from MinIO
- Camel REST DSL ([guide](https://camel.apache.org/manual/rest-dsl.html)): Expose REST services using Camel's REST DSL
