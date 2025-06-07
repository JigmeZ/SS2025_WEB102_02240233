# Designing and Implementing RESTful API Endpoints

## Objectives

1. Design RESTful API endpoints following best practices for URI design
2. Implement API endpoints with proper HTTP methods and status codes
3. Configure content negotiation with different MIME types
4. Set up proper request and response handling
5. Document your API endpoints

## Part 1: API Design

### Scenario

### You are building a social media platform similar to Instagram with the following resources:

● Posts
● Users
● Comments
● Likes
● Followers

### Tasks

1. For each resource, design endpoints for the following operations:
   ○ List all items
   ○ Get a specific item
   ○ Create a new item
   ○ Update an existing item
   ○ Delete an item

# Reflection

## Documentation

### Main Concepts Applied

- **RESTful API Design**: Designed endpoints for resources such as Posts, Users, Comments, Likes, and Followers, following RESTful conventions.
- **HTTP Methods and Status Codes**: Used appropriate HTTP methods (GET, POST, PUT/PATCH, DELETE) and status codes for each operation.
- **Content Negotiation**: Configured the API to handle different MIME types for requests and responses.
- **Request and Response Handling**: Ensured proper validation and formatting of incoming requests and outgoing responses.
- **API Documentation**: Documented all endpoints, including their URIs, methods, expected inputs, and outputs.

## Reflection

### What I Learned

Through this practical, I learned how to design RESTful APIs that are intuitive, scalable, and easy to maintain. I gained experience in structuring endpoints for multiple resources and ensuring that each operation uses the correct HTTP method and status code. Implementing content negotiation helped me understand how APIs can support different data formats, improving flexibility for clients.

I also realized the importance of clear and thorough documentation, which is essential for both developers and API consumers. Setting up proper request and response handling improved my attention to detail and helped me write more robust code.

### Challenges Faced

One challenge was ensuring consistency in endpoint naming and HTTP method usage across different resources. I overcame this by referring to RESTful best practices and reviewing examples from established APIs.

Another challenge was handling content negotiation and supporting multiple MIME types. I researched how to configure this in the backend framework and tested different scenarios to ensure correct behavior.

Overall, this exercise strengthened my understanding of RESTful API design and gave me practical skills that will be valuable in future backend projects.
