# Blockchain Access Control System

A full-stack application with Spring Boot (backend) and React (frontend).

## Prerequisites

- **Java 17** (for Spring Boot)
- **Maven** (for Spring Boot)
- **Node.js 18+** and **npm** (for React)
- **Git**

## Setup

### Backend (Spring Boot)

1. Navigate to the backend directory:

   ```bash
   cd backend

   Build the project:
   mvn clean install

   Run the application:
   mvn spring-boot:run
   ```

navigate to the frontend project

```bash
cd frontend
```

Run the application:

```bash
mvn spring-boot:run
```

Install dependencies

```bash
npm install
```

Start the development server

```bash
npm start
```


## Local configuration

Copy `access-control-system/.env.example` to `access-control-system/.env` and set your own local credentials before running. The properties file reads the administrator key, database password, and Jasypt secret from the environment. Do not commit `.env` or real private keys.
