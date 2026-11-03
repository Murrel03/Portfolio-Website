# Portfolio Website

Personal portfolio website of **Murrel Miranda** — Full Stack / Backend Developer and MS in Information Systems student at The University of Texas at Arlington.

🔗 **Live site:** https://cozy-griffin-4492da.netlify.app/

## About

A responsive, single-page portfolio with a dark aurora-gradient design. The whole site lives in one self-contained `index.html` (inline CSS + vanilla JavaScript) — no build step, no framework, and no external CSS/JS dependencies except Google Fonts.

## Sections

- **Hero** — introduction with an animated typing effect and key stats (30% faster MongoDB retrieval, 35% SQL improvement, 99.99% uptime, 1,200+ participants)
- **About** — background and story
- **Skills** — Frontend, Backend, Databases, and Cloud & Tools
- **Experience** — timeline: Find Me LLC, Wipro Technologies, Rustomjee Academy
- **Projects** — cards for:
  - AI-First CRM — HCP Module (React, FastAPI, LangGraph)
  - Bottleneck BFF — ML-powered SQL optimization (Python, Streamlit)
  - Bubble Board — Kanban task management (JavaScript)
  - Predicting Dog Emotions Using Machine Learning
  - Image Classification — Fashion MNIST
  - Stock Market Analysis Using Time Series (R)
- **Education & More** — degrees, certifications, leadership & involvement
- **Contact** — email and LinkedIn call-to-action

## Tech Stack

- **HTML5 + CSS3** — custom design system in a single file: CSS variables, gradients, glassmorphism cards, responsive grid layouts
- **Vanilla JavaScript** — typed-text rotator, scroll-reveal animations (IntersectionObserver), mobile navigation
- **Fonts** — Sora + Inter via Google Fonts
- **Images** — my own project artwork from this repo, plus two free-to-use [Pexels](https://www.pexels.com) photos (digital healthcare for the AI-CRM card, Kanban board for Bubble Board)

## Project Structure

```
Portfolio-Website/
├── index.html          # The entire site (entry point)
├── Main.html           # Earlier version of the site (kept for reference)
├── Resume.pdf          # Downloadable resume
├── Murrel_Image.jpg    # Profile photo
└── *.jpg / *.png       # Background and project images
```

## Run Locally

No build step needed. Either:

1. Open `index.html` directly in a browser, or
2. Serve the folder with any static server, for example:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Deployed as a static site on **Netlify**: https://cozy-griffin-4492da.netlify.app/ — pushing to `main` redeploys automatically.

## Author

**Murrel Miranda**

- GitHub: [@Murrel03](https://github.com/Murrel03)
- LinkedIn: [murrelmiranda](https://www.linkedin.com/in/murrelmiranda)
- Portfolio: https://cozy-griffin-4492da.netlify.app/
