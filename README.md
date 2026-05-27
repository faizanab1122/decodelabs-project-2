# Pixel & Flow — Creative Studio Website
### Project 2 | Responsive Web Layout | DecodeLabs Industrial Training | Batch 2026

---

## 📌 Project Overview

**Pixel & Flow** is a fully responsive creative studio website built as **Project 2** of the DecodeLabs Industrial Training Program (Batch 2026). The goal of this project is to demonstrate mastery of **responsive web design** using pure HTML and CSS — ensuring the website looks great on every screen size, from mobile phones to large desktop monitors.

---

## 🎯 Project Goal

> Build a responsive webpage that works across different screen sizes using CSS media queries, responsive navigation, and proper spacing and alignment.

---

## 🗂️ Project Structure

```
project-2/
│
├── index.html          # Main HTML file (all code in one file)
└── README.md           # Project documentation
```

---

## ✅ Implementation Checklist

| Feature | Status |
|---|---|
| Viewport Meta Tag (`width=device-width`) | ✅ Done |
| Mobile-First Base CSS | ✅ Done |
| CSS Flexbox for components | ✅ Done |
| Responsive Navigation | ✅ Done |
| Hamburger Menu (mobile) | ✅ Done |
| Media Query — Tablet (768px) | ✅ Done |
| Media Query — Desktop (1024px) | ✅ Done |
| Proper Spacing and Alignment | ✅ Done |
| Marquee / Scrolling Banner | ✅ Done |
| Accessible Touch Targets (44px+) | ✅ Done |

---

## 📱 Responsive Breakpoints

| Screen | Breakpoint | Layout |
|---|---|---|
| Mobile | Default (0px+) | Single column, hamburger menu |
| Tablet | `max-width: 768px` | 2 columns, stacked footer |
| Desktop | `min-width: 1024px` | 3 columns, full navbar |

---

## 🧠 Key Concepts Used

### 1. Viewport Meta Tag
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
This is the "Key to the Kingdom" — without it, mobile browsers use a fake 980px viewport.

### 2. Mobile-First CSS
All base styles are written for mobile. Larger screens are handled with `@media` queries on top.

### 3. Flexbox Layout
Used for navbar, hero buttons, service cards, work grid, testimonials, and footer.

```css
.services-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}
```

### 4. CSS Media Queries
```css
/* Tablet and below */
@media (max-width: 768px) {
    .service-card { width: 100%; }
    .nav-pages    { display: none; }
    .burger-btn   { display: flex; }
}

/* Desktop */
@media (min-width: 1024px) {
    .service-card { width: 30%; }
}
```

### 5. Hamburger Navigation (JavaScript)
Mobile navigation using a toggle button that shows/hides the mobile menu drawer.

---

## 🗂️ Sections in the Website

1. **Navbar** — Fixed top navigation with logo, links, and hamburger for mobile
2. **Mobile Menu** — Full-width dropdown that appears on burger click
3. **Hero** — Full-screen landing section with title, description, CTA buttons, and stats
4. **Marquee** — Scrolling skills banner using CSS animation
5. **Services** — 6 service cards in a responsive flex grid
6. **Work** — 4 project showcase cards in a responsive grid
7. **Process** — 5-step numbered process list
8. **Testimonials** — 3 client review cards
9. **CTA** — Call to action section with dark background
10. **Footer** — Multi-column footer with links and social icons

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantic markup |
| CSS3 | Styling, layout, animations |
| Flexbox | Responsive grid layouts |
| CSS Media Queries | Breakpoints for different screens |
| CSS Animations | Marquee scrolling effect |
| JavaScript (Vanilla) | Hamburger menu toggle |
| Google Fonts | Open Sans + Poppins typography |

---

## 🚀 How to Run

1. Download or clone this project
2. Open `index.html` in any web browser
3. No installations or dependencies required
4. Resize the browser window to test responsiveness

---

## 🖥️ Screenshots / Preview

| Device | Description |
|---|---|
| Mobile (360px) | Single column layout, hamburger menu visible |
| Tablet (768px) | 2-column cards, nav still hidden |
| Desktop (1200px) | Full 3-column layout, complete navbar |

---

## 👨‍💻 Author

**Muhammad Faizan Abdul Salam**
Frontend Developer Intern — DecodeLabs
Batch 2026 | University of Lahore

---

## 🏢 Organization

**DecodeLabs**
📧 decodelabs.tech@gmail.com
🌐 www.decodelabs.tech
📍 Greater Lucknow, India

---

## 📄 License

This project was built as part of the DecodeLabs Industrial Training Program.
For educational and training purposes only.
