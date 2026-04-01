# Deepak T Portfolio

This repository contains a single-page, recruiter-focused portfolio website built from provided resume content.

## Project Structure

- `index.html` – Main page markup and content sections.
- `styles.css` – Responsive styles, layout, and visual theme.
- `script.js` – Mobile navigation toggle and scroll reveal behavior.
- `assets/Deepak-T-Resume.txt` – Downloadable plain-text resume.

## Build Process Followed

1. Gathered and used only the provided resume details.
2. Structured the portfolio into clear recruiter-friendly sections:
   - Hero
   - About
   - Skills
   - Projects
   - Experience
   - Education
   - Certifications
   - Achievements
   - Contact
3. Implemented a clean, minimal, and responsive UI using plain HTML/CSS.
4. Added lightweight JavaScript for interaction and reveal animations.
5. Ensured the resume download points to a real file in `assets/`.
6. Kept the output static-host friendly for GitHub Pages/Netlify/Vercel.

## Run Locally

Because this is a static site, you can run it with any local web server.

Example with Python:

```bash
python -m http.server 8000
```

Then open:

- `http://127.0.0.1:8000/`

## Deployment

This project can be deployed directly on:

- GitHub Pages
- Netlify
- Vercel

No build step is required.
