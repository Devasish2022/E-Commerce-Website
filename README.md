# 🛍️ ShopHub – React E-Commerce Store

🔗 **Live Demo:**  
https://e-commerce-website-one-blond.vercel.app/

A fully functional, responsive **E-Commerce Web Application** built with **React.js** and styled using modern **CSS (Grid + Flexbox)**.  
Designed to simulate a real-world shopping experience with authentication, cart management, protected routes, and persistent sessions.

---

## 📸 Preview

<p align="center">
  <img width="1289" height="957" alt="image" src="https://github.com/user-attachments/assets/126df9fa-5924-4e82-a21e-a10d2de7a1ba" />
</p>

> Replace the image link above with your actual screenshot after uploading it to GitHub.

---

## 🚀 Overview

This project demonstrates:

- Full e-commerce shopping flow
- Dynamic product detail routing (`/products/:id`)
- Authentication with protected routes
- Global state management using Context API
- Persistent cart & session using `localStorage`
- Responsive UI architecture
- Production-ready deployment on Vercel

The application replicates a real online store experience — from browsing products to checkout simulation.

---

## 🛠 Tech Stack

- **React.js**
- **React Router**
- **Context API**
- **JavaScript (ES6+)**
- **CSS (Grid + Flexbox)**
- **localStorage**
- **Vercel (Deployment)**

---

## 🧠 Core Implementation Logic

- `AuthContext` manages user authentication state.
- `CartContext` manages cart items and business logic.
- Cart total calculation:

  ```js
  cartTotal = Σ(product.price * quantity)
  ```

- `getProductById()` connects cart logic to product data.
- `localStorage` preserves:
  - Login session
  - Cart items across page refresh
- Protected routes restrict checkout/cart access when not logged in.

---

## 🎨 UI Highlights

- Clean product grid layout (CSS Grid)
- Responsive navigation bar (Flexbox)
- Dynamic auth-based Navbar state
- Interactive Product Cards
- Mobile-friendly responsive design
- Professional spacing & typography

---

## ⚡ What This Project Demonstrates

- Strong understanding of React ecosystem
- Advanced React Router usage
- Real-world cart business logic implementation
- Lightweight global state without Redux
- Proper session persistence handling
- Clean component architecture (Single Responsibility Principle)
- Deployment-ready frontend workflow
