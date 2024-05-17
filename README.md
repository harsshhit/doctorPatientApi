# Doctor Patient Management System

Platform where doctors can register their patients through a mobile or web portal. This system includes backend APIs to achieve tasks such as adding a doctor, adding a patient and their symptoms, and suggesting doctors based on patient symptoms.

## Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Swagger UI

## Features

- Register a doctor
- Delete any doctor by DoctorId
- Register a patient
- Delete a patient by patientID
- Suggest best doctors based on patient's location and symptoms

## Modules

- Doctor Module
- Patient Module
- Doctor Suggestion Module

## Installation & Run

Before running the API server, update the database config inside the `application.properties` file.

```properties
# Changing the server port
server.port=8888

# Database specific properties
spring.datasource.url=jdbc:mysql://localhost:3306/DoctorPatientManagementDB
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=myUsername
spring.datasource.password=myPassword

# ORM software specific properties
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
