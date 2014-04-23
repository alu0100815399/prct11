all:
	latex Pi.tex
	latex Pi.tex
	dvips -o Pi.ps Pi.dvi
	ps2pdf -sPAPERSIZE=a4 -DMaxSubsetPct=100 -dCompatibilityLevel=1.2 -dSubsetFonts=true -dEmbedAllFonts=true Pi.ps Pi.pdf

clean:
	rm -f *.toc *.ps *.log *.lof *.lot *.dvi *.aux *.blg *.bbl *.*~ tex/*.*~
