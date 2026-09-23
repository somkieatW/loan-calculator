# Home Loan Tools

Two interactive mortgage calculators in one page — split a monthly budget across two loans, or model extra payments on a single balance.

**Live:** https://somkieatw.github.io/loan-calculator/

## Tools

1. **Two-loan planner** — set a total monthly payment and split it between a main loan and a top-up, with bank minimums, rollover when one clears, and payoff charts.
2. **Single loan** — model what extra monthly payments do to one balance, with amortization schedule and interest saved.

## Tech

- Single static HTML file (no build step)
- GitHub Pages + GitHub Actions for deploy

## Local preview

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
# visit http://localhost:8080
```

## Deploy

Push to `main` — GitHub Actions deploys automatically to GitHub Pages.

First-time setup in the repo: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
