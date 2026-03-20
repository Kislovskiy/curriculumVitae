# curriculumVitae

[![CV](https://img.shields.io/badge/View%20CV-GitHub%20Pages-blue?logo=github)](https://kislovskiy.github.io/curriculumVitae/)

My CV as a software engineer, written in LaTeX.

No LaTeX installation needed — compilation runs inside [Docker](https://www.docker.com/).

## Compile

```bash
docker run --rm \
  -v "$(pwd):/workdir" \
  -w /workdir \
  texlive/texlive:latest \
  pdflatex -pdf cv.tex
```

Output: `cv.pdf`
