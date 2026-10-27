# Team T175 — Spatial Hypothesis Generator

Team site for QUT IFB399 Capstone, Project P953 (OreFox AI).

## Add the team photos

Create an `images` folder next to `index.html` and add one photo per person, named exactly:

```
images/simon.jpg
images/kayne.jpg
images/jasmine.jpg
images/lewis.jpg
images/mark.jpg
```

Portrait (4:5) photos look best. Until a photo is added, the card shows the person's initials.

To add LinkedIn links for Lewis or Mark, open `index.html`, find their card, replace `href="#" onclick="return false"` with `href="https://www.linkedin.com/in/..." target="_blank" rel="noopener"`, and copy the `li-badge` block from one of the other cards.

## Host it on GitHub Pages

1. Create a new public repository on GitHub (e.g. `t175-shg`).
2. Upload `index.html`, `README.md` and the `images` folder (Add file → Upload files → Commit).
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/t175-shg/`.
