# Flipkart Clone

A full-stack Flipkart clone designed to provide seamless e-commerce functionality for users and administrators. This project replicates key features of Flipkart, including user authentication, product management, order tracking, and more.

## Features

### User Features
- **Authentication**:
  - Secure login and signup for user accounts.
  - Update profile details and change passwords.
  - Password reset via email using SendGrid.
- **Shopping Cart**:
  - Add/remove items.
  - Update quantities for cart items.
- **Save For Later**: Manage a list of items to purchase later.
- **Wishlist**: Add or remove items from your wishlist.
- **Product Browsing**:
  - Pagination (12 products per page by default).
  - Search functionality to find specific products.
  - Filters for categories, ratings, and price ranges.
- **Order Management**:
  - Store shipping information in session storage.
  - View past orders with filtering options.
  - Detailed view of ordered items.
  - Receive an order confirmation email with detailed information.
- **Reviews**: Add and view reviews for purchased products.

### Admin Features
- **Dashboard**: Exclusive access for admin users.
- **Order Management**:
  - Update order status.
  - Delete orders.
- **Product Management**:
  - Add and update product details.
  - Manage product stock (automatically decreases upon shipping).
- **User Management**:
  - View, update, or delete user accounts.
- **Review Management**:
  - List all reviews for a product.
  - Delete inappropriate or unwanted reviews.

## Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Clerk or custom JWT-based solution
- **Email Service**: SendGrid for transactional emails
- **State Management**: Context API or Redux
- **Hosting**: AWS, Vercel, or Netlify
