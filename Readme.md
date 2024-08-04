# Library Management System

## Overview
This project is a comprehensive library management system built with Flask and SQLAlchemy. It provides functionalities for managing books and users, including administrative operations like adding, updating, and removing books and users.

## Getting Started

### Prerequisites
- Ensure you have Python installed (preferably Python 3.7+).
- Install the required Python packages using:
  ```bash
  pip install -r requirements.txt

Setup

Initialize the Database:
Navigate to the project directory.
Run the following command to create the database and tables:
    
    python app.py
After running the program, use a tool like Thunder or Postman to manually add an admin user via the registerAdmin endpoint.

Admin Setup:

Log in with the admin credentials you created.
You can now add books, manage users, and perform other administrative tasks.

    HTML Pages:
        Login Page
        Registration Page
    Books Management (Admin Only):
        View Books
        Loan Books
        Remove Books
    Clients Management (Admin Only):
        View Clients
        Remove Clients
    User's Books Management:
        View User's Borrowed Books
        Return Books

API Endpoints

    Authentication:
        POST /login - Authenticate user.
        POST /register - Register a new user.
        POST /registerAdmin - Register an admin user.
    Books Management:
        POST /books - Create a new book.
        DELETE /books/<id> - Delete a book.
        PUT /books/<id> - Update book details.
        GET /books - Show all books.
        GET /books/<id> - Show details of a specific book.
    Users Management:
        GET /users - Show all users.
        PUT /users/<id> - Update user details.
        DELETE /users/<id> - Delete a user.
    Loan Management:
        POST /books/loan - Loan a book to a user.
        POST /books/return - Return a book.

Notes
Make sure you are in the correct directory when running the application.
The registerAdmin endpoint is essential for initial setup to enable administrative functionalities.
   
