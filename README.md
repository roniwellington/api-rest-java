# 📦 API REST Java com Spring Boot

Este projeto foi desenvolvido durante a formação **"Java e Spring Boot"** da Alura. A proposta da aplicação é construir uma API REST completa com boas práticas de desenvolvimento, segurança, documentação, testes e preparada para deploy em produção.

---

## 📚 Conteúdos Abordados

### 🚀 Módulo 1: Desenvolvendo uma API REST com Spring Boot 3
- Criação do projeto com Spring Initializr
- Implementação de CRUD utilizando Spring Data JPA
- Integração com banco de dados MySQL
- Utilização do **Flyway** para versionamento e Migrations
- Validações com **Bean Validation**
- Paginação dos dados da API com Spring

### 🔒 Módulo 2: Aplicando Boas Práticas e Protegendo a API
- Tratamento de erros e padronização de respostas
- Utilização correta dos códigos HTTP
- Implementação de autenticação com **Spring Security**
- Geração e validação de **JSON Web Tokens (JWT)**
- Controle de acesso baseado em perfil de usuário

### 📄 Módulo 3: Documentação, Testes e Deploy
- Aplicação de princípios **SOLID**
- Isolamento de regras de negócio
- Documentação com **OpenAPI/Swagger**
- Escrita de **testes automatizados** (unitários e de integração)
- Preparação do ambiente para **deploy**
- Uso de **variáveis de ambiente** no projeto

---

## 🧰 Tecnologias Utilizadas

- Java 17
- Spring Boot 3
- Spring Security
- Spring Data JPA
- MySQL
- Flyway
- Bean Validation (Hibernate Validator)
- JWT (Json Web Token)
- Swagger / OpenAPI
- Maven
- JUnit
- Docker (para deploy e ambiente)

---

## ⚙️ Como executar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/api-rest-java.git
cd api-rest-java

# Configure as variáveis de ambiente (application.properties ou application.yml)
# Execute a aplicação com Maven
./mvnw spring-boot:run

```
# 📑 Documentação
Acesse a documentação da API gerada com Swagger em:
```
http://localhost:8080/swagger-ui.html

```
# 🧪 Testes
```
./mvnw test

```
