# IgorLimaJesus.github.io

This repository hosts the static personal site for Igor L. de Jesus. The site is served via GitHub Pages and the site files live at the repository root (index.html).

Deployment is automated with a GitHub Actions workflow at `.github/workflows/pages.yml` which publishes the repository root to GitHub Pages whenever the `main` branch receives a push.

Next steps / notes:
- If you want a custom domain, add a `CNAME` file at the repository root containing your domain (for example `igordejesus.dev`) and configure DNS A/ALIAS records to point to GitHub Pages.
- You can also configure the Pages source and enforce HTTPS via the repository Settings → Pages after the first successful deployment.
- The workflow uses the repository root; if you later add a build step (e.g., bundling), update the workflow's build step and artifact path.

If you want, I can also add a `CNAME` file or adjust the workflow to publish from a `build/` folder.
