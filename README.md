# Cinema shop 🎫

**Project description:**

A simple application that supports authentication, registration and other CRUD operations.

**Features:**

- registration as a user/admin;
- authentication as a user/admin;
- add cinema halls, movie sessions as an admin;
- create/get a cinema hall;
- create/get a movie;
- create/get an available movie session;
- create order and get history of user's orders;
- create/update user's shopping cart;

**Description:**

This project represents N-tier architecture model:

- The service layer. This layer contains all business logic;
- The DAO layer. Data access objects layer uses Hibernate to make CRUD operations with DB.
- The layer of controllers, which receive requests, call service methods and send responses.

This application based on Spring and Hibernate frameworks.
Hibernate is used for CRUD operations with DB in DAO layer. 
Spring annotations mark Dao, Service and Controller classes to create Spring Beans 
for realizing Inversion of Control principle. Spring Security part hashes passwords with BCrypt.
Also, project has Dto models for responses.

**Data Base structure of the project:**

![pic](cinema_shop_structure.png)

**Technologies used in project:**

- Java 11
- Maven
- Hibernate, version: 5.4.27.Final
- Spring: Spring Core, Spring MVC and Spring Security
- HQL
- JDBC
- MySQL
- Apache TomCat

**How to run the project:**

1. Clone this project.
2. Install MySQL and create a schema.
3. Set up your url, driver, username and password data to db.properties file.
4. Set up Apache TomCat Local Service configuration and run application.
5. Enjoy 👍
