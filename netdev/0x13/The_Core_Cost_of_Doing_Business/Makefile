all:
	pdflatex corecost.tex
	bibtex corecost
	pdflatex corecost.tex
	pdflatex corecost.tex
	pdflatex corecost.tex

clean:
	rm -f *.pdf *.out *.log *.aux *.toc *.lot *.lof *.blg *.bbl *.ent figures/*eps-converted-to.pdf
