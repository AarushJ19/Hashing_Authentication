# Hashing Authentication System using bcrypt and JWT

This project implements a user authentication system using **bcrypt** for password hashing and **JWT (JSON Web Tokens)** for secure user authentication. It also provides basic CRUD operations for managing user data.

## Features
- **User Registration**: Register a new user with a hashed password using bcrypt.
- **User Login**: Authenticate users with a hashed password and return a JWT token upon successful login.
- **JWT-Based Authentication**: Protect routes using JWT, ensuring only authenticated users can access certain routes.
- **CRUD Operations**: Create, Read, Update, and Delete (CRUD) operations for user data, protected by authentication.

## Tech Stack
- **Node.js** with **Express** for server-side functionality.
- **MongoDB** for database storage (could use Mongoose for schema and data modeling).
- **bcrypt** for password hashing.
- **jsonwebtoken (JWT)** for secure authentication.
