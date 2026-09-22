# CivicPulse Nexus

## Smart Governance Platform for Administrative Operations with Citizen Service Assistance

CivicPulse Nexus is a web-based smart governance platform designed to simplify communication between citizens and government administration. It provides digital access to citizen services, request tracking, administrative management, and citizen assistance.

## Features

### Citizen

* Citizen dashboard
* Apply for government services
* Track submitted requests
* Citizen assistance
* View service/request information

### Admin

* Admin dashboard
* Manage citizen service requests
* Monitor administrative operations
* View and update request status

## Technology Stack

### Frontend

* React
* JavaScript / TypeScript
* HTML
* CSS
* Vite

### Backend

* Java 21
* Spring Boot
* Spring Data JPA
* REST APIs
* Maven

### Database

* PostgreSQL

### Tools

* Visual Studio Code
* Git & GitHub
* Postman
* Docker

## Project Structure

```text
CivicPulse_Nexus/
├── backend/
│   ├── src/
│   ├── pom.xml
│   └── ...
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── docker-compose.yml
├── generate_backend.js
└── generate_frontend.js
```

## How to Run

### Backend

Navigate to the backend folder:

```bash
cd backend
```

Run:

```bash
mvn spring-boot:run
```

The backend runs on:

```text
http://localhost:8080
```

### Frontend

Navigate to the frontend folder:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The frontend normally runs on:

```text
http://localhost:5173
```

## Database

The backend uses PostgreSQL for storing application data.

Configure the database connection in:

```text
backend/src/main/resources/application.yml
```

Do not commit real database passwords or other sensitive credentials to GitHub.

## Project Status

The Spring Boot backend has been successfully executed and connected to the PostgreSQL database. The frontend is configured as a Vite-based React application.

## Team

Developed as part of an internship/project focused on smart governance and citizen service assistance.
