all: clean presentation

pdf:
	for i in 0 ; do \
	  pdflatex stream_ciphers.tex ; \
	done

presentation:
	for i in 0 ; do \
	  pdflatex "\def\pres{}\input{stream_ciphers.tex}"  ; \
	done

clean:
	rm -f *.log
	rm -f *.aux
	rm -f *.pdf
	rm -f *.out
