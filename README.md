# Web Services with Spring Boot, JPA and Hibernate

In this project, I developed a complete REST API using Spring Boot, JPA and Hibernate, applying concepts commonly used in real-world backend applications.

The goal was to build a layered application capable of exposing REST endpoints, persisting data into relational databases and implementing CRUD operations following good software architecture practices.

## Topics Covered

* Spring Boot
* Maven
* REST API
* Spring Web
* JPA
* Hibernate
* H2 Database
* PostgreSQL
* Domain Modeling
* Layered Architecture
* Dependency Injection
* Spring Data JPA
* Repository Pattern
* CRUD Operations
* Entity Relationships
* Exception Handling
* HTTP Status Codes
* REST Controllers
* Application Profiles
* Database Seeding

## Key Concepts

* Spring Boot simplifies the development of Java web applications.
* REST controllers expose application resources through HTTP endpoints.
* JPA and Hibernate provide object-relational mapping (ORM).
* Spring Data JPA reduces boilerplate code by providing repository implementations.
* Dependency Injection allows loose coupling between application layers.
* Layered architecture separates responsibilities into Resource, Service and Repository layers.
* Application profiles make it possible to switch between different environments.
* Exception handlers provide standardized API error responses.

## Project Structure

The application was organized using a layered architecture:

* **Resource Layer** — REST Controllers responsible for handling HTTP requests.
* **Service Layer** — Business logic implementation.
* **Repository Layer** — Data access using Spring Data JPA.
* **Entities** — Domain model mapped to the database.

This organization makes the application easier to maintain, test and extend.

## Domain Model

The API models a simple e-commerce system composed of:

* Users
* Orders
* Products
* Categories
* Payments
* Order Items
* Order Status

Different types of entity relationships were implemented, including:

* One-to-Many
* Many-to-One
* Many-to-Many
* One-to-One

## Implemented Features

* Spring Boot project setup
* REST API creation
* Entity mapping with JPA annotations
* CRUD operations
* Database seeding
* H2 in-memory database configuration
* PostgreSQL configuration
* Dependency Injection
* Repository implementation using Spring Data JPA
* Service layer implementation
* REST Controllers
* Entity relationships
* Custom exception handling
* Standardized API error responses
* Environment configuration using application profiles

## Exercises

The project focused on building a complete backend application from scratch.

Some practical implementations included:

* Creating the entire domain model
* Mapping entity relationships
* Creating REST endpoints
* Implementing CRUD operations
* Persisting data using JPA/Hibernate
* Configuring H2 for testing
* Configuring PostgreSQL for development
* Creating custom exception classes
* Handling database integrity exceptions
* Organizing the application following a layered architecture

The original course also included deployment using Heroku.

Since Heroku no longer offers the same free hosting plan available when the course was recorded, this deployment step was not performed. All other stages of the project were fully implemented.

## What I Learned

This project marked my first complete backend application using Spring Boot.

It helped me understand how modern Java applications are structured, how REST APIs communicate with clients and how data persistence works through JPA and Hibernate.

I also gained practical experience with dependency injection, entity relationships, layered architecture and standardized exception handling.

More than learning individual technologies, this project helped connect several concepts into a single real-world application, making it one of the most important projects I've developed during the course.

---

## 📌 Resumo (Português)

Neste projeto desenvolvi uma API REST completa utilizando Spring Boot, JPA e Hibernate, aplicando conceitos muito utilizados no desenvolvimento backend com Java.

Implementei uma arquitetura em camadas (Resource, Service e Repository), modelagem de domínio, mapeamento de entidades com JPA, relacionamentos entre tabelas, operações CRUD, injeção de dependência e tratamento padronizado de exceções.

Também configurei diferentes ambientes utilizando H2 para testes e PostgreSQL para desenvolvimento, além de utilizar o Spring Data JPA para simplificar o acesso aos dados.

O curso também apresentava uma etapa de deploy utilizando Heroku. Essa parte não foi realizada porque a plataforma deixou de oferecer a mesma disponibilidade gratuita existente na época em que as aulas foram gravadas. Todas as demais etapas do projeto foram implementadas normalmente.

Esse foi um dos projetos mais importantes do curso até aqui, pois reuniu diversas tecnologias do ecossistema Spring em uma aplicação completa, aproximando bastante do desenvolvimento utilizado no mercado.
