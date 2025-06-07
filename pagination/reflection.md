# Reflection

## Documentation

### Main Concepts Applied

- **Environment Variables**: Used `.env` files to manage sensitive configuration data securely.
- **Database Connections**: Established and managed connections to the database for reliable data access.
- **Pagination**: Implemented both offset-based and cursor-based pagination strategies to efficiently handle large datasets in API responses.
- **Backend Structure**: Organized code into logical modules, separated concerns, and followed best practices for maintainability and scalability.
- **Middleware**: Developed reusable middleware for authentication, validation, and error handling.
- **Supabase Integration**: Leveraged Supabase for storage and authentication, extending backend functionality with cloud services.

## Reflection

### What I Learned

Through this project, I deepened my understanding of backend development, especially regarding API design and efficient data handling. Implementing pagination taught me about the trade-offs between offset-based and cursor-based approaches, and how each affects performance and scalability. I also improved my skills in structuring backend projects for clarity and maintainability, and in writing reusable middleware for common backend tasks.

Working with Supabase gave me practical experience in integrating third-party services and managing authentication and storage in a scalable way. Managing environment variables reinforced the importance of security and configuration management in real-world applications.

### Challenges Faced

One of the main challenges was implementing efficient pagination for endpoints dealing with large datasets. I initially struggled with performance issues when using offset-based pagination, especially as the data grew. By researching and applying cursor-based pagination, I was able to improve response times and scalability.

Another challenge was ensuring that the backend structure remained organized as the project grew. Refactoring code into modules and writing reusable middleware helped keep the codebase clean and maintainable.

Overall, this project enhanced my technical skills, problem-solving abilities, and confidence in building scalable backend solutions.
