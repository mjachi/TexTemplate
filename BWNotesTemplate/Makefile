.PHONY: clean all

all: doc clean

doc:
	cd src && latexmk notes.tex && cd ..

clean:
	cd src && rm *.aux *.bcf *.log *.out *.lua *.toc *.pre *.ind *.ilg *.idx && cd ..
