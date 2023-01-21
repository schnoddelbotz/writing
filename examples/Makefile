
all: va.pdf

va.pdf: va.tex
	# twice for TOC - Table of contents - Inhaltsverzeichnis
	pdflatex va && biber va && pdflatex va

clean:
	rm -f va.{aux,bcf,log,out,pdf,run.xml,toc,upa,upb,bbl,blg}
