# (c) 2016-2017 Rahmat M. Samik-Ibrahim
# REV01 Fri Mar 10 14:10:50 WIB 2017
# REV00 Wed Mar  8 19:52:02 WIB 2017
# START Tue Jul 12 15:02:37 WIB 2016

all:	skripsi.pdf

skripsi.pdf:	skripsi.tex
	pdflatex skripsi
	pdflatex skripsi
	bibtex   skripsi
	pdflatex skripsi
	pdflatex skripsi

clean:
	rm -f *.aux *.log *.idx *.toc *.bbl *.blg
	rm -f *.lof *.lol *.lot *.out

cleanpdf:	clean
	rm -f *.pdf

