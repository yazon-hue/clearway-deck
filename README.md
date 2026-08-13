# Clearway — pitch deck

A single-file, swipeable pitch deck. Navigate with arrow keys, scroll/swipe, or the on-screen arrows and dots.

## Deploy to GitHub Pages

1. Create a new repo (e.g. `clearway-pitch`) and add this `index.html` to the root.
2. Push to GitHub:
   ```
   git init
   git add index.html README.md
   git commit -m "Add pitch deck"
   git branch -M main
   git remote add origin https://github.com/<your-username>/clearway-pitch.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**, set **Source** to the `main` branch and `/ (root)` folder, then save.
4. Your deck will be live at `https://<your-username>.github.io/clearway-pitch/` within a minute or two.

## Editing content

All slide content lives directly in the `<section class="slide">` blocks in `index.html` — edit the text in place, no build step required. Placeholder figures (funding ask, unit economics, founder contact) are marked to be replaced with real numbers before pitching.
