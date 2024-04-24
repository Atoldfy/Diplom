MAIN_TEX_FILE=diploma.tex
PRESENTAION_FILE=presentation.tex
PDFTEX_FLAGS=-output-format=pdf -halt-on-error

all:
	# Two calls for right construction of a table of contents and other variables
	pdflatex $(MAIN_TEX_FILE) $(PDFTEX_FLAGS) 
	pdflatex $(MAIN_TEX_FILE) $(PDFTEX_FLAGS) 
	pdflatex $(PRESENTAION_FILE) $(PDFTEX_FLAGS) 
	pdflatex $(PRESENTAION_FILE) $(PDFTEX_FLAGS) 

	rm -f *.log *.out *.toc *.nav *.snm *.aux ./src/*.aux ./pics/*.pdf

clean:
	rm -f *.log *.out *.toc *.nav *.snm *.aux ./src/*.aux ./pics/*.pdf *.pdf
