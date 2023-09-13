.PHONY: pdf
pdf:
	@pdflatex curriculumVitae.tex

.PHONY: clean
clean:
	@rm -f curriculumVitae.aux curriculumVitae.log curriculumVitae.out \
		curriculumVitae.fdb_latexmk curriculumVitae.fls

.PHONY: publish
publish:
	@mv curriculumVitae.pdf ../edmundGoodmanCV.pdf
