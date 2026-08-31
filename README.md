# ariyahlabs.com

Public site for Ariyah Labs, the applied research practice of Ariyah LLC.

Single static page, no build step, no dependencies. Edit `index.html` and push;
GitHub Pages redeploys automatically.

- `index.html` — the entire site, self-contained (inline CSS, no external assets)
- `CNAME` — custom domain for GitHub Pages

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000
