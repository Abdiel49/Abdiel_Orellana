<div align="center">

# Abdiel Orellana — Portfolio

**Software Engineer & Tech Lead**

A modern, performant portfolio built with **Nuxt 4**, **Tailwind CSS**, and **Pinia** — statically generated and deployed to **GitHub Pages** via CI/CD.

[![Deploy to GitHub Pages](https://github.com/Abdiel49/Abdiel_Orellana/actions/workflows/deploy.yml/badge.svg)](https://github.com/Abdiel49/Abdiel_Orellana/actions/workflows/deploy.yml)
[![Nuxt](https://img.shields.io/badge/Nuxt-4.x-00DC82?logo=nuxt.js&logoColor=white)](https://nuxt.com)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[**🌐 Live Site**](https://abdiel49.github.io/Abdiel_Orellana/) · [**📄 View CV**](https://drive.google.com/drive/folders/1odYHsboGBk7pVL0V68PgZQopk5ULsxhV?usp=sharing) · [**💼 LinkedIn**](https://linkedin.com/in/abdiel-orellana)

</div>

---

## ✨ Highlights

- 🏗️ **11 production projects** showcased — mobile apps with 10,000+ global users, e-commerce platforms, ERP systems, and more
- 📦 **3 open-source npm packages** published — AI specification suites, calendar utilities, and email validators
- ✍️ **Technical articles** on Dev.to covering AI-native development, Cloudflare email routing, and more
- 🎨 **Dark-themed editorial design** with ambient gradients, glassmorphism cards, and smooth animations
- ⚡ **Statically generated** (SSG) for blazing-fast load times and perfect SEO
- 🤖 **Automated CI/CD** — every push to `main` triggers build and deployment to GitHub Pages

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | [Nuxt 4](https://nuxt.com) (Vue 3 + SSG via `nuxt generate`) |
| **Styling** | [Tailwind CSS 3](https://tailwindcss.com) with custom dark theme system |
| **State Management** | [Pinia](https://pinia.vuejs.org) |
| **UI Components** | [Headless UI](https://headlessui.com/vue) (accessible modals, transitions) |
| **Icons** | [@nuxt/icon](https://nuxt.com/modules/icon) (Heroicons, Logos, MDI) |
| **Language** | TypeScript (strict mode) |
| **Deployment** | GitHub Pages with GitHub Actions CI/CD |
| **Rendering** | Static Site Generation (SSG) via `github-pages` Nitro preset |

---

## 📁 Project Structure

```
├── .github/workflows/
│   └── deploy.yml          # CI/CD pipeline for GitHub Pages
├── assets/css/
│   └── main.css            # Global styles & custom utilities
├── components/
│   ├── HeroSection.vue     # Landing hero with architecture spec card
│   ├── ExperienceTimeline.vue
│   ├── ProjectCard.vue     # Project grid cards
│   ├── ProjectModal.vue    # Detailed project view with gallery
│   ├── ArticleCard.vue     # Dev.to article cards
│   ├── PackageCard.vue     # npm package cards with download stats
│   ├── TechBadge.vue       # Reusable technology badges
│   ├── TheNavbar.vue       # Sticky navigation
│   └── TheFooter.vue       # Footer with social links
├── composables/
│   ├── useArticles.ts      # Dev.to articles data composable
│   ├── usePackages.ts      # npm packages data composable
│   └── useAssetPath.ts     # Asset path resolution for GitHub Pages
├── constants/
│   └── index.ts            # External links & contact info
├── data/
│   ├── articles.ts         # Blog post entries
│   ├── experience.ts       # Work experience timeline
│   ├── packages.ts         # Published npm packages
│   └── projects.ts         # Featured project showcase
├── layouts/
│   └── default.vue         # Default app layout
├── pages/
│   └── index.vue           # Single-page portfolio (all sections)
├── public/images/          # Project screenshots & gallery assets
├── stores/
│   └── portfolio.ts        # Pinia store for project selection state
├── types/
│   └── index.ts            # TypeScript interfaces (Project, Experience, Article, NpmPackage)
├── nuxt.config.ts          # Nuxt configuration (SSG, modules, base URL)
└── tailwind.config.ts      # Custom theme (colors, fonts, animations)
```

---

## 🌟 Featured Sections

### 🚀 Projects

Eleven production-grade projects spanning mobile, web, and enterprise systems:

| Project | Description | Tech |
|---|---|---|
| **Racquets App** | Sports management for 10,000+ global users across 11 languages | React Native, Expo, Node.js, Stripe, Firebase |
| **WhoopTrip** | Adventure tour booking with real-time group chat | React Native, Expo, Socket.io, Stripe |
| **ManyMore** | Group buying marketplace with dynamic volume-based pricing | React Native, Expo, Socket.io |
| **Daypass** | Travel accommodation booking with customizable pricing | React Native, Expo, Stripe |
| **ToqueApp** | Social discovery platform with geolocation matching | React Native, Expo, Socket.io |
| **Enjoy Loyalty** | Tiered loyalty & rewards program (Silver/Gold/Platinum) | React Native, Socket.io, OneSignal |
| **Puntos del Sol** | Retail loyalty platform for Grupo del Sol merchant network | React Native, Socket.io, OneSignal |
| **Virbac Club** | Pet nutrition loyalty program with gamified rewards | React Native, Socket.io, OneSignal |
| **SIB Cochabamba** | Local business directory with category search & promotions | React Native, NestJS, PostgreSQL, Docker |
| **Conduce Ya** | Gamified driving exam simulator with offline-first architecture | React Native, PouchDB, WatermelonDB |
| **Digall** | Enterprise ERP for construction material distribution | React Native, Expo, Firebase |

### 📦 Published npm Packages

| Package | Description | Downloads |
|---|---|---|
| [`spec-suite-skill`](https://www.npmjs.com/package/spec-suite-skill) | Technical specs & compliance suite for AI agents and LLM orchestration | ~930/month |
| [`calendar-calculate`](https://www.npmjs.com/package/calendar-calculate) | Lightweight date utility for filtering dates by custom weekday ranges | Published |
| [`is-email-demo`](https://www.npmjs.com/package/is-email-demo) | Email validation & utility helpers with full TypeScript support | Published |

### ✍️ Blog Articles

Published on [Dev.to (@abdiel49)](https://dev.to/abdiel49):

- [**Spec Suite: Putting an End to Hallucinated AI Documentation**](https://dev.to/abdiel49/spec-suite-skill-4bbk) — Why I built a specification framework to eliminate hallucinated context for AI agents
- [**Configure Cloudflare Email Routing with Gmail**](https://dev.to/abdiel49/configure-cloudflare-email-routing-with-gmail-to-send-and-receive-mails-382j) — Complete walkthrough for free custom domain email using Cloudflare + Gmail SMTP

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** ≥ 20
- **npm** (included with Node.js)

### Installation

```bash
# Clone the repository
git clone https://github.com/Abdiel49/Abdiel_Orellana.git
cd Abdiel_Orellana

# Install dependencies
npm install
```

### Development

```bash
# Start the development server at http://localhost:3000
npm run dev
```

### Build & Preview

```bash
# Generate static site
npm run generate

# Preview the production build locally
npm run preview
```

---

## 🚢 Deployment

This project is configured for **automatic deployment to GitHub Pages** using GitHub Actions.

### How It Works

1. **Push to `main`** triggers the [`deploy.yml`](.github/workflows/deploy.yml) workflow
2. **Build step**: Installs dependencies → runs `nuxt generate` (SSG) → outputs static HTML to `.output/public/`
3. **Deploy step**: Uploads the artifact and deploys to GitHub Pages using `actions/deploy-pages@v4`

### Configuration

The `baseURL` in [`nuxt.config.ts`](nuxt.config.ts) is set to `/Abdiel_Orellana/` to match the GitHub repository name:

```ts
app: {
  baseURL: '/Abdiel_Orellana/',
}
```

The Nitro preset is configured for GitHub Pages:

```ts
nitro: {
  preset: 'github-pages'
}
```

### GitHub Repository Settings

To enable GitHub Pages deployment, ensure the following in your repository settings:

1. Go to **Settings → Pages**
2. Set **Source** to **GitHub Actions**

---

## 🎨 Design System

The portfolio uses a custom dark theme defined in [`tailwind.config.ts`](tailwind.config.ts):

| Token | Value | Usage |
|---|---|---|
| `brand` | `#3b82f6` (Electric Blue) | Primary accent, CTAs, highlights |
| `dark-bg` | `#0f172a` (Slate 900) | Main background |
| `dark-surface` | `#1e293b` (Slate 800) | Cards, elevated surfaces |
| `dark-card` | `#111827` (Gray 900) | Terminal/spec cards |
| `dark-text` | `#f8fafc` (Slate 50) | Primary text |
| `dark-muted` | `#94a3b8` (Slate 400) | Secondary text |

Custom animations: `fade-in` and `slide-up` for smooth section transitions.

Typography: [Inter](https://fonts.google.com/specimen/Inter) font family.

---

## 📬 Contact

- **Email**: [abdielorellana3@gmail.com](mailto:abdielorellana3@gmail.com)
- **LinkedIn**: [linkedin.com/in/abdiel-orellana](https://linkedin.com/in/abdiel-orellana)
- **GitHub**: [github.com/Abdiel49](https://github.com/Abdiel49)
- **Dev.to**: [dev.to/abdiel49](https://dev.to/abdiel49)
- **npm**: [npmjs.com/~abdiel49](https://www.npmjs.com/~abdiel49)

---
