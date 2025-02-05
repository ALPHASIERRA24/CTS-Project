# CTS-Project

The Library Management System is a web-based application built using Spring Boot with Thymeleaf, Spring Security, and Spring Data JPA. It allows users to:

✔️ Login and authenticate using Spring Security.
✔️ View the catalog of books available in the library.
✔️ Borrow books and view their borrow history.
✔️ Admin users can manage books and users.

The system follows a multi-layered architecture:

Frontend (View Layer): Thymeleaf templates (.html files) inside src/main/resources/templates.
Controller Layer: Handles HTTP requests (.java files in controller package).
Service Layer: Business logic (.java files in service package).
Repository Layer: Database operations using Spring Data JPA (.java files in repository package).
Model Layer: Defines the data structure (.java files in model package).

For reference only. Update as per latest update
alphasierra24-lib-mgmt/
│── pom.xml
│── src/
│   ├── main/
│   │   ├── java/com/cts/LibraryManagementSystem/
│   │   │   ├── LibraryManagementApplication.java
│   │   │   ├── config/SecurityConfig.java
│   │   │   ├── controller/
│   │   │   │   ├── AuthController.java
│   │   │   │   ├── CatalogController.java
│   │   │   │   ├── BorrowController.java
│   │   │   │   ├── UsersController.java
│   │   │   ├── model/
│   │   │   │   ├── UsersModel.java
│   │   │   │   ├── BorrowRecordModel.java
│   │   │   │   ├── CatalogModel.java
│   │   │   ├── repository/
│   │   │   │   ├── UsersRepository.java
│   │   │   │   ├── BorrowRecordRepository.java
│   │   │   │   ├── CatalogRepository.java
│   │   │   ├── service/
│   │   │   │   ├── UserDetailsServiceImpl.java
│   │   │   │   ├── BorrowService.java
│   │   │   │   ├── CatalogService.java
│   │   │   │   ├── UsersService.java
│   │   ├── resources/
│   │   │   ├── templates/
│   │   │   │   ├── index.html
│   │   │   │   ├── login.html
│   │   │   │   ├── user-dashboard.html
│   │   │   │   ├── book-list.html
│   │   │   │   ├── borrow-books.html
│   │   │   │   ├── borrow-history.html
│   │   │   ├── static/
│   │   │   │   ├── styles.css
│   │   │   │   ├── borrow.js
│   │   │   │   ├── catalog.js
│   │   │   │   ├── user.js
│   │   │   ├── application.properties
│   │   │   ├── data.sql
│   ├── test/
│   │   ├── java/com/as/LibraryManagementSystem/AppTest.java

alphasierra24-lib-mgmt/
│── pom.xml
│── src/
│   ├── main/
│   │   ├── java/com/cts/LibraryManagementSystem/
│   │   │   ├── LibraryManagementApplication.java
│   │   │   ├── config/SecurityConfig.java
│   │   │   ├── controller/
│   │   │   │   ├── AuthController.java
│   │   │   │   ├── CatalogController.java
│   │   │   │   ├── BorrowController.java
│   │   │   │   ├── UsersController.java
│   │   │   ├── model/
│   │   │   │   ├── UsersModel.java
│   │   │   │   ├── BorrowRecordModel.java
│   │   │   │   ├── CatalogModel.java
│   │   │   ├── repository/
│   │   │   │   ├── UsersRepository.java
│   │   │   │   ├── BorrowRecordRepository.java
│   │   │   │   ├── CatalogRepository.java
│   │   │   ├── service/
│   │   │   │   ├── UserDetailsServiceImpl.java
│   │   │   │   ├── BorrowService.java
│   │   │   │   ├── CatalogService.java
│   │   │   │   ├── UsersService.java
│   │   ├── resources/
│   │   │   ├── templates/
│   │   │   │   ├── index.html
│   │   │   │   ├── login.html
│   │   │   │   ├── user-dashboard.html
│   │   │   │   ├── book-list.html
│   │   │   │   ├── borrow-books.html
│   │   │   │   ├── borrow-history.html
│   │   │   ├── static/
│   │   │   │   ├── styles.css
│   │   │   │   ├── borrow.js
│   │   │   │   ├── catalog.js
│   │   │   │   ├── user.js
│   │   │   ├── application.properties
│   │   │   ├── data.sql
│   ├── test/
│   │   ├── java/com/as/LibraryManagementSystem/AppTest.java

alphasierra24-lib-mgmt/
│── pom.xml
│── src/
│   ├── main/
│   │   ├── java/com/cts/LibraryManagementSystem/
│   │   │   ├── LibraryManagementApplication.java
│   │   │   ├── config/SecurityConfig.java
│   │   │   ├── controller/
│   │   │   │   ├── AuthController.java
│   │   │   │   ├── CatalogController.java
│   │   │   │   ├── BorrowController.java
│   │   │   │   ├── UsersController.java
│   │   │   ├── model/
│   │   │   │   ├── UsersModel.java
│   │   │   │   ├── BorrowRecordModel.java
│   │   │   │   ├── CatalogModel.java
│   │   │   ├── repository/
│   │   │   │   ├── UsersRepository.java
│   │   │   │   ├── BorrowRecordRepository.java
│   │   │   │   ├── CatalogRepository.java
│   │   │   ├── service/
│   │   │   │   ├── UserDetailsServiceImpl.java
│   │   │   │   ├── BorrowService.java
│   │   │   │   ├── CatalogService.java
│   │   │   │   ├── UsersService.java
│   │   ├── resources/
│   │   │   ├── templates/
│   │   │   │   ├── index.html
│   │   │   │   ├── login.html
│   │   │   │   ├── user-dashboard.html
│   │   │   │   ├── book-list.html
│   │   │   │   ├── borrow-books.html
│   │   │   │   ├── borrow-history.html
│   │   │   ├── static/
│   │   │   │   ├── styles.css
│   │   │   │   ├── borrow.js
│   │   │   │   ├── catalog.js
│   │   │   │   ├── user.js
│   │   │   ├── application.properties
│   ├── test/
│   │   ├── java/com/as/LibraryManagementSystem/AppTest.java

Execution starts from File: LibraryManagementApplication.java
When the application starts, it loads all configurations and initializes the embedded Tomcat server.
Many Spring Boot starters include default embedded containers. 
For servlet stack applications, the spring-boot-starter-web includes Tomcat by including spring-boot-starter-tomcat , but you can use spring-boot-starter-jetty or spring-boot-starter-undertow instead.
