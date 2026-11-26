# NEXAproject

Four static websites for NEXA Solution. Each one is plain HTML: no build step needed.

| Folder | What it is | View online (GitHub Pages) |
| --- | --- | --- |
| `nexa-solution/` | Main website | https://lihyang2003.github.io/NEXAproject/nexa-solution/ |
| `nexa-trien-lam/` | Exhibition landing page | https://lihyang2003.github.io/NEXAproject/nexa-trien-lam/ |
| `nexa-b2b/` | B2B marketing landing page | https://lihyang2003.github.io/NEXAproject/nexa-b2b/ |
| `nexa-seo/` | SEO, AIO, GEO service landing page | https://lihyang2003.github.io/NEXAproject/nexa-seo/ |

The landing pages' header links point to `../nexa-solution/` (and to each other), so the sites link to each other inside this repo.

## Run locally

```bash
npx http-server . -p 8080
```

Then open http://localhost:8080/.
