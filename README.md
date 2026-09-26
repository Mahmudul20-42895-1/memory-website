# Public static website

This repository contains only the compiled, publicly intended website and its published media. It does not include the admin dashboard, source database, or environment secrets.

GitHub Actions deploys the `site/` directory to GitHub Pages whenever `main` is updated. To publish content changes from the admin database, export and rebuild the static site, then replace `site/` with the newly generated files and push the update.
