<p align="center">
  <img src="https://cdn.synthenis.com/img/synthenisBanner0.png" alt="Synthenis UI Kit" width="100%">
</p>

<p align="center">
  <a href="https://github.com/synthenis/ui-kit/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square&color=3e91ff" alt="MIT License"></a>
  <a href="https://github.com/synthenis/ui-kit/releases"><img src="https://img.shields.io/badge/version-1.0.0-blue?style=flat-square&color=3e91ff" alt="Version"></a>
  <a href="https://cdn.synthenis.com/public/design_kit.html"><img src="https://img.shields.io/badge/demo-live-blue?style=flat-square&color=3e91ff" alt="Live Demo"></a>
  <img src="https://img.shields.io/badge/dependencies-zero-blue?style=flat-square&color=3e91ff" alt="Zero Dependencies">
</p>

<h1 align="center">Synthenis UI Kit</h1>

<p align="center">
  A complete, production-ready design system for building dark-first interfaces.<br>
  Zero dependencies. No build tools required. Drop in and start building.
</p>

---

## Overview

Synthenis UI Kit is the open-source design system powering Synthenis products. It provides a consistent visual language built around dark glassmorphism, the SYN typeface, and a focused set of CSS custom properties that make theming straightforward.

Every component is designed for real use — not generic placeholders. The system prioritizes clarity, accessibility, and consistency without imposing a framework or build pipeline.

## Components

| Component | Description |
|-----------|-------------|
| **Buttons** | Primary, Secondary, Accent, Danger — three sizes + Floating Action Button |
| **Inputs** | Text, Email, Search (icon-prefixed), Textarea |
| **Cards** | Glass surface with icon, body, footer, badge |
| **Toggle** | 32×20px track, 16px thumb, instant state change |
| **Checkbox** | 21×21px, 7px radius, accent fill on checked |
| **Dropdown** | Fixed-position, getBoundingClientRect, outside-click closes |
| **Progress** | Accent fill, shimmer animation, eased width transition |
| **Toast** | Auto-dismiss 10s, deduplication, slide-fade animation |
| **Typography** | SYN typeface, 6-level scale |
| **Design Tokens** | CSS custom properties for colors, surfaces, borders |

## Installation

### CDN

    <!-- Add to <head> -->
    <link rel="preconnect" href="https://cdn.synthenis.com">
    <link rel="stylesheet" href="https://cdn.synthenis.com/ui-kit/v1/synthenis-ui.min.css">

### Clone

    git clone https://github.com/synthenis/ui-kit.git
    cd ui-kit
    open index.html

## Usage

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <link rel="preconnect" href="https://cdn.synthenis.com">
      <link rel="stylesheet" href="https://cdn.synthenis.com/ui-kit/v1/synthenis-ui.min.css">
    </head>
    <body>
      <button class="btn-primary">Get Started</button>
      <button class="btn-secondary">Learn More</button>
      <button class="btn-accent">Confirm</button>
    </body>
    </html>

## Design Tokens

    :root {
      --accent:       #3e91ff;
      --accent-light: #0072de;
      --bg:           #0a0a0a;
      --surface:      rgba(18,18,18,0.6);
      --border:       rgba(255,255,255,0.08);
      --border-hover: rgba(255,255,255,0.15);
      --text:         #ffffff;
      --text-muted:   rgba(255,255,255,0.5);
      --text-dim:     rgba(255,255,255,0.25);
      --ease:         cubic-bezier(0.4,0,0.2,1);
    }

## Typography

The SYN typeface is served from Synthenis CDN and loaded automatically when you include the stylesheet.

    Font stack: 'SYN', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif

| Style | Weight | Size | Tracking |
|-------|--------|------|----------|
| Display | 700 | 40px | -3.5% |
| Section | 700 | 30px | -2.8% |
| Subsection | 600 | 22px | -2% |
| Body | 400 | 15px | — |
| Small | 400 | 13px | — |
| Caption | 700 | 11px | +10% |

## Live Demo

[cdn.synthenis.com/public/design_kit.html](https://cdn.synthenis.com/public/design_kit.html)

## License

MIT — see [LICENSE](./LICENSE) for full terms.

---

<p align="center">
  Built and maintained by <a href="https://synthenis.com">Synthenis</a> · Istanbul, Turkey
</p>
