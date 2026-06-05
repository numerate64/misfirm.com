# misfirm.com

Static one-page site for MIS Solutions.

The current mockup positions MIS Solutions around:

- AWS and Azure migration, optimization, and hybrid integration
- Microsoft 365 governance without naming the underlying governance platform
- Anthropic Claude services readiness and delivery practice development

## Files

- `index.html` - main site markup
- `styles.css` - site styling
- `script.js` - footer year helper
- `CNAME` - GitHub Pages custom domain value for `misfirm.com`

## Local Preview

From this folder:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## GitHub Pages Publishing

1. Use the repo `github.com/numerate64/misfirm.com`.
2. Push this directory to the `main` branch.
3. In GitHub Pages settings, serve from the default branch root.
4. Keep the `CNAME` file containing `misfirm.com`.
5. Point DNS for `misfirm.com` to GitHub Pages.

Recommended apex records:

```text
A     @     185.199.108.153
A     @     185.199.109.153
A     @     185.199.110.153
A     @     185.199.111.153
AAAA  @     2606:50c0:8000::153
AAAA  @     2606:50c0:8001::153
AAAA  @     2606:50c0:8002::153
AAAA  @     2606:50c0:8003::153
```
