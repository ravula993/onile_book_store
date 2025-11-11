
# 📚 Online Book Store — Full Stack Web Application

### 🚀 Live Demo  
👉 [Visit Live Website](https://readstream-nexus.lovable.app) <!-- Replace with your deployed link once available -->

---

## 🧩 Overview
The **Online Book Store** is a full-stack e-commerce web application that allows users to browse, search, and purchase books online.  
It includes secure authentication, shopping cart functionality, payment gateway integration, and an admin dashboard for managing books and orders.

This project demonstrates complete end-to-end development using **React, Node.js, Express, MongoDB**, and **Stripe** (or Razorpay) for payments.

---

## 🏗️ Tech Stack

### **Frontend**
- React.js (or Next.js)
- Tailwind CSS
- Framer Motion (for animations)
- Axios (for API calls)
- React Router DOM (for routing)

### **Backend**
- Node.js + Express.js
- MongoDB (Mongoose ODM)
- JWT Authentication
- Stripe / Razorpay Integration
- Bcrypt for password hashing

### **Tools & Hosting**
- GitHub (Version Control)
- Vercel / Netlify (Frontend Deployment)
- Render / Railway / AWS EC2 (Backend Deployment)
- MongoDB Atlas (Database)
- SendGrid / Nodemailer (Email notifications)

---

## ✨ Features

### 👤 User Features
- Signup, Login, Logout (JWT-based authentication)
- Browse and search books by category, title, or author
- View detailed book information
- Add to cart, update quantities, remove items
- Checkout with payment integration
- View past orders and invoices
- Wishlist management

### 🛒 Shopping Cart & Checkout
- Persistent cart (stored for logged-in users)
- Discount / Promo code support
- Secure payment using Stripe or Razorpay
- Email confirmation after purchase

### 🧑‍💻 Admin Features
- Admin login panel
- Add, edit, delete books
- Manage orders and user data
- View sales analytics and reports
- Upload book images via dashboard

---

## 📁 Folder Structure

```bash
Online-Book-Store/
├── client/                  # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── utils/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── server/                  # Backend API
│   ├── config/              # DB and environment setup
│   ├── controllers/         # Business logic
│   ├── models/              # Mongoose schemas
│   ├── routes/              # API endpoints
│   ├── middlewares/
│   ├── server.js
│   └── package.json
│
├── .env                     # Environment variables
├── README.md
└── package.json
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/online-book-store.git
cd online-book-store
```

### 2️⃣ Install Dependencies
**Frontend:**
```bash
cd client
npm install
```
**Backend:**
```bash
cd ../server
npm install
```

### 3️⃣ Create Environment Variables
Create `.env` files in both `/client` and `/server` directories.

**Backend `.env`:**
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
```

**Frontend `.env`:**
```
REACT_APP_API_URL=http://localhost:5000/api
```

### 4️⃣ Run Development Servers
**Backend:**
```bash
cd server
npm run dev
```
**Frontend:**
```bash
cd client
npm start
```

Local:   http://localhost:8080/
Network: http://10.2.8.99:8080/

---

## 🧪 Testing

- Jest / Mocha for backend testing  
- Cypress or Playwright for end-to-end testing  
- Postman for API testing

---

## 🚀 Deployment

- **Frontend:** Deploy on Vercel / Netlify  
- **Backend:** Deploy on Render / Railway / AWS  
- **Database:** MongoDB Atlas  

### Example:
```bash
vercel --prod
```

---

## 🧠 Future Enhancements
- Personalized book recommendations using AI/ML
- User reviews & ratings
- Advanced search filters (price, language, format)
- Dark mode UI
- Mobile app version (React Native)
---

## ⭐ Support
If you like this project, don’t forget to **⭐ star the repo** and share it with your friends!
