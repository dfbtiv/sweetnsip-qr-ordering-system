# SweetNSip – QR Ordering System

SweetNSip is a web-based QR Ordering System designed to streamline the ordering workflow in dessert cafés.  
The system allows customers to place orders directly from their table via QR code, while cashiers and staff monitor and manage operations through a centralized dashboard.

This project is developed as an industry-oriented portfolio project, focusing on clean architecture, role separation, and real-world SDLC implementation.

---

## 🎯 Project Objectives
- Improve order efficiency using QR-based digital menus
- Reduce manual cashier workload and queue congestion
- Enable real-time order monitoring for café operations
- Demonstrate a scalable and maintainable web system design

---

## 🧩 System Roles
- **Customer**
  - Scan QR code at the table
  - View digital menu
  - Place orders without calling waiters

- **Cashier / Admin**
  - Manage menu items
  - Monitor incoming transactions
  - Update order and table status

- **Staff (Kitchen / Cleaning)**
  - Track order progress
  - Support operational workflow based on system status

---

## ✨ Key Features
- QR Code based ordering system
- Digital menu & transaction management
- Real-time order tracking
- Role-based system access
- Clean backend architecture following MVC pattern

---

## 🛠 Tech Stack
- **Backend:** Laravel
- **Database:** MySQL
- **Language:** PHP
- **Version Control:** Git & GitHub
- **Local Development:** Laragon

---

## 📂 Project Structure
This project follows Laravel’s standard MVC architecture:
- Controllers for business logic
- Models for database interaction
- Views for UI rendering
- Environment-based configuration using `.env`

---

## ⚙️ Installation & Setup

### Prerequisites
- PHP ≥ 8.x
- Composer
- MySQL
- Laragon / Local server

### Steps
```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

### 🚧 Development Status
Initial project setup completed
Database connection configured
Core system development in progress

### 📄 License
This project is licensed under the MIT License.

### 👩‍💻 Author
Dwi Febriyanti
Software Engineering Technology Student
Portfolio Project – 2025
