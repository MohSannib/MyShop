🛒 My Shop – E-Commerce Platform

🎯 Project Overview

My Shop is a multi-layered ASP.NET Core MVC e-commerce application designed to provide a seamless online shopping experience. It enables customers and administrators to:

Browse products and place orders online.
Manage shopping cart and checkout processes.
Process secure online payments using Stripe API.
Manage products, categories, users, and orders.
Track transactions and support efficient order management.

🏗️ Project Structure

DataAccess Layer: Handles database context, migrations, repositories, and unit-of-work for structured data access.

Utilities Layer: Contains helper services such as EmailSender, StripeData, and application settings.

Entities Layer: Includes all models, repository interfaces, and ViewModels.

Web Layer: ASP.NET Core MVC application with Areas for different user roles:

Admin – Manage products, categories, users, orders, and payments.
Customers – Browse products, manage shopping cart, place orders, and complete checkout.
Identity – Authentication and user login.
Services – Business logic for orders, payments, and cart management.

🛠️ Technologies Used

ASP.NET Core 8.0
Entity Framework Core
SQL Server
Razor Pages / MVC Views
Bootstrap / CSS
Stripe API for secure payments

🚀 Getting Started

Clone the repository:

git clone https://github.com/MohSannib/MyShop.git

Open the solution in Visual Studio.

Check database connection settings in appsettings.Development.json.

Apply database migrations:

update-database

Run the project:

dotnet run

or press F5 in Visual Studio.

👤 Developer

Developed by Mohamad Sannib
