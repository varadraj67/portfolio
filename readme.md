# 🚀 Varadraj Arun Nalavade - Professional Portfolio

A premium, modern professional portfolio website built with **HTML5**, **Tailwind CSS**, and **Vanilla JavaScript**. Featuring a cutting-edge dark theme with **glassmorphism**, **claymorphism**, smooth interactive animations, and a sleek layout designed for high conversion.

## 📋 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Customization](#-customization)
- [Performance](#-performance)
- [Contact](#-contact)

## ✨ Features

### 🎨 **Premium Aesthetic & UI/UX**
- High-end dark theme incorporating indigo, pink, and violet.
- Stunning **Glassmorphism** and soft **Claymorphism** design elements.
- Fluid, animated ambient background shapes and textures.
- Complex and smooth micro-interactions on hover and scroll.

### 📱 **Revolutionary Mobile Layout**
- True mobile-first approach.
- Top-centered, frosted glass logo (`V.A.N.`).
- **Floating Snackbar Tab Navigation**: A highly interactive, pill-shaped bottom tab bar with animated icons and expanding text tags—just like native mobile apps.
- Fully responsive typography stack and CSS Grid handling for every breakpoint.

### ⚡ **Performance Optimized**
- Zero dependency Vanilla JavaScript.
- Hardware-accelerated CSS animations for buttery smooth transitions.
- Intersection Observers for performant scroll-spying and `slide-in` reveals.

### 🔧 **Key Sections**
1. **Hero Section** - Impactful top introduction featuring stacked headline typography.
2. **About** - Personal details, structured grid, and skill tags.
3. **Skills** - Categorized toolkit cards beautifully encased in frosted glass arrays.
4. **Projects** - Custom featured project cards wrapping live links and descriptions.
5. **Contact** - "Get in Touch" area with clean contact info blocks and form layout.

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic structure and layout |
| **Tailwind CSS** *(via CDN)* | Scalable utility classes |
| **Vanilla CSS** | Advanced animations, glassmorphism filters, and specific structural logic |
| **Vanilla JavaScript** | Scroll-spy behavior, mobile nav effects, and form submission |
| **Font Awesome 6** | Vector iconography |
| **Google Fonts** | `DM Serif Display` (Headings) & `Manrope` / `Outfit` (Body) |

## 📦 Installation

### Quick Start

1. **Clone the Repository**
```bash
git clone https://github.com/varadraj/portfolio.git
cd portfolio
```

2. **Run Locally**
You don't need any build steps! Simply open `index.html` in your browser.
Alternatively, use a local server like `npx serve`, Live Server in VS Code, or python:
```bash
python -m http.server 8000
```

3. **View Portfolio**
- Open `http://localhost:8000`

## 🎨 Customization

### Changing Content
Since this portfolio relies on clean semantic HTML over heavy JavaScript rendering, you can quickly customize content directly inside `index.html`.
- **Bio/Text Details:** Search for natural text blocks inside `<section id="home">`, `<section id="about">`, etc.
- **Project Cards:** Copy and paste the `.project-card` div template to easily add more projects to the Flex/Grid layout.

### Updating Colors
Root color mappings are located directly inside the `<style>` block in `<head>`:
```css
:root {
    --primary: #6366f1;        /* Indigo */
    --primary-dark: #4f46e5;
    --secondary: #ec4899;      /* Pink accent */
    --accent: #8b5cf6;         /* Violet/Purple */
    --dark-bg: #0f172a;        /* Deep Space / Slate background */
    --card-bg: rgba(255, 255, 255, 0.05); /* Base Glass */
}
```

### Modifying Typography
If you want to swap the fonts, update the Google Fonts `<link>` tag and amend the `font-family` references for `.nav-logo`, `body`, and `h1`-`h6`.

## 🎨 Color Scheme

| Color | Hex | Usage |
|---|---|---|
| Indigo (Primary) | `#6366f1` | Vibrant buttons, text highlights, icons |
| Violet (Accent) | `#8b5cf6` | Background gradients, hover boundaries |
| Pink (Secondary) | `#ec4899` | Emphatic text colors and logo gradients |
| Slate (Dark BG)| `#0f172a` | Solid deep space background |
| Slate Text | `#cbd5e1` | General readable subtitle and article text |

## 🔍 Browser Support
- Responsive across Chrome, WebKit (Safari), Firefox, and Microsoft Edge.

## 📝 License
This portfolio is open source. Standard MIT License guidelines apply.

---

**Made with ❤️ by Varadraj Arun Nalavade**

Last Updated: 2026
Portfolio Version: 3.0 (Glass UI & Mobile Tab Concept Overhaul)