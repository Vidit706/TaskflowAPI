# TaskFlow API

A backend REST API for a task management application built with **Node.js, Express.js, and MongoDB**. The project provides APIs for user authentication, authorization, task management, validation, and email functionality.

## 🚀 Features

* User registration and login
* JWT-based authentication
* Authorization and protected routes
* Password hashing using bcrypt
* Task creation, retrieval, updating, and deletion
* MongoDB database integration using Mongoose
* Request validation using Express Validator
* Cookie-based authentication handling
* Email functionality using Nodemailer
* CORS configuration
* Environment variable configuration using dotenv
* API testing and debugging with Postman

## 🛠️ Tech Stack

* **Node.js**
* **Express.js**
* **MongoDB**
* **Mongoose**
* **JWT (JSON Web Token)**
* **bcrypt**
* **Express Validator**
* **Nodemailer**
* **Mailgen**
* **Cookie Parser**
* **CORS**
* **dotenv**
* **Postman**

## 📁 Project Structure

```text
TaskflowAPI/
│
├── public/
│   └── images/
│
├── src/
│   ├── controllers/
│   ├── db/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── index.js
│
├── .env
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Vidit706/TaskflowAPI.git
```

### 2. Navigate to the project

```bash
cd TaskflowAPI
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file in the root directory and add the required environment variables.

Example:

```env
PORT=8000
MONGODB_URI=your_mongodb_connection_string

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

ACCESS_TOKEN_EXPIRY=your_access_token_expiry
REFRESH_TOKEN_EXPIRY=your_refresh_token_expiry

EMAIL_USER=your_email
EMAIL_PASSWORD=your_email_password
```

> Do not upload your `.env` file or expose secret keys on GitHub.

## ▶️ Run the Project

### Development mode

```bash
npm run dev
```

### Production mode

```bash
npm start
```

The API will run on the configured port.

## 🔐 Authentication

TaskFlow API uses **JWT-based authentication** to protect authorized resources.

The authentication flow includes:

1. User registration
2. Password hashing using bcrypt
3. User login
4. JWT token generation
5. Authentication through protected routes
6. Authorization of authenticated users

## 📌 API Functionality

The API is designed around REST principles and provides functionality for:

### User APIs

* Register a new user
* Login user
* Authenticate user
* Access protected resources
* Manage authenticated user data

### Task APIs

* Create a task
* Get tasks
* Get a specific task
* Update a task
* Delete a task

## 🧪 API Testing

The APIs can be tested using **Postman**.

Recommended testing flow:

```text
Register User
      ↓
Login
      ↓
Receive Authentication Token
      ↓
Access Protected Routes
      ↓
Create / Read / Update / Delete Tasks
```

## 📚 What I Learned

Through this project, I gained practical experience in:

* Building RESTful APIs with Express.js
* Working with MongoDB and Mongoose
* Implementing JWT authentication
* Password hashing and security practices
* Creating middleware and protected routes
* API validation and error handling
* Testing APIs using Postman
* Managing environment variables
* Structuring a Node.js backend project

## 👨‍💻 Author

**Vidit Mishra**

GitHub: [Vidit706](https://github.com/Vidit706)

## 📄 License

This project is licensed under the ISC License.
