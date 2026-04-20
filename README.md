# P1
# 🌱 AgroSmart+ – Smart Agriculture Platform (MERN Stack)

## 📌 Overview

**AgroSmart+** is a full-stack web application designed to modernize agriculture by connecting farmers directly with consumers while providing intelligent advisory tools. The platform eliminates middlemen, improves transparency, and helps farmers make data-driven decisions using weather insights and AI-based suggestions.

---

## 🚀 Features

### 🔐 Authentication & Security

* User registration and login (JWT-based authentication)
* Role-Based Access Control (Admin, Farmer, Consumer)
* Secure password hashing using bcrypt

---

### 👨‍🌾 Farmer Module

* Add, edit, and delete crop/product listings
* Upload product images
* Manage orders
* Basic crop advisory system (AI-inspired suggestions)

---

### 🛒 Consumer Module

* Browse and search products
* Filter by category and price
* Add to cart and place orders
* Order tracking and history

---

### 🛠️ Admin Module

* Manage users and products
* Approve/reject product listings
* View analytics dashboard (users, products, orders)

---

### 🌦️ Weather Module

* Real-time weather data using API
* Displays temperature, humidity, and rain probability
* Provides farming-related suggestions

---

### 🤖 AI Advisory (Basic)

* Farmers can input crop issues
* System provides suggestions (rule-based or API-based)

---

### 🌐 Multi-Language Support

* Supports English and Hindi
* Improves accessibility for rural users

---

## 🏗️ Tech Stack

### Frontend

* React.js
* HTML, CSS, JavaScript
* Chart.js (for analytics)

### Backend

* Node.js
* Express.js

### Database

* MongoDB (Atlas)

### Other Tools

* Multer (image upload)
* JWT (authentication)
* bcrypt (password security)
* OpenWeather API

---

## 📂 Project Structure

```id="j2u7n3"
pro1/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── config/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash id="4smz2m"
git clone https://github.com/your-username/agrosmart-plus.git
cd pro1
```

---

### 2. Setup Backend

```bash id="0rqg0d"
cd backend
npm install
```

Create a `.env` file in backend:

```env id="x6b3jl"
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
OPENWEATHER_API_KEY=your_api_key
```

Run backend:

```bash id="2cc4d2"
npm run dev
```

---

### 3. Setup Frontend

```bash id="r0v0kl"
cd ../frontend
npm install
npm run dev
```

---

## 📊 Future Enhancements

* AI-based crop disease detection (image processing)
* Chat system between farmers and buyers
* Payment gateway integration
* Mobile app version
* Advanced analytics using ML

---

## 🎯 Project Goal

To create a scalable and user-friendly platform that:

* Bridges the gap between farmers and consumers
* Promotes sustainable agriculture
* Uses technology to improve productivity and profitability

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork this repository and submit pull requests.

---

## 📜 License

This project is for educational purposes.
