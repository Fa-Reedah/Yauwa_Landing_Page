# 🎙️ Yauwa — The Voice Ledger You Use Together

> **"Log the sale, tally the stock, and turn every WhatsApp voice note into a balanced book."**

[![Live Demo](https://img.shields.io/badge/Live-Demo-157A76?style=for-the-badge&logo=googlechrome&logoColor=white)](https://Fa-Reedah.github.io/Yauwa_Landing_Page/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-191919?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Fa-Reedah/Yauwa_Landing_Page)
[![Architecture](https://img.shields.io/badge/Architecture-Zero--Dependency%20Vanilla%20Web-EAB308?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/Fa-Reedah/Yauwa_Landing_Page)
[![Design System](https://img.shields.io/badge/Design-Editorial%20Paper%20%26%20Glass-C0392B?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/Fa-Reedah/Yauwa_Landing_Page)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

---

## 📖 Table of Contents

1. [Executive Summary](#-executive-summary)
2. [The Core Philosophy](#-the-core-philosophy)
3. [Key Features & Showcase](#-key-features--showcase)
4. [Visual Design System & Aesthetics](#-visual-design-system--aesthetics)
5. [Cultural Craftsmanship: Bespoke Nigerian Avatars](#-cultural-craftsmanship-bespoke-nigerian-avatars)
6. [Technical Architecture & Engineering](#-technical-architecture--engineering)
7. [Directory Structure](#-directory-structure)
8. [Getting Started & Local Setup](#-getting-started--local-setup)
9. [Deployment Guide](#-deployment-guide)
10. [Accessibility, SEO & Performance](#-accessibility-seo--performance)
11. [Future Roadmap](#-future-roadmap)
12. [Contributing](#-contributing)
13. [License & Acknowledgements](#-license--acknowledgements)

---

## 🌟 Executive Summary

**Yauwa** (*pronounced "Yah-wah"*, from the Hausa exclamation signifying affirmation, agreement, and completeness: *"Exactly! Perfect! All good!"*) is a voice-first, AI-driven shop assistant and collaborative ledger designed specifically for Africa's informal and MSME retail ecosystem.

Across open markets and kiosk clusters in Lagos, Kano, Onitsha, and Kaduna, business moves at lightning speed. Shopkeepers rarely have the time or luxury to sit down at a spreadsheet, key numbers into complex accounting software, or manually write receipts while haggling with customers. Instead, transactions happen through quick handshakes, mobile bank transfers, and **WhatsApp voice notes** sent back and forth between shop owners, apprentices, kiosk managers, and market co-op suppliers.

**Yauwa meets traders where they already live.** By transforming informal voice messages, Pidgin phrasing, and multilingual voice memos into verified double-entry ledgers, automated stock threshold alerts, and shared market restock checklists, Yauwa eliminates unrecorded debts and stock shortages without changing how people naturally work.

This repository houses the **high-converting, editorial-grade product landing page** for Yauwa, built from the ground up with pure, high-performance web standards.

---

## 💡 The Core Philosophy

Traditional fintech and inventory tools fail informal merchants because they demand high digital friction: tedious typing, complex category dropdowns, and rigid forms. 

Yauwa is built around four counter-principles:

```
┌────────────────────────────────────────────────────────────────────────┐
│                        YAUWA PRODUCT PILLARS                           │
├───────────────────┬───────────────────┬────────────────────────────────┤
│ 1. Voice-First    │ 2. Multiplayer    │ 3. Proactive, Not Passive      │
│ Zero typing       │ Shop owners &     │ The system alerts you before   │
│ required; speaks  │ apprentices share │ stock finishes; autonomous     │
│ vernacular/pidgin │ a single live book│ reconciliation of bank alerts  │
└───────────────────┴───────────────────┴────────────────────────────────┘
```

1. **Zero-Friction Voice Logging**: "I don sell two bread to Mr. Akpan, e pay five thousand naira" is parsed instantly into customer attribution, item inventory decrement, cash-vs-transfer tagging, and a balanced daily balance.
2. **Multiplayer Shop Coordination**: Kiosks and retail shops are team operations. Owners, boys (*umu-boy* apprentices), cashiers, and co-op partners interact through group audio streams.
3. **Proactive Threshold Radar**: Rather than waiting for an owner to manually run a stock count, Yauwa tracks inventory velocity and whispers proactive alerts when essential goods are about to run out.
4. **True Multi-Surface Continuity**: From WhatsApp voice messages and native iOS/Android home screen lock widgets to the widescreen desktop Yauwa Studio feed.

---

## 🚀 Key Features & Showcase

The landing page features five interactive showpieces:

### 1. 3D Orbital Phone Mockup Cluster
The hero section showcases a dynamic 4-phone interactive cluster mimicking physical handheld devices running Yauwa:
- **Phone 1 (Center / Primary)**: **Daily Spoken Ledger** — Displays live daily turnover (e.g., `₦42,500`), cash collected vs. bank transfer split, and an unrecorded debt counter.
- **Phone 2 (Left Flank)**: **Threshold Radar** — Displays low-stock alerts (*"Mallam Idris, bread don dey finish o! 3 loaf remain for kiosk"*).
- **Phone 3 (Right Flank)**: **Market Checklist** — Live collaborative restock checklist for market supply runs (Sliced Bread, Cabin Biscuits, Pure Water).
- **Phone 4 (Back Flank)**: **Spoken Sale Recorder** — Real-time audio waveform capture showing transaction processing.
- *Interaction*: Users can **click or tap any phone** to dynamically rotate it into the focal position, cycle through screens via **touch swipe gestures**, or use keyboard navigation (**Space / Enter**).

### 2. Multiplayer WhatsApp Group Simulator
- Recreates a live group chat scenario showing an audio voice note recorded by an apprentice.
- Features an **interactive audio waveform player** with animated equalizer bars (`toggleWaveAnim()`) simulating speech playback.
- Displays the immediate automated response from **Yauwa Ledger Bot**, verifying the transaction and updating shop revenue in real time.

### 3. Autonomous Commerce ("Leave it to Yauwa")
- **Automated Ledger Extraction**: Real-time extraction and categorization into income, credit, and outstanding receivables.
- **Threshold Alerts**: Intelligent early-warning alerts delivered before shelves go empty.

### 4. Native OS Mobile Widgets
- Realistic Apple iOS / Android home screen widget simulation.
- Showcases lock-screen balance tickers (`₦68,400 live revenue`) and a single-touch **"Hold to Speak Sale"** instant microphone trigger.

### 5. Unified Continuity (Yauwa Studio)
- Full desktop studio dashboard preview featuring:
  - Multi-tab management (*Provisions Ledger*, *Stock Thresholds*, *Market Co-op*, *WhatsApp Settings*).
  - Live synced transaction stream with real-time mobile mirror feed.

### 6. Liquid Glass Download Dialog (`.gad`)
- Glassmorphic modal accessible from both header and hero CTA buttons.
- Direct **WhatsApp Bot deep-link** (`wa.me` instant message trigger: *"Hello Yauwa start my book"*).
- Direct app store badges for Apple iOS App Store and Google Play.

---

## 🎨 Visual Design System & Aesthetics

The visual language draws inspiration from high-end editorial aesthetics (such as [wabi.ai](https://wabi.ai), Stripe, and modern print publications), combining tactile warmth with cutting-edge optical effects.

### Color Palette

| Token Name | Hex / Value | Semantic Role & Purpose |
| :--- | :--- | :--- |
| `--canvas` | `#FAF8F3` | Warm archival paper background mimicking artisanal stationery |
| `--paper-pure` | `#FFFFFF` | Elevated card surfaces and floating interface plates |
| `--ink` | `#191919` | High-contrast typography and structural borders |
| `--ink-70` | `rgba(25, 25, 25, 0.70)` | Secondary descriptive and supporting body copy |
| `--teal` | `#157A76` | **Primary Brand Color**: Nigerian emerald / deep tropical teal |
| `--teal-dark` | `#0D5855` | Focused states, active pills, and hover depths |
| `--terracotta` | `#C0392B` | Alert accents, threshold warning badges, and Igbo chieftaincy scarlet |
| `--gold` | `#EAB308` | Revenue highlight indicators, Islamic fula stitches, and Gele weaves |

### Typography Hierarchy

```css
/* Editorial Display Headline Font */
--face-serif: 'LaunchKalice', Kalice, 'Fraunces', ui-serif, Georgia, serif;

/* Ultra-Clean Modern UI Sans-Serif */
--face-sans: 'LaunchSelecta', Selecta, 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
```

### Optical Effects & Motion
- **4-Band Progressive Blur Veil (`.wh-veil`)**: The fixed navigation bar utilizes a layered, masked quad-band backdrop filter (`2px`, `5px`, `9px`, `16px`) creating a smooth, organic dissolve over underlying content without harsh demarcation lines.
- **Micro-Grid Ledger Texture**: A subtle `28px × 28px` grid pattern overlaid on the body canvas simulating traditional accounting paper.
- **Liquid Glass Pills (`.mgb`)**: Dynamic button with a moving specular shine highlight (`--angle-1`, `--angle-2`) driven by modern CSS `@property`.
- **Soft Edge Dissolves**: Progressive alpha gradient masks framing the mobile mockup stage to prevent sharp screen clipping.

---

## 🌍 Cultural Craftsmanship: Bespoke Nigerian Avatars

Embedded directly into the hero headline is an avatar cluster celebrating the diversity, dignity, and entrepreneurial energy of Nigerian commerce across ethnic regions:

```
                       DIVERSE TRADER AVATARS
  ┌─────────────────────────────────────────────────────────────┐
  │ 1. Mallam Idris (Northern Trader - Kano)                   │
  │    • Traditional embroidered Fula / Kufi cap               │
  │    • Terracotta textile with chevron needlework            │
  ├─────────────────────────────────────────────────────────────┤
  │ 2. Iya Oloja (Market Matriarch - Lagos)                    │
  │    • Towering pleated royal teal Gele headwrap             │
  │    • Polished gold filigree ear studs                      │
  ├─────────────────────────────────────────────────────────────┤
  │ 3. Chief Chidi (Commodity Merchant - Onitsha)              │
  │    • Scarlet red wool Ozo chieftaincy cap                  │
  │    • Traditional white eagle feather quill                 │
  ├─────────────────────────────────────────────────────────────┤
  │ 4. Amina (Agri-trader - Kaduna)                            │
  │    • Graceful saffron gold Mayafi / Hijab drape            │
  │    • Intricate headwrap folds with gold piping             │
  └─────────────────────────────────────────────────────────────┘
```

Each avatar is rendered entirely in scalable, vector-precise SVG code with hover and touch states: hovering any trader focuses their portrait while gently dimming the peers.

---

## 🛠️ Technical Architecture & Engineering

### Pure Vanilla Stack
- **HTML5**: Semantic, accessible markup using native `<header>`, `<main>`, `<section>`, `<footer>`, `<dialog>`, and ARIA attributes.
- **CSS3 (Vanilla)**:
  - Custom Properties (`--vars`) for a design token system.
  - `@property` definitions for GPU-interpolated angle animations.
  - CSS Grid & Flexbox with clamp-based fluid scales (`clamp(min, preferred, max)`).
  - Hardware-accelerated 3D transforms (`translate3d`, `rotateY`, `perspective`).
  - Zero Tailwind / Bootstrap dependencies — 100% bespoke CSS.
- **Modern JavaScript (ES6+)**:
  - Modular, zero-dependency state machine managing the 3D phone orbital rotation.
  - Touch-swipe listener calculating horizontal delta thresholds (`diffX > 35px`).
  - Audio waveform simulation with automatic timer reset.
  - Native modal state management with document body scroll-locking.

### Key Performance Characteristics
- **Zero Build Step**: Runs directly in any modern browser without npm, webpack, or vite.
- **Immediate First Contentful Paint (FCP)**: Optimized font preloading for `LaunchKalice` and `LaunchSelecta` fonts with instant fallback to Google Fonts (`Fraunces` & `Inter`).
- **GPU-Layered Animations**: Properties like `transform`, `opacity`, and `filter` are isolated to composite layers using `will-change`.

---

## 📂 Directory Structure

```text
Yauwa_Landing_Page/
├── .git/                      # Git repository version history
├── index.html                 # Complete standalone production landing page
│                              # (Includes CSS design system, SVG assets, and JS logic)
└── README.md                  # Comprehensive technical documentation & guide
```

---

## 💻 Getting Started & Local Setup

Because Yauwa is built without heavy node frameworks, local setup takes under 10 seconds.

### Method 1: Direct Browser Opening
Simply double-click `index.html` or drag it into any modern web browser (Chrome, Edge, Safari, Firefox, Brave).

### Method 2: VS Code Live Server
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and click **"Open with Live Server"**.
4. The site will launch automatically at `http://127.0.0.1:5500`.

### Method 3: Python Built-In HTTP Server
Open your terminal inside the project directory:

```bash
# Python 3.x
python -m http.server 8080
```
Then visit [http://localhost:8080](http://localhost:8080) in your browser.

### Method 4: Node.js / npx serve
```bash
npx serve .
```

---

## 🚀 Deployment Guide

This repository is optimized for instantaneous zero-config deployment on any static hosting provider:

### 1. GitHub Pages (Recommended)
1. Navigate to your repository settings: `https://github.com/Fa-Reedah/Yauwa_Landing_Page/settings/pages`.
2. Under **Build and deployment > Source**, select **Deploy from a branch**.
3. Choose branch: `main`, folder: `/ (root)`.
4. Click **Save**. Your site will be live within 60 seconds at `https://Fa-Reedah.github.io/Yauwa_Landing_Page/`.

### 2. Vercel
```bash
npm i -g vercel
vercel
```

### 3. Netlify
Drag and drop the root folder into [app.netlify.com/drop](https://app.netlify.com/drop) or link the GitHub repo for continuous automatic deployment.

---

## ♿ Accessibility, SEO & Performance

### Accessibility (a11y)
- **High Contrast Ratios**: Deep charcoal (`#191919`) on light archival paper (`#FAF8F3`) satisfies WCAG 2.1 AAA contrast benchmarks.
- **Keyboard Navigation**: The phone mockups and modal can be navigated and activated via keyboard (`Tab`, `Enter`, `Space`, `Escape`).
- **Screen Reader Support**: Decorative SVG elements are marked with `aria-hidden="true"`, while meaningful components feature descriptive `aria-label` tags and interactive roles (`role="region"` / `role="button"`).

### SEO Optimization
- Semantic meta descriptions and Open Graph structure.
- Canonical document hierarchy (`h1` through `h3`) with optimized indexing hooks for retail, AI voice assistants, and West African commerce.

---

## 🗺️ Future Roadmap

- [ ] **Interactive Voice Playback Demo**: Integrate the Web Audio API with real voice recordings in Nigerian Pidgin, Yoruba, Hausa, and Igbo to demonstrate live transcription in the browser.
- [ ] **Live WhatsApp Bot Sandbox**: Embed an interactive playground where prospective users can test typing or uploading real voice notes to see instantaneous JSON ledger output.
- [ ] **PWA Offline Support**: Add a Service Worker (`sw.js`) and Web App Manifest (`manifest.json`) enabling installability as an offline-first progressive web application.
- [ ] **Multi-Currency Converter**: Add dynamic currency toggling (₦ NGN, ₵ GHS, KSh KES, $ USD).

---

## 🤝 Contributing

Contributions are welcomed! To propose enhancements, bug fixes, or new features:

1. **Fork the Repository**:
   ```bash
   git clone https://github.com/Fa-Reedah/Yauwa_Landing_Page.git
   cd Yauwa_Landing_Page
   ```
2. **Create a Feature Branch**:
   ```bash
   git checkout -b feature/revolutionary-feature
   ```
3. **Commit your Changes**:
   ```bash
   git commit -m "feat: add interactive voice memo audio test"
   ```
4. **Push to GitHub**:
   ```bash
   git push origin feature/revolutionary-feature
   ```
5. **Open a Pull Request** describing your changes and testing procedures.

---

## 📄 License & Acknowledgements

- **License**: Distributed under the **MIT License**. See `LICENSE` for details.
- **Typography**: Inspired by the editorial styling of *wabi.ai* and typeset with *LaunchKalice*, *LaunchSelecta*, *Fraunces*, and *Inter*.
- **Crafted with pride** for the hardworking traders, market women, shopkeepers, and merchants building the backbone of African commerce.

---

<p align="center">
  <b>Yauwa, Inc. © 2026 — More of what you want to do. Less of what you have to.</b>
</p>
