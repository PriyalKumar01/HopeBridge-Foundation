<div align="center">

<img src="assets/images/logo.png" alt="HopeBridge Foundation Logo" width="120" height="120" style="border-radius:16px"/>

# 🌉 HopeBridge Foundation

### *Building Hope, Empowering Lives*

> "Together we create opportunities through education, healthcare, environmental awareness, and community development."

[![Website](https://img.shields.io/badge/🌐%20Live%20Website-hopebridgefoundation-teal?style=for-the-badge)](https://priyalkumar01.github.io/HopeBridge-Foundation/index.html)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-181717?style=for-the-badge&logo=github)](https://priyalkumar01.github.io/HopeBridge-Foundation/index.html)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## 📋 Table of Contents

- [About the Project](#-about-the-project)
- [Live Demo](#-live-demo)
- [Pages Overview](#-pages-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Programs Covered](#-programs-covered)
- [Color Palette & Design](#-color-palette--design)
- [Getting Started](#-getting-started)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🏛️ About the Project

**HopeBridge Foundation** is a fully responsive, professionally designed NGO website built with pure **HTML, CSS, and Vanilla JavaScript** — no frameworks, no dependencies. The website represents a non-profit organization committed to improving lives through education, healthcare, skill development, environmental conservation, and humanitarian support.

This project was built as a complete, production-ready multi-page website featuring:

- 🎨 Premium design with a curated **Teal + Gold** color palette
- ✨ Smooth scroll-triggered animations and micro-interactions
- 📱 Fully **responsive** across all screen sizes
- 🖼️ AI-generated imagery for all sections
- 📬 Interactive forms with toast notifications
- 🗺️ Google Maps integration on the Contact page
- 🔢 Animated statistics counters
- 🌟 Floating particle hero section

---

## 🌐 Live Demo

> 🔗 **[https://priyalkumar01.github.io/HopeBridge-Foundation/index.html](https://priyalkumar01.github.io/HopeBridge-Foundation/index.html)**

---

## 📄 Pages Overview

| Page | URL | Description |
|------|-----|-------------|
| 🏠 **Home** | `/index.html` | Hero section, about preview, programs, stats, volunteer CTA, gallery preview, testimonials, donate banner |
| ℹ️ **About** | `/about.html` | Foundation story, mission/vision/values, team members |
| 📋 **Programs** | `/programs.html` | Detailed view of all 5 program areas |
| 🤝 **Volunteer** | `/volunteer.html` | Why volunteer, statistics, full registration form |
| ❤️ **Donate** | `/donate.html` | Donation amounts, impact breakdown, trust badges, form |
| 🖼️ **Gallery** | `/gallery.html` | Filterable image gallery with lightbox viewer |
| 💬 **Testimonials** | `/testimonials.html` | Volunteer, beneficiary & donor stories + story submission form |
| 📞 **Contact** | `/contact.html` | Contact info, Google Maps embed, contact form, FAQ section |

---

## ✨ Features

### 🎯 Core Features
- **Multi-page architecture** — 8 fully connected HTML pages
- **Fixed navbar** that transforms on scroll (transparent → solid with blur)
- **Mobile hamburger menu** with smooth slide animation
- **Scroll-to-top** floating button
- **Active nav link** detection based on current page
- **Toast notifications** on all form submissions

### 🎬 Animations & Interactions
- **Animated particle hero** — 25 floating gold particles over a cinematic banner
- **Intersection Observer** based fade-up/fade-in animations on scroll
- **Counter animation** — numbers count up from 0 when scrolled into view (15,000+ Beneficiaries, 300+ Volunteers, 75+ Campaigns, 20+ Cities)
- **Hero entrance animation** — staggered reveal on page load
- **Hover micro-animations** on cards, buttons, nav links

### 🖼️ Gallery
- **Category filter buttons** — All / Education / Plantation / Medical / Community / Women / Animals
- **Lightbox viewer** — click any image to view full-screen with smooth open/close
- **Hover overlay** with title and location label

### 💳 Donate Page
- **Amount selector** — preset buttons (₹500, ₹1000, ₹2500, ₹5000, ₹10,000, Custom)
- **Impact cards** — shows what each donation amount accomplishes
- **Trust badges** — 80G Tax benefit, Secure, Transparent, FCRA Registered

### 📬 Forms
- Volunteer Registration Form
- Donation Form
- Contact Form
- Testimonial Submission Form
- All forms have **visual success feedback** and reset after submission

### 📱 Responsive Design
- Fully responsive from **320px to 1600px+**
- Mobile-first media queries at 480px, 768px, 1024px
- Collapsible mobile nav drawer
- Grid layouts adapt from multi-column to single-column

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic page structure, SEO meta tags |
| **CSS3** | Custom properties (variables), Flexbox, CSS Grid, Animations, Media Queries |
| **Vanilla JavaScript** | DOM manipulation, Intersection Observer API, scroll events, form handling |
| **Google Fonts** | Playfair Display, Inter, Cormorant Garamond |
| **Google Maps Embed** | Location map on Contact page |
| **GitHub Pages** | Static site hosting |

> ⚡ **Zero dependencies** — No npm, no build tools, no frameworks required.

---

## 📁 Project Structure

```
HopeBridge-Foundation/
│
├── 📄 index.html               # Homepage
├── 📄 about.html               # About Us page
├── 📄 programs.html            # Our Programs page
├── 📄 volunteer.html           # Volunteer page
├── 📄 donate.html              # Donate page
├── 📄 gallery.html             # Gallery page
├── 📄 testimonials.html        # Testimonials page
├── 📄 contact.html             # Contact page
│
└── 📁 assets/
    ├── 📁 css/
    │   └── style.css           # Main stylesheet (~950 lines)
    │                           # — CSS variables / design tokens
    │                           # — Component styles (navbar, hero, cards, forms)
    │                           # — Utility classes (.btn, .container, .section-pad)
    │                           # — Animations (fade-up, fade-in, particles)
    │                           # — Responsive breakpoints
    │
    ├── 📁 js/
    │   └── main.js             # Main JavaScript file
    │                           # — Navbar scroll behavior
    │                           # — Particle system generation
    │                           # — Counter animation (IntersectionObserver)
    │                           # — Scroll-triggered animations
    │                           # — Mobile nav toggle
    │                           # — Lightbox open/close
    │                           # — Form submission handlers
    │                           # — Toast notification system
    │                           # — Amount selector (donate page)
    │
    └── 📁 images/
        ├── logo.png            # Foundation logo (AI-generated)
        ├── hero_banner.png     # Hero section background
        ├── about_team.png      # About page team photo
        ├── gallery_education.png
        ├── gallery_plantation.png
        ├── gallery_medical.png
        ├── gallery_community.png
        ├── gallery_women.png
        ├── gallery_animals.png
        ├── volunteer_sarah.png # Testimonial avatar 1
        ├── volunteer_rahul.png # Testimonial avatar 2
        └── volunteer_priya.png # Testimonial avatar 3
```

---

## 🌟 Programs Covered

| Program | Description | Key Activities |
|---------|-------------|----------------|
| 📚 **Education Support** | Bridging the education gap | Scholarships, Digital literacy centers, Free tutoring, Dropout prevention |
| 🌱 **Environment** | Green Earth initiatives | Tree plantation (10,000+ trees), Clean-up drives, Awareness campaigns |
| ❤️ **Healthcare** | Free medical access | Rural medical camps, Blood donation drives, Mental health workshops, Medicine distribution |
| 👩 **Women Empowerment** | Skill & independence | Vocational training, Entrepreneurship, Legal awareness, Mentorship network |
| 🐶 **Animal Welfare** | Compassion for animals | Feeding drives, Rescue operations, Vaccination camps, Adoption drives |

---

## 🎨 Color Palette & Design

### Brand Colors

| Color | Hex | Usage |
|-------|-----|-------|
| **Teal Dark** | `#084f4f` | Primary dark, backgrounds |
| **Teal** | `#0d6e6e` | Primary color, buttons, accents |
| **Teal Light** | `#1a9090` | Hover states, gradients |
| **Gold** | `#c9a84c` | Accent, highlights, CTAs |
| **Gold Light** | `#e8c97a` | Gold hover, hero headings |
| **Gold Dark** | `#a07832` | Gold text, borders |
| **Cream** | `#faf7f0` | Section backgrounds |
| **Text Dark** | `#1a1a2e` | Headings |

### Typography

| Font | Weight | Usage |
|------|--------|-------|
| **Playfair Display** | 400–800 | All headings (h1–h4) |
| **Inter** | 300–700 | Body text, labels, buttons, UI |
| **Cormorant Garamond** | 400 Italic | Pull quotes, testimonials |

### Design System
- **Border radius:** `12px` (cards) / `20px` (large panels) / `50px` (pills/buttons)
- **Shadows:** 3-tier — `shadow-sm`, `shadow-md`, `shadow-lg`
- **Transitions:** `all 0.35s cubic-bezier(0.4, 0, 0.2, 1)` throughout

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- No Node.js, npm, or build tools needed!

### Run Locally

```bash
# Clone the repository
git clone https://github.com/PriyalKumar01/HopeBridge-Foundation.git

# Navigate into the project
cd HopeBridge-Foundation

# Open directly in browser
# Option 1: Double-click index.html
# Option 2: Use VS Code Live Server extension
# Option 3: Use Python's built-in server
python -m http.server 8000
# then open http://localhost:8000
```

---

## 🌍 Deployment

This site is deployed via **GitHub Pages** — zero configuration required.

### Steps to deploy your own fork:
1. Fork this repository
2. Go to **Settings → Pages**
3. Set Source to `main` branch, `/ (root)` folder
4. Click **Save**
5. Your site will be live at `https://<your-username>.github.io/HopeBridge-Foundation/`

---

## 📊 Page Statistics

| Metric | Value |
|--------|-------|
| Total Pages | 8 |
| Total Files | 22 |
| CSS Lines | ~950 |
| JS Lines | ~120 |
| Images | 12 AI-generated |
| Dependencies | 0 |
| Frameworks | 0 |
| Load Time | < 2s |

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

```bash
# Fork the repo
# Create a feature branch
git checkout -b feature/your-feature-name

# Commit your changes
git commit -m "add: your feature description"

# Push and open a Pull Request
git push origin feature/your-feature-name
```

Please keep code clean, semantic, and consistent with the existing design system.

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute.

---

## 📞 Contact

**HopeBridge Foundation**

- 🌐 Website: [hopebridgefoundation.org](https://priyalkumar01.github.io/HopeBridge-Foundation/index.html)
- 📧 Email: info@hopebridgefoundation.org
- 📞 Phone: +91 12345 67890
- 📍 Location: 42, Hope Street, Connaught Place, New Delhi — 110001
- 🤝 Volunteer: [volunteer.html](https://priyalkumar01.github.io/HopeBridge-Foundation/volunteer.html)
- ❤️ Donate: [donate.html](https://priyalkumar01.github.io/HopeBridge-Foundation/donate.html)

---

<div align="center">

**Made with ❤️ for a better world**

*HopeBridge Foundation — Building Hope, Empowering Lives since 2015*

⭐ If you find this project helpful, please consider giving it a **star** on GitHub!

</div>
