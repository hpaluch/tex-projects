

all: mujpoc.pdf

# Note: TeX must be run 2 times to correctly generate toc
mujpoc.pdf : mujpoc.tex conn.mf
	pdfcsplain $<
	pdfcsplain $<


.PHONY: clean
clean:
	-rm -f *.dvi *.pdf *.toc *.log *.*pk *.tfm
	
