# 🛒 My Shop – E-Commerce Platform

## 🎯 Project Overview

My Shop is a multi-layered ASP.NET Core MVC e-commerce application designed to provide a seamless online shopping experience. It enables customers and administrators to:

- Browse products and place orders online.  
- Manage shopping cart and checkout processes.  
- Process secure online payments using Stripe API.  
- Manage products, categories, users, and orders.  
- Track transactions and support efficient order management.  

## 🏗️ Project Structure

### DataAccess Layer
Handles database context, migrations, repositories, and unit-of-work for structured data access.

### Utilities Layer
Contains helper services such as EmailSender, StripeData, and application settings.

### Entities Layer
Includes all models, repository interfaces, and ViewModels.

### Web Layer
ASP.NET Core MVC application with Areas for different user roles:

- **Admin** – Manage products, categories, users, orders, and payments.  
- **Customers** – Browse products, manage shopping cart, place orders, and complete checkout.  
- **Identity** – Authentication and user login.  
- **Services** – Business logic for orders, payments, and cart management.  

## 🛠️ Technologies Used

- ASP.NET Core 8.0  
- Entity Framework Core  
- SQL Server  
- Razor Pages / MVC Views  
- Bootstrap / CSS  
- Stripe API for secure payments  

## 🚀 Getting Started

### Clone the repository
```bash
git clone https://github.com/MohSannib/MyShop.git
```

### Apply database migrations
```bash
update-database
```

### Run the project
```bash
dotnet run
```

Or press **F5** in Visual Studio.

## 👤 Developer
Developed by **Mohamad Sannib**
