# Blogging Platform

A professional full-stack Blogging Platform built using Java and Spring Boot. This project is being developed as a practical learning and portfolio project, following industry-standard Java development practices.

## Project Overview

The Blogging Platform aims to provide a web application where users can create, publish, view, and manage blog posts.

The project is being developed incrementally, starting with the Spring Boot application foundation and gradually introducing database integration, authentication, authorization, and other features.

## Technology Stack

| Technology | Purpose |
|---|---|
| Java 21 | Programming language |
| Spring Boot 3.5.16 | Backend application framework |
| Maven | Dependency and build management |
| Spring Web | HTTP requests and REST APIs |
| Thymeleaf | Server-side HTML rendering |
| Spring Boot DevTools | Development support |
| HTML5 | Web page structure |
| CSS3 | Styling |
| JavaScript | Frontend interactions |
| Git | Version control |
| GitHub | Remote repository hosting |
| IntelliJ IDEA | Development environment |

## Prerequisites

Make sure the following software is installed:

- JDK 21
- IntelliJ IDEA
- Git
- Maven (the project includes Maven Wrapper)

## Getting Started

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the project directory

```bash
cd BloggingPlatform
```

### 3. Build the project

On Windows PowerShell:

```powershell
.\mvnw.cmd clean install
```

### 4. Run the application

```powershell
.\mvnw.cmd spring-boot:run
```

Alternatively, open the project in IntelliJ IDEA and run `BloggingPlatformApplication.java`.

### 5. Open the application

Visit:

http://localhost:8090/

Note: The homepage and application features will be implemented in upcoming development modules. A 404 response at this stage does not necessarily indicate an application startup failure.

## Project Structure

```text
BloggingPlatform/
│
├── .mvn/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── blogging/
│   │   │           └── BloggingPlatformApplication.java
│   │   │
│   │   └── resources/
│   │       ├── static/
│   │       ├── templates/
│   │       └── application.properties
│   │
│   └── test/
│
├── .gitignore
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
```

## Development Roadmap

The application will be developed in multiple phases.

- [x] Spring Boot project initialization
- [x] Java 21 configuration
- [x] Maven configuration
- [x] Spring Web dependency
- [x] Thymeleaf dependency
- [x] Git repository initialization
- [ ] Home page development
- [ ] MySQL database integration
- [ ] Spring Data JPA and Hibernate
- [ ] User registration and login
- [ ] Spring Security integration
- [ ] Blog creation and management
- [ ] Categories and tags
- [ ] Comments and likes
- [ ] Input validation and exception handling
- [ ] Testing
- [ ] Deployment

## Development

This project is being developed incrementally with a focus on:

- Clean code and layered architecture
- REST API development
- Database design
- Secure authentication and authorization
- Maintainable and testable code

## License

This project is currently intended for educational and portfolio purposes.
