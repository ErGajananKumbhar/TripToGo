# 🚌 TripToGo - Online Bus Booking Application

TripToGo is a **Spring Boot-based travel booking system** where users can register, log in, search buses, book seats, make payments, and view their trip orders.  
It’s built using a **Java Full Stack** approach, integrating Spring Boot, REST APIs, JPA, and secure authentication using JWT.

---

## 🚀 Features

| Module | Description |
|---------|--------------|
| **User Module** | User registration, login, JWT authentication |
| **Bus Module** | Add, view, and search available buses by route and date |
| **Booking Module** | Book seats, cancel bookings, and view booking history |
| **Payment Module** | Integration with Razorpay/Stripe for online payments |
| **Order Module** | Checkout, order summary, and order tracking |

---

## 🧱 Project Architecture


| Layer | Purpose |
|--------|----------|
| **Controller** | Exposes REST APIs for frontend or Postman |
| **Service** | Contains business logic |
| **Repository** | Interacts with the database using Spring Data JPA |
| **Entity** | Defines database tables |
| **Security** | Handles authentication and authorization using Spring Security + JWT |

---

## ⚙️ Tech Stack

| Technology | Purpose |
|-------------|----------|
| **Java 17+** | Core programming language |
| **Spring Boot 3.x** | Backend framework |
| **Spring Security + JWT** | Authentication & Authorization |
| **Spring Data JPA (Hibernate)** | ORM and database communication |
| **MySQL** | Database |
| **Lombok** | Reduce boilerplate code |
| **Maven** | Build and dependency management |
| **Postman** | API testing |
| **Razorpay / Stripe API** | Payment gateway integration |
| **AWS / Render / Railway** | Deployment (optional) |

---

## 🧩 Modules Overview

### 1️⃣ User Module
- Register new users  
- Login and generate JWT Token  
- Secure APIs using JWT filter  

### 2️⃣ Bus Module
- Admin can add buses  
- Users can view/search buses by route or date  

### 3️⃣ Booking Module
- Book/cancel seat  
- View booking details and status  

### 4️⃣ Payment Module
- Razorpay/Stripe payment integration  
- Payment status and transaction details  

### 5️⃣ Order Module
- Checkout and confirm trip order  
- Generate order summary  

---

## 🛠️ Project Setup

### Prerequisites
- Java 17+
- Maven 3+
- MySQL Database
- Postman (for API testing)

### Steps to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/triptogo.git
   cd triptogo
