<img width="706" height="443" alt="homePage" src="https://github.com/user-attachments/assets/06c86d99-f12e-493f-9381-2b8cdc7fa116" /># 🛍️ ShopLite – Full-Stack E-Commerce Platform

## 📌 Overview

**ShopLite** is a full-stack e-commerce system designed to simulate real-world online shopping platforms. It demonstrates end-to-end web application development including authentication, product management, shopping cart logic, and order processing using a RESTful API architecture.

The system integrates a JavaScript frontend with a Node.js + Express backend and MongoDB database, focusing on scalable architecture, security, and user experience.

---

## 🧠 Core Engineering Goals

- Build a real-world e-commerce workflow (browse → cart → checkout → order tracking)
- Implement secure authentication and authorization using JWT
- Design RESTful APIs for scalable backend communication
- Manage persistent client-side state using localStorage
- Apply modular architecture for maintainability

---

## 🏗️ System Architecture

### Frontend (Client Layer)
- HTML5 / CSS3 (Responsive UI)
- Vanilla JavaScript (modular ES6 architecture)
- localStorage (cart persistence + session handling)

### Backend (Server Layer)
- Node.js + Express.js (REST API)
- MongoDB + Mongoose (data modeling)
- JWT (authentication & route protection)
- bcryptjs (password hashing)

---

## 🚀 Key Features

### 👤 Authentication System
- Secure user registration and login
- Password encryption using bcrypt
- JWT-based session authentication
- Protected API routes

### 🛒 Product & Cart System
- Dynamic product catalog
- Filtering, sorting, and search functionality
- Persistent shopping cart using localStorage
- Quantity management and total calculation

### 📦 Order Management
- Checkout workflow (cart → order creation)
- Order history tracking per user
- Order status management system

### 📱 User Experience
- Fully responsive UI (mobile-first design)
- Toast notifications for system feedback
- Clean navigation across pages

### 🔐 Security Implementation
- Hashed passwords (bcryptjs)
- JWT authentication for protected routes
- Input validation and sanitization
- CORS protection
- Secure API headers (Helmet.js)
- Basic API rate limiting

---

## 📁 Project Structure
ShopLite/
├── frontend/
│ ├── index.html
│ ├── css/
│ ├── js/
│ └── assets/
├── backend/
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── middleware/
│ └── server.js
├── database/
│ └── mongodb/
└── README.md


**Layer Responsibilities:**
- **Frontend** – Handles UI + client-side state
- **Backend** – Handles API + business logic
- **Database** – Handles persistent storage

---

## ⚙️ Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or Atlas)
- npm or yarn

### Backend Setup

bash
# Clone the repository
git clone https://github.com/yourusername/shoplite.git
cd shoplite/backend

# Install dependencies
npm install

# Create .env file
touch .env

Add the following to your .env file:

text
PORT=5000
MONGODB_URI=mongodb://localhost:27017/shoplite
JWT_SECRET=your_secret_key_here
JWT_EXPIRE=7d
bash
# Start the backend server
npm run dev
Frontend Setup
bash
cd ../frontend

# Open index.html in your browser
# Or serve with live server
npx live-server
Running the Full Stack
Start MongoDB: mongod

Start backend: npm run dev (runs on http://localhost:5000)

Open frontend: http://localhost:5500 (or your live server port)

🧪 Testing Credentials
Use the following demo account to test the platform:

Field	Value
Email	test@example.com
Password	password123
You can also register a new account through the signup page.

📌 What This Project Demonstrates
✅ Full-stack JavaScript development

✅ REST API design and integration

✅ Authentication and security implementation

✅ Database modeling with MongoDB

✅ Frontend-backend separation of concerns

✅ Real-world system workflow design

✅ Persistent client-side state management

✅ Responsive UI/UX principles

🔧 Tech Stack Summary
Layer	Technologies
Frontend	HTML5, CSS3, Vanilla JavaScript, localStorage
Backend	Node.js, Express.js, JWT, bcryptjs
Database	MongoDB, Mongoose ODM
Security	Helmet.js, CORS, Rate Limiting, Input Validation
Dev Tools	Nodemon, dotenv, Git

##📸 Screenshots
(Add your screenshots here)

text
screenshots/
├── homepage.png
├── products-page.png
├── cart-page.png
├── checkout-page.png
├── order-history.png
└── mobile-view.png




👨‍💻 Author
Developed as a full-stack portfolio project demonstrating real-world e-commerce architecture and secure API design.

📄 License
This project is for educational and portfolio purposes only.

🚀 From browse to checkout — a complete e-commerce experience.


