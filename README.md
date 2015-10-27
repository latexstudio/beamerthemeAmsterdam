# beamerthemeAmsterdam
A clean and simple LaTeX beamer theme

## Installation

1. Find out where your local texmf directory is. (Mac users, read below.) Here, we use `TEXMF` to indicate that directory.
1. Copy `beamerthemeAmsterdam.sty` to `TEXMF/latex/beamer/themes/theme/`
2. Copy `beamerouterthemeamsterdam.sty` to `TEXMF/latex/beamer/themes/outer/`
3. Copy `beamercolorthemeamsterdam.sty` to `TEXMF/latex/beamer/themes/color/`

#### Note for MacTeX users

The local texmf directory can be found at `/usr/local/texlive/texmf-local`

You might want to run the following commands:

```
mkdir -p /usr/local/texlive/texmf-local/tex/latex/local/beamer/themes/theme/
mkdir -p /usr/local/texlive/texmf-local/tex/latex/local/beamer/themes/outer/
mkdir -p /usr/local/texlive/texmf-local/tex/latex/local/beamer/themes/color/
```

Copy the files to their respective directories, and then run: 

```
texhash /usr/local/texlive/texmf-local
```
