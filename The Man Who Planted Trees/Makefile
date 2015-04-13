all: interlude.pdf

interlude.pdf: interlude.tex
	texi2pdf -q -c $<

clean:
	rm -f *.aux *.log *.out *.toc *.blg *.bbl
