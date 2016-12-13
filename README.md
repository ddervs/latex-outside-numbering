# latex-outside-numbering

This package adds an option to the [`listings`](http://www.ctan.org/tex-archive/macros/latex/contrib/listings/ "listings CTAN link") package in LaTeX. The option added is `numbers=outside`, which numbers the lines of a block of code on the outside margin of a document (i.e. on the right hand side for odd pages, and on the left for even pages). Designed for use in document classes with the 'twoside' option enabled.

The implementation is shown in `document.tex`, which is easily compiled by executing
```
pdflatex document.tex
```
in the directory with the two files. Note sometimes it requires compiling twice to get the numbering correct.

The `BaseHTTPServer.py` file is just sample code, taken from the Python 2.7 installation.

Enjoy!
