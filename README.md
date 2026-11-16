# Spring-Boot-Thymeleaf-Form

Dynamic web forms built with Spring Boot and Thymeleaf. This project was developed as part of my internship at NIC Shillong, focusing on building server-rendered forms with Spring MVC and Thymeleaf templates.

## Tech stack

- Java 23
- Spring Boot 3.4.1 (spring-boot-starter-web, spring-boot-starter-thymeleaf)
- Thymeleaf
- Maven (wrapper included)

## Project layout

The Maven project lives in the `springboot-thymeleaf-form/` directory:

```text
springboot-thymeleaf-form/
  pom.xml
  mvnw
  src/main/java/net/NIC/springboot_thymeleaf_form/
  src/main/resources/application.properties
  src/test/java/...
```

## Getting started

```bash
cd springboot-thymeleaf-form
./mvnw spring-boot:run
```

The app serves on http://localhost:8080 by default. Java 23 is required; the Maven wrapper downloads the right Maven version for you, so no local Maven install is needed.

## Tests

```bash
cd springboot-thymeleaf-form
./mvnw test
```
