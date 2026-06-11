# 🏥 Healthcare Appointment Booking System

A scalable Healthcare Appointment Booking System built using **NestJS**, **TypeScript**, and **MySQL/PostgreSQL**. The platform enables patients to book appointments with doctors, manage schedules, and streamline healthcare service management.

---

## 📌 Features

### 👨‍⚕️ Doctor Management

* Doctor registration and profile management
* Specialty categorization
* Availability schedule management
* Appointment tracking

### 🧑‍🤝‍🧑 Patient Management

* Patient registration and authentication
* Profile management
* Appointment booking and cancellation
* Appointment history

### 📅 Appointment System

* Real-time appointment scheduling
* Appointment status tracking
* Conflict-free booking system
* Appointment reminders and notifications

### 🔐 Authentication & Authorization

* JWT-based authentication
* Role-based access control (RBAC)
* Secure API endpoints
* Password encryption using bcrypt

### 📊 Admin Dashboard

* Manage doctors and patients
* Monitor appointments
* Generate reports
* System analytics

---

## 🏗️ Tech Stack

| Technology         | Purpose              |
| ------------------ | -------------------- |
| NestJS             | Backend Framework    |
| TypeScript         | Programming Language |
| TypeORM            | ORM                  |
| MySQL / PostgreSQL | Database             |
| JWT                | Authentication       |
| bcrypt             | Password Hashing     |
| Swagger            | API Documentation    |

---

## 📂 Project Structure

```bash
src/
├── auth/
├── users/
├── doctors/
├── patients/
├── appointments/
├── notifications/
├── common/
├── database/
├── config/
├── app.module.ts
└── main.ts
```

---

## 🗄️ Database Design

### ER Diagram

![ER Diagram](./ER%20diagram/Healthcare%20appointment%20booking%20system%20diagram.png)

### Main Entities

* Users
* Patients
* Doctors
* Appointments
* Schedules
* Specializations
* Notifications

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/healthcare-appointment-booking-system.git
```

```bash
cd healthcare-appointment-booking-system
```

### Install Dependencies

```bash
npm install
```

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory:

```env
PORT=3000

DB_HOST=localhost
DB_PORT=3306
DB_USERNAME=root
DB_PASSWORD=password
DB_NAME=healthcare_db

JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=1d
```

---

## ▶️ Running the Application

### Development Mode

```bash
npm run start:dev
```

### Watch Mode

```bash
npm run start
```

### Production Mode

```bash
npm run build
npm run start:prod
```

---

## 📚 API Documentation

Generate Swagger documentation:

```bash
http://localhost:3000/api
```

Example API Endpoints:

### Authentication

```http
POST /auth/register
POST /auth/login
```

### Doctors

```http
GET /doctors
GET /doctors/:id
POST /doctors
PUT /doctors/:id
DELETE /doctors/:id
```

### Patients

```http
GET /patients
GET /patients/:id
POST /patients
PUT /patients/:id
DELETE /patients/:id
```

### Appointments

```http
POST /appointments
GET /appointments
PUT /appointments/:id
DELETE /appointments/:id
```

---

## 🧪 Testing

### Unit Tests

```bash
npm run test
```

### End-to-End Tests

```bash
npm run test:e2e
```

### Coverage Report

```bash
npm run test:cov
```

---

## 🔒 Security Features

* JWT Authentication
* Password Hashing (bcrypt)
* Input Validation
* Role-Based Access Control
* Secure Environment Variables
* Exception Handling

---

## 📈 Future Enhancements

* Video Consultation Integration
* Email & SMS Notifications
* Payment Gateway Integration
* Electronic Health Records (EHR)
* AI-Based Appointment Recommendations
* Multi-Hospital Support

---

## 👨‍💻 Author

**Shreevatsa G S**

* GitHub: https://github.com/your-github-username

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

Contributions, issues, and feature requests are welcome!
