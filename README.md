# Skewed Vertical Menu with Font Awesome Icons

A stylish **skewed vertical navigation menu** built using pure HTML & CSS, featuring Font Awesome icons rendered via pseudo-elements. This project focuses on CSS transforms, layering, and icon rendering without JavaScript.

---

## ✨ Features

* Skewed 3D-like vertical menu
* Font Awesome icons rendered using `::before`
* Smooth hover transitions
* Pure HTML + CSS (no JS)
* Icons centered perfectly using Flexbox
* Easy to customize and extend

---

## 🧰 Tech Stack

* HTML5
* CSS3 (Flexbox, Transforms)
* Font Awesome 6 (Free)

---

## 📦 Project Structure

```
project-root/
│
├── index.html
├── style.css
└── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Include Font Awesome

Add this inside the `<head>` of your HTML file:

```html
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
/>
```

---

### 2️⃣ HTML Markup

Icons are injected using the `data-icon` attribute and rendered via CSS pseudo-elements:

```html
<ul>
  <li style="--i:6;" data-icon="&#xf015;"><a href="#">Home</a></li>
  <li style="--i:5;" data-icon="&#xf2bb;"><a href="#">About</a></li>
  <li style="--i:4;" data-icon="&#xf03a;"><a href="#">Services</a></li>
  <li style="--i:3;" data-icon="&#xf07c;"><a href="#">Portfolio</a></li>
  <li style="--i:2;" data-icon="&#xf0c0;"><a href="#">Our Team</a></li>
  <li style="--i:1;" data-icon="&#xf0e0;"><a href="#">Contact</a></li>
</ul>
```

---

## 🎯 Key CSS Concepts Used

### Centering the Entire Menu

The menu is centered both vertically and horizontally using Flexbox:

* `display: flex`
* `justify-content: center`
* `align-items: center`

### Centering Icons

Icons are centered using Flexbox **inside the `::before` pseudo-element**:

* `display: flex`
* `justify-content: center`
* `align-items: center`

### Font Awesome Requirements

To render Font Awesome icons correctly:

* Use `font-family: "Font Awesome 6 Free"`
* Always set `font-weight: 900` for solid icons
* Ensure unicode values belong to **Font Awesome Free**

---

## ⚠️ Common Pitfalls

* ❌ Forgetting `font-weight: 900` → icons won’t appear
* ❌ Using Pro-only unicode icons
* ❌ Missing `display: flex` on pseudo-elements
* ❌ Overwriting `transform` instead of merging transforms

---

## 🎨 Customization Ideas

* Change skew angle for different depth illusion
* Animate icons independently on hover
* Replace unicode icons with SVGs
* Convert menu into a reusable component

---

## 📸 Preview

> A vertical skewed navigation menu with animated side panels and centered Font Awesome icons.

---

## ❤️ Author

Built with care for **CSS practice and visual UI experiments**.

Happy coding, sweetheart 💫
