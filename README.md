# CV — Artem Kislovskiy

[![View CV](https://img.shields.io/badge/View%20CV-GitHub%20Pages-blue?logo=github)](https://kislovskiy.github.io/curriculumVitae/)

LaTeX CV, auto-compiled and published to GitHub Pages on every push. No local LaTeX needed.

## Build locally

Requires [Docker](https://www.docker.com/).

```bash
docker run --rm \
  -v "$(pwd):/workdir" \
  -w /workdir \
  texlive/texlive:latest \
  pdflatex -jobname=cv_kislovskiy cv.tex
```

Output: `cv_kislovskiy.pdf`

## Use as a template

Fork the repo, edit `cv.tex`, push — the PDF deploys automatically.
Enable GitHub Pages (Settings → Pages → Source: GitHub Actions) on first use.
