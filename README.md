🛒 Online Shopping Web Application
This project is a full-stack dynamic e-commerce platform that allows customers to browse products, manage carts, and place orders, while administrators can manage products and track orders. The application is designed with a responsive frontend and a structured backend connected to a MySQL database.

✅ Project Features
🔹 Customer Panel
User Registration and Login

Product Browsing by Category

Add/Remove Products in Cart

Place and Track Orders

View Order History

🔹 Admin Panel
Admin Login

Add, Update, and Delete Products

View and Manage Orders

Track Inventory

🛠 Technology Stack
Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Local Hosting: XAMPP / WAMP Server

📊 Validation & Testing Features
Manual testing of user inputs, login flows, and order placement

SQL queries used for backend data validation

Input validation for forms and data handling

Database consistency checks using test records

📈 Future Enhancements
Integration of secure payment gateway (e.g., Razorpay, Stripe)

Product image upload and cloud storage

Email notifications for order confirmations

Responsive design for mobile and tablets

User reviews and rating system

📁 Dataset (Database)
Database: MySQL

Tables: users, products, orders, cart, admin

Fields:

Users: ID, Name, Email, Password, Address

Products: ID, Name, Description, Price, Category

Orders: Order ID, User ID, Product ID, Quantity, Status

Cart: Cart ID, User ID, Product ID, Quantity

⚙️ How to Run the Project
🔸 Prerequisites
XAMPP/WAMP (for Apache + MySQL)

PHP 7.x or above

MySQL Server

🔸 Steps
Clone the repository

bash
Copy
Edit
git clone https://github.com/Namandeepgupta/online-shopping-web-app.git
cd online-shopping-web-app
Start your local server

Open XAMPP/WAMP and start Apache and MySQL

Import the database

Go to phpMyAdmin, create a new database (e.g., shopping_db)

Import the provided .sql file (in /database folder)

Run the application

Place project folder in htdocs (XAMPP) or www (WAMP)

Open in browser: http://localhost/online-shopping-web-app

Login Credentials

Customer: Register via signup page

Admin: admin@shop.com / admin123 (or check database)
