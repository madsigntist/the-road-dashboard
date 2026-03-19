# The Road — Dashboard

A single-page dashboard that provides a visual overview of **The Road**, a 16-project JavaScript learning curriculum spanning vanilla JS, browser APIs, React, and Next.js.

![HTML](https://img.shields.io/badge/HTML-semantic-blue) ![CSS](https://img.shields.io/badge/CSS-BEM%20%2B%20custom%20properties-blue) ![JS](https://img.shields.io/badge/JavaScript-vanilla-yellow)

## Features

- **Project Roadmap tab** — All 16 projects displayed as cards, grouped by level with color-coded accents:
  - **Level 1** — Core JS + DOM + Semantic HTML/CSS (5 projects)
  - **Level 2** — Browser APIs + Async/Await + Real UI Patterns (6 projects)
  - **Level 3** — React Fundamentals (2 projects)
  - **Level 4** — Next.js (2 projects)
  - **Bonus** — Experimental APIs (1 project)
- **Concept → Project Mapping** — Quick-reference showing which concepts are covered by which projects.
- **Learning Framework tab** — Collapsible accordion displaying the full 10-step teaching framework:
  - Learning Objectives, Semantic HTML, BEM CSS, JS explanations, Readiness Quiz, Remediation, and Extensions.
- **Rules grid** — All 11 project generation rules at a glance.

## Screenshot

Open `the-road.html` in a browser to view the dashboard.

## Project Structure

```
the-road-dashboard/
├── the-road.html   ← Full dashboard (HTML + CSS + JS, self-contained)
└── README.md
```

## Getting Started

No build tools or dependencies — just open the HTML file in a browser.

```bash
# Clone the repo
git clone https://github.com/madsigntist/the-road-dashboard.git

# Open in browser
cd the-road-dashboard
start the-road.html       # Windows
open the-road.html        # macOS
xdg-open the-road.html    # Linux
```

## Related

- [Data Types Playground](https://github.com/madsigntist/data-types-playground) — Project 01 from the roadmap.

## Built With

- Vanilla JavaScript
- Semantic HTML
- CSS custom properties + BEM naming + dark theme

## License

This is a personal learning project. Feel free to use it as a reference.
