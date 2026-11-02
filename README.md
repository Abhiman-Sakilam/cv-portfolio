# Abhiman Sakilam · Portfolio

Personal portfolio of Abhiman Sakilam, AI engineer building computer vision, VLM and LLM systems that run in production.

**Live site:** https://abhiman-sakilam.github.io/cv-portfolio/

A single static page (`index.html`) with inline CSS and JavaScript. No build step or dependencies; fonts load from Google Fonts.

| File | Purpose |
| --- | --- |
| `index.html` | The site |
| `assets/abhiman.jpg` | Hero photo |
| `assets/abhiman-subject.webp` | Cut-out of the person in the hero photo, layered above the name for the depth effect. It must line up exactly with `abhiman.jpg`, so regenerate it if the photo changes |
| `assets/Abhiman-Sakilam-Resume.pdf` | Resume linked from the nav and hero |
| `og.jpg` | Link preview image for LinkedIn, WhatsApp and X (1200 × 630) |
| `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png` | Browser and home-screen icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

On screens at least 1200px wide, the hero, the "In production" section and the project chapters are scroll-driven sequences. Smaller screens and visitors with reduced motion get a simpler stacked layout.

To update the site, edit `index.html` and push to `main`. GitHub Pages redeploys in a minute or two.
