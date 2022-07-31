# Cinema shop 🎫

**Project description:**

A simple application that support authentication, registration and other CRUD operations.

**Features:**

- registration as a user;
- authentication as a user;
- create/get a cinema hall;
- create/get a movie;
- create/get an available movie session;
- create order and get history of user's orders;
- create/update user's shopping cart;

**Description:**

This project represents N-tier architecture model:

- The service layer. This layer contains all business logic;
- The DAO layer. Data access objects layer uses Hibernate to make CRUD operations with DB.

**Data Base structure of the project:**

![pic](cinema_shop_structure.png)

**Technologies used in project:**

- Java 11
- Maven
- Hibernate, version: 5.4.27.Final
- HQL
- JDBC
- MySQL

**How to run the project:**

1. Clone this project.
2. Install MySQL and create a schema.
3. Set up your url, driver, username and password data to hibernate.cfg.xml file.
4. Run application in the main method.
5. Enjoy 👍
