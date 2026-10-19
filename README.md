[![PDFLatex](https://github.com/xiahualiu/ms-thesis/actions/workflows/build.yaml/badge.svg?branch=main)](https://github.com/xiahualiu/ms-thesis/actions/workflows/build.yaml)

# My M.S Thesis

My graduate M.S thesis at UC CEAS school archive.

## Requirement

* Latest [TeX Live](https://tug.org/texlive/) distribution (currently TeX Live 2026).

## Build

```bash
latexmk -interaction=nonstopmode -pdf main.tex
```

Python code is highlighted with the LaTeX `listings` package; no Python helper
or Pygments installation is needed to build the thesis.

## Download PDF

To build a PDF on GitHub, open **Actions → PDFLatex → Run workflow** and select
the branch to build. The workflow uses the latest TeX Live release and runs only
when manually triggered. After a successful run, download the **PDF** artifact
from the workflow run page.
