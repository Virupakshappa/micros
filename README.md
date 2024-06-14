# .NET Microservices for E-Commerce

This project is a comprehensive e-commerce platform comprising multiple microservices that handle different aspects of the application. It features role-based authentication, a manga cart, and content management capabilities, aimed at providing a robust system for both administrators and customers.

## Features

- **Role-based Authentication**: The system supports two user roles—**Admin** and **Customer**. Each role is granted different levels of access and functionalities within the application.
- **Manga Cart**: Customers can add items to their shopping cart and proceed to checkout. The cart supports the use of coupon codes to apply discounts.
- **Email Cart**: Customers can email the contents of their carts to themselves or others, which is useful for sharing or saving cart details.
- **Content Management**: Administrators can manage the product listings and coupons. This includes creating, editing, and deleting products and discount coupons.

## Technologies Used

- **.NET Framework**: Utilized for building robust and scalable microservices.
- **API Endpoints**: Each microservice exposes specific API endpoints that enable CRUD operations on products, user management, and cart functionalities.
- **Frontend Web Project**: A separate web-based frontend that consumes the APIs, providing a user interface for interaction with the system.
