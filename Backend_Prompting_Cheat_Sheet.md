
# Backend Prompting Cheat Sheet for Cursor (and Other AI Code Assistants)

Use this guide to describe backend logic, APIs, data models, and infrastructure tasks clearly—even if you’re not writing the backend code yourself.

---

## 1. CRUD Operations & REST APIs

**Prompt Examples:**
1. Create a REST API endpoint to retrieve a list of products from the database.
2. Add a POST endpoint that creates a new user with email and password.
3. Update the GET endpoint to include pagination and a `search` query parameter.
4. Add error handling to the PUT `/users/:id` endpoint.
5. Use Express.js to define basic CRUD routes for a `Task` model.
6. Connect this route to a MongoDB database using Mongoose.
7. Return a 404 if the record isn’t found.
8. Ensure the DELETE endpoint returns a success message.
9. Use async/await syntax with proper try/catch blocks.
10. Include input validation using `express-validator`.

---

## 2. Authentication & Authorization

**Prompt Examples:**
1. Implement user login using JWT authentication.
2. Hash passwords using bcrypt before saving them to the database.
3. Protect the `/admin` route so only users with the ‘admin’ role can access it.
4. Add middleware to check for a valid JWT token in headers.
5. Store the access token in a secure HTTP-only cookie.
6. Build a `signup` endpoint that validates email format and password length.
7. Refresh the token when the user visits the app after 24 hours.
8. Include a `reset password` token with an expiration time.
9. Return appropriate HTTP status codes for auth failures.
10. Separate the authentication logic into a service file.

---

## 3. Data Modeling & Validation

**Prompt Examples:**
1. Create a Mongoose schema for a `Project` with name, description, and status.
2. Add a required `email` field to the `User` model and validate its format.
3. Use Sequelize to define a `Product` model with price, name, and category.
4. Add a default value for the `createdAt` field.
5. Mark the `username` field as unique.
6. Use Joi to validate incoming request bodies.
7. Make sure no empty strings are allowed in required fields.
8. Add a virtual field for the user’s full name.
9. Set up a foreign key relationship between `Order` and `User`.
10. Document this schema using comments or OpenAPI.

---

## 4. Error Handling & Logging

**Prompt Examples:**
1. Wrap this function in a try/catch block and return an error message.
2. Send 500 status codes for unexpected server errors.
3. Log request details using Morgan middleware.
4. Add centralized error handling middleware to Express.
5. Log errors to the console in development and to a file in production.
6. Return a JSON error response with a message and status code.
7. Use custom error classes for 404 and validation errors.
8. Log the time and route of any error that occurs.
9. Include stack traces in development mode only.
10. Ensure users never see raw error objects in the response.

---

## 5. Database Interaction

**Prompt Examples:**
1. Connect to a PostgreSQL database using Knex.
2. Write a query to fetch all tasks assigned to a specific user.
3. Update the `isActive` field to `false` for all inactive users.
4. Add an index to the `email` column for performance.
5. Run a database migration to add a `lastLogin` timestamp field.
6. Use a transaction to create an order and update inventory atomically.
7. Add seed data for testing: 5 users, 3 products.
8. Retrieve the latest 10 blog posts sorted by `createdAt` descending.
9. Use parameterized queries to avoid SQL injection.
10. Set up an environment variable for the database URL.

---

## Quick Reference: Useful Keywords & Terms

| Goal                | Useful Terms to Include                           |
|---------------------|---------------------------------------------------|
| APIs & Endpoints    | GET, POST, PUT, DELETE, REST, route, middleware   |
| Auth & Security     | JWT, bcrypt, login, protected route, middleware   |
| Database            | schema, model, foreign key, query, transaction    |
| Error Handling      | try/catch, status code, error message, logger     |
| Validation          | required, unique, regex, Joi, express-validator   |

---

## Tools That Help

- **Express.js** – backend framework for Node.js
- **Mongoose** – ODM for MongoDB
- **Sequelize** – ORM for SQL databases
- **Joi** – schema validation for request bodies
- **JWT** – secure JSON Web Tokens for auth
- **bcrypt** – password hashing
- **Morgan** – request logging middleware
- **Dotenv** – load environment variables from `.env` files

---

This cheat sheet helps you collaborate with AI on backend tasks—even if you’re focused on product management, testing, or frontend.
