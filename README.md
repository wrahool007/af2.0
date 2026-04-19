# Algorithmic Fairness 2.0
### Empowering Users to Recognize, Interrupt, and Reshape Recommendation Systems

[![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-View%20Now-4ECDC4?style=for-the-badge)](https://wrahool007.github.io/af2.0/)
[![MSc Project](https://img.shields.io/badge/MSc%20Thesis-Northeastern%20University%20Vancouver-0090B8?style=for-the-badge)](https://northeastern.edu)
[![Year](https://img.shields.io/badge/Year-2026-C07820?style=for-the-badge)](#)

---

## Overview

**Algorithmic Fairness 2.0** is an MSc thesis project in Information Design & Data Visualization at Northeastern University Vancouver (2026). It addresses a fundamental problem in digital life: YouTube's recommendation algorithm optimizes entirely for watch time rather than user wellbeing, silently trapping users in self-reinforcing echo chambers.

This project intervenes through a **12-day structured diary study** with four occupation-based personas, measuring whether structured self-reflection alone — without any technical tools, browser extensions, or platform setting changes — can produce measurable, lasting algorithmic empowerment.

> **Key finding:** Average mood improved by +1.9 points (1–5 scale) across all participants. All four echo chambers were disrupted. No tools. No settings changes. Only self-reflection.

---

## Live Interactive Dashboard

🔗 **[wrahool007.github.io/af2.0/](https://wrahool007.github.io/af2.0/)**

The dashboard contains 10 interactive screens:

| Tab | Visualization |
|-----|---------------|
| **Overview** | Study metrics, 4-step framework, data distribution donut |
| **Wellbeing Arc** | 12-day mood & agency line charts for all 4 personas |
| **Word Universe** | Interactive word cloud + word diversity across sections |
| **Theme Sunburst** | Radial bar chart (persona → section → theme hierarchy) |
| **Journey Flow** | Sankey diagram: all personas through sections → outcomes |
| **Word Network** | Term co-occurrence network per persona |
| **Theme Heat Map** | 6 themes × 12 days intensity heatmap |
| **Section Deep Dive** | Per-section grouped bar charts of theme scores |
| **Empowerment Radar** | Final state comparison across 5 empowerment dimensions |
| **Closing Reflection** | 5 post-study reflection questions + scores |

---

## Study Design

### Participant Personas

Four occupation-based archetypes, each representing a different form of algorithmic entrapment:

| Persona | Domain | Echo Chamber → Journey |
|---------|--------|------------------------|
| 👨‍🍳 **Chef** | Food & Culinary Arts | Western cuisine loop → Global cuisine |
| 💻 **IT Student** | Software & Technology | Python/DSA productivity loop → UX & ethics |
| 🎸 **Musician** | Music & Performing Arts | Single-genre guitar silo → World music |
| 📰 **News Reader** | Media & Current Affairs | Outrage loop → Balanced, diverse news |

### 4-Step Empowerment Framework

```
Section I   (Days 1–3)   →  Recognize the Bias
Section II  (Days 4–6)   →  Break the Loop
Section III (Days 7–9)   →  Diversify Your Feed      ★ Highest impact
Section IV  (Days 10–12) →  Build Digital Awareness
```

### Data Collection

- **308 total diary entries** — 6 structured questions per day per persona
- **12-day study duration**
- **4 participant personas**
- Each entry coded across **6 themes** on a 0–9 scale

---

## Six Coded Themes

| Theme | Description | Direction |
|-------|-------------|-----------|
| 🔴 **Echo Chamber** | Repetitive, narrow content — same creators every session | ↓ Positive when decreasing |
| 🟠 **Absence & Bias** | Voices & genres systematically excluded by the algorithm | ↓ Positive when decreasing |
| 🟢 **Agency & Control** | Intentional, self-directed viewing session | ↑ Positive when increasing |
| 🔵 **Algorithm Signal** | Autoplay driving viewing without user intent | ↓ Positive when decreasing |
| 🟣 **Discovery** | New creators & genres encountered beyond prior history | ↑ Positive when increasing |
| 🟡 **Emotional Impact** | Effect on mood, anxiety & sense of autonomy | ↑ Positive when increasing |

---

## Key Findings

| Metric | Result |
|--------|--------|
| Average mood gain | **+1.9 pts** (1–5 scale) |
| Musician mood gain | **+2.3** (fastest) |
| News Reader mood gain | **+1.4** (slowest, but highest Days 10–12 rise) |
| Average agency gain | **+3.0 pts** (1–5 scale) |
| Highest-impact section | **Section III — Diversify Your Feed** |
| Technical tools required | **Zero** |
| Echo chambers disrupted | **4 of 4** |

**Core insight:** Awareness consistently precedes control. Participants who could name their algorithmic experience were substantially better positioned to change it.

---

## Analysis Methods

```
TF-IDF Term Extraction      →  Top terms per persona per section
Theme Coding (0–9)          →  6 dimensions coded from diary entries
Sentiment Analysis          →  Emotional valence trajectory
Latent Semantic Analysis    →  Conceptual relationship mapping
Co-occurrence Network        →  Term relationship visualization
```

---

## Tech Stack

### Dashboard
| Technology | Use |
|------------|-----|
| **HTML5 / CSS3** | Structure & layout |
| **Chart.js 4.4** | Line, bar, radar, polar area, doughnut charts |
| **D3.js 7** | Sunburst, Sankey (journey flow), word network |
| **Vanilla JavaScript** | Navigation, state, interactions |

### Typography & Design
- **Playfair Display** — headings, display text
- **Outfit** — body, labels, UI elements
- **JetBrains Mono** — data, code, metrics
- Background: `#080C14` | Accent: `#4ECDC4`

---

## Repository Structure

```
af2.0/
├── index.html              ← Main interactive dashboard (single file)
├── README.md               ← This file
└── assets/                 ← (optional) images, poster exports
```

> The entire dashboard is a **single self-contained HTML file** — no build step, no dependencies to install, no server required. Open `index.html` in any modern browser.

---

## Running Locally

```bash
# Clone the repository
git clone https://github.com/wrahool007/af2.0.git
cd af2.0

# Open in browser (no server needed)
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or simply visit the live version at **[wrahool007.github.io/af2.0/](https://wrahool007.github.io/af2.0/)**

---

## Theoretical Framework

This work sits at the intersection of three fields:

- **UX Research Methodology** — diary study design, persona construction, qualitative coding
- **Data Visualization** — information design as an empowerment tool (Giorgia Lupi, Tufte 2001)
- **Digital Wellbeing** — filter bubble theory, algorithmic accountability

Key references: Muller & Druin (2012), Miles & Huberman (1994), Tufte (2001).

---

## Abstract

YouTube's recommendation algorithm serves over 2 billion users daily, optimising for watch time rather than wellbeing — trapping users in self-reinforcing echo chambers. Algorithmic Fairness 2.0 addresses this through a 12-day diary study with four personas — Chef, IT Student, Musician, and News Reader — following a 4-step framework: Recognize the Bias, Break the Loop, Diversify Your Feed, and Build Digital Awareness. Responses were analysed using TF-IDF, theme coding, sentiment analysis, and co-occurrence mapping across 308 data points. Mood improved by 1.9 points. Echo chambers were disrupted — no tools, no settings changes, only self-reflection — positioning information design as an active agent of behavioural change.

---

## Author

**Rahul Kharel**
MSc Information Design & Data Visualization
Northeastern University Vancouver · Class of 2026

---

## License

This project is submitted as an academic thesis. All content, visualizations, and data are original work by the author. Please cite appropriately if referencing this research.

```
Kharel, R. (2026). Algorithmic Fairness 2.0: Empowering Users to Recognize,
Interrupt, and Reshape Recommendation Systems. MSc Thesis, Northeastern
University Vancouver.
```
