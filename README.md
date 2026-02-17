# 🍽️ OrderOnTheGo – MERN Stack Food Ordering Platform

**OrderOnTheGo** is a full-stack food ordering application built using the **MERN** stack. It enables users to browse restaurants, add items to cart, and place orders. Restaurants can manage their menu and orders via a dedicated dashboard, while admins can promote restaurants and monitor platform activity.

---

## 🚀 Features

### 👤 User
- Register/Login
- Browse restaurants and products
- Add to cart and place orders
- View past orders and cancel live ones

### 🍴 Restaurant
- Login/Register
- Dashboard to manage products
- View and fulfill customer orders

### 🛡️ Admin
- Login
- View users and restaurants stats
- Promote restaurants to homepage

---

## 🛠️ Tech Stack

| Layer        | Technology             |
|--------------|------------------------|
| Frontend     | React.js (Context API) |
| Backend      | Node.js + Express.js   |
| Database     | MongoDB                |
| Auth         | bcrypt + Context API   |
| Styling      | CSS Modules / Plain CSS|

---

## 📁 Folder Structure

```bash
OrderOnTheGo/
│
├── client/          # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── styles/
│   │   └── App.js
│
├── server/          # Node + Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── index.js
````

---

## ⚙️ Setup Instructions

### 📦 Prerequisites

* Node.js (v14 or above)
* MongoDB (local or Atlas)

### 🧩 Installation

```bash
# 1. Clone the repo
git clone https://github.com/srinu0906/OrderOnTheGo-mern-stack-internship-project.git

# 2. Install dependencies
cd client
npm install

cd ../server
npm install
```


### ▶️ Running the App

```bash
# Start frontend
cd client
npm run dev

# Start backend
cd ../server
npm start
```

---

## 🔌 API Overview

### 🧑 User Routes

* `POST /api/users/signup`
* `POST /api/users/login`
* `POST /api/cart`
* `POST /api/orders`

### 🍴 Restaurant Routes

* `POST /api/restaurants/login`
* `POST /api/restaurants/:id/products`
* `GET /api/restaurants/:id/products`
* `GET /api/restaurants/:id/orders`

### 🛠 Admin Routes

* `GET /api/restaurants/all`
* `POST /api/admin/promote/:id`

---

## 🔐 Authentication

* Passwords hashed with **bcrypt**
* **React Context API** used for login state

---

## 🧪 Testing

* Manual testing using frontend UI
* Backend tested using Thunder Client
* User acceptance testing covered all flows (UAT report available in `/documentation`)

---

## 🖼 Demo

> 📸 [Link to Demo Video](https://drive.google.com/file/d/1iXTpXvCYmCfNxp_BeDDFqVF3GosNmMtB/view?usp=sharing)

---

## 🐞 Known Issues

* No payment gateway (dummy flow)
* No delivery partner module yet
* No mobile app (React Native support planned)

---

## 🌱 Future Enhancements

* Integrate Razorpay/Stripe for real payments
* Add delivery partner tracking
* Push notifications
* Mobile app via React Native

---

## 📎 Documentation

All project documents (ideation, design, testing, planning) are available in the `documentation/` folder.

---

## 🧑‍💻 Contributors

* Srinu – Backend, Rotes & API Integration
* Saranya – Frontend, UI Design and Implementation
* Rishitha – Frontend, Authentication and Frontend logic
* Roja – Backend, Schemas & Controllers

---

## 📂 License

This project was developed as part of the **SmartBridge Full Stack Developer MERN Stack Internship Program**.

The source code is shared for learning and demonstration purposes. You may use or extend the code for educational or non-commercial use with proper attribution.

For any reuse or distribution, please include a link to this repository and credit the original contributors.

License: **Educational / Non-commercial Use Only**

