SOURCE=enos-slides
OPTIONS=-pdflatex=lualatex

all:
	latexmk -pdf ${OPTIONS} ${SOURCE}.tex

clean:
	latexmk -c ${SOURCE}.tex

mrproper:
	latexmk -C ${SOURCE}.tex
	rm -rf ${SOURCE}.bbl
	rm -rf ${SOURCE}.nav
	rm -rf ${SOURCE}.vrb
	rm -rf ${SOURCE}.snm

daemon:
	latexmk -pvc -pdf ${OPTIONS} ${SOURCE}.tex

