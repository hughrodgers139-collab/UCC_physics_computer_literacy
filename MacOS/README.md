# macOS

[Workshop index](../README.md)

- [Read the macOS guide](MaxOS.pdf)
- [Edit the LaTeX source](MaxOS.TEX)

The guide covers macOS installation, Finder, Terminal/zsh, paths, Python
environments, Git, LaTeX, shortcuts, and troubleshooting. Python and
data-analysis exercises are in the
[shared notebook](../Example_Code/Exersize.ipynb). The original `MaxOS`
filename is retained for compatibility.

Shared guides: [Git and GitHub](../Git/Git.pdf) and
[LaTeX](../LaTeX/LaTeX.pdf).

From the repository root, rebuild with:

```text
latexmk -cd -pdf -interaction=nonstopmode -halt-on-error MacOS/MaxOS.TEX
```
