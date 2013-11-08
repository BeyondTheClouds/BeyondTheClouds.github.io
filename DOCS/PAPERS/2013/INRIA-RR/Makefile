all: rr

rr: *.tex main.bib
	pdflatex RR-XXXX.tex
	bibtex RR-XXXX
	pdflatex RR-XXXX.tex
	pdflatex RR-XXXX.tex
         
clean:
	@echo "Deleting tmp files"
	@rm -f rr.pdf *.log *.aux *.dvi *.lof *.lot *.bit *.idx *.glo *.bbl *.ilg *.toc *.blg  .*swp
