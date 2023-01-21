
SOURCES := va.tex va-template.tex va-bibliography.bib

# the first target in this makefile will be default.
# that is just calling "make" without arguments will
# build all the dependencies of the target arbitrarily
# called "all".
all: va.pdf

# here, we tell make: Build va.pdf if any of $SOURCES is newer
# than the pdf (file timestamp). Clear? It only NEEDS to
# recompile if you CHANGED something. That's impact of $(SOURCES) here
va.pdf: $(SOURCES)
	# twice for TOC - Table of contents - Inhaltsverzeichnis; don't ask pls
	pdflatex va && biber va && pdflatex va && pdflatex va

# by convention a Makefile's clean target removes any build artefacts
clean:
	rm -f va.{aux,bcf,log,out,pdf,run.xml,toc,upa,upb,bbl,blg,lof}
