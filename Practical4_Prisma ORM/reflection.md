# Reflection

## Documentation

### Main Concepts Applied

- **Prisma ORM**: Used Prisma to define models, manage migrations, and interact with a PostgreSQL database.
- **Express.js**: Built RESTful API endpoints for creating and retrieving student records.
- **CRUD Operations**: Implemented Create and Read operations using Prisma's API.
- **Error Handling**: Ensured robust error handling and appropriate HTTP response codes.
- **Resource Management**: Managed database connections and ensured graceful shutdown of the Prisma client.

## Reflection

### What I Learned

This project gave me hands-on experience integrating Prisma ORM with Express.js to build a backend API. I learned how to set up Prisma, define data models, and perform CRUD operations efficiently. Structuring API endpoints and handling asynchronous operations improved my understanding of Express routing and middleware.

I also realized the importance of clear error handling and returning proper status codes to make the API user-friendly and reliable. Managing database connections and shutting down the Prisma client gracefully taught me best practices for backend resource management.

### Challenges Faced

One challenge was configuring Prisma and connecting it to the PostgreSQL database. I encountered issues with the database URL format, which I resolved by carefully checking the connection string and Prisma documentation.

Another challenge was handling errors gracefully, especially when dealing with invalid input or database failures. I improved the error handling logic to provide meaningful responses and status codes.

Overall, this project strengthened my backend development skills and deepened my understanding of integrating ORMs with Express for building maintainable APIs.
