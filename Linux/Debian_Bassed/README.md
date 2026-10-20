# Debian and Ubuntu

[Workshop index](../../README.md)

- [Read the Linux guide](Linux.pdf)
- [Edit the LaTeX source](Linux.TEX)
- [VS Code keyboard shortcuts](VSCODE%20_keyboard-shortcuts-linux.pdf)

The guide covers Debian/Ubuntu installation, Bash, paths, Python environments,
Git, LaTeX, shortcuts, and troubleshooting. Python and data-analysis exercises
are in the [shared notebook](../../Example_Code/Exersize.ipynb).

Shared guides: [Git and GitHub](../../Git/Git.pdf) and
[LaTeX](../../LaTeX/LaTeX.pdf).

From the repository root, rebuild with:

```text
latexmk -cd -pdf -interaction=nonstopmode -halt-on-error Linux/Debian_Bassed/Linux.TEX
```
