# Employee Management System

A full-stack web application for managing employee data efficiently with Spring Boot backend and React frontend.

## Features

- **Employee Dashboard**: View all employees with pagination and search functionality
- **CRUD Operations**:
  - Add new employee records with validation
  - Edit existing employee details
  - Remove employees from the system
- **Responsive Design**: Works on desktop and mobile devices
- **REST API**: Complete CRUD operations via REST endpoints
- **Database Integration**: MySQL with JPA for data persistence

## Technologies Used

### Backend
- Spring Boot (Java)
- Spring Data JPA
- MySQL
- Maven

### Frontend
- React (Vite)
- Bootstrap
- Axios

### DevOps
- Docker
- Render (Backend)
- Railway (Database)
- Netlify (Frontend)

## Live Demo

[View Live Application](https://ems-springboot-application-kvr10.netlify.app/)

> **Note**: The backend service on Render may take ~50 seconds to respond on first request due to cold start.

## Screenshots

![Dashboard](screenshots/dashboard.png)
![Add Employee](screenshots/add-employee.png)
![Update Employee](screenshots/update-employee.png)

## Installation

### Prerequisites
- Java JDK 17+
- Node.js 16+
- MySQL 8+
- Maven
- npm

## Backend Setup

Clone the repository:
```bash
git clone https://github.com/Kvr-10/Employee-Management-System.git
cd Employee-Management-System/backend
```
## Configure environment variables:

```bash
# Create .env file
echo "DATASOURCE_URL=jdbc:mysql://your-database-url" >> .env
echo "DATASOURCE_USER=your-username" >> .env
echo "DATASOURCE_PASSWORD=your-password" >> .env
echo "FRONTEND_URL=your-frontend-url" >> .env
```

## Build and Run

```bash
mvn clean install
mvn spring-boot:run
```

## Frontend Setup

### Navigate to frontend directory:

```bash
cd ../frontend
```

### Install dependencies and run:

```bash
npm install
npm run dev
```

## Deployment

| Component  | Service  |
|------------|---------|
| Frontend   | Netlify |
| Backend    | Render  |
| Database   | Railway |

## API Endpoints

| Method | Endpoint               | Description          |
|--------|------------------------|----------------------|
| GET    | /api/employees         | Get all employees   |
| POST   | /api/employees         | Create new employee |
| GET    | /api/employees/{id}    | Get employee by ID  |
| PUT    | /api/employees/{id}    | Update employee     |
| DELETE | /api/employees/{id}    | Delete employee     |

## Contact

- **Email:** chamansinha9480@gmail.com
- **Portfolio:** [Chaman Sinha](https://kvr-10.github.io)
- **GitHub:** [@Kvr-10](https://github.com/Kvr-10)

