#project1  Employee Management System

## Overview
This is a full-stack web application designed to manage employee records efficiently. Administrators can perform CRUD operations (Create, Read, Update, Delete) on employee data while ensuring secure authentication and validation mechanisms.

### Features
- User authentication and registration (JWT-based).
- Add, update, view, and delete employee records.
- Secure API endpoints with authentication middleware.
- Backend: Node.js, Express.js, MongoDB.
- Frontend: React.js for user interface.

## Key Activities
1. **Authentication**: Secure login and registration using bcrypt for password hashing and JWT for session management.
2. **CRUD Operations**:
   - Add new employees with name, position, department, and email.
   - Update employee details.
   - View a list of all employees.
   - Delete employee records.
3. **Frontend**:
   - Dynamic interface for interacting with employee data.
   - Real-time updates using RESTful API calls.<br>


   - #Project 2
   - Overview
The Secure User Authentication project provides a Flask-based web application with secure user registration, login, and role-based access control using JWT (JSON Web Tokens) and bcrypt for password hashing. It enables users to securely sign up, log in, and access protected routes.

Objectives<br>
Secure Authentication: <br>Implement hashed password storage and JWT-based login.
JWT Authentication: Manage user sessions securely with JWT tokens.
Role-based Access: Use roles (admin/user) to restrict access to sensitive routes.
Protected Routes: Ensure only authenticated users can access protected resources.<br>
Key Activities<br>
Set Up Flask Project: Install dependencies like Flask, SQLAlchemy, bcrypt, and JWT.<br>
Database Model: <br>Create a User model with email, password, and role.
User Registration and Login: Implement routes for secure sign-up and login, using bcrypt for password hashing and JWT for authentication.<br>
Protected Routes: <br>Add routes that require JWT authentication to access.<br>
Role-based Access Control: <br>Restrict admin-only routes using role-based access.<br>
Testing and Documentation:<br> Ensure proper functionality 



