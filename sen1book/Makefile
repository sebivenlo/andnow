LATEX=pdflatex
TEXOPTIONS=
sebibook.pdf: main.tex */material.tex
	mkdir -p out
	$(LATEX) -shell-escape -jobname=sebibook -output-directory out $(TEX_OPTIONS) main.tex
#	bibtex out/sebibook
	$(LATEX) -shell-escape -jobname=sebibook -output-directory out $(TEX_OPTIONS) main.tex
	$(LATEX) -shell-escape -jobname=sebibook -output-directory out $(TEX_OPTIONS) main.tex
	cp out/sebibook.pdf .

clean:
	texclean
	rm -f sebibook.pdf

