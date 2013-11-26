all: main.pdf

main.pdf: *.tex main.bib
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex
  
clean:
	@echo "Deleting tmp files"
	@rm -f main.pdf *.log *.aux *.dvi *.lof *.lot *.bit *.idx *.glo *.bbl *.ilg *.toc *.blg  .*swp
