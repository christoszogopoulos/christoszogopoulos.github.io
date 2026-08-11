# Christos Zogopoulos — Academic Website

Plain HTML/CSS site, no build tools required. Free to host on GitHub Pages.

## Files

- `index.html` — Home
- `research.html` — Working papers / research interests
- `teaching.html` — Teaching appointments
- `cv.html` — Embedded CV + download link
- `contact.html` — Contact details
- `assets/style.css` — All styling (colors, fonts, layout) — edit once, applies everywhere
- `assets/Christos_Zogopoulos_CV.pdf` — Your CV file

## How to publish for free (GitHub Pages)

1. Go to github.com and create a free account (if you don't have one).
2. Click "New repository". Name it `yourusername.github.io` (replace `yourusername`
   with your actual GitHub username) — this exact naming makes GitHub host it automatically.
   Set it to Public.
3. On the new repo page, click "uploading an existing file" and drag in every file
   and folder from this `website` folder (keep the `assets` folder structure intact).
4. Commit the upload.
5. Go to Settings → Pages in the repo. Under "Source", select the `main` branch
   and `/ (root)` folder, then Save.
6. Wait 1–2 minutes. Your site is live at `https://yourusername.github.io`.

## How to maintain it

- **Add a new paper:** open `research.html`, find the comment
  `ADD NEW PAPERS HERE`, copy the `<div class="paper">...</div>` block above it,
  paste a new copy below, and edit the text.
- **Add a new teaching role:** same idea in `teaching.html`, look for
  `ADD NEW TEACHING ROLES HERE`.
- **Update your CV:** replace `assets/Christos_Zogopoulos_CV.pdf` with your new
  PDF, keeping the exact same filename. No HTML edits needed.
- **Add a whole new page** (e.g. "Publications" once you have journal articles):
  duplicate any existing page, rename it (e.g. `publications.html`), edit its
  content, then add a link to it in the `<nav class="site-nav">` block near the
  top of every page (copy the same `<a href="...">` line into all pages so the
  menu stays consistent).
- **Change colors/fonts:** edit `assets/style.css` once — it applies to the
  whole site.

After editing, just re-upload the changed file(s) to GitHub (drag-and-drop on
the repo page, or use GitHub Desktop if you want a proper git workflow) — the
live site updates automatically within a minute.
