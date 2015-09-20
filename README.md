# latex-outside-numbering

This hack adds an option to the listings package in LaTeX. The option added is `numbers=outside`, which numbers the lines of a block of code on the outside margin of a document (i.e. on the right hand side for odd pages, and on the left for even pages). Designed for use in document classes with the 'twoside' option enabled. 

The implementation is shown in `document.tex`, which is easily compiled with
```
pdflatex document.tex
```
in the directory with the two files. Note sometimes it requires compiling twice to get the numbering correct.

The `BaseHTTPServer.py` file is just sample code, taken from the Python 2.7 installation.

Enjoy!
