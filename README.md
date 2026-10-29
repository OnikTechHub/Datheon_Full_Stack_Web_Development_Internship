<div align="center">

# 🌐 Datheon Full Stack Web Development Internship
### Engineering Capstone & Production Portfolio Showcase

[![Internship Status](https://img.shields.io/badge/Internship_Status-Completed_%26_Audited-059669?style=for-the-badge&logo=checkmarx&logoColor=white)](https://github.com/OnikTechHub/Datheon_Full_Stack_Web_Development_Internship)
[![Cohort](https://img.shields.io/badge/Application_ID-DT--2026--2ENRC-2563eb?style=for-the-badge&logo=id&logoColor=white)](mailto:onikdas.dev@gmail.com)
[![Intern](https://img.shields.io/badge/Intern-Onik_Das-7c3aed?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OnikTechHub)
[![Deployments](https://img.shields.io/badge/Cloud_Deployments-Vercel_Edge-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-amber.svg?style=for-the-badge)](LICENSE)

<p align="center">
  <b>A comprehensive 4-week full-stack web development internship capstone repository demonstrating mastery in semantic web architectures, dynamic client-side state engines, resilient asynchronous REST integrations, and enterprise-grade Next.js React application engineering.</b>
</p>

[**Explore Tasks**](#-complete-task-showcase) • [**Tech Stack Matrix**](#-tech-stack--tools-matrix) • [**Architecture**](#-repository-architecture) • [**Verification Audit**](#-program-completion--verification-audit)

</div>

---

## 📑 Executive Summary & Internship Overview

The **Datheon Full Stack Web Development Internship** is an intensive, production-oriented engineering program structured over 4 progressive milestones. Designed to mirror real-world software engineering workflows, the curriculum immerses candidates in building modular, scalable, and responsive web applications from foundational web primitives to advanced modern frameworks.

```
┌─────────────────────────────────────────────────────────────────────────────────────────────────┐
│                          4-WEEK ENGINEERING PROGRESSION TIMELINE                                │
├──────────────────┬──────────────────┬─────────────────────────────┬─────────────────────────────┤
│      WEEK 1      │      WEEK 2      │           WEEK 3            │           WEEK 4            │
│  Semantic Web    │  Reactive State  │    REST Telemetry & APIs    │ Modern Full-Stack Storefront│
│ & Portfolio Eng. │  & CRUD Systems  │   & Geolocation Services    │  Next.js 15 & React 19 Core │
├──────────────────┼──────────────────┼─────────────────────────────┼─────────────────────────────┤
│ • Semantic HTML5 │ • CRUD Operations│ • Asynchronous Fetch/Await  │ • Next.js 15 App Router     │
│ • Tailwind CSS   │ • LocalStorage   │ • OpenWeatherMap API        │ • Reactive Context State    │
│ • Mobile-First   │ • Search & Filter│ • Geolocation Telemetry     │ • FakeStoreAPI Resilience   │
│ • Performance    │ • UI Analytics   │ • Condition-Based Themes    │ • Checkout Simulation       │
└──────────────────┴──────────────────┴─────────────────────────────┴─────────────────────────────┘
```

### Key Competencies Developed & Validated
- **Semantic & Accessible Architecture**: Crafting structured, accessible, and SEO-friendly document models conforming strictly to modern W3C standards without layout bloat.
- **Client-Side State Persistence**: Structuring reactive state stores synchronized with browser storage APIs (`localStorage`) for real-time reactivity and data survivability.
- **Resilient Asynchronous Networking**: Consuming third-party RESTful APIs with defensive timeout controllers (`AbortController`), runtime fallback models, and granular error-state recovery.
- **Modern Framework Architecture**: Engineering production-grade single- and multi-page web applications utilizing **Next.js (App Router)**, **React 19**, and utility-first styling with **Tailwind CSS**.
- **Continuous Edge Delivery**: Automating continuous integration and zero-configuration production deployments on the **Vercel** edge network.

---

## 🏆 Complete Task Showcase

The following table provides an indexed showcase of all four deliverables completed during the internship, complete with source code paths, technology stacks, and live production endpoints.

| # | Project Name | Directory / Source Code | Primary Tech Stack | Live Production Demo | Status |
| :-: | :--- | :--- | :--- | :--- | :-: |
| **01** | **Developer Portfolio** | [`Developer-Portfolio-Task1/`](./Developer-Portfolio-Task1) | Semantic HTML5, Tailwind CSS, JavaScript (ES6+), FontAwesome | [![Live Demo](https://img.shields.io/badge/Demo-Vercel-black?style=flat-square&logo=vercel)](https://developer-portfolio-delta-steel.vercel.app/) | `Production Ready` |
| **02** | **Taskflow Pro: Dynamic Task Manager** | [`Dynamic-Task-Manager-Productivity-Tracker/`](./Dynamic-Task-Manager-Productivity-Tracker) | HTML5, Tailwind CSS, ES6+ JS, LocalStorage CRUD Engine | [![Live Demo](https://img.shields.io/badge/Demo-Vercel-black?style=flat-square&logo=vercel)](https://taskflow-pro-sigma-neon.vercel.app/) | `Production Ready` |
| **03** | **SkyPulse: Climate & Weather Telemetry** | [`weather-forecast-app/`](./weather-forecast-app) | HTML5, Tailwind CSS, ES6+ JS, OpenWeatherMap API, Geolocation | [![Live Demo](https://img.shields.io/badge/Demo-Vercel-black?style=flat-square&logo=vercel)](https://sky-pulse-weather-swart.vercel.app/) | `Production Ready` |
| **04** | **ZynixCart: Next.js E-Commerce Storefront** | [`ZynixCart/`](./ZynixCart) | Next.js 15, React 19, Tailwind CSS, FakeStoreAPI, Context API | [![Live Demo](https://img.shields.io/badge/Demo-Vercel-black?style=flat-square&logo=vercel)](https://zynix-cart-nine.vercel.app/) | `Production Ready` |

---

## 🔍 Detailed Task Architecture & Milestone Breakdowns

### Task 1: Professional Developer Portfolio
> **Directory**: [`./Developer-Portfolio-Task1`](./Developer-Portfolio-Task1) • **Live URL**: [developer-portfolio-delta-steel.vercel.app](https://developer-portfolio-delta-steel.vercel.app/)

A sleek, responsive, and performance-tuned personal developer portfolio designed with zero third-party UI framework overhead.

```
Developer-Portfolio-Task1/
├── index.html                 # Semantic HTML5 architecture (Header, Sections, Modals)
├── js/main.js                 # Theme engine, scroll spy, modal controller & filter logic
├── assets/                    # Optimized photography, project graphics & resume document
└── vercel.json                # Edge deployment rules & caching headers
```

- **Architectural Highlights**:
  - **100% Tailwind CSS Utility Architecture**: Zero custom external CSS stylesheets; crafted exclusively with utility classes for rapid render cycles and minimal bundle footprint.
  - **Dynamic Theme Engine**: Smooth dark/light theme switching with automatic system OS preference detection (`prefers-color-scheme`) and persistent `localStorage` synchronization.
  - **Interactive Filterable Showcase**: Dynamic category filtering (*All*, *Full Stack*, *AI Platforms*, *Web Apps*) with interactive project deep-dive modal dialogs.
  - **Fluid Scroll Spy Navigation**: Active route tracking linked to window scroll position and fully responsive mobile navigation drawer.
  - **Form Validation & Accessibility**: Accessible form fields with client-side regex validation and user feedback toasts.

---

### Task 2: Dynamic Task Manager & Productivity Tracker
> **Directory**: [`./Dynamic-Task-Manager-Productivity-Tracker`](./Dynamic-Task-Manager-Productivity-Tracker) • **Live URL**: [taskflow-pro-sigma-neon.vercel.app](https://taskflow-pro-sigma-neon.vercel.app/)

A reactive productivity tracking dashboard enabling real-time task lifecycle management and analytical progress monitoring.

```
Dynamic-Task-Manager-Productivity-Tracker/
├── index.html                 # App layout, metric summaries, task submission modal
├── app.js                     # CRUD event handlers, filter pipelines & storage syncer
├── style.css                  # Custom micro-interactions & accent styles
└── vercel.json                # Static routing configuration
```

- **Architectural Highlights**:
  - **Comprehensive CRUD Operations**: Create tasks with title, description, category tag (Work, Personal, Study, Health), priority (Low, Medium, High), and due dates. Edit, toggle completion status, and safely delete with confirmation dialogs.
  - **Persistent LocalStorage Layer**: Encapsulated state persistence pipeline (`saveToLocalStorage()` / `loadFromLocalStorage()`) safeguarding user data across browser reloads.
  - **Dynamic Search & Multi-Criteria Filtering**: Instant tokenized search matching task titles and descriptions in combination with tab filters (*All*, *Active*, *Completed*).
  - **Live Analytical Progress Tracking**: Dynamic summary widgets computing Total, In-Progress, and Completed tasks with a real-time responsive progress completion bar.

---

### Task 3: Real-Time Weather Forecast & Climate Telemetry App
> **Directory**: [`./weather-forecast-app`](./weather-forecast-app) • **Live URL**: [sky-pulse-weather-swart.vercel.app](https://sky-pulse-weather-swart.vercel.app/)

A real-time meteorological intelligence web application consuming the official OpenWeatherMap API, pairing live climate metrics with automated geolocation services.

```
weather-forecast-app/
├── index.html                 # Glassmorphic layout, telemetry widgets, search drawer
├── app.js                     # REST async/await pipeline, geolocation & DOM hydration
├── style.css                  # Custom backdrop-filter blur & ambient atmospheric gradients
└── vercel.json                # Vercel deployment metadata
```

- **Architectural Highlights**:
  - **Dual API REST Integration**: Concurrent asynchronous requests querying OpenWeatherMap `/weather` (current telemetry) and `/forecast` (5-day outlook) endpoints with comprehensive error boundaries.
  - **Hardware Geolocation Telemetry**: One-click device location detection via browser `navigator.geolocation` API mapping precise coordinates to nearest weather stations.
  - **Atmospheric Metric Gauges**: 6-parameter dashboard displaying wind velocity & compass angle, humidity & dew point, barometric pressure (hPa), visibility range, UV index, and sunrise/sunset timestamps.
  - **Dynamic Atmospheric Theming**: UI ambient backgrounds automatically adapt to real-time weather conditions (Clear/Sunny, Thunderstorm, Rain, Snow, Mist/Haze, Night).
  - **Interactive 24-Hour & 5-Day Outlook**: Hourly progression cards and 5-day daily forecast summary cards with instant Celsius (`°C`) and Fahrenheit (`°F`) conversions.

---

### Task 4: ZynixCart — Modern Next.js E-Commerce Storefront
> **Directory**: [`./ZynixCart`](./ZynixCart) • **Live URL**: [zynix-cart-nine.vercel.app](https://zynix-cart-nine.vercel.app/)

A modern, production-grade e-commerce application engineered with **Next.js 15 (App Router)** and **React 19**, featuring a persistent sliding cart drawer, resilient product querying, and a simulated multi-step checkout workflow.

```
ZynixCart/
├── src/
│   ├── app/
│   │   ├── layout.js          # Root layout with Cart & Toast Context Providers
│   │   ├── page.js            # Storefront Home (Hero, Featured, Trending, Trust badges)
│   │   └── products/page.js   # Dedicated Catalog route with search, filter pills & breadcrumbs
│   ├── components/
│   │   ├── Navbar.js          # Sticky header with search, links & reactive cart counter badge
│   │   ├── CartDrawer.js      # Slide-out drawer with free shipping calculator & coupon engine
│   │   ├── CheckoutModal.js   # 2-step order checkout flow with simulated receipt modal
│   │   ├── ProductGrid.js     # Responsive catalog grid with shimmer skeleton loaders
│   │   └── ProductQuickView.js# Interactive product specification quick-view modal
│   ├── context/
│   │   ├── CartContext.js     # Global cart reducer, price calculator & localStorage sync
│   │   └── ToastContext.js    # Non-blocking reactive user notification system
│   └── lib/
│       ├── api.js             # FakeStoreAPI fetch client with timeout & offline fallbacks
│       └── constants.js       # Tax rates, promo codes, shipping brackets & sample data
└── vercel.json                # Next.js deployment configuration
```

- **Architectural Highlights**:
  - **Next.js 15 App Router Architecture**: Multi-page routing structure separating the storefront landing (`/`) from the comprehensive catalog browser (`/products`) with breadcrumb navigation.
  - **Resilient API Layer with Offline Fallbacks**: Asynchronous integration with [FakeStoreAPI](https://fakestoreapi.com/) backed by an `AbortController` timeout safeguard and curated fallback data for guaranteed zero-downtime reliability.
  - **Global Reactive State Management**: Context-driven cart architecture persisting items, quantities, and applied promotional discounts to `localStorage`.
  - **Full Cart Financial Engine**: Real-time evaluation of subtotals, configurable taxes (8%), progressive free-shipping eligibility gauges ($50 threshold), and multi-voucher coupon redemption (`ZYNIX10`, `SAVE20`, `FREESHIP`).
  - **Simulated 2-Step Checkout & Receipt Generator**: Realistic payment processing simulation with credit card/PayPal options, form validation, and instant itemized order confirmation receipts.

---

## 🛠️ Tech Stack & Tools Matrix

A breakdown of the core technologies, frameworks, APIs, and DevOps tooling utilized across the repository:

```
┌─────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                    TECHNOLOGY STACK MATRIX                                      │
├──────────────────────┬──────────────────────────────────────────┬───────────────────────────────┤
│ Domain               │ Technologies / Libraries                 │ Purpose                       │
├──────────────────────┼──────────────────────────────────────────┼───────────────────────────────┤
│ Core Foundations     │ HTML5, CSS3, Modern JavaScript (ES6+)    │ Semantic markup & logic       │
│ UI Frameworks        │ React 19, Next.js 15 (App Router)        │ Component architecture & SSR  │
│ Styling & Aesthetics │ Tailwind CSS, PostCSS, Glassmorphism CSS │ Utility styling & aesthetics  │
│ State & Storage      │ React Context API, Web LocalStorage API  │ Reactive persistent state     │
│ Remote REST APIs     │ OpenWeatherMap API, FakeStoreAPI         │ Live meteorological & catalog │
│ Device APIs          │ HTML5 Geolocation API                    │ Client telemetry & location   │
│ Iconography          │ Lucide React, Lucide Icons, FontAwesome  │ Vector visual indicators      │
│ Tooling & Bundling   │ Node.js, npm, Next.js Compiler           │ Environment & build pipeline  │
│ Cloud & CI/CD        │ Vercel Edge Network, Git, GitHub         │ Automated cloud deployments   │
└──────────────────────┴──────────────────────────────────────────┴───────────────────────────────┘
```

### Detailed Tooling Highlights

- **HTML5 (Semantic & Accessible)**: Employed across all four tasks adhering to accessible W3C standards with structured landmark elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **Tailwind CSS (Utility-First)**: Standardized design tokens, mobile-first responsive breakpoints (`sm`, `md`, `lg`, `xl`), subtle gradients, and dark mode variants.
- **JavaScript (ES6+)**: Extensive implementation of modern syntax standards—destructuring, arrow functions, template literals, optional chaining, array manipulation methods (`map`, `filter`, `reduce`), and asynchronous `Promise`/`async`/`await` patterns.
- **Next.js 15 & React 19**: Modern component lifecycle architectures, client-side boundaries (`"use client"`), and modular layout structuring.
- **OpenWeatherMap 2.5 API**: Real-time meteorological telemetry consumption powering 5-day weather forecasting and atmospheric indices.
- **FakeStoreAPI**: RESTful e-commerce inventory endpoints facilitating real-time product discovery, category segregation, and shopping cart hydration.
- **Vercel Cloud Platform**: Continuous delivery pipelines linking GitHub repository branches directly to distributed global edge nodes with instant atomic rollbacks.

---

## 📁 Repository Architecture

```text
Datheon_Full_Stack_Web_Development_Internship/
│
├── Developer-Portfolio-Task1/                 # [Task 1] Modern Personal Portfolio
│   ├── assets/                                # Profile photos, project screenshots, resume PDF
│   ├── css/                                   # Supplemental stylesheets
│   ├── js/main.js                             # Portfolio dynamic logic & theme handling
│   ├── index.html                             # Semantic HTML5 single-page document
│   ├── README.md                              # Dedicated setup & feature documentation
│   └── vercel.json                            # Vercel deployment parameters
│
├── Dynamic-Task-Manager-Productivity-Tracker/ # [Task 2] Taskflow Pro Productivity App
│   ├── app.js                                 # Task state management & localStorage persistence
│   ├── index.html                             # Task dashboard interface & modals
│   ├── style.css                              # Custom interactive animations & UI polish
│   ├── README.md                              # Task 2 specifications & user guide
│   └── vercel.json                            # Vercel deployment parameters
│
├── weather-forecast-app/                      # [Task 3] SkyPulse Weather & Climate App
│   ├── app.js                                 # OpenWeatherMap API client & dynamic rendering
│   ├── index.html                             # Telemetry widgets & responsive glass UI
│   ├── style.css                              # Atmospheric theme animations & glassmorphism
│   ├── README.md                              # Weather API integration notes & guide
│   └── vercel.json                            # Vercel deployment parameters
│
├── ZynixCart/                                 # [Task 4] Enterprise Next.js E-Commerce
│   ├── src/
│   │   ├── app/                               # Next.js App Router (layout, home, /products)
│   │   ├── components/                        # Modular UI components (Cart, Modal, Grid, Nav)
│   │   ├── context/                           # CartContext & ToastContext global providers
│   │   └── lib/                               # API fetch clients, promo codes & constants
│   ├── public/                                # Public brand assets
│   ├── package.json                           # Next.js & React dependencies
│   ├── tailwind.config.js                     # Tailwind theme customizations
│   ├── README.md                              # Comprehensive store documentation & promo codes
│   └── vercel.json                            # Edge deployment configuration
│
├── LICENSE                                    # Open-source MIT License
└── README.md                                  # Root Master Portfolio Documentation
```

---

## ⚡ Quick Start & Local Setup

To clone and run any of the task projects locally on your development machine:

### 1. Clone the Master Repository
```bash
git clone https://github.com/OnikTechHub/Datheon_Full_Stack_Web_Development_Internship.git
cd Datheon_Full_Stack_Web_Development_Internship
```

### 2. Running Static Projects (Tasks 1, 2, & 3)
Tasks 1, 2, and 3 use native browser web standards and require no build step:
```bash
# Navigate to desired task folder:
cd Developer-Portfolio-Task1
# or: cd Dynamic-Task-Manager-Productivity-Tracker
# or: cd weather-forecast-app

# Launch with any local server:
npx serve .
# or: python -m http.server 3000
```
Open `http://localhost:3000` in your web browser.

### 3. Running Next.js Application (Task 4: ZynixCart)
Task 4 is a modern Next.js project requiring Node.js (v18.17+ or v20+ recommended):
```bash
cd ZynixCart

# Install dependencies
npm install

# Start development server
npm run dev
```
Open `http://localhost:3000` in your web browser.

---

## 📜 Quality Assurance & Verification Standards

All deliverables within this repository were designed and audited against strict quality benchmarks:

| Evaluation Criteria | Implementation Verification |
| :--- | :--- |
| **Responsive Design** | Tested and verified across mobile (375px+), tablet (768px), and high-resolution desktop (1440px+) displays without layout breaks or horizontal overflow. |
| **Code Modularity** | Clean separation of concerns adhering to modular JavaScript, reusable React components, and encapsulated utility styling. |
| **Defensive Networking** | API calls incorporate timeout controllers, try/catch error handling blocks, user-friendly fallback messaging, and offline mock datasets. |
| **State Integrity** | Deterministic state transitions; all critical data modifications safely serialized and validated against schema expectations. |
| **Cross-Browser Parity** | Validated on modern Chromium (Chrome, Edge, Brave), Gecko (Firefox), and WebKit (Safari) rendering engines. |

---

## 👨‍💻 Program Completion & Verification Audit

<div align="center">

```
========================================================================================
                      DATHEON WEB DEVELOPMENT INTERNSHIP AUDIT
========================================================================================
  Intern Name         : Onik Das
  Application ID      : DT-2026-2ENRC
  Role                : Full-Stack Web Development Intern
  Curriculum Scope    : 4-Week Comprehensive Web Engineering Track
  Tasks Completed     : 4 of 4 (100% Milestone Completion)
  Deployment Platform : Vercel Cloud Platform (100% Live & Verified)
  Repository Status   : Production Master - Audited & Finalized
========================================================================================
```

### Connect with the Author

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/onik-das/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OnikTechHub)
[![Portfolio](https://img.shields.io/badge/Portfolio-2563eb?style=for-the-badge&logo=googlechrome&logoColor=white)](https://developer-portfolio-delta-steel.vercel.app/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:onikdas.dev@gmail.com)

**Location**: Chattogram, Bangladesh  
**Portfolio Profile**: [Onik Das (@OnikTechHub)](https://github.com/OnikTechHub)

</div>

---

## 📄 License

This repository and all included projects are released and distributed under the terms of the [MIT License](LICENSE).

<div align="center">
  <sub>Designed & engineered with precision by <strong>Onik Das</strong> for the <strong>Datheon Internship Program</strong>.</sub>
</div>