# Darshak Alapati — Portfolio

Personal portfolio website for **Darshak Alapati**, Data Scientist & Software Engineer.
Live at: https://darshakalapati.com

A single-file, dependency-light site (`index.html`) with a Three.js 3D background,
animated hero, and responsive layout. No build step required.

## Local preview
Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy
This repo is set up for **continuous deployment**. Any push to the `main`
branch automatically rebuilds and publishes the live site.

- Hosting: Netlify (see `netlify.toml`)
- Alternative: GitHub Pages workflow in `.github/workflows/deploy.yml`

## Making changes
1. Edit `index.html`.
2. Commit and push:
   ```bash
   git add .
   git commit -m "Update portfolio content"
   git push
   ```
3. The live site updates automatically within ~1 minute.

## Structure
```
.
├── index.html                 # the entire site
├── netlify.toml               # Netlify config (custom domain + headers)
├── .github/workflows/deploy.yml  # optional GitHub Pages auto-deploy
├── CNAME                      # custom domain for GitHub Pages
└── README.md
```
