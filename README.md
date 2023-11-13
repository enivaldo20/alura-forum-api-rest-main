# alura-forum-api-rest-main
# Challenge ONE Back End Java + Spring
## Desafio:
- Foi proposto desenvolver uma **API REST** usando o **Spring** para criar um Hotel e reservas de hospedagem.

## Requisitos:
## O foco principal são os tópicos, em que permita os usuários:
- Criar um novo tópico
- Mostrar todos os tópicos criados
- Mostrar um tópico específico
- Atualizar um tópico
- Eliminar um tópico

### Implementação pessoal:

  - [x] Cadastrar novo usuário
  - [x] Senha protegida com BCrypt
  - [ ] hierarquia de usuário
  - [x] Criar uma nova categoria
  - [x] Adicionar um novo curso
  - [x] Adicionar uma resposta no tópico
  - [x] status do tópico
  - [x] Swagger UI

### Tecnologias utilizadas:
- [Eclipse](https://www.eclipse.org/)
- [MySQL](https://www.mysql.com/)
- [Java](https://www.java.com/)
- [Spring Boot 3](https://start.spring.io/)
- [Token JWT](https://jwt.io/)

## Aplicativo:
### Requisitos:
  - MySQL 8
  - Java 17 ou superior

### \>>[DOWNLOAD BETA VERSION](https://github.com/enivaldo20/alura-forum-api-rest/releases)<<

### Configurando o MySQL:
```sql
CREATE DATABASE alurahotel_api;
```
### executando o aplicativo com o CMD[^1]:
[^1]: execute o CMD na pasta onde está o aplicativo
```cmd
java -D"spring.profiles.active=prod" -DJWT_SECRET=12345678 -DDATASOURCE_URL=jdbc:mysql://localhost/aluraforum_api -DDATASOURCE_USERNAME=root -DDATASOURCE_PASSWORD=root -jar alura-forum-api-rest-v0.1.0.jar
```
### Guia completo das funcões da API, quando o aplicativo em execução:
```
http://localhost:8080/swagger-ui/index.html
```

![alura-forum-api](https://github.com/enivaldo20/alura-forum-api-rest/assets)

