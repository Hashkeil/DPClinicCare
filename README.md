# DPClinicCare - Clinic Management System

## Overview
DPClinicCare is a **clinic management system** for appointment scheduling, patient records, and doctor availability tracking. Built with **Java, Spring Boot, and MySQL**, it provides secure authentication, RESTful APIs, and JUnit testing.

## Features
- **User Authentication & Role Management**
- **Appointment Scheduling**
- **Patient Record Management**
- **Doctor Availability Tracking**
- **RESTful APIs**
- **Automated Testing with JUnit**

## Tech Stack
- **Backend:** Java, Spring Boot
- **Database:** MySQL
- **Testing:** JUnit
- **Version Control:** Git, GitHub

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/DPClinicCare.git
   ```
2. Navigate to the project directory:
   ```sh
   cd DPClinicCare
   ```
3. Configure the database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/clinic_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```
4. Run the application:
   ```sh
   mvn spring-boot:run
   ```

## API Endpoints
| Endpoint             | Method | Description                     |
|----------------------|--------|---------------------------------|
| `/api/auth/login`   | POST   | User authentication            |
| `/api/patients`     | GET    | Retrieve all patients          |
| `/api/doctors`      | GET    | Retrieve all doctors           |
| `/api/appointments` | POST   | Schedule an appointment        |

## Testing
Run JUnit tests with:
```sh
mvn test
```

## Contributing
Feel free to submit pull requests or report issues!


