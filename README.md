# TODO Application

## Introduction
In this article, we’ll go through the creation of a basic TODO application using Spring Boot and MySQL, covering essential CRUD operations. With tools like JPA for database interaction, this project will enhance your skills in developing RESTful applications that perform efficiently. By the end, you’ll have a fully functional backend API for a TODO application.

## Technologies and Tools
- Java
- Spring Boot
- MySQL
- JPA
- IntelliJ IDEA
- Postman

## API Overview
Our TODO application will use a RESTful API for CRUD operations:

- **GET** — `/todos` — Retrieve all the Todos — **200 OK**
- **POST** — `/todos` — Creates a new Todo — **201 CREATED**
- **PUT** — `/todos/{id}/update` — Update the existing Todo — **200 OK**
- **DELETE** — `/todos/{id}` — Delete Todo By Id — **200 OK**
- **PUT** — `/todos/{id}/isCompleted` — Update the Completed State to True — **200 OK**

## Glossary
- **API** — Application Programming Interface
- **CRUD** — Create, Read, Update, and Delete
- **REST API** — Representational State Transfer
