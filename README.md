# Doctor Patient Management System

Welcome to our innovative platform designed to empower doctors in managing their patient interactions seamlessly, whether through mobile or web portals. Our sophisticated backend APIs are meticulously crafted to streamline essential tasks, including doctor registration, patient enrollment alongside their symptoms, and providing personalized doctor recommendations based on patient symptoms.

## Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Swagger UI

## Features

- Registration of doctors
- Deletion of doctors by DoctorId
- Registration of patients
- Deletion of patients by patientID
- Suggesting the best doctors based on patients' locations and symptoms

## Modules

- Doctor Module
- Patient Module
- DoctorSuggestion Module

## Installation & Run

Before running the API server, update the database configuration inside the `application.properties` file.

```properties
# Changing the server port
server.port=8888

# Database specific properties
spring.datasource.url=jdbc:mysql://127.0.0.1:3306/PatienttManagement
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=****
spring.datasource.password=****

# ORM software specific properties
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
