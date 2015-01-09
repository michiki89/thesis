#
#	Makefile fuer die Erstellung von Arbeiten am IBT
#

dipl:		pdf

clean:          ; 
		rm -f *~ *.aux *.bbl *.blg *.dvi *.idx *.ilg *.ind *.lof *.log *.lot *.out *.toc


DIPLTEX = diplomarbeit.tex title.tex kapitel1.tex kapitel2.tex kapitel3.tex kapitel4.tex kapitel5.tex kapitel6.tex kapitel7.tex kapitel8.tex anhang1.tex
DIPLBIB = refbase.bib literatur.bib

DIPL =	$(DIPLTEX) $(DIPLBIB)

ps:     diplomarbeit.dvi
	dvips -o diplomarbeit.ps diplomarbeit.dvi

diplomarbeit.dvi:	$(DIPL)
		latex diplomarbeit ; bibtex diplomarbeit ; latex diplomarbeit ; latex diplomarbeit

pdf:    $(DIPL)
	pdflatex diplomarbeit ; bibtex diplomarbeit ; pdflatex diplomarbeit ; pdflatex diplomarbeit

