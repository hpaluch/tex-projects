
all: newspaper.pdf

newspaper.pdf : newspaper.tex
	pdfcsplain $<

.PHONY: clean
clean:
	-rm -f *.dvi *.pdf *.log

