# Node.js Authentication Boilerplate

This is a simple and clean Node.js authentication boilerplate. It includes user authentication (register, login), JWT token generation, password hashing, and secure environment handling using `dotenv`. The app is structured in a professional and modular way with clear separation of concerns for scalability and maintainability.

## Features

- **User Registration**: Users can register with an email and password.
- **User Login**: Authenticates users using JWT (JSON Web Token).
- **JWT Token**: Secured token-based authentication to protect routes.
- **Password Hashing**: Secure password storage using `bcryptjs`.
- **Environment Variables**: Sensitive information like MongoDB URI and JWT secret are stored in environment variables.
- **Modular Structure**: The project is divided into different modules (e.g., authentication, routes, models) to keep the codebase clean and scalable.
- **Error Handling**: Centralized error handling for better debugging and user feedback.
- **Security Practices**: Use of environment variables, password hashing, and token authentication to ensure a secure application.

## Project Structure
.
├── app.js                   # Main server file
├── config
│   └── db.js                # Database connection
├── controllers
│   └── authController.js     # Controller for authentication logic
├── models
│   └── User.js              # User model (MongoDB schema)
├── routes
│   └── authRoutes.js        # Routes for authentication (register/login)
├── middleware
│   └── authMiddleware.js    # JWT token verification middleware
├── .env.example             # Example environment variables file
├── .gitignore               # Files and directories to be ignored in version control
├── package.json             # Project dependencies and scripts
├── README.md                # Project documentation
└── package-lock.json        # Package lock file (excluded in gitignore)
