# thomassaulou.github.io

Thomas Saulou's personal blog — a static site served via GitHub Pages at
**https://thomassaulou.github.io/**.

## Structure

| File | Purpose |
|------|---------|
| `index.html` | Landing page markup |
| `styles.css` | Design tokens and layout |
| `main.js` | Small progressive enhancements |

## Local preview

It's a plain static site — open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Pushing to `main` publishes automatically through GitHub Pages (source: `main` `/`).
