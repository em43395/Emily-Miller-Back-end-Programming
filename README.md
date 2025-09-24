Travel Agency Backend (Spring Boot + MySQL)

This project is a modernized Spring Boot backend built to replace a legacy system for a travel agency’s vacation booking platform. The backend integrates with a provided Angular front end and MySQL database, ensuring smooth booking and checkout functionality.

🔹 Features & Implementation

Object-Oriented Design: Created entity classes and enums aligned with UML diagrams to model customers, orders, excursions, and vacation packages.

Data Access Layer: Implemented DAO repositories with JpaRepository and cross-origin support for Angular integration.

Service Layer: Built purchase handling, order tracking response, and a checkout service with validation.

Controller Layer: Exposed RESTful endpoints for booking vacations, excursions, and customer orders.

Validation: Enforced business rules and input validation to prevent incomplete or invalid submissions.

Database Integration: Connected Spring Boot to MySQL with JPA, persisting customer and order data.

Sample Data: Preloaded five customers and enabled proper handling so data is not overwritten at runtime.

End-to-End Demo: Successfully added a vacation order with multiple excursions through the Angular frontend, confirmed in MySQL Workbench.

🔹 Skills Demonstrated

Java + Spring Boot (OOP, design patterns, REST APIs)

Relational database integration (MySQL + JPA)

Full-stack system integration with Angular frontend

Validation, error handling, and professional documentation

Git version control with iterative commits
