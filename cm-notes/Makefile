
chap2:
	docker run -w /data -v `pwd`:/data -ti draftbox /usr/bin/pdflatex -interaction nonstopmode -halt-on-error -file-line-error chap2-summary.tex
	gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.5 -dNOPAUSE -dQUIET -dBATCH -dPrinted=false -sOutputFile=chap2-summary-small.pdf chap2-summary.pdf

p2.32:
	docker run -w /data -v `pwd`:/data -ti draftbox /usr/bin/pdflatex -interaction nonstopmode -halt-on-error -file-line-error p2.32.tex


clean:
	rm -f *.aux *.log *out

