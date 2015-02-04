MAIN=main

all: clean pdf open

pdf: ${MAIN}.tex ${MAIN}.bib
	latexmk --pdf ${MAIN}.tex

clean:
	@echo "Deleting tmp files"
	latexmk -C
	@rm -f *.brf *.glg *.glo *.gls *.maf *.mtc*

open:
	@open ${MAIN}.pdf
