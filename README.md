# admin-server-microservice

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/0a54f6fbba8d48e187545332986accf7)](https://www.codacy.com/app/mahanhz/admin-server-microservice?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=mahanhz/admin-server-microservice&amp;utm_campaign=Badge_Grade)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/mahanhz/admin-server-microservice.svg)](http://isitmaintained.com/project/mahanhz/admin-server-microservice "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/mahanhz/admin-server-microservice.svg)](http://isitmaintained.com/project/mahanhz/admin-server-microservice "Percentage of issues still open")

This uses [spring-boot-admin](https://github.com/codecentric/spring-boot-admin) to monitor Spring Boot applications.

It is an opt in approach so any Spring Boot app that wants to be monitored must do the following:

* Add the spring-boot-admin-starter-client dependency
* Add the following properties (e.g. to your bootstrap.yml file):
 * spring.boot.admin.url 
 * spring.boot.admin.client.management-url
 * spring.boot.admin.client.health-url
 * spring.boot.admin.client.service-url
