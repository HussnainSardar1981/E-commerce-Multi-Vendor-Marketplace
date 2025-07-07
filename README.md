# E-commerce Multi-Vendor Marketplace 🛒

A full-featured, modern multi-vendor e-commerce platform where users can shop, manage carts and orders, and vendors can create and manage their own online stores.

Built as a **personal full-stack project** using:

- **Frontend**: React.js (Vite) + TailwindCSS + Axios
- **Backend**: Django REST Framework (DRF)
- **Authentication**: JWT with secure token refresh flow
- **State Management**: React Context API
- **Payment Method**: Stripe

---

## 🌟 Features

### 🛍️ For Customers
- Browse and view products
- Add/remove items to/from cart
- Update item quantities
- Checkout & place orders
- View order history
- Payment Integration via stripe webhook

### 🧑‍💼 For Vendors
- Vendor authentication & dashboard
- Add, edit, and manage products
- View customer orders related to their products
- Payment Integration via stripe connect

### 🔐 Auth & Security
- JWT-based secure login/logout
- Auto-refresh tokens using interceptors
- Protected routes with role-based access
