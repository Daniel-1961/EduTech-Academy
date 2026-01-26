# EduTech Academy

A simple, responsive static website for EduTech Academy showcasing the landing page, courses, about, and contact pages. Built with plain HTML and CSS — ideal for learning, customization, and quick deployment (including GitHub Pages).

Repository: [EduTech-Academy](https://github.com/Daniel-1961/EduTech-Academy)

## Project overview
This repository contains a small static site intended as a template or demo for an online learning platform. It's lightweight and easy to modify for personal or teaching use.

## Features
- Clean, semantic HTML structure
- Centralized styling via `style.css`
- Pages included for:
  - Home / Landing (`index.html`)
  - Courses (`courses.html`)
  - About (`about.html`)
  - Contact (`contact.html`)
- Mobile-friendly layout and simple navigation

## Repository structure
- index.html — Home / landing page
- about.html — Information about the academy
- courses.html — Course listings and details
- contact.html — Contact form / information
- style.css — Global styles for the site
- README.md — This file

## Preview locally
Option 1 — open in your browser:
- Double-click `index.html` or right-click → Open With → your browser.

Option 2 — use a simple local HTTP server (recommended for consistent behavior):
- Python 3:
  - Run `python -m http.server 8000` in the repository root, then open http://localhost:8000
- Node (http-server):
  - Install: `npm install -g http-server`
  - Run: `http-server -p 8000` and open http://localhost:8000

Option 3 — use VS Code Live Server extension for one-click preview.

## Deployment
- Deploy as a static site (e.g., GitHub Pages, Netlify, Vercel).
- For GitHub Pages, publish the `main` branch in repository settings or enable Pages for the `docs/` folder if you move files.

## How to customize
- Edit HTML files to change content and page structure.
- Update `style.css` to adjust layout, colors, fonts, and responsive behavior.
- Add assets (images, fonts) in a new `assets/` or `images/` folder and reference them from HTML/CSS.

## Contributing
Contributions are welcome:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Describe your change"`
4. Push to your fork and open a Pull Request.

Please keep contributions focused (small, single-purpose changes) and include clear descriptions.

## License
This project does not include a license file. If you want to make this project open source, add a LICENSE (e.g., MIT) to the repository.

## Contact
For questions or suggestions, open an issue in this repository or reach out via the repository's contact page.

Enjoy customizing EduTech Academy!
