all: examples.pdf login.pdf manual.pdf projects.pdf
	
%.pdf: %.tex
	pdflatex $<

clean:
	rm -f *.pdf *.out *.aux *.toc *.log
