# Prisma ORM Practical

This project demonstrates how to use **Prisma ORM** with **Express.js** to build a backend API for managing student records. It covers model definition, database migrations, CRUD operations, and best practices for error and resource management.

## Features

- RESTful API endpoints for student records
- Create and retrieve students using Prisma
- Robust error handling and status codes
- Graceful shutdown of database connections
- Example code for integrating Prisma with Express

## Technologies Used

- Node.js
- Express.js
- Prisma ORM
- PostgreSQL

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- PostgreSQL database
- npm

### Installation

1. Clone the repository or copy the project files.
2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure your `.env` file with the correct `DATABASE_URL` for your PostgreSQL instance.

4. Run Prisma migrations to set up the database schema:

   ```bash
   npx prisma migrate dev --name init
   ```

5. Start the server:

   ```bash
   npm start
   ```

   The server will run on `http://localhost:5100` by default.

## API Usage

- **GET /students**: Retrieve all students
- **GET /students/:id**: Retrieve a student by ID
- **POST /students**: Create a new student (provide `name`, `email`, `course`, `enrollment_date` in the request body)

## License

This project is for educational purposes.
