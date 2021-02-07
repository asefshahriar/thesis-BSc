proposal.pdf: proposal.tex bibliography.bib \
              signature.pdf \
	      00-overview.tex \
	      01-objectives.tex \
	      02-literature.tex \
	      03-methodology.tex \
	      04-results.tex \
	      nomenclature.tex
	latexmk -pdf proposal.tex

.PHONY: clean

clean:
	rm proposal.pdf
