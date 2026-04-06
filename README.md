# 🛒 GreenCart  

## 📌 Overview  

**GreenCart** is a full-stack **grocery delivery web application** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.  

It provides a seamless shopping experience for customers along with a **dedicated seller dashboard** for managing products, inventory, and orders.  

The project follows the **MVC architecture** for a clean, scalable, and maintainable code structure.  

---

## 🌐 Live Demo  

- 👤 **User App** → [Visit GreenCart](https://green-cart-jade.vercel.app/)  
- 🏪 **Seller Dashboard** → [Visit Seller Panel](https://green-cart-jade.vercel.app/seller)  

---

## ✨ Features  

### 👤 User Module  

- 🔐 **User Authentication** — Secure registration and login  
- 🛍️ **Category-Wise Browsing** — Browse groceries by category  
- 🔎 **Search Functionality** — Search products by name or category  
- 📦 **Product Details** — View detailed product information  
- 🛒 **Cart System** — Add, remove, and manage cart items  
- 🏠 **Delivery Address** — Add/update address during checkout  
- 💳 **Payment Options** — Cash on Delivery (COD) & Stripe (Online)  
- ✅ **Order Placement** — Smooth checkout and confirmation  

---

### 🏪 Seller Module  

- 🔐 **Seller Authentication** — Separate login/signup  
- 📊 **Seller Dashboard** with:  
  - ➕ Add Product  
  - 📋 Product List  
  - 📦 Orders Management  
- 🔁 **Stock Control** — Toggle In Stock / Out of Stock  
- ⚡ **Real-Time Management** — Manage inventory and orders efficiently  

---

## 🛠️ Tech Stack  

- **MongoDB** — Database  
- **Express.js** — Backend framework  
- **React.js** — Frontend library  
- **Node.js** — Runtime environment  
- **Tailwind CSS** — UI styling  
- **JWT** — Authentication  
- **Stripe** — Payment gateway  
- **Vercel** — Deployment  
- **MVC Architecture** — Structured code design  

---

## 📂 Project Structure  

```
GreenCart
│
├── backend/
├── frontend/      # User application
├── seller/        # Seller dashboard
├── .gitignore
└── README.md
```

---

## ▶️ Run Locally  

### Backend  

```bash
cd backend
npm install
npm start
```

### Frontend (User)  

```bash
cd frontend
npm install
npm run dev
```

### Seller Dashboard  

```bash
cd seller
npm install
npm run dev
```

---

## 🔑 Environment Variables  

### Backend (.env)

```
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key

STRIPE_SECRET_KEY=your_stripe_secret_key

FRONTEND_URL=your_user_app_url
SELLER_URL=your_seller_dashboard_url
```

---

### Frontend (.env)

```
VITE_BACKEND_URL=your_backend_api_url
```

---

### Seller (.env)

```
VITE_BACKEND_URL=your_backend_api_url
```

---

## 🚧 Future Improvements  

- Order tracking system  
- Admin panel  
- Advanced filters and recommendations  
- Notifications (email/SMS)  
- Performance optimization  

---

## 👨‍💻 Author  

Rohit Kuwar  

---

## ⭐ Note  

This project demonstrates a real-world **e-commerce grocery platform** with both **user and seller modules**, including authentication, payment integration, and full CRUD operations using the MERN stack.
