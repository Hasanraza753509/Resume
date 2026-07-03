# Hasan Raza — Resume

Personal resume site, built with plain HTML/CSS and deployed via GitHub Pages.

**Live site:** _add your GitHub Pages URL here once deployed, e.g. https://<your-username>.github.io/resume/_

## About

B.Tech student in Artificial Intelligence & Machine Learning at Delhi Technological University (Batch of 2029). IBM-certified in Machine Learning with Python, contributing to real-world AI/ML and web projects, including a mechanistic interpretability pipeline for detecting backdoors in LLMs.

## Structure

- `index.html` — the resume page
- `hasan-photo.jpg` — profile photo

Both files must stay in the same folder for the photo to load correctly.

## Deploying

```bash
git init
git add index.html hasan-photo.jpg README.md
git commit -m "Add resume site"
git branch -M main
git remote add origin https://github.com/<your-username>/resume.git
git push -u origin main
```

Then in the repo: **Settings → Pages → Source → Deploy from branch → main → /(root) → Save**

## Updating

Edit `index.html` directly, then:

```bash
git add .
git commit -m "Update resume"
git push
```

GitHub Pages redeploys automatically on every push to `main`.
