#
# Makefile
#
# (c) 2019 Prof Dr Andreas Müller, Hochschule Rapperswil
#
all:	images ikosaeder.txt

images:	04001-W.pdf 04001-signal.pdf 04001-spektrum.pdf 07001-graph.pdf


04001-W.pdf: 04001-W.tex
	pdflatex 04001-W.tex

04001-signal.pdf: 04001-signal.tex
	pdflatex 04001-signal.tex

04001-spektrum.pdf: 04001-spektrum.tex
	pdflatex 04001-spektrum.tex

07001-graph.pdf: 07001-graph.tex
	pdflatex 07001-graph.tex

ikosaeder.txt:	ikosaeder.maxima
	maxima -q -b ikosaeder.maxima | tee ikosaeder.txt

