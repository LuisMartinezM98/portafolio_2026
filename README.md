<div align="center">
  <img src="https://img.shields.io/badge/Astro-BC52EE?logo=astro&logoColor=fff&style=for-the-badge" alt="Astro" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwindcss&logoColor=fff&style=for-the-badge" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=for-the-badge" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=fff&style=for-the-badge" alt="Vite" />
</div>

<br />

<div align="center">
  <h1>LUIS.DEV</h1>
  <p><strong>Full Stack Software Engineer — Portfolio</strong></p>
  <p>
    <a href="#-overview">Overview</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#-features">Features</a> •
    <a href="#-getting-started">Getting Started</a> •
    <a href="#-project-structure">Structure</a>
  </p>

  <br />

  <a href="https://luismartinez.dev">🌐 Live Demo</a>
  &nbsp;·&nbsp;
  <a href="mailto:luiizmartinez@gmail.com">✉️ Contact</a>
</div>

<br />

---

## 🧭 Overview

Personal portfolio built with **Astro** and **Tailwind CSS v4**. Designed as a high-performance, SEO-optimized landing page to showcase professional experience, technical skills, and project work — all delivered with zero JavaScript overhead on initial load.

> **Stack:** Astro 6 · Tailwind CSS 4 · TypeScript · Vite

---

## 🛠️ Tech Stack

<table>
  <tr>
    <th>Category</th>
    <th>Technologies</th>
  </tr>
  <tr>
    <td><strong>Framework</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Astro_6-BC52EE?logo=astro&logoColor=fff&style=flat-square" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=flat-square" />
      <img src="https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=fff&style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>Styling</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Tailwind_CSS_4-38B2AC?logo=tailwindcss&logoColor=fff&style=flat-square" />
      <img src="https://img.shields.io/badge/Geist-000?logo=googlefonts&logoColor=fff&style=flat-square" />
      <img src="https://img.shields.io/badge/Inter-000?logo=googlefonts&logoColor=fff&style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>Icons</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Material_Symbols-4285F4?logo=materialdesignicons&logoColor=fff&style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>SEO</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Open_Graph-000?logo=openstreetmap&logoColor=fff&style=flat-square" />
      <img src="https://img.shields.io/badge/JSON--LD-000?logo=json&logoColor=fff&style=flat-square" />
      <img src="https://img.shields.io/badge/Twitter_Cards-1DA1F2?logo=x&logoColor=fff&style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>Dev Tools</strong></td>
    <td>
      <img src="https://img.shields.io/badge/VS_Code-007ACC?logo=visualstudiocode&logoColor=fff&style=flat-square" />
      <img src="https://img.shields.io/badge/Node_22-339933?logo=nodedotjs&logoColor=fff&style=flat-square" />
      <img src="https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=fff&style=flat-square" />
    </td>
  </tr>
</table>

---

## ✨ Features

- **⚡ Blazing Fast** — 100% static output, zero JS overhead by default
- **🌙 Dark Mode** — Deep minimal aesthetic with custom Material 3-inspired palette
- **📱 Fully Responsive** — Mobile-first layout with glassmorphic cards and smooth animations
- **🎯 Scroll Animations** — IntersectionObserver-powered reveal-on-scroll
- **🔍 SEO Optimized** — Open Graph, Twitter Cards, JSON-LD structured data
- **📄 Resume Download** — One-click PDF download

### Sections

| Section | Description |
|---|---|
| **Hero** | Headline + CTAs with radial glow background |
| **Experience** | Vertical timeline with 4 professional roles |
| **Skills** | Categorized tech stack grid (Languages, Backend, Frontend, Cloud, Testing, AI) |
| **Projects** | 2-column card grid with tech tags & privacy badges |
| **Contact** | Glassmorphic CTA card with email & social links |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/LuisMartinezM98/portafolio-dev.git
cd portafolio-dev

# Install dependencies
npm install

# Start the dev server (http://localhost:4321)
npm run dev

# Build for production
npm run build

# Preview the production build
npm run preview
```

**Requirements:** Node.js >= 22.12.0

---

## 📁 Project Structure

```
.
├── public/                  # Static assets
│   ├── favicon.ico
│   ├── favicon.svg
│   └── Luis_Martinez_Resume_EN.pdf
├── src/
│   ├── components/          # Astro components
│   │   ├── Header.astro     # Nav bar (desktop + mobile)
│   │   ├── Hero.astro       # Landing section
│   │   ├── Experience.astro # Timeline
│   │   ├── Skills.astro     # Tech stack
│   │   ├── Projects.astro   # Project cards
│   │   ├── Contact.astro    # Contact CTA
│   │   └── Footer.astro     # Footer
│   ├── layouts/
│   │   └── Layout.astro     # Root HTML + SEO + fonts
│   ├── pages/
│   │   └── index.astro      # Single-page entry
│   └── styles/
│       └── global.css       # Tailwind + custom theme
├── astro.config.mjs         # Astro configuration
├── tsconfig.json            # Strict TypeScript config
└── package.json
```

---

## 🎨 Design System

A custom dark theme built on Tailwind CSS v4's `@theme` directive:

| Token | Value | Usage |
|---|---|---|
| `--color-background` | `#0A0A0A` | Page background |
| `--color-primary` | `#b4c5ff` | Accent / links |
| `--color-secondary` | `#4edea3` | Secondary accent |
| `--color-surface` | `#131313` | Card surfaces |
| `--font-geist` | `Geist` | Headlines / code |
| `--font-inter` | `Inter` | Body text |

Utilities: `glass-card`, `text-gradient`, `inner-glow`, `section-divider`

---

## 📬 Contact

**Luis Martinez** — Full Stack Software Engineer

- ✉️ [luiizmartinez@gmail.com](mailto:luiizmartinez@gmail.com)
- 🐙 [github.com/LuisMartinezM98](https://github.com/LuisMartinezM98)
- 🔗 [linkedin.com/in/lmartinezm0298/](https://linkedin.com/in/lmartinezm0298/)

---

<div align="center">
  <sub>Built with precision — 2026</sub>
</div>
