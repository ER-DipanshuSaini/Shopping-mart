
# 🛒 E-Commerce PHP Project

## Overview
This is a **dynamic** eCommerce website built using **PHP** and **MySQL**. The application allows users to browse products, add items to the cart, and make purchases. Admins can efficiently manage product listings, orders, and customer data, all through a dedicated Admin Panel.

---

## ✨ Features
- **🔐 User Authentication:** Registration, login, and user profile management.
- **🛍️ Product Browsing:** Search, filter, and view detailed product information.
- **🛒 Shopping Cart:** Add, remove, and update products in the cart.
- **💳 Checkout Process:** Complete orders with payment options.
- **🔧 Admin Panel:** Manage products, categories, orders, and customers.
- **📱 Responsive Design:** Mobile-friendly layout using HTML, CSS, and JavaScript.

---

## 🛠️ Technologies Used
- **Back-end:** PHP
- **Database:** MySQL
- **Front-end:** HTML, CSS, JavaScript (optional: Bootstrap for styling)
- **Version control:** Git
- **Payment Integration:** (e.g., PayPal, Stripe)

---

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ER-DipanshuSaini/Shopping-mart.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Shopping-mart
   ```

3. **Database setup:**
   - Open your MySQL client (e.g., phpMyAdmin or MySQL CLI).
   - Create a new database:
     ```sql
     CREATE DATABASE ecommerce_db;
     ```
   - Import the SQL file located in the `/database` folder.

4. **Update the configuration file:**
   - Modify the `config.php` file with your database credentials:
     ```php
     define('DB_SERVER', 'localhost');
     define('DB_USERNAME', 'your-username');
     define('DB_PASSWORD', 'your-password');
     define('DB_NAME', 'ecommerce_db');
     ```

5. **Run the server:**
   - If using XAMPP, place the project folder in the `htdocs` directory.
   - Open your browser and visit `http://localhost/Shopping-mart`.

---

## 🚀 Usage
- **For Users:**
  - Browse products and make purchases.
  - Manage your cart and user profile.

- **For Admins:**
  - Log into the admin panel to manage products, categories, and view orders.

---

## 📸 Screenshots
_(Include project screenshots here for a better visual representation.)_

---

## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request if you want to improve the project.

---

## 📝 License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.
