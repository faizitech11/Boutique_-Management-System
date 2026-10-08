# Boutique_-Management-System


# 👗 Boutique Management System

**Boutique Management System** is a web-based management application designed to help boutique owners manage their daily business operations from one place.

The system provides modules for **users, products, customers, orders, returns, invoices, and employees**, with a clean dashboard-based interface.

## ✨ Features

* 👤 User Management
* 👗 Product Management
* 👥 Customer Management
* 🛍️ Order Management
* 🔄 Return Order Management
* 🧾 Invoice Management
* 👨‍💼 Employee Management
* 📊 Dashboard
* 🔐 Role-based access
* 🗃️ Database management
* 📱 Responsive interface
* 🎨 Modern boutique-style UI

---

## 🏢 System Modules

### 👤 User Management

Manage system users and their access to different parts of the application.

### 👗 Product Management

Add, update, view, and manage boutique products.

Product information can include:

* Product name
* Category
* Price
* Quantity
* Product details
* Availability

### 👥 Customer Management

Maintain customer records and manage customer-related information.

### 🛍️ Order Management

Create and manage customer orders while keeping order information organized.

### 🔄 Return Orders

Handle returned products and maintain return-order records.

### 🧾 Invoice Management

Generate and manage invoices for customer orders.

### 👨‍💼 Employee Management

Manage employee information and employee-related operations.

### 📊 Dashboard

The dashboard provides a centralized overview of the boutique management system.

---

## 🛠️ Technology Stack

### Backend

* Python
* Flask

### Frontend

* HTML5
* CSS3
* JavaScript

### Database

* MySQL

### Tools

* VS Code
* XAMPP
* Git
* GitHub

---

## 📁 Project Structure

```text
BoutiqueManagementSystem/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── index.html
│   ├── user.html
│   ├── products.html
│   ├── customers.html
│   ├── returnorder.html
│   ├── invoice.html
│   ├── modInv.html
│   └── employee.html
│
├── myApp.py
├── database/
└── README.md
```

> The exact folder structure may vary depending on the current project version.

---

## 🔗 Main Routes

The application includes routes for major boutique operations:

```text
/user
/products
/customers
/returnorder
/invoice
```

Additional routes include:

```text
/modInv
/employee
```

These routes can be accessed according to the user's role and system permissions.

---

## 👥 User Role

The project includes role-based functionality.

Current project role:

```text
OWNER
```

The system can be extended with additional roles such as:

```text
Admin
Manager
Employee
Staff
```

---

## 🗄️ Database

The project uses a database named:

```text
BoutiqueManagementSystem
```

Make sure the required database and tables are created before running the application.

---

## ▶️ Run the Project

### 1. Open the Project Folder

```bash
cd C:\xampp\htdocs\B
```

### 2. Install Flask

```bash
pip install flask
```

If the project contains a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 3. Start the Application

```bash
python myApp.py
```

### 4. Open in Browser

```text
http://127.0.0.1:5000
```

---

## ⚙️ Database Configuration

Before running the project, configure the database connection inside the Flask application according to your local MySQL/XAMPP setup.

Example configuration:

```python
DB_HOST = "localhost"
DB_USER = "root"
DB_PASSWORD = ""
DB_NAME = "BoutiqueManagementSystem"
```

Use your actual database credentials if they are different.

---

## 🔄 Application Flow

```text
                    ┌─────────────────┐
                    │     Dashboard   │
                    └────────┬────────┘
                             │
          ┌──────────────────┼──────────────────┐
          │                  │                  │
          ▼                  ▼                  ▼
       Products          Customers            Users
          │                  │
          └──────────┬───────┘
                     ▼
                  Orders
                     │
              ┌──────┴──────┐
              ▼             ▼
        Return Orders     Invoice
                            │
                            ▼
                     Invoice Management
```

---

## 🎨 UI & Design

The application uses a boutique-focused dashboard interface designed to provide a professional management experience.

### UI Highlights

* Modern dashboard
* Boutique-inspired design
* Responsive layout
* Navigation sidebar
* Management cards
* Tables for business data
* Interactive buttons
* Form-based data management
* Clean visual hierarchy

---

## 🚀 Future Improvements

The system can be further expanded with:

* 🧾 Advanced POS system
* 📏 Customer measurements
* 📊 Sales reports
* 📈 Business analytics
* 👗 Dress preview system
* 📱 WhatsApp customer reminders
* 💳 Online payments
* 📦 Inventory alerts
* 🧾 Printable invoices
* 📅 Appointment management
* 👥 Advanced employee permissions

---

## 👨‍💻 Project Team

### The 4th Legion

**Role:** Owner

The project was developed as a practical boutique-management solution with a focus on business workflow, database management, and web application development.

---

## 💻 Skills Demonstrated

```text
Python
Flask
HTML5
CSS3
JavaScript
MySQL
CRUD Operations
REST/Web Routing
Database Integration
Role-Based Access
Responsive UI
Git & GitHub
```

---

## 📌 Project Purpose

The main purpose of the **Boutique Management System** is to digitize common boutique operations and provide a centralized platform for managing products, customers, orders, returns, invoices, users, and employees.

It demonstrates practical experience in **Python Flask backend development, MySQL database integration, CRUD operations, routing, and frontend UI development**.

---

## 📄 License

This project is developed for **educational, portfolio, and demonstration purposes**.

---

⭐ **If you find this project useful, consider giving the repository a star!**
