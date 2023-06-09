# My cinema-app
![img_1.png](img_1.png)
### Description
* This is a simple server-based web-application which has the following capabilities:
* User registration and authentication;
* Possibility to be in the role of admin / user;
* Admin functions :
  * add new cinema halls
  * add new movies
  * create / change / delete / movie sessions
  * find users by-email
* User functions:
  * see list of the cinema halls
  * see list of the movies
  * choose available movie sessions with date
  * bye tickets to the shopping cart
  * see list of the orders

### Project structure
The solution based on 3-tier architecture:
- DAO - Data access layer;
- Service - Business logic layer;
- Controllers - Presentation layer.

### UML diagram of models

![img.png](img.png)


### Technologies
- JDK 17;
- Maven 4.0.0;
- MySQL 8.0.22;
- Tomcat 9.0.50;
- Spring 5.2.2;

### How to use
- Copy one from GitHub;
- Fill you own DB properties in /resources/db.properties file
- Configure Tomcat server (it is recommended to use version 9.0.50)
- User with ADMIN role is created automatically with the following credentials:
email: admin@i.ua
password: admin123
