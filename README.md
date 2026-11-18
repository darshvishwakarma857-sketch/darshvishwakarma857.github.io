# Darsh Anand Vishwakarma — Portfolio

A dark, futuristic personal portfolio built with plain HTML, CSS and JavaScript (no build step, no dependencies).

## Structure
```
index.html        # the whole site (HTML + CSS + JS)
assets/profile.jpg
README.md
```

## Before publishing — update these placeholders
In `index.html`, search for and replace:
- `https://linkedin.com/in/your-profile`
- `https://instagram.com/your-handle` (or delete that line)
- Project cards in the `#projects` section (replace the placeholders with real projects, GitHub and live-demo links)
- Skill list: the `S` array in the script at the bottom of `index.html`

## Run locally
Open `index.html` in a browser.

## Deploy free with GitHub Pages
1. Create a new repository on GitHub (for a personal site, name it `<your-username>.github.io`).
2. Upload these files, or from this folder run:
   ```
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo>.git
   git push -u origin main
   ```
3. In the repository go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then save.
4. Your site will be live at `https://<your-username>.github.io/` (or `/<repo>/`) within a minute or two.

## Contact form
The form opens the visitor's email app (`mailto:`). For a form that sends directly, connect a free service such as Formspree or EmailJS.
