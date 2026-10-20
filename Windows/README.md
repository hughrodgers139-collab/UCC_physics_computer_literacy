# Windows

[Workshop index](../README.md)

- [Read the Windows guide](Windows.pdf)
- [Edit the LaTeX source](Windows.TEX)
- [VS Code keyboard shortcuts](VSCODE%20_keyboard-shortcuts-windows.pdf)

The guide covers Windows installation, PowerShell, paths, Python environments,
Git, LaTeX, shortcuts, and troubleshooting. These instructions use PowerShell, Command Prompt, or WSL. Python and data-analysis exercises are in the
[shared notebook](../Example_Code/Exersize.ipynb).

Shared guides: [Git and GitHub](../Git/Git.pdf) and
[LaTeX](../LaTeX/LaTeX.pdf).

From the repository root, rebuild with:

```text
latexmk -cd -pdf -interaction=nonstopmode -halt-on-error Windows/Windows.TEX
```
