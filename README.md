# Spring-Cloud-and-Kubernetes
Un proyecto creado a partir de un curso de Kubernetes y Spring Cloud.
Es un proyecto que implementa una arquitectura de microservicios con Spring Boot 3 y maneja la comunicación de los mismo mediante Kubernetes utilizando AWS para el registro y
escalamiento dinámico. Los microservicios utilizan bases de datos diferentes una MySQL8 y el otro Postgres. Todavía no está implementado pero se añadirá en un futuro seguridad a los 
endpoints con Spring Security OAuth2.

# Descripción de los microservicios
Microservicio Usario.
En un microservice en el que podemos realizar operaciones CRUD mediante API Rest conectado a una base de datos MySQL8

**HTTP Request
GET http://localhost.....**

| Parameter | Type | Description
| --- | --- | --- |
| None | None | Lista todos los usuarios

**HTTP Request
GET http://localhost.....**

| Parameter | Type | Description
| --- | --- | --- |
| id | Long | Muestra el detalle de un usuario por id

**HTTP Request
POST http://localhost.....**

| Parameter | Type | Description
| --- | --- | --- |
| None | None | Crea un usuario pasando el objeto en el request

