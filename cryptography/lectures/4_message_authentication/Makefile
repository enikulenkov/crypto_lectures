all: clean pdf 

pdf:
	for i in 0 ; do \
	  pdflatex message_auth.tex ; \
	done

clean:
	rm -f *.log
	rm -f *.aux
	rm -f *.pdf
	rm -f *.out
