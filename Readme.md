# Academia-Synapse [Student Management System (SMS)]

A full-stack application for managing student records, built with Node.js/Express/MongoDB for the backend and React for the frontend.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Application Setup](#application-setup)
- [Running Tests](#running-tests)

## Features

- **CRUD Operations**: Complete functionality to Create, Read, Update, and Delete student records.
- **Frontend/Backend Separation**: Clear separation between the React UI and the REST API.
- **Unit Tested**: Both the API (Jest/Supertest) and the UI components (Jest/RTL) are covered with unit tests.
- **Persistent Data**: Uses MongoDB to store student data permanently.

## Technologies Used

### Backend (Node.js/Express)
- **Node.js**: Runtime environment.
- **Express.js**: Web application framework for REST API.
- **MongoDB**: NoSQL database.
- **Mongoose**: ODM for MongoDB.
- **Jest & Supertest**: For API unit and integration testing.

### Frontend (React)
- **React**: JavaScript library for building the UI.
- **Axios**: HTTP client for API communication.
- **Jest & React Testing Library (RTL)**: For component unit testing.

## Project Structure

The project is divided into two main folders: `backend` for the API and `frontend` for the UI.

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

-   **Node.js** (v18 or higher)
-   **npm** (Node Package Manager)
-   **MongoDB** (A running instance of MongoDB, either local or cloud-based)

### Application Setup

1.  **Navigate to the academia-synapse directory:**
    ```bash
    cd academia-synapse-docker
    ```

2.  **Use docker-compose to start the application:**
    ```bash
    # a. Start the frontend, backend and database together
    docker compose up -d --build
    
    # b. verify if the backend is able to connect to DB
    docker compose logs -f backend
    
    #c. Access the frontend
    http://localhost:3000
    ```

3.  **Stop Application:**
    ```bash
    docker compose down
    ```

Author - Soumiyajit Das Chowdhury


























