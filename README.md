# 🚀 Workshop Spring Boot + JPA

Projeto desenvolvido com o objetivo de praticar a construção de uma API REST utilizando **Java + Spring Boot + Spring Data JPA**, seguindo boas práticas de arquitetura em camadas.

## 📌 Sobre o projeto

Este projeto consiste em uma API RESTful para gerenciamento de entidades, implementando operações básicas de CRUD (Create, Read, Update, Delete).

A aplicação foi estruturada com foco em organização, separação de responsabilidades e entendimento do fluxo completo de uma aplicação backend.

## 🛠️ Tecnologias utilizadas

- Java 21
- Spring Boot
- Spring Web
- Spring Data JPA
- Hibernate
- Banco de dados H2 (em memória)
- Maven

O uso do Spring Data JPA permite reduzir código boilerplate ao fornecer implementações automáticas de repositórios e operações de banco de dados :contentReference[oaicite:0]{index=0}.

## 🧱 Arquitetura

O projeto segue o padrão em camadas:

- **Resource (Controller)** → Responsável pelas requisições HTTP
- **Service** → Regras de negócio
- **Repository** → Acesso ao banco de dados
- **Entities** → Modelos do sistema

Essa separação facilita manutenção, testes e escalabilidade.

## 🔁 Funcionalidades

- ✔️ Cadastro de entidades
- ✔️ Listagem de dados
- ✔️ Busca por ID
- ✔️ Atualização de dados
- ✔️ Remoção de registros
- ✔️ Tratamento básico de exceções
