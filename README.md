# Report: The Perplexity AI Story

An **interactive, single-page research report** on Perplexity AI — from its genesis as an idea to the people behind it, how the product works, its plans and pricing, the competitive arena, its core conflicts, and future outlook. Built as a self-contained, visually rich HTML page with interactive charts.

## Features

- Single-page interactive report (`index.html` — no build step, opens anywhere)
- Dark, modern editorial design with Tailwind CSS via CDN
- Interactive data visualizations powered by Chart.js
- Report sections:
  - **The Genesis of an Idea** — origins and founding story
  - **The Architects** — the team and minds behind Perplexity
  - **How It Works** — product mechanics and technology
  - **Plans & Pricing** — subscription tiers and cost breakdown
  - **The Competitive Arena** — Perplexity vs ChatGPT, Claude, Google Gemini, and others
  - **The Core Conflict** — key tensions and industry debates
  - **Future Outlook** — where Perplexity and AI search go next
- Fully responsive, mobile-friendly layout

## Tech Stack

- HTML5, CSS (Tailwind CSS via CDN)
- JavaScript + Chart.js for interactive charts
- Inter font family via Google Fonts

## Quick Start

No build tools or installation required:

```bash
git clone https://github.com/girishlade111/Report-The-Perplexity-AI-Story.git
cd Report-The-Perplexity-AI-Story
# Just open index.html in your browser:
open index.html   # or double-click it
```

Or serve it locally with Python:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Project Structure

```
├── index.html   # The complete interactive report (styles + charts inline)
└── README.md
```

## Deploy Notes

Static site — deployable anywhere static hosting works. Live demo is hosted on GitHub Pages (repo homepage link).

## Built by

Built by Girish Lade — https://ladestack.in
