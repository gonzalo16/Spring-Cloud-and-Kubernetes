# Spring-Cloud-and-Kubernetes
Un proyecto creado a partir de un curso de Kubernetes y Spring Cloud.
Es un proyecto que implementa una arquitectura de microservicios con Spring Boot 3 y maneja la comunicación de los mismo mediante Kubernetes utilizando AWS para el registro y
escalamiento dinámico. Los microservicios utilizan bases de datos diferentes una MySQL8 y el otro Postgres. Todavía no está implementado pero se añadirá en un futuro seguridad a los 
endpoints con Spring Security OAuth2.

# Descripción de los microservicios
### Microservicio Usario.
En un microservice en el que podemos realizar operaciones CRUD mediante API Rest conectado a una base de datos MySQL8

**HTTP Request
GET ae65e0d59d4be4011b542247e7b2483a-364527965.eu-north-1.elb.amazonaws.com:8001**

| Parameter | Type | Description
| --- | --- | --- |
| None | None | Lista todos los usuarios

**HTTP Request
GET ae65e0d59d4be4011b542247e7b2483a-364527965.eu-north-1.elb.amazonaws.com:8001**

| Parameter | Type | Description
| --- | --- | --- |
| id | Long | Muestra el detalle de un usuario por id

**HTTP Request
POST ae65e0d59d4be4011b542247e7b2483a-364527965.eu-north-1.elb.amazonaws.com:8001**

| Parameter | Type | Description
| --- | --- | --- |
| None | None | Crea un usuario pasando el objeto en el request

**HTTP Request
PUT ae65e0d59d4be4011b542247e7b2483a-364527965.eu-north-1.elb.amazonaws.com:8001**

| Parameter | Type | Description
| --- | --- | --- |
| id | Long | Actualiza el usuario pasando el objeto en el request y la id como parametro

**HTTP Request
DELETE ae65e0d59d4be4011b542247e7b2483a-364527965.eu-north-1.elb.amazonaws.com:8001**

| Parameter | Type | Description
| --- | --- | --- |
| id | Long | Elimina el usuario

**HTTP Request
GET ae65e0d59d4be4011b542247e7b2483a-364527965.eu-north-1.elb.amazonaws.com:8001**

| Parameter | Type | Description
| --- | --- | --- |
| None | None | Lista los alumnos que pertenecen a un curso


### Microservicio Curso.
En un microservice en el que podemos realizar operaciones CRUD mediante API Rest conectado a una base de datos Postgres

