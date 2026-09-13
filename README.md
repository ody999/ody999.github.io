# Static website

A lightweight HTML/CSS website with no build step.

## Local preview

Run from the project directory:

```sh
python3 -m http.server 4000 --bind 127.0.0.1
```

Open http://127.0.0.1:4000. Refresh after editing; stop the server with Ctrl+C.

## Files

- `index.html`: page content.
- `styles.css`: layout and styling.
- `assets/`: images and other static assets.
- `.nojekyll`: disables Jekyll processing on GitHub Pages.
