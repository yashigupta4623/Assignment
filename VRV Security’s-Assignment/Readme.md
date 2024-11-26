# Authentication and Authorization System

## **Overview**
This is a basic implementation of an **Authentication and Authorization System**. It allows users to securely register, log in, and log out, while ensuring role-based access control (RBAC) to restrict access to specific resources based on user roles.

---

## **Features**
- **User Registration**: Create an account with a unique username and password.
- **Login**: Authenticate users securely.
- **Logout**: Safely terminate user sessions.
- **Role-Based Access Control**:
  - Roles such as Admin, Moderator, and User.
  - Each role has specific permissions to access certain resources.
- **Secure Authentication**: Uses **JWT (JSON Web Tokens)** for managing sessions.

---

## **Core Requirements**
- **Registration**: Collect and store user credentials securely.
- **Authentication**: Verify user credentials during login.
- **Authorization**: Restrict access to resources based on roles.
- **Security**: 
  - Passwords are hashed for storage.
  - Tokens are used for session management.

---

## **Technologies**
- **Programming Language**: JavaScript (backend basics)
- **Database**: SQLite or JSON file storage for simplicity
- **Authentication**: JWT for session management

---

