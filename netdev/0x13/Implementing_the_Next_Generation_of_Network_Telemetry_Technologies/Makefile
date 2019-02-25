all:
	pdflatex int.tex
	bibtex int
	pdflatex int.tex
	pdflatex int.tex
	pdflatex int.tex

clean:
	rm -f *.pdf *.out *.log *.aux *.toc *.lot *.lof *.blg *.bbl *.ent figures/*eps-converted-to.pdf
