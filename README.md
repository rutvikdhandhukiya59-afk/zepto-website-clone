# 🛒 Zepto Clone — Quick-Commerce Web UI

A responsive and visually accurate frontend clone of the **Zepto** quick-commerce web application [cite: 1, 2]. Built using modern semantic **HTML5** and **CSS3**, enhanced with FontAwesome icons [cite: 1].

---

## ✨ Features

- **Header & Navigation Bar**:
  - Brand logo and real-time delivery estimation badge (*Delivery in minutes — Bhavnagar*) [cite: 1].
  - Global product search bar [cite: 1, 2].
  - User Login and Cart action indicators [cite: 1, 2].
  - Horizontally scrollable category navigation bar (Cafe, Fresh, Mobiles, Pharmacy, Toys, etc.) with active indicators [cite: 1, 2].
- **Promo Banners**: Double promotional showcase banner section [cite: 1, 2].
- **Category Grid**: 20-item categorized grocery & essentials grid with clean card iconography [cite: 1].
- **Curated Product Shelves**:
  - **Laundry Care**: Detergents, liquid pouches, powders with pricing, discounts, and customer ratings [cite: 1].
  - **Cleaning Essentials**: Surface cleaners, toilet sanitizers, sprays [cite: 1].
  - **Rice & Grains**: Everyday essentials, Basmati rice, poha, and millets [cite: 1].
- **Interactive Elements**:
  - Sticky header navigation on scroll [cite: 2].
  - Interactive "ADD" button mechanism for adding items to the cart [cite: 1, 2].
  - Responsive cards with discount badges (`<del>`), weight labels, and rating counts [cite: 1, 2].

---

## 🛠️ Tech Stack

- **HTML5**: Semantic document structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) [cite: 1].
- **CSS3**: Modern layouts using CSS Grid and Flexbox, custom scrollbars, responsive styling, and sticky positioning [cite: 2].
- **FontAwesome (v6.5.2)**: Clean vector icons for navigation, search, and cart utilities [cite: 1].
- **Vanilla JavaScript**: Lightweight inline cart counter functionality [cite: 1].

---

## 📁 Project Structure

```text
zepto-clone/
│
├── index.html            # Main landing page markup
├── style.css             # Stylesheet (Grid, Flexbox, layout & typography)
├── README.md             # Project documentation
└── asset/                # Images & static assets
    ├── favicon.jpg
    ├── primary-logo.svg
    ├── banner-1.png
    ├── banner-2.png
    ├── catagary card/     # Category thumbnail icons
    ├── product card/      # Laundry care product images
    ├── product card-2/    # Cleaning essentials product images
    └── product card-3/    # Rice & grains product images
```

---

## 🚀 Getting Started

1. **Clone or Download** the repository:
   ```bash
   git clone https://github.com/your-username/zepto-clone.git
   cd zepto-clone
   ```

2. **Open the Project**:
   - Double-click `index.html` to open it directly in any modern browser (Chrome, Firefox, Edge, Safari).
   - *Or* run a local development server using VS Code's **Live Server** extension or Python:
     ```bash
     python -m http.server 8000
     ```
   - Visit `http://localhost:8000` in your web browser.

---

## 📌 Planned Enhancements

- [ ] Connect shopping cart count dynamically to an interactive slide-in cart drawer.
- [ ] Implement live product search and filter functionality.
- [ ] Add media queries for optimized mobile and tablet screen breakpoints.
- [ ] Integrate local storage persistence for cart items.

---

## 📄 License

This project is created for educational and portfolio demonstration purposes as an HTML/CSS UI clone [cite: 1].
