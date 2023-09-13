.PHONY: pdf
pdf:
	@xelatex resume.tex

.PHONY: clean
clean:
	@rm -f resume.aux resume.fdb_latexmk resume.fls resume.log resume.out \
		resume.synctex.gz resume.xdv

.PHONY: publish
publish:
	@mv resume.pdf ../edmundGoodmanCV.pdf
