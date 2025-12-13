all:
	pdflatex -shell-escape main
	pdflatex -shell-escape main
	bibtex main
	bibtex main
	pdflatex -shell-escape main
	bibtex main
	pdflatex -shell-escape main

haste:
	pdflatex -shell-escape main
	open main.pdf

clean:
	rm *.aux *.bbl *.out *.log
	rm supplementary_material/*.aux supplementary_material/*.bbl supplementary_material/*.out supplementary_material/*.log
