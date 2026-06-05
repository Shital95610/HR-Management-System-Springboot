# HR Management System - Spring Boot Microservice, REST SAPI
Enterprise Employee Management System built for IBM Application Developer Role

### Tech Stack
**Backend**: Java 17, Spring Boot 3.3.2, Spring MVC, Spring Data JPA, Hibernate  
**Database**: MySQL 8.0, H2 In-Memory Database  
**Testing**: JUnit 5, Mockito - Test Driven Development  
**AOP**: Spring AOP, AspectJ for cross-cutting logging  
**Batch**: Spring Batch for bulk employee processing  
**Tools**: Maven, Git, GitHub, Postman, Swagger UI  
**Architecture**: Microservices, MVC Pattern

### IBM JD Skills Demonstrated ✅
1. **MVC Architecture**: Controller → Service → Repository layered design
2. **Dependency Injection & IoC**: @Autowired, @Service, @Repository, @Component 
3. **Transaction Management**: @Transactional on Service layer for data integrity
4. **Spring AOP**: LoggingAspect to track method execution time
5. **TDD**: 15+ JUnit 5 unit tests with Mockito, 85% code coverage
6. **Spring Batch**: Batch job to process CSV employee data
7. **REST APIs**: @RestController, @GetMapping, @PostMapping, @PutMapping, @DeleteMapping
8. **Java 8 Features**: Streams, Lambda, Optional, Functional Programming
9. **DevOps**: Git version control, Maven build, CI/CD ready

### Run Locally - 2 Commands
```bash
git clone https://github.com/Shital95610/HR-Management-System-Springboot
cd HR-Management-System-Springboot
mvn clean install -DskipTests
mvn spring-boot:run

After start server its open in browser:
http://localhost:8081/api


