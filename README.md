# Sistema Escolar - Cadastro de Alunos

Projeto prático avaliativo da disciplina de **Projeto Web**, desenvolvido com **Spring Boot** para cadastro e listagem de alunos em um sistema escolar.

---

## Tecnologias Utilizadas
Java 17+
Spring Boot 3+
Spring Web
Spring Data JPA
Thymeleaf
MySQL
Maven

---

## Funcionalidades
Cadastro de aluno com os campos:
  - **ID** (gerado automaticamente)
  - **Nome**
  - **Matrícula**
  - **Curso**
  - **Idade**
Listagem de alunos cadastrados na mesma página do formulário
Persistência de dados em banco de dados MySQL

---

## Estrutura do Projeto
psii.senai.appescola
│
├── controller
│ └── AlunoController.java
│
├── model
│ └── Aluno.java
│
├── repository
│ └── AlunoRepository.java
│
└── resources
└── templates
└── alunos.html

## A aplicação estára disponivel no:
http://localhost:8088/alunos
