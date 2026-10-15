# 🚀 Marsraja — Creative Vision & Scroll Animation Portfolio

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Canvas](https://img.shields.io/badge/Canvas_API-000000?style=for-the-badge&logo=html5&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

<p align="center">
  A premium, interactive personal portfolio website and 300-frame canvas scroll animation experience crafted with pure HTML5, CSS3, and modern Vanilla JavaScript.
</p>

[**Explore Features**](#-key-features) • [**Project Structure**](#-project-structure) • [**Quick Start**](#-quick-start) • [**GitHub Pages**](#-deploy-to-github-pages)

</div>

---

## 🌟 Overview

This repository contains two interconnected creative web experiences:

1. **Portfolio Website (`portpilo web site/`)**: A sleek, dark-themed Creative Director & Product Designer portfolio featuring micro-interactions, scroll reveals, service highlights, a brand ticker, and responsive grid galleries.
2. **Interactive Canvas Scroll Animation (`index.html`)**: A 300-frame sequential canvas visualizer that synchronizes fluid animations directly with the user's scroll progression.

---

## ✨ Key Features

### 🎨 1. Modern Portfolio Website (`portpilo web site/index.html`)
- **Luxury Dark Aesthetic**: Designed with an ultra-deep charcoal backdrop (`#0b0b0b`), high-contrast typography, and a signature warm flame orange accent (`#e8420a`).
- **Dynamic Scroll Progress Indicator**: Real-time progress bar fixed at the top of the viewport tracking scroll depth.
- **Scroll Reveal Animations**: Smooth entry animations driven by `IntersectionObserver` with staggered child element delays.
- **Service Offering Cards**: Clean presentation of core competencies (Brand Strategy, Identity Design, Packaging, and Creative Direction).
- **Infinite Brand Ticker**: Continuous seamless horizontal marquee displaying trusted brand partners.
- **Interactive Work Grid**: Interactive media tiles with hover saturation, scaling, dynamic gradient overlays, and animated metadata labels.
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices.

### 🎞️ 2. 300-Frame Canvas Scroll Animation (`index.html`)
- **Frame-by-Frame Scrubbing**: Renders a 300-frame image sequence (`ezgif-frame-001.jpg` to `ezgif-frame-300.jpg`) directly mapped to page scroll.
- **High Performance (60 FPS)**: Powered by `window.requestAnimationFrame` to ensure stutter-free rendering during rapid scrolling.
- **Adaptive Canvas**: Automatically resizes and preserves frame aspect ratios across varying screen resolutions.
- **Image Preloader**: Loads image frames sequentially into memory for instantaneous response.

---

## 📂 Project Structure

```text
portifilo/
│
├── index.html                   # Interactive 300-frame canvas scroll animation
│
├── portpilo web site/           # Creative Director portfolio website
│   ├── index.html               # Main portfolio page with full styling & interactions
│   ├── WhatsApp Image ...37.jpeg# Hero & featured project visuals
│   └── WhatsApp Image ...38.jpeg# Portfolio project visual asset
│
├── ezgif-73f80200a9bfa22d-jpg/  # Sequence of 300 high-resolution JPG animation frames
│   ├── ezgif-frame-001.jpg
│   ├── ezgif-frame-002.jpg
│   └── ... (up to frame 300)
│
├── .gitignore                   # Ignored temporary build/helper files
└── README.md                    # Project documentation
```

---

## 🚀 Quick Start

No package managers or external dependencies required — run it directly in any modern web browser!

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/24x55a0514-dot/Marsraja.git
   cd Marsraja
   ```

2. **Open in browser:**
   - Double-click `index.html` to experience the **Scroll Animation**.
   - Navigate into `portpilo web site/` and double-click `index.html` to view the **Portfolio Website**.
   - *Or* serve using VS Code Live Server / Python:
     ```bash
     python -m http.server 8000
     ```
     Then navigate to `http://localhost:8000`.

---

## 🌐 Deploy to GitHub Pages

To make this live on the web for free with GitHub Pages:

1. In your GitHub repository, go to **Settings** &rarr; **Pages** (under "Code and automation").
2. Under **Build and deployment** &rarr; **Branch**:
   - Select **`main`** branch and root **`/ (root)`**.
   - Click **Save**.
3. In 1–2 minutes, your website will be live at:
   `https://24x55a0514-dot.github.io/Marsraja/`

---

## 🛠️ Built With

- **HTML5**: Semantic tags, canvas drawing surface, responsive meta viewport.
- **CSS3**: Flexbox, CSS Grid, Custom Properties (Variables), Keyframe animations, Backdrop blur.
- **Vanilla JavaScript**: Canvas 2D Context, `IntersectionObserver` API, `requestAnimationFrame`, event listeners.
- **Google Fonts**: [Outfit](https://fonts.google.com/specimen/Outfit).

---

## 👤 Author

**Rajesh (Marsraja)**
- GitHub: [@24x55a0514-dot](https://github.com/24x55a0514-dot)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — free for personal and commercial creative use.
