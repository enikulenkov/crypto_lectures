all: clean pdf 

pdf:
	for i in 0 ; do \
	  pdflatex block_ciphers.tex ; \
	done

clean:
	rm -f *.log
	rm -f *.aux
	rm -f *.pdf
	rm -f *.out
