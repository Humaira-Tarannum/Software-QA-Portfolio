# Software Requirements Specification (SRS)

# Project Name
ShopEasy - E-commerce Web Application

## Prepared By
Humaira Tarannum

## Purpose
ShopEasy is an online shopping platform where customers can browse products, add them to a cart, make payments, and track their orders. This document defines the functional requirements of the application.

---

# Modules

1. User Registration
2. User Login
3. Home Page
4. Product Search
5. Product Details
6. Shopping Cart
7. Wishlist
8. Checkout
9. Payment
10. Order History
11. User Profile

---

# Functional Requirements

## Registration
- User should be able to create an account using a valid email address.
- Password must contain at least 8 characters.
- Email address must be unique.
- Mandatory fields cannot be left blank.

## Login
- Registered users should be able to log in.
- Invalid credentials should display an error message.
- Forgot Password option should be available.
- User should be redirected to the Home page after successful login.

## Home Page
- Display featured products.
- Display categories.
- Display promotional banners.
- Search bar should be visible.

## Product Search
- Search products by keyword.
- Filter by category.
- Filter by price.
- Sort by price and popularity.

## Product Details
- Display product images.
- Display description.
- Display price.
- Display stock availability.
- Allow Add to Cart.
- Allow Add to Wishlist.

## Shopping Cart
- Add products.
- Update quantity.
- Remove products.
- Display total amount.

## Wishlist
- Add products.
- Remove products.
- Move product to Cart.

## Checkout
- Select delivery address.
- Select payment method.
- Review order before placing it.

## Payment
- Credit/Debit Card
- UPI
- Net Banking
- Wallet

Successful payment should create an order.

## Order History
- View previous orders.
- View order status.
- Download invoice.

## User Profile
- Update personal information.
- Change password.
- Manage addresses.

---

# Non-Functional Requirements

- Website should load within 3 seconds.
- Application should support Chrome, Edge and Firefox.
- Passwords should be encrypted.
- Website should be responsive for desktop and mobile devices.
- User session should expire after 30 minutes of inactivity.
