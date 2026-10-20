# LaTeX for physics

[Workshop index](../README.md)

## Shared learning guide

- [Read the LaTeX guide](LaTeX.pdf)
- [Edit the guide source](LaTeX.tex)

One guide for every OS: Overleaf and local builds, text and maths, references,
tables, figure floats, citations, report structure, and troubleshooting.
Install TeX using your OS guide. The guide source is self-contained: copy
all of it into a new `.tex` file or an Overleaf blank project and compile
without any other workshop files. The
[reference bibliography](ref.bib) and
[example image](LaTeX_meme.png) are optional practice materials.

Further online instructions: the
[Overleaf LaTeX introduction](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)
and [LaTeX Project documentation](https://www.latex-project.org/help/documentation/).

From the repository root, rebuild with:

```text
latexmk -cd -pdf -interaction=nonstopmode -halt-on-error LaTeX/LaTeX.tex
```
