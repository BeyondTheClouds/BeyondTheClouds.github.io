all: main.tex main.bib
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex

clean:
	@rm -f *.aux
	@rm -f *.idx
	@rm -f *.log
	@rm -f *.toc
	@rm -f *.bbl
	@rm -f *.tdo

cleanall: clean
	@rm -f main.pdf
