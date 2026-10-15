user-service (Spring Boot)

REST API управления пользователями. Spring Boot 3.5, Spring Web, Spring Data JPA, PostgreSQL.

## API

GET  /api/users - список
GET  /api/users/{id} - один
POST  /api/users - создать
PUT  /api/users/{id} - обновить 
DELETE  /api/users/{id} - удалить 

Тело запроса: `{"name":"Alex","email":"alex@mail.ru","age":20}`
