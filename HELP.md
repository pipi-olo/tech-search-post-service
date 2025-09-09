# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/3.5.5/gradle-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/3.5.5/gradle-plugin/packaging-oci-image.html)
* [Coroutines section of the Spring Framework Documentation](https://docs.spring.io/spring-framework/reference/6.2.10/languages/kotlin/coroutines.html)
* [Spring Boot Testcontainers support](https://docs.spring.io/spring-boot/3.5.5/reference/testing/testcontainers.html#testing.testcontainers)
* [Testcontainers R2DBC support Reference Guide](https://java.testcontainers.org/modules/databases/r2dbc/)
* [Testcontainers Chroma Module Reference Guide](https://java.testcontainers.org/modules/testcontainers/)
* [Spring Reactive Web](https://docs.spring.io/spring-boot/3.5.5/reference/web/reactive.html)
* [Spring Data R2DBC](https://docs.spring.io/spring-boot/3.5.5/reference/data/sql.html#data.sql.r2dbc)
* [Chroma Vector Database](https://docs.spring.io/spring-ai/reference/api/vectordbs/chroma.html)
* [Testcontainers](https://java.testcontainers.org/)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/3.5.5/reference/using/devtools.html)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a Reactive RESTful Web Service](https://spring.io/guides/gs/reactive-rest-service/)
* [Accessing data with R2DBC](https://spring.io/guides/gs/accessing-data-r2dbc/)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)
* [R2DBC Homepage](https://r2dbc.io)

### Testcontainers support

This project uses [Testcontainers at development time](https://docs.spring.io/spring-boot/3.5.5/reference/features/dev-services.html#features.dev-services.testcontainers).

Testcontainers has been configured to use the following Docker images:

* [`chromadb/chroma:latest`](https://hub.docker.com/r/chromadb/chroma)

Please review the tags of the used images and set them to the same as you're running in production.

