# Notes on node wrappers for LaTeX:

`gammalatex` seems to be our winner.

## gammalatex
Automatically reruns pdflatex if necessary to resolve references, etc.

https://github.com/gammasoft/latex

## latex
Bare-bones package.  Exports a single function, which takes LaTeX source
and returns a PDF (or DVI) stream.  No re-run support?

https://github.com/mikolalysenko/node-latex

## node-pdf
Does substitution on the .tex source using mustache.  Probably not useful
for our purposes.

https://github.com/zweifisch/node-pdf

## node-tex
Super-minimal, runs `lualatex`.  Probably not right.

https://github.com/mikanda/node-tex

## pdflatex
Directly invokes pdflatex, but doesn't handle I/O redirections or re-running.

https://github.com/oschrenk/node-pdflatex

## pdflatex-ng
Slightly improved version of `pdflatex`.  Still not enough functionality.

http://github.com/jasperla/node-pdflatex-ng
