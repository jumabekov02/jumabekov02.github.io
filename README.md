# jumabekov02.github.io

Personal portfolio website — built with plain HTML, CSS, and JavaScript. Hosted on GitHub Pages.

**Live site:** https://jumabekov02.github.io

## Structure

```
.
├── index.html      # Page markup
├── styles.css      # Styling (dark theme)
├── script.js       # Mobile nav, scroll effects, fade-in animations
├── assets/         # Profile photo and other images
└── README.md
```

## Local preview

Just open `index.html` in a browser. No build step required.

For live reload during edits, you can use any static server, e.g.:

```bash
# Python
python -m http.server 8000

# Node (npx)
npx serve
```

Then visit http://localhost:8000.

## Customizing

- **Bio:** edit the placeholder paragraphs in the About section in `index.html` (look for text in `<em>` tags).
- **Photo:** drop `profile.jpg` into `assets/` and replace the `.image-placeholder` block with `<img src="assets/profile.jpg" alt="Murad Zhumabekov">`.
- **Projects:** edit the `<article class="project-card">` blocks in the Projects section.
- **Colors:** tweak the CSS variables at the top of `styles.css` (`--accent`, `--bg`, etc.).
