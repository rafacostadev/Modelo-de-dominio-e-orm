Aulas - Modelo de Domínio e ORM

Esse projeto faz parte do curso de Spring Boot do DevSuperior, no módulo de Modelo de Domínio e ORM.

O objetivo deste repositório é praticar os conceitos de:

  Modelagem de domínio com Java

  Mapeamento objeto-relacional (ORM) usando JPA e Hibernate

  Definição de entidades, atributos e associações

  Persistência de dados em banco de dados relacional

  Uso do Spring Data JPA

Tecnologias Utilizadas:

  Java 21

  Spring Boot
  
  Spring Data JPA
  
  Banco de dados H2
  
  Maven
  
  Eclipse

O projeto consiste na criação de um modelo de domínio representando um determinado cenário de negócio.

Durante o desenvolvimento foram aplicados:

  Criação de entidades JPA
  
  Definição de atributos e tipos
  
  Implementação de relacionamentos como:
  
  Um-para-muitos (@OneToMany)
  
  Muitos-para-um (@ManyToOne)
  
  Muitos-para-muitos (@ManyToMany)
  
  Criação de repositórios com Spring Data JPA
  
  Testes de persistência com banco de dados

Diagrama entidade/relacionamento

![Diagrama-entidade-relacionamento](https://github.com/rafacostadev/Modelo-de-dominio-e-orm/blob/main/MOR.png)

Como Executar o Projeto
  Clone o repositório:
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    
  Abra o projeto na sua IDE

  Execute a classe principal

  Acesse o console do H2:
    http://localhost:8080/h2-console

O que foi aprendido:

  Criação de modelos de domínio usando boas práticas
  
  Mapeamento objeto-relacional (ORM) com JPA
  
  Aplicação de anotações como @Entity, @Id, @GeneratedValue, @ManyToMany...
  
  Persistência de dados utilizando Spring Data JPA
  
  Uso do banco de dados H2 para testes
