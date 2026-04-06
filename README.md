# 📒 Ledger Backend API

## 📌 Overview

Ledger Backend is a RESTful API designed to manage financial transactions, including income and expenses. It allows users to securely track, store, and manage their financial records.

---

## 🚀 Features

* 🔐 User Authentication (Login/Signup)
* ➕ Add Income & Expenses
* 📊 Track Financial Records
* ✏️ Update & Delete Transactions
* 🔎 Fetch Transaction History
* 🛡️ Secure API with JWT Authentication

---

## 🛠️ Tech Stack

**Backend:**

* Node.js
* Express.js

**Database:**

* MongoDB

**Other Tools:**

* JWT Authentication
* REST API

---

## 📡 API Endpoints

### Auth Routes

* POST /api/auth/register
* POST /api/auth/login

### Transaction Routes

* GET /api/transactions
* POST /api/transactions
* PUT /api/transactions/:id
* DELETE /api/transactions/:id

---

## ⚙️ Installation & Setup

1. Clone the repository
   git clonehttps://github.com/rupeshsamarth/backend-ledger.git

2. Navigate to project folder
   cd ledger-backend

3. Install dependencies
   npm install

4. Create a `.env` file and add:
   MONGO_URI=your_mongodb_url
   JWT_SECRET=your_secret_key

5. Run the server
   npm start

---

## 🌐 Live API
Base URL: https://backend-ledger-s6kq.onrender.com

> Note: Server may take 30–40 seconds to start due to free hosting (Render).

## 📚 What I Learned

* Building RESTful APIs using Express.js
* Implementing JWT Authentication
* Database operations with MongoDB
* Backend project structuring

---




