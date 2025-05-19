# 🧾 Projeto - Bradesco Dev Week 2025

Este projeto foi desenvolvido durante a Bradesco Dev Week 2025, seguindo as orientações do instrutor. A aplicação simula funcionalidades de uma conta bancária, como visualização de saldo, limite e dados do usuário.

---

## 🔍 Funcionalidades

Consulta de informações da conta bancária (número, agência, saldo e limite adicional)

Exibição de dados do usuário

Organização em camadas (Controller, Service, Repository, Model)

## 📁 Estrutura do Projeto
```
src/
└── main/
    ├── java/
    │   └── me.dio/
    │       ├── controller/
    │       │   └── UserController.java
    │       ├── domain/
    │       │   ├── model/
    │       │   │   ├── Account.java
    │       │   │   └── BaseItem.java
    │       │   └── repository/
    │       └── service/
    │           ├── impl/
    │           │   └── UserServiceImpl.java
    │           └── UserService.java
    └── resources/
        ├──application-dev.yml
        ├──application-prd-yml
```
## 🚀 Tecnologias
* Java

* Spring Boot

* JPA (Hibernate)

* Gradle

## ▶️ Como executar o projeto

### ✅ Pré-requisitos

- Java 11 ou superior
- Maven ou Gradle instalado
- IDE como IntelliJ, VSCode ou Eclipse (opcional)

1. Clone o repositório
   ```
   git clone https://github.com/seu-usuario/nome-do-repo.git

2. Abra o projeto em sua IDE (como IntelliJ ou VSCode com suporte Java)

3. Execute a aplicação
   
   Rode a classe Main ou Application (caso tenha esse nome) como aplicação Spring Boot.

4. Acesse a API

   Por padrão, a API estará disponível em:
```
 http://localhost:8080
```

## ✍️ Autora
Flaviane de Lima com instrução do instrutor.
