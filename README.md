# Taxi-service
### List of content
 - [Brief description](#brief-description-)
 - [Features](#features)
 - [Stack of technologies](#stack-of-technologies)
 - [Installing](#installing)
 - [Getting started](#getting-started)
 - [Authors](#authors)

### Brief description 
```
Realization web-application of taxi - service. 
This is simple application that supports authentication, registration and other CRUD operations.
The application focusing on back-end in Java.

Project implements MVC pattern and have 3-tier arhitecture:
- Data tier - MySQL DB and DAO's;
- Application Tier - business logic in Java services;
- Presentation Tier - Servlet Controllers, JSP pages;
```

### Features

 - registration like a driver;
 - authentication like a driver;
 - create/update/remove a manufacturer;
 - create/update/remove a car;
 - create/update/remove a driver;
 - display list of all manufacturers;
 - display list of all drivers
 - display list of all cars;

### Stack of technologies
 - Java 17
 - MySQL 8.0
 - Servlet 4.0.1
 - Maven 4.0
 - Tomcat 9.0.73

### Installing
 1. Download project from this repository and add to IDE as Maven project;
    (copy SSH link and in IDE will create clone : File -> New -> Project from Version Control..., add link to field of URL)
 2. Install and configure Tomcat;
    (Edit configurations -> "+" -> Tomcat server(local) : push on "Fix" button and choose "tax-service war exploded")
  __Pay attention:__ in the "Application context" field have to only "/"
 3. Install and configure MySQL;
 4. Run init_db.sql in database; (use in "resources" folder)
 5. Make sure all dependencies from pom.xml are loaded;

### Getting started
 First of all, you should add your connection parameters in util/ConnectionUtil class. 
 After that you can begin your familiarity with the program.
 
### Authors
[Vitalii Romanyuk](https://github.com/vromanyuk)