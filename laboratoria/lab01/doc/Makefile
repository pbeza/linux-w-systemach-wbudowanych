NAME = 'report'
PDF_FILENAME = $(NAME).pdf

.PHONY: $(PDF_FILENAME) all clean

all: $(PDF_FILENAME)

$(PDF_FILENAME):
	latexmk -pdf

clean:
	latexmk -C
