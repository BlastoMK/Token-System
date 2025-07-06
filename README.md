# 🚀 Cyber Auth App

![React](https://img.shields.io/badge/Frontend-React-blue?logo=react)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green?logo=node.js)
![Express](https://img.shields.io/badge/API-Express-black?logo=express)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen?logo=mongodb)
![SQLite](https://img.shields.io/badge/Database-SQLite-blue?logo=sqlite)
![Bootstrap](https://img.shields.io/badge/UI-Bootstrap-purple?logo=bootstrap)

---

<p align="center">
  <img src="https://user-images.githubusercontent.com/7680528/236678964-6e2e7e2e-2e2e-4e2e-8e2e-2e2e2e2e2e2e.png" width="120" alt="Cyber Auth Logo"/>
</p>

A modern, full-stack authentication app with secure login, registration, JWT-based sessions, and a beautiful UI. Built for learning, prototyping, or as a foundation for your next project.

---

## ✨ Features

- 🔒 Secure authentication (JWT, bcrypt, rate limiting, account lockout)
- 📝 User registration & login
- 🛡️ Token validation and revocation (logout)
- 👤 User dashboard with token info
- 🎨 Responsive, modern UI (React, Bootstrap, Bootstrap Icons)
- 🌐 RESTful API (Express.js)
- 🗄️ MongoDB/SQLite for user storage

---

## 🛠️ Tech Stack

**Frontend:**
- React 18
- React Router DOM
- React Bootstrap & Bootstrap Icons
- Axios

**Backend:**
- Node.js
- Express.js
- Helmet, CORS, dotenv
- bcryptjs, jsonwebtoken
- express-rate-limit
- MongoDB (via Mongoose) & SQLite3

---

## 📦 Prerequisites

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- (Optional) [MongoDB](https://www.mongodb.com/) if you want to use MongoDB instead of SQLite

---

## ⚡ Installation

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd Cyber
```

### 2. Install backend dependencies
```bash
cd backend
npm install
```

### 3. Install frontend dependencies
```bash
cd ../frontend
npm install
```

### 4. Configure environment variables
- Copy `.env.example` to `.env` in `/backend` and set your `JWT_SECRET` and (optionally) MongoDB URI.

### 5. Start the backend server
```bash
cd ../backend
npm start
```

### 6. Start the frontend app
```bash
cd ../frontend
npm start
```

The frontend runs on [http://localhost:3001](http://localhost:3001) and the backend on [http://localhost:5000](http://localhost:5000).

---

## 🖥️ Usage

- Visit `/signup` to create a new account
- Login at `/login`
- Access your dashboard at `/dashboard` (shows token info, permissions, and logout)

---

## 📁 Project Structure

```
Cyber/
├── backend/         # Express API, auth logic, DB models
│   ├── routes/
│   ├── models/
│   ├── server.js
│   └── ...
├── frontend/        # React app
│   ├── src/
│   ├── public/
│   └── ...
└── README.md
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

This project is licensed under the ISC License.

---

<p align="center">
  <img src="https://img.icons8.com/color/96/000000/lock--v1.png" width="48"/>
  <br/>
  <b>Secure. Modern. Beautiful.</b>
</p>
