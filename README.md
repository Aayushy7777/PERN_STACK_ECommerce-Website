Here is a **clean, professional, and GitHub-ready README.md** for your project **PERNS_STACK_ECommerce-Website**, formatted properly and rewritten in your style.
You can copy–paste directly into your repository.

---

# 🛒 **PERN_STACK_ECommerce-Website**

A full-stack **E-Commerce** application built with the **PERN Stack** (PostgreSQL, Express.js, React.js, Node.js).
This project includes:

* 🔹 Product catalog
* 🔹 User authentication
* 🔹 Shopping cart
* 🔹 Order processing
* 🔹 Admin inventory tools
* 🔹 Fully functional API + frontend integration

---

## 🚀 **Start Development**

### **1️⃣ Fork & Clone the Repository**

```
git clone <your_repo_link>
cd PERN_STACK_ECommerce-Website
```

---

## 🛠️ **Installation**

## 📌 Frontend Installation

Navigate to the `frontend` folder:

```
cd frontend
npm install
```

## 📌 Backend Installation

Navigate to the `backend` folder:

```
cd backend
npm install
```

---

## ⚙️ **Backend Setup**

Create a **.env** file inside the **backend** folder and add:

```env
PORT=?
DB_PORT=?
DB_USER=?
DB_HOST=?
DB_DATABASE=?
DB_PASSWORD=?

# Set timezone (1 for GMT+1, -1 for GMT-1)
TIME_ZONE=?

# Skip React preflight warnings
SKIP_PREFLIGHT_CHECK=true 

# Allowed frontend origin
FRONT_END_URL=http://localhost:3000
```

---

## ▶️ **Starting the Project**

---

## 🖥️ **Start Frontend**

Inside the frontend folder:

```
npm start
```

Frontend runs at:

👉 `http://localhost:3000`

### **To use local backend instead of FakeStore API**

Open `.env` inside the **frontend** folder and update:

```env
REACT_APP_PRODUCT_URL=http://localhost:5000/products
REACT_APP_BACKEND_URL=http://localhost:5000
```

---

## 🛢️ **Start Backend**

Inside the backend folder:

### ✔️ (Optional but recommended) Run Tests

```
npm run test
```

This creates required tables and checks DB connection.

### ▶️ Start Backend Server

```
npm start
```

Backend runs at:

👉 `http://localhost:5000`

---

## 👨‍💻 **Tech Stack**

| Layer       | Technology          |
| ----------- | ------------------- |
| Frontend    | React.js            |
| Backend     | Node.js, Express.js |
| Database    | PostgreSQL          |
| Testing     | Jest / Supertest    |
| Environment | Dotenv              |

---

## ✨ **Features**

* 🔐 User Signup & Login (JWT-based)
* 🛍️ Product listing & details
* 🛒 Add to cart
* 💳 Checkout flow
* 📦 Order processing
* 🛠️ Admin features (inventory & product management)
* ⚡ REST API with PostgreSQL integration

---

## 🎩 **Author**

**Aayush Yadav**


---

## ⭐ **Support**

If you find this useful, don’t forget to **star ⭐ the repository**.
Thanks for checking out the project! 😄

---

If you want, I can also create:

✅ GitHub badges
✅ Folder structure section
✅ Preview screenshots section
✅ API documentation table
✅ Contribution guide

Just tell me!

