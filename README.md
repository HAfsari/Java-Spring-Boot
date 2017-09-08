# Java-Spring-Boot

Use JPA + Hibernate + MySQL in Spring Boot
--------------------------------------------

See here for more informations: https://docs.spring.io/spring-data/data-jpa/docs/current/reference/html/#jpa.query-methods.query-creation

Usage
-----

Run the application and go on http://localhost:8080/
Use the following urls to invoke controllers methods and see the interactions with the database:
/create?email=[email]&name=[name]: create a new user with an auto-generated id and email and name as passed values.
/delete?id=[id]: delete the user with the passed id.
/get-by-email?email=[email]: retrieve the id for the user with the passed email address.
Build and run

Configurations
--------------

Open the application.properties file and set your own configurations for the database connection.

Prerequisites
--------------

Java 7
Maven 3
