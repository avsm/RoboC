all: exercises.pdf login.pdf manual.pdf projects.pdf
	
%.pdf: %.tex
	pdflatex $<
	pdflatex $<
	pdflatex $<

	rm -f *.out *.aux *.toc *.log
clean:
	rm -f *.pdf *.out *.aux *.toc *.log
