# ShopSphere 🛒

This project is a full-stack E-Commerce web application built with **Spring Boot**, **MySQL**, and **Angular**.  
It supports browsing products, managing a shopping cart, and placing orders dynamically.

---

## ✨ Features

- Product catalog browsing
- Add to Cart / Remove from Cart
- Checkout with form validation
- Dynamic country and state dropdowns
- Order history tracking
- RESTful backend API
- Responsive frontend design

---

## 🛠️ Tech Stack

- **Frontend**: Angular 13+, Bootstrap
- **Backend**: Java 17, Spring Boot 2.7+, Spring Data JPA
- **Database**: MySQL
- **Authentication**: (Basic authentication setup, ready for JWT expansion)

## 🚀 Running Locally

1. **Backend (Spring Boot)**

    ```bash
    cd backend
    ./mvnw spring-boot:run
    ```

    - Backend API runs at: `http://localhost:8080/api/products`

2. **Frontend (Angular)**

    ```bash
    cd frontend
    npm install
    ng serve
    ```

    - Frontend UI runs at: `http://localhost:4200/`

---

## 📚 Database Setup

- Create a database named `ecommerce`.
- Import SQL scripts from `/assets/db-scripts/` into your MySQL server.

---

## 📈 Future Enhancements

- User authentication (JWT login/register)
- Payment gateway integration (Stripe/PayPal)
- Admin dashboard for product management
- Product search, category filters, and pagination
