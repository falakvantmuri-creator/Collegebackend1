# College Management API



<img width="1906" height="827" alt="Screenshot 2026-07-08 155618" src="https://github.com/user-attachments/assets/4f24eef0-4677-4f06-959e-ddd31400423f" />
<img width="1897" height="957" alt="Screenshot 2026-07-08 155528" src="https://github.com/user-attachments/assets/cc1f34cb-dee7-4777-8ed6-6929301d517c" />
<img width="1906" height="1073" alt="Screenshot 2026-07-08 154616" src="https://github.com/user-attachments/assets/15ff8677-5920-4fad-bb93-45778ad95144" />


//github.com/user-attachments/assets/5d86725d-2f0d-4791-8475-c692a3c2f7b0" />



A robust RESTful API built with **Node.js**, **Express**, and **Mongoose** for managing a college database system. This project includes secure user authentication using **JWT (JSON Web Tokens)** and full **CRUD (Create, Read, Update, Delete)** operations for managing student records.

---

## 🚀 Features

* **User Authentication**: Secure user registration and login endpoints utilizing `bcryptjs` for password hashing and `jsonwebtoken` for stateless authentication.
* **Student Management**: Complete CRUD operations for handling student profiles.
* **Database Integration**: Structured data management using MongoDB and Mongoose schemas (User, Course, Teacher, Student).
* **Environment Configuration**: Protected environment variables handled via `dotenv`.

---

## 🛠️ Tech Stack

* **Backend**: Node.js, Express.js
* **Database**: MongoDB, Mongoose ODM
* **Security**: bcryptjs, JSON Web Tokens (JWT)
* **Configuration**: dotenv

---

## 📋 Prerequisites

Before running this project, ensure you have the following installed:
* [Node.js](https://nodejs.org/) (v14+ recommended)
* [MongoDB](https://www.mongodb.com/) (Running locally on `mongodb://127.0.0.1:27017`)

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash

git clone <repository-url>
cd <project-directory>

Install Dependencies 
npm install

Put environment variable by creating .env file
JWT_SECRET=your_super_secret_jwt_key_here


##Owner - falak

