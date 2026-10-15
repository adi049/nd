# Hotel ND Manor

Static website source for Hotel ND Manor, Dehradun.

## Enable live hosting

This repository includes a GitHub Actions workflow at `.github/workflows/pages.yml`. The connected GitHub App cannot enable GitHub Pages for the repository because GitHub returns `Resource not accessible by integration` for the Pages settings API.

Open **Settings → Pages** in this repository and set **Build and deployment → Source** to **GitHub Actions**. Then rerun the workflow in the Actions tab. The expected site URL is `https://adi049.github.io/nd/` after Pages is enabled and a deployment succeeds.
