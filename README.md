# 🚖TAXI-SERVICE🚖
## 📚 Project description:
This app is simple visualisation of Taxi Service.

## 📋 Project structure
***The project has an 3-Tier Architecture:***
- DAO - This level of architecture is responsible for communicating with the database.
- Controller - This level allows the user to work with this application.
- Service - all business logic is built on this level

## 💡 Features
- registration a new driver
- log in / log out
- create, update and remove all models
- display list of all manufacturers, cars, drivers, cars of current driver

## ⚙ Technologies
- Java 11
- Git
- Maven
- JDBC
- Javax Servlet
- JSTL
- MySQL
- Tomcat
- JSP

### 👀 INSTRUCTIONS FOR LAUNCHING THE PROJECT:
1. Fork this repository
2. Create new project from Version Control
3. Edit ConnectionUtil.class - set the necessary parameters
``` java
    private static final String URL = "URL";
    private static final String USERNAME = "USERNAME"; 
    private static final String PASSWORD = "PASSWORD";
    private static final String JDBC_DRIVER = "JDBC_DRIVER";
```
4. Create the necessary tables in your database using the file "init_db.sql"
5. Install this [Tomcat](https://tomcat.apache.org/download-90.cgi) version
6. Add Tomcat server to configuration
7. Run project
