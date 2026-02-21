# DSCommerce

API REST desenvolvida com Spring Boot durante o curso **Java Spring Professional** da DevSuperior.

O projeto simula um sistema de e-commerce, abordando desde modelagem de domínio e CRUD até autenticação, autorização e controle de acesso com OAuth2 e JWT.

---

## 🛠 Tecnologias utilizadas

- Java 21  
- Spring Boot  
- Spring Security (OAuth2 + JWT)  
- Spring Data JPA / Hibernate  
- Bean Validation  
- Banco de dados H2  
- Maven  

---

## 📌 Funcionalidades principais

- Cadastro e consulta de produtos
- Busca paginada com filtro por nome
- Controle de acesso por perfil (ADMIN / CLIENT)
- Autenticação com OAuth2 e JWT
- Endpoint para obter usuário logado
- Criação e consulta de pedidos
- Controle de acesso programático (self ou admin)
- Validação de dados com mensagens customizadas
- Tratamento global de exceções

---

## ▶️ Executando o projeto

Pré-requisitos:
- Java 21
- Maven

1. Clonar o repositório:
```
git clone https://github.com/thiagosohsa/dscommerce-spring.git
```
2. Entre do diretório:
```bash
cd dscommerce-spring/
```
3. Executar
```
mvn clean spring-boot:run
```
4. Ou execute dessa forma:
```
./mvnw spring-boot:run
```

A aplicação ficará disponível em:
```
http://localhost:8080
```

---
## 👤 Usuários de teste

| Perfil | Email           | Senha |
|------|-----------------|------|
| ADMIN | alex@gmail.com  | 123456 |
| CLIENT | maria@gmail.com | 123456 |


## 🔐Autenticação

- A API utiliza OAuth2 com JWT para autenticação e autorização.
- O fluxo de login pode ser testado via Postman, conforme configuração do Authorization Server presente no projeto.
---