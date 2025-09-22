# Actions for Data Scientists — Starter

**Start here:** Lint your Python files (and notebooks), then automatically render a Quarto site via GitHub Pages. Optional: run a cross‑OS compatibility report and a tiny pytest.

## Quick start
1. Push this repo to GitHub.
2. Open **Actions** and watch **Lint** start. Fix any issues so it turns green.
3. Edit `index.qmd`, Copy `samples/quarto-pages.yml` to `.github/workflows/quarto-pages.yml`, and then push to GitHub → **Quarto Publish** will render and deploy your site (see run URL).
4. (Optional) Copy `samples/compat.yml` to `.github/workflows/compat.yml`, push to GitHub.
5. (Optional) Copy `samples/ci_pytest.yml` to `.github/workflows/ci_pytest.yml` and commit to enable a simple test.
