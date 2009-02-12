all: intro.ps intro.pdf

intro.ps: intro.tex
	latex intro
	dvips intro

intro.pdf: intro.ps
	ps2pdf intro.ps