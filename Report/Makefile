all: tex bib
tex: 
	pdflatex --shell-escape -halt-on-error -output-directory pdf src/project.tex
bib:
	bibtex pdf/project
clean:
	rm -rf pdf/*.out pdf/*.log pdf/*.aux
