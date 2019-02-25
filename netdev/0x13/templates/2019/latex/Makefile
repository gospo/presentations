all:
	pdflatex usenix2019.tex
	bibtex usenix2019
	pdflatex usenix2019.tex
	pdflatex usenix2019.tex
	pdflatex usenix2019.tex

clean:
	rm -f *.pdf *.out *.log *.aux *.toc *.lot *.lof *.blg *.bbl *.ent figures/*eps-converted-to.pdf
