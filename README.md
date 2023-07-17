<h1 align="center">🚀 ERP System</h1>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License" />
</p>

<p align="center">
  Welcome to the ERP System repository! This repository contains the source code for an ERP (Enterprise Resource Planning) system, which is designed to manage various aspects of a business, including product management, table management, and user authentication. 💼📊
</p>

## 📚 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 🌟 Introduction

The ERP System is a web-based application developed to provide businesses with a centralized platform for managing product information, table data, and user authentication. It offers features such as adding products, viewing product data in a table format, and facilitating purchase and sell actions.

The project is implemented using PHP for server-side scripting, HTML for markup, and CSS for styling. It also utilizes a MySQL database to store and retrieve product and user data. The codebase follows a modular structure, making it easy to understand and extend. 🖥️💡

## ✨ Features

- **User Authentication**: The system allows users to sign in securely to access the application. 🔐👤
- **Product Management**: Users can add products with details such as name, quantity, and price. 📦💰
- **Table View**: The product data is displayed in a table format, making it easy to browse and analyze. 📊📋
- **Purchase and Sell Actions**: Buttons are provided for purchase and sell actions, enabling users to interact with the system for business transactions. 🛒💲

## ⚙️ Installation

To install and run the ERP System locally, follow these steps:

1. Move the cloned repository folder (`erp-system`) to the WampServer's `www` directory. By default, the `www` directory is located at `C:\wamp64\www` for WampServer 64-bit or `C:\wamp\www` for WampServer 32-bit. 📁🚀
2. Launch WampServer and ensure both Apache and MySQL services are running. 🌐✅
3. Open your web browser and visit `http://localhost/erp-system` (or `http://localhost:8080/erp-system` depending on your WampServer configuration) to access the ERP System homepage. 🌐🔗
4. Create a MySQL database for the ERP System. In your web browser, navigate to `http://localhost/phpmyadmin`, click on "New" to create a new database, and give it a suitable name (e.g., `erp_system`). 🗃️💾
5. Import the provided database schema and data into the newly created database. Inside the cloned repository, locate the `database.sql` file. In phpMyAdmin, select the newly created database, go to the "Import" tab, choose the `database.sql` file, and click "Go" to import the schema and data. 📂📥
6. Update the database connection details in the `php/dbconnection.php` file to match your local setup. Modify the following lines with your database credentials:
   ```php
   $host = 'localhost';
   $username = 'your-username';
   $password = 'your-password';
   $database = 'erp_system';
   ```
 7. Replace 'your-username' and 'your-password' with your MySQL username and password, respectively. 💻🔑
 8. Save the changes made to dbconnection.php. 💾✅

You can now access the ERP System by visiting http://localhost/erp-system in your web browser. Explore the different features, such as product management and table view. 🌐🚀

## 🎯 Usage

- Launch the ERP System by accessing the URL where you installed it. 🌐🚀
- Sign in using your credentials to access the main features of the system. 👤🔐
- On the Home page, you can navigate through the menu items, such as "Product" and "Table", to manage products and view product data. 📦📋
- In the Product section, you can add new products by providing details such as the product name, quantity, and price. 💼💰
- The product data will be displayed in a table format, allowing you to easily view and interact with the information. 📊📋
- The Purchase and Sell buttons enable you to perform respective actions for each product. 🛒💲
- You can explore the various features and functionalities of the ERP System to manage your business effectively. 💼🚀

## 🤝Contributing

Contributions to the ERP System project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request. Please ensure to follow the contribution guidelines outlined in the repository. 🙌🌟

## 📝 License

This project is licensed under the MIT License. Feel free to use and modify the code as per the terms of the license. 📃📜

---

We hope this README provides you with an overview of the ERP System and guides you on how to install and use it. If you have any further questions or need assistance, please don't hesitate to reach out. 📚❓

Happy managing your business with the ERP System! 💼🚀


