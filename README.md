# admin-server-microservice

This uses [spring-boot-admin](https://github.com/codecentric/spring-boot-admin) to monitor Spring Boot applications.
It is an opt in approach so any Spring Boot app that wants to be monitored must do the following:

* Add the spring-boot-admin-starter-client dependency
* Add the following properties (e.g. to your bootstrap.yml file):
 * spring.boot.admin.url 
 * spring.boot.admin.client.management-url
 * spring.boot.admin.client.health-url
 * spring.boot.admin.client.service-url
