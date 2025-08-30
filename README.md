# 🛒 MERN E-Commerce 2024

A full-stack **E-Commerce Web Application** built using the **MERN stack** (MongoDB, Express.js, React, Node.js) with modern tooling (Vite, Tailwind CSS).  
This project provides a complete shopping experience including authentication, product browsing, cart management, and order handling.

---

## 🚀 Features
- User authentication (Register/Login with JWT)
- Browse products with search and filter
- Add/remove products to shopping cart
- Checkout & order management
- Responsive UI with Tailwind CSS
- RESTful API with Express.js
- MongoDB for database storage

---

## 🛠️ Tech Stack
**Frontend (client):**
- React (with Vite)
- Tailwind CSS
- React Router
- Context API / State Management

**Backend (server):**
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT Authentication
- REST APIs

---

 📂 Project Structure
mern-ecommerce-2024-master/
│── client/ # React frontend
│ ├── src/ # Components & pages
│ ├── public/ # Static assets
│ └── package.json
│
│── server/ # Backend (Express + MongoDB)
│ ├── models/ # Mongoose models
│ ├── routes/ # API routes
│ ├── controllers/ # Route logic
│ └── server.js
│

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/mern-ecommerce-2024.git
cd mern-ecommerce-2024-master
2️⃣ Install Dependencies
Frontend
bash
Copy code
cd client
npm install
Backend
bash
Copy code
cd server
npm install
3️⃣ Setup Environment Variables
Create a .env file inside server/ with:

ini
Copy code
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
4️⃣ Run Application
Start backend:
bash
Copy code
cd server
npm start
Start frontend:
bash
Copy code
cd client
npm run dev
👉 Open http://localhost:5173/ in your browser.

## 📂 Project Structure

📡 API Endpoints
Authentication

POST /api/auth/register → Register new user

POST /api/auth/login → Login & get token

Products

GET /api/products → Fetch all products

GET /api/products/:id → Fetch single product

POST /api/products → Add product (Admin only)

PUT /api/products/:id → Update product (Admin only)

DELETE /api/products/:id → Delete product (Admin only)

Orders

POST /api/orders → Place order

GET /api/orders/:userId → Get user orders

GET /api/orders → Get all orders (Admin only)
