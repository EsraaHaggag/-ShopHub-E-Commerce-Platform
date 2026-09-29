# 🛍️ E-Commerce Web Application

A bilingual (Arabic / English) e-commerce web application with role-based access for **Admins** and **Users**, built with **ASP.NET Core MVC** and a **3-Tier Architecture**.

## ✨ Features

### 👤 User
- Browse products with **search and filtering**
- **Shopping cart**: add, remove, and update quantities
- **Order management**: place orders and view order history and status
- **Secure authentication**: register, login, and protected pages
- **Multi-language UI**: Arabic (RTL) and English (LTR)

### 🛠️ Admin
- Manage products and categories
- View and manage orders
- Manage users and roles

## 🏛️ Architecture

The application follows a **3-Tier Architecture** to separate concerns and keep the code maintainable:

┌────────────────────────────────────┐
│ Presentation Layer (MVC) │ Controllers, Views
├────────────────────────────────────┤
│ Business Logic Layer (BLL) │ Services, Business Rules
├────────────────────────────────────┤
│ Data Access Layer (DAL) │ Data access, Entities
└────────────────────────────────────┘


- **Presentation Layer:** handles HTTP requests and renders the views. Contains no business logic.
- **Business Logic Layer:** contains the application rules such as cart and order handling.
- **Data Access Layer:** responsible for all communication with the database.

## 🧰 Tech Stack

| Layer | Technologies |
|---|---|
| Presentation | ASP.NET Core MVC, Razor Views |
| Business Logic | C# |
| Data Access | Entity Framework Core |
| Authentication | Role-based authorization (Admin / User) |
| Localization | Arabic and English UI |

## 🌍 Multi-language Support
- Full **Arabic (RTL)** and **English (LTR)** support
- The interface switches between the two languages

## 🔐 Authentication & Authorization
- Secure registration and login
- Role-based access control with two roles: **Admin** and **User**
- Protected pages based on the user's role

## 👩‍💻 Author
**Esraa**
Computer Science Graduate, Ain Shams University
