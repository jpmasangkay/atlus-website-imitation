# 🎮 ATLUS Website Imitation

### A Fan-Made Recreation of the Official ATLUS Website

**Browse. Discover. Play.**

A faithful, multi-page static website imitation of the official [ATLUS](https://atlus.com) gaming website — the legendary Japanese publisher behind Persona, Shin Megami Tensei, and Metaphor: ReFantazio. Built from scratch with vanilla HTML, CSS, and JavaScript, it recreates the look and feel of the original site with hand-crafted layouts, responsive design, and polished styling.

[![HTML](https://img.shields.io/badge/HTML5-80%25-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-18%25-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-1%25-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## ✨ Features

### 🏠 Home Page (`Index.html`)
- Hero section showcasing ATLUS branding and featured titles
- Navigation bar with links to all major sections of the site
- Highlights of the latest and most acclaimed game releases

### 🎮 Games Page (`Games.html`)
- Catalog-style layout displaying ATLUS game titles
- Game cards with cover art, titles, and key details
- A clean browsing experience inspired by the official ATLUS games library

### 🏢 About Page (`About.html`)
- Company history and background information
- Overview of ATLUS's iconic franchises and legacy
- Tribute to the studio's role in the JRPG genre

### 📬 Contact Page (`Contact.html`)
- Styled contact form layout for user inquiries
- Clean, accessible form fields matching the ATLUS brand aesthetic

### 🔐 Authentication Pages
- **Login (`Login.html`)** — Member sign-in form with branded styling
- **Registration (`Registration.html`)** — New user sign-up form with structured field layout

### 📱 Responsive Design
- Mobile-friendly layouts that adapt across screen sizes
- Consistent visual identity maintained at every breakpoint

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Page structure and semantic markup for all six pages |
| **CSS3** | Custom styling, layout, animations, and responsive design |
| **JavaScript** | Interactive UI behaviors and dynamic page elements |

No frameworks. No build tools. Pure web fundamentals — just the way the classics were built.

---

## 🚀 Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Edge, Safari)
- No installs, no dependencies, no build step required

### Running Locally

```bash
# Clone the repository
git clone https://github.com/jpmasangkay/atlus-website-imitation.git
cd atlus-website-imitation
```

Then open `Index.html` in your browser directly, or use a local server for the best experience:

```bash
# Using VS Code Live Server extension (recommended)
# Right-click Index.html → "Open with Live Server"

# Or using Python's built-in server
python -m http.server 5500
```

Open [http://localhost:5500](http://localhost:5500) in your browser.

---

## 📁 Project Structure

```
atlus-website-imitation/
├── Images/                   # All image assets (game covers, logos, banners)
├── css/                      # Stylesheets for each page and shared components
├── js/                       # JavaScript files for interactive behavior
├── pages/                    # Additional page assets or partials
├── Index.html                # Home page — hero, featured games, navigation
├── Games.html                # Games catalog page
├── About.html                # Company overview and history
├── Contact.html              # Contact form page
├── Login.html                # User login page
├── Registration.html         # New user registration page
├── .vscode/                  # VS Code workspace settings
├── .gitattributes
└── .gitignore
```

---

## 🧠 How It Works

This is a **pure static multi-page website** — no frameworks, no backend, no bundler.

1. **Page Layout** — Each `.html` file is a self-contained page, linked together through a shared navigation bar. Semantic HTML elements structure the content cleanly throughout.

2. **Styling** — Custom CSS in the `css/` folder handles all visual design: typography, color palette, card layouts, hero sections, and form styling — all aligned with the dark, stylish aesthetic ATLUS is known for.

3. **Interactivity** — Lightweight JavaScript in the `js/` folder powers UI interactions such as navigation toggles, form behavior, and any dynamic visual elements.

4. **Assets** — Game artwork, logos, and banners live in the `Images/` folder and are referenced directly from the HTML pages.

---

## 🎨 Design Inspiration

This project is an imitation of the official **[ATLUS West website](https://atlus.com)** — faithfully recreating its layout, visual tone, and content structure as a front-end development exercise.

> **Disclaimer:** This is a fan-made, non-commercial project created purely for educational and portfolio purposes. All ATLUS branding, game titles, artwork, and trademarks belong to **ATLUS Co., Ltd.**, a subsidiary of Sega. This project is not affiliated with or endorsed by ATLUS in any way.

---

## 👏 Acknowledgements

- Original website design by [ATLUS Co., Ltd.](https://atlus.com)
- Game titles and lore belong to their respective creators at ATLUS
- Built as a front-end development study project
