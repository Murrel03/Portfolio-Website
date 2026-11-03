# Portfolio Website

Personal portfolio website of **Murrel Miranda** — Full Stack / Backend Developer and MS in Information Systems student at The University of Texas at Arlington.

🔗 **Live site:** https://cozy-griffin-4492da.netlify.app/

## About

A responsive, single-page static portfolio showcasing my background, technical skills, resume, and projects. It is built with plain HTML, CSS, and JavaScript — no build step or framework required.

## Sections

- **Home / Hero** — introduction with a typed-text animation
- **About** — background and education summary
- **Skills** — languages, frameworks, databases, and tools
- **Resume** — education and work experience, with a downloadable resume (`Resume.pdf`)
- **Projects** — portfolio gallery of my work, including:
  - Bottleneck BFF — ML-powered SQL performance optimization
  - Predicting Dog Emotions Using Machine Learning
  - Image Classification — Fashion MNIST
  - Stock Market Analysis Using Time Series
  - Sentiment Analysis on Ukraine–Russia Using R
- **Leadership & Involvement** — extra-curricular activities

## Tech Stack

- **HTML5, CSS3** — custom styling in `style.css`, built on Bootstrap
- **JavaScript** — interactivity in `main.js` and `layout.js`
- **Libraries included in this repo:**
  - AOS — scroll animations
  - Typed.js — hero typed-text effect
  - GLightbox — project image lightbox
  - Swiper — sliders
  - PureCounter & Waypoints — animated counters and scroll triggers

## Project Structure

```
Portfolio-Website/
├── index.html          # Main page (entry point)
├── Main.html           # Earlier version of the main page
├── style.css           # Custom styles
├── main.js / layout.js # Site scripts
├── Resume.pdf          # Downloadable resume
└── *.jpg / *.png       # Profile, background, and project images
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

Deployed as a static site on **Netlify**: https://cozy-griffin-4492da.netlify.app/

## Author

**Murrel Miranda**

- GitHub: [@Murrel03](https://github.com/Murrel03)
- LinkedIn: [murrelmiranda](https://www.linkedin.com/in/murrelmiranda)
- Portfolio: https://cozy-griffin-4492da.netlify.app/
