# Mathematical Writing

This repository contains my personal notes on mathematical writing, formatted in LaTeX.

## Structure

* `main.tex`: The root LaTeX file.
* `.github/workflows/`: CI/CD configurations for auto-compilation and spell checking.

## How to Build Locally

Ensure you have `latexmk` and a TeX distribution (TeXLive/MacTeX) installed.

Run the following command in the root directory

```bash
latexmk -pdf main.tex
latexmk -xelatex main.tex
```
