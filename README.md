# NEXAproject

Two static websites for NEXA Solution. Each one is plain HTML: no build step needed.

| Folder | What it is | View online (GitHub Pages) |
| --- | --- | --- |
| `nexa-solution/` | Main website | https://lihyang2003.github.io/NEXAproject/nexa-solution/ |
| `nexa-trien-lam/` | Exhibition landing page | https://lihyang2003.github.io/NEXAproject/nexa-trien-lam/ |

The landing page's header links point to `../nexa-solution/`, so the two sites link to each other inside this repo.

## Run locally

```bash
npx http-server . -p 8080
```

Then open http://localhost:8080/.
