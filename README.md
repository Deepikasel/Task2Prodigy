🚀 Prodigy Internship – Task 02: Persistent Storage with Database Integration
💡 Project Overview

As part of my ongoing journey with ProDigy Infotech, I enhanced my previous REST API to support persistent storage using a database. This ensures that all user data is securely stored, retrievable, and managed efficiently, making the API ready for production environments.

✨ Key Implementations

✅ Database Integration: Connected the API to a relational database (MySQL / MongoDB) for real-time data storage.

✅ ORM/ODM Usage: Leveraged Prisma / Mongoose for structured, efficient, and maintainable database operations.

✅ Database Migrations: Created a users table with a clear schema, ensuring consistency across environments.

✅ Environment Configurations: Used .env files to manage environment-specific settings.

✅ Secure Credentials: Stored database credentials safely using environment variables.

✅ Connection Pooling: Implemented connection pooling to improve performance and scalability under load.

🛠 Features & Endpoints
Method	Endpoint	Description
POST	/users	Create a new user in the database
GET	/users	Fetch all users
GET	/users/:id	Fetch user by ID
PUT	/users/:id	Update user details
DELETE	/users/:id	Delete a user
GET	/	Welcome / Health check endpoint
⚡ Technologies & Tools

Node.js & Express.js – Backend server and routing

MySQL / MongoDB – Database for persistent storage

Prisma / Mongoose – ORM/ODM for database operations

dotenv – Environment variable management

Connection Pooling – Efficient DB connections for high performance

🚀 Skills & Learnings

Database integration for backend applications

Managing persistent data using ORM/ODM

Environment-based configurations for security & flexibility

Implementing connection pooling for scalable applications

Best practices for production-ready APIs

👩‍💻 Author

Deepika S. – Prodigy Internship Participant
