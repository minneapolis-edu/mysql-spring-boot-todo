# Sample To Do List web application using Spring Boot and H2

Microsoft Azure sample from https://github.com/Azure-Samples/mysql-spring-boot-todo

A simple Todo list application using Spring Boot with the following options:

- Spring JPA and H2 for data persistence
- Thymeleaf template for the rendering.

## Build and run the sample

1. `mvn package`
3. `java -jar target/TodoDemo-0.0.1-SNAPSHOT.jar`
3. Open a web browser to http://localhost:8080

## Java Version

Use Java 8.  

## Things to notice

Tasks are displayed in a form. Notice the hidden inputs that contain data about tasks.
The routes are able to these to figure out what changed, and update the database. 

There's only one page that shows all of the tasks. The routes redirect to this page when they have finished their operation.
