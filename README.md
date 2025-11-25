# 🛒 CARTSY – Java Shopping Mall Management System

A modern, interactive **shopping mall management application** built with **Java Swing** and database integration.

This project allows users to:
- Register and login as Admin, Seller, or Customer
- Manage products, inventory, and sales (Seller)
- Browse, add to cart, and order products (Customer)
- View analytics, manage users, and control ads (Admin)
- Chat between sellers and customers
- Edit profiles and manage payment info

---

### 🧠 Key Features

- ✅ Java Swing GUI with modern dialogs
- ✅ Admin, Seller, and Customer panels
- ✅ Product management and inventory
- ✅ Cart and order system with checkout and billing
- ✅ Sales analytics and user management
- ✅ Chat and ads modules
- ✅ Database integration (MySQL recommended)

---

### 📁 File Structure

- `MainMenu.java` – Entry point and main navigation
- `AdminLogin.java`, `AdminDashboard.java` – Admin panel
- `SellerLogin.java`, `SellerDashboard.java`, `ProductManagement.java` – Seller panel
- `CustomerLogin.java`, `CustomerDashboard.java`, `CustomerCartDialog.java`, `CustomerOrdersDialog.java`, `CustomerChatDialog.java`, `CustomerAdsDialog.java` – Customer panel
- `RegisterScreen.java` – Unified registration for sellers/customers
- `DBConnection.java` – Database connection handler
- `...` – Additional supporting files

---

### 🚀 Getting Started

- Open in any Java IDE
- Set up the database with the following tables:
  - `users`
  - `products`
  - `cart`
  - `orders`
  - `order_items`
  - `ads`
- Run `MainMenu.java` to launch the application

---

