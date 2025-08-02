# 🌿 Paradise Nursery - React + Redux Shopping App

This is the final project for the **Paradise Nursery** shopping application. It is a simple frontend web app built using **React** and **Redux** that allows users to browse houseplants, add them to a cart, and view/update the cart.

## ✨ Features

### 🏠 Landing Page
- Background image
- Company name and a short paragraph about the company
- "Get Started" button linking to the product listing page

### 🪴 Product Listing Page
- 6+ houseplants organized into 3+ categories
- Each plant displays:
  - Thumbnail image
  - Plant name
  - Price
  - "Add to Cart" button:
    - Adds plant to cart
    - Increases cart icon count
    - Disables after adding

### 🛒 Shopping Cart Page
- Displays:
  - Thumbnail, name, unit price for each plant in the cart
  - Quantity control (Increase/Decrease)
  - Total number of plants
  - Total cost
- Buttons:
  - **Delete** button for each plant
  - **Continue Shopping** button (returns to product listing)
  - **Checkout** button (shows "Coming Soon")

---

## 🛠️ Tech Stack

- React
- Redux Toolkit
- React Router DOM
- CSS

---

## 📂 Folder Structure
paradise-nursery/
├── public/
│ └── images/
├── src/
│ ├── components/
│ ├── pages/
│ ├── redux/
│ ├── App.js
│ └── index.js

