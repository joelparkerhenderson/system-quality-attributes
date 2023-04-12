TOP = $(shell git rev-parse --show-toplevel)

all: book.md book.pdf

.PHONY: clean
clean:
	@echo "make clean"
	rm -f book.md
	rm -f book.pdf

.PHONY: help
help:
	@echo "pandoc:"
	@which pandoc
	@pandoc --version
	@echo "pandoc-from-markdown-to-pdf:"
	@which pandoc-from-markdown-to-pdf

book.md:
	@echo "make book.md"
	./fold

book.pdf:
	@echo "make book.pdf"
	pandoc-from-markdown-to-pdf book.md -o book.pdf
