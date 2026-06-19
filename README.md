# Ridgeline Crane

Teaser hero header for **Ridgeline Crane** — locally owned crane & rigging service, Park City / Summit County, Utah.

Static single-page header: fullscreen background video, gold-accented branding, responsive nav with a mobile dropdown.

## Structure

```
index.html        # the page (self-contained — all CSS/JS inline)
assets/
  usethis.mp4     # background hero video
  logo.webp       # Ridgeline Crane logo
  poster.png      # video poster / fallback frame
.nojekyll         # tell GitHub Pages to serve assets/ untouched
```

## View locally

Open `index.html` directly, or serve it (recommended so the video autoplays):

```bash
python -m http.server
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)

Repo **Settings → Pages → Build and deployment → Deploy from a branch**, branch `main`, folder `/ (root)`.

---
made by [kellan](https://getkellan.com) ;)
