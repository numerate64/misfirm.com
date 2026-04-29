# misfirm.com

Static one-page site for MIS Solutions.

## Files

- `index.html` — main site markup
- `styles.css` — site styling
- `script.js` — tiny footer year helper

## Local preview

From this folder:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## GitHub Pages publishing

1. Create a repo named `misfirm.com` under `github.com/numerate64`.
2. Push this directory as the repo contents.
3. In GitHub Pages settings, serve from the default branch root.
4. Point the custom domain to `misfirm.com`.
5. Add a `CNAME` file containing `misfirm.com` if you want GitHub Pages to manage the custom domain cleanly.
