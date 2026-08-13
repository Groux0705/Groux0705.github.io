# Groux

Live site: **https://groux0705.github.io/**

个人博客，现托管于 GitHub Pages。

Older posts were copied from a private source-of-truth repo (`Groux0705/blog`). New writing lives here.

Theme: [PaperMod](https://github.com/adityatelange/hugo-PaperMod) via Hugo modules.

## Deploy

GitHub Pages currently publishes the prebuilt site from `main` `/docs` (Hugo output). A custom Hugo Actions workflow is saved as `.github/pages.yml.example` — the GitHub CLI token used to create this repo lacked the `workflow` scope, so `.github/workflows/*.yml` could not be pushed. After granting that scope, move the example file to `.github/workflows/pages.yml` and switch Pages to “GitHub Actions”.
