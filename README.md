🛠️ Project Overview

The Hospital Management System (HMS) is a backend application designed to efficiently manage hospital operations. It allows hospitals to store and manage patient records, doctor details, medical prescriptions, and billing information in a structured database.

This project is built using Java, Spring Boot, and MySQL, providing a robust and scalable system for healthcare institutions.

💪 Tech Stack

Backend: Java, Spring Boot, Spring Data JPA

Database: MySQL

REST API Testing: Postman

Build Tool: Maven

Version Control: Git

🚀 Features

✔ Patient Management – Add, update, delete, and retrieve patient details.✔ Doctor Management – Assign doctors to patients and manage their schedules.✔ Prescription Management – Store and retrieve medical prescriptions.✔ Billing System – Maintain a record of patient fees and payments.✔ Database Integration – Uses MySQL for efficient data storage and retrieval.✔ RESTful APIs – Exposes endpoints for CRUD operations on hospital data.

🛠️ Setup Instructions

✅ Clone the Repository

git clone https://github.com/yourusername/hospital-management-system.git
cd hospital-management-system

✅ Configure MySQL Database

Ensure MySQL is running and create a database:

CREATE DATABASE Hospital_Management;

Update src/main/resources/application.properties with your MySQL credentials:

spring.datasource.url=jdbc:mysql://localhost:3306/Hospital_Management
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update

✅ Build and Run the Application

mvn clean install
mvn spring-boot:run

After running successfully, open in the browser:

http://localhost:8080

🛠️ API Endpoints

Method

Endpoint

Description

GET

/api/v1/patients

Get all patients

POST

/api/v1/patients

Add a new patient

GET

/api/v1/patients/{id}

Get a patient by ID

PUT

/api/v1/patients/{id}

Update patient details

DELETE

/api/v1/patients/{id}

Delete a patient

Use Postman or cURL to test the API.

📸 Screenshots

(Add screenshots of API responses or UI, if applicable.)

📝 License

This project is open-source and available under the MIT License.

🚀 Future Enhancements

🔹 Add User Authentication & Role-Based Access (Admin, Doctor, Patient)

🔹 Integrate React or Angular Frontend

🔹 Implement Appointment Scheduling System

