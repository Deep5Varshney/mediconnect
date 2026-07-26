# MediConnect – Healthcare Management Platform

MediConnect is a full-stack healthcare platform designed to simplify interactions between patients and healthcare providers. The application enables users to securely manage medical records, schedule appointments, discover nearby hospitals, and access essential healthcare services through a modern, intuitive interface.

The platform focuses on improving accessibility, reducing administrative overhead, and delivering a seamless digital healthcare experience.

---

# Overview

Healthcare systems often struggle with fragmented patient information, inefficient appointment management, and limited accessibility.

MediConnect addresses these challenges by providing a centralized platform where patients and healthcare providers can efficiently manage healthcare-related information and services.

---

# Architecture

```text
                 Patient / Doctor
                        │
                        ▼
               React Frontend (Vite)
                        │
             REST API Requests
                        │
                        ▼
                 Go Backend Server
                        │
        ┌───────────────┴───────────────┐
        ▼                               ▼
 Authentication                 Business Logic
        │                               │
        └───────────────┬───────────────┘
                        ▼
                  SQLite Database
                        │
                        ▼
       Patient Records • Appointments
       Hospital Information • User Data
```

---

# Tech Stack

| Technology | Purpose |
|------------|---------|
| Go (Golang) | Backend Development |
| React.js | Frontend |
| TypeScript | Frontend Development |
| Vite | Build Tool |
| Tailwind CSS | Styling |
| ShadCN UI | UI Components |
| SQLite | Database |
| SQLC | Database Query Generation |
| JWT Authentication | Secure Login |
| Git & GitHub | Version Control |

---

# Features

- 👨‍⚕️ Patient Registration & Authentication
- 🔐 Secure User Login
- 🏥 Hospital Discovery
- 📅 Appointment Scheduling
- 📋 Medical History Management
- 💊 Medication Tracking
- 👤 Patient Profile Management
- 📍 Nearby Hospital Search
- ⚡ Fast & Responsive User Interface
- 🔒 Secure Database Management

---

# Core Functionalities

### User Authentication

- Secure Signup
- Login with JWT Authentication
- Protected Routes
- Session Management

### Patient Management

- Create Patient Profile
- Update Personal Information
- Store Medical History
- View Healthcare Records

### Appointment System

- Book Appointments
- View Appointment Details
- Manage Appointment History

### Hospital Services

- Browse Hospitals
- View Hospital Details
- Search Healthcare Facilities

---

# Project Workflow

```text
User Registration
        │
        ▼
Secure Authentication
        │
        ▼
Patient Dashboard
        │
        ├──────────────┐
        ▼              ▼
Medical Records   Book Appointment
        │              │
        └──────┬───────┘
               ▼
      Hospital Management
               │
               ▼
      Healthcare Services
```

---

# Installation

Clone the repository

```bash
git clone https://github.com/Deep5Varshney/mediconnect.git
```

Navigate into the project

```bash
cd mediconnect
```

---

## Backend Setup

Install Go dependencies

```bash
go mod tidy
```

Run the backend server

```bash
go run main.go
```

---

## Frontend Setup

Navigate to frontend

```bash
cd frontend
```

Install dependencies

```bash
npm install
```

Start the development server

```bash
npm run dev
```

---

# Usage

1. Register a new account.
2. Log in securely.
3. Complete your medical profile.
4. Browse nearby hospitals.
5. Book appointments.
6. Access medical history.
7. Manage healthcare information.

---

# Project Structure

```text
mediconnect/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── package.json
│
├── controllers/
├── routes/
├── middleware/
├── database/
├── models/
├── queries/
├── main.go
├── go.mod
├── README.md
└── LICENSE
```

---

# Security Features

- JWT Authentication
- Password Encryption
- Protected API Endpoints
- Secure User Sessions
- Input Validation
- Database Security

---

# Performance Highlights

- Lightweight Go backend
- Fast API response times
- Efficient SQL query generation using SQLC
- Responsive React frontend
- Modular and scalable architecture
- Optimized database operations

---

# Future Enhancements

- AI-based Symptom Checker
- Telemedicine & Video Consultation
- Digital Prescription Management
- Medical Report Upload
- Email & SMS Notifications
- Online Payment Gateway
- Doctor Dashboard
- Electronic Health Records (EHR)
- Health Analytics Dashboard
- Mobile Application

---

# Learning Outcomes

This project strengthened my understanding of:

- Full-Stack Web Development
- Go Backend Development
- REST API Design
- Authentication & Authorization
- SQL Database Design
- React & TypeScript
- State Management
- Responsive UI Development
- Secure Application Development

---
