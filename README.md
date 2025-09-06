# 🌱 ECOFINDS

> **Empowering Sustainable Consumption through a Second-Hand Marketplace**

EcoFinds is a frontend prototype for a sustainable marketplace platform that enables users to buy, sell, and discover eco-friendly second-hand products. Designed to promote a circular economy, it provides a seamless experience for individuals to reduce waste and make conscious consumption choices.

This is a **frontend-only prototype** built with HTML, CSS, and Alpine.js, demonstrating core functionality with client-side data persistence.

 **[📖 Documentation]** | **[🐛 Report an Issue]**

---

## ✨ Key Features Implemented

### 🔐 User Authentication System
- User registration and login.
- Session management using `localStorage`.
- Protected routes for authenticated actions.

### 📦 Product Management
- Browse a curated list of all available eco-friendly products.
- **Logged-in users** can add new product listings.
- Manage your own listings (view, edit, and delete functionality).

### 🛒 Interactive Shopping Cart
- Add and remove products from the cart.
- Adjust item quantities.
- Cart data is persisted in `localStorage` across sessions.

### 📜 Order History & Checkout
- Simulated checkout process to complete purchases.
- Completed orders are moved to a "Previous Purchases" section.
- View detailed history of all past orders.

### 📱 Responsive Design
- A fully responsive layout that works seamlessly on desktop, tablet, and mobile.
- Clean, modern UI with an eco-friendly green color scheme.

---

## 🛠️ Tech Stack

This prototype is built entirely with client-side technologies:

- **HTML5:** For structure and semantic markup.
- **CSS3:** For styling, layout, and responsive design.
- **Alpine.js:** A lightweight JavaScript framework for reactive UI components and interactivity.
- **localStorage:** Used for client-side data persistence (users, sessions, products, cart).

---

## 🚀 How to Use

Getting started with the EcoFinds prototype is simple:

1.  **Clone or Download the Project**
    ```bash
    git clone https://github.com/your-username/ecofinds.git
    ```

2.  **Open the Project**
    Navigate to the project directory and open `index.html` in your web browser. No build process or server is required.

3.  **Register an Account**
    - Click on "Login" and then "Register" to create a new account.
    - Your credentials will be stored in the browser's `localStorage`.

4.  **Explore the Marketplace**
    - Browse the homepage to see all available products.
    - Use the navigation to explore different categories.

5.  **List a Product (Logged-in Users)**
    - Click "Sell an Item" to open the product form.
    - Fill in the details and submit to add your product to the marketplace.

6.  **Make a Purchase**
    - Click "Add to Cart" on any product.
    - View your cart, adjust quantities, and proceed to checkout.
    - After a successful checkout, the order will appear in your "Purchase History".

---

## 📦 Project Structure
