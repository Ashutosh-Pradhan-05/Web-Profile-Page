# Ashutosh Pradhan — Responsive Web Profile Page (HTML & CSS)

Single-page responsive profile built with **only HTML & CSS**. This repository contains a personal portfolio/profile page showcasing About, Skills, Projects, Qualifications, Certifications, and Contact sections.

---

## 🔖 Project overview

This project is a clean, responsive personal profile page that highlights professional details and projects. It uses a single HTML file (`index.html`) and a separate stylesheet (`style.css`). The page is designed to be easily hosted on GitHub Pages or Netlify.

**Core principles:**

* Semantic, accessible HTML
* Responsive layout using CSS grid & flexbox
* No JavaScript frameworks — minimal JS (only optional, e.g., mobile nav checkbox technique)
* Smooth scrolling using native CSS (`scroll-behavior: smooth`)

---

## ✨ Key features

* Sticky, responsive navigation bar linking to page sections (Home, About, Skills, Projects, Qualifications, Certificates, Contact)
* Hero section with profile photo, title and CTA buttons
* About section with brief bio
* Skills section with a grid of technologies / skill bars
* Projects section with cards and links to GitHub repos
* Qualifications section with 3 cards (University, Intermediate, Schooling)
* Certificates list with verify links
* Contact section with contact card, email and social links
* Footer with copyright info and a back-to-top arrow
* Font Awesome for icons (linked via CDN)

---

## 📁 File structure

```
/ (project root)
├─ index.html            # Main HTML file (already provided)
├─ style.css             # Main stylesheet (create/upload this file)
├─ images/               # Contains all image assets (Certificate images,Academic logos, profile picture, Favicon etc.)
└─ README.md             # This file
```

---

## ⚙️ How to add the CSS file (if you can't upload large files)

1. Create a file named `style.css` in the same directory as `index.html`.
2. Paste your existing CSS content into `style.css` and save.
3. Ensure the `<link rel="stylesheet" href="style.css" />` line is present in your `index.html` `<head>` (your current HTML already has this).


---

## 📌 Font Awesome (CDN)

Add this to the `<head>` of `index.html` to enable Font Awesome icons (replace version with the latest if needed):

```html
<link rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
  integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
  crossorigin="anonymous" referrerpolicy="no-referrer" />
```

---

## 🧾 Accessibility & Best Practices

* Use semantic elements (`<header>`, `<main>`, `<section>`, `<nav>`, `<footer>`).
* Provide `alt` text for images.
* Add `rel="noopener"` to external links opened with `target="_blank"` (security).

---

## 🤝 Credits & License

Made by **Ashutosh Pradhan** — feel free to reuse and adapt. Add a license file if you want to make the repo open-source.

Happy to help — tell me which of the above you'd like next!
