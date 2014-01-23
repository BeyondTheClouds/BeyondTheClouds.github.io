all: main.pdf

main.pdf: *.tex main.bib
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex
  
rr: *.tex main.bib
	pdflatex RR-XXXX.tex
	bibtex RR-XXXX
	pdflatex RR-XXXX.tex
	pdflatex RR-XXXX.tex
         
clean:
	@echo "Deleting tmp files"
	@rm -f main.pdf rr.pdf *.log *.aux *.dvi *.lof *.lot *.bit *.idx *.glo *.bbl *.ilg *.toc *.blg  .*swp
