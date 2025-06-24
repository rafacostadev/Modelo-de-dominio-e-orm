# 📚 Aulas - Modelo de Domínio e ORM

Projeto desenvolvido durante as aulas do curso de **Spring Boot** da DevSuperior no módulo **Modelo de Domínio e ORM**.

## 🎯 Objetivo

Praticar os conceitos de:

- 📦 Modelagem de domínio com Java
- 🔗 Mapeamento objeto-relacional (ORM) usando JPA e Hibernate
- 🧱 Definição de entidades, atributos e associações
- 💾 Persistência de dados em banco de dados relacional
- 🔄 Uso do Spring Data JPA

## 🛠️ Tecnologias Utilizadas

- ☕ Java 21  
- 🌱 Spring Boot  
- 🗃️ Spring Data JPA  
- 🛢️ Banco de dados H2  
- 📦 Maven  
- 💻 Eclipse  

## 🧱 O Projeto

O projeto consiste na criação de um **modelo de domínio** representando um determinado cenário de negócio proposto nas aulas.

Durante o desenvolvimento foram aplicados:

- ✅ Criação de entidades JPA
- ✅ Definição de atributos e tipos
- ✅ Implementação de relacionamentos:

  - 🔁 Um-para-muitos (`@OneToMany`)
  - 🔂 Muitos-para-um (`@ManyToOne`)
  - 🔄 Muitos-para-muitos (`@ManyToMany`)

- ✅ Criação de repositórios com Spring Data JPA
- ✅ Testes de persistência com banco de dados

### 🗂️ Diagrama Entidade/Relacionamento

![Diagrama-entidade-relacionamento](https://github.com/rafacostadev/Modelo-de-dominio-e-orm/blob/main/MOR.png)

## ▶️ Como Executar o Projeto

1. Clone o repositório:
```bash
git clone git@github.com:rafacostadev/Modelo-de-dominio-e-orm.git
```

2.Abra o projeto na sua IDE (Eclipse, IntelliJ, VSCode...)

3. Execute a classe principal do projeto como uma Spring Boot Application

4. Acesse o console do H2:
``` console
http://localhost:8080/h2-console
```

JDBC URL: jdbc:h2:mem:testdb

User: sa

Password: (deixe em branco)


📚 O que foi aprendido
- ✅ Criação de modelos de domínio utilizando boas práticas

- ✅ Mapeamento objeto-relacional (ORM) com JPA

- ✅ Aplicação de anotações como @Entity, @Id, @GeneratedValue, @ManyToMany, entre outras

- ✅ Persistência de dados utilizando Spring Data JPA

- ✅ Uso do banco de dados H2 para testes e validações
