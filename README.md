# Computer literacy for physics

A beginner workshop from the UCC Physics Society. 

## Workshop material

| Topic | Guide or material |
| --- | --- |
| Windows and PowerShell | [PDF](Windows/Windows.pdf) · [LaTeX source](Windows/Windows.TEX) |
| macOS and zsh | [PDF](MacOS/MaxOS.pdf) · [LaTeX source](MacOS/MaxOS.TEX) |
| Debian/Ubuntu and Bash | [PDF](Linux/Debian_Bassed/Linux.pdf) · [LaTeX source](Linux/Debian_Bassed/Linux.TEX) |
| Git and GitHub | [PDF](Git/Git.pdf) · [LaTeX source](Git/Git.tex) |
| LaTeX reports | [PDF](LaTeX/LaTeX.pdf) · [LaTeX source](LaTeX/LaTeX.tex) |
| Python, data, and fitting | [Exercise notebook](Example_Code/Exersize.ipynb) · [synthetic data](Example_Code/linear_motion.csv) |

The OS guides cover terminal use, project folders and paths,
Python environments, editor shortcuts, and shell-profile shortcuts. They share
the same learning goals but use the tools and commands for each platform.
Exercises are in the Python notebook.


## Setup and rebuilding

Clone the repository. Create a project virtual
environment and install the packages in [requirements.txt](requirements.txt)
using your OS guide. The file describes the workshop environment; it is not a
version lockfile.


Replace the source path to build another guide. Each of the Windows, macOS,
Linux, Git, and LaTeX guides is self-contained: copy its entire source into
a new `.tex` file or an Overleaf blank project and compile it without any
other workshop files. Local builds require a TeX distribution with the
packages listed at the top of the source. Images and BibTeX files described
in the LaTeX guide are optional practice materials, not build dependencies.
In VS Code with LaTeX Workshop, open a handout's source and press
Ctrl+Alt+B to build it using the workspace recipe. Each handout declares
its own document class so the extension can identify the correct root file.
Generated `.aux`, `.log`, `.toc`, `.out`,
`.fls`, `.fdb_latexmk`, `.bbl`, and `.synctex.gz` files are build state, not
teaching sources.
