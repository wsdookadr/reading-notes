pdf:
	docker run -w /data -v `pwd`:/data -ti draftbox:latest /usr/bin/latexmk -pdflatex='pdflatex -file-line-error -synctex=0' -pdflatex -interaction=nonstopmode

shell:
	docker run -w /data -v `pwd`:/data -ti draftbox:latest bash

clean:
	rm -f *.pdf *.aux *.log *.out *.synctex.gz
