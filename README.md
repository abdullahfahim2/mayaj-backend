# 👟 Mayaj – Django E-Commerce Platform for Shoe Items

**Mayaj** is a modern, full-featured **eCommerce platform** built with **Django** and **Tailwind CSS**, focusing on selling **shoe products**.  
It provides a fully functional store backend with product management, cart, checkout, offers, and return request logic — all powered by a clean, scalable Django architecture.

> ⚙️ Authentication and SSLCommerz sandbox payment gateway integration are currently under development.

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| Backend Framework | Django (Python) |
| Frontend Styling | Tailwind CSS |
| Database (Development) | SQLite3 |
| Database (Production) | PostgreSQL |
| ORM | Django ORM |
| Template Engine | Django Templates |
| Payment Gateway | SSLCommerz (Sandbox – coming soon) |

---

## 🎯 Project Goal

> Build a robust, full-stack eCommerce platform for **shoe items**, featuring complete product management, user authentication, cart/checkout systems, and secure payment processing.

---

## 🌟 Core Features

### 🏠 Storefront
- Dynamic homepage with featured products, hero sections, rotating showcases, and active offers  
- Product listings with pagination and filtering  
- Product detail pages with images, ratings, and size management  
- Search functionality (name, description, category)

### 🛒 Cart & Checkout
- Add, update, and remove products from cart  
- AJAX-based cart operations for smoother UX  
- “Buy Now” option with direct checkout redirect  
- Checkout page with shipping details and total calculation  
- Order creation, tracking, and success page  

### 💬 Reviews & Offers
- Product review submission (requires admin approval)  
- Display of approved reviews with rating average  
- Active combo offers and discounts display  

### 📦 Returns & Policies
- Dynamic returns page with steps, policies, and refund methods  
- Return request form with validation and success feedback  

### 📄 Informational Pages
- About page (team, founders, company info)  
- Contact page with message form and dynamic contact info  
- Offers and return pages fully data-driven from the database  

---

## 🧠 Views & Logic Overview

All core application logic is managed in `store/views.py`, including:
- Search handling with `Q` lookups  
- Homepage, product listing, and product details  
- Cart management (`add_to_cart`, `remove_from_cart`, `update_cart`)  
- Checkout and order processing  
- Review creation, offer pages, and contact forms  
- Return policy form and validations  

---

