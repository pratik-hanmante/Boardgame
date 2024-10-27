# BoardgameListingWebApp

## Overview

**Board Game Database Full-Stack Web Application**
This web application provides a comprehensive database of board games, along with user-generated reviews. While any visitor can browse the board games and read reviews, logging in is required to contribute content. Regular users have the ability to add board games and reviews, while managers hold additional privileges to edit or delete reviews, along with all the capabilities of regular users.

## Technology Stack

- **Backend**: Java, Spring Boot, Spring MVC, Spring Security
- **Frontend**: Thymeleaf with Thymeleaf Fragments, HTML5, CSS, JavaScript, Bootstrap
- **Database**: H2 (In-memory), JDBC
- **Testing**: JUnit
- **Deployment**: AWS EC2
- **Build Tool**: Maven

## Key Features

- Full-stack web application with a dynamic, user-friendly interface.
- **Role-Based Access Control**:
  - Non-members can view game lists and reviews.
  - Registered users can add games and write reviews.
  - Managers can edit or delete reviews in addition to user privileges.
- Authentication and authorization using Spring Security, with login protection and varying permissions based on user roles.
- CRUD functionality for managing data in the database, with a customized schema and initial data seeded from a `schema.sql` file.
- Separation of concerns within the Spring MVC framework, dividing the project into clear view, controller, and database layers.
- Integration of Thymeleaf fragments to streamline repetitive HTML elements like headers, footers, and navigation.
- Deployed on AWS EC2 for easy online access and scalability.
- Unit testing implemented using the JUnit framework.
