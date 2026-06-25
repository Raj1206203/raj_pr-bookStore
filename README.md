# 📚 Book Store Management System

A RESTful backend application built with **Node.js**, **Express.js**, **MongoDB**, and **Mongoose** that provides complete book and user management functionality using the **MVC (Model-View-Controller)** architecture.

---

## 📖 Project Overview

The **Book Store Management System** is a backend API designed to efficiently manage books and users while following industry-standard development practices. It provides secure and scalable REST APIs for performing CRUD operations on books along with user registration and authentication features.

The project emphasizes clean code architecture, middleware implementation, request validation, error handling, and efficient database management. It was developed as a learning-oriented project to strengthen backend development skills and serves as a portfolio-ready application demonstrating real-world API development.

---

## 🚀 Features

### 👤 User Management

* User Registration
* User Login
* Email-Based User Verification
* Duplicate User Prevention
* Request Validation Middleware

### 📚 Book Management

* Add New Books
* View All Books
* Search Books by Title
* Get Single Book Details
* Update Book Information
* Delete Books

### 🛡️ Middleware & Validation

* Custom Validation Middleware
* User Input Validation
* Book Data Validation
* Global Error Handling Middleware
* Express Request Processing Middleware

### 🗄️ Database Management

* MongoDB Integration
* Mongoose Schema Validation
* Data Modeling with Mongoose
* Complete CRUD Operations
* Optimized Database Queries

---

## 🏗️ Project Architecture

This project follows the **MVC (Model-View-Controller)** architecture to keep the code organized, scalable, and maintainable.

```
Book-Store-Management-System/
│
├── controllers/
├── models/
├── routes/
├── middleware/
├── config/
├── services/
├── validators/
├── utils/
├── app.js
├── server.js
└── package.json
```

### MVC Structure

* **Models** – Define MongoDB schemas and interact with the database.
* **Controllers** – Handle business logic and process client requests.
* **Routes** – Define REST API endpoints.
* **Middleware** – Validate requests, handle errors, and manage request flow.
* **Database** – MongoDB stores application data using Mongoose ODM.

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose
* JavaScript (ES6+)
* Dotenv
* Nodemon
* Postman

---

## 📌 REST API Features

### Authentication APIs

* Register User
* Login User
* Email Verification

### Book APIs

* Create Book
* Get All Books
* Search Books
* Get Book by ID
* Update Book
* Delete Book

---

## 🎯 Learning Outcomes

This project demonstrates practical implementation of:

* REST API Development
* Express.js Routing
* MongoDB Integration
* Mongoose Schema Design
* CRUD Operations
* MVC Architecture
* Middleware Development
* Request Validation
* Error Handling
* Backend Project Structure
* API Testing using Postman

---

## 📦 Installation

### Clone the Repository

```bash
git clone <repository-url>
```

### Navigate to the Project

```bash
cd Book-Store-Management-System
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file in the root directory and add:

```env
PORT=5000
MONGODB_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Start Development Server

```bash
npm run dev
```

The server will start on:

```text
http://localhost:5000
```

---

## 🧪 API Testing

You can test all API endpoints using:

* Postman
* Thunder Client
* Insomnia

---

## 🔮 Future Enhancements

* Password Hashing using bcrypt
* JWT Authentication & Authorization
* Role-Based Access Control
* Shopping Cart System
* Order Management
* Book Categories & Genres
* Pagination & Filtering
* Reviews & Ratings
* Image Upload Support
* Payment Gateway Integration

---

## 📹 Project Demonstration

Watch the complete project walkthrough and API demonstration in the video linked below.

---

## 🤝 Contributing

Contributions are welcome!

If you would like to improve this project:

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 👨‍💻 Developer

**Raj D Patel**

**BCA Graduate | Aspiring Full Stack Developer**

Passionate about building scalable web applications using modern backend technologies. This project reflects practical knowledge of RESTful API development, database management, middleware implementation, software architecture, and clean coding practices.

---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub. It helps support the project and motivates future improvements.

---

## 📄 License

This project is developed for **educational and portfolio purposes**.

## Project Demo 

https://drive.google.com/file/d/1zsEz_dE8fQXWhrKoyDiz-h9vscpuc64N/view?usp=drive_link
