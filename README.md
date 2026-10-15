# HelpDesk — IT Support Ticket Management System

A Java full-stack web application for managing IT support tickets, built using Spring Boot, Thymeleaf, Bootstrap, and relational database technologies.

## Features

- Create IT support tickets
- View ticket details
- Track ticket status: Open, In Progress, and Resolved
- Categorize tickets by priority
- Search and filter tickets
- Dashboard with ticket statistics
- Persistent storage using Spring Data JPA

## Tech Stack

- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA / Hibernate
- Thymeleaf
- HTML, CSS, JavaScript, Bootstrap
- MySQL for development
- H2 for standalone demo mode
- Maven

## Run Locally

1. Install JDK 17 and MySQL.
2. Create the `helpdesk_db` database in MySQL.
3. Configure your database credentials using the `DB_PASSWORD` environment variable.
4. Open the project in IntelliJ IDEA or use Maven.
5. Run the `HelpdeskApplication` main class.
6. Visit http://localhost:8082/.

## Build

```bash
mvn clean package
```

## Demo Mode

The project includes an H2-based demo profile intended to run without a separate MySQL server.

Build the application and activate the `demo` Spring profile when launching the executable JAR.

## Project Structure

- `entity` — ticket data model
- `repository` — database access
- `service` — business logic
- `controller` — web request handling
- `templates` — Thymeleaf HTML pages

## Purpose

Developed as an internship evaluation project to demonstrate Java full-stack development, MVC architecture, database integration, and CRUD workflows.
