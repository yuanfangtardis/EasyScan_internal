.DEFAULT_GOAL := pdf

pdf:
	-pdflatex main.tex
	-bibtex main.aux
	-pdflatex main.tex
	-pdflatex main.tex
	-xdg-open main.pdf
