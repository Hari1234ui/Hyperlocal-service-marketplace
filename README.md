# ConnectLocal

## Project Overview

ConnectLocal is a full stack Hyperlocal Service Marketplace that connects customers with nearby service providers. Users can register, log in, browse available services, book appointments, and manage bookings through a responsive web interface backed by a Spring Boot REST API.

## Features

* User Registration and Login
* Service Provider Registration
* Browse Available Services
* Book Services Online
* View and Manage Bookings
* REST API Integration
* MySQL Database
* Responsive User Interface

## Technology Stack

Frontend

* HTML5
* CSS3
* JavaScript

Backend

* Java
* Spring Boot
* Spring Data JPA
* Maven

Database

* MySQL

## Project Structure

```text
ConnectLocal/
├── backend/
├── frontend/
└── README.md
```

## Prerequisites

* Java 17 or later
* Maven
* MySQL Server
* Git

## Running the Project

Clone the repository

```bash
git clone https://github.com/<your-username>/ConnectLocal.git
cd ConnectLocal
```

Create a MySQL database named:

```sql
connectlocal_db
```

Configure database credentials

PowerShell

```powershell
$env:DB_USERNAME="root"
$env:DB_PASSWORD="your_password"
```

Start the backend

```bash
cd backend
mvn spring-boot:run
```

The backend runs at

```text
http://localhost:8080
```

Run the frontend

Open the frontend folder using VS Code Live Server or any local web server and open the index.html file.

The frontend communicates with

```text
http://localhost:8080/api
```

## Modules

* Customer Registration
* Provider Registration
* Login
* Service Listing
* Service Booking
* Booking Management

## API

Base URL

```text
http://localhost:8080/api
```

## Future Improvements

* JWT Authentication
* Online Payment Integration
* Email Notifications
* Admin Dashboard
* Reviews and Ratings
* Location Based Search

## Author

B. Hari Shankar

GitHub: https://github.com/<your-github-username>

