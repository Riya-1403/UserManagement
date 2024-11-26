![image](https://github.com/user-attachments/assets/f9eb4488-c35d-4056-ac1a-1f0e74ef18c1)
![image](https://github.com/user-attachments/assets/553b3a39-f578-4824-bbd5-2b14ceb01fa4)
![image](https://github.com/user-attachments/assets/e7b03739-4f1c-44fc-860d-88be98dec658)

User Management System with Role-Based Access Control (RBAC)

This project implements a User Management System using Spring Boot for the backend and React.js for the frontend. The system includes Authentication, Authorization, and Role-Based Access Control (RBAC) to ensure secure access to resources based on user roles.

Features

Authentication

Secure login: Users can log in using their credentials, and a JWT token is issued upon successful authentication.
Registration: Users can register with a unique username and password.
Password security: Passwords are securely hashed before storage.

Authorization

Role-based authorization: Access to resources is granted based on user roles (e.g., Admin, User).
Protected endpoints: Routes are secured to ensure only authorized roles can access them.
Role-Based Access Control (RBAC)

Admin role:

View all user profiles.
Add new users.
Update existing user details.
Delete users from the system.

User role:

View their own profile and details.
Cannot access admin-specific functionalities.
