.PHONY: clean all

all: doc clean

doc:
	cd src && xelatex notes.tex && cd ..

clean:
	rm notes.log && cd src && rm *.aux *.bcf *.log *.out *.lua\
		*.dvi *fdb_latexmk *.fls *.toc *.pre *.ind *.ilg *.idx && cd ..
