Spring Cloud Config server and client example.
=

### Launch

1. Start `ConfigServer` application using `mvn spring-boot:run` command
1. Start `ConfigClient` application using `mvn spring-boot:run` command
1. Go to `http://localhost:8080/whoami/{username}` replacing `{username}` placeholder with any string value
1. You will see welcome message with passed `{username}` and user role, loaded right from `ConfigService`

### Tutorials used

* [Using Spring Boot without the parent POM](https://docs.spring.io/spring-boot/docs/current/reference/html/using-boot-build-systems.html#using-boot-maven-without-a-parent)
* [Spring Boot Dependency Management with a Custom Parent](http://www.baeldung.com/spring-boot-dependency-management-custom-parent)
* [Quick Intro to Spring Cloud Configuration](http://www.baeldung.com/spring-cloud-configuration)
* [Spring Cloud - File System Backend](http://projects.spring.io/spring-cloud/spring-cloud.html#_file_system_backend)