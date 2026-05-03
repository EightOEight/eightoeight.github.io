# eightoeight.github.io

Marketing site for **EightOEight** — enterprise WordPress hosting on Kubernetes.

Served via GitHub Pages from the `main` branch root.

## Local preview

No build step. Just open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Production URL

- Primary: <https://eightoeight.io> (CNAME)
- GitHub Pages fallback: <https://eightoeight.github.io>

## Editing pricing

Pricing tier amounts are placeholders (`$X / mo`) and tagged with
`data-price="starter|growth|enterprise"` on the `.pricing__amt` span. Swap the
amounts before announcing the site publicly.

## Stack

Plain HTML + CSS, system fonts plus Inter + JetBrains Mono via Google Fonts.
No JS framework, no build pipeline — Pages serves the files directly.
