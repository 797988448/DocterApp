# <h1 align = "center">  Doctor app </h1>
___ 
<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.1.3-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
</p>

---

<p align="left">

<!-- Project Description -->
## Overview
<p align="center">This project,   Insta Basic ," is a robust Spring Boot application designed for managing user data efficiently. It provides a set of API endpoints that allow you to perform various operations on user records, such as adding, retrieving, updating, and deleting user information. 
</p>

<!-- Table of Contents -->
## Table of Contents
1. [Technologies Used](#technologies-used)
2. [Key Features](#key-features)
3. [Usage](#usage)
4. [API reference](#api-reference)
5. [License](#license)
6. [Acknowledgments](#acknowledgments)
7. [Contact](#contact)

<!-- Technologies Used -->
## Technologies Used
- Java 8
- Spring Boot
- Spring Web Initializer
- Maven
- Spring Web Dependency
- SQL DRIVER
- JPA
- SWAGGER
- sQL DATABASE
- OneToOne Mapping
- OneToMany Mapping
- ManyToMany Mapping
- ManyToOne Mapping

## Model Classes
1. Admin Mode
The Admin mode is designed for administrative staff to manage the system, including adding and managing doctors and patients, as well as overseeing appointments.
2. Appointment Mode
In this mode, users can schedule, view, and manage appointments with doctors. This includes checking appointment availability and confirming or canceling appointments.
3. Doctor Mode
The Doctor mode is for healthcare professionals to access their patient appointments, view patient information, and update their availability.
4. Patient Mode
Patients can use this mode to view their scheduled appointments, update personal information, and contact the hospital.
## Controller Class
1. Admin Controller
The Admin Controller is responsible for handling administrative tasks, including user management, doctor and patient record management, and appointment supervision.
2. Appointment Controller
The Appointment Controller handles appointment-related operations, such as scheduling appointments, managing appointment availability, and sending notifications to users.
3. Doctor Controller
The Doctor Controller manages doctor-related functionalities, such as retrieving patient appointments, updating doctor availability, and handling patient information.
4. Patient Controller
The Patient Controller oversees patient-specific operations, including viewing scheduled appointments, updating personal information, and communication with the hospital.
## Service Class
1. Admin Service
The Admin Service is responsible for executing administrative tasks, including user management, doctor and patient record management, and appointment supervision.
2. Appointment Service
The Appointment Service manages appointment-related operations, such as scheduling appointments, managing appointment availability, and sending notifications to users.
3. Doctor Service
The Doctor Service handles doctor-related functionalities, such as retrieving patient appointments, updating doctor availability, and handling patient information.
4. Patient Service
The Patient Service oversees patient-specific operations, including viewing scheduled appointments, updating personal information, and communication with the hospital.
5. Email Service
The Email Service is responsible for sending email notifications to users for appointment reminders and other important messages.
6. Ptoken Service
The Ptoken Service generates and manages secure tokens for authentication and authorization purposes.
7. AppointmentService
The AppointmentService coordinates appointment-related operations and ensures the smooth functioning of the appointment scheduling system.
Features
Implementation of core service functionalities based on the modes.
Integration with the Controller to execute user requests.
Sending email notifications and reminders to users.
Generation and validation of secure tokens for authentication.
Coordinating appointment scheduling and management.
Service Architecture
The Service component follows a modular and service-oriented architecture to ensure the efficient execution of various tasks. It interacts with the Controller and external services (such as Email and Ptoken) to provide a seamless experience to users.

<!-- Key Features -->
## Key Features
- Get Student by Id.
- Get all Sudent.
- Get Student Details By Id.
- Delete Course By Id.
- Update StudentName
- SingUp
- SingIn

<!-- Usage -->
## Usage
- Access the application at `http://localhost:8080`.
- Use the provided API endpoints to CRUD Operation And Custom finder.

### Controller:
- It consists of a class named APIController which basically controls the flow of data.
- @RestController annotation is used to make the APIController as a controller layer.
- We perform the CRUD operations such as @PostMapping , @GetMapping , @PutMapping , @DeleteMapping.

### API Reference

#### Add Users :
PostMethod :  http://localhost:8080/posts
### UPdate User:
PutMapping : http://localhost:8080/companyName/Id

### Delete User:
DeleteMapping: http://localhost:8080/Delete/Id/


#### Get All Users :
 - GET Method : http://localhost:8080/get

 

 <!-- Acknowledgments -->
## Acknowledgments
- Thank you to the Spring Boot and Java communities for providing excellent tools and resources.

<!-- Contact -->
## Contact
For questions or feedback, please contact : SHRAVAN KUMAR   -
- Maild Id : shravankm93@gmail.com

<h1 align="center">Thank You...<h1>
<h3 align = "center"> ***********************************************************<h3>
*  Insta Basic 
