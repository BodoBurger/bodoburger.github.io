# bodoburger.github.io

Personal CV website for Bodo Burger, published with GitHub Pages.

The site is a static HTML/CSS project. There is no build step and no backend runtime.

## Files

- `index.html` - main CV page
- `css/style.css` - active stylesheet used by `index.html`
- `images/` - profile photo, background image, and small visual assets
- `social.html` - reference/template page for social button styles
- `css/style_v*.css` - older stylesheet variants kept for comparison

## Local Preview

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

Push changes to the branch configured for GitHub Pages deployment. GitHub Pages/GitHub Actions can take a short moment to update the public site after a successful deployment.

## Updating Links

The social buttons are defined near the top of `index.html` in the `.social-buttons` block. Update the `href` values there when profile URLs change.
