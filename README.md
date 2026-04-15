---

# 🏋️ Royal Gym — Responsive Landing Page

This project was developed as part of a **technical assessment** for **Dingus & Zazzy**.

A modern, fully responsive landing page for a premium gym experience, focused on performance, scalability, and clean architecture.

---

## 🚀 Overview

This project is a complete front-end implementation of a gym landing page with:

* Mobile-first responsive design
* Dynamic pricing system
* Clean and scalable CSS architecture (BEM)
* Smooth UI interactions and animations

---

## 📱 Responsive Design

Built with a **mobile-first approach**, using 4 well-defined breakpoints:

### 🖥 Desktop (1025px+)

* Full layout with 4-column grids
* Side-by-side sections
* Custom cursor enabled
* Enhanced visual effects

### 💻 Tablet (≤1024px)

* 2-column grid layout
* Simplified visuals for performance
* Stacked sections (e.g., About)
* CTA adjustments

### 📱 Mobile (≤768px)

* Hamburger navigation with slide-down menu
* Single-column layout
* Optimized spacing and readability

### 📲 Small Mobile (≤420px)

* Compact spacing
* Reduced typography scale
* Simplified gallery layout

---

## 💰 Dynamic Pricing System

The pricing section includes **fully interactive tabs**:

* Monthly
* Quarterly (Save 10%)
* Semi-Annual (Save 15%)
* Annual (Save 20%)

### Features:

* Real-time content swapping (prices + features)
* Dynamic billing labels
* Smooth card animations (staggered fade-in)
* Highlighted featured plan

---

## 🎯 Architecture & Code Quality

### 🧱 BEM Methodology

The project uses **BEM (Block Element Modifier)** for scalable and maintainable CSS.

#### Examples:

* **Block**

  * `.price-card`
  * `.service-card`
  * `.testi-card`

* **Element**

  * `.price-card__plan`
  * `.service-card__title`

* **Modifier**

  * `.price-card--featured`
  * `.btn--gold`

* **State**

  * `.is-active`
  * `.is-open`

---

## ⚙️ JavaScript Features

* Dynamic pricing logic
* Tab switching system
* Hamburger menu toggle
* UI state handling

### JS Hooks (separated from styling)

* `#js-cursor`
* `#js-hamburger`
* `#js-pricing-grid`

---

## 🧭 Navigation

* Fully responsive navbar
* Hamburger menu on mobile
* Smooth interaction states

---

## 🎨 UI & UX Highlights

* Clean modern design
* Smooth transitions and animations
* Performance-optimized layout
* Overflow issues fully resolved on small screens

---

## 📂 Project Structure

```
RoyalGym/
│
├── Html/
│   └── royal-gym_3.html
├── Layout/
│   └── style.css
```

---

## 🛠 Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla)

---

## 📄 License

This project is intended for **evaluation purposes** as part of a technical test.

---

