all: unified-test.pdf

%.pdf: %.tex %.bib
	xelatex $*
	biber $*
	xelatex $*
