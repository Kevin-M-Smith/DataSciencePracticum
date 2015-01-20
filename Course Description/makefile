MD_FILES  = $(wildcard *.md)
HTML_FILES = $(patsubst %.md, %.html, $(MD_FILES))
PDF_FILES  = $(patsubst %.md, %.pdf, $(MD_FILES))

html: $(HTML_FILES)
pdf: $(PDF_FILES)
all: html pdf

%.pdf : %.md
	pandoc $< -o $@
	
%.html : %.md
	pandoc $< -o $@

clean:
	rm $(HTML_FILES)
	rm $(PDF_FILES)
	
rebuild: clean all