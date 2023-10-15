# Documentação

## todolist:springboot

Uma simples aplicação utilizando SpringBoot de To do List

### Authorization

- Basic Auth
  - Username: <username>
  - Password: <password>

### POST user

- URL: http://localhost:8080/users/
- Authorization
  - Basic Auth
    - Username: <username>
    - Password: <password>
- Body
  - raw (json)
  - json
    {
      "name": "Name User",
      "username": "user",
      "password": "1234"
    }

### POST task

- URL: http://localhost:8080/tasks/
- Authorization
  - Basic Auth
    - Username: <username>
    - Password: <password>
- Body
  - raw (json)
  - json
    {
      "description": "Descrição",
      "title": "Titulo",
      "priority": "ALTA",
      "startAt": "2023-10-09T12:30:00",
      "endAt":"2023-10-09T15:30:00"
    }

### GET task

- URL: http://localhost:8080/tasks/
- Authorization
  - Basic Auth
    - Username: <username>
    - Password: <password>

### PUT task

- URL: http://localhost:8080/tasks/{id}
- Authorization
  - Basic Auth
    - Username: <username>
    - Password: <password>
- Body
  - raw (json)
  - json
    {
      "title": "Alterei titulo",
      "priority":"BAIXA"
    }

### DELETE task

- URL: http://localhost:8080/tasks/{id}
- Authorization
  - Basic Auth
    - Username: <username>
    - Password: <password>
