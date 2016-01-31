# finite_diffferences_penalty
penalty method for finite differences

This is a document written using literate programming, pweave (http://mpastell.com/pweave/) for Python.

In order to extract the code, run ptangle from the command line.

ptangle "finited_differences.pnw"

In order to create the pdf document, run from within python

import pweave pweave.weave(r'finite_differences.pnw', figformat='png', doctype='texmint

followed by running LaTeX

pdflatex finite_differences.tex
