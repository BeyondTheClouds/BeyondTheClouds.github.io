all: short-proposal.pdf

short-proposal.pdf: *.tex short-proposal.bib
	pdflatex short-proposal.tex
	bibtex short-proposal
	pdflatex short-proposal.tex
	pdflatex short-proposal.tex
         
clean:
	@echo "Deleting tmp files"
	@rm -f short-proposal.pdf *.log *.aux *.dvi *.lof *.lot *.bit *.idx *.glo *.bbl *.ilg *.toc *.blg  .*swp
