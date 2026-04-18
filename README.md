# courier-management-system
# 🚚 Courier Management System

A web-based Courier Management System developed using PHP and MySQL to manage courier bookings, sender and receiver details, delivery records, and admin operations.

This project helps streamline courier service processes such as placing orders, tracking records, managing users, and maintaining delivery history.

---

## 📌 Features

### 👤 User Side
- Place courier orders
- Enter sender and receiver details
- View courier booking history

### 🔐 Admin Side
- Secure admin login
- Dashboard management
- View courier records
- Delete records
- Manage users
- View delivery history

---

## 🛠️ Tech Stack

- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Database: MySQL
- Server: XAMPP / WAMP

---

## 📂 Project Structure

```bash
courier-management-system/
│── adminlogin.php
│── dashboard.php
│── courierMenu.php
│── datadeleted.php
│── datahistory.php
│── deleteusers.php
│── courierdb.sql
│── README.md

⚙️ Installation Steps
1. Clone Repository
git clone https://github.com/your-username/courier-management-system.git
2. Move Folder

Copy project folder into:

htdocs (XAMPP)
www (WAMP)
3. Start Server

Start Apache and MySQL from XAMPP/WAMP.

4. Import Database
Open phpMyAdmin
Create database named courierdb
Import courierdb.sql
5. Run Project
http://localhost/courier-management-system/
🔑 Admin Login

Use admin credentials stored in database.

🚀 Future Improvements
Live courier tracking
Email/SMS notifications
Payment integration
Better UI design
Reports and analytics
