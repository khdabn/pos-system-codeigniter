# POS System - CodeIgniter 4

A basic Point-of-Sale web application developed using CodeIgniter 4 and MySQL.

## Features

- Landing Page
- About Page
- Customer Accounts
- User Accounts
- MySQL database integration
- CodeIgniter Models, Views, and Controllers

## Database

Database name: `pos_db`

Tables:
- `customers`
- `users`

The database export is included as `pos_db.sql`.

## How to Run

1. Install XAMPP and Composer.
2. Place the project inside the XAMPP `htdocs` folder.
3. Start Apache and MySQL.
4. Create a database named `pos_db` in phpMyAdmin.
5. Import `pos_db.sql`.
6. Configure the database connection in `.env`.
7. Open CMD inside the project folder.
8. Run:

   php spark serve

9. Open `http://localhost:8080` in a browser.

## Pages

- `/` - Home
- `/about` - About
- `/customers` - Customer Accounts
- `/users` - User Accounts