# Book Management System

A comprehensive Book Management System built with PHP and MySQL. This web application provides a multi-user environment, allowing different types of users to manage, sell, buy, and track book inventory.

The system is designed with four distinct user roles, each with its own dashboard and privileges:
* **Admin:** Has complete control over the application.
* **Accountant:** Manages finances and sales reports.
* **Book Seller:** Manages their own book inventory and sales.
* **Buyer:** Can browse, search, and purchase books.

---

## ✨ Features by Role

### 👤 Admin
* Full dashboard with oversight of the entire system.
* Manage all user accounts (create, edit, delete all user types).
* Approve new Book Seller and Accountant registrations.
* View and manage the complete book inventory from all sellers.
* Monitor site-wide sales and transactions.

### 📚 Book Seller
* Register for a new seller account (must be approved by Admin).
* Log in to a dedicated seller dashboard.
* Upload new books, including details, pricing, and cover images.
* Edit and delete their own book listings.
* View and manage orders for their books.

### 💰 Accountant
* Log in to a dedicated accountant dashboard.
* View all financial transactions and sales records.
* Generate sales reports (e.g., daily, monthly, per-seller).
* Manage payment and commission information.

### 🧑 Buyer
* Create a new buyer account and log in.
* Browse and search the entire book catalog from all sellers.
* View detailed information for each book.
* (Add other features like "Add to cart" or "Purchase" here)

---

## 🛠️ Technologies Used

* **Backend:** PHP
* **Database:** MySQL
* **Frontend:** HTML, CSS, JavaScript
